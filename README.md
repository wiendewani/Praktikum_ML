<h2>Cigarette Smoker Detection</h2>

Nama Anggota :
- Wien Nurul Dewani
- Putri Sari Asih


<b>Summary Data </b>

Data terdiri dari 2 kelas 
- not smoking (1276)
- smoking(1996)


<h3><b>Overview Jurnal </b></h3>

<b>Tahapan Preprocessing </b>
Size (150,150)

<b>Arsitektur Model</b>
![image](https://user-images.githubusercontent.com/48399925/144561246-c451f885-12ac-4856-b70d-76827b75e0c4.png)

Pada Jurnal juga telah melakukan model yang lain menggunakan Transfer Learning 
![image](https://user-images.githubusercontent.com/48399925/144561460-2fb469e8-86c3-4465-b22c-d1533214b785.png)

Hasil 
![image](https://user-images.githubusercontent.com/48399925/144561574-220a31ab-13d2-4a19-bb38-5189fa2e8bae.png)


<h3><b>Overview Kelompok Kami Kerjakan </b></h3>

Data dibagi menjadi 2 yaitu train dan val dengan ratio 8:1.9:0.1

<b>Tahapan Preprocessing </b>

- Normalisasi Image (1/255)
- shuffle=False,
- color_mode="rgb",
- target_size=(250, 250), 
- batch_size=20,
- class_mode='binary'



Setelah melakukan percobaan didapatkan hasil model yang terbaik menggunakan <b>MobileNetV2</b>



Hasil Accuracy dan Loss

![image](https://user-images.githubusercontent.com/48399925/146616456-d60f291f-d04b-4285-a273-a4de430014ee.png)


Hasil Evaluasi 
![image](https://user-images.githubusercontent.com/48399925/146616431-ea5c691f-b78b-498d-b005-829efe286b4a.png)









