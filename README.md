# Tugas 1 Computer Vision: Peningkatan score simple deep neural network
Beberapa hal yang harus diganti untuk mendapatkan score lebih baik:
1. Penerapan seed agar reproduceable dan dapat model terbaik.
2. Data train dan test akan di StandardScaler terlebih dahulu agar diambil avg dan diassign sebagai 0 dan bila ada difference maka akan 0 (-,+).
3. Diberikan dropout 0.2 agar model akan dengan random akan hilang ingatan pada neutron (tidak tergantung pada 1 neuron saja)
4. Digantikan learning rate nya dengan menggunakan nilai lebih kecil.
- [Notebook](./Deep_Neural_Network.ipynb)
- [Colab](https://colab.research.google.com/drive/1mEQuRZpiES3skA4kSpWrSwi8O4ti9Cjx?usp=sharing)
