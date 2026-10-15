# RefCheck

### Does your citation actually exist?

RefCheck is a lightweight browser based citation verification tool that helps researchers, students, reviewers, and editors quickly check whether references are real.

Simply upload a PDF, paste a list of references, or enter a DOI. RefCheck searches multiple scholarly databases in real time and tells you whether each citation can be verified.

The goal is simple.

Help people catch missing, hallucinated, or incorrect references before submitting or publishing a paper.

Everything runs inside your browser and no files are stored anywhere.

## Why I built this

AI writing tools have made academic writing much faster, but they have also introduced a new problem.

Hallucinated citations.

It is surprisingly easy for language models to generate references that look completely legitimate but do not actually exist.

Manually checking dozens or hundreds of citations is time consuming and frustrating.

RefCheck automates that process.

Instead of opening multiple websites and searching one paper at a time, you can verify an entire reference list in a single place.

## Features

✅ Upload a PDF and automatically extract references

✅ Paste references in multiple citation styles

✅ Verify citations using multiple scholarly databases

✅ Detect potentially hallucinated references

✅ Support DOI and paper URL lookups

✅ Export reports as CSV or JSON

✅ Work entirely in the browser

✅ Require no account and no signup

## How it works

### Extract references

If you upload a PDF, PDF.js reads the document directly in your browser.

RefCheck locates the references section and separates individual citations.

### Search multiple databases

Each reference is searched against CrossRef, Semantic Scholar, and OpenAlex.

### Compare metadata

RefCheck compares title, authors, publication year, DOI information, and keywords.

### Generate a report

Each reference is marked as Verified, Not Found, or Uncertain.

## Privacy

Privacy was a priority from the beginning.

Your files are never uploaded to a server.

PDF processing happens entirely inside your browser.

No accounts are required.

No personal data is collected.

No documents are stored.

## Technologies used

HTML

CSS

Vanilla JavaScript

PDF.js

CrossRef API

Semantic Scholar API

OpenAlex API

No backend is required.

The project can be deployed directly on GitHub Pages.

## Who this is for

Researchers

Graduate students

PhD candidates

Peer reviewers

Journal editors

Conference organizers

Academic institutions

Anyone who wants to verify citations quickly

## Running locally

Clone the repository.

```bash
git clone https://github.com/VaskarChakma/refcheck.git

```

Open index.html in your browser.

No installation is required.

## License

This project is available under the MIT License.
