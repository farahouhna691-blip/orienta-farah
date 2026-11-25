# orienta-farah

> **Status:** Work in Progress (`v0.1`) — Active development. Presentation deck (PPT) and technical report are planned next.

A browser-based post-graduation orientation assistant designed to help students explore study paths, analyze transcripts, and prepare for entrance exams with multi-language support.

## Current Features (`v0.1`)
- **7-Step Diagnostic Flow**: Progressive questions covering academic background, learning style, interests, work preferences, career priorities, and study duration.
- **Personalized Guidance Summary & Follow-Up Q&A**: Generates a structured summary and answers tailored follow-up questions.
- **Grade Sheet Analysis**: Supports importing `.pdf` (text extraction and page rendering via `pdf.js`), images (`.png`, `.jpg`, `.jpeg`, `.webp`), and text/data files (`.txt`, `.csv`, `.json`) to highlight strengths/weaknesses, relevant schools/tracks, and exam preparation priorities.
- **Multi-Language Support**: Full interface and prompt support in French (`FR`), Arabic (`AR` with RTL layout), and English (`EN`).
- **API Provider & Model Selection**: Supports Groq and Gemini APIs with model listing, key validation, and error handling.

## Roadmap / Upcoming
- Finalize presentation slides (PPT) and technical report.
- Refine grade sheet parsing and school/exam guidance depth.
- Add UI polish and additional test cases.

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript (`fetch`, `FileReader`)
- `pdf.js` for PDF reading
- Groq & Gemini REST APIs

## Usage
1. Open `index.html` in a web browser.
2. Choose your preferred language (`Français`, `العربية`, `English`).
3. Select an API provider (`Groq` or `Gemini`), enter your API key, check/test the model, and click **Start**.
