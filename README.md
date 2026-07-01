# Buttercol Proxy

<p align="center">
  <img src="./assets/Butter-col.png" alt="Buttercol Logo" width="200">
</p>

A lightweight, fast, and flexible proxy designed for simplicity, privacy, and ease of deployment.  
Buttercol Proxy is built to be minimal, hackable, and perfect for personal projects, school networks, or custom infrastructure setups.

---

## ✨ Features

- **Fast & Lightweight** — Minimal overhead, clean architecture.
- **Simple Setup** — Drop it on any machine and run.
- **Customizable** — Modify routes, middleware, or UI easily.
- **Secure** — Includes certificate support for HTTPS proxying.
- **Frontend Included** — Comes with a ready‑to‑use `public/` interface.

---

## 📁 Project Structure

```
assets/
  Butter-col.png        # Project logo
cert/                   # Certificates for HTTPS
public/                 # Frontend files (HTML, CSS, JS)
index.html              # Main landing page
server/                 # Backend server logic
src/                    # Source code for proxy internals
LICENSE                 # Open-source license
```

---

## 🚀 Getting Started

### 1. Install Dependencies
Make sure you have **Node.js** installed.

```bash
npm install
```

### 2. Run the Server

```bash
npm start
```

The proxy will start and serve the frontend from `public/`.

---

## 🔧 Configuration

Buttercol Proxy is designed to be easily configurable.  
You can adjust:

- Proxy target URLs  
- Middleware  
- Certificates (inside `/cert`)  
- UI elements (inside `/public`)

---

## 🧈 Why “Buttercol”?

Because it’s smooth, simple, and spreads easily across your network.  
Also… butter is cool.

---

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Pull requests are welcome.  
If you want to add features, improve performance, or help expand documentation, feel free to contribute.

---

## 🐛 Issues

If you encounter bugs or have suggestions, open an issue on the repository.
