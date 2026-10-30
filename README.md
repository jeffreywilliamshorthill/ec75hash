# Jeffrey Shorthill

I’m an independent mechanistic interpretability researcher investigating how computational structures and representations develop, persist, and change across related language models.

**Where do a language model’s internal representations come from, and how do they change as the model develops?**

[Research website](https://ec75hash.github.io/) · [Open datasets](https://huggingface.co/ec75hash) · [Contact](mailto:jws299792@icloud.com)

## Research and open evidence

- **Composition-sensitive register readouts.** E114 in Qwen3.5-35B-A3B: controlled routing experiments and causal interventions examining a readout associated with phenomenological language and its relationship to upstream representations. [Preprint](https://zenodo.org/records/21213596) · [Paper, current status, and methodological caveats](https://github.com/ec75hash/moe-routing).
- **Architectural inheritance and weight correspondence.** Repeated decoder blocks across 31 Qwen checkpoints, two Qwen-derived models, and SOLAR as a calibration control; separate studies of cross-checkpoint weights and neuronal activation responses. [Versioned dataset and reproduction materials](https://huggingface.co/datasets/ec75hash/copy-blocks-qwen/tree/v0.3.0) · [Code mirror](https://github.com/ec75hash/copy-blocks-qwen/tree/v0.3.0-mirror).
- **In-context availability and routing.** How text already available in a conversation changes expert routing with the final prompt and scored tokens held fixed. [Preprint v1.2](https://zenodo.org/records/23546831) · [Paper and correction history](https://github.com/ec75hash/in-context-availability-moe-routing) · [Versioned evidence](https://huggingface.co/datasets/ec75hash/qwen35-exact-turn-routing/tree/v1.3.1).
- **Cross-checkpoint Jacobian lenses.** Evaluating how a fitted lens transfers between related checkpoints and how its calibration changes. [Preprint v1.1](https://zenodo.org/records/22133736) · [Evaluation code and data links](https://github.com/ec75hash/jacobian-lens-transfer-qwen36-38).

[All papers and publication evidence](https://github.com/ec75hash/ec75hash/blob/main/PUBLICATIONS.md)

## Tools and exploratory studies

- [MindVolume](https://github.com/ec75hash/MindVolume) / [JVolume](https://github.com/ec75hash/JVolume): web and native macOS viewers for inspecting Jacobian-lens vocabulary projections and their capture data.
- [DeepSeek planted-answer experiments](https://github.com/ec75hash/dsv4-flash-planted-answer): a preregistered case study of responses to planted answers, with retained predictions, lens readouts, nulls, and a count-verification script.
- [Gemma SAE steering](https://github.com/ec75hash/gemma-steering-bot) and [consult-lens](https://github.com/ec75hash/consult-lens): exploratory tools for activation interventions and model access to lens measurements.

Related measurement work: [arithmetic readout sensitivity](https://github.com/jeffreywilliamportfolio/qwen36-arithmetic-readouts) · [repeated blocks and J++ readout check](https://github.com/ec75hash/qwen-depth-upscaling-jpp-check).

I publish methods, data, and findings for independent verification, criticism, and collaboration. Conclusions remain open to revision; the linked projects distinguish measured results, limitations, and exploratory interpretations. I’m self-funded, with no institutional affiliation, and welcome comparisons, replications, and notes from other researchers.

My [earlier research and software development](https://github.com/jeffreywilliamportfolio) remain available on my previous account. This is my primary research account; historical repositories and their existing links remain in place.
