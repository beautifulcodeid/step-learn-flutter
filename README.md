# Step by Step Learn Flutter
disini aku share step by step aku dalam mempelajari Flutter selama 1.5 bulan. Aku akan bagi menjadi 2 bagian, pertama ```Learn Dart``` dan kedua ```Learn Flutter```

## Learn Dart
Sebelum menyentuh Flutter, aku lebih menyarankan kalian untuk mempelajari Dart terlebih dahulu meskipun temen-temen udah berbekal pengetahuan basic programming atau bahkan OOP dari bahasa pemrograman lain. Tujuannya untuk membiasakan diri dengan syntax dart dan mengetahui utility yang ada di dart itu apa saja. Pada bagian ```Learn Dart``` akan aku bagi menjadi 3 bagian yaitu ```Learn Basic Dart```, ```Learn Dart OOP```, dan ```Learn Advanced Dart```.

### Learn Basic Dart
Aku pelajarin basic dart dengan baca dari official documentationnya [disini](https://dart.dev/language) dan coba-coba soal-soal coding test sederhana. Waktu itu aku baca semuanya tanpa terkecuali. Tapi ini yang paling penting untuk kalian pelajari dan latih:

1. Variables (var, late, final, const, and null safety): https://dart.dev/language/variables
2. Collections (List, Set, and Map): https://dart.dev/language/collections
3. Function: https://dart.dev/language/functions
4. Dart command-line tool: https://dart.dev/tools/dart-tool
5. Latihan soal-soal dart: https://leetcode.com/problemset/all/ atau https://hackmd.io/@kuzmapetrovich/S1x90jWGP

### Learn Dart OOP
Pada Dart terdapat beberapa tambahan konsep OOP dari OOP di Java. Aku menyarankan kalian membaca cepat konsep OOP yang mirip dengan OOP disebagian besar bahasa pemrograman seperti class, object, property, constructor, method, inheritance, polymorphism, static method, and enum. Tetapi ada beberapa point penting yang perlu kalian baca dan pelajari dengan detail:

1. Constructor: https://dart-tutorial.com/object-oriented-programming/constructor-in-dart/
2. Factory constructor: https://dart.dev/language/constructors#factory-constructors and https://medium.com/nerd-for-tech/factory-constructor-in-dart-part-1-1bbdf0d0f7f0 
3. Getters and Setters: https://dart.dev/language/methods#getters-and-setters
4. extends (Polymorphism): https://dart-tutorial.com/object-oriented-programming/polymorphism-in-dart/
5. Mixins: https://dart.dev/language/mixins
6. implements (Interface): https://dart-tutorial.com/object-oriented-programming/interface-in-dart/
7. Enhanced Enums: https://dart.dev/language/enums#declaring-enhanced-enums
8. Generics: https://dart.dev/language/generics
9. Latihan OOP Basic: https://www3.ntu.edu.sg/home/ehchua/programming/java/j3f_oopexercises.html (Ini Java tapi implement aja pake Dart)
10. Latihan OOP dengan implement Algorithm & Data Structure: https://github.com/TheAlgorithms/Dart

### Learn Advanced Dart
Advanced Dart ini terdapat konsep yang penting untuk dipelajari sebelum kalian benar-benar terjun mempelajari Flutter. Konsep-konsep ini (terutama ```asynchronous``` dan ```error handling```), akan sering kalian jumpai dalam membuat aplikasi dengan Flutter. Disini terbagi menjadi empat bagian:
1. Asynchronous: https://dart.dev/codelabs/async-await
2. Error Handling: https://dart.dev/language/error-handling
3. Generators: https://www.geeksforgeeks.org/generators-in-dart/
4. Dart Unit Test: https://dart.dev/guides/testing

## Learn Flutter
Dengan asumsi kalian sudah mempelajari konsep-konsep dart yang sudah dijabarkan diatas dan familiar dengan syntax dart, selanjutnya kalian bisa memulai untuk belajar Flutter. Disini akan dijabarkan step by step mempelajari flutter dari 0 hingga ```Fetch API``` di Flutter. Sebagai catatan, disini tidak memberikan kalian step by step kepada kalian hingga menjadi pro di Flutter. Tetapi setidaknya melalui penjabaran disini, dapat membantu kalian mempelajari Flutter secara berurutan hingga kalian bisa membuat aplikasi pertama kalian dengan Flutter. Pada bagian ini ```Learn Flutter``` dibagi menjadi dua yaitu ```Flutter UI``` dan ```Flutter Data Integration```.

### Flutter UI
Pada bagian ini kita lebih fokus mempelajari step by step dalam membuat UI di Flutter. Berawal dari pemahaman mengenai Widget, Layout, dan Navigation. Detail stepnya dijabarkan sebagai berikut:

1. Run Counter App di Emulator dan Real Device: https://docs.flutter.dev/get-started/test-drive & https://stackoverflow.com/a/54526682/21317510
2. Intro tentang Widget: https://docs.flutter.dev/ui/widgets-intro
3. Stateless vs Stateful Widget: https://docs.flutter.dev/ui/interactive#stateful-and-stateless-widgets
4. Styled Widget: https://docs.flutter.dev/ui/widgets/styling
5. Custom Widget: https://www.geeksforgeeks.org/flutter-custom-widgets/
6. About ```pupbspec.yaml```: https://docs.flutter.dev/tools/pubspec
7. Menggunakan Asset di Flutter: https://docs.flutter.dev/ui/assets-and-images
8. Layouting Flutter: https://docs.flutter.dev/ui/layout
9. Constraints Flutter: https://docs.flutter.dev/ui/layout/constraints
10. Buat 5 Screen Dari Aplikasi yang kalian suka
11. Navigation Flutter: https://docs.flutter.dev/ui/navigation
12. Sambungkan kelima screen menggunakan Navigation

### Flutter Data Integration
Pada bagian ini kita lebih fokus pada integrasi data dengan UI yang sudah kita buat. Terutama dengan data dinamis yang bisa kita konsumsi melalui internet (API). Detail stepnya dijabarkan sebagai berikut:

1. Dart & Flutter Packages: https://docs.flutter.dev/packages-and-plugins
2. Network Request (Opsional untuk WebSocket): https://docs.flutter.dev/cookbook/networking
3. Buat 2 Aplikasi yang menggunakan Network Request. Kalian bisa menggunakan data dari [JSON Placeholder](https://jsonplaceholder.typicode.com/) dan [Poke API](https://pokeapi.co/) 
4. State Management (Saran saya pelajari Provider untuk memulai): https://docs.flutter.dev/data-and-backend/state-mgmt/simple
5. Buat 1 Aplikasi yang kalian suka, berdasarkan permasalahan atau keresahan yang kalian rasakan
6. Teruslah membuat sesuatu dan mempelajari sesuatu yang ada di Flutter. Semangat!