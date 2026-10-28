<!-- ═══════════════════════════════════════════════════════════════════════════
     Amirhoseyn Asghari · GitHub Profile README
     Repo: github.com/AmirhoseynpowAsghari/AmirhoseynpowAsghari
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f6feb,100:39d353&height=210&section=header&text=Amirhoseyn%20Asghari&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Condensed%20Matter%20%C2%B7%20Quantum%20Information%20%C2%B7%20Computational%20Physics&descAlignY=58&descSize=17&animation=fadeIn" width="100%" alt="Amirhoseyn Asghari"/>

<a href="https://amirhoseynpowasghari.github.io">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=720&lines=PhD+student+in+Condensed+Matter+Physics;Open+quantum+systems+%26+entanglement+dynamics;Green%27s+functions%2C+BdG+solver%2C+Kraus+maps;Turning+many-body+structure+into+a+quantum+resource" alt="Typing SVG" />
</a>

<br/>

<a href="https://amirhoseynpowasghari.github.io"><img src="https://img.shields.io/badge/Website-amirhoseynpowasghari.github.io-1f6feb?style=flat-square&logo=githubpages&logoColor=white" alt="Website"/></a>
<a href="https://github.com/AmirhoseynpowAsghari?tab=repositories"><img src="https://img.shields.io/badge/Repositories-17%20public-39d353?style=flat-square&logo=github&logoColor=white" alt="Repositories"/></a>
<img src="https://komarev.com/ghpvc/?username=AmirhoseynpowAsghari&label=visitors&color=1f6feb&style=flat-square" alt="Profile views"/>
<a href="https://github.com/AmirhoseynpowAsghari"><img src="https://img.shields.io/github/followers/AmirhoseynpowAsghari?label=followers&style=flat-square&color=8957e5" alt="Followers"/></a>

</div>

---

<table>
<tr>
<td width="55%" valign="top">

### ⚛️ About me

I work at the intersection of **condensed matter theory**, **open quantum systems**, and **quantum information** — with a bias toward writing the numerics myself rather than trusting a black box.

- 🎓 PhD student in **Condensed Matter Physics** (Iran)
- 🧪 I study how **many-body structure** becomes a *resource* — or a *constraint* — for quantum information
- 🔭 Main lens: **superconductivity + spin–orbit coupling → two-qubit entanglement**
- 🐍 Everything is reproducible Python: self-consistency solvers, BZ integrations, noise channels
- 📓 I also teach the ML side of a physicist's toolkit (kNN → SVM → CNN, from scratch in notebooks)
- 🌱 Currently: non-Markovian dynamics, Holevo capacity, and cleaner numerical pipelines

</td>
<td width="45%" valign="top">

```python
# the object of study
rho: DensityMatrix = build_from_greens(
    G = G_r_theta,      # normal Green's function
    F = F_r_theta,      # anomalous correlations
)

rho = evolve(rho, channels.non_markovian(gamma))

return {
    "concurrence": C(rho),      # entanglement
    "singlet_fraction": S(rho), # teleportation quality
    "holevo": chi(rho),         # dense-coding capacity
    "entropy": S_vN(rho),       # decoherence
}
```

</td>
</tr>
</table>

---

## 🔬 Research focus

<table>
<tr>
<th align="left" width="33%">🧊 Condensed Matter Theory</th>
<th align="left" width="33%">🔗 Quantum Information</th>
<th align="left" width="34%">🌊 Open Quantum Systems</th>
</tr>
<tr valign="top">
<td>

Superconductivity, lattice models, spin–orbit coupling, Green's functions and correlation effects in quantum materials.

`BCS` · `BdG` · `Hubbard` · `Rashba SOC` · `d-wave pairing` · `phonons`

</td>
<td>

Entanglement, teleportation, dense coding, information capacity — and how quantum resources survive realistic dynamics.

`concurrence` · `fidelity` · `singlet fraction` · `Holevo χ`

</td>
<td>

Non-Markovian noise, amplitude damping, dephasing, common environments and their fingerprints on two-qubit states.

`Kraus maps` · `memory effects` · `decoherence` · `Lindblad`

</td>
</tr>
</table>

> **Research axis:** correlations → decoherence → computation.

---

## 🚀 Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🔗 Quantum Teleportation & Dense Coding in Open Quantum Systems
<a href="https://github.com/AmirhoseynpowAsghari/quantum-teleportation-and-dense-coding-in-open-quantum-systems"><img src="https://img.shields.io/badge/code-GitHub-58A6FF?style=flat-square&logo=github&logoColor=white" alt="code"/></a>
<img src="https://img.shields.io/badge/stars-2-8957e5?style=flat-square&logo=github&logoColor=white" alt="stars"/>

