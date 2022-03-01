# Tubes AI ~ Face Mask Detection Using Transfer Learning
## Deskripsi Dataset
Dalam penyusunan project ini menggunakan dataset yang didapatkan dari [Github.com](https://github.com/prajnasb/observations/tree/master/experiements/dest_folder). Dataset ini digunakan untuk Klasifikasi Deteksi Masker Wajah dengan gambar yang terdiri dari kurang lebih 1700 gambar. Dengan rincian direktori :
  1. Test :
     * WithMask : 97 images
     * WithoutMask : 97 images
  2. Train :
     * WithMask : 658 images
     * WithoutMask : 657 images
  3. Validation :
     * WithMask : 71 images
     * WithoutMask : 71 images
## Tentang 
Penelitian ini membahas klasifikasi gambar wajah menggunakan masker dan tidak menggunakan masker. Penelitian ini mengembangkan penelitian sebelumnya yang ada di referensi jurnal utama dengan menggunakan dataset serupa akan tetapi menerapkan proposed method yang berbeda yaitu menggunakan metode transfer learning dengan arsitektur pre-trained model VGG16 untuk klasifikasi gambar wajah yang menggunakan masker dan tidak menggunakan masker dengan nilai akurasi dan nilai evaluasi yang mengalami peningkatan dibandingkan metode sebelumnya.
## Tujuan
Penelitian ini dilakukan dengan tujuan untuk mendapatkan hasil nilai akhir akurasi dan nilai evaluasi yang terbaik dari penelitian sebelumnya dengan menggunakan metode transfer learning dengan arsitektur pre-trained model VGG16.
## Metode
Terdapat beberapa proses yakni pada awal pra-pemrosesan data yang berupa pembagian data menjadi data training, validasi, dan testing, setelah itu data yang berasal dari training dan validasi akan dilakukan proses augmentasi. Selanjutnya, dataset training akan dilatih bersamaan dengan validation set untuk melakukan validasi performa pelatihan pada setiap akhir epoch. Sedangkan, tahap terakhir yaitu evaluasi dimana performa model akan dievaluasi dengan menggunakan dataset testing yang merupakan unseen dataset. 
## Teknik Deep Learning yang digunakan
* Model menggunakan algoritma CNN (Convolutional Neural Network)
* Model menggunakan algoritma Transfer Learning VGG16
* Model dilatih menggunakan Google Colaboratory
## Jurnal Referensi
* Jurnal referensi pada projek ini berjudul ["Control The COVID-19 Pandemic: Face Mask 
Detection Using Transfer Learning"](https://www.mendeley.com/catalogue/33180134-8299-34ea-8f45-c008326f90f6/) Oumina A, El Makhfi N, Hamdi M.
2020 IEEE 2nd International Conference on Electronics, Control, Optimization and Computer Science, ICECOCS 2020 (2020)
## Cara Pengeksekusian Program
* Download file .ipynb
* Buka di Google Colaboratory

## Authors
Kontributor dalam project kali ini adalah :
1. Ahmad Junjung Sudrajad
2. Lidya Fankky Oktavia Putri
3. Ulfah Nur Oktaviana
4. Galih Wasis Wicaksono

## Acknowledgments
Inspiration, code snippets, etc.
* [Keras Documentation](https://keras.io/api/applications/vgg/)
