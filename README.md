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



Terdapat 2 model yang telah dilakukan percobaan

<h3>Model 1</h3>
Arsitektur model :
![image](https://user-images.githubusercontent.com/48399925/144560582-c4c8972c-61bb-4781-80a4-b95fb7a4666f.png)

Hasil Accuracy
![image](https://user-images.githubusercontent.com/48399925/144560430-1b2a5a67-d663-412f-ab9c-f3ce8147356f.png)

Hasil Loss
![image](https://user-images.githubusercontent.com/48399925/144560618-8c3a1726-8ae8-45bc-8ed7-050a73dd8705.png)

Hasil Evaluasi 
![image](https://user-images.githubusercontent.com/48399925/144560751-c86b66de-eaaf-422b-a4c0-7a443607750f.png)



<h3>Model 2</h3>
Arsitektur model :
![image](https://user-images.githubusercontent.com/48399925/144563672-f797d896-7472-413a-be0b-dc7d7bf5e0e3.png)


Hasil Accuracy
![image](https://user-images.githubusercontent.com/48399925/144563741-05de396d-66e0-40a3-9df4-6e05901880e3.png)

Hasil Loss
![image](https://user-images.githubusercontent.com/48399925/144563766-3dbd938b-d7c6-40d5-9223-4a6770b80da8.png)

Hasil Evaluasi 
![image](https://user-images.githubusercontent.com/48399925/144563797-dc0e701c-a934-4dc7-be89-e4c68ccb8396.png)







