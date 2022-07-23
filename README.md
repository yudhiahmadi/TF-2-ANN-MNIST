# TF-2-ANN-MNIST

Langkah - langkah penggunaan dan keterangan: 

1. Import library tensorflow dan muat data publik mnist serta bagi menjadi data train dan data test
2. Buat model
- Flatten

Tahapan flattening adalah merubah dari matriks yang ada di pooling layer menjadi satu kolom saja (sebuah vektor tunggal). Nantinya vektor ini akan menjadi bagian dari input layer di artificial neural networks (ANN). Ilustrasinya sebagai berikut:

![image](https://user-images.githubusercontent.com/87703066/180595889-7c25ab44-5354-4d59-9483-1c452e1bd5cc.png)

(source : https://www.megabagus.id/)

- ReLu

Aktivasi ReLU (Rectified Linear Unit) merupakan lapisan aktivasi pada model CNN yang mengaplikasikan fungsi f(x)=max(0,x) yang berarti fungsi ini
melakukan thresholding dengan nilai nol terhadap nilai piksel pada input citra. Aktivasi ini membuat seluruh nilai piksel
yang bernilai kurang dari nol pada suatu citra akan dijadikan 0.

![image](https://user-images.githubusercontent.com/87703066/180595975-47f2c68a-432c-4f86-ac28-9d9fde018394.png)

(source : Ilahiyah dan Nilogiri 2018)

- Dropout

Fungsi dari dropout adalah teknik untuk mencegah masalah overfitting
Dropout ini direpresentasikan pada fully connected layer dengan
cara kerja menonaktifkan beberapa neuron secara rendom yang tidak
diperlukan

![image](https://user-images.githubusercontent.com/87703066/180596085-e8d96907-a5e8-459e-8825-60830692dbcb.png)

(source : https://towardsdatascience.com/)

- optimizer adam

Adam adalah algoritma optimasi pengganti untuk stochastic gradient descent untuk training model deep learning. Adam menggabungkan sifat-sifat terbaik dari algoritma AdaGrad dan RMSProp untuk memberikan optimization algorithm yang dapat menangani sparse gradients pada noisy problem. (https://lms.onnocenter.or.id)

![image](https://user-images.githubusercontent.com/87703066/180596171-bc849bb9-13e9-412e-97c8-80e89638b684.png)

- Sparse Categorical Crossentropy

Fungsi loss ini memiliki tugas untuk mencari nilai gradien atau nilai yang menunjukan seberapa cepat nilai suatu variable
berubah. Nilai tersebut nantinya akan digunakan untuk memperbarui nilai bobot. Categorical Cross-entropy (CC), meruapakan salah satu loss function yang biasa digunakan dalam
klasifikasi yang memiliki kategori multi-class. Sedangkan untuk Sparse Categorical Cross-entropy (SCC)
memiliki fungsi yang sama seperti Categorical Cross-entropy, hanya saja pada fungsi SCC data yang
digunakan tidak dilakukan Hot-Encoding terlebih dahulu

3. Visualisasi Loss per iterasi
4. Visualisasi Akurasi per iterasi
5. Evaluasi menggunakan confusion matrix
6. Menampilkan contoh beberapa misklasifikasi

![image](https://user-images.githubusercontent.com/87703066/180596363-b958ab57-d54a-438f-98a3-59487f45566c.png)




