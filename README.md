# CosmoNotes – Day 1 Progress Log
# CosmoNotes – Space-Themed Note-Taking App

A simple, elegant note-taking web application designed for the Agnirva Software Internship (Summer 2025). Users can write and store personal notes with a sleek UI. Future versions will integrate NASA’s Astronomy Picture of the Day (APOD) API to provide educational and space-themed enhancements.

---

## Day 1 Progress Log

### Features Implemented:
- Created project structure with `index.html`
- Implemented basic note creation and display
- Notes are saved to `localStorage` and persist on reload
- Simple and clean space-themed UI using inline CSS

### Challenges Faced:
- Ensuring localStorage data persisted correctly between sessions
- Displaying updated notes after each addition (fixed with `displayNotes()` call)

### Next Steps:
- Add delete/edit functionality to notes
- Integrate NASA APOD API
- Improve UI and responsiveness

---

## Tech Stack:
- **HTML, CSS, JavaScript (Vanilla)**
- **Storage**: `localStorage`
- **API (upcoming)**: NASA APOD API

---

##  Day 2 Progress Log

### Features Implemented:
- Added **Delete Note** functionality  
- Added **Edit Note** functionality  
- Notes can now be updated or removed after creation  
- `localStorage` integration ensures notes persist even after page reload  
- Updated the “Add Note” button dynamically to say “Update Note” during editing

---

### Challenges Faced:
- Managing edit state: required maintaining an `editId` to track which note is being edited  
- Re-rendering note list correctly after update/delete without losing state  
- Ensuring clean UX toggle between “Add Note” and “Update Note” during edit operations

---

### Tech Stack Used:
- **HTML, CSS, JavaScript (Vanilla)**  
- **Data Storage:** `localStorage` (client-side)

---

### Next Steps:
- Integrate NASA’s **Astronomy Picture of the Day (APOD)** API at the top of the app  
- Fetch and display the latest space image and explanation from NASA  
- Polish UI further to match the space theme  

---

## Day 3 Progress Log

### Features Implemented:
- Integrated NASA’s **Astronomy Picture of the Day (APOD)** API
- Fetched and displayed the daily space image with title and explanation
- Added **timestamp** to each note upon creation
- Polished the UI with a modern space-themed design:
  - Rounded note cards and input boxes
  - Hover effects on buttons
  - Dark background with vibrant accent colors

---

### Challenges Faced:
- Styling alignment issues across devices (fixed using better padding/margins)
- Managing notes created without timestamps (resolved using fallback in HTML rendering)
- Ensured APOD media fetch was robust using error handling

---

### Tech Stack Used:
- **HTML, CSS, JavaScript (Vanilla)**
- **Data Storage:** Browser `localStorage`
- **Space API:** NASA APOD (via `api.nasa.gov`)

---

### Completed Tasks Summary:
- Finalized note creation, editing, and deletion
- Implemented localStorage-based persistence
- Successfully integrated space-related feature
- Fully functional and visually complete app

---

# CosmoNotes – A Space-Themed Note-Taking App

CosmoNotes is a simple, modern note-taking web application that lets users write, edit, and delete notes. What makes it unique is its integration with NASA’s **Astronomy Picture of the Day (APOD)** API — combining productivity with cosmic inspiration.

---

## ✅ Features

- Add, edit, and delete notes
- Save notes to `localStorage` so they persist across sessions
- Display the current NASA Astronomy Picture of the Day (APOD)
- Responsive and space-themed UI
- Timestamps for all notes

---

## 🛠️ Technologies Used

- **HTML, CSS, JavaScript (Vanilla)**
- **NASA APOD API** for space integration
- **localStorage** for client-side persistence

---

## 🧪 Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CosmoNotes.git
   ```
2. Open the project folder:
   ```bash
   cd CosmoNotes
   ```
3. Open `index.html` in your browser

> No build or dependencies required – it’s a single static HTML file.

---

##  Screenshots

![Home Page](screenshots/home.png)  
![Add Note](screenshots/add.png)  
![Delete Note](screenshots/delete.png)  
![Edit Note](screenshots/edit.png)  
![NASA APOD](screenshots/apod.png)

---

##  License

This project is licensed under the **MIT License** – feel free to use and modify.

---

## Day 4 Progress Log

### ✅ What Was Done:
- Final polish and bug testing completed
- Timestamp added to notes
- Modern CSS theme added for better usability
- NASA APOD section visually improved
- Final version tested across multiple browsers
- README.md finalized with setup guide, screenshots.

---

## 🌐 Live Demo

🔗 [Click to View CosmoNotes Live](https://cosmo-notes.vercel.app/)
