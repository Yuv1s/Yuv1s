<div align="center">

### student developer building systems, tools, and things I actually want to use

`software engineering` · `cloud` · `cybersecurity` · `developer tools`

[![Trawl](https://img.shields.io/badge/Trawl-open_source-111111?style=for-the-badge\&logo=rust\&logoColor=white)](https://github.com/Yuv1s/Trawl)
[![EzRegex](https://img.shields.io/badge/EzRegex-live_tool-111111?style=for-the-badge\&logo=react\&logoColor=white)](https://ezregex.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-111111?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/yuv1)

</div>

<br>

I build across application development, cloud, cybersecurity, automation, and AI. I'm still a student, but most of what I learn comes from shipping systems, breaking things, fixing them, and understanding why they broke.

> **I use AI to move faster, not to outsource the thinking. If I can't explain the code, test the edge cases, and account for the security decisions, I don't ship it.**

## what I'm building

<details open>
<summary><b>Trawl</b> · browser-based CTF toolkit</summary>

<br>

[Trawl](https://github.com/Yuv1s/Trawl) is the project I'm pushing hardest right now.

It's a browser-based toolkit for CTF analysis across steganography, cryptography, web challenges, and forensics.

A few decisions behind it matter more to me than the feature count:

* files stay on the user's machine instead of being uploaded somewhere
* the analysis core is written in Rust and compiled to WebAssembly
* the core has zero runtime dependencies
* parsers, detectors, decoders, and attacks are implemented inside the project
* detectors are tested against known-positive files and clean controls instead of being trusted because they "look right"

I like tools that let me get close to the mechanism. Trawl gives me an excuse to do exactly that.

[try it](https://trawlctf.vercel.app) · [source](https://github.com/Yuv1s/Trawl) · [roadmap](https://github.com/Yuv1s/Trawl/blob/main/ROADMAP.md)

</details>

<details>
<summary><b>EzRegex</b> · regex playground with plain-English explanations</summary>

<br>

[EzRegex](https://github.com/Yuv1s/EzRegex) turns regular expressions into something easier to inspect.

It highlights matches live and explains the pattern piece by piece using a hand-written tokenizer that walks through anchors, character classes, groups, escapes, quantifiers, alternation, and literals.

The app runs client-side with no backend or API key.

This repo is also a pretty good example of how I work with AI. Some scaffolding and repetitive work can be accelerated. The tokenizer, behavior, product decisions, and the parts I actually need to understand stay mine.

[open the app](https://ezregex.vercel.app) · [source](https://github.com/Yuv1s/EzRegex)

</details>

## what I'm working toward

I'm interested in the parts of software that force you to understand what is actually happening underneath the abstraction.

That usually pulls me toward developer tooling, security, cloud systems, automation, and projects where correctness matters more than making the demo look impressive.

I also compete in cybersecurity and spend time working with Windows and Linux hardening, scripting, forensics, cryptography, and reverse engineering. It has made me a lot more suspicious of assumptions, which is probably a good habit to have when writing software.

<details>
<summary><b>what I tend to work with</b></summary>

<br>

**Languages**

`Rust` `Python` `JavaScript` `TypeScript` `Dart` `SQL` `Bash` `PHP`

**Application development**

`React` `Svelte` `Flutter` `Firebase` `Firestore` `Stripe`

**Cloud & infrastructure**

`AWS` `Google Cloud` `Vercel` `MySQL`

**Security**

`Windows Hardening` `Linux Hardening` `Forensics` `Cryptography` `Reverse Engineering`

**AI & automation**

`OpenAI API` `Fine-tuning` `Prompt Engineering` `Workflow Automation`

</details>

<br>

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,python,js,ts,react,svelte,flutter,dart,aws,firebase,gcp,mysql,bash,git,vercel" alt="Technologies I work with" />
</p>

---

<div align="center">

`build it` → `understand it` → `break it` → `fix it` → `ship it`

</div>
