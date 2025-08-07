# 👟 Shoe Store App — React + Git/GitHub Beginner Guide

Welcome to the **Shoe Store App**!  
We’ll build a simple React app that shows our shoe collection.  
Each person has a specific task, and we’ll use Git & GitHub to work together.

---

## 🚀 Getting Started
```bash
git clone https://github.com/username/shoe-store-app.git
cd shoe-store-app
npm install
npm run dev
```

---

## 🔄 Keeping Your Code Updated
```bash
git pull origin main
```

---

## 🌿 Working with Branches
```bash
git checkout -b feature-name
git checkout branch-name
git branch
```

---

## 💾 Saving and Pushing Your Work
```bash
git add .
git commit -m "Your commit message"
git push -u origin feature-name
```

---

## 🔀 Merging Your Work
```bash
git checkout main
git merge feature-name
```
(Or create a Pull Request on GitHub and merge there.)

---

## ⏪ Undoing Commits
```bash
git reset --soft HEAD~1
git reset --hard HEAD~1
```

---

## 🧩 Task Assignments
- **Dalitso** → Build the `Header` component (store name + navigation)
- **Jade** → Build the `ProductList` component (list all shoes)
- **Leeloo** → Build the `ContactForm` component (name, email, message fields)
- **Isaac** → Build the `ProductCard` component (hover effects + “Buy Now” button)
- **Deborah** → Build the `Footer` component (About Us + social links)

---

## 🗂 Suggested Project Structure
```
shoe-store-app/
│
├── src/
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── ProductList.jsx
│   │   ├── ProductCard.jsx
│   │   ├── ContactForm.jsx
│   │   └── Footer.jsx
│   ├── App.jsx
│   └── main.jsx
│
├── package.json
└── README.md
```

---

## 📋 Workflow Recap
```bash
# 1. Clone the repo
git clone https://github.com/username/shoe-store-app.git

# 2. Create a branch
git checkout -b feature-name

# 3. Code your component

# 4. Add & commit
git add .
git commit -m "message"

# 5. Push
git push -u origin feature-name

# 6. Open PR and merge

# 7. Pull latest changes
git pull origin main
```

💡 **Tip:** Always pull before you start coding to avoid merge conflicts!
