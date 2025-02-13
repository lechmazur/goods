# LLM Public Goods Game

The public goods game is a classic paradigm in experimental economics used to study cooperation and free-riding in groups. Each player decides how many tokens from a personal endowment to contribute to a common pool; the total contributions are then multiplied by a factor 𝑀 and redistributed equally to all players. Any tokens not contributed remain with the individual. Although contributing maximally can yield high payoffs for the group as a whole, each player has an incentive to “free-ride,” hoping to benefit from others’ contributions while contributing little themselves. 

This project investigates popular LLMs and their contributions. A total of 310 games were played, varying in four different multiplication factors, number of rounds, and number of players.

## Results

![average_contribution_percentage](https://github.com/user-attachments/assets/1ebaa7a2-7463-4526-99e0-c1689d121ff3)

## Contribution % Leaderboard

Sorted by average contribution percentage (descending).

| Rank | Model | Avg. % Contrib | ±SE (%) | Games |
|-----:|:------|---------------:|--------:|------:|
| 1 | Gemini 2.0 Flash Exp | 45.20% | ±2.07 | 72 |
| 2 | Claude 3.5 Haiku | 40.97% | ±1.55 | 75 |
| 3 | Gemma 2 27B | 31.16% | ±1.57 | 67 |
| 4 | Gemini 1.5 Flash | 30.20% | ±1.99 | 76 |
| 5 | GPT-4o mini | 24.82% | ±2.13 | 64 |
| 6 | Gemini 1.5 Pro (Sept) | 24.64% | ±1.88 | 71 |
| 7 | Qwen 2.5 72B | 23.59% | ±0.96 | 75 |
| 8 | Claude 3.5 Sonnet 2024-10-22 | 20.89% | ±0.99 | 77 |
| 9 | Gemini 2.0 Flash Thinking Exp 01-21 | 20.00% | ±2.73 | 41 |
| 10 | Grok 2 12-12 | 15.83% | ±1.56 | 62 |
| 11 | DeepSeek-V3 | 15.50% | ±1.47 | 79 |
| 12 | GPT-4o | 14.70% | ±1.59 | 82 |
| 13 | Llama 3.1 405B | 3.16% | ±0.76 | 70 |
| 14 | o1-mini | 2.59% | ±0.49 | 80 |
| 15 | o1 | 2.55% | ±0.47 | 70 |
| 16 | Mistral Large 2 | 1.57% | ±0.52 | 67 |
| 17 | Llama 3.3 70B | 1.24% | ±0.50 | 65 |
| 18 | Qwen 2.5-Max | 0.51% | ±0.19 | 61 |
| 19 | DeepSeek R1 | 0.31% | ±0.28 | 41 |
| 20 | o3-mini | 0.00% | ±0.00 | 47 |
| 21 | DeepSeek R1 | 0.00% | ±0.00 | 18 |

## Updates and Other Benchmarks
- Also check out the [LLM Confabulation/Hallucination Benchmark](https://github.com/lechmazur/confabulations/), [LLM Step Game](https://github.com/lechmazur/step_game), [LLM Thematic Generalization Benchmark](https://github.com/lechmazur/generalization), [LLM Creative Story-Writing Benchmark](https://github.com/lechmazur/writing), [LLM Deception Benchmark](https://github.com/lechmazur/deception) and [LLM Divergent Thinking Creativity Benchmark](https://github.com/lechmazur/divergent).
