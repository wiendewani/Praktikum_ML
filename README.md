<h2>Cigarette Smoker Detection</h2>

Nama Anggota :
- Wien Nurul Dewani
- Putri Sari Asih


<b>Summary Data </b>

Data terdiri dari 2 kelas 
- not smoking (1276)
- smoking(1996)

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
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_2 (Conv2D)            (None, 250, 250, 215)     6020      
_________________________________________________________________
max_pooling2d_2 (MaxPooling2 (None, 125, 125, 215)     0         
_________________________________________________________________
dropout_3 (Dropout)          (None, 125, 125, 215)     0         
_________________________________________________________________
conv2d_3 (Conv2D)            (None, 125, 125, 215)     416240    
_________________________________________________________________
max_pooling2d_3 (MaxPooling2 (None, 63, 63, 215)       0         
_________________________________________________________________
dropout_4 (Dropout)          (None, 63, 63, 215)       0         
_________________________________________________________________
flatten_1 (Flatten)          (None, 853335)            0         
_________________________________________________________________
dropout_5 (Dropout)          (None, 853335)            0         
_________________________________________________________________
dense_2 (Dense)              (None, 16)                13653376  
_________________________________________________________________
dense_3 (Dense)              (None, 1)                 17      

![image](https://user-images.githubusercontent.com/48399925/144560430-1b2a5a67-d663-412f-ab9c-f3ce8147356f.png)


<h3>Model 2</h3>
Arsitektur model :
Transfer Learning InceptionV3

<h3>Kendala</h3> 



