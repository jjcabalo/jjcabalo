from pathlib import Path

readme = r'''<div align="center">

<a href="https://github.com/jjcabalo">
<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=000000&customColorList=0&text=JERVYS&fontColor=FFD21F&fontSize=58&fontAlignY=38&desc=UI%2FUX%20DESIGNER%20%C2%B7%20BUILDER%20%C2%B7%20ASPIRING%20AI%20ENGINEER&descColor=FFFFFF&descSize=16&descAlignY=58&animation=fadeIn" width="100%"/>
</a>

<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=600&size=18&pause=1200&color=FFD21F&center=true&vCenter=true&width=650&lines=I+design+interfaces+people+want+to+use.;I+turn+ideas+into+digital+experiences.;UI%2FUX+%2B+Creative+Technology+%2B+AI." alt="Animated introduction"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-000000?style=flat-square&logo=linkedin&logoColor=FFD21F)](https://www.linkedin.com/in/jjcabalo/)
[![Figma](https://img.shields.io/badge/FIGMA-000000?style=flat-square&logo=figma&logoColor=FFD21F)](https://www.figma.com/design/o72FIFhP9JvfqAFDOtAAh0/Designs-by-JJ-Cabalololo)
[![Instagram](https://img.shields.io/badge/INSTAGRAM-000000?style=flat-square&logo=instagram&logoColor=FFD21F)](https://www.instagram.com/not_jrvys/)
[![Facebook](https://img.shields.io/badge/FACEBOOK-000000?style=flat-square&logo=facebook&logoColor=FFD21F)](https://www.facebook.com/jjrvys)

</div>

---

## 01 / THE DESIGNER

**John Jervys Cabalo** — a 4th-year Computer Science student focused on **UI/UX, web & mobile experiences, and creative technology**.

I like working where **design meets engineering**: shaping the interface, directing the visual story, then building the experience behind it.

Currently growing toward **AI Engineering + Data Science**.

<details>
<summary><b>↳ HOW I THINK</b></summary>

<br>

**01 — Understand**  
Find the real problem before touching the interface.

**02 — Design**  
Make complex things feel simple, intentional, and human.

**03 — Build**  
Turn the visual system into something functional.

**04 — Iterate**  
Test, refine, repeat.

</details>

---

## 02 / SELECTED WORK

<table>
<tr>
<td width="50%">

### KOMYUTPH
**Offline-first public transport · UI/UX · Product Design**

A community-powered navigation concept for Philippine public transportation, designed around real-world commuting constraints.

→ [View project](https://github.com/jjcabalo)

</td>
<td width="50%">

### HANDA
**Disaster response · UI/UX · Media Direction**

Household Assessment and Needs Determination Application created for the **eGovPH Hackathon 2026**.

→ [View GitHub](https://github.com/jjcabalo)

</td>
</tr>
</table>

<details>
<summary><b>MORE THINGS I'VE BUILT</b></summary>

<br>

**Sertify** — certificate generation platform  
**RefactorAI** — automated code-smell detection using AST + GNN concepts  
**IoTrack** — IoT-based machine monitoring and learning system

</details>

---

## 03 / PROOF OF WORK

**🏆 Top 10 Finalist — eGovPH Hackathon 2026**  
Team Cordon Bleu · UI/UX Designer + Media Director

**🥇 Most Commercially Viable Award — UMak 7th Hackathon 2025**

**🥇 Champion — OpenGov Hackathon 2025**

**🎓 Consistent Dean's Lister**  
6 consecutive semesters · Running average: **1.243**

**🎬 Slide Deck Committee + Technical Committee Staff — CIC, University of Makati**  
Supported live presentation production for major university ceremonies, including the UMak Hooding Ceremony and 53rd Commencement Exercises.

---

## 04 / MY TOOLKIT

**DESIGN**  
`Figma` · `UI/UX` · `Design Systems` · `Prototyping` · `Visual Design` · `Motion`

**BUILD**  
`TypeScript` · `React Native` · `NestJS` · `ASP.NET` · `Jetpack Compose` · `Tailwind CSS`

**DATA / AI**  
`Python` · `scikit-learn` · `XGBoost` · `PostGIS` · `Gemini API`

**CREATIVE**  
`Figma` · `Video Editing` · `Videography` · `Media Production`

---

<div align="center">

### DESIGN. BUILD. ITERATE.

[**VIEW MY DESIGNS ↗**](https://www.figma.com/design/o72FIFhP9JvfqAFDOtAAh0/Designs-by-JJ-Cabalololo) ·
[**CONNECT ON LINKEDIN ↗**](https://www.linkedin.com/in/jjcabalo/) ·
[**FOLLOW THE PROCESS ↗**](https://www.instagram.com/not_jrvys/)

<br><br>

<img src="https://komarev.com/ghpvc/?username=jjcabalo&style=flat-square&color=FFD21F&label=PROFILE+VIEWS" alt="Profile views"/>

<br>

<sub>Black canvas. Yellow signal. Human-centered by default.</sub>

</div>
'''

path = Path("/mnt/data/readme_redesigned.md")
path.write_text(readme, encoding="utf-8")
print(f"Created: {path}")
