Proyek ini bertujuan untuk mengembangkan sistem yang dapat mengklasifikasikan teriakan dan non-teriakan dengan akurasi tinggi, memanfaatkan berbagai metode pembelajaran mesin. Dalam proyek ini, kami menggunakan tiga pendekatan utama: Support Vector Machine (SVM), Regresi Logistik, dan Convolutional Neural Network (CNN). SVM dan regresi logistik digunakan untuk menganalisis Mel Spectrogram dan Zero Crossing Rate (ZCR) dari sinyal audio, sementara CNN digunakan untuk menganalisis gambar Mel Spectrogram.

Pendekatan SVM dan regresi logistik memanfaatkan fitur Mel Spectrogram dan ZCR untuk mengidentifikasi pola dalam sinyal audio. Melalui SVM, kami mencoba membedakan antara teriakan dan non-teriakan dengan menemukan batas keputusan yang optimal di antara fitur-fitur ini. Sementara regresi logistik memodelkan kemungkinan teriakan berdasarkan fitur-fitur tersebut.

Selain itu, kami menggunakan pendekatan yang lebih maju, yaitu CNN, untuk menganalisis gambar Mel Spectrogram. Dengan CNN, kami dapat secara otomatis mengekstrak fitur-fitur penting dari gambar-gambar ini dan melakukan klasifikasi dengan tingkat akurasi yang tinggi.


Sumber data:
https://www.kaggle.com/datasets/afisarsy/raw-audio-of-accident-and-crime-detection

File akhir bernama pengenal_teriak.ipynb. Experimental code berisi kode pada tahap pengembangan. Kode generate_noise_in_data.ipynb untuk menambahkan noise pada data teriak sehingga lebih mirip dengan kasus dunia nyata. 