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
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Dist%20Gaji%20Karyawan.PNG)
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Dist%20Gaji%20Manager.PNG)
- 5 Departemen dengan Gaji Maksimum Terendah
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/5%20Dept%20Gaji%20Maks%20Terendah.PNG)
- Korelasi antara Besar Komisi (%) dengan Total Salary di Departemen Sales
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Korelasi%20Bawahan-Gaji%20Manager_Scatter.PNG)
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Korelasi%20Bawahan-Gaji%20Manager_Heatmap.PNG)
- Rata-Rata Gaji Seluruh Karyawan Berdasarkan Negara
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Avg%20Gaji%20Karyawan%20per%20Negara.PNG)
- Korelasi Banyaknya Bawahan Manager dengan Gaji Manager
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Korelasi%20Bawahan-Gaji%20Manager_Scatter.PNG)
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Korelasi%20Bawahan-Gaji%20Manager_Heatmap.PNG)
- Perbedaan Gaji Tiap Departemen
![](https://github.com/reinaldoivan/CapstoneModule2/blob/main/Screenshots/Avg%20Gaji%20per%20Department.PNG)

<br />

Additional Links
----------------
Link Video Penjelasan & Screenshots Visualisasi: https://drive.google.com/drive/folders/1eyNzDFBOzL5HEz6rWxertMZRnn6fuVac?usp=sharing
