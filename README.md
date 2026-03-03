<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=d2a8ff&height=220&section=header&text=Deep%20Research%20Agent&fontSize=42&fontAlignY=35&desc=Web%20Application&descAlignY=55&fontColor=ffffff" alt="Header"/>

<p align="center">
  <img src="https://img.shields.io/badge/Type-Web%20Application-d2a8ff?style=for-the-badge&logo=target&logoColor=black" alt="Type" />
  <img src="https://img.shields.io/badge/Language-JavaScript-d2a8ff?style=for-the-badge&logo=code&logoColor=black" alt="Language" />
  <img src="https://img.shields.io/badge/Files-22-161b22?style=for-the-badge&logo=files&logoColor=d2a8ff" alt="Files" />
  <img src="https://img.shields.io/badge/License-PROPRIETARY-ff0000?style=for-the-badge&logo=shield&logoColor=white" alt="License" />
</p>

  <img src="https://img.shields.io/badge/Express.js-161b22?style=flat-square&logo=expressjs&logoColor=d2a8ff" alt="Express.js" />


</div>

---

## Overview

> Deep Research Agent is an AI research system that searches seven trusted sources in parallel, cross-validates results, and generates structured reports with real citations. Using a multi-agent architecture and Gemini 3, it identifies consensus, contradictions, and knowledge gaps in real time.

**Deep Research Agent** is a proprietary web application system engineered by **Karthik Idikuda**. It leverages Express.js for its core functionality.

<br/>

## System Architecture

```mermaid
graph TD;
    A["Client Browser"] -->|HTTP| B["Static HTML/CSS/JS"];
    B --> C["DOM Renderer"];
    B -->|API Calls| E["Express.js Backend"];
    E -->|JSON| F[(Database)];

    classDef frontend fill:#0d1117,stroke:#58a6ff,stroke-width:2px,color:#fff;
    classDef backend fill:#161b22,stroke:#d2a8ff,stroke-width:2px,color:#fff;
    classDef styling fill:#21262d,stroke:#79c0ff,stroke-width:1px,color:#fff;
    class A,B,C frontend;
    class D styling;
    class E,F backend;
```

<br/>

## Project Structure

```
Deep-Research-Agent/
  .env.example
  .gitignore
  LICENSE
  README.md
  package-lock.json
  package.json
  vercel.json
  client/
    index.html
    package-lock.json
    package.json
    postcss.config.js
    tailwind.config.js
  src/
    server.js
```

<br/>

## Technical Specifications

| Attribute | Detail |
|:---|:---|
| **Primary Language** | `JavaScript` |
| **Project Category** | `Web Application` |
| **Total Source Files** | `22` |
| **Frameworks** | `Express.js` |
| **Key Dependencies** | `axios` | `uuid` | `cheerio` | `cors` | `express` | `ws` | `@google/generative-ai` | `concurrently` | `dotenv` |
| **Intellectual Property** | `Strictly Proprietary` |

<br/>

## STRICT LEGAL WARNING & LICENSE

> **PROPRIETARY AND CONFIDENTIAL**

This software and all associated documentation are the **exclusive property of Karthik Idikuda**.

- **NO PERMISSION IS GRANTED** to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of this software without explicit, written consent from the author.
- **UNAUTHORIZED USE WILL RESULT IN SEVERE LEGAL ACTION.** Any individual or organization found using, referencing, or deploying this code without paying the required licensing fees will face immediate litigation, financial penalties, and potentially criminal prosecution where applicable by law.
- **TO OBTAIN A LEGAL LICENSE**, you must directly contact Karthik Idikuda to negotiate payment terms.

*By accessing this repository, you acknowledge and accept these strict proprietary terms.*

---

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=600&size=18&pause=1000&color=D2A8FF&center=true&vCenter=true&width=535&lines=Engineered+by+Karthik+Idikuda;Web+Application+Architecture;Strict+Proprietary+License" alt="Typing SVG" />
</div>

<!-- TRACKING: S0ktRGVlcC1SZXNlYXJjaC1BZ2VudC1UUkFDSw== -->
