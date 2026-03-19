# L-Genesis

Deriving optimal architectures from compute constraints.
Not search. Not tuning. Laws.

## Core Principle
Given budget B (bytes), the optimal transformer architecture
is derived analytically — depth, width, vocabulary.

## Application
→ OpenAI Parameter Golf: [PR #58](https://github.com/openai/parameter-golf/pull/58)
Prediction: 1-layer recurrent × 12 passes beats 9-layer static at 16MB.

*Hypothesis logged: 2026-03-19. Verification in progress.*# L-Genesis