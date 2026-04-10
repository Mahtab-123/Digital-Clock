# ⏰ Digital Clock

A simple and stylish **Digital Clock** built using **HTML, CSS, and JavaScript**.  
It displays the current time and updates every second in real-time.

---

## 🌐 Live Demo

https://digital-clock-24-m.netlify.app/

---

## 🚀 Features

- ⏱️ Real-time clock (updates every second)  
- 🎨 Clean and modern UI  
- 💡 Smooth hover animation  
- 📱 Responsive design  
- ⚡ Lightweight and fast  

---

## 🛠️ Tech Stack

- HTML  
- CSS  
- JavaScript  

---

## 📂 Project Structure

```
Digital-Clock/
├── index.html
├── style.css
├── script.js
```

---

## ⚙️ How It Works

- JavaScript uses `Date()` object to get current time  
- `setInterval()` updates time every second  
- Time is displayed inside a `div` element  

```javascript
const div = document.querySelector("div");

setInterval(() => {
    let time = new Date();
    div.textContent = time.toLocaleTimeString();
}, 1000);
```

---

## 🧑‍💻 Run Locally

```bash
git clone https://github.com/Mahtab-123/Digital-Clock.git
cd Digital-Clock
```

Open `index.html` in your browser

---

## 🚀 Deployment

Go to **Settings → Pages → Select main branch → Save**

Live URL:
```
https://github.com/Mahtab-123/Digital-Clock/
```

---

## 👨‍💻 Author

**Mahtab Alam**  

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!