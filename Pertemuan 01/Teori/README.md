# Letter Cut

## Sumber Masalah

- Algoritma pengiriman surat pada saat ini 99% menggunakan sentralize database yang memudahkan hacker melakukan peretasan dengan mudah. Dengan teknik keamanan apapun ketika data yang dikirim disimpan dalam suatu database yang bersifat terpusat maka dapat dipastikan dokumen tersebut dapat diretas sekalipun menggunakan metode keamanan yang rumit. Hal ini disebabkan oleh database dan storage yang terpusat yang dimiliki atau dikelola oleh suatu perusahaan tertentu. Sebut saja suatu perusahaan menciptakan metode keamanan tertentu, namun dengan terdeteksinya network API pada browser itu justru memudahkan para hacker dalam melacak di server mana dokumen tersebut di simpan. Kadang seseorang menganggap ketika dokumennya didapat akan sulit dipecahkan karena masih dipasangkan enkripsi surat yang rumit, sayangnya dengan kehadiran super computer metode enkripsi bagaimanapun tetap akan dapat dipecahkan dengan mudah.
- Disclaimer: Masalah-masalah kecil akan diselesaikan dalam pengembangan selanjutnya

## Rancangan Solusi

- Hadirnya Aplikasi Surat Rahasial Letter Cut adalah solusi terbaik untuk memecahkan masalah tersebut.
- Letter Cut menghadirkan suatu Algoritma yang melibatkan unsur yang Letter Cut sebut "Committee Chain", yakni pemecahan enkripsi surat rahasia.
- Analoginya layaknya kita mengirim surat kepada suatu badan tertentu, namun suratnya dipotong-potong menjadi beberapa bagian dan potongan-potongan tersebut dipegang oleh beberapa tukang pos. Tukang pos sendiri tidak akan memahami isi surat tersebut dan masing-masing tidak dapat mengetahui bagaimana surat tersebut disatukan.
- Potongan-potongan surat tersebut hanya dapat disatukan oleh persetujuan pengirim, committee, dan ketersediaan penerima. Namun hanya pengirim dan penerima saja yang dapat membaca isi surat tersebut secara utuh dan tidak ada database terpusat yang menyimpan seluruh enkripsi surat.

## Akan hadir pertanyaan

- Bagaimana ceritanya transaksi data tanpa database terpusat? Jawab: Konsepsi peralihan data yang Letter Cut pakai menggunakan sistem Desentralize Database yang melibatkan unsur semirip mungkin dengan transaksi yang berjalan pada sistem Block Chain. Seperti halnya suatu NFT yang disimpan pada IPFS Storage yang hanya dapat diunduh ketika terjadi pesetujuan dari committee, pemilik, dan pembuat smart contract.

- Bagaimana dapat dipastikan metode keamanan dapat dikatakan sangat aman? Jawab: Hadirnya unsur Committee Chain adalah kunci keamanan data. Data yang diamankan akan dilakukan enkripsi yang dibuat oleh komunitas pembuat template enkripsi dengan macam-macam metode kriptografi yang terus menerus berkembang. Setelah dienkripsi, data tersebut akan dipecah dan pecahan-pecahannya akan dipegang oleh beberapa Committee, dan committee tersebut yang akan bertanggung jawab saat data tersebut terdapat request decrypt. Setelah committee menyerahkan data kepada pemilik dan penerima data, masih harus dilakukan satu proses yakni penyusunan kembali. Penyusunan kembali data akan melibatkan suatu super computer dengan pemecahan Algoritma enkripsi yang dipilih di awal.

- Disclaimer: Masalah-masalah kecil lainnya akan diselesaikan pada tahap pengembangan lebih lanjut.
