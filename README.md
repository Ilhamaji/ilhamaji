<div align="left">

<img src="https://komarev.com/ghpvc/?username=ilhamaji&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views" />

# Ilham Aji

Computer science student in Indonesia. I build web apps end to end, and I care most about the parts that are easy to skip: fallback when an API fails, a schema that survives real data, a README you can actually follow.

<a href="mailto:ilhmsap@gmail.com"><img src="https://img.shields.io/badge/Email-ilhmsap%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://ilhamaji.github.io"><img src="https://img.shields.io/badge/Portfolio-ilhamaji.github.io-0e75b6?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>

<!-- lang-switcher -->
**English** · [Bahasa Indonesia](README.id.md)

</div>

---

## Selected Projects

Four projects that show what I actually work on. Everything else is on [my repositories page](https://github.com/Ilhamaji?tab=repositories).

### [groq-article-summarizer](https://github.com/Ilhamaji/groq-article-summarizer)

Gathering journal sources for a thesis is slow: open the article, download the PDF, read the abstract and conclusion, repeat. This pipeline does that path in one call — give it an article URL, it finds the PDF link, extracts the text with PyMuPDF, splits the body from the bibliography so citations don't pollute the summary, and returns a structured summary from `llama-3.3-70b-versatile` via Groq.

The part I'd point at: it has an evaluation mode that measures latency and title/author similarity with `SequenceMatcher`, because the summariser needed numbers for a thesis chapter, not just a demo.

`Python` · `Groq` · `PyMuPDF` · `BeautifulSoup`

### [skin-cancer-inference-api](https://github.com/Ilhamaji/skin-cancer-inference-api)

An image-classification REST API from a Dicoding machine-learning course. Two classes, Cancer and Non-cancer, with a 50% confidence floor — below that it answers *Non-cancer*, because a false positive here is the expensive mistake. Every prediction is written to Firestore so results can be reviewed later.

`Hapi.js` · `TensorFlow.js` · `Firestore` · `Google Cloud`

### [cheting](https://github.com/Ilhamaji/cheting)

A real-time chat app in the Discord/Slack shape: DMs, groups that hold categories and channels, a friend system, and WebRTC voice channels. NextAuth for auth, Prisma over PostgreSQL, Radix/Shadcn for the UI.

The interesting constraint was doing real-time signalling on the Next.js App Router, where there is no long-lived server to park a socket on.

`Next.js 15` · `Prisma` · `PostgreSQL` · `WebRTC`

### [academy-dashboard](https://github.com/Ilhamaji/academy-dashboard)

A Laravel app for a school's finances: tuition payments, expenses, and the reports both need. Replaces the cash book and loose spreadsheets with one searchable database and Excel/PDF export.

It's the least glamorous thing here and probably the most used. Worth knowing before you open it: there is no role separation — every route under the `auth` group is reachable by any logged-in account.

`Laravel` · `PHP` · `MySQL` · `Blade`

---

## In Progress

- **[ats-cv-maker](https://github.com/Ilhamaji/ats-cv-maker)** — Nuxt 4 CV editor that exports through Puppeteer. The editor and PDF export work; it does not save yet, so a refresh loses your data.
- **[haclash](https://github.com/Ilhamaji/haclash)** — a 2D hack-and-slash in Godot. Movement, platforms, and attack animations exist; there are no enemies, so it isn't playable as a game.

Both have a roadmap in their READMEs.

---

## Stack

Day to day: TypeScript, React, Next.js, Tailwind. Backend in Node/Express or Laravel with PostgreSQL or MySQL. Python for NLP work.

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,nodejs,express,php,laravel,mysql,postgres,python,docker,git" alt="Tech stack" />
</p>
