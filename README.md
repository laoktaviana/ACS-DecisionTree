Laily Ade Oktaviana - 2101201026 

Advanced Cyber Security

1. Problem Statment:
Membangun sebuah _Intrusion Detection System(IDS)_ yang merupakan software appplikasi untuk mendeteksi network intrusion menggunakan algoritma machine learning. IDS memonitoring sebuah jaringan atau sistem untuk aktifitas malicious dan melindungi jaringan komputer dari unauthorized akses dari user. IDS membangunn predictive model yang mampu untuk membedakan antara koneksi buruk (intrusi/serangan), dan koneksi baik (normal).  

Jenis Serangan

* DoS: Mematikan mesin atau jarinngan sehingga tidak dapat diakses oleh pengguna.
* R2L: Launched by an attacker to gain unauthorized access to a victim machine in the entire network.
* U2R: Lauched by illegally obtaining the root's privilages when legally accessing a local machine.
* Probe: Its target detects and reports it with a recognizable "fingerprint" in the report. The attacker then uses the collaborative infrastructure to learn the detector's location and defensive capabilities from this report. 

2. Dataset Used: KDD Cup 1999 dataset 

KDD Cup'99 merupakan data set yang telah dalam kurun waktu yang tidak sebentar untuk evaluasi jaringan sistem instrusi.  KDDcup99 Dataset berisi 41 atribut variasi data yang disimulasikan dari intrusi pada jaringan militer. Pada tugas ini menggunakan data 10% dataset KDD Cup 1999 (http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html).

<img width="475" alt="Screen Shot 2022-01-04 at 22 58 25" src="https://user-images.githubusercontent.com/73576347/148086948-a724e84c-9d56-4a9d-b653-d6186a53bf8d.png">



3. Decision Tree

Decision Tree adalah algoritma dengan sistem pengambilan keputusan berdasarkan aturan yang ditetapkan. Aturan yang bekerja dalam sistem diilustrasikan seperti pohon. Pada pohon terdapat daun yang diilustrasikan sebagai aturan dan cabang diilustrasikan sebagai keputusan yang diambil. Klasifikasi error yang didefinisikan sebagai presentasi dari misclassified cases merupakan faktor performansi utama untuk decision tree. Pada praktiknya data set training berukuran besar, sehingga menghasilkan lebih banyak cabang dan layers pada generator decision tree. Terdapat perbedaan algoritma untuk mengenerate decision tree seperti ID3, J48, FT, BFTee, LMT, etc. Untuk tugas ini menggunakan algoritma J48 yang diusulkan oleh Quinalan di tahun 1997 karena algoritma J48 memiliki tingkat akurasi yang lebih tinggi.  

<img width="232" alt="Screen Shot 2022-01-12 at 19 32 28" src="https://user-images.githubusercontent.com/73576347/149140972-00414f0d-d986-421d-be69-68ddc596c568.png">
Gambar 1. Contoh sederhana Decision Tree

Decision tree merupakan outstanding method untuk data mining. Pada intrusion detection system (IDS), data mining digunakan untuk mendeteksi serangan terutama anomaly detection. IDS merupakan bagian terpenting dalam infrastruktur kemanan untuk koneksi jaringan ke internet. 

A. Algoritma

<img width="371" alt="Screen Shot 2022-01-12 at 19 39 12" src="https://user-images.githubusercontent.com/73576347/149141902-6842e5fd-a694-402c-8680-f38540fb2824.png">

B. Informasi Gain

C. Confusion Matrix
A confusion matrix memiliki 4 fakror pengukuran: 
1. True Positive(TP): Angka dari prediksi benar dan termasuk kelas sama.
2. True Negative(TN): Angka dari prediksi salah dan termasuk kelas berbeda. 
3. False Positive(FP): Angka dari prediksi salah dan termasuk kelas sama.
4. False Negetive(FN): Angka dari  prediksi benar dan termauk kelas berbeda. 

<img width="332" alt="Screen Shot 2022-01-12 at 20 22 51" src="https://user-images.githubusercontent.com/73576347/149148439-c99e9f18-7930-4733-a421-cdce8bc7859d.png">

D. Akurasi
Akurasi adalah presentasi dari kleasifikasi yang benar. Akurasi digitung menggunakan confussion matriks. 

<img width="226" alt="Screen Shot 2022-01-12 at 20 25 03" src="https://user-images.githubusercontent.com/73576347/149148792-2baf4144-25ed-43fa-9b69-93d5e8dd4fd4.png">


