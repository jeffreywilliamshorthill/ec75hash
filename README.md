# Jeffrey W. Shorthill

Independent mechanistic interpretability researcher investigating how computational structures and representations develop, persist, and change across language models.

**Central research question:** Where do a language model's internal representations come from, and how do they change as the model develops?

My research combines structural weight analysis, mixture-of-experts routing, Jacobian lenses, and causal interventions to investigate how internal computations relate to model behavior.

[Research Website](https://ec75hash.github.io/) · [ORCID](https://orcid.org/0009-0004-3954-2752) · [Publications](PUBLICATIONS.md) · [Hugging Face](https://huggingface.co/ec75hash)

## Selected Research

### Mechanistic Interpretability

**1. In-Context Availability and Expert Routing**

Demonstrates how the availability of previously encountered text reorganizes MoE routing, even with target tokens and final prompts held fixed. Includes controlled experiments, cross-checkpoint replication, and corrected, dispatch-verified causal interventions.

[Paper (v1.2)](https://doi.org/10.5281/zenodo.23546831) · [Code & Methods](https://github.com/ec75hash/in-context-availability-moe-routing)

**2. Architectural Inheritance in Qwen**

Identifies repeated decoder-block weight patterns across Qwen checkpoints and investigates structural correspondence, neuronal responses, and functional divergence. Includes pinned revisions, tensor hashes, measurement tables, and reproducibility tools.

[Archived Dataset](https://doi.org/10.5281/zenodo.23546828) · [Current Dataset](https://huggingface.co/datasets/ec75hash/copy-blocks-qwen) · [Code](https://github.com/ec75hash/copy-blocks-qwen)

**3. Cross-Checkpoint Jacobian Lens Transfer**

Investigates whether fitted Jacobian lenses retain useful intermediate representations across related model versions. Finds that semantic readouts can survive checkpoint changes while calibration and depth-dependent performance diverge.

[Paper](https://doi.org/10.5281/zenodo.22133736) · [Code & Evaluations](https://github.com/ec75hash/jacobian-lens-transfer-qwen36-38)

### Routing, Evaluation, and Safety

**4. Expert Specialization During Generation**

Shows that generation-time expert sets track the local subject of model outputs, revealing specialization that pooled prefill measurements can obscure.

[Paper](https://doi.org/10.5281/zenodo.22236999) · [Code & Evidence](https://github.com/ec75hash/paper-expert-specialization-generation)

**5. Dialect-Marked Response Audit (DMRA)**

Develops a matched-pair evaluation protocol to isolate linguistic features contributing to differences in safety-critical assistance, including responses to AAVE-marked prompts.

[Paper](https://doi.org/10.5281/zenodo.22291463) · [Methods & Artifacts](https://github.com/ec75hash/dmra-paper)

**6. Distributed Safety Routing**

Investigates whether refusal behavior depends on individual MoE experts. In a controlled case study, suppressing the leading refusal-associated expert index redistributes routing while refusal behavior persists.

[Paper](https://doi.org/10.5281/zenodo.22088890) · [Code & Evidence](https://github.com/ec75hash/distributed-safety-routing)

---

## Open Research

I conduct this work independently and publish methods, measurements, code, and reproducibility materials wherever possible. My releases document experimental limitations, methodological corrections, and negative or null findings to support independent verification and criticism.

I welcome research collaboration, independent replication, and feedback on experimental methodology.

[Full Publication Index](PUBLICATIONS.md) · [Research Website](https://ec75hash.github.io/) · [Contact](mailto:jws299792@icloud.com)
