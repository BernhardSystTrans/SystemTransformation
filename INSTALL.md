# Installing System Transformation Skills

These skills are designed to work with any AI tool or agent that supports the [Agent Skills](https://agentskills.io) standard. No installation needed—just point your tool to the skill files.

## Quick Start

### Option 1: Use a Single Skill URL
Most AI tools let you load a skill by its raw GitHub URL. Copy the URL for any skill you want:

- **Driving Question**: `https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/driving_question/skill.md`
- **9 Dimensions of Transformation**: `https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/9_dimensions_transformation/skill.md`
- **12 Dialectical Thoughtforms**: `https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/12_dialectical_thoughtforms/skill.md`
- **Circles of Influence & Attention**: `https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/circles_influence_attention/skill.md`
- **Integral Quadrants**: `https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/integral_quadrants/skill.md`
- **Transformational Canvas**: `https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/transformational_canvas/skill.md`

Paste the URL into your AI tool's skill loader and you're ready to go.

### Option 2: Clone the Entire Repository
If you want all skills together or plan to customize them:

```bash
git clone https://github.com/BernhardSystTrans/SystemTransformation.git
```

Then point your AI tool to the local `skill.md` files, or use the raw GitHub URLs from Option 1.

## How Skills Reference the Foundation

Each skill's `skill.md` file references the shared foundation (`base.md`) through a `base:` line in its frontmatter:

```yaml
base: https://raw.githubusercontent.com/BernhardSystTrans/SystemTransformation/main/base.md
```

Your AI tool will automatically fetch and apply the shared foundation when you load a skill. **No extra setup needed.**

## Using Skills in Popular AI Tools

### GitHub Copilot & Copilot Skills
1. Go to your skill settings or abilities configuration
2. Add a new skill by URL
3. Paste the skill URL from Option 1
4. Save and activate

### Other Agent Frameworks
If your tool supports Agent Skills standard:
1. Look for "Add Skill," "Load Ability," or "Attach Instructions"
2. Provide the skill URL or local path
3. The tool will fetch and parse the `skill.md` file

## Offline Use

To use these skills without internet access:

1. Clone the repository locally
2. In each skill's `skill.md`, update the `base:` URL to a local file path:
   ```yaml
   base: file:///path/to/SystemTransformation/base.md
   ```
3. Load skills from your local copy

## Support

- **Questions?** Check the [README.md](README.md) for an overview of all skills
- **Issues?** Open a GitHub issue or contact the author
- **License**: All skills are CC BY-SA 4.0 — feel free to adapt and share
