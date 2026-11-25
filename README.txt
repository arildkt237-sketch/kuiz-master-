KUIS MASTER - GAME EDUKASI WEB

Cara menjalankan:
1. Ekstrak folder kuis-master.
2. Buka folder tersebut di Visual Studio Code atau Sublime Text.
3. Buka index.html di browser (atau gunakan ekstensi Live Server).
4. Klik "Mulai bermain".

Fitur:
- Bank soal berisi 100 pertanyaan dari 10 kategori.
- Setiap sesi mengambil 10 pertanyaan secara acak.
- Timer 15 detik untuk setiap soal.
- Skor 10 poin untuk jawaban benar.
- Penanda jawaban benar/salah, progres, hasil, dan akurasi.
- Aturan permainan dan tombol main lagi.

Struktur:
kuis-master/
  index.html
  css/style.css
  js/script.js
  assets/images/
  assets/sounds/

Teknologi:
HTML untuk struktur, CSS untuk tampilan, JavaScript untuk logika permainan.

Catatan:
Untuk mengganti atau menambah soal, edit array QUESTION_BANK di js/script.js.
Setiap soal memiliki format: category, question, options (4 pilihan), answer (indeks jawaban benar mulai dari 0).
