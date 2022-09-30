# Notes App
## Tempat Menyimpan Catatan

[![N|Solid](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodesource.com/products/nsolid) [![N|Solid](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)](https://nodesource.com/products/nsolid) [![N|Solid](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://nodesource.com/products/nsolid)

Notes App merupakan sebuah aplikasi berbasis web yang dapat menyimpan catatan kita secara online.

## Features

- Menambahakan Catatan
- Menghapus Catatan
- Mengedit Catatan
- Tambahkan Pengingat untuk Catatan

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

NotesApp bekeja di beberapa teknologi seperti:

- [node.js] - I/O untuk Backend
- [Express] - Framework NodeJS
- [Eslint] - Panduan menulis kode sesuai gaya penulisan

## Installation

NotesApp membutuhkan [Node.js](https://nodejs.org/) v16+ untuk dapat berjalan.

Instalasi dependencies dan devDependencies lalu jalankan server

```sh
cd notes-app
npm install
node server.js
```

Untuk lingkungan Prosuksi...

```sh
npm install --production
NODE_ENV=production node server.js
```


## Structure

📦notes-app-back-end
 ┣ 📂src
 ┃ ┣ 📜handler.js
 ┃ ┣ 📜notes.js
 ┃ ┣ 📜route.js
 ┃ ┗ 📜server.js
 ┣ 📜.eslintrc.json
 ┣ 📜.gitignore
 ┣ 📜package-lock.json
 ┗ 📜package.json