# Changelog

Every commit to Najwa's private source repository, newest first: the title only. Written by the
source repository's `scripts/sync_showcase.py`, which makes one commit here for each one there, with
its date.

## 2026-10-05

- Server engine: the page's own engine, with Whisper and the CTC model on the server (/ws/ear)
- Practice mode: the line checker (Python and JS), its bench lane, the Tarteel research
- Popularity counts: a Mafatih block no longer shares every run with its own corpus text

## 2026-10-04

- Next line on evidence, on by default; shared-passage keep and B1 removed; write-up
- Fix the switch confirmation under two position() calls; same-text scoring by the tracker's spelling

## 2026-10-03

- Tracker: switch_sure (off), and same_as stays empty while the old du'a is held
- Next-line gate v2 (still off): compare the words reached, hold through ties, skip identical text
- Shared-passage rules for the tracker, B1 for the stream decoder, jump diagnosis (all off)
- Stream decoder: evidence gate into the next line (off), bench guard, page stream settings
- Write-up: finding the du'a, the perfect-ear split, prior adopted, harvest retrains
- Tracker prior by how often each du'a is recited, on by default (0.5)
- Popularity prior (off), fairer bench scoring, harvest clip cache for Whisper training
- English for the added Mafatih texts, from duas.org's older pages
- Add Du'a al-Sabah, al-'Adeelah, al-'Asharat and Munajat 2-15 from Mafatih
- The stream decoder is the page's default; focused start; real-page check
- Stream decoder: talk filler takes blanks free and resumes anywhere; follower timing in the log
- Stream decoder: blank bias, du'a-change guard, lapse during speech; bench write-up
- Scenario bench for every way people read; stream decoder; capture clock check

## 2026-10-02

- Phone word follower, latency, stops, repeats, jumps; data harvest tooling

## 2026-09-28

- README: a results chart, a tighter front page, the new demo's caption
- Explainer on the 505-text corpus, with current results
- Demo: the app finding and following a held-out reciter, beside the sound
- README in the shape of a project front page; the depth moves to docs/
- CI: declare yt-dlp; checkout and setup-python on Node 24
- README: 505 texts; the reliability write-ups and newer modules
- Reader: favourites, "for tonight", fonts and text size, share a line
- Reliability run, step 4: Tilawa's FastConformer vs wav2vec2; wav2vec2 stays
- Reliability run, step 3: where the word follower's line lag comes from
- Reliability run, step 2: measure the phone's speech gate; legacy stays
- Reliability run, steps 0-1: a frozen manifest and label provenance
- Cap debug-session uploads; a dropped upload leaves no .part behind

## 2026-09-27

- "I'm here": a tap on a line moves the tracker and the display there
- Shared passages spelled differently count as one, for the lock too
- Hold out test venues by channel name too; read holdout files once
- transcribe_windows: don't load CTC models through the Whisper loader
- Instruction lines out of the Arabic; the last untranslated lines found
- Mend duas.org's line slips: swapped fields, late readings, blank English
- Translations and readings for the duas.org and duas.pro texts

## 2026-09-26

- Show a passage several texts share instead of withholding it
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
