# Progress

Two checkboxes per video. **Solo is the one that counts.** Code-along feels like
learning; rebuilding from a blank file is learning.

A video is done when you can rebuild it from an empty file, without notes or the
video, and it runs. Not when you finish watching it.

| # | Video | Along | Solo | Notes |
|---|-------|:-----:|:----:|-------|
| 01 | Building micrograd | [ ] | [ ] | |
| 02 | Building makemore (bigram) | [ ] | [ ] | |
| 03 | makemore Part 2: MLP | [ ] | [ ] | |
| 04 | makemore Part 3: Activations, Gradients, BatchNorm | [ ] | [ ] | |
| 05 | Let's build GPT from scratch | [ ] | [ ] | |

Skipped on purpose: Part 4 (Backprop Ninja) and Part 5 (WaveNet). Come back to
Part 4 later if you want it. Tokenizer and GPT-2 reproduction are out of scope.

## Schedule

Five weeks, semester starts mid-September.

| Week | Dates | Target |
|------|-------|--------|
| 1 | Aug 9 to 15 | 01 micrograd, along **and** solo |
| 2 | Aug 16 to 22 | 02 makemore bigram, along and solo |
| 3 | Aug 23 to 29 | 03 MLP, along and solo |
| 4 | Aug 30 to Sep 5 | 04 activations and gradients |
| 5 | Sep 6 to 12 | 05 build GPT, then rebuild it solo |

Four videos in five weeks. That is the correct pace. Someone who can rebuild a
small transformer unaided is ahead of most people who "completed" a
specialization.

## The rules

1. **Watch a chunk with your hands off, then type it.** Five or ten minutes,
   however long one idea takes. Then pause and write that section from memory,
   going back to the video only when stuck. Typing *while* listening is
   transcription, and it eats the attention that understanding needs.
2. Never paste code from the video. Type it.
3. Segment by segment: whiteboard derivations, just watch. Library code, use the
   watch-then-write rhythm. Debugging and tangents, just watch — you don't need
   his typos in your repo.
4. Solo rebuild happens on a **different day** to the code-along. Sleeping on it
   is doing work.
5. Failing the solo rebuild is the point, not a setback. Note what you missed in
   the table above and rebuild again.
6. Commit as you go with `./save "what you did"`. Every time something works,
   not just at the end of a session. The commit history is the portfolio
   artifact.
7. Stuck for more than 30 minutes: write the question down in LOG.md, move on,
   come back tomorrow.
8. Lost for a second time in one sitting? You have been watching longer than you
   have been doing. Stop the video and go play with the code you already have.

## Definition of done for the whole thing

You can open a blank file and write a working transformer that trains on a text
file and generates something. Then you start the rep counter.
