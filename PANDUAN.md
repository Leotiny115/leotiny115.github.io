# Publikasi identitas SolChat Devnet
1. Di akun Leotiny115, buat repositori publik bernama `leotiny115.github.io`, atau gunakan repositori tersebut jika sudah ada.
2. Unggah `index.html`, `solchat-icon.png`, file kosong `.nojekyll`, dan `.well-known/assetlinks.json` ke root branch `main`. Jika lewat antarmuka GitHub dan file tersembunyi terlewat, pakai **Add file → Create new file** untuk membuat `.well-known/assetlinks.json` dengan isi yang sudah disiapkan, dan buat `.nojekyll` sebagai file kosong.
3. Di **Settings → Pages**, pilih **Deploy from a branch → main → / (root) → Save**. Gunakan **Enforce HTTPS** bila aktif di pengaturan.
4. Setelah Pages berhasil deploy, buka https://leotiny115.github.io/.well-known/assetlinks.json. Endpoint ini harus mengembalikan HTTP 200 langsung dengan tipe `application/json`. Jangan arahkan ke URL repo GitHub atau ke situs dengan prefix path.
5. Setelah tes file tersebut hijau, lanjutkan uji di Phantom Devnet. Status file publik belum membuktikan Phantom menerima identitas atau transaksi berhasil.
