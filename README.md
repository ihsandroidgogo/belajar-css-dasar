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