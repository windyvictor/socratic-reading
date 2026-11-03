# socratic-reading

English | [中文](README.cn.md) · [Research Skillbox](https://github.com/windyvictor/research-skillbox)

A book-reading skill that combines Socratic questioning with Adler's levels of reading. It supports interactive co-reading, one-shot interpretation, inspectional reading, analytical reading, syntopical reading, and comprehension checks.

## Why this skill

Finishing pages is not the same as understanding a book. Active reading asks what problem the author addresses, how the argument is built, where it succeeds or fails, and what changes in the reader's own thinking. This skill turns those questions into a reading process matched to the available material and the reader's goal.

### What you get

- A fast inspectional map before deciding whether a book deserves deeper reading
- Interactive co-reading that responds to the reader's actual answers
- Analytical reading of terms, propositions, arguments, evidence, and structure
- Syntopical comparison across books around one question
- Recall, correction, and transfer tasks that reveal whether understanding is usable

**Workflow:** define the reading purpose → inspect the structure → reconstruct the author's argument → question and evaluate it → connect or transfer the result.

## Use it for

- Deciding whether a book deserves deeper reading
- Reading a book together, one question at a time
- Producing a complete one-shot interpretation
- Explaining a chapter, passage, or concept
- Comparing several books around one question
- Testing understanding through recall, feedback, and transfer

## Modes

Interactive co-reading waits for the reader's actual answer and gives targeted feedback. One-shot delivery completes the requested interpretation without requiring a reply. Local questions stop at the requested passage or concept.

## Contents

- `SKILL.md`: mode and reading-scope routing
- `references/adler-model.md`: four reading levels and core questions
- `references/reading-practice.md`: practical reading methods
- `references/socratic-toolkit.md`: questioning and comprehension tools
- `references/reading-feedback.md`: recall, correction, and transfer
- `assets/reading-worksheet.md`: optional worksheet
- `evals/`: behavioral cases

## Core rule

Record the material actually available. A table of contents, abstract, or single chapter cannot support claims about the whole book. “I understand” is not evidence of understanding; use an actual explanation, derivation, example, or transfer task when verification is needed.

## Install

```bash
git clone https://github.com/windyvictor/socratic-reading.git
ln -s "$PWD/socratic-reading" ~/.agents/skills/socratic-reading
```

## License

MIT. Book quotations and third-party materials retain their original rights.

