# Research Creation Network

Static **D3 v7** force-directed graph: **`index.html`** loads **`apps.json`** (tags + nodes). Serve the folder over HTTP so `fetch("apps.json")` succeeds (for example `npx serve .` or any static server).

---

## Tags

| id | name |
|----|------|
| `video-app` | VIDEO_APP |
| `embodied-interaction` | Embodied_Interaction |
| `ai-realtime` | Real time AI |
| `llm` | LLM |

---

## All nodes

Data lives in **`apps.json`**. Optional **`shortName`** is what the graph draws when set; **`name`** is the full label (e.g. tooltips). **`hubAll`** hubs link broadly; **`linkOnly`** / **`linkTo`** restrict custom edges.

### VIDEO_APP

| id | name | shortName | url |
|----|------|-----------|-----|
| `alwatchedover-machines` | All Watched Over by Machines of Loving Grace | All Watched Over… | https://marlonbarrios.github.io/alwatchedoverbymachinesoflovinggrace/ |
| `we-came-to-rule` | We Came to Rule | — | https://marlonbarrios.github.io/we_came_to_rule/ |
| `she-has-good-genes` | She Has Good Genes | — | https://marlonbarrios.github.io/she_has_good_genes/ |
| `god-mode-palantir` | God Mode (Palantir) | — | https://marlonbarrios.github.io/god_mode_palantir/ |
| `barely-there` | Barely There | — | https://marlonbarrios.github.io/barely_there/ |

### Embodied_Interaction

| id | name | url |
|----|------|-----|
| `canonical01` | Canonical01 | https://marlonbarrios.github.io/canonical01/ |
| `what-is-hand` | What is Hand | https://marlonbarrios.github.io/ahandisfourrelationships/ |
| `pulling-molecules` | Pulling Molecules | https://marlonbarrios.github.io/pulling-molecules/ |
| `cyberblue` | Cyberblue | https://marlonbarrios.github.io/cyberblue/ |
| `extraordinary-alien2` | Extraordinary Alien 2 | https://marlonbarrios.github.io/extraordinary_alien2/ |
| `instrumental-proximities` | Instrumental Proximities | https://marlonbarrios.github.io/instrumentalproximities/ |
| `body-proximities` | Body Proximities | https://marlonbarrios.github.io/body_proximities/ |
| `impossible-simplicity` | Impossible Simplicity | https://marlonbarrios.github.io/impossiblesimplicity/ |

### Real time AI

| id | name | shortName | url |
|----|------|-----------|-----|
| `bauhaus-time-travelers` | Bauhaus Time Travelers Daydream | Bauhaus Time Travelers | https://bauhaus-time-travelers-daydream.vercel.app/ |
| `looking-mr-parker` | Looking for Mr. Parker | — | https://lookingformrparker.vercel.app/ |

### LLM

| id | name | url |
|----|------|-----|
| `machine-forgetting` | Machine Forgetting | https://machine-forgetting-textvoice-gestur.vercel.app/ |
| `i-am-not-saying` | I Am Not Saying | https://i-am-not-saying.vercel.app/ |
| `alan-ai` | Alan-AI | https://alan-ai-one.vercel.app/ |
| `semantic-tensegrities` | Semantic Tensegrities | https://semantic-tensegrities.vercel.app/ |
| `elinmigrante` | El Inmigrante | https://elinmigrante.vercel.app/ |
| `decolonial-ai` | Decolonial AI | https://pangeaia-2.vercel.app/?agentConfig=Pangea_IA |
| `realtimetransformer` | RealTime Transformer | https://realtimetransformer-r267.vercel.app/ |

### No tag (playlist, album, portfolio, hubs, former Creative Code projects)

| id | name | shortName | notes | url |
|----|------|-----------|-------|-----|
| `dark-enlightenment-rave-playlist` | Music Videos for Dark Enlightenment Rave | Dark Enlightenment Rave | `linkOnly`; links only to **unstable landscapes** | https://www.youtube.com/watch?v=gTnYNPA-55o&list=PLC2ijZ2U-avi_CB1NQFV6og2eg7ZTpWo3 |
| `digressions-latent-space-album` | Digressions in Latent Space (The Music Album) | Digressions in Latent Space | Bandcamp album | https://marlonbarriossolano.bandcamp.com/album/digressions-in-latent-space |
| `my-house-your-house` | My House is Your House | — | — | https://marlonbarrios.github.io/detroit/ |
| `time-instances` | Time Instances | — | — | https://marlonbarrios.github.io/time_instances/ |
| `brainfuck-swarm` | BrainFuck Swarm | — | — | https://marlonbarrios.github.io/brainfuck_swarm/ |
| `tangerine-dreams` | Tangerine Dreams | — | — | https://marlonbarrios.github.io/tangerine_dreams2/ |
| `pseudo-ouroboros` | Pseudo Ouroboros: The Genesis of Self Interest in Gradient Descent | Pseudo Ouroboros | — | https://marlonbarrios.github.io/pseudo_ouroboros/ |
| `tonguezap` | TongueZap: The Hungry Chameleon Game | TongueZap | — | https://marlonbarrios.github.io/tonguezap/ |
| `proteans-video` | Proteans | — | — | https://www.youtube.com/watch?v=iYiMgqiLDyU&t=122s |
| `proteus-temporal` | Proteus: Trns Temporal Dating Portal | Proteus | `linkTo` → LLM tag | https://proteus-umber.vercel.app/ |
| `rabbitholes-podcast` | rabbitHoles: Recursive Pathways to the Edges of Material Knowing and Back Speculative Podcast | rabbit holes | — | https://marlonbarrios.github.io/rabbitholes/ |
| `my-portfolio` | My Portfolio | — | `linkOnly`; links only to hubs below | https://marlonbarrios.github.io/ |
| `press-and-writings` | Press and Writings | — | `hubAll` | https://marlonbarrios.github.io/#recent-interviews-press-and-writings |
| `born-in-latent-space` | born in latent space | — | `hubAll` | https://marlonbarrios.github.io/born_in_latent_space/ |
| `unstable-landscapes` | unstable landscapes | — | `hubAll` | https://marlonbarrios.github.io/unstablelandscape/ |

---

## Summary

- **4** tags  
- **37** nodes (22 under a tag + 15 without `tagId`)
