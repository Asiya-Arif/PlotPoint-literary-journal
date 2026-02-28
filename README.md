# PlotPoint&

**PlotPoint&** is a visual reading archive that transforms your Goodreads library into an interactive digital bookshelf and analytics journal.

Live Demo: https://plotpoint-dusky.vercel.app/

---

## Overview

PlotPoint& turns raw reading data into a narrative experience.  
Upload your Goodreads export and explore:

- A dynamic visual bookshelf
- Personalized reading analytics
- A journal-style reading dashboard
- Custom tagging, ratings, and notes

The project focuses on combining **data visualization + literary aesthetics**.

---

## How It Works

1. Export your Goodreads library  
   https://www.goodreads.com/review/import

2. Upload the CSV into PlotPoint&

3. The app:
   - Parses book metadata
   - Builds your visual library
   - Generates reading analytics

---

## Features

### Goodreads Import
- Upload Goodreads CSV export
- Automatic parsing of reading metadata
- Local and cloud persistence

### Visual Library
- Interactive bookshelf layout
- Filter by:
  - Read
  - Currently Reading
  - Want to Read
  - Did Not Finish
- Editable shelf labels
- Search and manual book additions

### Book Detail System
- Ratings (1–5 stars)
- Custom tags
- Notes / review editor
- Genre + series metadata

### Reading Journal Analytics
- Reading trends visualization
- Genre distribution
- Progress metrics
- Summary statistics

### Authentication & Sync
- Email/password login
- Google authentication
- Firestore cloud sync
- Local fallback storage

---

## Tech Stack

**Frontend**
- HTML5
- TailwindCSS
- Vanilla JavaScript
- Chart.js

**Backend / Cloud**
- Firebase Authentication
- Firebase Firestore

**Deployment**
- Vercel

---
