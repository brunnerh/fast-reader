# Instructions

After making changes to the codebase:

- Check for type issues via `deno task check`.\
  Note that this exacts script contents and the line numbers will be off from
  the source file. You might be able to reconstruct the source location by
  applying the offset of the opening `<script>` tag.
- Format code via `deno fmt`.

## UI Requirements

- Word display has to be motionless so words can be easily read.
- The highlighting of the current word in the text display must not affect
  layout for performance reasons.

## Segmentation Requirements

- Words should be split locale-aware (`Intl.Segmenter`).
- Punctuation should stay with the adjacent word.
- Punctuation of different writing systems should be considered, e.g. `。` in
  Japanese.
- Very long words are forcibly broken up.
