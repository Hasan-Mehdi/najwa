# Changelog

Every commit to Najwa's private source repository, newest first: the title only. Written by the
source repository's `scripts/sync_showcase.py`, which makes one commit here for each one there, with
its date.

## 2026-09-26

- Harvest Al-Fatemah IC streams and cut the du'as out of them

## 2026-09-25

- README and results for the 506-text corpus and the new phone model
- Phone app: switch to the whisper-base fine-tune trained on more voices
- Write up the pause handling (docs/results/pauses.md)
- Grow the corpus from 91 to 506 du'as and ziyarat; more training audio
- Follow pauses, unknown du'as and ordinary voices; align 30x faster
- Rework the explainer: an introduction, then one idea at a time
- Research a noha mode: language ID, cross-script lyrics matching, fine-tunes
- Redo the explainer in 3Blue1Brown style
- Add feature demo and Manim explainer animations to the README
- Rebuild as a live du'a follower: HMM score-following tracker, fine-tuned Whisper, on-device web app

## 2026-06-28

- initial commit
