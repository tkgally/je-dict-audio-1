# je-dict-audio-1

Recorded readings of the example sentences in the Japanese-English learner's dictionary at
https://www.tkgje.jp/ (source: [tkgally/je-dict-1](https://github.com/tkgally/je-dict-1)).

Each MP3 was made by a text-to-speech model (Gemini TTS) and accepted only after four AI checkers
confirmed that every word was pronounced as the dictionary's furigana say. The workflow, its
evidence and its changelog are in `AUDIO_WORKFLOW.md` in je-dict-1. The files are served by
GitHub Pages at `https://tkgally.github.io/je-dict-audio-1/`, and the dictionary links to them
through its manifest (`audio/manifest/` in je-dict-1).

- `<range>/<example id>.<hash>.mp3`: recordings, grouped by entry ID in ranges of 500, as in
  je-dict-1's `entries/` directory.
- `logs/`: every attempt, checker verdict and transcript of each recording run.
- `review/`: listening pages for spot checks by the dictionary's editor.

This repository is written by the dictionary's scheduled maintenance sessions. Do not edit it by
hand: files are named by content hash, and the manifest in je-dict-1 must match them.
