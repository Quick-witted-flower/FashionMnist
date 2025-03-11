#Fashion-MNIST Classification Project

##Opis projektu

    Projekt polega na stworzeniu i trenowaniu konwolucyjnej sieci neuronowej (CNN) do klasyfikacji obrazów z zestawu Fashion-MNIST. Celem było osiągnięcie testowej dokładności >94% poprzez zastosowanie odpowiedniej architektury modelu oraz technik augmentacji danych.

##Struktura katalogów

    
│── Fashion_Mnist.ipynb                   # Główny notebook Jupyter z kodem modelu
│── fashion_data.npz                       # Zbiór danych Fashion-MNIST
│── model_fashion_mnist_v2.keras           # Druga wersja modelu
│── model_augmented_v1.keras               # Model po pierwszej augmentacji
│── model_augmented_v2.keras               # Model po dalszym tuningu
│── model_augmented_v4.keras               # Ostateczna wersja modelu
│── README.md                               # Dokumentacja projektu


##Opis plików

    Fashion_Mnist.ipynb – główny notebook, w którym trenowano model.
    fashion_data.npz – zapisany zestaw danych Fashion-MNIST.
    model_fashion_mnist_v2.keras – drugi zapisany model, ulepszony w stosunku do podstawowej wersji.
    model_augmented_v1.keras – model po pierwszej augmentacji danych.
    model_augmented_v2.keras – ulepszona wersja modelu po dalszym tuningu.
    model_augmented_v4.keras – ostateczna wersja modelu, który osiągnął najlepszy balans między generalizacją a dokładnością.
    README.md – dokumentacja projektu
    ##Etapy realizacji

1️⃣ Trening modelu CNN

    Model został wytrenowany na zbiorze Fashion-MNIST z podziałem 90%/10% (train/test).


2️⃣ Zapisanie modelu i stworzenie interfejsu predykcji

    Modele zapisano w formacie Keras (.keras), umożliwiając łatwe ponowne użycie.
    Przetestowano predykcję modeli na nowych danych.

3️⃣ Augmentacja danych i optymalizacja

    Zastosowano zaawansowane techniki augmentacji (CutMix, MixUp,ElasticTransform), aby poprawić generalizację.
    Najlepszy model osiągnął dokładność walidacyjną 94.62% i testową 92.47%.
    Model augmented_v2 wykazał najlepszą generalizację i spełnia warunki zadania.

