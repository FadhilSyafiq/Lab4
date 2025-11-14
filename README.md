# Fadhil Syafiq Abdullah (312510161)

## Membuat sebuah list kosong di awal untuk menampung semua data yang akan dimasukkan, dengan cara "data_mahasiswa = []"
## Menambahkan "while True:" sebagai perulangan tak terbatas (infinite loop), program akan terus berjalan di dalam loop ini sampai ada perintah break.
## Menginput data program dengan cara meminta input nama, nim, nilai_tugas, nilai_uts, dan nilai_uas.
## Membuat program untuk mengidentifikasi dan respons kesalahan (error handling) dengan "try-except ValueError", jika memasukkan sesuatu selain angka disaat program meminta nilai berupa angka, maka program akan menampilkan pesan error dan continue ke awal loop tanpa menyebabkan crash.
## Menambahkan Perhitungan Nilai Akhir yang akan dihitung sesuai bobot yang ditentukan: (0.30 * nilai_tugas) + (0.35 * nilai_uts) + (0.35 * nilai_uas)
## Membuat Penyimpanan Data supaya data yang sudah lengkap akan disimpan dalam format dictionary (data_entry) agar lebih terstruktur, dictionary kemudian ditambahkan ke list data_mahasiswa menggunakan .append()
## Membuat kondisi berhenti yang akan menanyakan Tambah data lagi (y/t)? jika "tambah_lagi.lower() == 't':" kode ini akan mengubah input (apapun itu, 'y' atau 't') menjadi huruf kecil, jika inputnya adalah 't', kondisi if terpenuhi. Perintah "break" akan menghentikan perulangan "while True:" dan program akan lanjut ke kode di bawahnya.
## Menampilkan data, setelah loop berhenti, program akan mencetak semua data yang telah tersimpan di list "data_mahasiswa" menggunakan perulangan for. ".2f" ini adalah f-string formatting untuk menampilkan angka desimal (float) dengan dua angka di belakang koma, bertujuan agar nilai akhir terlihat rapi.