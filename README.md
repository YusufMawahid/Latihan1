Buat repositori baru di GitHub. Untuk menghindari kesalahan, jangan menginisialisasi repositori baru dengan file README, lisensi, atau gitignore. Anda dapat menambahkan file-file ini setelah proyek Anda didorong ke GitHub.

Buat drop-down Repositori Baru
Buka Git Bash.

Ubah direktori kerja saat ini ke proyek lokal Anda.

Inisialisasi direktori lokal sebagai repositori Git.

$ git init
Tambahkan file dalam repositori lokal baru Anda. Ini tahap mereka untuk komit pertama.

$ git tambahkan.
# Tambahkan file dalam repositori lokal dan tahapankan untuk komit. Untuk menghapus file, gunakan 'git reset HEAD YOUR-FILE'.
Komit file yang telah Anda staging di repositori lokal Anda.

$ git commit -m "Komit pertama"
# Melakukan perubahan yang terlacak dan mempersiapkannya untuk didorong ke repositori jarak jauh. Untuk menghapus komit ini dan memodifikasi file, gunakan 'git reset --soft HEAD ~ 1' dan komit dan tambahkan file lagi.
Di bagian atas halaman Pengaturan Cepat repositori GitHub Anda, klik untuk menyalin URL repositori jarak jauh.

Salin bidang URL repositori jarak jauh
Di Command prompt, tambahkan URL untuk repositori jarak jauh di mana repositori lokal Anda akan didorong.

$ git remote menambahkan URL repositori jauh asal # Menetapkan remote baru
$ git remote -v
# Memverifikasi URL jarak jauh baru
Dorong perubahan di repositori lokal Anda ke GitHub.

$ git push master asal
# Dorong perubahan dalam repositori lokal Anda ke repositori jarak jauh yang Anda tentukan sebagai th
