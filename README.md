# Design Thinking Studio

A free, mobile-first educational web app that helps students practice three core Design Thinking methods:

- **Persona**
- **Empathy Map**
- **Customer Journey Map**

Students answer guided questions, receive structured guidance built from their own notes, and can ask clarifying questions in a simple Q&A panel.

**No login. No server. Works fully offline after the first load.** Notes are saved in the browser (localStorage).

---

## Live Demo (GitHub Pages)

Once you enable GitHub Pages (see below), the app will be available at:

```
https://amalendhusp.github.io/DesignThinking/
```

(Replace with your exact username/repo if different.)

---

## How to use (for students)

1. Open the link on a phone or computer.
2. Go through the three tabs one by one.
3. Answer the questions as thoughtfully as you can.
4. Tap **Generate Guidance** — the app will show you how to turn your notes into a proper Persona / Empathy Map / Journey Map.
5. Use the **Ask** button at the bottom if you need help with concepts.

You can reset your notes anytime with the Reset button in the top-right.

---

## How to add this to your GitHub repository

### Option A – Upload via GitHub website (easiest)

1. Go to your repository:  
   https://github.com/Amalendhusp/DesignThinking
2. Click **Add file → Upload files**
3. Drag and drop these two files into the root of the repository:
   - `index.html`
   - `README.md`
4. Commit the changes (message example: `Add Design Thinking Studio web app`).

### Option B – Using Git on your computer

```bash
git clone https://github.com/Amalendhusp/DesignThinking.git
cd DesignThinking
# copy index.html and README.md into this folder
git add index.html README.md
git commit -m "Add Design Thinking Studio web app"
git push origin main
```

---

## Enable GitHub Pages (so students can open it)

1. Go to:  
   https://github.com/Amalendhusp/DesignThinking/settings/pages
2. Under **Source**, choose:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
3. Click **Save**.
4. Wait 1–2 minutes.
5. Your live link will appear at the top of the same page, usually:

   ```
   https://amalendhusp.github.io/DesignThinking/
   ```

Share that link with your students.

---

## Features

- Mobile-first, modern and clean interface
- Guided questions for each method
- Progress indicators
- Automatic synthesis that re-uses the student’s own words
- Follow-up prompts when more information is needed
- Simple Q&A panel with answers about design-thinking concepts
- Fully client-side (privacy-friendly, works offline)

---

## License

Feel free to use, share and modify for educational purposes.
