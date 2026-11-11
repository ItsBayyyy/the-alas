# The Alas

Prototipe game survival horror 3D (first-person) untuk PC, bisa langsung dimainkan di browser dengan keyboard dan mouse.

> Sedikit itu cukup. Banyak itu petaka.

Mobilmu mogok di tengah alas. Cari **Kunci Mobil**, **Busi**, **Aki**, dan **Jeriken Bensin**, bawa ke mobil, lalu kabur sebelum 7½ menit habis. Ada sesuatu di antara pepohonan. Ia tidak melihat, ia mendengar.

## Mekanik utama

- **Beban:** setiap barang yang diambil membuat langkah lebih lambat, stamina lebih cepat habis, dan lompatan lebih pendek.
- **Noise bar:** suara naik saat berlari, melompat, mengambil atau membuang barang, lewat semak, dan menginjak kerikil. Makhluknya memburu lewat suara.
- **Timer:** 7:30. Kalau habis, kamu tertangkap.
- **Petunjuk:** catatan di mobil menyebut landmark tempat setiap barang berada, dan kompas di atas layar menunjuk arahnya.
- **Barang antik dan kutukan keserakahan:** opsional. Setiap barang antik yang dipungut membuat makhluk 6% lebih cepat dan pendengarannya 10% lebih tajam.
- **Lempar barang:** barang yang dilempar jadi umpan suara di titik jatuhnya.
- **Skor:** 1000 + 3 × sisa detik + 150 × (4 − beban rata-rata, minimal 0) + ⅓ nilai barang antik. Perjalanan ringan menang atas perjalanan serakah.

## Kontrol (PC)

| Aksi | Tombol |
| --- | --- |
| Berjalan | W A S D |
| Menoleh | Mouse (klik layar untuk mengunci mouse) |
| Lari | Tahan Shift |
| Jongkok | C |
| Lompat | Spasi |
| Ambil, taruh di mobil | E atau klik kiri |
| Pilih barang yang dipegang | 1–9 atau scroll |
| Buang barang yang dipegang | Q (saat jongkok: letakkan pelan) |
| Lempar barang sebagai umpan | G atau klik kanan |
| Petunjuk | H |
| Lihat kontrol | Tahan Tab |
| Layar penuh | F |
| Bunyi | M |
| Mikrofon nyala / mati | V |
| Jeda dan pengaturan | Esc |

Menu jeda berisi pengaturan sensitivitas mouse, kecerahan, volume, sudut pandang, kualitas grafis, dan arah mouse. Pengaturan tersimpan otomatis di browser.

## Mikrofon (suara hybrid)

Noise bar menggabungkan suara di dalam game (langkah, lari, lompat, barang) dengan suaramu sendiri lewat mikrofon. Bicara biasa bisa terdengar makhluk itu dari belasan meter, teriakan lebih jauh, sedangkan berbisik relatif aman. Mikrofon bersifat opsional dan bisa dinyalakan dari layar awal, menu jeda, atau tombol V. Pakai headphone supaya bunyi game tidak tertangkap mikrofon.

Mikrofon hanya bekerja di halaman https, misalnya GitHub Pages.

## Menjalankan

Cukup buka `index.html` di browser modern. Game memakai three.js r128 dari CDN, jadi butuh koneksi internet.

Untuk dimainkan online, aktifkan **GitHub Pages** di *Settings → Pages*, pilih branch `main` dan folder `/ (root)`.

## Status

Prototipe. Belum ada multiplayer, jadi belum ada voice chat antarpemain.
