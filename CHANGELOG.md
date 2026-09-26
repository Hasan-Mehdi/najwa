# Changelog

Every commit to Najwa's private source repository, newest first: the title only. Written by the
source repository's `scripts/sync_showcase.py`, which makes one commit here for each one there, with
its date.

## 2026-09-26

- Names people recognise for the scraped texts; drop a font-test page
- One transliteration style for every line, from the vowelled Arabic
- Follower doc: measured GPU word-step latency on the phone server
- Follower round 2 results: gate failed on train, no test look; ?words=ctc live check
- Research notes: current-state review and execution plan (2026-09-26)
- Debug sessions and an opt-in CTC word follower in the app
- CTC word follower, round 2: lag diagnostics and line-onset options
- Fetch and cut majlis and ordinary-voice test audio
- Keep test venues and test voices out of training
- Held-out test sets beyond DuaPlayer: a registry, gold/silver tiers, review round-trip
- CTC word follower: an experiment, not wired in
- Tools for a real-user test set
- CTC stream dumps for the pause benchmark
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
