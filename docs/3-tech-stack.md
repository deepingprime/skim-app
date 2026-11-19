# Tech Stack & Hosting Strategy

## Defined Tech Stack
- `Next.js (React + TypeScript)`: Used for building the web interface and handling backend API requests safely.
- `OpenAI Whisper API`: Used to transcribe uploaded voice message audio into text.
- `OpenAI GPT-4o-mini API`: Used to turn raw transcripts into concise bullet points and action items.
- `Tailwind CSS`: Used to style a simple, mobile-friendly layout quickly.

## Hosting & Deployment Strategy
The app will be deployed on **Vercel** linked directly to the `main` branch of `github.com/deepingprime/skim-app`. Pushing updates to `main` automatically deploys the live web app to a public HTTPS link, making it usable on mobile and desktop browsers immediately without going through App Store review.
