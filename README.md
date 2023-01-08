# MyDeepNavigation
Aplikasi yang menggunakan fitur untuk kembali ketika menekan notifikasi yang ada masuk ke dalam halaman tersebut dan jika tekan kembali akan menuju ke home aplikasi, tidak kembali langsung ke home screen.
memanfaatkan TaskStackBuilder API untuk membuat sebuah back stack baru yang akan dimasukkan ke dalam task yang sudah ada. Ketika kelas DetailActivity dijalankan, kemudian pengguna menekan tombol back baik itu system back button maupun up button,
maka pengguna akan diarahkan ke ParentActivity dari DetailActivity. ParentActivity tersebut didefinisikan di berkas AndroidManifest.xml. 
penambahan atribut launchMode pada MainActivity di AndroidManifest.xml dimaksudkan agar MainActivity tidak selalu menciptakan dirinya kembali (recreate) dan akan diarahkan ke instance MainActivity yang telah tercipta di memori.
