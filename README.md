# Growth Bridge — College Presentation Demo

A responsive child-development website prototype built with **React, TypeScript, Vite and Tailwind CSS**.

## Important: demo-only data handling

This version intentionally has **no backend, no database, no account system and no network API**. Parent/child details, diary entries and routine changes exist only in the browser's temporary React state. They disappear when the page is refreshed or closed. No form submits personal details to a server. Do not enter real personal, medical or disability information; use fictional sample details for your presentation.

The optional photo field only detects whether a file was selected. The file is **not uploaded, analysed or retained**. The AI assistant uses built-in sample responses and does not send prompts to an AI service. Therapist cards are fictional sample listings and must not be presented as real professionals.

## Features

- Landing page and responsive navigation
- Demo parent/child setup without email or password
- Temporary child profiles and dashboard
- Screen-free activities and learning games with instructions
- Activity diary with demo reflection and optional non-uploaded photo selection
- Fictional therapist directory with locality filtering
- Growth tracker based on temporary activity entries
- Editable daily routine for the current session
- Parent corner with supportive tips
- Built-in demo assistant with sample guidance

## Run on Windows

### 1. Install Node.js

Install the current Node.js LTS version from https://nodejs.org/ . This also installs npm.

### 2. Open the project

1. Extract the ZIP file.
2. Open the extracted `growth-bridge` folder in Visual Studio Code.
3. In VS Code, choose **Terminal → New Terminal**.

### 3. Install the frontend packages

In the terminal, run:

```bash
cd client
npm install
```

### 4. Start the website

Run:

```bash
npm run dev
```

Open the local address shown in the terminal, usually http://localhost:5173 . Keep the terminal running while presenting.

## Suggested presentation flow

1. Show the landing page and explain the Growth Bridge concept.
2. Select **Join Growth Bridge** and enter fictional sample details.
3. Explore the dashboard and child profile.
4. Open Screen-Free Activities and demonstrate an activity card.
5. Add a sample activity in the diary and show the generated demo reflection.
6. Demonstrate the therapist locality filter and point out that entries are fictional.
7. Show the growth tracker, daily routine and AI assistant.
8. Refresh the page to demonstrate that session data resets and is not stored.

## Limitations (intentional)

This is a college presentation prototype, not a production service. It does not provide real authentication, database persistence, real AI responses, image analysis, therapist verification or clinical assessment. Growth and activity displays are illustrative only.
