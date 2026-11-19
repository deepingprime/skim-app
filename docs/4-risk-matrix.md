# Major Risk and Contingency Plan

## Greatest Technical Risk
- **Riskiest Feature:** Audio File Upload and Transcription
- **What Could Go Wrong:** Messaging applications have numerous options for saving voice messages (in .opus or .ogg format, for example), and huge audio files could cause transcription API to slow down or timeout or go over its usage rate.

## Contingency Plan
In case there are too many bugs when handling such a variety of audio formats or big files, I would do the following:
1. Support only .mp3 and .m4a files under 10 MB size (approx. 10 minutes of audio file) initially to avoid timeouts and failure of file upload/ conversion.
2. Have a couple of predefined voice messages with saved transcripts on the landing page to let users check out the transcript summarizing feature regardless of the API limitations.
