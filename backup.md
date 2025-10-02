

warna utama jdti [ #5CB3FF]

theme [done]
side-menu [done]
ganti template jurnal [done]
make a submission [done]
    link sub 
            https://jdti.unigamalang.ac.id/?journal=jdti&page=about&op=submissions
index things [done]
mengecilkan ukuran judul jurnal [done]
munculkan login diatas [done]
jarak dewan redaksi dll [done]
link profil [--]

[explore_OJS_LOCAL]
icon favico di tab [already-done]
footer things [already-done]


/* Bungkus dua elemen dalam layout horizontal */
.journal-description, .current_issue {
  display: inline-block;
  vertical-align: top;
}

/* Deskripsi di kiri, lebih lebar */
.journal-description {
  width: 60%;
  padding-right: 20px;
  box-sizing: border-box;
}

/* Current Issue di kanan */
.current_issue {
  width: 35%;
  box-sizing: border-box;
}

/* Responsif: susun vertikal di layar kecil */
@media (max-width: 768px) {
  .journal-description,
  .current_issue {
    width: 100%;
    display: block;
  }

  .journal-description {
    padding-right: 0;
  }
}


