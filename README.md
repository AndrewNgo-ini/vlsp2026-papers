# VLSP 2026 papers (team WiTake)

Papers by Hieu Ngo, Thuan Nguyen and Huy Nguyen (Trivita AI) for the 12th Workshop on Vietnamese Language and Speech Processing (VLSP 2026), Ho Chi Minh City, November 2026.

## What Transfers and What Does Not: An Audio-Encoder Ensemble for Speech Quality Assessment and Fault Localisation

**Second Rank, Speech Quality Assessment shared task.** [PDF](ngo2026-speech-quality-assessment.pdf)

An ensemble of 14 fine-tuned audio encoders (Qwen2-Audio and WavLM-Large) that predicts an overall quality score and localises noise, distortion and unnatural pauses in Vietnamese speech, trained only on English data. The paper measures which abilities transfer across languages and which do not.

## Judge-Guided Generation, Selection and Repair of Inline Non-Verbal Sounds in Vietnamese Speech Synthesis

**Second Rank, Vietnamese Non-Verbal TTS for Conversational Synthesis shared task (Track B).** [PDF](ngo2026-nonverbal-tts.pdf)

A Vietnamese text-to-speech system that renders inline tags such as laughter, breathing, sniff and throat clearing at the tagged position, built as a generate–judge–repair loop around a fine-tuned masked TTS model with class-aware preference optimisation.

## Citation

```bibtex
@inproceedings{ngo2026sqa,
  title     = {What Transfers and What Does Not: An Audio-Encoder Ensemble for Speech Quality Assessment and Fault Localisation},
  author    = {Ngo, Hieu and Nguyen, Thuan and Nguyen, Huy},
  booktitle = {Proceedings of the 12th Workshop on Vietnamese Language and Speech Processing (VLSP 2026)},
  year      = {2026}
}

@inproceedings{ngo2026nvtts,
  title     = {Judge-Guided Generation, Selection and Repair of Inline Non-Verbal Sounds in Vietnamese Speech Synthesis},
  author    = {Ngo, Hieu and Nguyen, Thuan and Nguyen, Huy},
  booktitle = {Proceedings of the 12th Workshop on Vietnamese Language and Speech Processing (VLSP 2026)},
  year      = {2026}
}
```
