Selector adalah bagian penting dalam bahasa CSS (Cascading Style Sheets) yang digunakan untuk memilih elemen HTML yang akan diberi gaya. Berikut adalah penjelasan singkat tentang tiga jenis selector dasar:

* ID Selector:
        Penulisan: Diawali dengan tanda pagar (#), diikuti oleh nama ID elemen yang ingin dipilih.
        Contoh: #header { color: blue; }
        Penjelasan: Selector ID digunakan untuk memilih elemen HTML dengan atribut id tertentu dan tidak bersifat shareable. Setiap ID harus unik dalam dokumen HTML. Ini adalah salah satu selector yang paling spesifik, sehingga gaya yang diberikan akan berlaku hanya untuk elemen dengan ID yang cocok.

* Attribute Selector:
        Penulisan: Dalam bentuk [atribut=nilai], yang memungkinkan Anda untuk memilih elemen dengan atribut tertentu.
        Contoh: input[type="text"] { border: 1px solid #ccc; }
        Penjelasan: Attribute Selector memungkinkan Anda untuk memilih elemen berdasarkan atribut atau kombinasi atribut-nilai tertentu. Ini berguna saat Anda ingin menggaya elemen berdasarkan nilai atribut, seperti jenis input atau atribut lainnya.
        
        Berikut adalah beberapa contoh Attribute Selector beserta penjelasannya:

    1. Menggunakan Attribute Selector dengan Atribut Tertentu:
        Penulisan: [atribut]
        Contoh: [target] { text-decoration: underline; }
        Penjelasan: Selector ini akan memilih semua elemen yang memiliki atribut tertentu, dalam contoh ini, akan memilih semua elemen yang memiliki atribut target. Ini bisa digunakan untuk menggaya elemen dengan atribut tersebut.

    2. Menggunakan Attribute Selector dengan Nilai Atribut Tertentu:
        Penulisan: [atribut="nilai"]
        Contoh: [type="button"] { background-color: #ff0000; }
        Penjelasan: Selector ini akan memilih semua elemen yang memiliki atribut dengan nilai yang sesuai. Dalam contoh ini, semua elemen dengan atribut type yang memiliki nilai "button" akan diberi latar belakang merah.

    3. Menggunakan Attribute Selector dengan Atribut yang Memiliki Nilai yang Dimulai Dengan:
        Penulisan: [atribut^="nilai"]
        Contoh: [href^="https://"] { color: blue; }
        Penjelasan: Selector ini akan memilih semua elemen yang memiliki atribut dengan nilai yang dimulai dengan string tertentu. Dalam contoh ini, elemen-elemen dengan atribut href yang dimulai dengan "https://" akan diberi warna biru.

    4. Menggunakan Attribute Selector dengan Atribut yang Mengandung Nilai Tertentu:
        Penulisan: [atribut*="nilai"]
        Contoh: [title*="video"] { font-weight: bold; }
        Penjelasan: Selector ini akan memilih semua elemen yang memiliki atribut dengan nilai yang mengandung string tertentu. Dalam contoh ini, elemen-elemen dengan atribut title yang mengandung kata "video" akan diberi cetak tebal.

    5. Menggunakan Attribute Selector dengan Atribut yang Berakhir Dengan Nilai Tertentu:
        Penulisan: [atribut$="nilai"]
        Contoh: [src$=".png"] { border: 1px solid #000; }
        Penjelasan: Selector ini akan memilih semua elemen yang memiliki atribut dengan nilai yang berakhir dengan string tertentu. Dalam contoh ini, elemen-elemen dengan atribut src yang berakhir dengan ".png" akan diberi garis tepi.

* Universal Selector:
        Penulisan: Menggunakan tanda asterisk (*) sebagai selector.
        Contoh: * { margin: 0; padding: 0; }
        Penjelasan: Universal Selector digunakan untuk memilih semua elemen dalam dokumen HTML. Ini berguna ketika Anda ingin menerapkan gaya secara global ke semua elemen di halaman web. Namun, harus digunakan dengan hati-hati, karena dapat menghasilkan gaya yang tidak diinginkan jika tidak dikendalikan dengan baik.

Selain selector dasar ini, terdapat juga berbagai jenis selector lainnya dalam CSS, seperti selector kelas (.nama-kelas), selector elemen (tag), dan pseudo-class selectors (:hover, :nth-child, dll.) yang memungkinkan Anda untuk memilih dan menggaya elemen dengan lebih spesifik dan dinamis sesuai kebutuhan desain dan struktur halaman web Anda.

	Berikut adalah beberapa contoh Universal Selector beserta penjelasannya:
	1 * { color: blue; } /* digunakan untuk menargetkan seluruh tipe elemen warna*/
	2 *[lang^='en'] { font-style: sans-serif; } /* berfungsi untuk menargetkan keseluruhan tipe elemen huruf nilai "en" pada atribut lang */
	3. *.wrapper { color: green; } /* digunakan pada keseluruhan atribut class untuk memiliki warna color green*/
	4. *#container { color: #fff; font-style: sans-serif; border .7rem solid blue;} /* digunakan pada keseluruhan atribut id untuk memiliki nilai yang telah ditentukan*/