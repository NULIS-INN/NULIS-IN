# NULIS'IN — Website VS Code

## Struktur folder

```text
NULIS-IN/
│
├── index.html
├── style.css
└── README.md
```

## Cara membuka di VS Code

1. Extract ZIP ini.
2. Buka VS Code.
3. Pilih **File → Open Folder**.
4. Pilih folder `NULIS-IN`.
5. Buka `index.html`.

## Cara melihat website

Cara paling gampang:

1. Install extension **Live Server** di VS Code.
2. Buka `index.html`.
3. Klik kanan pada `index.html`.
4. Pilih **Open with Live Server**.

Browser akan otomatis membuka website.

## Belajar edit

### Mau mengganti nama?

Buka `index.html`, lalu cari:

NULIS'IN

Ganti dengan nama yang kamu mau.

### Mau mengganti warna?

Buka `style.css`.

Di bagian paling atas ada:

```css
:root {
    --green: #173c2a;
    --lime: #d8ed72;
}
```

Kamu bisa mengganti kode warna tersebut.

### Mau mengganti tulisan?

Semua tulisan utama ada di `index.html`.

### Mau mengganti Instagram?

Di bagian paling bawah `index.html`, cari:

```html
href="https://www.instagram.com/"
```

Ganti menjadi URL Instagram NULIS'IN.

Contoh:

```html
href="https://www.instagram.com/nulis.in/"
```

## Tips untuk pemula

Jangan takut mencoba.

Kalau website tiba-tiba berantakan, tekan `Ctrl + Z` untuk membatalkan perubahan terakhir.

File `index.html` = struktur/isi website.

File `style.css` = tampilan website.