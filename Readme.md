📝 My List - TypeScript To-Do App
A simple and clean To-Do List application built with TypeScript and Vite, applying concepts like OOP, DOM manipulation, and Local Storage.

🚀 Features
➕ Add new tasks
✅ Mark tasks as completed
❌ Delete individual tasks
🧹 Clear all tasks
💾 Data persistence using Local Storage
⚡ Fast development with Vite

🛠️ Tech Stack
TypeScript
Vite
HTML5
CSS3
Local Storage API

📂 Project Structure
src/
│
├── main.ts # Entry point (app initialization)
├── css/
│ └── style.css # Styling
│
├── model/
│ ├── FullList.ts # Handles list logic (CRUD + storage)
│ └── ListItem.ts # Item model (id, text, checked)
│
├── template/
│ └── template.ts # DOM rendering logic

⚙️ How It Works
The app uses the Singleton pattern for:
FullList → manages application state
ListTemplate → handles UI rendering
Tasks are stored in Local Storage:
Loaded when the app starts
Automatically updated on every change
Event listeners handle:
Form submission (add item)
Checkbox toggle (mark complete)
Delete button (remove item)
Clear button (remove all items)

🧪 Getting Started

1. Install dependencies
   npm install
2. Run development server
   npm run dev
3. Build for production
   npm run build
4. Preview production build
   npm run preview

✨ Future Improvements
✏️ Edit tasks
🔍 Search functionality
📱 Improved mobile UX
🎨 Light/Dark mode

📌 Notes
Each item has a unique id
Data is stored in localStorage under the key: myList
Clear separation between logic (model) and UI (template)

👩‍💻 Author
Developed by Solafa Issa

live demo: https://first-vanilla-typescript-app.onrender.com
