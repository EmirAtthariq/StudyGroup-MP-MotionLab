﻿#StudyGroupMobileProgrammingMotionLab

 Navigation adalah proses berpindah dari satu layar ke layar lain di aplikasi

 Routing mengacu pada pengelolaan jalur layar dan pengoperan data antar layar

 Elemen Navigation diantaranya terdapat:

 -Navhost
 
Navhost berfungsi sebagai tempat diamana semua layar yang ada di aplikasi didefinisikan beserta rute yang dapat diakses.
![image](https://github.com/user-attachments/assets/69f054c0-fc00-4606-916c-85e5186db86b)

-NavController

Navcontroller berfungsi sebagai objek yang akan mengatur perpindahan antar layar di dalam aplikasi.
![image](https://github.com/user-attachments/assets/4d9a3da4-7599-4b91-a176-90d0ca8ef899)

-Composable

Composable adalah blok navigasi didalam NavHost. Setiap composable dapat mewakili satu layar atau komponen dalam aplikasi.
![image](https://github.com/user-attachments/assets/5a639b87-2fb7-44e2-b8ee-a047018b50b5)

-NavBackStackEntry

NavBackStackEntry adalah representasi dari layar yang saat ini ada di backstack navigasi

Terdapat juga Hirearki Navigation yang terdiri dari:

-Single Navigation Graph

Semua rute didefinisikan dalam satu NavHost

-Nested Navigation Graphs

Navigasi terbagi menjadi beberapa sub-graf. Setiap sub-graf memiliki NavHost

-Multiple Backstack Navigation

Setiap bagian aplikasi memiliki backstack sendiri
