# CapstoneModul2
**Data Analysis Project**

**Database: HR Database**

<br />

Context
-------
Sebuah perusahaan yang memiliki berbagai departemen tersebar di beberapa negara ingin **memperluas tim-nya** di tahun mendatang. Mereka ingin tahu bagaimana mereka dapat menambah tim nya secara **efisien** dan juga dapat memperhitungkan **budget** yang diperlukan.

Perusahaan memiliki sebuah database yang berisikan data-data karyawan, termasuk gaji, lokasi, dan berbagai detail lainnya. Maka, kita akan merangkum serta menampilkan database dalam bentuk visual sehingga dapat memberikan insight terbaik sehubungan skenario di atas.

<br />

Tables
------
**1. Data General Employee**

Data berikut merupakan data utama yang menampilkan beberapa informasi utama (diambil dari beberapa kolom dari tabel yang digabung) mengenai seorang employee secara general, dan tergabung dari 6 tabel, yaitu ```employees```, ```jobs```, ```departments```, ```locations```, ```countries```, dan ```regions```. Informasi yang diambil antara lain adalah:
- employee_id dari tabel employees
- first_name dari tabel employees
- last_name dari tabel employees
- region_name dari tabel regions
- country_name dari tabel countries
- city dari tabel locations
- department_name dari tabel departments
- job_title dari tabel jobs
- salary dari tabel employees
- commission_pct dari tabel employees
- manager_id dari tabel employees

<br />

**2. Data General Department**

Data berikut merupakan data department yang menampilkan informasi mengenai department secara general, seperti job apa saja yang ada ataupun salary nya. Data tergabung dari 3 tabel, yaitu ```employees```, ```jobs```, dan ```departments```. Informasi yang diambil antara lain adalah:
- department_id dari tabel departments
- department_name dari tabel departments
- job_title dari tabel jobs
- min_salary dari tabel jobs
- max_salary dari tabel jobs
- range_salary dari tabel jobs (pengurangan max dan min salary)

<br />

Visualization & Statistics
--------------------------
- Distribusi Gaji Seluruh Karyawan & Hanya Manager
- 5 Departemen dengan Gaji Maksimum Terendah
- Korelasi antara Besar Komisi (%) dengan Total Salary di Departemen Sales
- Rata-Rata Gaji Seluruh Karyawan Berdasarkan Negara
- Korelasi Banyaknya Bawahan Manager dengan Gaji Manager
- Perbedaan Gaji Tiap Departemen

<br />

Additional Links
----------------
Link Video Penjelasan: https://drive.google.com/file/d/1ECY-o8wSSdHG1XAM0fEW51gkNPRv4odQ/view?usp=sharing
