# Webcam Image Classification

A webcam image-classification demonstration using a hosted Teachable Machine model.

**Repository created:** 2021-12-21  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2021-12-21

## Features and implementation

- Capture snapshots with WebcamJS.
- Classify the captured image using ml5.
- Display the top label and confidence.

## Technologies

HTML, JavaScript, Bootstrap, jQuery, ml5.js, WebcamJS, Teachable Machine (hosted model).

## How the code works

The `take_snapshot()`, `check()` and `gotResult()` functions form the image-capture and classification flow.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |

Key functions in the source:
- `main.js`: `take_snapshot()`, `check()`, `gotResult()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/Face-recognition-project.git
cd Face-recognition-project
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Allow camera access, capture an image of a consenting test subject, and click Identify Image.

## Current status and limitations

This is a small predefined-label classifier, not general face identification or authentication. The model and referenced stylesheet may be unavailable.

## Related project snapshots

Other repositories in this project family:
- [Face_Recognition_project](https://github.com/Avenger-Sonic123/Face_Recognition_project) — repository created 2021-12-05

---

Source reference: [`f248a9d1`](https://github.com/Avenger-Sonic123/Face-recognition-project/tree/f248a9d12c572601d4d82753885f0cb86656e3ce) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
