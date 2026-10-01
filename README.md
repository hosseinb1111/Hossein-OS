# HOSSEIN OS

> **A personal portfolio that behaves like a desktop operating system.**
>
> Explore projects, labs, experiments, tools, and developer notes by interacting with the system itself.

[![HTML](https://img.shields.io/badge/HTML-standalone-E34F26?logo=html5&logoColor=white)](#)
[![CSS](https://img.shields.io/badge/CSS-custom-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E?logo=javascript&logoColor=111)](#)
[![Responsive](https://img.shields.io/badge/UI-responsive-22c55e)](#mobile)

**HOSSEIN OS** is the interactive portfolio environment of **Hossein Seyed Bagheri**, a Computer Engineering student and developer interested in practical software across **web development, AI applications, Cloudflare edge systems, realtime applications, APIs, networking, and experimentation**.

The idea is simple:

```text
Don't just read the portfolio.
Use it.
```

---

## ✦ Why this exists

Most developer portfolios are pages of cards and links.

HOSSEIN OS takes a different approach: the **portfolio itself becomes a software project**.

You boot the environment, open applications, inspect projects, browse a fictional filesystem, run terminal commands, switch themes, inspect public GitHub data, and jump into the real projects behind the interface.

The desktop metaphor is not meant to hide the work behind decoration. It is meant to make the work **discoverable through interaction**.

---

## ⚡ What you can do

| Application | Purpose |
|---|---|
| `System Information` | Identity, education, technical direction and current focus |
| `Projects` | Browse the main project catalog and inspect individual work |
| `AI Lab` | Explore recurring AI projects, APIs, search, memory and automation themes |
| `Edge Lab` | Explore Cloudflare Workers, KV, Durable Objects, WebSockets and serverless patterns |
| `Realtime Lab` | Explore messaging, rooms, synchronization and realtime UI concepts |
| `Network Monitor` | Learn how the Ping Monitor measures browser-side HTTPS timing |
| `File Explorer` | Navigate a fictional portfolio filesystem mapped to real work |
| `Experiments` | Smaller experiments, games, utilities and UI projects |
| `Terminal` | Execute portfolio-focused commands inside the browser |
| `GitHub` | Load public GitHub profile/repository information dynamically |
| `Portfolio / Web` | Visit the public English and Persian portfolio surfaces |
| `Settings` | Theme, motion and language controls |
| `Contact` | Public contact channels |
| `Project Timeline` | Qualitative progression without invented dates |
| `System Log` | Aesthetic developer-style logs, explicitly not production telemetry |
| `README Viewer` | Built-in explanation of the OS itself |

---

## 🧭 Start here

The first interaction is intentional.

```text
HOSSEIN OS

[ OK ] Interface
[ OK ] Portfolio
[ OK ] Projects
[ OK ] AI systems
[ OK ] Realtime systems
[ OK ] Edge systems
[ OK ] Experiments

Loading user environment...

Welcome.
```

Once the desktop appears, open **Projects** first.

From there, the rest of the system acts like a map of the developer behind it.

---

## 🧠 Project map

### Flagship / core work

#### System AI

**AI workspace** for conversations and related AI application features.

Documented areas represented in the portfolio include:

- AI conversations
- streaming responses
- long-term memory
- web search
- image support
- conversation management
- exports
- English / Persian support
- authentication
- per-user storage
- rate limiting

**Live:** https://ai.hossein.my.id/

**Source:** https://github.com/hosseinb1111/cloudflare-based-AI

---

#### WireChat

Realtime communication project centered around:

- WebSockets
- Cloudflare Durable Objects
- room-based communication
- synchronization
- profiles
- themes
- lightweight realtime architecture

**Live:** https://wirechat.hossein.my.id/

---

#### Live Messenger

Realtime messaging experience with documented concepts including:

- messaging
- replies
- reactions
- profiles
- live application state
- responsive interface behavior

**Live:** https://chat.hossein.my.id/

---

#### File to Link

A serverless file-sharing tool built around a **Cloudflare Worker + KV** architecture.

Documented capabilities include:

- multi-file upload
- batch sharing
- shareable links
- individual file links
- file preview
- raw viewing
- direct download
- expiry settings
- Unicode filename support
- CORS
- automatic expiration

The repository documents an **18 MB per-file limit** and explains why **R2 becomes more appropriate for larger files or heavier workloads**.

```text
Browser
   │
   ▼
Cloudflare Worker
   │
   ▼
   KV
   │
   ▼
Temporary file access
```

**Live:** https://filetolink.hossein.my.id/

**Source:** https://github.com/hosseinb1111/file-to-link

---

### Network

#### Ping Monitor

A browser-side network measurement project.

It is important to understand what it **does not** claim to be:

> It is not an OS-level ICMP ping utility.

Browsers do not expose ordinary OS-level ICMP socket access to application JavaScript, so the project measures **HTTPS fetch timing from the browser**.

The interface reports documented measures such as:

- latency
- median
- average
- best / worst
- jitter
- success rate
- status classification
- configurable concurrency
- multiple services

The project also emphasizes browser constraints, CORS behavior, and the fact that the measurements describe client-side HTTP timing rather than raw ICMP network latency.

**Live Worker:** https://pinging.ai09.workers.dev/

**Standalone:** https://hosseinb1111.github.io/ping-monitor/

**Source:** https://github.com/hosseinb1111/ping-monitor

---

### AI

#### Groq Telegram Bot

Telegram AI experiment covering documented areas such as:

- conversational AI
- Telegram Bot API
- external API integration
- streaming
- image understanding
- web search
- tool calling
- conversation memory
- rate limiting
- webhook deduplication

**Source:** https://github.com/hosseinb1111/groq-telegram-bot

---

#### Cloudflare AI

Cloudflare-based AI chat project with documented features including:

- streaming AI responses
- Markdown rendering
- code highlighting
- stop / resume generation
- conversation history
- automatic titles
- persistent memory
- memory management
- web search
- image uploads
- drag and drop
- conversation search
- conversation export
- dark / light mode
- English / Persian support
- JWT authentication
- user data isolation
- rate limiting

The repository lists **Meta Llama 4 Scout** among the project model details.

**Source:** https://github.com/hosseinb1111/cloudflare-based-AI

---

#### Cloudflare Telegram AI

A Cloudflare-hosted AI Telegram system exploring:

- Telegram AI
- LLM integration
- conversation memory
- web search
- search classification
- multimodal handling
- continuation of long responses
- Telegram rich messages
- administration / broadcasting
- Cloudflare storage

It is presented here as an **AI infrastructure experiment**, not as an enterprise-scale platform.

**Source:** https://github.com/hosseinb1111/tg-AI-bot-cloudflare-hosted-OSS-120B

---

### Experiments & smaller projects

| Project | Area | Link |
|---|---|---|
| Stack Master | 3D browser game / experiment | https://stack-master.hossein.my.id/ |
| Random Adventure Generator | serverless interactive experiment | https://random-adventure-generator.hossein.my.id/ |
| Cool UI Chat Website | realtime UI experiment | https://github.com/hosseinb1111/Cool-UI-chat-website |
| Python Downloader | Python utility experiment | https://github.com/hosseinb1111/python-downloader1 |
| Motivation | bilingual web experiment | https://github.com/hosseinb1111/motivation |
| Snake Game | browser game | GitHub profile |
| Daily Boost | web project | portfolio archive |
| HTTP 204 | network / utility | https://204.hossein.my.id/ |
| Ping | network utility | https://ping.hossein.my.id/ |

These projects are intentionally shown with lighter descriptions where the public source material provides less technical detail.

---

## ☁️ The recurring technical direction

Across the projects, several themes appear repeatedly:

```text
WEB
 │
 ├── Frontend interfaces
 ├── Responsive applications
 └── Interactive browser projects

AI
 │
 ├── LLM APIs
 ├── Telegram bots
 ├── Search
 ├── Vision / multimodal workflows
 └── Memory + automation

EDGE / CLOUD
 │
 ├── Cloudflare Workers
 ├── KV
 ├── Durable Objects
 ├── D1
 └── WebSockets

REALTIME
 │
 ├── Messaging
 ├── Rooms
 ├── State synchronization
 └── Live UI behavior

NETWORKING
 │
 ├── HTTP / HTTPS
 ├── latency
 ├── jitter
 ├── DNS / TLS concepts
 └── browser networking constraints
```

This is not a claim of expertise in every item above. It is a representation of the technologies and directions that recur across the documented projects.

---

## 🖥️ Terminal

The terminal is intentionally functional enough to feel like part of the system rather than a screenshot.

Try:

```text
help
whoami
about
projects
skills
ai
cloud
realtime
network
github
open projects
open ai-lab
open edge-lab
open realtime-lab
open network
contact
ls
pwd
date
clear
```

Example:

```text
> whoami

Hossein
Computer Engineering student
Developer
Web / AI / Edge / Realtime
```

And:

```text
> cloud

Cloudflare Workers
Durable Objects
KV
D1
WebSockets
Serverless
```

---

## 📁 Portfolio filesystem

The File Explorer uses a fictional filesystem to organize the real portfolio conceptually:

```text
/home/hossein/
│
├── Desktop/
├── Projects/
│   ├── AI/
│   ├── Realtime/
│   ├── Cloud/
│   ├── Web/
│   ├── Utilities/
│   └── Experiments/
│
├── Labs/
│   ├── AI/
│   ├── Cloudflare/
│   ├── Networking/
│   └── Realtime/
│
├── About/
├── Contact/
└── README.md
```

It is a navigation model, not a real server filesystem.

---

## 🐙 GitHub integration

The GitHub application can request public profile and repository data from the GitHub API when the browser can reach it.

The UI deliberately avoids hardcoding dynamic GitHub numbers such as:

- followers
- following
- repository counts
- stars
- forks
- update dates

When GitHub API access fails, the application falls back to direct profile/source links instead of inventing data.

**GitHub:** https://github.com/Hosseinb1111

---

## ⚙️ Settings

The current OS includes lightweight experience controls:

- **Dark / Light theme**
- **Motion on / off**
- **English / Persian interface**
- direct GitHub access
- direct portfolio access
- built-in README viewer

The settings are intentionally small. The goal is to control the experience, not create a giant configuration dashboard.

---

## 📱 Mobile behavior

HOSSEIN OS does not simply shrink a desktop layout onto a phone.

On smaller screens:

```text
Desktop metaphor
      ↓
Full-screen applications
      ↓
Touch-friendly controls
      ↓
Bottom taskbar / launcher behavior
      ↓
Readable project views
```

Windows become application-sized surfaces, desktop controls adapt, and the terminal remains usable without requiring horizontal scrolling.

---

## ♿ Accessibility

The interface is designed around real controls and basic accessibility expectations:

- semantic buttons
- visible focus states
- keyboard navigation
- ARIA labels on important controls
- reduced-motion support
- readable contrast
- touch-friendly targets on mobile
- graceful fallback when network-loaded data is unavailable

The system log also clearly states that it is **aesthetic UI output, not production infrastructure telemetry**.

---

## 🎛️ Visual language

HOSSEIN OS intentionally avoids the usual portfolio tropes:

- no giant SaaS hero
- no fake analytics dashboard
- no skill percentage bars
- no inflated experience claims
- no excessive glassmorphism
- no constant particle animation
- no meaningless badges everywhere
- no huge gradients competing with the content

Instead, the interface uses:

**dark surfaces · precise borders · restrained cyan/violet accents · terminal typography · small status signals · compact system messages · functional interactions**

The result is intended to feel closer to a **personal developer workstation** than a website template.

---

## 🧪 Easter eggs

A few small secrets are intentionally hidden throughout the system.

Examples include:

- Konami code handling
- terminal jokes
- wallpaper interaction Easter egg
- developer-oriented system messages
- reboot / shutdown interactions

They are deliberately subtle so the portfolio remains usable first.

---

## 🏗️ Implementation

The current implementation is intentionally deployable as a **single standalone HTML file**.

### Main layers

```text
HOSSEIN OS
│
├── Data
│   ├── project catalog
│   ├── application definitions
│   └── public links
│
├── Desktop shell
│   ├── wallpaper
│   ├── launcher
│   ├── taskbar
│   └── system status
│
├── Window manager
│   ├── open / close
│   ├── focus / z-index
│   ├── minimize
│   ├── maximize
│   ├── drag
│   └── resize
│
├── Applications
│   ├── projects
│   ├── labs
│   ├── terminal
│   ├── explorer
│   ├── GitHub
│   ├── settings
│   └── system tools
│
└── Platform behavior
    ├── keyboard shortcuts
    ├── local settings
    ├── responsive behavior
    ├── reduced motion
    └── graceful API fallback
```

The page uses custom HTML/CSS/JavaScript rather than a component library or generic dashboard framework.

---

## 🔒 Factuality by design

One of the most important design constraints is that the interface should **not create a better-looking fictional version of the developer**.

HOSSEIN OS therefore avoids invented:

- employment history
- seniority
- awards
- certifications
- revenue
- users
- company relationships
- production scale
- performance claims
- GitHub statistics
- skill percentages

Where the public material is detailed, the UI can be detailed.

Where the public material is sparse, the UI stays sparse.

That is intentional.

---

## 👤 About Hossein

**Hossein Seyed Bagheri** is a **Computer Engineering student and developer** whose work repeatedly explores practical software across:

- web applications
- AI-powered tools
- Cloudflare edge systems
- realtime applications
- APIs
- networking
- developer-oriented experimentation

A concise way to describe the direction of the work is:

```text
WEB + AI + CLOUDFLARE + REALTIME + SOFTWARE EXPERIMENTATION
```

The portfolio is not trying to present a finished career story.

It presents a developer who is **learning by building, debugging, deploying, and iterating**.

---

## 🔗 Public links

| Resource | URL |
|---|---|
| GitHub | https://github.com/Hosseinb1111 |
| Portfolio | https://hossein.my.id/ |
| Persian Portfolio | https://fa.hossein.my.id/ |
| System AI | https://ai.hossein.my.id/ |
| WireChat | https://wirechat.hossein.my.id/ |
| Live Messenger | https://chat.hossein.my.id/ |
| File to Link | https://filetolink.hossein.my.id/ |
| Ping Monitor | https://pinging.ai09.workers.dev/ |

---

## 🚀 Run it locally

Because the current version is self-contained, you do not need a framework setup just to run the portfolio.

### Option 1 — open directly

Open `hossein-os.html` in a modern browser.

### Option 2 — serve it locally

Using Python:

```bash
python -m http.server 8080
```

Then visit:

```text
http://localhost:8080/hossein-os.html
```

Using Node.js:

```bash
npx serve .
```

A local server is useful when testing browser behavior and remote API requests.

---

## ⌨️ Keyboard shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl / Cmd + K` | Open launcher |
| `F1` | Open README Viewer |
| `F10` | Open shutdown screen |
| `Esc` | Close launcher / clear active state |
| Any key on lock screen | Unlock |
| Boot click / keypress | Skip boot sequence |

---

## 🛠️ Customizing the OS

The easiest customization points are near the top of the script:

```js
const LINKS = { ... };
const PROJECTS = [ ... ];
const APPS = [ ... ];
const DESKTOP_APPS = [ ... ];
```

This keeps the portfolio content separate from most of the presentation logic even though the current deployment artifact is a single file.

For example, a new project can be added to `PROJECTS` with its:

```js
{
  id,
  name,
  category,
  description,
  stack,
  details,
  live,
  source
}
```

The existing applications can then surface that data without duplicating the project content throughout the interface.

---

## 📌 Design philosophy

The project is built around one very simple loop:

```text
Idea
  ↓
Research
  ↓
Architecture
  ↓
Implementation
  ↓
Debugging
  ↓
Deployment
  ↓
Failure
  ↓
Understanding
  ↓
Improvement
```

Or, in four words:

> **Build. Break. Understand. Improve.**

---

## 📄 License 

This project is under MIT License feel free to use this code in any way that you like

---

<div align="center">

### HOSSEIN OS

**The portfolio is the project.**

`WEB` · `AI` · `EDGE` · `REALTIME` · `NETWORKING` · `EXPERIMENTS`

</div>
