# -LT-15_Alert_Prompt_Confirm

`alert` dan `prompt` adalah dua fungsi built-in yang disediakan oleh JavaScript untuk menampilkan pesan kepada pengguna. `alert` adalah fungsi yang bisa digunakan untuk menampilkan pesan pemberitahuan kepada pengguna. Jika Anda menggunakan `alert`, maka pesan akan ditampilkan dalam jendela dialog yang memiliki tombol `OK`. Pengguna harus mengklik tombol tersebut untuk menutup jendela dialog dan melanjutkan dengan program yang sedang dijalankan. Penggunaannya dapat ditulis seperti ini:

    alert("This is an alert message.");

`prompt` adalah fungsi yang bisa digunakan untuk menampilkan jendela dialog yang meminta input dari pengguna. Jendela dialog ini biasanya memiliki pesan yang ingin ditampilkan, input teks, dan tombol `OK` dan `Cancel`. Pengguna dapat memasukkan teks ke dalam input teks dan mengklik tombol `OK` untuk mengirimkan input atau mengklik tombol `Cancel` untuk membatalkannya. Penggunaannya dapat ditulis seperti ini:

    let name = prompt("What is your name?");

Di sini, kita akan menampilkan jendela dialog yang meminta pengguna untuk memasukkan namanya. Nilai yang dimasukkan oleh pengguna akan disimpan ke dalam variabel `name`. Jika pengguna mengklik tombol `Cancel`, maka `name` akan diisi dengan nilai `null`.

Baik, tidak apa-apa. Berikut ini adalah beberapa catatan tambahan mengenai `alert`, `prompt`, dan `confirm`:

 > `confirm` adalah fungsi yang mirip dengan `prompt`, tetapi yang menampilkan jendela dialog yang memiliki tombol `OK` dan `Cancel` saja. Penggunaannya dapat ditulis seperti ini:
 
    let result = confirm("Are you sure you want to do this?");

Di sini, kita akan menampilkan jendela dialog yang meminta pengguna untuk mengkonfirmasi sesuatu. Nilai yang dikembalikan oleh `confirm` adalah `true` jika pengguna mengklik tombol `OK` dan `false` jika pengguna mengklik tombol `Cancel`.

* Selain itu, perlu diingat bahwa `alert`, `prompt`, dan `confirm` adalah fungsi yang dipanggil secara langsung dari JavaScript, dan bukan elemen HTML. Anda tidak perlu menambahkan tag HTML untuk menggunakannya.

* `alert`, `prompt`, dan `confirm` juga termasuk dalam objek `window`, sehingga Anda bisa menggunakan `window.alert()`, `window.prompt()`, dan `window.confirm()` untuk memanggilnya.

* `alert`, `prompt`, dan `confirm` tidak disarankan untuk digunakan dalam aplikasi web modern karena mereka dapat mengganggu aliran program dan memberikan pengalaman pengguna yang kurang baik. Sebaiknya gunakan elemen HTML seperti modal atau toast untuk menampilkan pesan kepada pengguna.
