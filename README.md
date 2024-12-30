# Text Editor using Draft.js
# Draft.js Custom Editor with Vite

This project implements a custom text editor using **Draft.js** with the following features:
- Typing special characters (`#`, `*`, `**`, `***`) as the first string in a line applies specific text formatting.
- Saves editor content to `localStorage` and reloads it upon refresh.

---

## ✨ Features
1. **Heading Format**: Typing `#` followed by a space converts the line to a heading.
2. **Bold Format**: Typing `*` followed by a space makes the text bold.
3. **Red Text**: Typing `**` followed by a space makes the text red.
4. **Underline Format**: Typing `***` followed by a space underlines the text.
5. **Persistence**: The editor content is saved in `localStorage`. Refreshing the page restores the saved content.

---

## 🚀 Installation

### Prerequisites
Ensure you have the following installed:
- Node.js (>=14.x)
- npm or yarn

### Steps
1. Clone the repository:
   git clone <repository_url>

2. Navigate to the project directory:
   cd draftjs-editor
   
3. Install Dependencies
   npm install
   
4. Run the Server
   npm run dev


## Project Structure
├── src

│   ├── App.jsx         # Main application component

│   ├── Editor.jsx      # Custom Draft.js editor logic

│   ├── styles.css      # Styling for the editor

│   └── main.jsx        # Entry point for Vite

├── public

│   └── index.html      # Main HTML file

├── package.json        # Project dependencies and scripts

├── vite.config.js      # Vite configuration

└── README.md           # Project documentation

## Usage
Start typing in the editor.
Use special characters (#, *, **, ***) as the first character on a line for formatting.
Press the Save button to save your content.
Refresh the page to see the content restored.

