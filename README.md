**BANK MARKETING CAMPAIGN**
#### **Problem Statement**

Proses menarik nasabah untuk mau menggunakan/ berlangganan produk Term Deposit memerlukan waktu dan sumber daya yang besar jika perusahaan melakukan usaha campaign tersebut kepada semua nasabah. Terlebih menurut Brian Williams, Ph.D, rata-rata sales menghubungi calon nasabah sebanyak lima kali agar calon nasabah tertarik menggunakan produk yang kita tawarkan. Sehingga perusahaan ingin meningkatkan efisiensi marketing campaign dengan memfokuskan campaign berikutnya kepada calon nasabah yang memiliki peluang untuk menggunakan produk Term Deposit berdasarkan karakteristik nasabah yang telah menggunakan produk Term Deposit. Oleh karena itu dibutuhkan sebuah model yang dapat menjadi solusi untuk permasalahan tersebut, agar sebuah bank dapat menentukan calon nasabah yang berpeluang tinggi akan menggunakan term deposit melalui analisa data nasabah untuk mencapai tujuan. 

##### **Context**
Term Deposit atau tabungan berjangka adalah jenis rekening tabungan yang memberikan suku bunga tetap selama jangka waktu tertentu, biasanya satu bulan hingga lima tahun. yang membedakan jenis tabungan ini dengan tabungan konvensional lainnya adalah bahwa pada Term Deposit, nasabah tidak diperbolehkan mengambil dana yang sudah di setor selama jangka waktu deposit, jika nasabah menarik dana nya sebelum waktu deposit, maka nasabah akan dikenai biaya.

Dalam dunia perbankan, deposit memiliki peran penting bagi pertumbuhan industri perbankan. Bank membutuhkan dana yang disetorkan nasabah (Term Deposit) sebagai sumber dana yang dapat digunakan untuk memberikan pinjaman kepada nasabah lain dan menginvestasikan dana tersebut kepada calon investor. Dana deposit juga membantu bank dalam menjaga likuiditas dan stabilitas keuangan dari perusahaan bank tersebut. Sehingga bank harus terus meningkatkan jumlah nasabah yang menggunakan produk term deposit yang ditawarkan sehingga pada akhirnya akan memberikan manfaat jangka panjang dalam mendukung pertumbuhan dan kestabilitasan keuangan bank.
   
Namun, bank harus bersaing agar tidak kehilangan nasabah. Salah satu cara yang digunakan adalah dengan melakukan kampanye pemasaran melalui panggilan telepon untuk menawarkan deposito berjangka. Jika nasabah setuju, mereka akan menandai variabel target dengan `yes` sama dengan `1`, jika tidak setuju, maka akan ditandai dengan `no` sama dengan `0`.

   Keterangan target:

   1 : Nasabah Menggunakan Term Deposit

   0 : Nasabah Tidak Menggunakan Term Deposit

##### **Stakeholder** 
   - Bank's Sales and Marketing Team. 
   - Bank's Finance.

##### **Goal**
   
Berdasarkan Problem Statement diatas, perusahaan ingin memiliki kemampuan untuk dapat memprediksi nasabah mana yang memiliki potensi untuk mau menggunakan/ berlangganan produk Term Deposit pada campaign berikutnya, sehingga tim marketing dapat lebih memfokuskan campaign berikutnya kepada calon nasabah yang terprediksi akan menggunakan produk Term Deposit berdasarkan karakteristik dari nasabah yang menggunakan/ berlangganan Term Deposit pada campaign sebelumnya. Selain itu, untuk meningkatkan pelayanan dan performa dari bank itu sendiri, perusahaan juga ingin mengetahui faktor atau variabel apa yang membuat nasabah mau menggunakan atau berlangganan Term Deposit. Sehingga perusahaan dalam hal ini akan membuat perencanaan yang lebih baik lagi dalam mendekati calon nasabah yang potensial (nasabah yang ingin membuka Term Deposit)

##### **Visualization in Tableau**
https://public.tableau.com/app/profile/dafiq.alfaiz/viz/GroupDelta-BankMarketingCampaign/GroupDelta-BankMarketingCampaign?publish=yes
   
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third-party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- Documentation of project
    │
    ├── notebooks          <- Jupyter notebooks. The naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `bank-marketing-campaign`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results-oriented visualizations
    │       └── visualize.py
    │
    └── references         <- Dataset : https://www.kaggle.com/datasets/volodymyrgavrysh/bank-marketing-campaigns-dataset

--------
