CSS Combinators adalah bagian dari Cascading Style Sheets (CSS) yang digunakan untuk menghubungkan dan memilih elemen HTML dalam hal bagaimana aturan gaya (styles) diterapkan ke elemen-elemen tersebut. Terdapat beberapa jenis combinator yang berbeda untuk memilih elemen dalam dokumen HTML. Berikut adalah beberapa jenis combinator CSS dan contoh penggunaannya:

* Descendant Selector (Whitespace):
  
    Combinator ini menggunakan tanda spasi (whitespace) untuk memilih elemen yang merupakan keturunan (nested) dari elemen lain.

    Contoh: div p {
    color: blue; }

* Child Selector (>):
Combinator ini digunakan untuk memilih elemen yang adalah anak langsung dari elemen lain.

    Contoh: dul > li {
    list-style-type: square; }


* Adjacent Sibling Selector (+):
Combinator ini digunakan untuk memilih elemen yang adalah saudara sejajar dan langsung setelah elemen lain.

   Contoh: h2 + p {
    font-weight: bold; }

* General Sibling Selector (~):
Combinator ini digunakan untuk memilih elemen-elemen yang adalah saudara sejajar dari elemen lain, tanpa memperhatikan apakah mereka berada langsung setelah elemen tersebut.

   Contoh: h2 ~ p {
    font-style: italic; }

Referensi artikel: 
*https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator
*https://www.w3schools.com/css/css_combinators.asp

