# nn-zero-to-hero

Working through Karpathy's *Neural Networks: Zero to Hero*, building each thing
twice: once alongside the video, once from a blank file.

Goal: be able to write a small transformer unaided, then apply it to on-device
rep counting in Volt.

## Layout

```
01-micrograd/
  along/    code written while following the video
  solo/     rebuilt from scratch on a later day, no video, no notes
```

`solo/` is the real work. `along/` is a warm-up.

## Tracking

- `PROGRESS.md` — checkboxes, schedule, rules
- `LOG.md` — one line per session, appended with `./log "what you did"`

## Setup

```bash
python3 -m venv .venv && source .venv/bin/activate
pip install numpy matplotlib torch jupyter
```

System Python here is 3.9, which is old for current PyTorch. If pip fights you,
install a newer Python (`brew install python@3.12`, or use `uv`) and point the
venv at that instead.

micrograd needs nothing but Python. Torch is not required until video 03.
