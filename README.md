<picture>
  <img alt="Anurag P.O." src="./banner.svg" width="100%" />
</picture>

<br/>

Second-year B.Tech CS student at GCET, Vadodara. I ship full-stack and AI systems, then get them into production — most recently an offline computer vision pipeline running on a chemical plant floor.

**[anuragpo.is-a.dev](https://anuragpo.is-a.dev/) &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/anurag-po) &nbsp;·&nbsp; anuragpo393@gmail.com**

<br/>

### GACL — Industrial OCR Pipeline

A month into my internship at Gujarat Alkalies & Chemicals Limited, my mentor sat me down in front of a SCADA dashboard and said the standard OCR tools weren't holding up on the UI. I built a replacement: an offline pipeline that reads live HMI tables through an IP camera, reconstructs them with custom grid detection and line regression (the off-the-shelf models kept producing phantom columns and misaligned diagonal cells), runs it through PaddleOCR, and exports to Excel with a human-review step before anything is finalized. No data leaves the building. It now runs at near-100% accuracy.

![Python](https://img.shields.io/badge/-Python-0a0a0a?style=flat-square) ![OpenCV](https://img.shields.io/badge/-OpenCV-0a0a0a?style=flat-square) ![PaddleOCR](https://img.shields.io/badge/-PaddleOCR-0a0a0a?style=flat-square)

<br/>

### Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>ALEX</strong> — Adaptive Logic EXecutor
      <br/><br/>
      A deterministic AI execution layer. Natural language in, schema-validated JSON out; every action runs through a controlled function registry instead of unrestricted tool calls. Voice + text input, real-time overlay UI.
      <br/><br/>
      <img alt="Python" src="https://img.shields.io/badge/-Python-0a0a0a?style=flat-square" />
      <img alt="FastAPI" src="https://img.shields.io/badge/-FastAPI-0a0a0a?style=flat-square" />
      <img alt="PySide6" src="https://img.shields.io/badge/-PySide6-0a0a0a?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <strong>MinuteMind</strong> — AI Meeting Execution
      <br/><br/>
      Turns meeting transcripts into structured, owned tasks through an async LLM pipeline with validation logic for missing owners and deadlines. Cut pilot workflow turnaround from 6 days to 2.
      <br/><br/>
      <img alt="Next.js" src="https://img.shields.io/badge/-Next.js-0a0a0a?style=flat-square" />
      <img alt="FastAPI" src="https://img.shields.io/badge/-FastAPI-0a0a0a?style=flat-square" />
      <img alt="Supabase" src="https://img.shields.io/badge/-Supabase-0a0a0a?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Nexlyra</strong> — Productivity Browser
      <br/><br/>
      A keyboard-first desktop browser. Instead of treating every input as a URL, it classifies intent and routes to sites, search, or an AI assistant automatically.
      <br/><br/>
      <img alt="Electron" src="https://img.shields.io/badge/-Electron-0a0a0a?style=flat-square" />
      <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-0a0a0a?style=flat-square" />
    </td>
    <td width="50%" valign="top">
      <strong>Mnemosyne</strong> <em>— in progress</em>
      <br/><br/>
      A memory layer for conversational agents that stores experiences as structured episodes instead of retrieving flat documents, with retrieval guided by explainable associations rather than vector similarity alone.
      <br/><br/>
      <img alt="Python" src="https://img.shields.io/badge/-Python-0a0a0a?style=flat-square" />
      <img alt="LLMs" src="https://img.shields.io/badge/-LLMs-0a0a0a?style=flat-square" />
    </td>
  </tr>
</table>

<br/>

### Stack

<table>
  <tr>
    <td valign="top"><strong>Languages</strong></td>
    <td>Python · JavaScript · C++</td>
  </tr>
  <tr>
    <td valign="top"><strong>AI / CV</strong></td>
    <td>OpenCV · PaddleOCR · LLM integration (Claude, Gemini)</td>
  </tr>
  <tr>
    <td valign="top"><strong>Backend</strong></td>
    <td>FastAPI · PostgreSQL · Supabase</td>
  </tr>
  <tr>
    <td valign="top"><strong>Frontend / Desktop</strong></td>
    <td>React · Next.js · Electron · PySide6</td>
  </tr>
</table>

<br/>

> Build to understand. Refine until it feels inevitable.
