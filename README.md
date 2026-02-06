# Teaching-DEMO-pedagogical
# FeelGoodAI: Pedagogical Alignment Pipeline

A Research Engineer demo project implementing Direct Preference Optimization (DPO) to align Language Models with pedagogical strategies and human well-being dimensions.

## Project Overview

This repository demonstrates a complete fine-tuning pipeline designed for educational contexts. It addresses the challenge of making AI tutors not just accurate, but pedagogically effective and supportive of student well-being.

### Key Features
- **DPO Implementation**: Custom `MinimalDPO` trainer for stable preference learning without a separate reward model.
- **Pedagogical Annotation**: Automated detection of teaching strategies:
  - *Scaffolding* (breaking down complex tasks)
  - *Mastery Learning* (checking prerequisites)
  - *Collaborative Learning* (encouraging peer discussion)
- **Well-being Tracking**: Real-time monitoring of engagement, frustration, and burnout risk during training using Weights & Biases.

## Structure
- `pedagogical_dpo_demo.ipynb`: End-to-end notebook containing:
  1. Synthetic pedagogical data generation
  2. Custom DPO Trainer implementation
  3. Well-being metric integration
  4. Inference and evaluation loop

## Usage

1. Install dependencies:
```bash
pip install -r requirements.txt
jupyter notebook pedagogical_dpo_demo.ipynb
