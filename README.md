# Portfolio Generator

**Create a personal portfolio website and a matching resume / CV PDF in a few minutes. Free, no coding, no sign-up.**

🔗 **Live app:** https://hemasri-kalaiselvan.github.io/portfolio-generator/

Fill in your details once. The generator designs a one-page portfolio website, creates your resume or academic CV as a PDF, and gives you a ZIP file that is ready to publish free on GitHub Pages, with step-by-step instructions.

---

## Who it is for

| User type | What you get |
|---|---|
| 🎓 **Student** | Portfolio website + **one-page ATS-friendly resume** |
| 💼 **Fresher** (graduated, looking for a first job) | Job-ready portfolio with an **"Open to work"** badge (target role + availability) + **one-page ATS resume** with a professional summary |
| 🏢 **Working professional** | Experience-led portfolio with **career highlights** and an optional **"Open to…"** badge + **1- or 2-page ATS resume**. Choose your field (IT, Engineering, Banking & finance, Accounts & audit, Government / PSU, Sales & marketing) and the form's labels and examples adapt. |
| 🩺 **Doctor / Healthcare** | Practice-focused site with **registration number**, qualifications, **consultation timings** (Book · Call · Directions), clinical expertise, publications and CME + **CV PDF** |
| 🧑‍🏫 **Professor / Academic** | Academic portfolio website + **full academic CV** (all pages) + **2-page summary CV** |
| 🌱 **Career break** (returning to work) | Portfolio that presents the break confidently (dated entry + what you did, reason private by default) + **ATS resume** |

Each user type's details are saved separately in your browser, so you can switch between them without losing anything.

---

## How it works: 4 steps

### 1 · Your details
- Choose **Student**, **Fresher**, **Working professional**, **Career break**, **Doctor / Healthcare** or **Professor / Academic** at the top.
- Fill in the sections. Only a few are required; everything else is optional.
- Upload a profile photo. It is cropped to a square and compressed automatically.
- Tap **✨ Fill sample data** to see a complete example first.
- A **completeness bar and checklist** show what will make your portfolio stronger.
- Everything is **saved automatically** in your browser. Use **⬇ Export backup** to keep a copy or move to another device, and **⬆ Import backup** to continue later.

### 2 · Design & preview
- **🎲 Shuffle** mixes five design parts at random, giving **12,000 possible designs**:
  - 6 layouts: Classic, Split, Sidebar, Timeline, Minimal, Bento
  - 10 colour themes, each with light and dark versions
  - 8 font styles
  - 5 navigation styles: top bar, floating pill, bottom dock, menu button, side dots
  - 5 hover and animation sets: lift, glow, 3D tilt, slide, calm
- **🔒 Lock** the parts you like and shuffle the rest.
- **Live preview** in Mobile, Tablet and Laptop sizes, in Light or Dark mode.
- Note the **design code** (e.g. `split.ocean.tech.pill.lift`) to get the exact same design back later.

### 3 · Resume / CV
- **Students and freshers:** a one-page **ATS-friendly resume**. It uses real, selectable text in a single column with standard headings, and it automatically fits on one page.
- **Freshers** also get a **Professional summary**, an optional **Work experience** section (freelance, part-time or contract work), and their availability and preferred locations on the resume.
- **Working professionals:** a **1-page or 2-page ATS resume** with Professional Summary, Key Achievements, Core Skills, Experience (choose how many achievements per role) and Key Projects. The notice period is shown only if you switch it on.
- **Doctors:** a CV (up to 2 pages, or the full CV) with your medical registration number under your name, clinical expertise, experience, training, fellowships, publications and CME.
- **Career break:** the break appears as a short dated entry in your experience, listing what you did (courses, projects, volunteering), so there is no unexplained gap. The reason is shown only if you choose.
- **Professors:** a **full academic CV** with page numbers and your name on every page, plus a **2-page summary CV** with your selected publications.
- A **check panel** gives tips: missing contact details, action verbs, DOIs, indexing and more.
- Choose A4 or US Letter, section order, and which sections to include.

### 4 · Download & deploy
- Type your **GitHub username** and choose a repository name.
- Tap **⬇ Download ZIP**. Choose the laptop layout (folders) or the phone layout (plain files).
- Follow the **7-step publishing guide** on screen. Your site goes live at `https://your-username.github.io`.

---

## Special features for professors

- **Research profiles:** Google Scholar, ORCID, Scopus, Web of Science ResearcherID, Vidwan, ResearchGate.
- **Citation metrics:** citations, h-index and i10-index, with an "as on" date.
- **📋 Publication paste box:** paste a list in IEEE or APA style, or use Google Scholar's copy format. It is split into separate entries automatically.
- **BibTeX import:** upload a `.bib` file exported from Google Scholar, Scopus, Mendeley or Zotero. This is the most accurate method.
  *Google Scholar → your profile → tick your papers → Export → BibTeX.*
- Duplicate publications are detected automatically.
- **Your own name in bold** in every author list.
- Publications are **grouped and numbered** (J1, C1, BC1…) in IEEE style, with DOI and indexing tags (Scopus, SCIE, UGC-CARE, Q1–Q4).
- Further sections: patents, funded projects and consultancy, Ph.D. and PG guidance, courses and labs handled, FDPs (organised, resource person, attended), invited talks, academic service, administrative roles, awards and memberships.
- The website includes **publication filters** (Journals / Conferences / Book chapters / ⭐ Selected) and a **Show all** button.

