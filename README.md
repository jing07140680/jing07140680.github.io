# Hugo Blog Development Guide

This project is built using [Hugo](https://gohugo.io/), a fast and flexible static site generator written in Go.

## 🚀 Prerequisites

Make sure you have **Hugo (extended version)** installed on your system.

### 🧰 Install Hugo

#### Ubuntu/Debian Linux

```bash
sudo apt update
sudo apt install hugo
```

> ✅ To verify installation:

```bash
hugo version
```

## 👨‍💻 Running the Site Locally

To preview the website and see your changes in real time:

1. **Navigate to the project directory:**

   ```bash
   cd jing07140680.github.io/J-site
   ```

2. **Start the local development server:**

   ```bash
   hugo server -D
   ```

   * The `-D` flag ensures that draft posts are also shown.
   * Open your browser and go to: [http://localhost:1313](http://localhost:1313)

## 🏁 Build for Production

To generate the final static files:

```bash
hugo
```

The output will appear in the `public/` directory. You can deploy this folder to your hosting provider (e.g., GitHub Pages, Netlify).
