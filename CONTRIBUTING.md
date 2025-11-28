# Contributing to FutureNet

Welcome! This guide is for **non-coders contributing for the first time**.

You do **not** need to be a developer to help. These steps walk you through:

- Installing Node.js
- Setting up GitHub Desktop
- Cloning this repository
- Opening the project in an editor
- Installing dependencies
- Running the app locally (`npm run dev`)

Where possible, links point to **official GitHub documentation**.

---

## 1. Prerequisites

- A GitHub account  
  - If you don’t have one yet, sign up: https://github.com/signup
- A computer with internet access

---

## 2. Install Node.js

FutureNet uses Node.js to run the development server.

1. Go to the official Node.js download page:  
   https://nodejs.org/en/download
2. Download the **LTS** version for your operating system (recommended).  
3. Run the installer and follow the steps (accept defaults unless you know you need something different).

To confirm installation later, you can run this command in a terminal:

```bash
node -v
```

Official docs (reference):  
- Node.js downloads: https://nodejs.org/en/download

---

## 3. Install GitHub Desktop

GitHub Desktop is a beginner-friendly app for working with GitHub repositories.

1. Download GitHub Desktop from the official page:  
   https://desktop.github.com/
2. Install and open the app.
3. Sign in with your GitHub account.

Official GitHub Desktop docs:  
- Getting started: https://docs.github.com/en/desktop/installing-and-configuring-github-desktop

---

## 4. Authenticating to GitHub in GitHub Desktop

1. Open your new GitHub Desktop application
2. To keep your account secure, you must authenticate before you can use GitHub Desktop to access resources on GitHub.: https://docs.github.com/en/desktop/installing-and-authenticating-to-github-desktop/authenticating-to-github-in-github-desktop

## 5. Clone the repository with GitHub Desktop

You’ll copy the FutureNet repo from GitHub to your computer (“clone” it).

1. Go to the FutureNet demo repository:
https://github.com/ragTechDev/futurenet-demo
2. Follow GitHub’s official guide to clone the repo:  
- **Clone a repository from GitHub to GitHub Desktop**:  
    https://docs.github.com/en/desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop

After cloning, you’ll have a local copy of FutureNet on your machine.

---

## 5. Open the project in a terminal
Once cloned:

1. In GitHub Desktop, right-click the repository in the list or use the **Repository** menu.
2. Choose **Open in Command Prompt**. A terminal should appear.

## 6. Install project dependencies (`npm install`)

In the terminal, run:

```bash
npm install
```

This command reads `package.json` and downloads all required packages into a `node_modules` folder.

If this is your first time:

- It may take a few minutes, depending on your internet connection.  
- You only need to run `npm install` again when dependencies change (for example, after pulling new changes that add packages).

For reference:  
- npm documentation: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

---

## 7. Run the development server (`npm run dev`)

Once installation is complete, start the local dev server:

```bash
npm run dev
```

By default (Next.js convention), this runs the app on:

- http://localhost:3000

Open that link in your browser.

You should now see the FutureNet UI demo running locally.

Official Next.js docs (for context):  
- https://nextjs.org/docs/app/getting-started

---

# Optional Steps to Make Changes to Code in Code Editor
You can make changes to the code here, or directly in GitHub.

## 8. Edit the Code with a Code Editor
You can use any code editor. Visual Studio Code (VS Code) is popular and beginner-friendly.

- Download VS Code: https://code.visualstudio.com/
- Official VS Code docs (getting started): https://code.visualstudio.com/docs

Once installed:

1. In GitHub Desktop, right-click the repository in the list or use the **Repository** menu.
2. Choose **Open in Visual Studio Code** (or your preferred editor).

To open a terminal in the project folder (VS Code example):

1. With the project open in VS Code, open the menu **Terminal ▸ New Terminal**.  
2. This should open a terminal at the project’s root directory (where `package.json` is located).

Official GitHub Desktop docs (opening in an editor):  
- https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop#opening-your-project-in-a-text-editor

---

## 9. Make changes and see them live

As you edit files (for example `app/page.tsx`), the browser will auto-refresh.

Examples of non-coding contributions you can make:

- Copy edits (spelling, clarity, tone) in documentation
- Suggesting content changes for kid/parent-facing text
- Updating designs in documentation and noting UX improvements
- Tidying up file names, structure, or README instructions

If you’re unsure where to start, you can:

- Check the issue list on GitHub for labels like `good first issue` or `documentation`.
- Comment on an issue to ask for clarification.

Official GitHub docs on issues and pull requests:

- Issues: https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues
- Pull requests: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests

---

## 9. Create a branch and commit your changes

You don’t need to memorize Git commands; GitHub Desktop provides a visual workflow.

Follow GitHub’s official Desktop docs for detailed steps:

- **Making changes in a branch**:  
  https://docs.github.com/en/desktop/making-changes-in-a-branch

Typical flow (high-level):

1. In GitHub Desktop, create a **new branch** (e.g., `docs/update-contributing-guide`).
2. Make your edits in the editor.
3. Come back to GitHub Desktop: you’ll see a list of changed files.
4. Write a short **summary** of what you changed.
5. Click **Commit to &lt;your-branch&gt;**.

---

## 10. Push your branch and open a pull request

1. In GitHub Desktop, click **Push origin** to upload your branch to GitHub.
2. You’ll see a button or link to **Create Pull Request**.
3. This opens GitHub in your browser where you can:
   - Add a title (short description of your change)
   - Add more details in the description if needed
   - Submit the pull request

Official GitHub docs:

- Creating a pull request:  
  https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/creating-and-managing-pull-requests/creating-a-pull-request

We’ll review your pull request, give feedback if needed, and help you land your first contribution.

---

## 11. Getting help

If you get stuck at any step:

- Open an issue in the repository describing where you got stuck and what you tried.
- Include screenshots or copy-paste error messages when possible.

Official GitHub docs (general help):

- GitHub Docs home: https://docs.github.com/

Thank you for taking the time to contribute to FutureNet — especially if this is your **first ever** open-source contribution.
