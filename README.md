# Penyunting Tag OpenStreetMap (OpenStreetMap Tags Editor)

Ini adalah WebExtension yang menambahkan tombol "Edit Tag" ke semua halaman simpul (node), jalan (way), dan relasi (relation) di situs web [osm.org](https://www.openstreetmap.org). Tombol ini akan membuka area teks untuk menyunting tag mentah (dalam format `kunci=nilai` atau `key=value`) dilengkapi dengan tombol "Simpan" untuk mengunggah perubahan.

![Tangkapan layar penyunting](osmtags-editor-screen.png)

## Cara Instalasi

### Melalui Toko Ekstensi Resmi (Versi Asli/Berbahasa Inggris)
Anda dapat membuka konsol pengembangan dan menggunakan kode sumber, atau langsung menuju ke toko ekstensi peramban Anda untuk versi asli:

* [Mozilla Firefox](https://addons.mozilla.org/firefox/addon/openstreetmap-tags-editor/)
* [Google Chrome](https://chrome.google.com/webstore/detail/openstreetmap-tags-editor/gcbcbndjajojkneicbfdaegcghgbdjnj)

### Melalui Mode Pengembang (Berbahasa Indonesia)
Karena repositori ini merupakan fork lokal ([FajrAlim/osmtags-editor-bahasa-indonesia](https://github.com/FajrAlim/osmtags-editor-bahasa-indonesia)), Anda dapat menginstalnya secara manual menggunakan Fitur Mode Pengembang (*Developer Mode / Load Unpacked*):

1. **Unduh Kode Sumber:**
   * Klik tombol **Code** di halaman GitHub ini lalu pilih **Download ZIP**, atau klon repositori ini menggunakan Git.
   * Ekstrak berkas ZIP yang telah diunduh ke dalam sebuah folder di komputer Anda.

2. **Aktifkan Mode Pengembang di Peramban:**
   * **Google Chrome / Chromium based:**
     * Buka tab baru dan ketik `chrome://extensions/` pada bilah alamat.
     * Di pojok kanan atas, aktifkan sakelar **Developer mode** (Mode pengembang).
   * **Mozilla Firefox:**
     * Buka tab baru dan ketik `about:debugging#/runtime/this-firefox` pada bilah alamat.

3. **Muat Ekstensi (*Load Unpacked*):**
   * **Google Chrome / Chromium:**
     * Klik tombol **Load unpacked** (Muat yang belum dikemas) di pojok kiri atas.
     * Pilih folder hasil ekstrak berkas ZIP tadi (pastikan memilih folder yang berisi berkas `manifest.json`).
   * **Mozilla Firefox:**
     * Klik tombol **Load Temporary Add-on...** (Muat Pengaya Sementara...).
     * Pilih berkas `manifest.json` dari folder hasil ekstrak berkas ZIP tadi.

Untuk ekstensi dapat aktif, biasanya dibutuhkan buka ulang peramban.

## Penulis dan Lisensi

Ditulis oleh Ilya Zverev, diterjemahkan oleh FajrAl, dan diterbitkan di bawah lisensi MIT.
