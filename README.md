# MOUTHY AI — One Chat Interface

This version puts the user experience in one chat area. Users do not need to switch pages to request songwriting help, AI art prompts, code help, project planning, or MOUTHY LIVE planning. Tool chips simply set the chat's task context.

## Access design
- Regular users see the unified chat and tool chips.
- The administrator gets extra owner controls, including developer access management, beta tester management, Live Studio access, backend setup reminders, and coming-soon feature promotions.
- The prototype's owner preview is opened with `?ownerPreview=1` appended to the URL. This is only a visual demo gate, not real security.
- Production must use secure login and enforce admin permissions on the server for every admin action.
- Plan: creator/owner has full access; up to 5 selected developer/marketing accounts may use MOUTHY LIVE; 10–15 beta testers receive full beta app access. Testers do not automatically get Live Studio unless separately approved into the five-person limit.

## Content boundaries
After Dark is on by default, with profanity, adult humor, and roast-style personality. The product boundary requested by the owner is no nudity of any kind and no sexual exploitation of people or children.

## Publish
Upload both `index.html` and `mouthy-ai-logo.jpeg` to the root of the `MouthyAI` repository. Keep GitHub Pages set to `main` and `/ (root)`. Back up your existing files first.

## Prototype limitation
This is front-end only. Replies are canned demo logic. Real model responses, authentication, role checks, persistent projects, social login, and live streaming require a secure backend and platform-approved integrations. Never put API keys in this repository.
