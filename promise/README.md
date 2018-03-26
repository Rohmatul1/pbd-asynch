Promise adalah salah fitur terbaru dari ES6. 
Jika anda sebelumnya sudah pernah menggunakan 
.then maka anda sudah menggunakan promise. 
Mari kita mulai dari analogi sederhana. 
Anda janjian ketemuan dengan salah satu kolega anda, 
tiba-tiba kolega tersebut bertanya anda sudah dimana? 
Ada beberapa kemungkinan jawaban disini : dalam perjalanan, 
sudah sampai atau janjinya di batalkan.

Dalam dunia promise analogi di atas juga sama, 
ketika melakukan request asynchronous seperti Ajax, 
maka ada 3 kemungkinan state :
~Pending ( sedang dalam proses )
~Fulfilled ( berhasil )
~Rejected ( gagal )