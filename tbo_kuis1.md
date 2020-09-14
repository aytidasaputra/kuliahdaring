## TEORI BAHASA DAN AUTOMATA Kuis 1

### ADITYA SAPUTRA
### 201843500528

---

**1.**  Apakah yang kamu ketahui tentang teori bahasa automata?
---
- Teori bahasa dan automata merupakan bagian
ilmu komputer berupa model dam gagasan yang
mendasari mengenasi komputasi. Automata
adalah mesin abstrak yang dapat mengenali
(recognize), menerima (accept), atau
membangkitkan (generate) sebuah kalimat
dalam bahasa tertentu.

---
**2.**  Jelaskan ciri - ciri dari terminal dan non - terminal yang anda ketahui?
---
**Simbol terminal**

- huruf kecil awal alfabet, misalnya : a, b, c
- simbol operator, misalnya : +, −, dan ×
- simbol tanda baca, misalnya : (, ), dan ;
- string yang tercetak tebal, misalnya : if, then, dan else. 

**Simbol non - terminal**
- huruf besar awal alfabet, misalnya : A, B, C
- huruf S sebagai simbol awal
- string yang tercetak miring, misalnya : expr dan stmt. 
---

**3.** Sebutkan dan jelaskan golongan hierarki chomsky yang anda ketahui? dan berikan contohnya masing - masing!

- *Tipe 0 (Unrestricted)* : Pada tipe 0 ini "simbol  ruas sebelah kiri harus minimal ada sebuah simbol variabel dan tidak ada batasan pada aturan produksi". Tipe 0 menggunakan mesin automata dengan Mesin Turing.

- *Tipe 1 (Context Sensitive)* : Pada tipe 1 ini "simbol pada ruas sebelah kiri harus minimal ada sebuah variabel dan panjang String ruas kiri harus lebih kecil atau sama dengan ruas kanan (|a| <=|B|)". Tipe 1 menggunakan mesin automata dengan Linier Bounded Automata.

- *Tipe 2 (Free Context)* : Pada tipe 2 ini "simbol sebelah kiri harus simbol variabel". Tipe 2 menggunakan mesin automata dengan Push Down Automata.

- *Tipe 3 (Regular)* : Pada tipe 3 ini "simbol sebelah kiri harus berupa simbol variabel dan simbol sebelah kanan maksimal hanya memiliki sebuah simbol variabel dan bila ada terletak di paling kanan". Tipe 3 menggunakan mesin automata dengan Finite State Automata DFA dan NFA.
  
---
  
**4.** Berikan contoh sebuah Graph dalam kehidupan sehari - hari?
- Mencari rancangan terpendek
- Perancangan Navigasi Web
- Pengambilan keputusan dengan pohon keputusan
