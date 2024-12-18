# athena

(Work-in-progress)

Athena: Safe Autonomous Agents with Verbal Contrastive Learning

Abstract. Due to emergent capabilities, large language models (LLMs) have been utilized as language-based agents to perform a variety of tasks and make decisions with an increasing degree of autonomy. These autonomous agents can understand high-level instructions, interact with their environments, and execute complex tasks using a selection of tools available to them. As the capabilities of the agents expand, ensuring their safety and trustworthiness becomes more imperative. In this study, we introduce the Athena framework which leverages the concept of verbal contrastive learning where past safe and unsafe trajectories are used as in-context (contrastive) examples to guide the agent towards safety while fulfilling a given task. The framework also incorporates a critiquing mechanism to guide the agent to prevent risky actions at every step. Furthermore, due to the lack of existing benchmarks on the safety reasoning ability of LLM-based agents, we curate a set of 80 toolkits across 8 categories with 180 scenarios to provide a safety evaluation benchmark. Our experimental evaluation, with both closed- and open-source LLMs, indicates verbal contrastive learning and interaction-level critiquing improve the safety rate significantly.

Link to arXiv: https://arxiv.org/abs/2408.11021

Accepted at EMNLP 2024 Industry Track

```
@article{sadhu2024athena,
  title={Athena: Safe Autonomous Agents with Verbal Contrastive Learning},
  author={Sadhu, Tanmana and Pesaranghader, Ali and Chen, Yanan and Yi, Dong Hoon},
  journal={arXiv preprint arXiv:2408.11021},
  year={2024}
}
```
