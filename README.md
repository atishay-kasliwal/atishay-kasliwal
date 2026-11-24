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

I contribute to open-source infrastructure at NVIDIA, Red Hat, Intuit and Mezmo, and to the scientific Python stack: SciPy, statsmodels, UMAP and Nixtla.

| | Project | What I did |
|:-:|---|---|
| <img src="https://github.com/NVIDIA.png?size=128" width="44" alt="NVIDIA" /> | **[NVKR](https://github.com/dsx-ai-factory/nvkr)**<br /><sub>NVIDIA · build and release for the NVIDIA Kubernetes Engine</sub> | CLI features for exploring and releasing builds: `catalog show`, `run list`, `release diff`, `definition init` and filters for `release browse` |
| <img src="https://github.com/NVIDIA.png?size=128" width="44" alt="NVIDIA" /> | **[workload-map](https://github.com/dsx-ai-factory/workload-map)**<br /><sub>NVIDIA · maps Kubernetes workload types to one generic model</sub> | `kli` CLI features: `--sort-by` for `kli get`, the full set of `kli definitions` filters, and overridden definitions with a STATUS column |
| <img src="https://github.com/NVIDIA.png?size=128" width="44" alt="NVIDIA" /> | **[nodewright](https://github.com/NVIDIA/nodewright)**<br /><sub>NVIDIA · Kubernetes operator for node OS customizations</sub> | Replaces stale or unreadable drain blockers, and keeps the webhook Secret name in the kustomize Role in sync |
| <img src="https://github.com/keycloak.png?size=128" width="44" alt="Keycloak" /> | **[Keycloak](https://github.com/keycloak/keycloak)**<br /><sub>Red Hat · ★ 37.9k</sub> | An accessible name for the admin console's menu toggle on narrow screens |
| <img src="https://github.com/emilk.png?size=128" width="44" alt="egui" /> | **[egui](https://github.com/emilk/egui)**<br /><sub>Rust immediate-mode GUI · ★ 32.5k</sub> | The first frame gets the right content size when the zoom factor is set at startup, and `egui_kittest` copies texture readback rows whole instead of byte by byte |
| <img src="https://github.com/The-PR-Agent.png?size=128" width="44" alt="PR-Agent" /> | **[PR-Agent](https://github.com/The-PR-Agent/pr-agent)**<br /><sub>★ 16.3k</sub> | A test that pins down which config keys a PR comment can override |
| <img src="https://github.com/cockpit-project.png?size=128" width="44" alt="Cockpit" /> | **[Cockpit](https://github.com/cockpit-project/cockpit)**<br /><sub>Red Hat · ★ 15.4k</sub> | The terminal scrollbar and selected text show up in every theme again |
| <img src="https://raw.githubusercontent.com/anefzaoui/misterdownloadmanager/main/website/assets/logo-640.png" width="44" alt="Mister Download Manager" /> | **[Mister Download Manager](https://github.com/anefzaoui/misterdownloadmanager)**<br /><sub>★ 10.9k</sub> | Uses the system's yt-dlp on Linux and macOS, brings Download File Info to the front on macOS, and hides the video button after mouse focus |
| <img src="https://github.com/kiali.png?size=128" width="44" alt="Kiali" /> | **[Kiali](https://github.com/kiali/kiali)**<br /><sub>Istio service mesh console · ★ 3.6k</sub> | Remote cluster cache reads time out instead of hanging, so Kiali recovers once access returns |
| <img src="https://github.com/numaproj.png?size=128" width="44" alt="Numaflow" /> | **[Numaflow](https://github.com/numaproj/numaflow)**<br /><sub>Intuit · ★ 2.8k</sub> | Per-edge watermarks as a pipeline daemon metric, and the controller and webhook refuse a MonoVertex whose minimum replicas exceed its maximum, plus SDK tests, examples and docs |
| <img src="https://github.com/mezmo.png?size=128" width="44" alt="Mezmo" /> | **[AURA](https://github.com/mezmo/aura)**<br /><sub>Mezmo · Rust agent runtime</sub> | Orchestration fixes that keep earlier and long results and write result artifacts without a lock, plus fixes to event parsing, tool filtering, human-in-the-loop gating and CI |
| <img src="https://github.com/redhat-developer.png?size=128" width="44" alt="Red Hat" /> | **[mapt](https://github.com/redhat-developer/mapt)**<br /><sub>Red Hat</sub> | Stopped password aging from locking users out of SSH on IBM Cloud, plus fixes to runner setup, the results folder check and context handling for spot and serverless tasks |

### Data science

| | Project | What I did |
|:-:|---|---|
| <img src="https://github.com/scipy.png?size=128" width="44" alt="SciPy" /> | **[SciPy](https://github.com/scipy/scipy)**<br /><sub>★ 15.2k</sub> | `optimize.lsq_linear` no longer hangs when its trust-region step vanishes during backtracking |
| <img src="https://github.com/statsmodels.png?size=128" width="44" alt="statsmodels" /> | **[statsmodels](https://github.com/statsmodels/statsmodels)**<br /><sub>★ 11.8k</sub> | Tests for big-endian, Fortran-ordered and strided arrays at every Cython entry point, and fixes for the kernel density, exponential smoothing, VARMAX and state space code they caught |
| <img src="https://raw.githubusercontent.com/lmcinnes/umap/master/doc/logo.png" width="44" alt="UMAP" /> | **[UMAP](https://github.com/lmcinnes/umap)**<br /><sub>★ 8.3k</sub> | Parametric UMAP computes its cross-entropy loss correctly from log probabilities |
| <img src="https://github.com/Nixtla.png?size=128" width="44" alt="Nixtla" /> | **[NeuralForecast](https://github.com/Nixtla/neuralforecast)**<br /><sub>Nixtla · ★ 4.3k</sub> | Mixture distributions (PMM, GMM, NBMM) sample 1.6 to 7.6 times faster by drawing the component first |

[All merged pull requests →](https://github.com/pulls?q=is%3Apr+author%3Aatishay-kasliwal+is%3Amerged+-user%3Aatishay-kasliwal)

<p align="center">
  Open to full-time software engineering and AI/ML roles in the United States.<br />
  <a href="mailto:katishay@gmail.com">katishay@gmail.com</a>
</p>
