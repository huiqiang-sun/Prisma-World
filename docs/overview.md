# Project Overview

Prisma-World studies multi-agent video world modeling, where multiple agents observe and move in the same generated environment. Instead of generating each agent video independently, Prisma-World couples all agents in one denoising process and injects camera-aware relations into the generation model to improve cross-view consistency.

## Core Capabilities

**Camera control.** Prisma-World conditions generation on agent camera trajectories, enabling controllable viewpoint changes and interactive-style camera motion.

**Multi-agent consistency.** The model jointly processes multiple agent videos and uses multi-agent positional modeling and camera-aware consistency modeling to reduce inconsistent textures, layouts, and geometry across overlapping views.

**Variable agent number.** The framework supports different numbers of agents at inference time, making it suitable for 2-agent, 3-agent, and 4-agent generation settings.

**Minimap condition.** Optional minimap inputs provide top-down spatial cues, helping the model ground generated views to the surrounding scene layout.

## Resources

- Project page: https://huiqiang-sun.github.io/prisma-world/
- Paper: https://arxiv.org/abs/2606.09507
