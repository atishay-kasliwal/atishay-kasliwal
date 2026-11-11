<h1 align="center">Atishay Kasliwal</h1>

<p align="center">
  Software &amp; AI Engineer · New York<br />
  Building distributed systems, applied AI products, and the interfaces on top of them.
</p>

<p align="center">
  <a href="https://atishaykasliwal.com">Portfolio</a> ·
  <a href="https://www.atriveo.com">Atriveo</a> ·
  <a href="https://www.linkedin.com/in/atishay-kasliwal">LinkedIn</a> ·
  <a href="mailto:katishay@gmail.com">Email</a> ·
  <a href="https://atishaykasliwal.com/Atishay-Kasliwal-Resume.pdf">Résumé</a>
</p>

<p align="center">
  <a href="https://vimeo.com/1241118395"><img src="./assets/intro.gif" alt="Atishay Kasliwal: introduction video" width="720" /></a>
  <br /><sub>A one-minute intro. Click to watch the full video.</sub>
</p>

---

I like systems that do something useful with messy information: remember a workday, explain a readiness score, follow a job application, or find a signal in a Federal Reserve statement. I work from data model and infrastructure through the final interface, with a bias toward measurable behavior and software that can be operated after launch.

Right now I am building **[Atriveo](https://www.atriveo.com)**, a set of focused products for job search, working memory, and personal performance. I hold an **M.S. in Data Science from Stony Brook University (2026)** and previously built production software at **Bounteous**, **Wake Forest CAIR**, and **Stony Brook University**.

## Open source

Most of my recent work outside Atriveo has gone into infrastructure projects run by NVIDIA, Intuit, Red Hat and Mezmo: 33 merged pull requests across 11 repositories so far. Highlights:

- **NVIDIA · [NVKR](https://github.com/dsx-ai-factory/nvkr)**, which turns a component catalog into verifiable build and release identities for the NVIDIA Kubernetes Engine. I added four CLI features: `catalog show` explains one component ([#453](https://github.com/dsx-ai-factory/nvkr/pull/453)), `run list` lists recorded local runs ([#460](https://github.com/dsx-ai-factory/nvkr/pull/460)), `release browse` filters by kind and platform ([#469](https://github.com/dsx-ai-factory/nvkr/pull/469)), and `definition init` starts a new Definition from existing catalog tools ([#470](https://github.com/dsx-ai-factory/nvkr/pull/470)).
- **Intuit · [Numaflow](https://github.com/numaproj/numaflow)**, stream processing on Kubernetes. The controller and webhook now refuse a MonoVertex whose minimum replicas are above its maximum ([#3767](https://github.com/numaproj/numaflow/pull/3767)). I also added side input server tests to the Rust SDK ([numaflow-rs#191](https://github.com/numaproj/numaflow-rs/pull/191)) and cleaned up four docs and SDK examples.
- **[Kiali](https://github.com/kiali/kiali)**, the Istio service mesh console. Reads from a remote cluster's cache now time out instead of hanging forever, so Kiali recovers once a cluster that lost access gets it back ([#10514](https://github.com/kiali/kiali/pull/10514)).
- **Red Hat · [Keycloak](https://github.com/keycloak/keycloak), [Cockpit](https://github.com/cockpit-project/cockpit) and [mapt](https://github.com/redhat-developer/mapt)**: accessibility and theme fixes in Keycloak and Cockpit ([#54780](https://github.com/keycloak/keycloak/pull/54780), [#23897](https://github.com/cockpit-project/cockpit/pull/23897), [#23910](https://github.com/cockpit-project/cockpit/pull/23910)), and four mapt fixes, including one that locked users out of SSH on IBM Cloud ([#958](https://github.com/redhat-developer/mapt/pull/958)).
- **Mezmo · [AURA](https://github.com/mezmo/aura)**, a Rust agent runtime. Nine fixes, mostly in orchestration and event parsing, plus tool filtering, human-in-the-loop gating and CI.
- **[Mister Download Manager](https://github.com/anefzaoui/misterdownloadmanager)**: three Linux and macOS fixes, including using the system's yt-dlp ([#477](https://github.com/anefzaoui/misterdownloadmanager/pull/477)).
- **[PR-Agent](https://github.com/The-PR-Agent/pr-agent)**: a test that pins down which config keys a PR comment is allowed to override ([#4706](https://github.com/The-PR-Agent/pr-agent/pull/4706)).

[All merged pull requests →](https://github.com/pulls?q=is%3Apr+author%3Aatishay-kasliwal+is%3Amerged+-user%3Aatishay-kasliwal)

<p align="center">
  Open to full-time software engineering and AI/ML roles in the United States.<br />
  <a href="mailto:katishay@gmail.com">katishay@gmail.com</a>
</p>