A numerical framework that builds **Cooper-pair two-qubit states** from Hubbard/BdG Green's functions, evolves them through **non-Markovian noise**, and tracks entanglement + information-theoretic observables end to end.

`BdG solver` `ρ(θ, r)` `Kraus channels` `C · F · S · χ`

</td>
<td width="50%" valign="top">

### 🎶 Power Absorption under a Time-Dependent Perturbation
<a href="https://github.com/AmirhoseynpowAsghari/power-absorbed-in-the-presence-of-external-time-dependent-perturbation"><img src="https://img.shields.io/badge/code-GitHub-58A6FF?style=flat-square&logo=github&logoColor=white" alt="code"/></a>
<img src="https://img.shields.io/badge/stars-1-8957e5?style=flat-square&logo=github&logoColor=white" alt="stars"/>

BCS superconductivity with **Rashba spin–orbit coupling** on a 2D square lattice: self-consistent `Tc` and gap, then **ultrasonic attenuation** `W/Wₙ` as a function of `V_SO`, `U` and `T` — a four-stage reproducible pipeline.

`tight-binding` `ε±(k)` `Tc vs V_SO` `W/Wₙ`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌀 Quantum Phase Transition
<a href="https://github.com/AmirhoseynpowAsghari/Quantum-Phase-Transition"><img src="https://img.shields.io/badge/code-GitHub-58A6FF?style=flat-square&logo=github&logoColor=white" alt="code"/></a>

Sweeps the interaction strength `U` across negative → positive regimes, solves coupled BdG gap equations with **continuation & warm starts**, and plots **concurrence `C(U)`** with its numerical derivative — a phase-transition-like signature.

`2D BZ integration` `continuation solver` `dC/dU`

</td>
<td width="50%" valign="top">

### 🧠 Machine Learning for Physicists
<a href="https://github.com/AmirhoseynpowAsghari/Machine-Learning-for-Physicists-"><img src="https://img.shields.io/badge/code-GitHub-58A6FF?style=flat-square&logo=github&logoColor=white" alt="code"/></a>
<img src="https://img.shields.io/badge/stars-1-8957e5?style=flat-square&logo=github&logoColor=white" alt="stars"/>

A guided climb from **linear models → kNN → SVM → CNNs**, including digit recognition — written as notebooks that a physicist can actually read, not as a framework dump.

`Jupyter` `scikit-learn` `CNN` `digits`

</td>
</tr>
</table>

<details>
<summary><b>📚 All public repositories</b></summary>

<br/>

