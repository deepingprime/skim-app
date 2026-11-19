# Risk Mitigation & Technical Constraints

## Core Technical Risks
- **Highest Risk Feature:** `Audio File Upload` & Live Transcription
- **The Hazard:** Messaging apps save voice notes in different audio formats (like `.opus` or `.ogg`) and large files can cause slow API responses, serverless timeouts, or rate-limit errors.

## The Pivot Strategy
If our primary implementation for this feature fails or takes too long, our backup plan is to:
1. Limit v1.0 uploads to `.mp3` and `.m4a` files under 10MB (about 10 minutes of audio) to avoid timeout and format conversion issues.
2. Add pre-loaded sample voice notes with cached transcripts on the homepage so anyone testing the app can still try the summary feature if the live transcription API hits a limit.
