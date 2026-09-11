## Kausar Patherya

Computer Science PhD researcher at Georgia Tech building efficient, inspectable AI systems that connect
agentic reasoning with structured, sensor, and multimodal data.

### Focus areas

**AI systems and agentic data workflows** — schema-aware typed analysis plans, validation gates,
deterministic operators, and plan reuse, so that an agent's routing, planning, and execution steps stay
inspectable instead of collapsing into opaque code generation.

**Sensor intelligence and edge AI** — transit telemetry, inertial and GPS analytics, and statistical
summarization on constrained IoT hardware, where the bandwidth and power budget is part of the problem.

**Efficient multimodal AI** — vision-language pipelines, visual-inertial robot mapping, and perception
under real hardware constraints.

### Featured projects

**[Flash-Fusion](https://github.com/kpatherya/flash-fusion)** — an edge-cloud system for expressive
natural-language queries over IoT sensor streams. Edge-based statistical summarization cuts data volume,
and cloud-based query planning turns a question into a closed-vocabulary typed plan that is validated
against the live schema and executed by deterministic pandas operators. Every answer carries its routing,
plan, validation, cache, and execution evidence.
First-author preprint: [arXiv:2511.11885](https://arxiv.org/abs/2511.11885) ·
[live demo](https://flash-fusion.vercel.app/) ·
[project page](https://kausarpatherya.com/projects/flash-fusion/index.html)

**[POLARIS](https://github.com/kpatherya/polaris)** — a staged vision-language pipeline for matching
landmarks across seasonal and lighting change. Histogram-based keyframe selection precedes OWL-ViT
open-vocabulary detection, FastVLM semantic enrichment, depth consistency checks, and keypoint/RANSAC
geometric verification. Research prototype.
[project page](https://kausarpatherya.com/projects/polaris/index.html)

**[Sting-Sense](https://github.com/kpatherya/sting-sense)** — interactive analytics for Georgia Tech
bus-route telemetry. Collected GPS and IMU route data is combined with traffic scoring, hour-based
filtering, and route-level map views to surface ride quality and congestion patterns.
[live demo](https://sting-sense.vercel.app/) ·
[project page](https://kausarpatherya.com/projects/sting-sense/index.html) ·
[write-up](https://kausarpatherya.com/2024/12/13/mci-bus-analytics/index.html)

**[SIT-UP](https://github.com/kpatherya/situp)** — a human-centered sensing prototype that computes
posture signals from front- and side-camera video, logs them over a work session, and drives audio,
vibration, and desk-adjustment intervention experiments. Tracked study artifacts are anonymized under a
published [data policy](https://github.com/kpatherya/situp/blob/main/DATA_POLICY.md).
[project page](https://kausarpatherya.com/projects/situp/index.html) ·
[write-up](https://kausarpatherya.com/2024/12/09/situp-posture-hri/index.html)

Supporting technical work: a reproducible ROS 2 visual-inertial mapping toolbox
([quad-ugv-mapping](https://github.com/kpatherya/quad-ugv-mapping)), automated curriculum design for
robotic manipulation ([AutoCaLC](https://github.com/kpatherya/autocalc)), and a comparison of deep RL
families on a shared grasping environment ([rl-kuka-arm](https://github.com/kpatherya/rl-kuka-arm)).

### Writing and demos

- Portfolio and project write-ups: [kausarpatherya.com](https://kausarpatherya.com/)
- [Georgia Tech AI Podcast](https://georgiatech.ai/) — host and producer, interviewing Georgia Tech AI
  faculty and researchers ([YouTube](https://www.youtube.com/@gatechai),
  [Spotify](https://creators.spotify.com/pod/profile/gatechai/))

### Collaboration

Open to collaboration on research software, evaluation and benchmarking, and AI systems that need to be
reproducible and inspectable — whether that means a shared benchmark, a reusable artifact, or a
co-authored paper.

### Contact

[kpatherya3@gatech.edu](mailto:kpatherya3@gatech.edu) ·
[CV](https://kausarpatherya.com/static/Kausar-Patherya-Resume.pdf) ·
[LinkedIn](https://linkedin.com/in/kpatherya) ·
[Google Scholar](https://scholar.google.com/citations?user=oW5xkPQAAAAJ&hl=en)
