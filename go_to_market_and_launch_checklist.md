# Go-To-Market & Launch Checklist

## Marketing & User Acquisition
- **Primary Launch Channel:** University student group chats (LINE and Discord), campus study groups, and Reddit (`r/SideProject`, `r/productivity`).
- **Value Proposition:** Read a 4-minute voice note in 5 seconds without putting your headphones on.

## Pre-Launch Deployment Checklist
- [ ] Verify all code changes are merged into the `main` production branch
- [ ] Test audio file uploads and error messages for unsupported or oversized files
- [ ] Run a cross-browser usability check (Chrome, Safari, and mobile screens)
- [ ] Check that API keys are stored in environment variables and not committed to GitHub

## Launch Day Operations
- [ ] Trigger final deployment script on Vercel and check the live production URL
- [ ] Conduct live verification testing directly on the hosted platform using a real voice note
- [ ] Post the announcement and demo link across primary student channels