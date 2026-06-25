# Panduan Kontribusi untuk BlackberryHazard

Kami sangat senang Anda tertarik untuk berkontribusi pada proyek-proyek kami! Komunitas **BlackberryHazard** adalah wadah bagi para penggemar IT dan Gaming di Indonesia yang bersemangat untuk berkolaborasi dalam proyek open source. Panduan ini akan membantu Anda memulai proses kontribusi.

## Kode Etik

Untuk memastikan lingkungan yang ramah dan inklusif, kami mewajibkan semua kontributor untuk mematuhi [Kode Etik kami](./CODE_OF_CONDUCT.md). Dengan berpartisipasi, Anda diharapkan untuk menjunjung tinggi kode ini.

## Bagaimana Cara Berkontribusi?

Kami menyambut kontribusi dalam berbagai bentuk, termasuk perbaikan bug, fitur baru, peningkatan dokumentasi, atau bahkan ide-ide baru. Berikut adalah langkah-langkah umum untuk berkontribusi:

1.  **Fork Repository**: Mulailah dengan melakukan *fork* pada repositori yang ingin Anda kontribusikan ke akun GitHub Anda.
2.  **Clone Repository**: *Clone* repositori yang sudah Anda *fork* ke mesin lokal Anda:
    ```bash
    git clone https://github.com/USERNAME_ANDA/NAMA_REPOSITORI.git
    cd NAMA_REPOSITORI
    ```
3.  **Buat Branch Baru**: Buat *branch* baru untuk perubahan Anda. Gunakan nama yang deskriptif, misalnya `fitur/nama-fitur-baru` atau `perbaikan/bug-login`:
    ```bash
    git checkout -b fitur/nama-fitur-baru
    ```
4.  **Lakukan Perubahan**: Lakukan perubahan yang Anda inginkan pada kode atau dokumentasi.
5.  **Commit Perubahan**: *Commit* perubahan Anda dengan pesan *commit* yang jelas dan ringkas. Kami merekomendasikan format *Conventional Commits* (misalnya, `feat: menambahkan fitur X`, `fix: memperbaiki bug Y`, `docs: memperbarui dokumentasi Z`).
    ```bash
    git commit -m 'feat: menambahkan fitur X'
    ```
6.  **Push ke Branch**: *Push* perubahan Anda ke *branch* baru di repositori *fork* Anda:
    ```bash
    git push origin fitur/nama-fitur-baru
    ```
7.  **Buka Pull Request (PR)**: Setelah *push*, buka *Pull Request* dari repositori *fork* Anda ke repositori asli **BlackberryHazard**. Pastikan untuk memberikan deskripsi yang jelas tentang perubahan Anda, mengapa perubahan itu diperlukan, dan masalah apa yang dipecahkan (jika ada).

## Pedoman Tambahan

*   **Gaya Kode**: Usahakan untuk mengikuti gaya kode yang sudah ada dalam proyek. Jika ada linter atau formatter, jalankan sebelum membuat PR.
*   **Pengujian**: Jika Anda menambahkan fitur baru atau memperbaiki bug, sertakan tes yang relevan jika memungkinkan.
*   **Dokumentasi**: Perbarui dokumentasi yang relevan jika perubahan Anda memengaruhi fungsionalitas atau penggunaan proyek.

Terima kasih atas kontribusi Anda! Kami menghargai waktu dan usaha Anda untuk membantu mengembangkan komunitas **BlackberryHazard**.
