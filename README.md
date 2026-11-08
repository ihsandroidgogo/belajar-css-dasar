Install
```
npm install tailwindcss @tailwindcss/cli
```

Build Process
```
npx @tailwindcss/cli -i style.css -o output.css --watch
```

Server
```
npx lite-server .
```

Responsive Design

Untuk "grid-cols-1" buat tampilan mobile
Untuk "lg:grid-cols-3" untuk tampilan desktop

Untuk menampilkan hamburger menu hanya di mobile saja :
```
<button class="md:hidden">Mobile Menu</button>
```

Dark Mode

Cara ngetest nya :
- Buka Inspect Element
- Ctrl+Shift+p
- Pilih "Show Rendering"
- Pilih Emulate css media feature prefers-color-scheme
- Disitu bisa test tema light dan tema dark nya

Tambahkan juga di VSCode nya untuk Prefences JSON nya jadi seperti ini :

```
{
  "workbench.iconTheme": "material-icon-theme",
  "files.associations": {
    "*.css": "tailwindcss"
  }
}
```