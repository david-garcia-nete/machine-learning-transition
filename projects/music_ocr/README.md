# Music OCR / Sheet Music to MusicXML

## Purpose

Explore computer vision and structured output by converting sheet music images into a symbolic representation such as MusicXML. This is an ambitious project that can showcase deep learning, data challenges, evaluation complexity, and domain-specific modeling.

## Problem Framing

Potential question: can a system detect musical notation elements from sheet music and convert them into a structured, editable format?

No dataset is assumed. This project requires careful investigation of data availability, annotation formats, licensing, and evaluation methods.

## Possible Approaches

- Research existing optical music recognition workflows
- Start with symbol detection or staff-line detection as a constrained subproblem
- Use image preprocessing and classical computer vision baselines
- Explore convolutional or transformer-based vision models later
- Convert recognized components into a structured representation

## Evaluation Ideas

- Symbol detection precision and recall
- Staff and measure detection accuracy
- Edit distance between predicted and reference symbolic output
- Qualitative review on progressively harder examples

## Milestones

- [ ] Define a narrow first version, such as detecting staff lines or noteheads.
- [ ] Investigate available datasets and licensing.
- [ ] Identify baseline computer vision techniques.
- [ ] Document MusicXML structure at a high level.
- [ ] Decide whether this is a primary or long-horizon project.

## Next Actions

- [ ] Write a research note on optical music recognition.
- [ ] Identify the smallest useful milestone.
- [ ] Create an evaluation plan before attempting advanced models.
