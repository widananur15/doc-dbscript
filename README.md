**APA ITU DBSCRIPT**
Digunakan utk maintainer atau versioning migration table, function dan view dst
didalam dbscript terdapat fungsi utama
1. Inceremental, digunakan utk meletakan script2 yang sifatnya hanya boleh dijalankan sekali saja ex: create table, alter table dst
Guide penamaan file utk membuat inceremental:
	- 001_create_table_m_sample.sql
	- 002_alter_table_m_sample_add_column_xxxx.sql
	- dst
2. repeatable, digunakan utk meletakan script2 yang sifatnya bisa dijalankan berkali2 ex: function

**Syarat**
- Pastikan pada laptop terinstall java Min version 1.8

**RUNNING DBSCRIPT**
Utk menjalankan dbscript dapat melakukan langkah-langkah berikut ini
1. Buka terminal
2. Masuk ke directory namadbscript/system
3. Jalankan ./create.sh namaxxxx.zip, digunakan utk membuat bundle file zip
4. ./check.sh namaxxxx.zip, digunakan utk pengecekan script2 yg sudah kita bikin valid atau tidak
5. ./update.sh namaxxxx.zip, digunakan utk eksekusi script2 yg sudah kita buat


# SEKIAN
