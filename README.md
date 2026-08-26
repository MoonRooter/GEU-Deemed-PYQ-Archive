# GEU PYQ Archive

A student-contributed and maintained archive of **B.Tech Previous Year Question Papers (PYQs)** for **Graphic Era (Deemed to be University)**.

The goal of this project is to make previous year question papers easily accessible to GEU students and build a useful academic resource through student contributions.

## 📚 Available Papers

Currently, this archive focuses on:

* **University:** Graphic Era (Deemed to be University)
* **Program:** B.Tech
* **Semesters:** 1st – 8th

More papers and programs may be added in the future.

## 🤝 Contribute PYQs

Contributions are welcome!

If you have B.Tech previous year question papers that are not available in the archive, you can contribute them by opening a pull request or issue.

## 🙏 Credits

This project is based on and inspired by the original **GEHU PYQ Archive** maintained by the GEHU student community.

Original project: `https://haldwani.gehu.in/pyqs/`

---

# Local Development

## Requirements

Bun.js or Node.js >= v24.XX

## Steps

### 0. Clone the `gh-pages` branch

```sh
git clone --branch gh-pages --single-branch https://github.com/MoonRooter/GEU-PYQ-Archive.git pyqs-web
```

### 1. Change directory

```sh
cd pyqs-web
```

### 2. Clone the `main` branch

```sh
git clone --branch main --single-branch https://github.com/MoonRooter/GEU-PYQ-Archive.git pyqs-web/pyqs
```

### 3. Install dependencies

```sh
bun i
```

### 4. Run locally

```sh
bun --bun dev
```

### 5. Build

```sh
bun --bun run build
```
