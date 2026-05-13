# SavvySagas – Chronicle Auto-Poster

SavvySagas (Chronicle Auto-Poster) is a private studio tool that helps render and publish documentary-style videos to TikTok.

It is designed for **personal / internal use only** by the owner of this repository. The app uses the TikTok API to upload pre-rendered videos and manage posts on a connected creator account.

---

## What this project does

- Generates short, narrated videos based on documentary and storytelling scripts  
- Renders video scenes, images, and voiceovers locally  
- Uploads finished videos to a TikTok account using the TikTok API  
- Automates repetitive “post this finished video to TikTok” steps

This tool **does not** provide a public-facing service or multi-user platform. It is a workflow helper for a single creator.

---

## Data & Privacy

- The app does **not** collect, sell, or share personal data with third parties.  
- It stores only what is needed for publishing videos, such as:
  - Local render files (video, audio, images)
  - Captions and scripts
  - Basic logs for debugging

All data is stored on the owner’s own machines or configured storage.

For more details:

- **Privacy Policy**:  
  https://kzer-lab.github.io/SavvySagas/privacy.html

- **Terms of Service**:  
  https://kzer-lab.github.io/SavvySagas/terms.html

---

## TikTok API usage

SavvySagas uses the TikTok API strictly to:

- Authenticate the creator’s own TikTok account  
- Upload and publish pre-rendered video content  
- Optionally manage captions or post metadata for those videos

The app does **not** attempt to read or harvest follower data, messages, analytics, or personal information.

---

## Local development

This project is built primarily in Python and runs locally:

- Video scripts are generated and stored under a local `data` directory  
- Images and audio are rendered using external APIs (e.g. TTS, image generation)  
- Final videos are assembled and then uploaded via the TikTok API

Because this is an internal tool, there is no public signup, UI, or hosted backend.

---

## Contact

For questions about this project or the studio tool, contact:

**kzer-lab** – `youremail@example.com`
