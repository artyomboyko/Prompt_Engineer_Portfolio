# Prompt Engineering Portfolio

<p align="center">
  <strong>Structured prompting for text, image, video, multimodal workflows, reasoning patterns, and AI-agent interactions.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Prompt%20Engineering-Portfolio-6F42C1" alt="Prompt Engineering">
  <img src="https://img.shields.io/badge/Multimodal-Text%20%7C%20Image%20%7C%20Video-0969DA" alt="Multimodal prompting">
  <img src="https://img.shields.io/badge/ReAct-Tool%20Use%20%7C%20Constraints-2DA44E" alt="ReAct and tool use">
</p>

This repository is a public portfolio of my prompt-engineering work across **text generation**, **image generation**, and **video generation**.

The focus is not on isolated one-line prompts, but on designing structured instructions, reusable prompting patterns, refinement loops, tool-selection strategies, and multimodal workflows that make model behavior more predictable and useful for a concrete task.

## What this portfolio demonstrates

- **Zero-shot, one-shot, and few-shot prompting** for different task formats.
- **Multimodal prompt design** across text, image, and video generation.
- **Negative prompting** for controlling unwanted visual or video characteristics.
- **Reasoning-oriented prompting patterns**, including Chain-of-Thought-style task decomposition, self-consistency, and self-refinement.
- **Meta prompting** for generating or improving prompts through higher-level instructions.
- **ReAct-style workflows** that combine reasoning with actions or external tools.
- **Tool-selection strategies** for choosing the appropriate capability for a task.
- **Constraint prompting** for enforcing structure, boundaries, formats, and predictable outputs.

## Portfolio sections

| Area | Notebook | Focus |
|---|---|---|
| **Text generation** | [`1_Text_generation/Prompts.ipynb`](1_Text_generation/Prompts.ipynb) | Structured prompting patterns for text tasks, reasoning, refinement, and agent-oriented workflows. |
| **Image generation** | [`2_Image_generation/Prompts.ipynb`](2_Image_generation/Prompts.ipynb) | Prompt construction for image generation, including multimodal and negative-prompting patterns. |
| **Video generation** | [`3_Video_generation/Prompts.ipynb`](3_Video_generation/Prompts.ipynb) | Prompt design for video-generation workflows and controlled visual output. |

## Prompt-engineering approach

### Fundamental prompting

The portfolio includes examples of **zero-shot**, **one-shot**, and **few-shot** prompting, where task behavior is shaped either directly through instructions or through examples embedded in context.

### Iterative reasoning and refinement

Some tasks use structured reasoning and refinement patterns such as:

- decomposing a complex task into explicit steps;
- generating multiple candidate approaches;
- checking outputs against constraints;
- iteratively revising a result;
- separating planning from the final requested output.

### Agent and tool-oriented prompting

The repository also covers prompt patterns for systems where the model must do more than generate text. These include **ReAct**, tool-selection strategies, and explicit constraints that help an agent decide what action to take and what output contract to follow.

## Models and modalities

The examples were created across a range of AI systems and modalities. The original portfolio includes work with services and model families such as **Gemini**, **ChatGPT**, **Qwen**, **DeepSeek**, **DALL-E**, **Sora**, **Veo**, **Suno**, and **MiniMax**, among others.

The exact model is secondary to the main goal of the repository: showing how prompting patterns can be adapted to different interfaces, modalities, and task requirements.

## White Label / NDA policy

> A significant part of the work represented here originated from real commercial tasks. To respect confidentiality and NDA requirements, those examples are published in **White Label** form: the structure, prompt architecture, and solution logic are preserved, while confidential names, data, and identifying details are replaced or removed.

This allows the portfolio to demonstrate the underlying engineering approach without exposing client information.

## Repository structure

```text
Prompt_Engineer_Portfolio/
├── 1_Text_generation/
│   └── Prompts.ipynb
├── 2_Image_generation/
│   ├── Prompts.ipynb
│   └── img/
├── 3_Video_generation/
│   └── Prompts.ipynb
├── LICENSE
└── README.md
```

## Contact

- **Email:** [blademoon05@gmail.com](mailto:blademoon05@gmail.com)
- **LinkedIn:** [Artyom Boyko](https://www.linkedin.com/in/artyom-boyko/)

## License

This repository is licensed under the **Apache License 2.0**.