---

## What is inside the downloaded ZIP

```
your-username.github.io/
├─ index.html          ← your one-page portfolio website
├─ css/style.css       ← colours, fonts, layout, animations
├─ js/main.js          ← menu, dark mode toggle, scroll effects, contact form
├─ assets/img/         ← profile photo
├─ assets/resume/      ← your resume / CV PDF(s)
├─ 404.html            ← friendly page for broken links
└─ README.md           ← how to publish and update
```

Every generated portfolio includes:
- A one-page layout: Home, About, Skills / Research, Projects / Publications, Experience, Education, Highlights, Resume / CV and Contact.
- A design that works on **mobile, tablet and laptop**.
- **Light mode by default**, plus a 🌓 dark-mode toggle that remembers the visitor's choice.
- Smooth scrolling, the current section highlighted in the menu, and a back-to-top button.
- A contact form that opens the visitor's email app.
- Link-preview tags, so the site shows a proper title and description when shared.
- A link back to Portfolio Generator in the footer.

Sections you leave empty are hidden automatically.

---

## Publish your portfolio on GitHub Pages (free)

1. Download and **unzip** the ZIP file.
2. Sign in to **github.com**. If you don't have an account, create one; it's free.
3. Click **+ → New repository**. Name it exactly `your-username.github.io`, choose **Public**, then click **Create repository**.
4. Click **uploading an existing file** and upload **everything inside** the unzipped folder. `index.html` must be at the top level.
5. Click **Commit changes**.
6. Go to **Settings → Pages**. Under Source choose **Deploy from a branch**, then branch **main** and folder **/ (root)**, then click **Save**.
7. Wait 1–2 minutes, then open `https://your-username.github.io`.

> Prefer the address `your-username.github.io/portfolio/`? Choose **portfolio** as the repository name in Step 4 of the generator. The address and instructions update automatically.

### Updating your portfolio later
1. Open the generator, go to Step 1, and tap **⬆ Import backup** with your saved backup file.
2. Make your changes, then download a new ZIP.
3. In your repository: **Add file → Upload files**, drop in the new files (files with the same name replace the old ones), then **Commit changes**.

---

## Notes for doctors

Medical councils restrict self-promotion by doctors. The generator keeps doctor sites factual. Don't add patient testimonials, before/after photos, discounts, or claims like "best" or "guaranteed results", and check your State Medical Council / NMC rules before publishing. Every doctor site includes a footer note that it is not medical advice.

## Privacy

- Everything runs **inside your browser**. Your details and photo are **never uploaded** to any server.
- Data is stored only in your browser. Use **Export backup** to keep a copy.
- Your phone number is **hidden on the public website by default**, but it is still included in the PDF.
- The backup file is **not** included in the ZIP. Keep it private.

---

## Good to know

- **Internet is needed** for Google Fonts, the PDF engine (jsPDF) and the ZIP engine (JSZip). These load once from public CDNs.
- **Symbols in PDFs:** Greek letters and maths symbols (μ, Ω, α, ≤, ±) are supported. A symbol font downloads only when your CV contains them.
- **Indian scripts in PDFs:** Tamil and other Indian scripts **cannot** be shown in the PDF, and you will see a warning if any are removed. They display fine on the website.
- **No automatic Google Scholar fetch.** Google Scholar does not allow other websites to read profiles, so use BibTeX export or the paste box.
- Works in recent versions of Chrome, Edge, Firefox and Safari, on phones and computers.

---

## Host this generator yourself

The whole app is a **single file**, `index.html`, with no build step and no server.

1. Create a public repository, e.g. `portfolio-generator`.
2. Upload `index.html` and this `README.md`.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, then **main** and **/ (root)**, then **Save**.
4. Open `https://your-username.github.io/portfolio-generator/`.

### Built with
- Plain HTML, CSS and JavaScript (no framework)
- [jsPDF 2.5.1](https://github.com/parallax/jsPDF): resume / CV PDFs
- [JSZip 3.10.1](https://stuk.github.io/jszip/): ZIP download
- [DejaVu Sans](https://dejavu-fonts.github.io/): symbol font for PDFs (loaded only when needed)
- Google Fonts: Inter, Poppins, Playfair Display, Space Grotesk, DM Serif Display, Montserrat, Sora, JetBrains Mono and more

---

## Roadmap

- [x] Student portfolio + one-page ATS resume
- [x] Professor / Academic portfolio + full and summary CV
- [x] Publication paste box and BibTeX import
- [x] Fresher portfolio + one-page ATS resume
- [x] Working professional portfolio + 1- or 2-page ATS resume
- [x] Career break portfolio + ATS resume
- [x] Field presets for working professionals (Engineering, Banking, Accounts, Government / PSU, Sales)
- [x] Doctor / Healthcare portfolio + CV
- [ ] Optional AI help to improve project and bio descriptions

---

## Feedback

Found a problem or have an idea? Open an **Issue** in this repository.

© 2026 · Portfolio Generator
