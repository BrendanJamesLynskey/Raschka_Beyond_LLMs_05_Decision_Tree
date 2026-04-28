# Beyond Standard LLMs 05 &mdash; When to Reach for Non-Transformer

A companion to Sebastian Raschka's article *[Beyond Standard LLMs](https://magazine.sebastianraschka.com/p/beyond-standard-llms)*. The fifth and final deck of the series &mdash; the synthesis. The first four decks introduced each architecture family in detail; this one is a practical decision tree for choosing among them in your own work.

The standard transformer is still the right default for most workloads. This deck is about when, specifically, the cost of leaving it pays for itself &mdash; with explicit caveats about what each alternative gives up, and an honest argument for keeping the standard model as the orchestrator with specialists as tools rather than full architecture switches.

Includes an **interactive decision-tree walker**: a four-question flow that asks about your workload (constraint puzzle? code execution? long context + cost-sensitive? short on-device?) and routes to a recommendation card with caveats, deeper-deck links, and a path-trail showing how you got there.

**Live site:** https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_05_Decision_Tree/

## Companion deck series

| # | Deck | Architecture family |
|---|------|---------------------|
| 01 | [Linear-Attention Hybrids](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_01_Linear_Attention_Hybrids/) | MiniMax-M1, Qwen3-Next, DeepSeek V3.2, Kimi Linear &middot; gated DeltaNet &middot; KV-cache calculator |
| 02 | [Text Diffusion Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_02_Text_Diffusion/) | LLaDA, Gemini Diffusion &middot; iterative denoising &middot; diffusion-vs-AR visualiser |
| 03 | [Code World Models](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_03_Code_World_Models/) | CWM 32B &middot; world-modelling mid-training &middot; rollout stepper |
| 04 | [Small Recursive Transformers](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_04_Small_Recursive_Transformers/) | HRM, TRM &middot; iterative self-loops &middot; recursive trace viewer |
| 05 | [When to Reach for Non-Transformer](https://brendanjameslynskey.github.io/Raschka_Beyond_LLMs_05_Decision_Tree/) | Synthesis &middot; decision-tree walker |

Part of the [Modern Architectures sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Modern_Architectures).
