---
description: Pada topik ini, kita akan memahami dan mengenal apa itu TypeScript
---

# Introduction - TypeScript

**TypeScript** adalah bahasa pemrograman _open source_ yang dikembangkan oleh tim Microsoft. Sebenarnya TypeScript adalah JavaScript dengan tambahan beberapa sintaks untuk _type system_ atau mengatur tipe data pada JavaScript. TypeScript merupakan bahasa pemrograman yang sangat disukai oleh para developer berdasarkan survey yang dilakukan oleh [Stack Overflow](https://insights.stackoverflow.com/survey/2021#technology-most-loved-dreaded-and-wanted).



Pada [situs](https://www.typescriptlang.org) resminya, tertulis:

> TypeScript is JavaScript with syntax for types



**JavaScript** sendiri adalah bahasa pemrograman yang didesain secara fleksibel namun kekurangannya adalah pada saat aplikasi yang kita buat menggunakan JavaScript, semakin besar dan semakin banyak kode yang dibuat, maka berpotensi memiliki _bug_ jika kita melakukan kesalahan pada saat mengolah/mengganti sebuah data dan akan menyebabkan beberapa bagian pada aplikasi lainnya menjadi _bug_ karena tidak adanya pengaturan tipe data secara _strict_. JavaScript adalah bahasa pemrograman paling populer di dunia dan juga di Indonesia. Kita dapat melihat hasil survey yang dilakukan oleh [Stack Overflow](https://insights.stackoverflow.com/survey/2021#technology-most-popular-technologies) berikut pada tahun 2021.

### _Front-End_ dan _Back-End_

TypeScript dapat kita gunakan untuk _front-end_ dan _back-end._ Pada _front-end_ kita dapat menggunakan TypeScript untuk framework seperti Vue.js dan React.js yang populer lalu pada back-end kita dapat menggunakan TypeScript untuk Node.js dan framework salah satunya Express.js.

### TSC _Compiler_

Lalu bagaimana menjalankan TypeScript?

Pada dasarnya browser (_client-side_) dan _Node runtime environment_ (_server-side_) tidak memahami dan tidak mampu membaca serta menjalankan _file_ TypeScript ya (`.ts`) sehingga mekanisme yang dilakukan adalah _file_ TypeScript akan dikonversikan atau di-_compile_ menggunakan TSC _compiler_ menjadi _file_ JavaScript agar bisa dijalankan pada browser dan pada _Node runtime environment._

![Source: https://medium.com/extra-credit-by-guild/tsconfig-json-demystified-d8f333e578c1](.gitbook/assets/0\_rcQjgkO6dCASKjfI.png)



