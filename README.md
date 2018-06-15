### API

API adalah singkatan dari _application programming interface_, atau dalam bahasa sederhananya merupakan jembatan komunikasi antara program client dan server dalam aplikasi. Dengan kata lain, API menjadi bahasa komunikasi antara dua komputer yang client merequest dan server memproses dan merespond kembali atas apa yang diminta.

Contoh kejadiannya di dunia nyata ialah saat aplikasi Go-Jek kita hendak menampilkan data lokasi kita dalam aplikasinya. Go-Jek menampilkannya dalam format seperti yang ditampilkan pada aplikasi Google Maps. Hal ini dilakukan oleh karena Go-Jek menggunakan API dari Google Maps. Dengan kata lain, Go-Jek merequest peta lokasi kita ke server Google Maps dan server itu membalas dengan format aturan yang sudah dijelaskan sehingga dapat ditranslasi oleh Go-Jek untuk ditampilkan.

### OpenWeather Map API

OpenWeather Map API a dalah salah satu dari banyak API yang menyediakan data tentang informasi cuaca terkini dari sebuah tempat. API ini adalah produk dari OpenWeather yang telah dikembangkan sejak tahun 2012. OpenWeather Map API yang mereka sediakan termasuk dalam kategori **Restfull API** yang artinya kita dapat mengaksesnya menggunakan request HTTP dan server mereka akan mengirim data dengan format JSON. Saat ini, OpenWeather Map API telah menyediakan informasi data Cuaca terkini, perkiraan cuaca 5 hari ke depan dalam interval per tiga jam dan beberapa informasi terkait analisis cuaca lainnya.  


### Package Structure

Pada pembuatan aplikasi ini, saya _untuk sementara_ membuatnya dalam susunan sebagai berikut

```
|-- build.gradle
|-- README.md
|-- settings.gradle
|-- src
    |-- main
        |-- java
            |-- Controller
            |-- Model
            |-- Services
            |-- View
        |-- resources
    |-- test 
```

Struktur dasar dari aplikasi ini mengikuti guideline dari Maven sendiri agar mudah untuk dicompile. Untuk struktur package dalam folder Java, saya merasa modelnya akan dibagi menjadi beberapa package karena sejujurnya saya belum terlalu terbayang akan seberapa luas aplikasi ini nantinya.  

Untuk sementara ini file Java akan dikelompokkan ke dalam package Controller, Model, Services, View yang pasti ada pada proyek manapun. Dengan ini dalam proses pembuatan aplikasi, tidak akan ada package yang ditambah maupun dikurangi. Hal ini pasti karena Java adalah bahasa pemrograman yang _Full Object Oriented_. 

#### Implemented
NONE

#### Ongoing
* UI Positioning
* Search City and Connect to API
* Show Current Weather and Forecast 
* Set default location
* Testing and Debugging

### Cancelled
NONE