| Repository | What's inside |
| :--- | :--- |
| [quantum-teleportation-and-dense-coding-in-open-quantum-systems](https://github.com/AmirhoseynpowAsghari/quantum-teleportation-and-dense-coding-in-open-quantum-systems) | BdG Green's functions → two-qubit ρ → non-Markovian evolution → C, F, S, χ |
| [power-absorbed-in-the-presence-of-external-time-dependent-perturbation](https://github.com/AmirhoseynpowAsghari/power-absorbed-in-the-presence-of-external-time-dependent-perturbation) | BCS + Rashba SOC on a 2D lattice, self-consistent Tc, ultrasonic attenuation |
| [ultrasonic-power-absorbed-Modifications](https://github.com/AmirhoseynpowAsghari/ultrasonic-power-absorbed-Modifications) | Corrected/refined branch of the ultrasonic absorption study |
| [Quantum-Phase-Transition](https://github.com/AmirhoseynpowAsghari/Quantum-Phase-Transition) | Concurrence `C(U)` and `dC/dU` from self-consistent BdG + BZ integration |
| [Phonon-limited-superconducting-correlations-in-metallic-nanograins](https://github.com/AmirhoseynpowAsghari/Phonon-limited-superconducting-correlations-in-metallic-nanograins) | Phonon-limited superconducting correlations in metallic nanograins |
| [Machine-Learning-for-Physicists-](https://github.com/AmirhoseynpowAsghari/Machine-Learning-for-Physicists-) | Notebook course: linear models, kNN, SVM, CNN, digit recognition |
| [amirhoseynpowasghari.github.io](https://github.com/AmirhoseynpowAsghari/amirhoseynpowasghari.github.io) | Personal research site (GitHub Pages) |
| [symmetrical-octo-pancake](https://github.com/AmirhoseynpowAsghari/symmetrical-octo-pancake) · [jubilant-enigma](https://github.com/AmirhoseynpowAsghari/jubilant-enigma) | Numerical experiments & sandboxes |

</details>

---

## 🧰 Toolbox

<div align="center">

**Physics & numerics**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>

**Methods & tools**

<img src="https://img.shields.io/badge/Green's%20functions-1f6feb?style=for-the-badge" alt="Green's functions"/>
<img src="https://img.shields.io/badge/BdG%20solver-1f6feb?style=for-the-badge" alt="BdG"/>
<img src="https://img.shields.io/badge/Kraus%20maps-1f6feb?style=for-the-badge" alt="Kraus"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
<img src="https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white" alt="LaTeX"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>

</div>

---

## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=AmirhoseynpowAsghari&show_icons=true&hide_border=true&bg_color=00000000&title_color=58A6FF&icon_color=39D353&text_color=8b949e&include_all_commits=true&count_private=true" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmirhoseynpowAsghari&layout=compact&hide_border=true&bg_color=00000000&title_color=58A6FF&text_color=8b949e&langs_count=6" alt="Top languages"/>

<br/>

<img src="https://streak-stats.demolab.com?user=AmirhoseynpowAsghari&theme=tokyonight&hide_border=true&background=00000000&ring=39D353&fire=FF7B72&currStreakLabel=58A6FF" alt="Streak"/>

<br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=AmirhoseynpowAsghari&bg_color=00000000&color=58A6FF&line=39D353&point=ffffff&area=true&hide_border=true" alt="Activity graph"/>

</div>

---

## 🎯 Right now

```text
[■] BdG  ── self-consistency + continuation, tighter convergence
[■] OQS  ── non-Markovian channels, memory effects on 2-qubit states
[▶] INFO ── Holevo capacity & singlet fraction under noise
[ ] CODE ── package the solvers into one installable library
[ ] WRITE ── turn the two main studies into a clean paper draft
```

**Open to:** collaborations on quantum matter, open systems, and computational physics — especially people who like clean numerics and honest error bars.

---

## ✨ A line I keep coming back to

$$
|\psi\rangle = \alpha|00\rangle + \beta|11\rangle
\qquad\Longrightarrow\qquad
\text{entanglement is a currency, and the environment is the tax}
$$

<div align="center">

> *“The most exciting phrase in science is not ‘Eureka!’ but ‘that’s funny…’”* — I. Asimov

</div>

---

## 🤝 Connect

<div align="center">

<a href="https://amirhoseynpowasghari.github.io"><img src="https://img.shields.io/badge/Research%20site-Visit-1f6feb?style=for-the-badge&logo=githubpages&logoColor=white" alt="Site"/></a>
<a href="https://github.com/AmirhoseynpowAsghari"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://github.com/AmirhoseynpowAsghari?tab=achievements"><img src="https://img.shields.io/badge/Achievements-See%20all-8957e5?style=for-the-badge&logo=github&logoColor=white" alt="Achievements"/></a>

</div>

<details>
<summary><b>🇮🇷 درباره من (فارسی)</b></summary>

<br/>

دانشجوی دکتری فیزیک ماده چگال؛ کارم در مرزِ **نظریهٔ ماده چگال**، **سیستم‌های کوانتومی باز** و **اطلاعات کوانتومی** است. علاقه‌ام جایی است که ساختار چندجسمی به یک «منبع» یا «محدودیت» برای اطلاعات کوانتومی تبدیل می‌شود — مثلاً ابررسانایی با جفت‌شدگی اسپین–مدار، و سرنوشت درهم‌تنیدگی در حضور نویز غیرمارکوفی.

تقریباً همهٔ کارها را با پایتون و به‌صورت بازتولیدپذیر انجام می‌دهم: حل خودسازگار BdG، انتگرال‌گیری روی ناحیهٔ بریلوئن، کانال‌های کراوس، و محاسبهٔ کمیت‌هایی مثل هم‌بستگی (concurrence)، کسر تک‌تایی، و ظرفیت هلویو.

اگر روی مادهٔ کوانتومی، سیستم‌های باز یا فیزیک محاسباتی کار می‌کنید، خوشحال می‌شوم در ارتباط باشیم.

</details>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:39d353,50:1f6feb,100:0d1117&height=130&section=footer&fontSize=16&text=Thanks%20for%20stopping%20by%20%E2%80%94%20let%27s%20compute%20something.&fontColor=ffffff&fontAlignY=68" width="100%" alt="footer"/>

</div>
