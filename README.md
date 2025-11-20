# TimeTable-Optimizer

A clean and interactive web application that helps students generate a clash-free timetable based on selected courses and teachers.

This project is built using HTML, CSS, and JavaScript — no backend required.

# Features

 Select multiple courses
 Choose preferred teachers for theory and lab
 Automatically detects slot conflicts
 Generates a clean timetable grid
 Save & Load your selections
 Export timetable as PDF or Image
 Beautiful UI with icons and animations

# How It Works

User selects courses from the dropdown
Teachers for each course (theory/lab) are displayed dynamically
JavaScript checks for:
Slot clashes
Same teacher double-booked
Lab and theory overlaps
A timetable grid is auto-generated
Users can export as:
PDF (via jsPDF + html2canvas)
PNG Image

# Getting Started

1️ Clone or Download
git clone https://github.com/your-username/timetable-optimizer.git

2️ Open the Project

Just open index.html in any browser.
No installation needed ✔️

# Technologies Used

HTML5
CSS3
Vanilla JavaScript
Font Awesome (icons)
Google Fonts (Poppins)
html2canvas (for image export)
jsPDF (for PDF export)
📤 Export Options
📄 Export as PDF
Uses jsPDF + html2canvas to convert timetable to a downloadable PDF.

# Export as Image

Captures the timetable section and saves it as a PNG file.

# Sections Overview

1. Course Selection
Multi-select dropdown
Move to next page via “Continue to Teachers”

2. Teacher Selection
Dynamically populated
Save/Load Selection buttons
Reset option
Generate Timetable

3. Timetable Display
Theory & Lab color codes
Conflict highlights
Selected Teachers summary table
Export buttons

# UI Highlights

✔️ Modern card-based layout
✔️ Responsive design
✔️ Soft animations
✔️ Clean fonts and icons

# Contributing

Feel free to submit PRs to improve:
UI
Slot detection
Extra features
More course datasets

# License

This project is open-source under MIT License.

# Credits

Made with ❤️ for students who struggle with timetable planning.
