latihan1

# Pengertian VCS
Version Control System merupakan sebuah sistem yang merekam perubahan dari sebuah berkas atau sekumpulan berkas dari waktu ke waktu, sehingga anda dapat melihat kembali perubahannya.

# Langkah-langkah menggunakan GIT

1. Buka/masuk software "Git Bash".

2. Masuk ke direktori yang anda akan jadikan tempat penyimpanan file nantinya menggunakan command "cd /direktori anda"

3. Lalu buat file di direktori anda dengan command "mkdir 'nama file'"

4. Setelah dibuat, masuk kedalam file tersebut dengan command "cd /direktori/namafile"

5. Lalu ketik command "git init" untuk set folder tadi menjadi repositori lokal, setelah "git init" diketik akan terlihat seperti "/d/direktori/nama file (master)

6. Lalu buat file README.md dengan command "echo "# nama file" > README.md". reminder = tidak ada string sebelum kata echo dan setelah kata readme.md

7. Setelah file README.md dibuat, masuk kedalam file tersebut menggunakan command "nano README.md"

8. Jika sudah selesai mengisi file readme.md, langkah selanjutnya adalah meng-komit file dengan command "git commit -m "isi commit". reminder kembali = tidak ada string didepan kata git

9. Setelah file di komit, langkah selanjutnya adalah meremot repositori yang sudah anda buat di github dengan command "git remote add origin 'link repositori anda'". reminder = tidak ada kutip diluar link repositori anda

10. Lalu upload file README.md dengan command "git push -u origin master"

11. Kemudian ketik command "git pull origin master", untuk mengambil commit terbaru lalu menggabungkan otomatis (merge) dengan branch yang aktif.

12. Terakhir yaitu mengecek file README.md yang sudah diupload dengan command "ll".
