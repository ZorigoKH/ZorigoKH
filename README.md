<h1 align="center">Zorigtbaatar (Zori) Khasbaatar</h1>

<p align="center"><b>Data Science (AI) &amp; Economics @ NYU · Full-Stack Engineering @ Terran Enterprise</b></p>

<p align="center"><code>econometrics</code> · <code>fintech</code> · <code>full-stack products</code> · <code>data infrastructure</code></p>

## About Me

I started building in Ulaanbaatar: I co-founded HUR, Mongolia's first digital university-admissions platform, and led product and growth to a community of 6,000+. In 2026 I co-founded SolveSim, a case-interview simulator that reached 250+ users across free and paid tiers in its first three months.

Now I'm a full-stack engineering intern at Terran Enterprise and a founding engineer on [Terran Denizen](https://terrandenizen.com), a career platform for MBA students at the M7 business schools. In summer 2026 I was in technology risk at EY, assessing the security operations center of one of Mongolia's largest banks against SOC-CMM with the EY Hong Kong team. Most of my commits live in the private Terran Denizen org, which is where the green squares come from.

Ulaanbaatar → Shanghai → New York.

## Things I've built

### unbundle — how much of a fund's return could you have bought for a few basis points?

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZorigoKH/unbundle/main/docs/attribution-dark.svg">
  <img alt="Carhart attribution, 1963 to 2017: energy and business-equipment stocks both earned 7.3% a year over T-bills, but only business equipment had alpha" src="https://raw.githubusercontent.com/ZorigoKH/unbundle/main/docs/attribution-light.svg" width="720">
</picture>

Factor regressions from the CAPM to Fama–French five factors plus momentum, which split a return exactly into exposure and alpha, with Newey–West standard errors from sandwich, GRS and HAC Wald tests of all the alphas at once, rolling exposures, and a one-file HTML tearsheet. 57 tests, and every number in the README is recomputed by the test suite.

→ [github.com/ZorigoKH/unbundle](https://github.com/ZorigoKH/unbundle)

<code>Python</code> <code>Asset Pricing</code> <code>Fama–French</code> <code>Newey–West</code> <code>Fintech</code>

<table>
<tr>
<td width="50%" valign="top">

### [sandwich](https://github.com/ZorigoKH/Sandwich) — an econometrics engine in NumPy

OLS, HC / cluster / HAC standard errors, IV/2SLS and panel fixed effects, built on one idea: every covariance is `bread · meat · bread`, and only the meat changes. 51 tests match statsmodels and linearmodels to `rtol=1e-9`.

<code>NumPy</code> <code>SciPy</code> <code>Econometrics</code> <code>Panel Data</code>

</td>
<td width="50%" valign="top">

### [tailor](https://github.com/ZorigoKH/tailor) — a job-application copilot that can't make things up about you

Reads a posting into requirements, finds the evidence for each in your own notes with BM25 + embedding retrieval, and checks every quote word for word against its source, without asking a model. Offline evals run in CI.

<code>LLM</code> <code>RAG</code> <code>Retrieval</code> <code>Evals</code>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Terran Denizen — career platform for M7 MBAs

Founding engineer. Four Next.js apps and a Node API on one PostgreSQL backend, 76 row-level security policies guarded by an hourly leak check, and an Expo iOS app in progress. Private org; live at [terrandenizen.com](https://terrandenizen.com).

<code>Next.js</code> <code>TypeScript</code> <code>PostgreSQL</code> <code>React Native</code>

</td>
<td width="50%" valign="top">

### SolveSim — case-interview simulator

Co-founder. Three Next.js apps (member dashboard, admin analytics and the simulator) with auth, Stripe billing and signed-URL launches between them. 250+ users across free and paid tiers.

<code>Next.js</code> <code>PostgreSQL</code> <code>Stripe</code> <code>Co-Founder</code>

</td>
</tr>
</table>

## 🔭 Interests

```python
interests = {
    "econometrics": ["robust inference", "panel data", "factor models", "causal inference"],
    "fintech":      ["asset management", "payments", "risk"],
    "engineering":  ["full-stack products", "database security", "testing what the tests miss"],
}
```

## 🛠️ Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black" alt="Supabase" />
  <img src="https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white" alt="Stripe" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

📍 New York City · [LinkedIn](https://www.linkedin.com/in/zorigtbaatar/) · [zk2380@nyu.edu](mailto:zk2380@nyu.edu)

<i>Interested in what happens when the person who builds the model is also the one who has to ship the product.</i>
