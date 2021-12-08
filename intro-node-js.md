Mohon jelaskan apa itu Node.js? Apa perbedannya dengan JavaScript?
NodeJs adalah sebuah platform yang digunakan untuk mengembangkan aplikasi berbasis web dengan javascript seagai bahasa pemrogramannya yang dapat dijalankan di windows, mac, maupun linux.  Tidak ada perbedaan antara web JavaScript dan Node.js dalam hal bahasa yang digunakan. JavaScript digunakan di browser dan di Node.js hampir persis sama. Yang membuat Node.js istimewa adalah kumpulan API yang berbeda.

Mohon jelaskan arsitektur dari Node.js?
Node.js adalah Single Threaded Event Loop Sering Keliru bahwa Node adalah Multi-Threaded. Hal ini didasarkan pada Arsitektur Single Threaded Event Loop.

Ape perbedaan antara Built-in Module, External Module, dan Custom Module pada Node.js?
Built-in module dapat gunakan tanpa instalasi lebih lanjut,External module merupakan module yang harus diinstall terlebih dahulu, Custom module merupakan module yang definisikan sendiri.

Sebutkan salah satu contoh dari Built-in Module, External Module, dan Custom Module pada Node.js
Built-in Module : fs, http, path
External Module : moment, nodemon
Custom Module   :
exports.contoh = function () {

return "Hello World";
};