# socratic-reading

English | [中文](README.cn.md)

A book-reading skill that combines Socratic questioning with Adler's levels of reading. It supports interactive co-reading, one-shot interpretation, inspectional reading, analytical reading, syntopical reading, and comprehension checks.

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

