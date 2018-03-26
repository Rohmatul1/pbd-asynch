Async/await adalah fitur yang hadir sejak ES2017. Fitur ini mempermudah kita dalam menangani proses asynchronous. 
Keterangan dari syntax tersebut adalah :
async ? mengubah function menjadi asynchronous
await ? menunda eksekusi hingga proses asynchronous selesai, 
        dari kode di atas berarti console.log(result) tidak akan 
        di eksekusi sebelum prose doAsync( ) selesai. 
        await juga bisa digunakan berkali-kali di dalam function