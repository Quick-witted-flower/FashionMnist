#Fashion-MNIST Classification Project

##Opis projektu

    Projekt polega na stworzeniu i trenowaniu konwolucyjnej sieci neuronowej (CNN) do klasyfikacji obrazów z zestawu Fashion-MNIST. Celem było osiągnięcie testowej dokładności >94% poprzez zastosowanie odpowiedniej architektury modelu oraz technik augmentacji danych.

##Struktura katalogów

    
    │── Fashion_Mnist.ipynb                     # Główny notebook Jupyter z kodem modelu
    │── predict_interface.ipynb                  # Notebook do testowania predykcji
    │── model_fashion_mnist.h5                    # Pierwszy zapisany model (bez augmentacji)
    │── model_fashion_mnist_augmented.h5          # Model po pierwszej augmentacji
    │── model_fashion_mnist_augmented_final.h5    # Model po dalszym tuningu
    │── model_fashion_mnist_augmented_final2.h5   # Model z kolejnymi poprawkami
    │── model_fashion_mnist_augmented_final5.h5   # Ostateczny model spełniający wymagania
    │── README.md                                 # Dokumentacja projektu
      

##Opis plików

    Fashion_Mnist.ipynb – główny notebook, w którym trenowano model.
    predict_interface.ipynb – notebook testujący predykcje modelu.
    model_fashion_mnist.h5 – pierwszy zapisany model (podstawowy).
    model_fashion_mnist_augmented.h5 – model po augmentacji danych.
    model_fashion_mnist_augmented_final.h5 – lepszy model po tuningu.
    model_fashion_mnist_augmented_final2.h5 – kolejna wersja modelu.
    model_fashion_mnist_augmented_final5.h5 – ostateczna wersja modelu, która spełnia wymagania accuracy > 0.94.
    README.md – dokumentacja projektu.

##Etapy realizacji

1️⃣ Trening modelu CNN

    Model został wytrenowany na zbiorze Fashion-MNIST z podziałem 90%/10% (train/test).
    Osiągnął test accuracy 91.58%.

2️⃣ Zapisanie modelu i stworzenie interfejsu predykcji

    Model zapisano w formacie HDF5 (.h5), a interfejs pozwala wizualizować prognozy.

3️⃣ Augmentacja danych i optymalizacja

    Zastosowano techniki augmentacji do poprawienia generalizacji modelu.
    Po tuningu model osiągnął 99.78% dokładności walidacyjnej.
    Finalny model final5 spełnia warunki zadania.
