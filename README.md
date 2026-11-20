# Offline Ari model releases

This repository only hosts the on-device model files for **offline Ari**, the AI listening companion in the LET IT GO Android app. The app downloads a model from the [Releases](../../releases) page when someone taps **Settings › AI mode › Download offline Ari**, and checks its SHA-256 before using it. There's no app code here.

## What the model is
Each release is Google's **Gemma 3 1B, modified (fine-tuned)** for Ari's listening style and exported for MediaPipe. The training conversations are fictional and were written with AI; no real users' messages are used.

## Licence and use restrictions
- Gemma is provided under and subject to the Gemma Terms of Use found at gemma.ai/resources/terms. See [`NOTICE.txt`](NOTICE.txt) and the copy of the terms in [`GEMMA_TERMS_OF_USE.txt`](GEMMA_TERMS_OF_USE.txt).
- You must not use these models for anything the [Gemma Prohibited Use Policy](https://gemma.ai/resources/prohibited-use/) forbids, or in breach of the law.
- Google claims no rights in the models' outputs and does not endorse LET IT GO.

## Not for emergencies
Ari is an AI, not a therapist, doctor or crisis service. In India, call Tele-MANAS on **14416** (free, any time) or **112** in an emergency.
