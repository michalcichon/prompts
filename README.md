# Prompt Collection

A curated collection of specialized prompts for various AI models, organized by category and use case.

## Structure

Prompts are organized into topical directories, each containing ready-to-use prompt templates with metadata:

```
prompts/
├── audio-media/          # Audio, music, and vintage media analysis
│   └── cd-forensic-analysis.md
└── [future categories]/
```

## Categories

### 🎵 [Audio & Media](./audio-media/)
- **[CD Forensic Analysis](./audio-media/cd-forensic-analysis.md)** - Detect CD rot, bronzing, and manufacturing defects from photos

## Prompt Format

Each prompt includes YAML front matter with metadata:

```yaml
---
task: Brief description of the task
description: Detailed explanation
model_recommended: Suggested AI models
version: Prompt version number
tags: [relevant, tags, here]
---
```

## Usage

1. Browse the category folders
2. Read the prompt description in the YAML front matter
3. Copy the prompt content (excluding the front matter)
4. Paste into your preferred AI model
5. Adjust parameters as needed

## Recommended Models

Prompts are tested with:
- GPT-4o (OpenAI)
- Claude 3.5 Sonnet (Anthropic)
- Gemini 1.5 Pro (Google)

Check individual prompt metadata for specific model recommendations.

## Contributing

To add a new prompt:

1. Create or select the appropriate category folder
2. Add YAML front matter with required fields
3. Write clear, structured prompt content
4. Test with recommended models
5. Commit with descriptive message

## License

This is a personal collection. Use at your own discretion.
