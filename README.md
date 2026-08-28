# System Transformation Skills

A modular library of AI agent skills for **System Transformation** practice.

Each skill is a self-contained folder with a `skill.md` file, built to the
[Agent Skills](https://agentskills.io) standard. Skills can be dropped into any
AI tool or agent that supports skills — no installation, no dependencies.

## What's inside

```
SystemTransformation/
├── base.md                      # Shared foundation: identity, exercise modes, working principles
├── README.md                    # This file
├── LICENSE.md                   # CC BY-SA 4.0
├── driving_question/
│   └── skill.md
├── 9_dimensions_transformation/
│   └── skill.md
├── 12_dialectical_thoughtforms/
│   └── skill.md
├── circles_influence_attention/
│   └── skill.md
├── integral_quadrants/
│   └── skill.md
└── transformational_canvas/
    └── skill.md
```

## How the skills work

- Every skill stands on a shared foundation held in **base.md** — the identity,
  the exercise modes, and the working principles common to all models.
- A skill's `SKILL.md` does not copy that foundation. It references it through
  a `base:` line in the frontmatter at the top of the file:

  ```yaml
  ---
  name: driving_question
  description: Drives a client to their core question.
  base: https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/base.md
  ---
  ```

## Getting Started

Each skill folder contains a `skill.md` file with:
- The model description
- How to use it
- Exercises and coaching prompts
- Exercises modes (Roleplay, Case Analysis, Teaching & Practice, Advising)

## License

All skills in this repository are licensed under **CC BY-SA 4.0**.
See [LICENSE.md](LICENSE.md) for details.
