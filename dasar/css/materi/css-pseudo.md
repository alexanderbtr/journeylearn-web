Di dalam CSS, kata "pseudo" merujuk kepada "pseudo-class" dan "pseudo-element." Pseudo-class dan pseudo-element digunakan untuk memilih dan memanipulasi elemen HTML dengan cara tertentu. Berikut penjelasan singkat tentang keduanya:

1. Pseudo-Class:
Pseudo-class digunakan untuk mengubah gaya elemen HTML berdasarkan keadaan atau interaksi dengan elemen tersebut. Pseudo-class selalu diawali dengan tanda titik dua (":"). Contoh:  selector:pseudo-class { property: value; }

        Berikut contoh pseudo-class yang umum digunakan meliputi:

*   :hover: Mengubah gaya saat kursor berada di atas elemen.
*   :active: Mengubah gaya saat elemen sedang aktif, misalnya saat tombol ditekan.
*   :focus: Mengubah gaya saat elemen sedang dalam fokus, seperti saat input teks mendapat fokus.
*   :nth-child(n): Memilih elemen berdasarkan urutan ke-n di dalam elemen yang sama.



2. Pseudo-Element:
Pseudo-element digunakan untuk memanipulasi elemen HTML dengan cara menambahkan isi atau mengubah tampilan elemen tersebut. Pseudo-element diawali dengan dua tanda titik dua (::). Contoh: selector::pseudo-element { property: value; }

Beberapa contoh pseudo-element yang umum digunakan adalah:

*   ::before: Menambahkan isi sebelum elemen yang dipilih.
*   ::after: Menambahkan isi setelah elemen yang dipilih.
*   ::first-line: Memilih baris pertama dalam sebuah elemen.
*   ::first-letter: Memilih huruf pertama dalam sebuah elemen.