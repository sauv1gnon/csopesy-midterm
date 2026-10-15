# CSOPESY Mock Midterms Exam

An unofficial self-review tool for the CSOPESY (Introduction to Operating Systems) midterms.

**Live:** https://csopesy-midterm.alt-surf.com

- **Mock exam:** 100 items drawn fresh each attempt from a 245-question bank. Answers are revealed only after you submit; results track topic mastery across attempts.
- **Practice by topic:** instant feedback, weakest areas first. Practice never changes mastery.
- **Citations:** every answer links to the lecture page it came from, with the passage highlighted.

Everything runs in one self-contained, offline-capable HTML file (`public/index.html`). Progress is stored in your browser's `localStorage`; use **Export progress** to back it up.

## Coverage

| Lecture | Bank | Per exam |
|---|---|---|
| 01 Introduction | 41 | 17 |
| 02 Operating System Structure | 43 | 16 |
| 03 I/O and Display Interfaces | 36 | 14 |
| 04 Processes | 44 | 19 |
| 05 Threads | 31 | 12 |
| 06 CPU Scheduling | 50 | 22 |

## Notes

- The lecture PDFs are **not** included in this repository, so the "Open original file" links in the Sources view won't resolve. The embedded source viewer still shows the cited text.
- Built with the [mock-exam-builder](https://github.com/aq7zo/mock-exam-builder) skill. Questions were written only from the lecture slides; verify anything doubtful against your own course materials.

## Deploy

Hosted on Cloudflare Workers (static assets):

```bash
npx wrangler deploy
```
