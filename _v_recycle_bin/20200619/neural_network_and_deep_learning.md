# Neural Networks dan Deep Learning

*Neural Networks dan Deep Learning* adalah buku *online* bebas. Buku ini akan mengajarkan Anda tentang:
  - jaringan saraf (*neural networks*), sebuah paradigma pemrograman yang diilhami secara biologis yang indah yang memungkinkan komputer untuk belajar dari data pengamatan
  - Pembelajaran dalam (*deep learning*), seperangkat teknik yang kuat untuk belajar di jaringan saraf

Jaringan saraf (*neural networks*) dan pembelajaran dalam saat ini mampu memberikan solusi terbaik untuk banyak hal seperti untuk pengenalan gambar, pengenalan ucapan, dan pemrosesan bahasa alami. Buku ini akan mengajarkan Anda banyak konsep inti dibalik jaringan saraf (*neural networks*) dan pembelajaran dalam.

# Tentang buku ini

Jaringan saraf (*neural networks*) adalah salah satu paradigma pemrograman paling indah yang pernah ditemukan. Dalam pemrograman komputer, biasanya kita memberi tahu komputer apa yang harus dilakukan engan cara memecah masalah yang besar menjadi banyak pekerjaan-pekerjaan kecil spesifik yang dapat dikerjakan dengan mudah oleh komputer. Sebaliknya, dalam jaringan saraf (*neural networks*) kita tidak memberi tahu komputer bagaimana menyelesaikan masalah kita. Komputer belajar sendiri dari data pengamatan, lalu mencari solusi sendiri untuk masalah yang diberikan.

Belajar mandiri dari data yang tersedia terdengar begitu menjanjikan. Akan tetapi, hingga sekitar tahun 2006, kita tidak tahu bagaimana cara melatih jaringan saraf (*neural networks*) agar bisa melebihi pendekatan pembelajaran yang tradisional (kecuali untuk beberapa masalah khusus). Yang baru pada tahun 2006 adalah penemuan teknik pembelajaran jaringan saraf (*neural networks*) yang diistilahkan dengan jaringan saraf dalam (*deep neural network*). Teknik pembelajaran tersebut sekarang lebih dikenal dengan istilah pembelajaran dalam (deep learning). Teknik tersebut telah dikembangkan lebih lanjut, dan saat ini jaringan saraf dalam dan pembelajaran dalam telah mencapai unjuk kerja yang luar biasa pada banyak masalah penting dalam penglihatan komputer, pengenalan suara, dan pemrosesan bahasa alami. Teknik-teknik pembelajaran dalam sekarang digunakan dalam skala besar oleh perusahaan-perusahaan seperti Google, Microsoft, dan Facebook.

Tujuan dari buku ini adalah untuk membantu Anda menguasai konsep inti jaringan saraf, termasuk teknik-teknik modern untuk pembelajaran dalam. Setelah menguasai isi buku ini, Anda akan memiliki kode program yang menerapkan jaringan saraf (*neural networks*) dan pembelajaran dalam untuk memecahkan masalah pengenalan pola yang kompleks. Dengan ini, Anda akan memiliki dasar yang untuk menggunakan *jaringan saraf (neural networks)* dan pembelajaran dalam untuk mengatasi masalah yang Anda hadapi sendiri.

## Sebuah pendekatan berorientasi prinsip

Satu prinsip yang mendasari buku ini adalah bahwa lebih baik kita mendapatkan pemahaman yang kuat tentang prinsip-prinsip inti *jaringan saraf (neural networks)* dan pembelajaran dalam, daripada memiliki ide-ide yang banyak tapi tanpa pemahaman yang jelas. Jika Anda sudah memahami gagasan inti dari jaringan saraf (*neural networks*) dan pembelajaran dalam dengan baik, Anda dapat dengan cepat memahami materi baru lainnya. Dalam istilah bahasa pemrograman adalah sebagaimana Anda sedang berusaha menguasai sintaksis dasar, pustaka dan struktur data dari sebuah bahasa pemrograman baru. Anda mungkin masih hanya tahu sebagian kecil dari bahasa pemgorgraman tersebut - banyak bahasa pemrograman memiliki pustaka yang sangat besar- tetapi pustaka dan struktur data dari bahasa pemograman yang baru tersebut dapat dipahami dengan cepat dan mudah.

Ini artinya, buku ini bukanlah berisi tutorial tentang cara menggunakan beberapa pustaka jaringan saraf (*neural networks*) tertentu. Jika Anda ingin mempelajari suatu jenis pustaka jaringan saraf, jangan membaca buku ini\! Pilih pustaka jaringan saraf (*neural networks*) yang ingin Anda pelajari, lalu berlatihlah melalui melalui tutorial dan dokumentasi dari pustaka tersebut. Tapi berhati-hatilah. Meskipun cara tersebut memberikan hasil langsung berupa penyelesaian masalah yang Anda hadapi, akan tetapi jika Anda ingin memahami apa yang sebenarnya terjadi di dalam jaringan saraf, atau jika Anda ingin agar wawasan yang Anda kuasai akan tetap relevan bertahun-tahun kemudian, maka tidak cukup hanya dengan mempelajari beberapa pustaka jaringan saraf (*neural networks*) yang sedang populer. Anda perlu menguasai pemahaman yang bersifat tahan lama dan kekal yang mendasari cara kerja jaringan saraf. Teknologi datang dan teknologi pergi, tetapi pemahaman akan melekat selamanya.

## Sebuah pendekatan langsung

Melalui buku ini, kita akan mempelajari prinsip-prinsip inti di balik jaringan saraf (*neural networks*) dan pembelajaran dalam *(deep learning)* dengan mengatasi masalah yang nyata: mengajar sebuah komputer untuk mengenali tulisan tangan. Masalah ini sangat sulit dipecahkan dengan menggunakan pendekatan konvensional dalam pemrograman. Namun, seperti yang akan kita lihat nanti, masalah ini dapat diselesaikan dengan cukup baik menggunakan jaringan saraf (*neural networks*) sederhana, hanya dengan beberapa puluh baris kode, dan tanpa menggunakan pustaka khusus. Lebih dari itu, kami akan meningkatkan program melalui banyak iterasi kegiatan, yang secara bertahap memasukkan berbagai ide inti tentang jaringan saraf (*neural networks*) dan *pembelajaran dalam (deep learning)*.

Pendekatan langsung ini memiliki konsekuensi bahwa Anda perlu memiliki pengalaman pemrograman untuk dapat membaca buku ini. Tetapi tidak berarti Anda harus merupakan seorang programmer profesional. Saya menulis kode program pada buku ini menggunakan bahasa Python (versi 2.7), yang meskipun Anda tidak memiliki pengalaman memprogram dalam Python, ada dapat dengan mudah mengerti hanya dengan sedikit usaha.

Melalui buku ini kita akan mengembangkan pustaka *jaringan saraf (neural networks)* kecil, yang dapat Anda gunakan untuk bereksperimen dan mengembangkan pemahaman terhadapnya. Semua kode tersedia untuk diunduh di link Github ini (http://github.com/xxx). Setelah Anda selesai membaca buku ini, atau sembari Anda membaca buku ini, Anda dapat pula dengan  mudah menggunakan salah satu pustaka jaringan saraf (*neural networks*) yang lebih lengkap yang dirancang untuk digunakan dalam produksi atau proyek sesungguhnya.

Di sisi lain, persyaratan pengetahuan matematika untuk membaca buku ini tidak terlalu banyak. Ada beberapa perhitungan matematika di sebagian besar bab, tetapi sekadar aljabar dasar dan plot atas fungsi, yang saya perkirakan sebagian besar pembaca akan mudah memahaminya. Saya kadang-kadang menggunakan matematika lanjut, akan tetapi saya telah menyusun materi sedemikiannya sehingga Anda tetap dapat mengikuti bahkan jika beberapa rincian matematika terasa memberatkan Anda. Satu bab yang cukup banyak menggunakan matematika lanjut adalah Bab 2, yang membutuhkan sedikit kalkulus multivariabel dan aljabar linier. Jika itu juga tidak familier bagi anda, saya mulai Bab 2 dengan sedikit diskusi tentang bagaimana cara memahami matematika. Jika Anda merasa hal itu sangat berat, Anda dapat langsung menuju ringkasan hasil utama bab ini. Intinya, Anda tidak perlu merasa khawatir tentang hal ini sejak awal.

Buku yang memiliki dua tujuan (berorientasi pada prinsip dan dengan pendekatan langsung) memang jarang. Tapi saya percaya Anda dapat memahaminya dengan bai jika kita mengawalinya dengan ide-ide dasar jaringan saraf (neural networks). Kami akan mengembangkan kode program yang berfungsi, bukan hanya teori abstrak, yaitu kode yang dapat Anda kembangkan dan perluas. Dengan cara ini Anda akan memahami dasar-dasarnya, baik dalam teori maupun praktik, dan siap untuk menambah pengetahuan Anda.

# Tentang latihan-latihan dan soal-soal

Bukan hal yang aneh bagi buku teknis untuk memberikan peringatan bahwa pembaca harus melakukan berbagai latihan dan soal yang ada di dalam buku. Saya memang merasa sedikit aneh ketika saya membaca peringatan seperti itu. Akankah sesuatu yang buruk terjadi pada saya jika saya tidak melakukan latihan-latihan dan sal-soal? Tentu saja tidak. Saya memang akan mendapatakan beberapa waktu luang, tetapi itu dengan mengorbankan pemahaman mendalam terhadap materi. Terkadang hal itu sepadan. Tapi terkadang tidak.

Jadi apa yang mesti dilakukan melalui buku ini? Saran saya adalah Anda benar-benar harus mencoba mengerjakan sebagian besar latihan, dan Anda tidak harus melakukan sebagian besar soal-soal.

Mengapa? Anda harus melakukan sebagian besar latihan karena itu adalah pengecekan awal bahwa Anda telah memahami materi. Jika Anda tidak dapat menyelesaikan latihan dengan relatif mudah, berarti Anda mungkin melewatkan sesuatu yang mendasar. Tetapi, jika Anda terjebak kesulitan pada suatu latihan, lewati saja - kemungkinan itu hanya kesalahpahaman kecil dari Anda, atau mungkin saya yang menuliskannya dengan tidak jelas. Tetapi jika Anda kesulitan pada sebagian besar latihan, maka itu indikasi Anda mungkin perlu membaca beberapa bahan materi sebelumnya dengan lebih baik.

Soal-soal adalah perkara yang lain. Soal lebih sulit daripada latihan, dan Anda mungkin harus berjuang untuk menyelesaikan beberapa soal. Itu memang menyebalkan, tetapi, tentu saja, kesabaran dalam menghadapi frustrasi seperti itu adalah satu-satunya cara untuk benar-benar memahami dan menginternalisasi suatu subjek.

Dengan itu, saya tidak merekomendasikan Anda untuk mengerjakan semua soal. Yang lebih baik adalah, Anda menemukan proyek yang pas Anda sendiri. Mungkin Anda ingin menggunakan jaring saraf untuk mengklasifikasikan koleksi musik Anda. Atau untuk memprediksi harga saham. Atau terserah apa saja. Tetapi temukan proyek yang Anda sukai. Anda dapat mengabaikan soal-soal dalam buku ini, atau menggunakannya hanya sebagai inspirasi untuk mengerjakan proyek Anda sendiri. Berjuang dengan proyek yang Anda sukai akan mengajarkan Anda jauh lebih banyak daripada sekedar menyelesaikan soal dalam buku. Komitmen emosional
adalah kunci untuk menguasai suatu hal.

Bisa jadi, Anda mungkin tidak memiliki gagasan proyek untuk dikerjakan, setidaknya pada awal-awal membaca buku ini. Tidak masalah. Selesaikan soal-soal yang membuat Anda merasa termotivasi untuk mengerjakannya. Lalu gunakan soal dan bahan dari buku ini untuk membantu Anda mencari ide kreatif untuk proyek pribadi Anda.

# BAB 1 Menggunakan Jaringan Saraf untuk Mengenali Angka Tulisan Tangan

Sistem visual manusia adalah salah satu keajaiban dunia. Pertimbangkan urutan digit tulisan tangan berikut: 

![](http://neuralnetworksanddeeplearning.com/images/digits.png)

Kebanyakan orang akan dengan mudah mengenali angka-angka itu sebagai 504192. Akan tetapi, kemudahan itu menipu. Di setiap belahan otak kita, manusia memiliki korteks visual primer, yang dikenal dengan V1, yang mengandung 140 juta neuron, dan dengan puluhan miliar koneksi di antara mereka. Namun penglihatan manusia melibatkan tidak hanya V1, tetapi seluruh rangkaian korteks visual - V2, V3, V4, dan V5 – yang melakukan pemrosesan citra yang semakin kompleks. Kita membawa superkomputer di kepala kita, yang telah disempurnakan oleh proses evolusi selama ratusan juta tahun, dan diadaptasi secara hebat untuk memahami dunia visual. Mengenali angka tulisan tangan tidak mudah. Sebaliknya, kita manusia dengan luar biasa, sangat baik dalam memahami apa yang ditunjukkan oleh mata kita kepada kita. Tetapi hampir semua pekerjaan itu dilakukan secara tidak sadar. Jadi kita biasanya tidak menghargai betapa sulitnya masalah yang diselesaikan oleh sistem visual kita.

Pengenalan pola secara visual baru akan terasa sulit ketika Anda mencoba untuk membuat program komputer yang dapat mengenali angka-angka seperti di atas. Apa yang tampaknya mudah ketika kita melakukannya sendiri tiba-tiba menjadi sangat sulit. Intuisi sederhana tentang bagaimana kita mengenali bentuk bahwa "angka 9 memiliki bulatan di bagian atas, dan goresan vertikal di bagian kanan bawah" - berubah menjadi begitu sulit untuk diungkapkan secara algoritmik. Ketika Anda mencoba untuk membuat program pengenal angka dengan aturan yang seperti setepat mungkin, Anda akan dengan akan dengan mudah terjebak dalam berbagai pengecualian dan kasus-kasus khusus. Tampaknya tidak ada harapan bahwa sebuah komputer dapat mengenali sebuah digit angka.

Jaringan saraf (*neural networks*) mengatasi masalah di atas dengan cara yang berbeda. Idenya adalah untuk mengambil sejumlah besar contoh angka tulisan tangan (nantinya dikenal sebagai sebagai contoh untuk pelatihan pelatihan),

![](http://neuralnetworksanddeeplearning.com/images/mnist\_100\_digits.png)

dan kemudian mengembangkan sistem yang dapat belajar dari contoh-contoh pelatihan tersebut. Dengan kata lain, jaringan saraf (*neural networks*) menggunakan contoh-contoh untuk secara otomatis menyimpulkan aturan untuk mengenali angka tulisan tangan. Selanjutnya, dengan menambah jumlah contoh pelatihan, maka jaringan saraf (*neural networks*) dapat belajar lebih banyak tentang berbagai variasi tulisan tangan, dan dengan demikian meningkatkan akurasinya. Jadi, meskipun saya telah menunjukkan
sejumlah 100 digit pelatihan sebagaimana gambar di atas, mungkin kita bisa membangun pengenalan tulisan tangan yang lebih baik dengan menggunakan ribuan atau bahkan jutaan atau miliaran contoh digit pelatihan.

Dalam bab ini kita akan membuat program komputer yang mengimplementasikan jaringan saraf (*neural networks*) yang belajar
mengenali angka tulisan tangan. Program ini hanya memiliki 74 baris kode, dan tidak menggunakan pustaka jaringan saraf (*neural networks*) khusus. Tetapi program singkat ini dapat mengenali angka dengan akurasi lebih dari 96 persen, tanpa campur tangan manusia. Selanjutnya, dalam bab-bab selanjutnya kita akan mengembangkan ide-ide yang dapat meningkatkan akurasi hingga lebih dari 99 persen. Bahkan, *jaringan saraf (neural networks)* komersial terbaik sekarang sangat baik sehingga digunakan oleh bank untuk memproses cek bank, dan oleh kantor pos untuk mengenali alamat tujuan.

Kita akan berfokus pada pengenalan tulisan tangan karena ini adalah prototipe yang sangat baik untuk belajar tentang *jaringan saraf (neural networks)* pada umumnya. Sebagai sebuah prototipe, permasalahan ini begitu pas: ia sangat menantang - bukan hal yang mudah untuk mengenali angka tulisan tangan menggunakan komputer- tetapi tidak begitu sulit karena tidak membutuhkan solusi yang kompleks, atau mesin komputasi hebat. Selain itu, hal tersebut merupakan cara yang bagus untuk selanjutnya mengembangkan kita kepada teknik yang lebih maju, seperti *pembelajaran dalam (deep learning)*. Sehingga sepanjang buku ini kita akan kembali berulang kali mengerjakan solusi masalah pengenalan tulisan tangan. Dalam buku ini juga, kita akan membahas bagaimana ide-ide ini dapat diterapkan pada masalah lain dalam penglihatan komputer (computer vision), dan juga dalam pengenalan suara, pemrosesan bahasa alami, dan pekerjaan lainnya.

Tentu saja, jika titik bab ini hanya untuk membuat program komputer untuk mengenali angka tulisan tangan, maka bab ini akan sangat pendek\! Tetapi di sepanjang jalan, kita akan mempelajari banyak ide dasar tentang jaringan saraf, di antaranya meliputi dua jenis penting dari neuron buatan (yaitu perceptron dan neuron sigmoid), dan algoritma pembelajaran standar untuk jaringan saraf, yang dikenal sebagai penurunan gradien stokastik (stochastic gradient descent). Dalam bagian ini, saya berfokus pada penjelasana *mengapa* hal-hal dilakukan seperti itu, dan pada pembangunan intuisi jaringan saraf (*neural networks*) pada diri Anda. Hal itu membutuhkan pembahasan yang lebih panjang daripada jika saya hanya mempresentasikan teknik dasar dari kode yang dibuat. Tetapi itu hal tersebut jauh lebih baik baik bagi Anda karena Anda mendapatkan pemahaman yang lebih dalam. Di antara manfaatnya adalah, pada akhir bab ini kita akan berada dalam keadaan dapat memahami apa itu *pembelajaran dalam (deep learning)* itu, dan mengapa itu penting.

## Perceptron 

Apa itu jaringan saraf? Untuk memulai, saya akan menjelaskan jenis neuron buatan yang disebut perceptron . Perceptrons dikembangkan \[1\] pada 1950-an dan 1960-an oleh ilmuwan Frank Rosenblatt , diilhami oleh karya sebelumnya \[2\] oleh Warren McCulloch dan Walter Pitts . Saat ini, jauh lebih umum untuk menggunakan model neuron buatan lainnya dibandingkan model tersebut - dalam buku ini, dan dalam banyak penerapan modern dari jaringan saraf, model neuron utama yang lebih sering digunakan adalah yang disebut neuron sigmoid (sigmoid neuron). Kita akan mempelajari neuron sigmoid dengan segera. Tetapi untuk memahami mengapa neuron sigmoid didefinisikan seperti itu, ada baiknya meluangkan waktu untuk terlebih dahulu memahami apa itu perceptron.

Jadi bagaimana cara kerja perceptrons? Sebuah perceptron mengambil beberapa input biner, x1,x2, ... , dan menghasilkan output biner tunggal:

![](http://neuralnetworksanddeeplearning.com/images/tikz0.png)

Dalam contoh yang ditampilkan di gambar di atas perceptron memiliki tiga input, x1, x2, x3. Secara umum, dia dapat memiliki input lebih banyak atau lebih sedikit. Rosenblatt mengusulkan aturan sederhana untuk menghitung output. Dia memperkenalkan bobot , w1, w2, ..., yaitu bilangan real yang menyatakan pentingnya kontribusi masing-masing input terhadap output. Output neuron, 0 atau 1, ditentukan oleh apakah jumlah terbobot \(\sum_{\text{ij}}^{}{w_{j}x_{j}}\) kurang dari atau lebih besar dari beberapa nilai ambang batas . Sama seperti bobot, ambang adalah bilangan real yang merupakan parameter dari neuron. Untuk memasukkannya dalam istilah aljabar yang lebih tepat:

![](media/image4.png)

Hanya itulah cara kerja perceptron\!

Itulah model matematika dasar dari perceptron. Anda dapat memahami ide tentang perceptron dengan membayangkan bahwa itu adalah sebuah alat dapat membuat keputusan dengan menimbang fakta yang ada. Izinkan saya memberi contoh. Ini tentu bukan contoh yang nyata, tetapi mudah dimengerti, dan kita setelah itu akan memiliki contoh yang lebih nyata. Misalkan akhir pekan akan tiba, dan Anda telah mendengar bahwa akan ada festival kopi di kota Anda. Anda suka kopi, dan mencoba memutuskan apakah akan pergi ke festival atau tidak. Anda mungkin membuat keputusan dengan menimbang tiga faktor:

1.  Apakah cuacanya bagus?
2.  Apakah teman Anda bersedia menemani Anda?
3.  Apakah lokasi festival ini mudah dicapai dengan angkutan umum? (Karena Anda tidak punya mobil).

Kita dapat mewakili tiga faktor ini dengan tiga variabel biner yang sesuai x1, x2, dan x3. Misalnya, kita akan memiliki x1=1 jika cuacanya bagus, dan x1=0 jika cuacanya buruk. Demikian pula, x2=1 jika teman Anda ingin ikut pergi, dan x2=0 jika tidak. Sama juga untuk x3 yaitu x3=1 jika angkutan umum mudah mencapainya, dan x3=0 jika tidak.

Sekarang, anggaplah Anda benar-benar menyukai kopi, sehingga Anda senang pergi ke festival bahkan jika teman Anda tidak tertarik dan festival tersebut sulit untuk dicapai. Tapi mungkin juga Anda sangat membenci cuaca buruk, dan Anda tidak mungkin pergi ke festival jika cuacanya buruk. Anda dapat menggunakan perceptron untuk membuat model pengambilan keputusan semacam ini. Salah satu cara untuk melakukan ini adalah dengan memilih bobot w1=6 untuk cuaca, dan w2=2 dan w3=2 untuk kondisi lainnya. Nilai yang lebih besar dari w1 menunjukkan bahwa cuaca sangat berarti bagi Anda, lebih dari sekadar apakah teman Anda bergabung dengan Anda, atau mudahnya fasilitas angkutan umum. Akhirnya, anggaplah Anda memilih ambang batas 5 untuk perceptron tersebut. Dengan pilihan-pilihan ini, perceptron mengimplementasikan model pengambilan keputusan yang diinginkan, menghasilkan 1 setiap kali cuaca bagus, dan 0 setiap kali cuaca buruk. Dengan perceptron semacam itu, outputnya akan sama tidak peduli apakah teman Anda ingin ikut pergi, atau apakah angkutan umum yang mudah itu tersedia.

Dengan memvariasikan bobot dan ambang, kita bisa mendapatkan model pengambilan keputusan yang berbeda. Misalnya, misalkan kita memilih ambang 3. Kemudian perceptron akan memutuskan bahwa Anda harus pergi ke festival setiap kali cuaca baik atau ketika dua syarat festival itu dekat angkutan umum dan taman Anda bersedia ikut dengan Anda. Dengan kata lain, itu akan menjadi model pengambilan keputusan yang berbeda. Menurunkan ambang berarti Anda lebih bersedia pergi ke festival.

Tentu saja, perceptron bukanlah model yang memadai untuk menunjukkan pengambilan keputusan manusia\! Namun apa yang diilustrasikan oleh contoh tersebut adalah bagaimana perceptron dapat digunakan untuk menimbang berbagai jenis fakta untuk membuat keputusan. Sehingga menjadi masuk akal bahwa jaringan perceptron yang kompleks dapat membuat keputusan yang lebih baik:

![](http://neuralnetworksanddeeplearning.com/images/tikz1.png)

Dalam jaringan ini, kolom pertama dari perceptron - yang akan kita sebut *lapisan* pertama perceptron - membuat tiga keputusan yang sangat sederhana, dengan menimbang input berupa fakta. Bagaimana dengan perceptrons pada lapisan kedua? Masing-masing perceptrons pada lapisan kedua membuat keputusan dengan menimbang hasil dari lapisan pertama pengambilan keputusan. Dengan cara ini perceptron pada lapisan kedua dapat membuat keputusan yang lebih kompleks dan lebih abstrak daripada perceptron pada lapisan pertama. Keputusan yang lebih kompleks akan dapat dibuat oleh perceptron pada lapisan ketiga. Dengan cara ini, jaringan banyak lapis dari perceptron dapat digunakan dalam pengambilan keputusan yang sangat rumit.

Kebetulan saja, ketika saya mendefinisikan perceptron, saya mengatakan bahwa perceptron hanya memiliki satu output. Dalam jaringan pada gambar di atas perceptrons terlihat seperti mereka memiliki banyak keluaran. Sebenarnya, mereka masih memiliki output tunggal. Tanda panah keluar yang banyak dari setiap perceptron adalah hanya untuk menunjukkan bahwa satu keluaran dari perceptron digunakan sebagai input ke beberapa perceptron lain. Ini lebih mudah daripada menggambar satu garis output tunggal kemudian dibelah jadi banyak.

Mari kita sederhanakan cara kita menyatakan perceptrons. Kondisi \(\sum_{\text{ij}}^{}{w_{j}x_{j} > \text{threshold}}\) itu rumit, dan kita dapat membuat dua perubahan notasi untuk menyederhanakannya. Perubahan pertama adalah menulis \(\sum_{\text{ij}}^{}{w_{j}x_{j}}\) sebagai perkalian titik (dot product), \(w \bullet x = \sum_{\text{ij}}^{}{w_{j}x_{j}}\), yang mana *w* dan *x* adalah vektor yang masing-masing komponennya adalah bobot dan input. Perubahan kedua adalah memindahkan batas ambang (thershold) ke sisi lain dari pertidaksamaan tersebut, dan menggantikannya dengan apa yang dikenal sebagai *bias* perceptron, \(b \equiv - threshold\). Dengan menggunakan bias alih-alih ambang batas, aturan perceptron dapat ditulis ulang:

![](media/image6.png)

Anda dapat menganggap bias sebagai sebuah ukuran seberapa mudah bagi perceptron untuk menghasilkan 1. Atau dengan kata lain dalam istilah yang lebih biologis, bias adalah ukuran seberapa mudah untuk membuat perceptron *memicu* . Untuk perceptron dengan bias yang sangat besar, sangat mudah bagi perceptron untuk menghasilkan 1. Tetapi jika bias sangat negatif, maka sulit bagi perceptron untuk menghasilkan 1. Tentu saja, memperkenalkan konsep bias adalah sebuah perubahan kecil dalam cara menggambarkan perceptrons, tetapi kita akan melihat nanti bahwa hal itu mengarah pada penyederhanaan notasi lebih lanjut. Karena itu, sampai akhir buku ini kami tidak akan lagi menggunakan ambang batas (threshold), kami akan selalu menggunakan bias.

Saya telah menggambarkan perceptrons sebagai metode untuk menimbang fakta untuk membuat keputusan. Dalam perspektif lain, perceptrons dapat digunakan untuk menghitung fungsi-fungsi logika dasar yang lazimnya kita anggap sebagai dasar-dasar ilmu komputasi, yaitu fungsi-fungsi seperti AND , OR, dan NAND . Sebagai contoh, misalkan kita memiliki perceptron dengan dua input, masing-masing dengan bobot −2 , dan bias keseluruhan 3. Berikut ini perceptron kita:

![](http://neuralnetworksanddeeplearning.com/images/tikz2.png)

Kemudian kita dapat melihat bahaw input 00 akan menghasilkan output 1, arena (−2)∗0+(−2)∗0+3=3 adalah positif. Pada perhitungan ini, saya sekaligus memperkenalkan simbol ∗ untuk menyatakan secara eksplisit operasi perkalian. Perhitungan serupa menghasilkan bahwa input 01 dan 10 menghasilkan output 1. Tetapi input 11 menghasilkan output 0, karena (−2)∗1+(−2)∗1+3=−1 negatif. Dalam perceptron ini, kita telah mengimplementasikan sebuah gerbang NAND \!

Contoh NAND di atas telah menunjukkan bahwa kita dapat menggunakan perceptrons untuk menghitung fungsi logika sederhana. Akan tetapi sebenarnya, kita dapat menggunakan jaringan perceptrons untuk menghitung fungsi logika *apa pun* . Alasannya adalah karena gerbang NAND itu bersifat universal dalam komputasi logika, yaitu, kita dapat membangun komputasi logika apa pun dari gerbang NAND . Misalnya, kita dapat menggunakan gerbang NAND untuk membangun sirkuit yang menambahkan dua bit, *x*1 dan *x*2. Sirkuit penjumlahan membutuhkan dua perhitungan jaitu penjumlah bitwise, *x*1*+x*2, serta penghitungan carry bit yang ditetapkan ke 1 ketika *x*1 dan *x*2 adalah 1, yang berarti, carry bit itu adalah perkalian *x*1*x*2:

![](http://neuralnetworksanddeeplearning.com/images/tikz3.png)

\====

Untuk mendapatkan jaringan perceptron yang setara, kami mengganti semua gerbang NAND dengan perceptrons dengan dua input, masing-masing dengan bobot −2, dan bias keseluruhan sebesar 3. Inilah jaringan yang dihasilkan. Perhatikan bahwa saya telah memindahkan perceptron yang sesuai dengan gerbang NAND kanan bawah sedikit, hanya untuk mempermudah menggambar panah pada diagram:

![](http://neuralnetworksanddeeplearning.com/images/tikz4.png)

Salah satu aspek penting dari jaringan perceptron ini adalah bahwa output dari perceptron paling kiri digunakan dua kali sebagai input ke perceptron paling bawah. Ketika saya mendefinisikan model perceptron saya tidak mengatakan apakah jenis double-output-to-the-same-place diperbolehkan. Sebenarnya, tidak masalah. Jika kita tidak ingin mengizinkan hal semacam ini, maka dimungkinkan untuk hanya menggabungkan dua garis, menjadi satu koneksi dengan bobot -4 bukannya dua koneksi dengan bobot -2. (Jika Anda tidak menemukan ini jelas, Anda harus berhenti dan membuktikan kepada diri sendiri bahwa ini setara.) Dengan perubahan itu, jaringan terlihat sebagai berikut, dengan semua bobot tak bertanda sama dengan -2, semua bias sama dengan 3, dan berat tunggal -4, seperti yang ditandai:

![](http://neuralnetworksanddeeplearning.com/images/tikz5.png)

Hingga sekarang saya telah menggambar input seperti *x*1 dan *x*2 sebagai variabel yang mengambang di sebelah kiri jaringan perceptrons. Bahkan, itu konvensional untuk menggambar lapisan perceptrons tambahan - *lapisan input* - untuk menyandikan input:

![](http://neuralnetworksanddeeplearning.com/images/tikz6.png)

Notasi ini untuk input perceptrons, di mana kita memiliki output, tetapi tidak ada input,

![](http://neuralnetworksanddeeplearning.com/images/tikz7.png)

adalah sebuah steno. Sebenarnya bukan berarti perceptron tanpa input. Untuk melihat ini, misalkan kita memang memiliki perceptron tanpa input. Maka jumlah terbobot  *sumjwjxj* akan selalu nol, sehingga perceptron akan menghasilkan 1 jika *b*\>0, dan 0 jika *b* *leq*0. Artinya, perceptron hanya akan menghasilkan nilai tetap, bukan nilai yang diinginkan (*x*1, dalam contoh di atas). Lebih baik menganggap perceptron input sebagai tidak benar-benar menjadi perceptron sama sekali, melainkan unit khusus yang hanya didefinisikan untuk menampilkan nilai yang diinginkan, *x*1,*x*2, *ldots*.

Contoh penambah menunjukkan bagaimana jaringan perceptron dapat digunakan untuk mensimulasikan rangkaian yang berisi banyak gerbang NAND. Dan karena gerbang NAND bersifat universal untuk komputasi, maka perceptron juga universal untuk komputasi.

Universalitas komputasi dari perceptrons secara bersamaan meyakinkan dan mengecewakan. Ini meyakinkan karena memberi tahu kita bahwa jaringan perceptron bisa sekuat perangkat komputasi lainnya. Tapi itu juga mengecewakan, karena membuatnya seolah-olah perceptron hanyalah tipe baru dari gerbang NAND . Itu bukan berita besar\!

Namun, situasinya lebih baik dari pandangan ini. Ternyata kita dapat menyusun *algoritma pembelajaran* yang dapat secara otomatis
menyesuaikan bobot dan bias dari jaringan neuron buatan. Penyesuaian ini terjadi sebagai respons terhadap rangsangan eksternal, tanpa intervensi langsung oleh seorang programmer. Algoritma pembelajaran ini memungkinkan kita untuk menggunakan neuron buatan dengan cara yang secara radikal berbeda dengan gerbang logika konvensional. Alih-alih secara eksplisit menyusun sirkuit NAND dan gerbang lain, *jaringan saraf (neural networks)* kita dapat dengan mudah belajar untuk memecahkan masalah, kadang-kadang masalah di mana akan sangat sulit untuk secara langsung merancang sirkuit konvensional.

### Neuron Sigmoid 

Algoritma pembelajaran terdengar hebat. Tetapi bagaimana kita bisa membuat algoritma seperti itu untuk jaringan saraf? Misalkan kita memiliki jaringan perceptron yang ingin kita gunakan untuk belajar menyelesaikan beberapa masalah. Misalnya, input ke jaringan mungkin data piksel mentah dari gambar digit yang dipindai dengan tulisan tangan. Dan kami ingin jaringan mempelajari bobot dan bias sehingga output dari jaringan dengan benar mengklasifikasikan digit. Untuk melihat bagaimana pembelajaran mungkin bekerja, anggaplah kita membuat perubahan kecil dalam beberapa bobot (atau bias) dalam jaringan. Yang kami inginkan adalah perubahan kecil dalam bobot ini hanya menyebabkan perubahan kecil pada output dari jaringan. Seperti yang akan kita lihat sebentar lagi, properti ini akan memungkinkan pembelajaran. Secara skematis, inilah yang kami inginkan (jelas jaringan ini terlalu sederhana untuk melakukan pengenalan tulisan tangan\!):

![](http://neuralnetworksanddeeplearning.com/images/tikz8.png)

Jika benar bahwa perubahan kecil dalam bobot (atau bias) hanya menyebabkan perubahan kecil dalam output, maka kita bisa menggunakan fakta ini untuk memodifikasi bobot dan bias untuk membuat jaringan kita berperilaku lebih seperti yang kita inginkan. Misalnya, misalkan jaringan secara keliru mengklasifikasikan gambar sebagai "8" padahal seharusnya "9". Kita bisa mencari cara untuk membuat perubahan kecil pada bobot dan bias sehingga jaringan sedikit lebih dekat dengan mengklasifikasikan gambar sebagai "9". Dan kemudian kita akan mengulangi ini, mengubah bobot dan bias berulang untuk menghasilkan output yang lebih baik dan lebih baik. Jaringan akan belajar.

Masalahnya adalah ini bukan yang terjadi ketika jaringan kami mengandung perceptrons. Bahkan, perubahan kecil dalam bobot atau bias dari setiap perceptron tunggal dalam jaringan kadang-kadang dapat menyebabkan output dari perceptron itu benar-benar berubah, misalnya dari 0 ke 1. Balik itu kemudian dapat menyebabkan perilaku seluruh jaringan berubah sepenuhnya dalam beberapa cara yang sangat rumit. Jadi, sementara "9" Anda sekarang mungkin diklasifikasikan dengan benar, perilaku jaringan pada semua gambar lain kemungkinan telah benar-benar berubah dalam beberapa cara yang sulit dikendalikan. Itu membuatnya sulit untuk melihat bagaimana secara bertahap memodifikasi bobot dan bias sehingga jaringan lebih dekat dengan perilaku yang diinginkan. Mungkin ada beberapa cara pintar untuk mengatasi masalah ini. Tetapi tidak segera jelas bagaimana kita bisa mendapatkan jaringan perceptron untuk dipelajari.

Kita dapat mengatasi masalah ini dengan memperkenalkan jenis baru neuron buatan yang disebut neuron *sigmoid* . Neuron Sigmoid mirip dengan perceptron, tetapi dimodifikasi sehingga perubahan kecil dalam bobot dan biasnya hanya menyebabkan perubahan kecil pada outputnya. Itulah fakta penting yang akan memungkinkan jaringan neuron sigmoid untuk belajar.

Oke, izinkan saya menggambarkan neuron sigmoid. Kami akan menggambarkan neuron sigmoid dengan cara yang sama seperti kami menggambarkan perceptron:

![](http://neuralnetworksanddeeplearning.com/images/tikz9.png)

Sama seperti perceptron, neuron sigmoid memiliki input, *x*1,*x*2, *ldots*. Tetapi alih-alih hanya 0 atau 1, input ini juga dapat mengambil nilai *antara* 0 dan 1. Jadi, misalnya, 0,638 *ldots* adalah input yang valid untuk neuron sigmoid. Juga seperti perceptron,
neuron sigmoid memiliki bobot untuk setiap input, *w*1,*w*2, *ldots*, dan bias keseluruhan, *b*. Tetapi hasilnya bukan 0 atau 1. Alih-alih, ini  *sigma*(*w* *cdotx*+*b*), di mana  *sigma* disebut *fungsi sigmoid* \* \* Secara kebetulan,  *sigma* kadang-kadang disebut *fungsi logistik* , dan kelas neuron baru ini disebut *neuron logistik* . Sangat berguna untuk mengingat terminologi ini, karena istilah ini digunakan oleh banyak orang yang bekerja dengan jaring saraf. Namun, kami akan tetap menggunakan terminologi sigmoid. , dan didefinisikan oleh:   

\\ begin
{eqnarray} \\ sigma (z) \\ equiv \\ frac {1} {1 + e ^ {- z}}. \\ tag {3}
\\ end {eqnarray} Untuk membuatnya lebih jelas, output dari neuron
sigmoid dengan input *x*1,*x*2, *ldots*, bobot *w*1,*w*2, *ldots*, dan
bias *b* adalah \\ begin {eqnarray} \\ frac {1} {1+ \\ exp (- \\ sum\_j
w\_j x\_j-b)}. \\ tag {4} \\ end {eqnarray}

Pada pandangan pertama, neuron sigmoid tampak sangat berbeda dengan perceptron. Bentuk aljabar dari fungsi sigmoid mungkin tampak buram dan melarang jika Anda belum terbiasa dengannya. Faktanya, ada banyak kesamaan antara perceptron dan neuron sigmoid, dan bentuk aljabar dari fungsi sigmoid ternyata lebih merupakan detail teknis daripada hambatan sejati untuk memahami.

Untuk memahami kesamaan dengan model perceptron, anggaplah *z* *equivw* *cdotx*+*b* adalah angka positif yang besar. Kemudian *e*−*z* *sekitar*0 dan sigma (z) \\ sekitar 1 $. Dengan kata lain, ketika *z*=*w* *cdotx*+*b* besar dan positif, output dari neuron sigmoid adalah sekitar 1, sama seperti untuk perceptron. Misalkan di sisi lain *z*=*w* *cdotx*+*b* sangat negatif. Kemudian *e*−*z* *rightarrow* *infty*, dan *sigma*(*z*) *kira*−*kira*0. Jadi ketika *z*=*w* *cdotx*+*b* sangat negatif, perilaku neuron sigmoid juga mendekati sebuah perceptron. Hanya ketika *w* *cdotx*+*b* adalah ukuran sederhana bahwa ada banyak penyimpangan dari model perceptron.

Bagaimana dengan bentuk aljabar dari  *sigma* ? Bagaimana kita bisa mengerti itu? Bahkan, bentuk persis *sigma* tidak begitu penting - yang benar-benar penting adalah bentuk fungsi ketika diplot. Inilah bentuknya:

Bentuk ini adalah versi fungsi langkah yang dihaluskan:

Jika  *sigma*

sebenarnya merupakan fungsi langkah, maka neuron sigmoid akan *menjadi*
perceptron, karena outputnya menjadi 1 atau 0 tergantung pada apakah
*w* *cdotx*+*b* positif atau negatif \* \* Sebenarnya , ketika
*w* *cdotx*+*b*=0 output perceptron 0, sedangkan fungsi langkah
menghasilkan 1. Jadi, sebenarnya, kita perlu memodifikasi fungsi langkah
pada satu titik itu. Tetapi Anda mendapatkan idenya. . Dengan
menggunakan fungsi  *sigma* aktual yang kita dapatkan, seperti yang
sudah tersirat di atas, perceptron yang dihaluskan. Memang, kelancaran
fungsi  *sigma* itulah fakta penting, bukan bentuk detailnya. Kelancaran
 *sigma* berarti bahwa perubahan kecil  *Deltawj* dalam bobot dan
 *Deltab* dalam bias akan menghasilkan perubahan kecil
 *Delta* *mboxoutput* dalam output dari neuron. Bahkan, kalkulus
memberitahu kita bahwa  *Delta* *mboxoutput* diperkirakan dengan baik
oleh \\ begin {eqnarray} \\ Delta \\ mbox {output} \\ approx \\ sum\_j
\\ frac {\\ partial \\, \\ mbox {output}} {\\ partial w\_j} \\ Delta
w\_j + \\ frac {\\ partial \\, \\ mbox {output} } {\\ partial b} \\
Delta b, \\ tag {5} \\ end {eqnarray} di mana jumlahnya melebihi semua
bobot, *wj*, dan  *partial* *mboxoutput*/ *partialwj* dan
 *partial* *mboxoutput*/ *partialb* menunjukkan turunan parsial dari
 *mboxoutput* masing-masing berkaitan dengan *wj* dan *b*. Jangan panik
jika Anda tidak nyaman dengan turunan parsial\! Sementara ungkapan di
atas terlihat rumit, dengan semua turunan parsial, itu sebenarnya
mengatakan sesuatu yang sangat sederhana (dan yang merupakan kabar
baik):  *Delta* *mboxoutput* adalah *fungsi linear* dari perubahan
 *Deltawj* dan  *Deltab*

dalam bobot dan bias. Linieritas ini memudahkan untuk memilih perubahan
kecil dalam bobot dan bias untuk mencapai perubahan kecil apa pun yang
diinginkan pada output. Jadi sementara neuron sigmoid memiliki banyak
perilaku kualitatif yang sama dengan perceptron, mereka membuatnya lebih
mudah untuk mengetahui bagaimana mengubah bobot dan bias akan mengubah
output.

Jika bentuk  *sigma*

yang benar-benar penting, dan bukan bentuk yang tepat, lalu mengapa
menggunakan formulir khusus yang digunakan untuk  *sigma* dalam
Persamaan (3) ? Bahkan, nanti dalam buku ini kita kadang-kadang akan
mempertimbangkan neuron di mana outputnya adalah *f*(*w* *cdotx*+*b*)
untuk beberapa *fungsi aktivasi* lainnya *f*( *cdot*). Hal utama yang
berubah ketika kita menggunakan fungsi aktivasi yang berbeda adalah
bahwa nilai-nilai tertentu untuk turunan parsial dalam Persamaan (5)
perubahan. Ternyata ketika kita menghitung turunan parsial nanti,
menggunakan  *sigma* akan menyederhanakan aljabar, hanya karena
eksponensial memiliki sifat yang indah ketika dibedakan. Dalam kasus apa
pun,  *sigma*

biasanya digunakan untuk mengerjakan neural nets, dan merupakan fungsi
aktivasi yang paling sering kami gunakan dalam buku ini.

Bagaimana kita menafsirkan output dari neuron sigmoid? Jelas, satu
perbedaan besar antara perceptron dan neuron sigmoid adalah bahwa neuron
sigmoid tidak hanya menghasilkan 0

atau 1. Mereka dapat memiliki sebagai output bilangan real antara 0 dan
1, sehingga nilai-nilai seperti 0.173 *ldots* dan 0.689 *ldots* adalah
output yang sah. Ini dapat bermanfaat, misalnya, jika kita ingin
menggunakan nilai output untuk mewakili intensitas rata-rata piksel
dalam input gambar ke jaringan saraf. Tapi terkadang itu bisa jadi
gangguan. Misalkan kita ingin output dari jaringan menunjukkan "gambar
input adalah 9" atau "gambar input bukan 9". Jelas, akan lebih mudah
untuk melakukan ini jika outputnya adalah 0 atau 1, seperti dalam
perceptron. Tetapi dalam praktiknya kita dapat membuat konvensi untuk
menangani hal ini, misalnya, dengan memutuskan untuk menginterpretasikan
setiap output setidaknya 0,5 sebagai menunjukkan "9", dan setiap output
yang kurang dari 0,5

sebagai menunjukkan "bukan 9". Saya akan selalu menyatakan secara
eksplisit ketika kita menggunakan konvensi semacam itu, jadi seharusnya
tidak menyebabkan kebingungan.

#### [Latihan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#exercises_191892) 

  - **Neuron Sigmoid yang mensimulasikan perceptrons, bagian I**  *mbox*

Misalkan kita mengambil semua bobot dan bias dalam jaringan perceptrons,
dan mengalikannya dengan konstanta positif, *c*\>0

• . Tunjukkan bahwa perilaku jaringan tidak berubah.

• **Neuron Sigmoid yang mensimulasikan perceptron, bagian II**  *mbox*  
Misalkan kita memiliki pengaturan yang sama dengan masalah terakhir -
jaringan perceptrons. Misalkan juga bahwa keseluruhan input ke jaringan
perceptrons telah dipilih. Kami tidak akan membutuhkan nilai input
aktual, kami hanya perlu input sudah diperbaiki. Misalkan bobot dan
biasnya sedemikian rupa sehingga *w* *cdotx*+*b* *neq*0 untuk input *x*
untuk setiap perceptron tertentu dalam jaringan. Sekarang ganti semua
perceptron di jaringan dengan neuron sigmoid, dan gandakan bobot dan
bias dengan konstanta positif *c*\>0. Tunjukkan bahwa dalam batas
sebagai *c* *rightarrow* *infty* perilaku jaringan neuron sigmoid ini
persis sama dengan jaringan perceptron. Bagaimana ini bisa gagal ketika
*w* *cdotx*+*b*=0

  - untuk salah satu perceptrons?

### [Arsitektur jaringan saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#the_architecture_of_neural_networks) 

Pada bagian selanjutnya saya akan memperkenalkan *jaringan saraf (neural
networks)* yang dapat melakukan pekerjaan yang cukup baik
mengklasifikasikan angka tulisan tangan. Sebagai persiapan untuk itu,
ada baiknya dijelaskan beberapa terminologi yang memungkinkan kita
memberi nama berbagai bagian jaringan. Misalkan kita memiliki jaringan:

![http://neuralnetworksanddeeplearning.com/images/tikz10.png](media/image15.png)

Seperti yang disebutkan sebelumnya, lapisan paling kiri dalam jaringan
ini disebut lapisan input, dan neuron dalam lapisan disebut *input
neuron* . Lapisan paling kanan atau *keluaran* berisi *neuron keluaran*
, atau, seperti dalam kasus ini, neuron keluaran tunggal. Lapisan tengah
disebut *lapisan tersembunyi* , karena neuron di lapisan ini bukan input
maupun output. Istilah "tersembunyi" mungkin terdengar agak misterius -
pertama kali saya mendengar istilah itu saya pikir itu pasti memiliki
makna filosofis atau matematis yang mendalam - tetapi itu benar-benar
berarti tidak lebih dari "bukan input atau output". Jaringan di atas
hanya memiliki satu lapisan tersembunyi, tetapi beberapa jaringan
memiliki beberapa lapisan tersembunyi. Misalnya, jaringan empat lapis
berikut ini memiliki dua lapisan tersembunyi:

![http://neuralnetworksanddeeplearning.com/images/tikz11.png](media/image16.png)

Agak membingungkan, dan karena alasan historis, jaringan *berlapis* -
*lapis* seperti itu kadang-kadang disebut *multilayer perceptrons* atau
*MLPs* , meskipun terdiri dari neuron sigmoid, bukan perceptron. Saya
tidak akan menggunakan terminologi MLP dalam buku ini, karena saya pikir
itu membingungkan, tetapi ingin memperingatkan Anda tentang
keberadaannya.

Desain lapisan input dan output dalam jaringan seringkali mudah.
Misalnya, kita mencoba menentukan apakah gambar tulisan tangan
menggambarkan angka "9" atau tidak. Cara alami untuk merancang jaringan
adalah menyandikan intensitas piksel gambar ke dalam neuron input. Jika
gambar adalah 64

dengan 64 gambar skala abu-abu, maka kita akan memiliki
4.096=64 *kali*64 input neuron, dengan intensitas diskalakan tepat
antara 0 dan 1. Lapisan output akan berisi hanya satu neuron, dengan
nilai-nilai output kurang dari 0,5 menunjukkan "gambar input bukan 9",
dan nilai-nilai lebih besar dari 0,5

menunjukkan "gambar input adalah 9".

Sementara desain lapisan input dan output dari *jaringan saraf (neural
networks)* sering langsung, mungkin ada seni untuk desain lapisan
tersembunyi. Secara khusus, tidak mungkin untuk meringkas proses desain
untuk lapisan tersembunyi dengan beberapa aturan praktis sederhana.
Sebaliknya, para peneliti jaringan saraf (*neural networks*) telah
mengembangkan banyak heuristik desain untuk lapisan tersembunyi, yang
membantu orang mendapatkan perilaku yang mereka inginkan dari jaring
mereka. Misalnya, heuristik seperti itu dapat digunakan untuk membantu
menentukan cara menukar jumlah lapisan tersembunyi dengan waktu yang
diperlukan untuk melatih jaringan. Kami akan menemui beberapa heuristik
desain seperti itu nanti dalam buku ini.

Hingga saat ini, kami telah membahas jaringan saraf (*neural networks*)
di mana output dari satu lapisan digunakan sebagai input ke lapisan
berikutnya.Jaringan seperti itu disebut *jaringan saraf (neural
networks) feedforward* . Ini berarti tidak ada loop dalam jaringan -
informasi selalu diumpan maju, tidak pernah diumpan balik. Jika kita
memang memiliki loop, kita akan berakhir dengan situasi di mana input ke
fungsi bergantung pada output. Itu akan sulit untuk dipahami, jadi kami
tidak mengizinkan loop seperti itu.*σ*

Namun, ada model lain dari jaringan saraf (*neural networks*) tiruan di
mana loop umpan balik dimungkinkan. Model-model ini disebut [*jaringan
saraf (neural networks)*
berulang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Recurrent_neural_network&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiColxDFql7MqhYmEoKcGGEsKLv4w)
. Gagasan dalam model-model ini adalah untuk memiliki neuron yang
terbakar untuk jangka waktu terbatas, sebelum menjadi diam. Penembakan
itu dapat menstimulasi neuron lain, yang mungkin terbakar beberapa saat
kemudian, juga untuk durasi yang terbatas. Hal itu menyebabkan lebih
banyak lagi neuron yang terbakar, dan seiring berjalannya waktu kita
mendapatkan riam dari neuron yang ditembakkan. Loop tidak menyebabkan
masalah dalam model seperti itu, karena output neuron hanya memengaruhi
inputnya di lain waktu, tidak secara instan.

Jaring neural berulang kurang berpengaruh daripada jaringan feedforward,
sebagian karena algoritma pembelajaran untuk jaring berulang (setidaknya
sampai saat ini) kurang kuat. Tetapi jaringan berulang masih sangat
menarik. Semangat mereka jauh lebih dekat dengan cara kerja otak kita
daripada jaringan feedforward. Dan mungkin jaringan berulang dapat
memecahkan masalah penting yang hanya bisa diselesaikan dengan susah
payah oleh jaringan feedforward. Namun, untuk membatasi ruang lingkup
kami, dalam buku ini kami akan berkonsentrasi pada jaringan feedforward
yang lebih banyak digunakan.

### [Jaringan sederhana untuk mengklasifikasikan digit tulisan tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#a_simple_network_to_classify_handwritten_digits) 

Setelah mendefinisikan jaringan saraf, mari kita kembali ke pengenalan
tulisan tangan. Kita dapat membagi masalah mengenali angka tulisan
tangan menjadi dua sub-masalah. Pertama, kami ingin cara memecah gambar
yang berisi banyak digit ke dalam urutan gambar terpisah, masing-masing
berisi satu digit. Misalnya, kami ingin memecah gambar

![http://neuralnetworksanddeeplearning.com/images/digits.png](media/image1.png)

menjadi enam gambar terpisah,

![http://neuralnetworksanddeeplearning.com/images/digits\_separate.png](media/image17.png)

Kita manusia menyelesaikan *masalah segmentasi* ini dengan mudah, tetapi
sulit bagi program komputer untuk memecah gambar dengan benar. Setelah
gambar tersegmentasi, program perlu mengklasifikasikan setiap digit
individu. Jadi, misalnya, kami ingin program kami mengenali bahwa digit
pertama di atas,

![http://neuralnetworksanddeeplearning.com/images/mnist\_first\_digit.png](media/image18.png)

adalah 5.

Kami akan fokus pada penulisan program untuk menyelesaikan masalah
kedua, yaitu, mengklasifikasikan digit individu. Kami melakukan ini
karena ternyata masalah segmentasi tidak begitu sulit untuk dipecahkan,
setelah Anda memiliki cara yang baik untuk mengklasifikasikan digit
individu. Ada banyak pendekatan untuk memecahkan masalah segmentasi.
Salah satu pendekatan adalah dengan mencoba berbagai cara segmentasi
gambar, menggunakan pengelompokan digit individu untuk menilai setiap
segmentasi percobaan. Segmentasi percobaan mendapatkan skor tinggi jika
penggolong digit individu yakin akan klasifikasinya di semua segmen, dan
skor rendah jika penggolong tersebut mengalami banyak masalah dalam satu
segmen atau lebih. Idenya adalah bahwa jika classifier mengalami masalah
di suatu tempat, maka itu mungkin mengalami masalah karena segmentasi
telah dipilih secara tidak benar.Gagasan ini dan variasi lainnya dapat
digunakan untuk menyelesaikan masalah segmentasi dengan cukup baik. Jadi
alih-alih mengkhawatirkan segmentasi, kita akan berkonsentrasi pada
pengembangan jaringan saraf (*neural networks*) yang dapat memecahkan
masalah yang lebih menarik dan sulit, yaitu, mengenali digit tulisan
tangan individu.

Untuk mengenali masing-masing digit, kami akan menggunakan *jaringan
saraf (neural networks)* tiga lapis:

![http://neuralnetworksanddeeplearning.com/images/tikz12.png](media/image19.png)

Lapisan input jaringan berisi neuron yang mengkode nilai-nilai piksel
input. Seperti yang dibahas di bagian selanjutnya, data pelatihan kami
untuk jaringan akan terdiri dari banyak gambar oleh 28 piksel dari angka
tulisan tangan yang dipindai, dan lapisan input mengandung 784 = 28 × 28
neuron. Untuk mempermudah, saya telah menghilangkan sebagian besar input
neuron 784 pada diagram di atas. Pixel input berwarna abu-abu, dengan
nilai 0,0 mewakili putih, nilai 1,0 mewakili hitam, dan di antara nilai
mewakili gradasi warna abu-abu yang semakin gelap.28

28784=28×287840.01.0

Lapisan kedua dari jaringan adalah lapisan tersembunyi. Kami menunjukkan
jumlah neuron di lapisan tersembunyi ini oleh , dan kami akan
bereksperimen dengan nilai yang berbeda untuk n . Contoh yang
ditunjukkan menggambarkan lapisan kecil yang tersembunyi, yang
mengandung hanya n = 15 neuron.*n*

*nn*=15

Lapisan keluaran jaringan berisi 10 neuron. Jika neuron pertama menyala,
yaitu, memiliki output , maka itu akan menunjukkan bahwa jaringan
berpikir angka tersebut adalah 0 . Jika neuron kedua menyala maka itu
akan menunjukkan bahwa jaringan berpikir angka tersebut adalah 1 .≈1

01 Dan seterusnya.Sedikit lebih tepatnya, kami menghitung neuron
keluaran dari hingga 9 , dan mencari tahu neuron mana yang memiliki
nilai aktivasi tertinggi. Jika neuron itu, katakanlah, neuron nomor 6 ,
maka jaringan kami akan menebak bahwa digit input adalah 6 . Dan
seterusnya untuk neuron output lainnya.0966

Anda mungkin bertanya-tanya mengapa kami menggunakan neuron keluaran.
Lagi pula, tujuan jaringan adalah untuk memberi tahu kami digit mana ( 0
, 1 , 2 , ... , 9 ) yang sesuai dengan gambar input. Cara yang tampaknya
alami untuk melakukan itu adalah dengan menggunakan hanya 4 neuron
output, memperlakukan setiap neuron sebagai mengambil nilai biner,
tergantung pada apakah output neuron lebih dekat ke 0 atau ke 1 . Empat
neuron cukup untuk menyandikan jawaban, karena 2 4 = 16 lebih dari 10
nilai yang mungkin untuk digit input. Mengapa jaringan kami menggunakan
1010

0,1,2,…,940124=1610bukan neuron? Bukankah itu tidak efisien? Pembenaran
utama adalah empiris: kita dapat mencoba kedua desain jaringan, dan
ternyata, untuk masalah khusus ini, jaringan dengan neuron keluaran
belajar untuk mengenali digit lebih baik daripada jaringan dengan 4
neuron keluaran. Tapi itu membuat kita bertanya *-* tanya *mengapa*
menggunakan 10 neuron output bekerja lebih baik. Apakah ada beberapa
heuristik yang akan memberi tahu kita sebelumnya bahwa kita harus
menggunakan pengkodean 10 -out alih-alih 4 -output?10410104

Untuk memahami mengapa kami melakukan ini, ada baiknya memikirkan apa
yang dilakukan jaringan saraf (*neural networks*) dari prinsip pertama.
Pertimbangkan dulu kasus di mana kita menggunakan neuron keluaran. Mari
kita berkonsentrasi pada neuron output pertama, yang mencoba memutuskan
apakah digitnya 0 atau tidak . Ini dilakukan dengan menimbang bukti dari
lapisan neuron yang tersembunyi. Apa yang sedang dilakukan neuron-neuron
tersembunyi itu? Nah, anggap saja demi argumen bahwa neuron pertama di
lapisan tersembunyi mendeteksi apakah ada gambar seperti berikut ini:10

0

![http://neuralnetworksanddeeplearning.com/images/mnist\_top\_left\_feature.png](media/image20.png)

Ini dapat dilakukan dengan membobot piksel input yang tumpang tindih
dengan gambar, dan hanya membobot input lainnya dengan ringan. Dengan
cara yang sama, mari kita anggap demi argumen bahwa neuron kedua,
ketiga, dan keempat dalam lapisan tersembunyi mendeteksi apakah gambar
berikut ada atau tidak:

![http://neuralnetworksanddeeplearning.com/images/mnist\_other\_features.png](media/image21.png)

Seperti yang sudah Anda tebak, keempat gambar ini bersama-sama membentuk
gambar yang kami lihat di garis digit yang ditunjukkan
[sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#complete_zero)
:0

![http://neuralnetworksanddeeplearning.com/images/mnist\_complete\_zero.png](media/image22.png)

Jadi jika keempat neuron tersembunyi ini ditembakkan maka kita dapat
menyimpulkan bahwa digitnya adalah . Tentu saja, itu bukan *satu* -
*satunya* jenis bukti yang dapat kita gunakan untuk menyimpulkan bahwa
gambar itu 0 - kita bisa mendapatkan 0 secara sah dengan banyak cara
lain (katakanlah, melalui terjemahan gambar-gambar di atas, atau sedikit
distorsi). Tetapi tampaknya aman untuk mengatakan bahwa setidaknya dalam
kasus ini kita akan menyimpulkan bahwa inputnya adalah 0 .0

000

Misalkan fungsi jaringan saraf (*neural networks*) dengan cara ini, kita
bisa memberikan penjelasan yang masuk akal mengapa lebih baik memiliki
output dari jaringan, daripada 4 . Jika kita memiliki 4 output, maka
neuron output pertama akan mencoba untuk memutuskan apa bit paling
signifikan dari digit itu. Dan tidak ada cara mudah untuk menghubungkan
bit paling signifikan ke bentuk sederhana seperti yang ditunjukkan di
atas. Sulit untuk membayangkan bahwa ada alasan historis yang baik
mengapa bentuk komponen dari digit akan terkait erat dengan (katakanlah)
bit paling signifikan dalam output.10

44

Sekarang, dengan semua yang dikatakan, ini semua hanya heuristik. Tidak
ada yang mengatakan bahwa jaringan saraf (*neural networks*) tiga lapis
harus beroperasi seperti yang saya gambarkan, dengan neuron tersembunyi
yang mendeteksi bentuk komponen sederhana. Mungkin algoritma
pembelajaran yang cerdas akan menemukan beberapa tugas bobot yang
memungkinkan kita hanya menggunakan neuron output. Tetapi sebagai
heuristik cara berpikir yang saya jelaskan bekerja dengan sangat baik,
dan dapat menghemat banyak waktu Anda dalam merancang arsitektur
jaringan saraf (*neural networks*) yang baik.4

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#exercise_513527) 

  - Ada cara untuk menentukan representasi bitwise digit dengan
    menambahkan lapisan tambahan ke jaringan tiga lapis di atas. Lapisan
    tambahan mengubah output dari lapisan sebelumnya menjadi
    representasi biner, seperti yang diilustrasikan dalam gambar di
    bawah ini. Temukan seperangkat bobot dan bias untuk lapisan keluaran
    baru. Asumsikan bahwa lapisan neuron pertama adalah sedemikian
    sehingga output yang benar di lapisan ketiga (yaitu, lapisan output
    lama) memiliki aktivasi setidaknya 0,99 , dan output yang salah
    memiliki aktivasi kurang dari 0,01 .3

0.990.01

  - 
![http://neuralnetworksanddeeplearning.com/images/tikz13.png](media/image23.png)

### [Belajar dengan gradient descent](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#learning_with_gradient_descent) 

Sekarang kami memiliki desain untuk jaringan saraf (*neural networks*)
kami, bagaimana ia bisa belajar mengenali angka? Hal pertama yang kita
perlukan adalah kumpulan data untuk dipelajari - yang disebut set data
pelatihan. Kami akan menggunakan [set data
MNIST](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/mnist/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhHaBfKwPin41MRvcfSCOQQCRbjPg)
, yang berisi puluhan ribu gambar hasil pindaian tulisan tangan, bersama
dengan klasifikasi yang benar. Nama MNIST berasal dari fakta bahwa itu
adalah bagian yang dimodifikasi dari dua set data yang dikumpulkan oleh
[NIST](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/National_Institute_of_Standards_and_Technology&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhkHmoxRwgDoItB3PyFdGb1Nbv3Ag)
, Institut Nasional Standar dan Teknologi Amerika Serikat. Berikut
beberapa gambar dari MNIST:

![http://neuralnetworksanddeeplearning.com/images/digits\_separate.png](media/image17.png)

Seperti yang Anda lihat, angka-angka ini, pada kenyataannya, sama dengan
yang ditunjukkan pada [awal bab
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#complete_zero)
sebagai tantangan untuk dikenali. Tentu saja, ketika menguji jaringan
kami, kami akan meminta untuk mengenali gambar yang tidak ada dalam set
pelatihan\!

Data MNIST datang dalam dua bagian. Bagian pertama berisi 60.000 gambar
yang akan digunakan sebagai data pelatihan. Gambar-gambar ini adalah
sampel tulisan tangan yang dipindai dari 250 orang, setengah dari mereka
adalah pegawai Biro Sensus AS, dan setengahnya adalah siswa sekolah
menengah. Gambar berukuran abu-abu dan berukuran 28 kali 28 piksel.
Bagian kedua dari set data MNIST adalah 10.000 gambar yang akan
digunakan sebagai data uji. Sekali lagi, ini adalah 28 dengan 28 gambar
skala abu-abu. Kami akan menggunakan data uji untuk mengevaluasi
seberapa baik jaringan saraf (*neural networks*) kami telah belajar
mengenali angka. Untuk menjadikan ini sebagai tes kinerja yang baik,
data tes diambil dari yang *berbeda*set 250 orang dari data pelatihan
asli (meskipun masih kelompok dibagi antara karyawan Biro Sensus dan
siswa sekolah menengah). Ini membantu memberi kami keyakinan bahwa
sistem kami dapat mengenali angka dari orang-orang yang tulisannya tidak
dilihatnya selama pelatihan.

Kami akan menggunakan notasi untuk menunjukkan input pelatihan. Ini akan
mudah untuk menganggap setiap masukan pelatihan x sebagai 28 × 28 = 784
vektor berdimensi. Setiap entri dalam vektor mewakili nilai abu-abu
untuk satu piksel dalam gambar. Kami akan menunjukkan keluaran yang
diinginkan sesuai dengan y = y ( x ) , di mana y adalah vektor 10-
dimensi. Misalnya, jika gambar pelatihan tertentu, x , menggambarkan
angka 6 , maka y ( x ) = ( 0 , 0*x*

*x*28×28=784*y*=*y*(*x*)*y*10*x*6 adalah output yang diinginkan dari
jaringan. Perhatikan bahwa T di sini adalah operasi transpos, mengubah
vektor baris menjadi vektor (kolom)
biasa.*y*(*x*)=(0,0,0,0,0,0,1,0,0,0)*TT*

Apa yang kami inginkan adalah algoritma yang memungkinkan kami menemukan
bobot dan bias sehingga output dari jaringan mendekati untuk semua input
pelatihan x . Untuk mengukur seberapa baik kami mencapai tujuan ini,
kami mendefinisikan *fungsi biaya* \* \* Kadang-kadang disebut sebagai
fungsi *kerugian* atau *objektif* . Kami menggunakan fungsi biaya jangka
di seluruh buku ini, tetapi Anda harus mencatat terminologi lain, karena
sering digunakan dalam makalah penelitian dan diskusi lain dari jaringan
saraf.*y*(*x*)

*x* : Di sini,wmenunjukkan kumpulan semua bobot dalam jaringan,bsemua
bias,nadalah jumlah total input pelatihan,aadalah vektor output dari
jaringan ketikaxadalah input, dan jumlahnya adalah seluruh input
pelatihan,x. Tentu saja, outputatergantung padax,wdanb, tetapi untuk
menjaga notasi tetap sederhana, saya belum secara eksplisit
mengindikasikan ketergantungan ini. Notasi‖

*C*(*w*,*b*)≡12*n*∑*x*∥*y*(*x*)−*a*∥2.(6)

*wbnaxxaxwb* hanya menunjukkan fungsi panjang yang biasa untuk vektor v
. Kami akan memanggil C yang*kuadrat*fungsi biaya; terkadang juga
dikenal sebagai*mean squared error*atau hanya*MSE*. Memeriksa bentuk
fungsi biaya kuadratik, kita melihat bahwa C ( b , b ) adalah
non-negatif, karena setiap istilah dalam jumlah adalah non-negatif.
Selanjutnya, biaya C ( w , b ) menjadi kecil, yaitu, C ( w , b ) ≈ 0 ,
tepatnya ketika y∥*v*∥*vCC*(*w*,*b*)*C*(*w*,*b*)*C*(*w*,*b*)≈0 kira-kira
sama dengan output, a , untuk semua input pelatihan, x . Jadi algoritma
pelatihan kami telah melakukan pekerjaan dengan baik jika dapat
menemukan bobot dan bias sehingga C ( w , b ) ≈ 0 . Sebaliknya, itu
tidak bekerja dengan baik ketika C ( w , b ) besar - itu berarti bahwa y
( x ) tidak dekat dengan output a untuk sejumlah besar input. Jadi
tujuan dari algoritma pelatihan kami adalah untuk meminimalkan biaya C (
b , b*y*(*x*)*axC*(*w*,*b*)≈0*C*(*w*,*b*)*y*(*x*)*a* sebagai fungsi dari
bobot dan bias. Dengan kata lain, kami ingin menemukan serangkaian bobot
dan bias yang membuat biaya sekecil mungkin. Kami akan melakukannya
dengan menggunakan algoritma yang dikenal sebagai*gradient
descent*.*C*(*w*,*b*)

Mengapa memperkenalkan biaya kuadratik? Lagi pula, bukankah kita
terutama tertarik pada jumlah gambar yang diklasifikasikan dengan benar
oleh jaringan? Mengapa tidak mencoba memaksimalkan angka itu secara
langsung, daripada meminimalkan ukuran proxy seperti biaya kuadratik?
Masalahnya adalah bahwa jumlah gambar yang diklasifikasikan dengan benar
bukanlah fungsi yang mulus dari bobot dan bias dalam jaringan. Sebagian
besar, membuat perubahan kecil pada bobot dan bias tidak akan
menyebabkan perubahan sama sekali dalam jumlah gambar pelatihan yang
diklasifikasikan dengan benar. Itu membuatnya sulit untuk mencari tahu
bagaimana mengubah bobot dan bias untuk mendapatkan peningkatan kinerja.
Jika kita sebaliknya menggunakan fungsi biaya halus seperti biaya
kuadrat ternyata mudah untuk mencari tahu bagaimana membuat perubahan
kecil dalam bobot dan bias untuk mendapatkan peningkatan dalam biaya.
Bahwa'Itulah sebabnya kami fokus pertama pada meminimalkan biaya
kuadratik, dan hanya setelah itu kami akan memeriksa akurasi
klasifikasi.

Bahkan mengingat bahwa kami ingin menggunakan fungsi biaya yang lancar,
Anda mungkin masih bertanya-tanya mengapa kami memilih fungsi kuadratik
yang digunakan dalam Persamaan (6) .Bukankah ini pilihan yang agak *ad
hoc* ? Mungkin jika kita memilih fungsi biaya yang berbeda kita akan
mendapatkan serangkaian meminimalkan bobot dan bias? Ini adalah
kekhawatiran yang valid, dan nanti kami akan meninjau kembali fungsi
biaya, dan melakukan beberapa modifikasi. Namun, fungsi biaya kuadrat
dari Persamaan (6) bekerja dengan baik untuk memahami dasar-dasar
pembelajaran dalam jaringan saraf, jadi kami akan tetap menggunakannya
untuk saat ini.

Memulihkan, tujuan kami dalam melatih jaringan saraf (*neural networks*)
adalah untuk menemukan bobot dan bias yang meminimalkan fungsi biaya
kuadratik . Ini adalah masalah yang diajukan dengan baik, tetapi ada
banyak struktur yang mengganggu seperti saat ini diajukan - interpretasi
b dan b sebagai bobot dan bias, σ*C*(*w*,*b*)

*wbσ*

fungsi mengintai di latar belakang, pilihan arsitektur jaringan, MNIST,
dan sebagainya. Ternyata kita dapat memahami jumlah yang luar biasa
dengan mengabaikan sebagian besar struktur itu, dan hanya berkonsentrasi
pada aspek minimisasi. Jadi untuk saat ini kita akan melupakan semua
tentang bentuk spesifik dari fungsi biaya, koneksi ke jaringan saraf,
dan sebagainya. Sebagai gantinya, kita akan membayangkan bahwa kita
hanya diberi fungsi dari banyak variabel dan kami ingin meminimalkan
fungsi itu. Kita akan mengembangkan teknik yang disebut *gradient
descent* yang dapat digunakan untuk menyelesaikan masalah minimisasi
tersebut. Kemudian kita akan kembali ke fungsi spesifik yang ingin kita
perkecil untuk jaringan saraf.

Oke, misalkan kita mencoba untuk meminimalkan beberapa fungsi, . Ini
bisa berupa fungsi bernilai nyata dari banyak variabel, v = v 1 , v 2 ,
… . Perhatikan bahwa saya telah mengganti notasi w dan b dengan v
untuk menekankan bahwa ini bisa berupa fungsi apa pun - kita tidak lagi
secara khusus memikirkan konteks jaringan saraf. Untuk meminimalkan C (
v ) ada baiknya membayangkan C sebagai fungsi dari hanya dua variabel,
yang kita sebut v 1 dan v 2*C*(*v*)

*v*=*v*1,*v*2,…*wbvC*(*v*)*Cv*1*v*2

:

![http://neuralnetworksanddeeplearning.com/images/valley.png](media/image24.png)

Yang kami inginkan adalah menemukan di mana mencapai minimum globalnya.
Sekarang, tentu saja, untuk fungsi yang diplot di atas, kita dapat
melihat grafik dan menemukan minimum. Dalam hal itu, saya mungkin telah
menunjukkan fungsi yang sedikit *terlalu* sederhana\! Fungsi umum, C ,
mungkin merupakan fungsi rumit dari banyak variabel, dan biasanya tidak
akan mungkin hanya mengamati grafik untuk menemukan minimum.*C*

*C*

Salah satu cara untuk mengatasi masalah adalah dengan menggunakan
kalkulus untuk mencoba menemukan minimum secara analitis. Kita dapat
menghitung turunan dan kemudian mencoba menggunakannya untuk menemukan
tempat-tempat di mana adalah ekstrem. Dengan sedikit keberuntungan yang
mungkin berfungsi ketika C adalah fungsi dari hanya satu atau beberapa
variabel. Tapi itu akan berubah menjadi mimpi buruk ketika kita memiliki
lebih banyak variabel. Dan untuk jaringan saraf (*neural networks*) kita
akan sering ingin *jauh* lebih variabel - *jaringan saraf (neural
networks)* terbesar memiliki fungsi biaya yang tergantung pada miliaran
bobot dan bias dalam cara yang sangat rumit. Menggunakan kalkulus untuk
meminimalkan hal itu tidak akan berhasil\!*C*

*C*

(After asserting that we'll gain insight by imagining *C*

as a function of just two variables, I've turned around twice in two
paragraphs and said, "hey, but what if it's a function of many more than
two variables?" Sorry about that. Please believe me when I say that it
really does help to imagine *C*

as a function of two variables. It just happens that sometimes that
picture breaks down, and the last two paragraphs were dealing with such
breakdowns. Good thinking about mathematics often involves juggling
multiple intuitive pictures, learning when it's appropriate to use each
picture, and when it's not.)

Okay, so calculus doesn't work. Fortunately, there is a beautiful
analogy which suggests an algorithm which works pretty well. We start by
thinking of our function as a kind of a valley. If you squint just a
little at the plot above, that shouldn't be too hard. And we imagine a
ball rolling down the slope of the valley. Our everyday experience tells
us that the ball will eventually roll to the bottom of the valley.
Perhaps we can use this idea as a way to find a minimum for the
function? We'd randomly choose a starting point for an (imaginary) ball,
and then simulate the motion of the ball as it rolled down to the bottom
of the valley. We could do this simulation simply by computing
derivatives (and perhaps some second derivatives) of *C*

\- those derivatives would tell us everything we need to know about the
local "shape" of the valley, and therefore how our ball should roll.

Based on what I've just written, you might suppose that we'll be trying
to write down Newton's equations of motion for the ball, considering the
effects of friction and gravity, and so on. Actually, we're not going to
take the ball-rolling analogy quite that seriously - we're devising an
algorithm to minimize *C*

, not developing an accurate simulation of the laws of physics\! The
ball's-eye view is meant to stimulate our imagination, not constrain our
thinking. So rather than get into all the messy details of physics,
let's simply ask ourselves: if we were declared God for a day, and could
make up our own laws of physics, dictating to the ball how it should
roll, what law or laws of motion could we pick that would make it so the
ball always rolled to the bottom of the valley?

To make this question more precise, let's think about what happens when
we move the ball a small amount Δ*v*1

in the *v*1 direction, and a small amount Δ*v*2 in the *v*2 direction.
Calculus tells us that *C* changes as follows: 

Δ*C*≈∂*C*∂*v*1Δ*v*1+∂*C*∂*v*2Δ*v*2.(7)

We're going to find a way of choosing Δ*v*1 and Δ*v*2 so as to make Δ*C*
negative; ie, we'll choose them so the ball is rolling down into the
valley. To figure out how to make such a choice it helps to define Δ*v*
to be the vector of changes in *v*, Δ*v*≡(Δ*v*1,Δ*v*2)*T*, where *T* is
again the transpose operation, turning row vectors into column vectors.
We'll also define the *gradient* of *C* to be the vector of partial
derivatives, (∂*C*∂*v*1,∂*C*∂*v*2)*T*. We denote the gradient vector by
∇*C*, ie: 

∇*C*≡(∂*C*∂*v*1,∂*C*∂*v*2)*T*.(8)

In a moment we'll rewrite the change Δ*C* in terms of Δ*v* and the
gradient, ∇*C*. Before getting to that, though, I want to clarify
something that sometimes gets people hung up on the gradient. When
meeting the ∇*C* notation for the first time, people sometimes wonder
how they should think about the ∇ symbol. What, exactly, does ∇ mean? In
fact, it's perfectly fine to think of ∇*C* as a single mathematical
object - the vector defined above - which happens to be written using
two symbols. In this point of view, ∇ is just a piece of notational
flag-waving, telling you "hey, ∇*C* is a gradient vector". There are
more advanced points of view where ∇

can be viewed as an independent mathematical entity in its own right
(for example, as a differential operator), but we won't need such points
of view.

With these definitions, the expression (7) for Δ*C*

can be rewritten as 

Δ*C*≈∇*C*⋅Δ*v*.(9)

This equation helps explain why ∇*C* is called the gradient vector: ∇*C*
relates changes in *v* to changes in *C*, just as we'd expect something
called a gradient to do. But what's really exciting about the equation
is that it lets us see how to choose Δ*v* so as to make Δ*C* negative.
In particular, suppose we choose 

Δ*v*=−*η*∇*C*,(10)

where *η* is a small, positive parameter (known as the *learning rate*
). Then Equation (9) tells us that Δ*C*≈−*η*∇*C*⋅∇*C*=−*η*∥∇*C*∥2.
Because ∥∇*C*∥2≥0, this guarantees that Δ*C*≤0, ie, *C* will always
decrease, never increase, if we change *v* according to the prescription
in (10) . (Within, of course, the limits of the approximation in
Equation (9) ). This is exactly the property we wanted\! And so we'll
take Equation (10) to define the "law of motion" for the ball in our
gradient descent algorithm. That is, we'll use Equation (10) to compute
a value for Δ*v*, then move the ball's position *v* by that amount: 

*v*→*v*′=*v*−*η*∇*C*.(11)

Then we'll use this update rule again, to make another move. If we keep
doing this, over and over, we'll keep decreasing *C*

until - we hope - we reach a global minimum.

Summing up, the way the gradient descent algorithm works is to
repeatedly compute the gradient ∇*C*

, and then to move in the *opposite* direction, "falling down" the slope
of the valley. We can visualize it like this:

![http://neuralnetworksanddeeplearning.com/images/valley\_with\_ball.png](media/image25.png)

Notice that with this rule gradient descent doesn't reproduce real
physical motion. In real life a ball has momentum, and that momentum may
allow it to roll across the slope, or even (momentarily) roll uphill.
It's only after the effects of friction set in that the ball is
guaranteed to roll down into the valley. By contrast, our rule for
choosing Δ*v*

just says "go down, right now". That's still a pretty good rule for
finding the minimum\!

To make gradient descent work correctly, we need to choose the learning
rate *η*

to be small enough that Equation (9) is a good approximation. If we
don't, we might end up with Δ*C*\>0, which obviously would not be good\!
At the same time, we don't want *η* to be too small, since that will
make the changes Δ*v* tiny, and thus the gradient descent algorithm will
work very slowly. In practical implementations, *η*

is often varied so that Equation (9) remains a good approximation, but
the algorithm isn't too slow. We'll see later how this works.

I've explained gradient descent when *C*

is a function of just two variables. But, in fact, everything works just
as well even when *C* is a function of many more variables. Suppose in
particular that *C* is a function of *m* variables, *v*1,…,*vm*. Then
the change Δ*C* in *C* produced by a small change
Δ*v*=(Δ*v*1,…,Δ*vm*)*T* is 

Δ*C*≈∇*C*⋅Δ*v*,(12)

where the gradient ∇*C* is the vector 

∇*C*≡(∂*C*∂*v*1,…,∂*C*∂*vm*)*T*.(13)

Just as for the two variable case, we can choose 

Δ*v*=−*η*∇*C*,(14)

and we're guaranteed that our (approximate) expression (12) for Δ*C*
will be negative. This gives us a way of following the gradient to a
minimum, even when *C* is a function of many variables, by repeatedly
applying the update rule 

*v*→*v*′=*v*−*η*∇*C*.(15)

You can think of this update rule as *defining* the gradient descent
algorithm. It gives us a way of repeatedly changing the position *v* in
order to find a minimum of the function *C*. The rule doesn't always
work - several things can go wrong and prevent gradient descent from
finding the global minimum of *C*

, a point we'll return to explore in later chapters. But, in practice
gradient descent often works extremely well, and in neural networks
we'll find that it's a powerful way of minimizing the cost function, and
so helping the net learn.

Indeed, there's even a sense in which gradient descent is the optimal
strategy for searching for a minimum. Let's suppose that we're trying to
make a move Δ*v*

in position so as to decrease *C* as much as possible. This is
equivalent to minimizing Δ*C*≈∇*C*⋅Δ*v*. We'll constrain the size of the
move so that ∥Δ*v*∥=*ϵ* for some small fixed *ϵ*\>0. In other words, we
want a move that is a small step of a fixed size, and we're trying to
find the movement direction which decreases *C* as much as possible. It
can be proved that the choice of Δ*v* which minimizes ∇*C*⋅Δ*v* is
Δ*v*=−*η*∇*C*, where *η*=*ϵ*/∥∇*C*∥ is determined by the size
constraint ∥Δ*v*∥=*ϵ*. So gradient descent can be viewed as a way of
taking small steps in the direction which does the most to immediately
decrease *C*

.

#### [Latihan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#exercises_647181) 

  - Prove the assertion of the last paragraph. *Hint:* If you're not
    already familiar with the [Cauchy-Schwarz
    inequality](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Cauchy%25E2%2580%2593Schwarz_inequality&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhifCEZyqYTTRlQQeUKfhYpieQzbqQ)
    , you may find it helpful to familiarize yourself with it.

  - I explained gradient descent when *C*

is a function of two variables, and when it's a function of more than
two variables. What happens when *C*

  - is a function of just one variable? Can you provide a geometric
    interpretation of what gradient descent is doing in the
    one-dimensional case?

People have investigated many variations of gradient descent, including
variations that more closely mimic a real physical ball. These
ball-mimicking variations have some advantages, but also have a major
disadvantage: it turns out to be necessary to compute second partial
derivatives of *C*

, and this can be quite costly. To see why it's costly, suppose we want
to compute all the second partial derivatives ∂2*C*/∂*vj*∂*vk*. If there
are a million such *vj* variables then we'd need to compute something
like a trillion (ie, a million squared) second partial derivatives\*
\*Actually, more like half a trillion, since
∂2*C*/∂*vj*∂*vk*=∂2*C*/∂*vk*∂*vj*

. Still, you get the point. \! That's going to be computationally
costly. With that said, there are tricks for avoiding this kind of
problem, and finding alternatives to gradient descent is an active area
of investigation. But in this book we'll use gradient descent (and
variations) as our main approach to learning in neural networks.

How can we apply gradient descent to learn in a neural network? The idea
is to use gradient descent to find the weights *wk*

and biases *bl* which minimize the cost in Equation (6) . To see how
this works, let's restate the gradient descent update rule, with the
weights and biases replacing the variables *vj*. In other words, our
"position" now has components *wk* and *bl*, and the gradient vector
∇*C* has corresponding components ∂*C*/∂*wk* and ∂*C*/∂*bl*. Writing
out the gradient descent update rule in terms of components, we have 

*wkbl*→→*w*′*k*=*wk*−*η*∂*C*∂*wkb*′*l*=*bl*−*η*∂*C*∂*bl*.(16)(17)

By repeatedly applying this update rule we can "roll down the hill", and
hopefully find a minimum of the cost function. In other words, this is a
rule which can be used to learn in a neural network.

There are a number of challenges in applying the gradient descent rule.
We'll look into those in depth in later chapters. But for now I just
want to mention one problem. To understand what the problem is, let's
look back at the quadratic cost in Equation (6) . Notice that this cost
function has the form *C*=1*n*∑*xCx*

, that is, it's an average over costs *Cx*≡∥*y*(*x*)−*a*∥22 for
individual training examples. In practice, to compute the gradient ∇*C*
we need to compute the gradients ∇*Cx* separately for each training
input, *x*, and then average them, ∇*C*=1*n*∑*x*∇*Cx*

. Unfortunately, when the number of training inputs is very large this
can take a long time, and learning thus occurs slowly.

An idea called *stochastic gradient descent* can be used to speed up
learning. The idea is to estimate the gradient ∇*C*

by computing ∇*Cx* for a small sample of randomly chosen training
inputs. By averaging over this small sample it turns out that we can
quickly get a good estimate of the true gradient ∇*C*

, and this helps speed up gradient descent, and thus learning.

To make these ideas more precise, stochastic gradient descent works by
randomly picking out a small number *m*

of randomly chosen training inputs. We'll label those random training
inputs *X*1,*X*2,…,*Xm*, and refer to them as a *mini-batch* . Provided
the sample size *m* is large enough we expect that the average value of
the ∇*CXj* will be roughly equal to the average over all ∇*Cx*, that is,

∑*mj*=1∇*CXjm*≈∑*x*∇*Cxn*=∇*C*,(18)

where the second sum is over the entire set of training data. Swapping
sides we get 

∇*C*≈1*m*∑*j*=1*m*∇*CXj*,(19)

confirming that we can estimate the overall gradient by computing
gradients just for the randomly chosen mini-batch.

To connect this explicitly to learning in neural networks, suppose *wk*

and *bl* denote the weights and biases in our neural network. Then
stochastic gradient descent works by picking out a randomly chosen
mini-batch of training inputs, and training with those, 

*wkbl*→→*w*′*k*=*wk*−*ηm*∑*j*∂*CXj*∂*wkb*′*l*=*bl*−*ηm*∑*j*∂*CXj*∂*bl*,(20)(21)

where the sums are over all the training examples *Xj*

in the current mini-batch. Then we pick out another randomly chosen
mini-batch and train with those. And so on, until we've exhausted the
training inputs, which is said to complete an *epoch* of training. At
that point we start over with a new training epoch.

Incidentally, it's worth noting that conventions vary about scaling of
the cost function and of mini-batch updates to the weights and biases.
In Equation (6) we scaled the overall cost function by a factor 1*n*

. People sometimes omit the 1*n*, summing over the costs of individual
training examples instead of averaging. This is particularly useful when
the total number of training examples isn't known in advance. This can
occur if more training data is being generated in real time, for
instance. And, in a similar way, the mini-batch update rules (20) and
(21) sometimes omit the 1*m* term out the front of the sums.
Conceptually this makes little difference, since it's equivalent to
rescaling the learning rate *η*

. But when doing detailed comparisons of different work it's worth
watching out for.

We can think of stochastic gradient descent as being like political
polling: it's much easier to sample a small mini-batch than it is to
apply gradient descent to the full batch, just as carrying out a poll is
easier than running a full election. For example, if we have a training
set of size *n*=60,000

, as in MNIST, and choose a mini-batch size of (say) *m*=10, this means
we'll get a factor of 6,000 speedup in estimating the gradient\! Of
course, the estimate won't be perfect - there will be statistical
fluctuations - but it doesn't need to be perfect: all we really care
about is moving in a general direction that will help decrease *C*

, and that means we don't need an exact computation of the gradient. In
practice, stochastic gradient descent is a commonly used and powerful
technique for learning in neural networks, and it's the basis for most
of the learning techniques we'll develop in this book.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#exercise_263792) 

  - An extreme version of gradient descent is to use a mini-batch size
    of just 1. That is, given a training input, *x*

, we update our weights and biases according to the rules
*wk*→*w*′*k*=*wk*−*η*∂*Cx*/∂*wk* and
*bl*→*b*′*l*=*bl*−*η*∂*Cx*/∂*bl*. Then we choose another
training input, and update the weights and biases again. And so on,
repeatedly. This procedure is known as *online* , *on-line* , or
*incremental* learning. In online learning, a neural network learns from
just one training input at a time (just as human beings do). Name one
advantage and one disadvantage of online learning, compared to
stochastic gradient descent with a mini-batch size of, say, 20

  - .

Let me conclude this section by discussing a point that sometimes bugs
people new to gradient descent. In neural networks the cost *C*

is, of course, a function of many variables - all the weights and biases
- and so in some sense defines a surface in a very high-dimensional
space. Some people get hung up thinking: "Hey, I have to be able to
visualize all these extra dimensions". And they may start to worry: "I
can't think in four dimensions, let alone five (or five million)". Is
there some special ability they're missing, some ability that "real"
supermathematicians have? Of course, the answer is no. Even most
professional mathematicians can't visualize four dimensions especially
well, if at all. The trick they use, instead, is to develop other ways
of representing what's going on. That's exactly what we did above: we
used an algebraic (rather than visual) representation of Δ*C* to figure
out how to move so as to decrease *C*

. People who are good at thinking in high dimensions have a mental
library containing many different techniques along these lines; our
algebraic trick is just one example. Those techniques may not have the
simplicity we're accustomed to when visualizing three dimensions, but
once you build up a library of such techniques, you can get pretty good
at thinking in high dimensions. I won't go into more detail here, but if
you're interested then you may enjoy reading [this
discussion](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://mathoverflow.net/questions/25983/intuitive-crutches-for-higher-dimensional-thinking&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhJx53epT2kGEnOMT-YLWcZjYtLQQ)
of some of the techniques professional mathematicians use to think in
high dimensions. While some of the techniques discussed are quite
complex, much of the best content is intuitive and accessible, and could
be mastered by anyone.

### [Implementing our network to classify digits](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#implementing_our_network_to_classify_digits) 

Alright, let's write a program that learns how to recognize handwritten
digits, using stochastic gradient descent and the MNIST training data.
We'll do this with a short Python (2.7) program, just 74 lines of code\!
The first thing we need is to get the MNIST data. If you're a git user
then you can obtain the data by cloning the code repository for this
book,

git clone
https://github.com/mnielsen/neural-networks-and-deep-learning.git

If you don't use git then you can download the data and code
[here](https://github.com/mnielsen/neural-networks-and-deep-learning/archive/master.zip)
.

Incidentally, when I described the MNIST data earlier, I said it was
split into 60,000 training images, and 10,000 test images. That's the
official MNIST description. Actually, we're going to split the data a
little differently. We'll leave the test images as is, but split the
60,000-image MNIST training set into two parts: a set of 50,000 images,
which we'll use to train our neural network, and a separate 10,000 image
*validation set* . We won't use the validation data in this chapter, but
later in the book we'll find it useful in figuring out how to set
certain *hyper-parameters* of the neural network - things like the
learning rate, and so on, which aren't directly selected by our learning
algorithm. Although the validation data isn't part of the original MNIST
specification, many people use MNIST in this fashion, and the use of
validation data is common in neural networks. When I refer to the "MNIST
training data" from now on, I'll be referring to our 50,000 image data
set, not the original 60,000 image data set\* \*As noted earlier, the
MNIST data set is based on two data sets collected by NIST, the United
States' National Institute of Standards and Technology. To construct
MNIST the NIST data sets were stripped down and put into a more
convenient format by Yann LeCun, Corinna Cortes, and Christopher JC
Burges. See [this
link](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/mnist/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhHaBfKwPin41MRvcfSCOQQCRbjPg)
for more details. The data set in my repository is in a form that makes
it easy to load and manipulate the MNIST data in Python. I obtained this
particular form of the data from the LISA machine learning laboratory at
the University of Montreal (
[link](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://www.deeplearning.net/tutorial/gettingstarted.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg7R3WpUTGSH--OwNTJ3USl1-FSpg)
). .

Apart from the MNIST data we also need a Python library called
[Numpy](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://numpy.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjmYU7zir7C2Rn_RXHR1718aMfA-g)
, for doing fast linear algebra. If you don't already have Numpy
installed, you can get it
[here](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://www.scipy.org/install.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhxWHRnbJj4aZ0Bl3awAqT-hD-c6Q)
.

Let me explain the core features of the neural networks code, before
giving a full listing, below. The centerpiece is a Network class, which
we use to represent a neural network. Here's the code we use to
initialize a Network object:

class Network ( object ):

def \_\_init\_\_ ( self , sizes ):

diri num\_layers = len ( sizes )

diri sizes = sizes

diri biases = \[ np . random . randn ( y , 1 ) for y in sizes \[ 1 :\]\]

diri weights = \[ np . random . randn ( y , x )

for x , y in zip ( sizes \[: - 1 \], sizes \[ 1 :\])\]

In this code, the list sizes contains the number of neurons in the
respective layers. So, for example, if we want to create a Network
object with 2 neurons in the first layer, 3 neurons in the second layer,
and 1 neuron in the final layer, we'd do this with the code:

net = Network (\[ 2 , 3 , 1 \])

Bias dan bobot dalam objek Jaringan semuanya diinisialisasi secara acak,
menggunakan fungsi Numpy np.random.randn untuk menghasilkan distribusi
Gaussian dengan rata-rata dan standar deviasi 1 . Inisialisasi acak ini
memberikan tempat untuk memulai algoritma gradien gradien stokastik.
Dalam bab-bab selanjutnya kita akan menemukan cara yang lebih baik untuk
menginisialisasi bobot dan bias, tetapi ini akan berlaku untuk saat ini.
Perhatikan bahwa kode inisialisasi jaringan mengasumsikan bahwa lapisan
pertama dari neuron adalah lapisan input, dan dihilangkan untuk mengatur
bias apa pun untuk neuron-neuron tersebut, karena bias hanya pernah
digunakan dalam menghitung output dari lapisan selanjutnya.01

Note also that the biases and weights are stored as lists of Numpy
matrices. So, for example net.weights\[1\] is a Numpy matrix storing the
weights connecting the second and third layers of neurons. (It's not the
first and second layers, since Python's list indexing starts at 0 .)
Since net.weights\[1\] is rather verbose, let's just denote that matrix
*w*

. It's a matrix such that *wjk* is the weight for the connection between
the *k*th neuron in the second layer, and the *j*th neuron in the third
layer. This ordering of the *j* and *k* indices may seem strange -
surely it'd make more sense to swap the *j* and *k* indices around? The
big advantage of using this ordering is that it means that the vector of
activations of the third layer of neurons is: 

*a*′=*σ*(*wa*+*b*).(22)

There's quite a bit going on in this equation, so let's unpack it piece
by piece. *a* is the vector of activations of the second layer of
neurons. To obtain *a*′ we multiply *a* by the weight matrix *w*, and
add the vector *b* of biases. We then apply the function *σ* elementwise
to every entry in the vector *wa*+*b*. (This is called *vectorizing* the
function *σ*

.) It's easy to verify that Equation (22) gives the same result as our
earlier rule, Equation (4) , for computing the output of a sigmoid
neuron.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#exercise_358114) 

  - Write out Equation (22) in component form, and verify that it gives
    the same result as the rule (4) for computing the output of a
    sigmoid neuron.

With all this in mind, it's easy to write code computing the output from
a Network instance. We begin by defining the sigmoid function:

def sigmoid ( z ):

return 1.0 / ( 1.0 + np . exp ( - z ))

Perhatikan bahwa ketika input z adalah vektor atau array Numpy, Numpy
secara otomatis menerapkan fungsi sigmoid elementwise, yaitu dalam
bentuk vektor.

We then add a feedforward method to the Network class, which, given an
input a for the network, returns the corresponding output\* \*It is
assumed that the input a is an (n, 1) Numpy ndarray, not a (n,) vector.
Here, n is the number of inputs to the network. If you try to use an
(n,) vector as input you'll get strange results. Although using an (n,)
vector appears the more natural choice, using an (n, 1) ndarray makes it
particularly easy to modify the code to feedforward multiple inputs at
once, and that is sometimes convenient. . All the method does is applies
Equation (22) for each layer:

def feedforward ( self , a ):

"""Return the output of the network if "a" is input."""

for b , w in zip ( self . biases , self . weights ):

a = sigmoid ( np . dot ( w , a ) + b )

mengembalikan a

Of course, the main thing we want our Network objects to do is to learn.
To that end we'll give them an SGD method which implements stochastic
gradient descent. Here's the code. It's a little mysterious in a few
places, but I'll break it down below, after the listing.

def SGD ( self , training\_data , epochs , mini\_batch\_size , eta ,

test\_data = None ):

"""Train the neural network using mini-batch stochastic

gradient descent. The "training\_data" is a list of tuples

"(x, y)" representing the training inputs and the desired

output. The other non-optional parameters are

self-explanatory. If "test\_data" is provided then the

network will be evaluated against the test data after each

epoch, and partial progress printed out. This is useful for

tracking progress, but slows things down substantially."""

if test\_data : n\_test = len ( test\_data )

n = len ( training\_data )

for j in xrange ( epochs ):

random . shuffle ( training\_data )

mini\_batches = \[

training\_data \[ k : k + mini\_batch\_size \]

for k in xrange ( 0 , n , mini\_batch\_size )\]

for mini\_batch in mini\_batches :

diri update\_mini\_batch ( mini\_batch , eta )

if test\_data :

print "Epoch {0}: {1} / {2}" . format (

j , self . evaluate ( test\_data ), n\_test )

lain :

print "Epoch {0} complete" . format ( j )

The training\_data is a list of tuples (x, y) representing the training
inputs and corresponding desired outputs. The variables epochs and
mini\_batch\_size are what you'd expect - the number of epochs to train
for, and the size of the mini-batches to use when sampling. eta is the
learning rate, *η*

. If the optional argument test\_data is supplied, then the program will
evaluate the network after each epoch of training, and print out partial
progress. This is useful for tracking progress, but slows things down
substantially.

The code works as follows. In each epoch, it starts by randomly
shuffling the training data, and then partitions it into mini-batches of
the appropriate size. This is an easy way of sampling randomly from the
training data. Then for each mini\_batch we apply a single step of
gradient descent. This is done by the code
self.update\_mini\_batch(mini\_batch, eta) , which updates the network
weights and biases according to a single iteration of gradient descent,
using just the training data in mini\_batch . Here's the code for the
update\_mini\_batch method:

def update\_mini\_batch ( self , mini\_batch , eta ):

"""Update the network's weights and biases by applying

gradient descent using backpropagation to a single mini batch.

The "mini\_batch" is a list of tuples "(x, y)", and "eta"

is the learning rate."""

nabla\_b = \[ np . zeros ( b . shape ) for b in self . biases \]

nabla\_w = \[ np . zeros ( w . shape ) for w in self . weights \]

for x , y in mini\_batch :

delta\_nabla\_b , delta\_nabla\_w = self . backprop ( x , y )

nabla\_b = \[ nb + dnb for nb , dnb in zip ( nabla\_b , delta\_nabla\_b
)\]

nabla\_w = \[ nw + dnw for nw , dnw in zip ( nabla\_w , delta\_nabla\_w
)\]

diri weights = \[ w - ( eta / len ( mini\_batch )) \* nw

for w , nw in zip ( self . weights , nabla\_w )\]

diri bias = \[ b - ( eta / len ( mini\_batch )) \* nb

untuk b , nb dalam zip ( self . bias , nabla\_b )\]

Sebagian besar pekerjaan dilakukan oleh garis

delta\_nabla\_b , delta\_nabla\_w = mandiri . backprop ( x , y )

Ini memanggil sesuatu yang disebut algoritma *backpropagation* , yang
merupakan cara cepat untuk menghitung gradien dari fungsi biaya. Jadi
update\_mini\_batch bekerja hanya dengan menghitung gradien ini untuk
setiap contoh pelatihan di mini\_batch , dan kemudian memperbarui
self.weights dan self.biases dengan tepat.

Saya tidak akan menampilkan kode untuk self.backprop sekarang. Kami akan
mempelajari cara kerja backpropagation di bab selanjutnya, termasuk kode
untuk self.backprop . Untuk saat ini, anggap saja itu berperilaku
seperti diklaim, mengembalikan gradien yang sesuai untuk biaya yang
terkait dengan contoh pelatihan x .

Mari kita lihat program lengkapnya, termasuk string dokumentasi, yang
saya hilangkan di atas. Terlepas dari self.backprop program ini cukup
jelas - semua pekerjaan berat dilakukan di self.SGD dan
self.update\_mini\_batch , yang telah kita bahas. The self.backprop
Metode merek penggunaan beberapa fungsi tambahan untuk membantu dalam
menghitung gradien, yaitu sigmoid\_prime , yang menghitung turunan dari
fungsi, dan self.cost\_derivative*σ*

, yang tidak akan saya jelaskan di sini. Anda bisa mendapatkan inti dari
semua ini (dan mungkin detailnya) hanya dengan melihat kode dan string
dokumentasi. Kami akan melihat mereka secara rinci di bab berikutnya.
Perhatikan bahwa sementara program tampak panjang, sebagian besar kode
adalah string dokumentasi yang dimaksudkan untuk membuat kode mudah
dimengerti. Bahkan, program ini hanya berisi 74 baris kode non-spasi,
non-komentar. Semua kode dapat ditemukan di GitHub di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/network.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgDR3g24PY_1WVlyQXE7hoMkH0ixQ)
.

"" "

network.py

\~\~\~\~\~\~\~\~\~\~

Modul untuk mengimplementasikan

algoritma

pembelajaran gradien gradien stokastik untuk *jaringan saraf (neural
networks)* umpan maju. Gradien dihitung menggunakan backpropagation.
Perhatikan bahwa saya telah fokus membuat kode

sederhana, mudah dibaca, dan mudah dimodifikasi. Itu tidak dioptimalkan,

dan menghilangkan banyak fitur yang diinginkan.

"" "

\#\#\#\# Pustaka

\# Pustaka standar

impor acak

\# Pustaka pihak ketiga

impor numpy sebagai np

Jaringan kelas ( objek ):

def \_\_init\_\_ ( mandiri , ukuran ):

"" "Daftar\` \`size\`\` berisi jumlah neuron di

masing

\- masing lapisan jaringan. Misalnya, jika daftar itu \[2, 3, 1\] maka
akan menjadi jaringan tiga lapis, dengan

lapisan pertama berisi 2 neuron, neuron lapisan ketiga,

dan neuron lapisan ketiga 1. Bias dan bobot untuk

jaringan diinisialisasi secara acak, menggunakan

distribusi

Gaussian dengan rata-rata 0, dan varian 1. Catatan bahwa lapisan

pertama diasumsikan sebagai lapisan input, dan dengan konvensi kami
tidak akan menetapkan bias untuk neuron-neuron tersebut, karena bias
hanya

pernah digunakan dalam menghitung output dari lapisan selanjutnya. "" "

diri num\_layers = len ( sizes )

diri sizes = sizes

diri biases = \[ np . random . randn ( y , 1 ) for y in sizes \[ 1 :\]\]

diri weights = \[ np . random . randn ( y , x )

for x , y in zip ( sizes \[: - 1 \], sizes \[ 1 :\])\]

def feedforward ( self , a ):

"""Return the output of the network if \`\`a\`\` is input."""

for b , w in zip ( self . biases , self . weights ):

a = sigmoid ( np . dot ( w , a ) + b )

mengembalikan a

def SGD ( self , training\_data , epochs , mini\_batch\_size , eta ,

test\_data = None ):

"""Train the neural network using mini-batch stochastic

gradient descent. The \`\`training\_data\`\` is a list of tuples

\`\`(x, y)\`\` representing the training inputs and the desired

output. Parameter non-opsional lainnya cukup

jelas. Jika \`\` test\_data\`\` disediakan maka

jaringan akan dievaluasi terhadap data pengujian setelah setiap

zaman, dan sebagian kemajuan dicetak. Ini berguna untuk

melacak kemajuan, tetapi memperlambat segalanya secara substansial. "" "

Jika test\_data : n\_test = len ( test\_data )

n = len ( training\_data )

untuk j dalam xrange ( zaman ):

acak . Shuffle ( training\_data )

mini\_batches = \[

training\_data \[ k : k + mini\_batch\_size \]

untuk k di xrange ( 0 , n , mini\_batch\_size )\]

untuk mini\_batch di mini\_batches :

diri update\_mini\_batch ( mini\_batch , eta )

jika test\_data :

cetak "Epoch {0}: {1} / {2}" . Format (

j , diri . mengevaluasi ( test\_data ), n\_test )

lain :

cetak "Epoch {0} selesai" . format ( j )

def update\_mini\_batch ( self , mini\_batch , eta ):

"" "Perbarui bobot dan bias jaringan dengan menerapkan

gradient descent menggunakan backpropagation ke batch mini tunggal.\`

\`mini\_batch\`\` adalah daftar tupel\` \`(x, y)\` \`, dan\` \`eta\`\`

adalah tingkat pembelajaran." ""

nabla\_b = \[ np . nol ( b . bentuk ) untuk b di diri . bias \]

nabla\_w = \[ np . nol ( w . bentuk ) untuk w dalam diri . bobot \]

untuk x , y di mini\_batch :

delta\_nabla\_b , delta\_nabla\_w = mandiri . backprop ( x , y )

nabla\_b = \[ nb + dnb untuk nb , dnb dalam zip ( nabla\_b ,
delta\_nabla\_b )\]

nabla\_w = \[ nw + dnw untuk nw , dnw in zip ( nabla\_w ,
delta\_nabla\_w )\]

diri bobot = \[ w - ( eta / len ( mini\_batch )) \* nw

untuk w , nw in zip ( self . weights , nabla\_w )\]

diri bias = \[ b - ( eta / len ( mini\_batch )) \* nb

untuk b , nb dalam zip ( self . bias , nabla\_b )\]

def backprop ( self , x , y ):

"""Return a tuple \`\`(nabla\_b, nabla\_w)\`\` representing the

gradient for the cost function C\_x. \`\`nabla\_b\`\` and

\`\`nabla\_w\`\` are layer-by-layer lists of numpy arrays, similar

to \`\`self.biases\`\` and \`\`self.weights\`\`."""

nabla\_b = \[ np . zeros ( b . shape ) for b in self . biases \]

nabla\_w = \[ np . zeros ( w . shape ) for w in self . weights \]

\# feedforward

activation = x

activations = \[ x \] \# list to store all the activations, layer by
layer

zs = \[\] \# list to store all the z vectors, layer by layer

for b , w in zip ( self . biases , self . weights ):

z = np . dot ( w , aktivasi ) + b

zs . append ( z )

aktivasi = sigmoid ( z )

aktivasi . append ( aktivasi )

\# backward pass

delta = diri . cost\_derivative ( aktivasi \[ - 1 \], y ) \* \\

sigmoid\_prime ( zs \[ - 1 \])

nabla\_b \[ - 1 \] = delta

nabla\_w \[ - 1 \] = np . dot ( delta , activations \[ - 2 \] .
transpose ())

\# Note that the variable l in the loop below is used a little

\# differently to the notation in Chapter 2 of the book. Sini,

\# l = 1 means the last layer of neurons, l = 2 is the

\# second-last layer, and so on. It's a renumbering of the

\# scheme in the book, used here to take advantage of the fact

\# that Python can use negative indices in lists.

for l in xrange ( 2 , self . num\_layers ):

z = zs \[ - l \]

sp = sigmoid\_prime ( z )

delta = np . dot ( self . weights \[ - l + 1 \] . transpose (), delta )
\* sp

nabla\_b \[ - l \] = delta

nabla\_w \[ - l \] = np . dot ( delta , activations \[ - l - 1 \] .
transpose ())

return ( nabla\_b , nabla\_w )

def evaluate ( self , test\_data ):

"""Return the number of test inputs for which the neural

network outputs the correct result. Note that the neural

network's output is assumed to be the index of whichever

neuron in the final layer has the highest activation."""

test\_results = \[( np . argmax ( self . feedforward ( x )), y )

for ( x , y ) in test\_data \]

return sum ( int ( x == y ) for ( x , y ) in test\_results )

def cost\_derivative ( self , output\_activations , y ):

"""Return the vector of partial derivatives \\partial C\_x /

\\partial a for the output activations."""

return ( output\_activations - y )

\#\#\#\# Miscellaneous functions

def sigmoid ( z ):

"""The sigmoid function."""

return 1.0 / ( 1.0 + np . exp ( - z ))

def sigmoid\_prime ( z ):

"""Derivative of the sigmoid function."""

return sigmoid ( z ) \* ( 1 - sigmoid ( z ))

How well does the program recognize handwritten digits? Well, let's
start by loading in the MNIST data. I'll do this using a little helper
program, mnist\_loader.py , to be described below. We execute the
following commands in a Python shell,

\>\>\> import mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

Of course, this could also be done in a separate Python program, but if
you're following along it's probably easiest to do in a Python shell.

After loading the MNIST data, we'll set up a Network with 30

hidden neurons. We do this after importing the Python program listed
above, which is named network ,

\>\>\> import network

\>\>\> net = network . Network (\[ 784 , 30 , 10 \])

Finally, we'll use stochastic gradient descent to learn from the MNIST
training\_data over 30 epochs, with a mini-batch size of 10, and a
learning rate of *η*=3.0

,

\>\>\> net . SGD ( training\_data , 30 , 10 , 3.0 , test\_data =
test\_data )

Note that if you're running the code as you read along, it will take
some time to execute - for a typical machine (as of 2015) it will likely
take a few minutes to run. I suggest you set things running, continue to
read, and periodically check the output from the code. If you're in a
rush you can speed things up by decreasing the number of epochs, by
decreasing the number of hidden neurons, or by using only part of the
training data. Note that production code would be much, much faster:
these Python scripts are intended to help you understand how neural nets
work, not to be high-performance code\! And, of course, once we've
trained a network it can be run very quickly indeed, on almost any
computing platform. For example, once we've learned a good set of
weights and biases for a network, it can easily be ported to run in
Javascript in a web browser, or as a native app on a mobile device. In
any case, here is a partial transcript of the output of one training run
of the neural network. The transcript shows the number of test images
correctly recognized by the neural network after each epoch of training.
As you can see, after just a single epoch this has reached 9,129 out of
10,000, and the number continues to grow,

Epoch 0: 9129 / 10000

Epoch 1: 9295 / 10000

Epoch 2: 9348 / 10000

...

Epoch 27: 9528 / 10000

Epoch 28: 9542 / 10000

Epoch 29: 9534 / 10000

That is, the trained network gives us a classification rate of about 95

percent - 95.42

percent at its peak ("Epoch 28")\! That's quite encouraging as a first
attempt. I should warn you, however, that if you run the code then your
results are not necessarily going to be quite the same as mine, since
we'll be initializing our network using (different) random weights and
biases. To generate results in this chapter I've taken best-of-three
runs.

Let's rerun the above experiment, changing the number of hidden neurons
to 100

. As was the case earlier, if you're running the code as you read along,
you should be warned that it takes quite a while to execute (on my
machine this experiment takes tens of seconds for each training epoch),
so it's wise to continue reading in parallel while the code executes.

\>\>\> net = network . Network (\[ 784 , 100 , 10 \])

\>\>\> net . SGD ( training\_data , 30 , 10 , 3.0 , test\_data =
test\_data )

Sure enough, this improves the results to 96.59

percent. At least in this case, using more hidden neurons helps us get
better results\* \*Reader feedback indicates quite some variation in
results for this experiment, and some training runs give results quite a
bit worse. Using the techniques introduced in chapter 3 will greatly
reduce the variation in performance across different training runs for
our networks. .

Of course, to obtain these accuracies I had to make specific choices for
the number of epochs of training, the mini-batch size, and the learning
rate, *η*

. As I mentioned above, these are known as hyper-parameters for our
neural network, in order to distinguish them from the parameters
(weights and biases) learnt by our learning algorithm. If we choose our
hyper-parameters poorly, we can get bad results. Suppose, for example,
that we'd chosen the learning rate to be *η*=0.001

,

\>\>\> net = network . Network (\[ 784 , 100 , 10 \])

\>\>\> net . SGD ( training\_data , 30 , 10 , 0.001 , test\_data =
test\_data )

The results are much less encouraging,

Epoch 0: 1139 / 10000

Epoch 1: 1136 / 10000

Epoch 2: 1135 / 10000

...

Epoch 27: 2101 / 10000

Epoch 28: 2123 / 10000

Epoch 29: 2142 / 10000

Namun, Anda dapat melihat bahwa kinerja jaringan semakin lama semakin
baik. Itu menunjukkan peningkatan tingkat belajar, katakanlah . Jika
kita melakukan itu, kita mendapatkan hasil yang lebih baik, yang
menunjukkan peningkatan tingkat pembelajaran lagi. (Jika membuat
perubahan meningkatkan hal-hal, coba lakukan lebih banyak\!) Jika kita
melakukan itu beberapa kali lipat, kita akan berakhir dengan tingkat
pembelajaran sesuatu seperti η = 1.0 (dan mungkin fine tune ke 3.0 ),
yang dekat dengan kita percobaan sebelumnya. Jadi, meskipun pada awalnya
kami membuat pilihan parameter hiper yang buruk, kami setidaknya
mendapatkan informasi yang cukup untuk membantu kami meningkatkan
pilihan parameter hiper kami.*η*=0.01*η*=1.03.0

In general, debugging a neural network can be challenging. This is
especially true when the initial choice of hyper-parameters produces
results no better than random noise. Suppose we try the successful 30
hidden neuron network architecture from earlier, but with the learning
rate changed to *η*=100.0

:

\>\>\> net = network . Network (\[ 784 , 30 , 10 \])

\>\>\> net . SGD ( training\_data , 30 , 10 , 100.0 , test\_data =
test\_data )

Pada titik ini kita sudah terlalu jauh, dan tingkat pembelajarannya
terlalu tinggi:

Epoch 0 : 1009 / 10000

Epoch 1 : 1009 / 10000

Epoch 2 : 1009 / 10000

Epoch 3 : 1009 / 10000

...

Epoch 27 : 982 / 10000

Epoch 28 : 982 / 10000

Epoch 29 : 982 / 10000

Sekarang bayangkan bahwa kita akan membahas masalah ini untuk pertama
kalinya. Tentu saja, kami *tahu* dari percobaan kami sebelumnya bahwa
hal yang benar untuk dilakukan adalah mengurangi tingkat pembelajaran.
Tetapi jika kita sampai pada masalah ini untuk pertama kalinya maka
tidak akan ada banyak hasil untuk membimbing kita tentang apa yang harus
dilakukan. Kita mungkin khawatir tidak hanya tentang tingkat
pembelajaran, tetapi tentang setiap aspek lain dari *jaringan saraf
(neural networks)* kita. Kita mungkin bertanya-tanya apakah kita telah
menginisialisasi bobot dan bias dengan cara yang menyulitkan jaringan
untuk belajar? Atau mungkin kita tidak memiliki data pelatihan yang
cukup untuk mendapatkan pembelajaran yang bermakna? Mungkin kita belum
berlari untuk zaman yang cukup? Atau mungkin tidak mungkin bagi
jaringan saraf (*neural networks*) dengan arsitektur ini untuk belajar
mengenali angka tulisan tangan? Mungkin tingkat belajarnya terlalu
*rendah*? Atau, mungkin, tingkat pembelajarannya terlalu tinggi? Saat
Anda mengalami masalah untuk pertama kalinya, Anda tidak selalu yakin.

Pelajaran yang bisa diambil dari hal ini adalah bahwa men-debug
jaringan saraf (*neural networks*) bukan hal sepele, dan, seperti halnya
pemrograman biasa, ada seni untuk itu. Anda perlu mempelajari seni
debugging untuk mendapatkan hasil yang baik dari jaringan saraf. Secara
umum, kita perlu mengembangkan heuristik untuk memilih parameter yang
baik dan arsitektur yang baik. Kami akan membahas semua ini secara
panjang lebar melalui buku ini, termasuk bagaimana saya memilih
parameter hiper di atas.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#exercise_420023) 

  - Coba buat jaringan dengan hanya dua lapisan - input dan layer
    output, tanpa lapisan tersembunyi - dengan 784 dan 10 neuron,
    masing-masing. Melatih jaringan menggunakan keturunan gradien
    stokastik. Apa akurasi klasifikasi yang dapat Anda capai?

Earlier, I skipped over the details of how the MNIST data is loaded.
Cukup mudah. For completeness, here's the code. The data structures used
to store the MNIST data are described in the documentation strings -
it's straightforward stuff, tuples and lists of Numpy ndarray objects
(think of them as vectors if you're not familiar with ndarray s):

"" "

mnist\_loader

\~\~\~\~\~\~\~\~\~\~\~\~

A library to load the MNIST image data. For details of the data

structures that are returned, see the doc strings for \`\`load\_data\`\`

and \`\`load\_data\_wrapper\`\`. In practice,
\`\`load\_data\_wrapper\`\` is the

function usually called by our neural network code.

"" "

\#\#\#\# Libraries

\# Standard library

import cPickle

import gzip

\# Third-party libraries

impor numpy sebagai np

def load\_data ():

"""Return the MNIST data as a tuple containing the training data,

the validation data, and the test data.

The \`\`training\_data\`\` is returned as a tuple with two entries.

The first entry contains the actual training images. This is a

numpy ndarray with 50,000 entries. Each entry is, in turn, a

numpy ndarray with 784 values, representing the 28 \* 28 = 784

pixels in a single MNIST image.

The second entry in the \`\`training\_data\`\` tuple is a numpy ndarray

containing 50,000 entries. Those entries are just the digit

values (0...9) for the corresponding images contained in the first

entry of the tuple.

The \`\`validation\_data\`\` and \`\`test\_data\`\` are similar, except

each contains only 10,000 images.

This is a nice data format, but for use in neural networks it's

helpful to modify the format of the \`\`training\_data\`\` a little.

That's done in the wrapper function \`\`load\_data\_wrapper()\`\`, see

di bawah.

"" "

f = gzip . open ( '../data/mnist.pkl.gz' , 'rb' )

training\_data , validation\_data , test\_data = cPickle . load ( f )

f . close ()

return ( training\_data , validation\_data , test\_data )

def load\_data\_wrapper ():

"""Return a tuple containing \`\`(training\_data, validation\_data,

test\_data)\`\`. Based on \`\`load\_data\`\`, but the format is more

convenient for use in our implementation of neural networks.

In particular, \`\`training\_data\`\` is a list containing 50,000

2-tuples \`\`(x, y)\`\`. \`\`x\`\` is a 784-dimensional numpy.ndarray

containing the input image. \`\`y\`\` is a 10-dimensional

numpy.ndarray representing the unit vector corresponding to the

correct digit for \`\`x\`\`.

\`\`validation\_data\`\` and \`\`test\_data\`\` are lists containing
10,000

2-tuples \`\`(x, y)\`\`. In each case, \`\`x\`\` is a 784-dimensional

numpy.ndarry containing the input image, and \`\`y\`\` is the

corresponding classification, ie, the digit values (integers)

corresponding to \`\`x\`\`.

Obviously, this means we're using slightly different formats for

the training data and the validation / test data. These formats

turn out to be the most convenient for use in our neural network

code."""

tr\_d , va\_d , te\_d = load\_data ()

training\_inputs = \[ np . reshape ( x , ( 784 , 1 )) for x in tr\_d \[
0 \]\]

training\_results = \[ vectorized\_result ( y ) for y in tr\_d \[ 1 \]\]

training\_data = zip ( training\_inputs , training\_results )

validation\_inputs = \[ np . reshape ( x , ( 784 , 1 )) for x in va\_d
\[ 0 \]\]

validation\_data = zip ( validation\_inputs , va\_d \[ 1 \])

test\_inputs = \[ np . reshape ( x , ( 784 , 1 )) for x in te\_d \[ 0
\]\]

test\_data = zip ( test\_inputs , te\_d \[ 1 \])

return ( training\_data , validation\_data , test\_data )

def vectorized\_result ( j ):

"""Return a 10-dimensional unit vector with a 1.0 in the jth

position and zeroes elsewhere. This is used to convert a digit

(0...9) into a corresponding desired output from the neural

network."""

e = np . zeros (( 10 , 1 ))

e \[ j \] = 1.0

return e

I said above that our program gets pretty good results. Apa artinya?
Good compared to what? It's informative to have some simple
(non-neural-network) baseline tests to compare against, to understand
what it means to perform well. The simplest baseline of all, of course,
is to randomly guess the digit. That'll be right about ten percent of
the time. We're doing much better than that\!

What about a less trivial baseline? Let's try an extremely simple idea:
we'll look at how *dark* an image is. For instance, an image of a 2

will typically be quite a bit darker than an image of a 1

, just because more pixels are blackened out, as the following examples
illustrate:

![http://neuralnetworksanddeeplearning.com/images/mnist\_2\_and\_1.png](media/image26.png)

Ini menyarankan menggunakan data pelatihan untuk menghitung kegelapan
rata-rata untuk setiap digit, . Saat disajikan dengan gambar baru, kami
menghitung seberapa gelap gambar itu, dan kemudian tebak bahwa itu
adalah digit mana pun yang memiliki kegelapan rata-rata terdekat. Ini
adalah prosedur sederhana, dan mudah untuk dikodekan, jadi saya tidak
akan secara eksplisit menuliskan kode - jika Anda tertarik itu dalam
[repositori
GitHub](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/mnist_average_darkness.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgmHCPFRqcBmAvGSjob9e8RcqMNVA)
. Tapi ini adalah peningkatan besar dari tebakan acak, mendapatkan 2 ,
225 dari 10 , 000 gambar uji yang benar, yaitu akurasi 22,25
persen.0,1,2,…,9

2,22510,00022.25

Tidak sulit menemukan ide lain yang mencapai akurasi dalam kisaran
hingga 50 persen. Jika Anda bekerja sedikit lebih keras, Anda bisa
mendapatkan lebih dari 50 persen. Tetapi untuk mendapatkan akurasi yang
lebih tinggi, ada baiknya menggunakan algoritma pembelajaran mesin yang
sudah mapan. Mari kita coba menggunakan salah satu algoritma yang paling
dikenal, *mesin vektor dukungan* atau *SVM* . Jika Anda tidak terbiasa
dengan SVM, jangan khawatir, kami tidak perlu memahami detail cara kerja
SVM. Sebagai gantinya, kami akan menggunakan pustaka Python bernama
[scikit-learn](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://scikit-learn.org/stable/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhinPwCkQbI3gxYevLnEN0LxiVLmLw)
, yang menyediakan antarmuka Python sederhana ke pustaka berbasis C yang
cepat untuk SVM yang dikenal sebagai
[LIBSVM](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://www.csie.ntu.edu.tw/~cjlin/libsvm/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj1d9D-JkqDbSZJYRHf_RKQLaEYJQ)
.20

5050

Jika kita menjalankan classifier SVM scikit-learn menggunakan pengaturan
default, maka itu mendapatkan 9.435 dari 10.000 gambar uji yang benar.
(Kode tersedia di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/mnist_svm.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj5z3O71jyrUaHLaSBwWlV7N3eCag)
.) Itu peningkatan besar atas pendekatan naif kami dalam
mengklasifikasikan gambar berdasarkan seberapa gelap itu. Memang, itu
berarti bahwa SVM berkinerja kasar dan juga *jaringan saraf (neural
networks)* kita, hanya sedikit lebih buruk. Dalam bab-bab selanjutnya
kami akan memperkenalkan teknik-teknik baru yang memungkinkan kami untuk
meningkatkan jaringan saraf (*neural networks*) kami sehingga kinerjanya
jauh lebih baik daripada SVM.

Namun itu bukan akhir dari cerita. Hasil 9,435 dari 10.000 adalah untuk
pengaturan default scikit-learn untuk SVM. SVM memiliki sejumlah
parameter yang dapat disesuaikan, dan dimungkinkan untuk mencari
parameter yang meningkatkan kinerja out-of-the-box ini. Saya tidak akan
secara eksplisit melakukan pencarian ini, tetapi merujuk Anda ke
[posting blog
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://peekaboo-vision.blogspot.de/2010/09/mnist-for-ever.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgRpuaRAdHrOmnw4oojYTrtR23frg)
oleh [Andreas
Mueller](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://peekaboo-vision.blogspot.ca/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg_Kb1vaew11fGPa5EgAB8CxVNZsA)
jika Anda ingin tahu lebih banyak. Mueller menunjukkan bahwa dengan
beberapa pekerjaan mengoptimalkan parameter SVM itu mungkin untuk
mendapatkan kinerja di atas akurasi 98,5 persen. Dengan kata lain, SVM
yang disetel dengan baik hanya membuat kesalahan sekitar satu digit
dalam 70. Itu cukup bagus\! Bisakah jaringan saraf (*neural networks*)
(neural networks)lebih baik?

In fact, they can. At present, well-designed neural networks outperform
every other technique for solving MNIST, including SVMs. The current
(2013) record is classifying 9,979 of 10,000 images correctly. This was
done by [Li
Wan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://www.cs.nyu.edu/~wanli/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgCefcBG_xsuqC40-wE08DxDWhhSA)
, [Matthew
Zeiler](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://www.matthewzeiler.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiwrpLMjqXmWxtSpncFUkipTFT18g)
, Sixin Zhang, [Yann
LeCun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://yann.lecun.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgBwfmOUdKsx-2TH42ga-550noMsA)
, and [Rob
Fergus](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://cs.nyu.edu/~fergus/pmwiki/pmwiki.php&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh4-BIefHqt-y15xF11lyezc7-tYw)
. We'll see most of the techniques they used later in the book. At that
level the performance is close to human-equivalent, and is arguably
better, since quite a few of the MNIST images are difficult even for
humans to recognize with confidence, for example:

![http://neuralnetworksanddeeplearning.com/images/mnist\_really\_bad\_images.png](media/image27.png)

Saya percaya Anda akan setuju bahwa itu sulit untuk diklasifikasikan\!
Dengan gambar-gambar seperti ini di set data MNIST, sungguh luar biasa
bahwa jaringan saraf (*neural networks*) dapat secara akurat
mengklasifikasikan semua kecuali 21 dari 10.000 gambar uji. Biasanya,
ketika pemrograman kami percaya bahwa menyelesaikan masalah yang rumit
seperti mengenali angka MNIST membutuhkan algoritma yang canggih. Tetapi
bahkan jaringan saraf (*neural networks*) dalam makalah Wan *et al yang*
baru saja disebutkan melibatkan algoritma yang cukup sederhana, variasi
pada algoritma yang telah kita lihat dalam bab ini. Semua kerumitan
dipelajari, secara otomatis, dari data pelatihan. Dalam beberapa hal,
moral hasil kami dan orang-orang di makalah yang lebih canggih, adalah
bahwa untuk beberapa masalah:

Algoritma canggih Algoritma pembelajaran sederhana + data pelatihan yang
baik.≤

### [Menuju *pembelajaran dalam (deep learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhllgQ1UpKuN1D1Wc7Pw_eJHfIwiw#toward_deep_learning) 

Sementara jaringan saraf (*neural networks*) kami memberikan kinerja
yang mengesankan, kinerja itu agak misterius. Bobot dan bias dalam
jaringan ditemukan secara otomatis. Dan itu berarti kita tidak segera
memiliki penjelasan tentang bagaimana jaringan melakukan apa yang
dilakukannya. Bisakah kita menemukan cara untuk memahami prinsip-prinsip
yang digunakan jaringan kita untuk mengklasifikasikan angka tulisan
tangan? Dan, mengingat prinsip-prinsip tersebut, dapatkah kita berbuat
lebih baik?

Untuk mengajukan pertanyaan-pertanyaan ini dengan lebih jelas, anggaplah
bahwa beberapa dekade maka jaringan saraf (*neural networks*) mengarah
pada kecerdasan buatan (AI). Akankah kita memahami bagaimana jaringan
cerdas seperti itu bekerja? Mungkin jaringan akan menjadi buram bagi
kita, dengan bobot dan bias yang tidak kita pahami, karena mereka telah
dipelajari secara otomatis. Pada hari-hari awal penelitian AI orang
berharap bahwa upaya untuk membangun AI juga akan membantu kita memahami
prinsip-prinsip di balik kecerdasan dan, mungkin, fungsi otak manusia.
Tetapi mungkin hasilnya adalah bahwa kita akhirnya tidak memahami otak
atau bagaimana kecerdasan buatan bekerja\!

Untuk menjawab pertanyaan-pertanyaan ini, mari kita pikirkan kembali
interpretasi neuron buatan yang saya berikan pada awal bab ini, sebagai
alat untuk menimbang bukti. Misalkan kita ingin menentukan apakah suatu
gambar menunjukkan wajah manusia atau tidak:

Penghargaan: 1. [Ester
Inbar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://commons.wikimedia.org/wiki/User:ST&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhje_DwHbE7iwSCAuJXnweJZ0c-uxQ)
. 2. Tidak dikenal. 3. NASA, ESA, G. Illingworth, D. Magee, dan P. Oesch
(Universitas California, Santa Cruz), R. Bouwens (Universitas Leiden),
dan Tim HUDF09. Klik pada gambar untuk lebih jelasnya.

![http://neuralnetworksanddeeplearning.com/images/Kangaroo.JPG](media/image28.jpeg)![http://neuralnetworksanddeeplearning.com/images/Einstein\_crop.jpg](media/image29.jpeg)![http://neuralnetworksanddeeplearning.com/images/hubble.jpg](media/image30.jpeg)

Kita dapat menyerang masalah ini dengan cara yang sama seperti kita
menyerang pengenalan tulisan tangan - dengan menggunakan piksel pada
gambar sebagai input ke jaringan saraf, dengan output dari jaringan
neuron tunggal yang menunjukkan "Ya, itu wajah" atau "Tidak, itu bukan
wajah ".

Misalkan kita melakukan ini, tetapi kita tidak menggunakan algoritma
pembelajaran. Sebagai gantinya, kami akan mencoba merancang jaringan
dengan tangan, memilih bobot dan bias yang sesuai. Bagaimana mungkin
kita melakukannya? Lupa jaringan saraf (*neural networks*) sepenuhnya
untuk saat ini, heuristik yang bisa kita gunakan adalah untuk
menguraikan masalah menjadi sub-masalah: apakah gambar memiliki mata di
kiri atas? Apakah ada mata di kanan atas? Apakah hidungnya ada di
tengah? Apakah ada mulut di tengah bawah? Apakah ada rambut di atasnya?
Dan seterusnya.

Jika jawaban untuk beberapa pertanyaan ini adalah "ya", atau bahkan
"mungkin ya", maka kami akan menyimpulkan bahwa gambar tersebut
kemungkinan adalah wajah. Sebaliknya, jika jawaban untuk sebagian besar
pertanyaan adalah "tidak", maka gambar mungkin bukan wajah.

Tentu saja, ini hanya heuristik kasar, dan menderita banyak kekurangan.
Mungkin orang itu botak, jadi mereka tidak punya rambut. Mungkin kita
hanya bisa melihat sebagian wajah, atau wajah miring, sehingga beberapa
fitur wajah dikaburkan. Namun, heuristik menunjukkan bahwa jika kita
dapat menyelesaikan sub-masalah menggunakan jaringan saraf, maka mungkin
kita dapat membangun jaringan saraf (*neural networks*) untuk deteksi
wajah, dengan menggabungkan jaringan untuk sub-masalah. Berikut adalah
arsitektur yang mungkin, dengan persegi panjang yang menunjukkan
sub-jaringan. Perhatikan bahwa ini tidak dimaksudkan sebagai pendekatan
realistis untuk memecahkan masalah deteksi wajah; melainkan, ini untuk
membantu kami membangun intuisi tentang bagaimana fungsi jaringan.
Inilah arsitekturnya:

![http://neuralnetworksanddeeplearning.com/images/tikz14.png](media/image31.png)

Masuk akal juga bahwa sub-jaringan dapat diuraikan. Misalkan kita sedang
mempertimbangkan pertanyaan: "Apakah ada mata di kiri atas?" Ini dapat
diuraikan menjadi pertanyaan seperti: "Apakah ada alis?"; "Apakah ada
bulu mata?"; "Apakah ada iris?"; dan seterusnya.Tentu saja,
pertanyaan-pertanyaan ini harus benar-benar mencakup informasi posisi,
juga - "Apakah alis di kiri atas, dan di atas iris?", Hal semacam itu -
tetapi mari kita tetap sederhana. Jaringan menjawab pertanyaan "Apakah
ada mata di kiri atas?" sekarang dapat didekomposisi:

![http://neuralnetworksanddeeplearning.com/images/tikz15.png](media/image32.png)

Pertanyaan-pertanyaan itu juga dapat diuraikan, lebih jauh dan lebih
jauh melalui berbagai lapisan. Pada akhirnya, kami akan bekerja dengan
sub-jaringan yang menjawab pertanyaan sangat sederhana sehingga mereka
dapat dengan mudah dijawab pada tingkat piksel tunggal.
Pertanyaan-pertanyaan itu mungkin, misalnya, tentang ada atau tidaknya
bentuk yang sangat sederhana pada titik-titik tertentu dalam gambar.
Pertanyaan semacam itu dapat dijawab oleh neuron tunggal yang terhubung
ke piksel mentah pada gambar.

Hasil akhirnya adalah jaringan yang memecah pertanyaan yang sangat rumit
- apakah gambar ini menunjukkan wajah atau tidak - menjadi pertanyaan
yang sangat sederhana yang dapat dijawab pada tingkat piksel tunggal.
Ini melakukan ini melalui serangkaian banyak lapisan, dengan lapisan
awal menjawab pertanyaan yang sangat sederhana dan spesifik tentang
gambar input, dan lapisan kemudian membangun hierarki konsep yang lebih
kompleks dan abstrak. Jaringan dengan struktur banyak lapisan seperti
ini - dua atau lebih lapisan tersembunyi - disebut *jaringan saraf
(neural networks) dalam* .

Tentu saja, saya belum mengatakan bagaimana melakukan dekomposisi
rekursif ini ke dalam sub-jaringan. Jelas tidak praktis untuk mendesain
berat dan bias dalam jaringan secara manual. Alih-alih, kami ingin
menggunakan algoritma pembelajaran sehingga jaringan dapat secara
otomatis mempelajari bobot dan bias - dan dengan demikian, hierarki
konsep - dari data pelatihan. Para peneliti pada 1980-an dan 1990-an
mencoba menggunakan keturunan gradien stokastik dan backpropagation
untuk melatih jaringan yang dalam. Sayangnya, kecuali untuk beberapa
arsitektur khusus, mereka tidak memiliki banyak keberuntungan. Jaringan
akan belajar, tetapi sangat lambat, dan dalam praktik sering terlalu
lambat untuk berguna.

Sejak 2006, serangkaian teknik telah dikembangkan yang memungkinkan
pembelajaran di jaring saraf yang dalam. Teknik-teknik *pembelajaran
dalam (deep learning)* ini didasarkan pada keturunan gradien stokastik
dan backpropagation, tetapi juga memperkenalkan ide-ide baru.
Teknik-teknik ini telah memungkinkan jaringan yang lebih dalam (dan
lebih besar) untuk dilatih - orang-orang sekarang secara rutin melatih
jaringan dengan 5 hingga 10 lapisan tersembunyi. Dan, ternyata ini jauh
lebih baik pada banyak masalah daripada *jaringan saraf (neural
networks)* dangkal, yaitu jaringan dengan hanya satu lapisan
tersembunyi. Alasannya, tentu saja, adalah kemampuan jaring yang dalam
untuk membangun hierarki konsep yang kompleks. Ini agak seperti cara
bahasa pemrograman konvensional menggunakan desain modular dan ide-ide
tentang abstraksi untuk memungkinkan pembuatan program komputer yang
kompleks.Membandingkan jaringan yang dalam dengan jaringan yang dangkal
agak seperti membandingkan bahasa pemrograman dengan kemampuan untuk
membuat panggilan fungsi ke bahasa yang dipreteli tanpa kemampuan untuk
membuat panggilan seperti itu. Abstraksi mengambil bentuk yang berbeda
dalam jaringan saraf (*neural networks*) dibandingkan dengan pemrograman
konvensional, tetapi juga sama pentingnya.

Dalam karya akademis, silakan kutip buku ini sebagai: Michael A.
Nielsen, "Neural Networks dan Deep Learning", Determination Press,
2015  
  
Karya ini dilisensikan dengan [Lisensi Creative Commons
Attribution-NonCommercial 3.0
Unported](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=auto&sp=nmt4&tl=id&u=http://creativecommons.org/licenses/by-nc/3.0/deed.en_GB&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgr6ocxby5KfdeWeXs5dU5Rba4dlQ)
. Ini artinya Anda bebas menyalin, membagikan, dan membuat buku ini,
tetapi tidak untuk menjualnya. Jika Anda tertarik menggunakan komersial,
silakan [hubungi saya](mailto:mn@michaelnielsen.org) . Pembaruan
terakhir: Sel 11 Jun 16:58:53 2019  
  
  
![Lisensi Creative Commons](media/image33.png)

# [BAB 2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw) 

# [Cara kerja algoritma backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw) 

[jaringan saraf (*neural networks*) Tiruan dan Pembelajaran
Jauh](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhic73V7KqVjxIPGNbaQNJ2530s4GA)

[Tentang buku
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/about.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh4WEv8VZZCecHFGon_fBfEj9Fk-g)

[Tentang latihan dan
masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/exercises_and_problems.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgGXxYFYgdq20f8ymqVw5JGPzA2tA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Menggunakan
jaring saraf untuk mengenali angka tulisan
tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Cara
kerja algoritma
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Meningkatkan
cara belajar jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Bukti
visual bahwa jaring saraf dapat menghitung fungsi apa
pun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgzJKLAEjvxFJSTt899AGWkWymaQw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Mengapa
jaringan saraf (*neural networks*) yang dalam sulit untuk
dilatih?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[*Pembelajaran
dalam (deep
learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ)

[Lampiran: Apakah ada algoritma *sederhana* untuk
intelijen?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/sai.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi_r2W6B006rb7gK3F4bzy6prrdaQ)

[Ucapan Terima
Kasih](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/acknowledgements.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2YHKQpAuvZNHAiXn0Z6HVn-0KQA)

[Pertanyaan yang Sering
Diajukan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

Jika Anda mendapat manfaat dari buku ini, silakan berikan sumbangan
kecil. Saya menyarankan $ 5, tetapi Anda dapat memilih jumlahnya.

Top of Form

Bottom of Form

Sebagai alternatif, Anda dapat memberikan donasi dengan mengirimkan saya
Bitcoin, di alamat 1Kd6tXH5SDAmiFb49J9hknG5pqj7KStSAx

Sponsor  
![http://neuralnetworksanddeeplearning.com/assets/exxact.png](media/image36.png)

Workstation Deep Learning mulai dari $ 6.999: [pelajari lebih
lanjut](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.exxactcorp.com/Deep-Learning-NVIDIA-GPU-Solutions%3Futm_source%3Dneuralnetworksanddeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dsponsors&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj6rGsPToAcGlYjeEJXAHXJspW3eQ)

![http://neuralnetworksanddeeplearning.com/assets/lambda.png](media/image37.png)

[Workstation, Server, dan Laptop Belajar
dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://lambdalabs.com/%3Futm_source%3Dneuralnetworksdeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dblogin%26utm_content%3Drtext&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhmW9twAd-_7XhnUCemcjX98sl7gw)

![http://neuralnetworksanddeeplearning.com/assets/gsquared.png](media/image38.png)![http://neuralnetworksanddeeplearning.com/assets/tineye.png](media/image39.png)![http://neuralnetworksanddeeplearning.com/assets/visionsmarts.png](media/image40.png)

Terima kasih kepada semua
[pendukung](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/supporters.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj9HdVAwFQiYjPlo--NhrlXsSgZ2w)
yang memungkinkan buku ini, dengan terima kasih terutama kepada Pavel
Dudrenov. Terima kasih juga kepada semua kontributor di [Bugfinder Hall
of
Fame](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/bugfinder.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhbjVenylI9ODfotXyQdFoaBBrKaQ)
.

Sumber daya

[Michael Nielsen di
Twitter](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://twitter.com/michael_nielsen&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiM6kfoM32wXnoIMmahlwqfNqEWPg)

[Pesan
FAQ](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

[Repositori
kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhUDc58iR7PU8_gSuNnY9hUhxv0pw)

[Milis pengumuman proyek Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://eepurl.com/0Xxjb&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhCYC3lUQysyAb2pDyD_0ubQrqOeg)

[Deep
Learning](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.deeplearningbook.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhrv253n32Mv6Uv5S3BDOvpBcn5rg)
, buku karya Ian Goodfellow, Yoshua Bengio, dan Aaron Courville

[cognitivemedium.com](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://cognitivemedium.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgEBgr9y1U5WD3Da33Y88SX6zvRPA)

![http://neuralnetworksanddeeplearning.com/assets/Michael\_Nielsen\_Web\_Small.jpg](media/image41.jpeg)

Oleh [Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://michaelnielsen.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7zg7S5OLu9AePjnKFialijDRDZQ)
/ Jun 2019

Dalam [bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)
kita melihat bagaimana jaringan saraf (*neural networks*) dapat
mempelajari bobot dan bias mereka menggunakan algoritma gradient
descent. Namun, ada celah dalam penjelasan kami: kami tidak membahas
bagaimana menghitung gradien fungsi biaya. Kesenjangan yang cukup
besar\! Dalam bab ini saya akan menjelaskan algoritma cepat untuk
menghitung gradien tersebut, sebuah algoritma yang dikenal sebagai
*backpropagation* .

Algoritma backpropagation pada awalnya diperkenalkan pada tahun 1970-an,
tetapi kepentingannya tidak sepenuhnya dihargai sampai [kertas
tahun 1986 yang
terkenal](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.nature.com/nature/journal/v323/n6088/pdf/323533a0.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh4jxCt2IVbxz0shDabuxqgx5DYyA)
oleh [David
Rumelhart](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/David_Rumelhart&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgueuuPSk_-Nv0wzf_rx92PbxWDbg)
, [Geoffrey
Hinton](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.cs.toronto.edu/~hinton/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjaFpL094J8XmSCqxeQzYUZshrG9w)
, dan [Ronald
Williams](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Ronald_J._Williams&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhX4atnVOSsOvH63MQb6Xjzx0aRhw)
. Makalah itu menjelaskan beberapa jaringan saraf (*neural networks*) di
mana backpropagation bekerja jauh lebih cepat daripada pendekatan
sebelumnya untuk belajar, sehingga memungkinkan untuk menggunakan jaring
saraf untuk memecahkan masalah yang sebelumnya tidak dapat larut. Saat
ini, algoritma backpropagation adalah pekerja keras belajar di jaringan
saraf.

Bab ini lebih terlibat secara matematis daripada bagian lain dari buku
ini. Jika Anda tidak tergila-gila dengan matematika, Anda mungkin
tergoda untuk melewati bab ini, dan memperlakukan backpropagation
sebagai kotak hitam yang perinciannya tidak ingin Anda abaikan. Mengapa
meluangkan waktu untuk mempelajari detail-detail itu?

Alasannya, tentu saja, adalah pengertian. Inti dari backpropagation
adalah ekspresi turunan parsial  *partialC*/ *partialw*

dari fungsi biaya *C* sehubungan dengan bobot apa pun *w* (atau bias *b*

) dalam jaringan. Ekspresi memberi tahu kita seberapa cepat biaya
berubah ketika kita mengubah bobot dan bias. Dan meskipun ekspresinya
agak rumit, ia juga memiliki keindahannya, dengan setiap elemen memiliki
interpretasi yang alami dan intuitif. Jadi backpropagation bukan hanya
algoritma cepat untuk belajar. Ini benar-benar memberi kita wawasan
terperinci tentang bagaimana mengubah bobot dan bias mengubah perilaku
keseluruhan jaringan. Itu layak dipelajari secara detail.

Dengan itu, jika Anda ingin membaca bab, atau langsung ke bab
berikutnya, itu bagus. Saya telah menulis sisa buku agar dapat diakses
bahkan jika Anda memperlakukan backpropagation sebagai kotak hitam.
Tentu saja ada beberapa poin di buku ini di mana saya merujuk kembali ke
hasil dari bab ini. Tetapi pada titik-titik itu Anda masih harus bisa
memahami kesimpulan utama, bahkan jika Anda tidak mengikuti semua
alasannya.

### [Pemanasan: pendekatan berbasis matriks cepat untuk menghitung output dari jaringan saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#warm_up_a_fast_matrix-based_approach_to_computing_the_output_from_a_neural_network) 

Sebelum membahas backpropagation, mari kita pemanasan dengan algoritma
berbasis matriks cepat untuk menghitung output dari jaringan saraf. Kami
sebenarnya sudah melihat secara singkat algoritma ini di [dekat akhir
bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
, tapi saya jelaskan dengan cepat, jadi ada baiknya meninjau kembali
secara rinci. Secara khusus, ini adalah cara yang baik untuk merasa
nyaman dengan notasi yang digunakan dalam backpropagation, dalam konteks
yang akrab.

Mari kita mulai dengan notasi yang memungkinkan kita merujuk pada bobot
dalam jaringan dengan cara yang jelas. Kami akan menggunakan *wljk*

untuk menunjukkan bobot untuk koneksi dari *k* *rmth* neuron di
(*l*−1) *rmth* layer ke *j* *rmth* neuron di

^ {\\ rm th} $ layer. Jadi, misalnya, diagram di bawah ini menunjukkan
bobot pada koneksi dari neuron keempat di lapisan kedua ke neuron kedua
di lapisan ketiga jaringan:

![http://neuralnetworksanddeeplearning.com/images/tikz16.png](media/image42.png)

Notasi ini rumit pada awalnya, dan memang butuh beberapa pekerjaan untuk
dikuasai. Tetapi dengan sedikit usaha Anda akan menemukan notasi menjadi
mudah dan alami. Satu kekhasan dari notasi adalah pemesanan indeks *j*
dan *k*. Anda mungkin berpikir bahwa lebih masuk akal untuk menggunakan
*j* untuk merujuk ke neuron input, dan *k* ke neuron output, bukan
sebaliknya, seperti yang sebenarnya dilakukan. Saya akan menjelaskan
alasan kekhasan ini di bawah ini.

Kami menggunakan notasi serupa untuk bias dan aktivasi jaringan. Secara
eksplisit, kami menggunakan *blj*

untuk bias dari *j* *rmth* neuron di ^ {\\ rm th} $ layer. Dan kami
menggunakan *alj* untuk aktivasi ^ {\\ rm th} *neurondi*  *rmth*

layer. Diagram berikut menunjukkan contoh notasi ini yang digunakan:

![http://neuralnetworksanddeeplearning.com/images/tikz17.png](media/image43.png)

Dengan notasi-notasi ini, aktivasi *alj* dari *j* *rmth* neuron di
*l* *rmth* layer terkait dengan aktivasi di (*l*−1) *rmth* layer dengan
persamaan (bandingkan Persamaan (4) dan diskusi seputar di bab terakhir)
\\ begin {eqnarray} a ^ {l} \_j = \\ sigma \\ kiri (\\ sum\_k w ^ {l} \_
{jk} a ^ {l-1} \_k + b ^ l\_j \\ kanan), \\ tag {23} \\ end {eqnarray}
di mana jumlahnya lebih dari semua neuron *k* di (*l*−1) *rmth* layer.
Untuk menulis ulang ekspresi ini dalam bentuk matriks, kami
mendefinisikan *matriks bobot* *wl* untuk setiap lapisan, *l*. Entri
dari matriks bobot *wl* hanyalah bobot yang terhubung ke *l* *rmth*
lapisan neuron, yaitu entri dalam *j* *rmth* baris dan *k* *rmth* kolom
adalah *wljk*. Demikian pula, untuk setiap layer *l* kami mendefinisikan
*vektor bias* , *bl*. Anda mungkin bisa menebak cara kerjanya -
komponen-komponen dari vektor bias hanya nilai *blj*, satu komponen
untuk setiap neuron di ^ {\\ rm th} $ layer. Dan akhirnya, kita
mendefinisikan vektor aktivasi *al* yang komponennya adalah aktivasi
*alj*.

Bahan terakhir yang perlu kita tulis ulang (23) dalam bentuk matriks
adalah ide vectorizing suatu fungsi seperti  *sigma*

. Kami bertemu vektorisasi secara singkat di bab terakhir, tetapi untuk
rekap, idenya adalah bahwa kami ingin menerapkan fungsi seperti  *sigma*
ke setiap elemen dalam vektor *v*. Kami menggunakan notasi yang jelas
 *sigma*(*v*) untuk menunjukkan aplikasi semacam ini dari suatu fungsi.
Yaitu, komponen  *sigma*(*v*) hanya  *sigma*(*v*)*j*= *sigma*(*vj*).
Sebagai contoh, jika kita memiliki fungsi *f*(*x*)=*x*2 maka bentuk
vektor dari *f* memiliki efek \\ begin {eqnarray} f \\ kiri (\\ kiri
\[\\ begin {array} {c} 2 \\\\ 3 \\ end {array} \\ kanan\] \\ kanan) = \\
kiri \[\\ begin {array} {c} f (2 ) \\\\ f (3) \\ end {array} \\ kanan\]
= \\ kiri \[\\ begin {array} {c} 4 \\\\ 9 \\ end {array} \\ kanan\], \\
tag {24} \\ end {eqnarray} Yaitu, *f*

yang di-vektor-kan hanya persegi setiap elemen dari vektor.

Dengan memperhatikan notasi ini, Persamaan (23) dapat ditulis ulang
dalam bentuk vektor yang indah dan ringkas \\ begin {eqnarray} a ^ {l} =
\\ sigma (w ^ la ^ {l-1} + b ^ l). \\ tag {25} \\ end {eqnarray}
Ungkapan ini memberi kita cara berpikir yang jauh lebih global tentang
bagaimana aktivasi dalam satu lapisan berhubungan dengan aktivasi di
lapisan sebelumnya: kita hanya menerapkan matriks bobot ke aktivasi,
lalu tambahkan bias vektor, dan akhirnya menerapkan fungsi  *sigma*

\* \* Ngomong-ngomong, ungkapan inilah yang memotivasi quirk di notasi $
w ^ l\_ {jk} yang disebutkan sebelumnya. Jika kita menggunakan *j* untuk
mengindeks neuron input, dan *k*

untuk mengindeks neuron output, maka kita perlu mengganti matriks bobot
dalam Persamaan (25) oleh transpos dari matriks bobot. Itu adalah
perubahan kecil, tetapi menjengkelkan, dan kami akan kehilangan
kesederhanaan yang mudah dengan mengatakan (dan berpikir) "menerapkan
matriks bobot ke aktivasi". . Pandangan global itu seringkali lebih
mudah dan lebih ringkas (dan melibatkan lebih sedikit indeks\!) Daripada
pandangan neuron-oleh-neuron yang telah kita ambil sekarang. Anggap saja
sebagai cara keluar dari neraka indeks, sambil tetap tepat tentang apa
yang terjadi. Ekspresi ini juga berguna dalam praktiknya, karena
sebagian besar pustaka matriks menyediakan cara cepat untuk
mengimplementasikan perkalian matriks, penambahan vektor, dan
vektorisasi. Memang,
[kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
pada bab terakhir secara implisit menggunakan ungkapan ini untuk
menghitung perilaku jaringan.

Saat menggunakan Persamaan (25) untuk menghitung *al*

, kami menghitung kuantitas menengah *zl* *equivwlal*−1+*bl* di
sepanjang jalan. Kuantitas ini ternyata cukup bermanfaat sehingga layak
disebut: kita sebut *zl* *input terbobot* ke neuron di lapisan *l*. Kami
akan menggunakan cukup banyak input berbobot *zl* nanti dalam bab ini.
Persamaan (25) kadang-kadang ditulis dalam bentuk input terbobot,
sebagai *al*= *sigma*(*zl*). Perlu dicatat juga bahwa *zl* memiliki
komponen *zlj*= *sumkwljkal*−1*k*+*blj*, yaitu *zlj* hanyalah masukan
terbobot ke fungsi aktivasi untuk neuron *j* pada layer *l*

.

### [Dua asumsi yang kita butuhkan tentang fungsi biaya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_two_assumptions_we_need_about_the_cost_function) 

Tujuan backpropagation adalah untuk menghitung turunan parsial
 *partialC*/ *partialw*

dan  *partialC*/ *partialb* dari fungsi biaya *C* sehubungan dengan
bobot apa pun *w* atau bias *b* in jaringan. Agar backpropagation
berfungsi, kita perlu membuat dua asumsi utama tentang bentuk fungsi
biaya. Namun, sebelum menyatakan asumsi-asumsi itu, ada baiknya
memikirkan fungsi biaya contoh. Kami akan menggunakan fungsi biaya
kuadratik dari bab terakhir (cf Persamaan (6) ). Dalam notasi bagian
terakhir, biaya kuadratik memiliki formulir \\ begin {eqnarray} C = \\
frac {1} {2n} \\ sum\_x \\ | y (x) -a ^ L (x) \\ | ^ 2, \\ tag {26} \\
end {eqnarray} di mana: *n* adalah jumlah total contoh pelatihan;
jumlahnya lebih dari contoh pelatihan individu, *x*; *y*=*y*(*x*) adalah
output yang diinginkan yang sesuai; *L* menunjukkan jumlah lapisan dalam
jaringan; dan *aL*=*aL*(*x*) adalah vektor dari output aktivasi dari
jaringan ketika *x*

dimasukkan.

Oke, jadi asumsi apa yang perlu kita buat tentang fungsi biaya kita, *C*

, agar backpropagation dapat diterapkan? Asumsi pertama yang kita
butuhkan adalah bahwa fungsi biaya dapat ditulis sebagai rata-rata
*C*= *frac*1*n* *sumxCx* lebih dari fungsi biaya *Cx* untuk contoh
pelatihan individu, *x*. Ini adalah kasus untuk fungsi biaya kuadratik,
di mana biaya untuk contoh pelatihan tunggal adalah
*Cx*= *frac*12 |*yaL* |2

. Asumsi ini juga berlaku untuk semua fungsi biaya lain yang akan kita
temui dalam buku ini.

Alasan kita memerlukan asumsi ini adalah karena backpropagation yang
sebenarnya memungkinkan kita lakukan adalah menghitung derivatif parsial
 *partialCx*/ *partialw*

dan  *partialCx*/ *partialb* untuk contoh pelatihan tunggal. Kami
kemudian memulihkan  *partialC*/ *partialw* dan  *partialC*/ *partialb*
dengan rata-rata atas contoh pelatihan. Faktanya, dengan asumsi ini,
kita akan mengira contoh pelatihan *x* telah diperbaiki, dan menjatuhkan
subskrip *x*, menuliskan biaya *Cx* sebagai *C*. Kami akhirnya akan
memasukkan *x*

kembali, tetapi untuk sekarang ini adalah gangguan notasi yang lebih
baik dibiarkan tersirat.

Asumsi kedua yang kami buat tentang biaya adalah dapat ditulis sebagai
fungsi dari output dari jaringan saraf:

![http://neuralnetworksanddeeplearning.com/images/tikz18.png](media/image44.png)

Misalnya, fungsi biaya kuadrat memenuhi persyaratan ini, karena biaya
kuadrat untuk satu contoh pelatihan *x* dapat ditulis sebagai \\ begin
{eqnarray} C = \\ frac {1} {2} \\ | ya ^ L \\ | ^ 2 = \\ frac {1} {2} \\
sum\_j (y\_j-a ^ L\_j) ^ 2, \\ tag {27} \\ end {eqnarray} dan dengan
demikian merupakan fungsi dari aktivasi keluaran. Tentu saja, fungsi
biaya ini juga tergantung pada output yang diinginkan *y*, dan Anda
mungkin bertanya-tanya mengapa kami tidak menganggap biaya juga sebagai
fungsi dari *y*. Ingat, bagaimanapun, bahwa contoh pelatihan input *x*
sudah diperbaiki, dan output *y* juga merupakan parameter tetap. Secara
khusus, itu bukan sesuatu yang dapat kita modifikasi dengan mengubah
bobot dan bias dengan cara apa pun, yaitu, itu bukan sesuatu yang
dipelajari jaringan saraf. Jadi masuk akal untuk menganggap *C* sebagai
fungsi dari aktivasi output *aL* saja, dengan *y* hanya parameter yang
membantu mendefinisikan fungsi itu.

### [Produk Hadamard, <span class="underline">*s* *odott*</span>](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_hadamard_product_$s_\\\\odot_t$)

Algoritma backpropagation didasarkan pada operasi aljabar linear umum -
hal-hal seperti penambahan vektor, mengalikan vektor dengan matriks, dan
sebagainya. Tetapi salah satu operasi agak kurang umum digunakan. Secara
khusus, anggap *s*

dan *t* adalah dua vektor dari dimensi yang sama. Kemudian kita
menggunakan *s* *odott* untuk menunjukkan produk *elementwise* dari dua
vektor. Jadi komponen *s* *odott* hanya (*s* *odott*)*j*=*sjtj*

. Sebagai contoh, \\ begin {eqnarray} \\ kiri \[\\ begin {array} {c} 1
\\\\ 2 \\ end {array} \\ kanan\] \\ odot \\ kiri \[\\ begin {array} {c}
3 \\\\ 4 \\ end {array} \\ kanan\] = \\ kiri \[\\ mulai {array} {c} 1 \*
3 \\\\ 2 \* 4 \\ end {array} \\ kanan\] = \\ kiri \[\\ mulai {array} {c}
3 \\\\ 8 \\ end { array} \\ kanan\]. \\ tag {28} \\ end {eqnarray}
Semacam ini perkalian elemen kadang-kadang disebut *produk Hadamard*
atau *produk Schur* . Kami akan menyebutnya sebagai produk Hadamard.
Pustaka matriks yang baik biasanya memberikan implementasi cepat dari
produk Hadamard, dan itu sangat berguna ketika menerapkan
backpropagation.

### [Empat persamaan mendasar di balik backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_four_fundamental_equations_behind_backpropagation) 

Backpropagation adalah tentang memahami bagaimana mengubah bobot dan
bias dalam jaringan mengubah fungsi biaya. Pada akhirnya, ini berarti
menghitung derivatif parsial  *partialC*/ *partialwljk*

dan  *partialC*/ *partialblj*. Tetapi untuk menghitungnya, pertama-tama
kami perkenalkan kuantitas perantara,  *deltalj*, yang kami sebut
*kesalahan* dalam *j* *rmth* neuron di ^ {\\ rm th} $ layer.
Backpropagation akan memberi kita prosedur untuk menghitung kesalahan
 *deltalj*, dan kemudian akan menghubungkan  *deltalj* ke
 *partialC*/ *partialwljk* dan  *partialC*/ *partialblj*

.

Untuk memahami bagaimana kesalahan didefinisikan, bayangkan ada setan di
jaringan saraf (*neural networks*) kita:

![http://neuralnetworksanddeeplearning.com/images/tikz19.png](media/image45.png)

Setan itu duduk di *j* *rmth* neuron di layer *l*. Saat input ke neuron
masuk, iblis mengacaukan operasi neuron. Ia menambahkan sedikit
perubahan  *Deltazlj* ke input terbobot neuron, sehingga alih-alih
menghasilkan  *sigma*(*zlj*), neuron malah menghasilkan
 *sigma*(*zlj*+ *Deltazlj*). Perubahan ini menyebar melalui lapisan
selanjutnya dalam jaringan, akhirnya menyebabkan biaya keseluruhan
berubah dengan jumlah  *frac* *partialC* *partialzlj* *Deltazlj*.

Sekarang, iblis ini adalah iblis yang baik, dan berusaha membantu Anda
meningkatkan biaya, yaitu, mereka berusaha mencari  *Deltazlj*

yang membuat biayanya lebih kecil. Misalkan
 *frac* *partialC* *partialzlj* memiliki nilai yang besar (baik
positif atau negatif). Kemudian setan dapat menurunkan biaya sedikit
dengan memilih  *Deltazlj* untuk memiliki tanda kebalikan dari
 *frac* *partialC* *partialzlj*. Sebaliknya, jika
 *frac* *partialC* *partialzlj* mendekati nol, maka iblis tidak dapat
meningkatkan biaya sama sekali dengan mengganggu input terbobot *zlj*.
Sejauh iblis tahu, neuron sudah cukup dekat optimal \* \* Ini hanya
kasus untuk perubahan kecil  *Deltazlj*, tentu saja. Kami akan
menganggap bahwa iblis dibatasi untuk membuat perubahan kecil. . Jadi
ada pengertian heuristik di mana  *frac* *partialC* *partialzlj*

adalah ukuran kesalahan dalam neuron.

Termotivasi oleh cerita ini, kami mendefinisikan kesalahan  *deltalj*

neuron *j* di lapisan *l* oleh \\ begin {eqnarray} \\ delta ^ l\_j \\
equiv \\ frac {\\ partial C} {\\ partial z ^ l\_j}. \\ tag {29} \\ end
{eqnarray} Sesuai dengan konvensi kami yang biasa, kami menggunakan
 *deltal* untuk menunjukkan vektor kesalahan yang terkait dengan layer
*l*. Backpropagation akan memberi kita cara menghitung  *deltal* untuk
setiap lapisan, dan kemudian menghubungkan kesalahan-kesalahan itu
dengan jumlah bunga nyata,  *partialC*/ *partialwljk* dan
 *partialC*/ *sebagianblj*

.

Anda mungkin bertanya-tanya mengapa iblis mengubah input terbobot *zlj*

. Tentunya akan lebih alami untuk membayangkan setan mengubah aktivasi
output *alj*, dengan hasil bahwa kita akan menggunakan
 *frac* *partialC* *partialalj* sebagai ukuran kami untuk kesalahan.
Faktanya, jika Anda melakukan hal-hal ini bekerja sangat mirip dengan
diskusi di bawah ini. Tetapi ternyata membuat presentasi backpropagation
sedikit lebih rumit secara aljabar. Jadi kita akan tetap menggunakan
 *deltalj*= *frac* *partialC* *partialzlj* sebagai ukuran kesalahan
kita \* \* Dalam masalah klasifikasi seperti MNIST, istilah "kesalahan"
terkadang digunakan untuk mengartikan tingkat kegagalan klasifikasi.
Misalnya, jika jaringan saraf (*neural networks*) (neural
networks)dengan benar mengklasifikasikan 96,0 persen dari angka, maka
kesalahannya adalah 4,0 persen. Jelas, ini memiliki arti yang sangat
berbeda dari vektor  *delta*

kami. Dalam praktiknya, Anda seharusnya tidak kesulitan mengatakan arti
mana yang dimaksudkan dalam penggunaan apa pun. .

**Plan of attack:** Backpropagation didasarkan pada sekitar empat
persamaan mendasar. Bersama-sama, persamaan-persamaan itu memberi kita
cara menghitung kesalahan  *deltal*

dan gradien fungsi biaya. Saya nyatakan empat persamaan di bawah ini.
Namun, berhati-hatilah: Anda seharusnya tidak berharap untuk
mengasimilasi persamaan secara instan. Harapan seperti itu akan
menyebabkan kekecewaan. Sebenarnya, persamaan backpropagation sangat
kaya sehingga memahaminya dengan baik membutuhkan waktu dan kesabaran
yang besar saat Anda secara bertahap mempelajari lebih dalam ke dalam
persamaan. Kabar baiknya adalah bahwa kesabaran seperti itu dilunasi
berulang kali. Jadi diskusi di bagian ini hanyalah permulaan, membantu
Anda dalam perjalanan menuju pemahaman menyeluruh tentang persamaan.

Berikut adalah pratinjau cara-cara yang akan kami telusuri lebih dalam
pada persamaan nanti dalam bab ini: Saya akan [memberikan bukti singkat
dari
persamaan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#proof_of_the_four_fundamental_equations_\(optional\))
, yang membantu menjelaskan mengapa mereka benar; kami akan [menyatakan
kembali
persamaan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_backpropagation_algorithm)
dalam bentuk algoritmik sebagai pseudocode, dan [melihat
bagaimana](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_code_for_backpropagation)
pseudocode dapat diimplementasikan sebagai nyata, menjalankan kode
Python; dan, di [bagian akhir bab
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#backpropagation_the_big_picture)
, kita akan mengembangkan gambaran intuitif tentang apa arti persamaan
backpropagation, dan bagaimana seseorang dapat menemukannya dari awal.
Sepanjang jalan kita akan kembali berulang kali ke empat persamaan
mendasar, dan ketika Anda memperdalam pemahaman Anda, persamaan tersebut
akan terasa nyaman dan, mungkin, bahkan indah dan alami.

**Persamaan untuk kesalahan di lapisan output,  *deltaL***

**:** Komponen  *deltaL* diberikan oleh \\ begin {eqnarray} \\ delta ^
L\_j = \\ frac {\\ partial C} {\\ partial a ^ L\_j} \\ sigma '(z ^
L\_j). \\ tag {BP1} \\ end {eqnarray} Ini adalah ungkapan yang sangat
alami. Istilah pertama di sebelah kanan,  *partialC*/ *partialaLj*,
hanya mengukur seberapa cepat biaya berubah sebagai fungsi dari
*j* *rmth* aktivasi aktivasi output. Jika, misalnya, *C* tidak banyak
bergantung pada neuron output tertentu, *j*, maka  *deltaLj* akan kecil,
dan itulah yang kami harapkan. Istilah kedua di sebelah kanan,
 *sigma*′(*zLj*), mengukur seberapa cepat fungsi aktivasi  *sigma*
berubah pada *zLj*

.

Perhatikan bahwa semua yang ada di (BP1) mudah dihitung. Secara khusus,
kami menghitung *zLj*

sambil menghitung perilaku jaringan, dan itu hanya overhead tambahan
kecil untuk menghitung  *sigma*′(*zLj*). Bentuk persis
 *partialC*/ *partialaLj* tentu saja akan tergantung pada bentuk
fungsi biaya. Namun, asalkan fungsi biaya diketahui maka akan ada
sedikit kesulitan menghitung  *partialC*/ *partialaLj*. Misalnya, jika
kita menggunakan fungsi biaya kuadrat maka
*C*= *frac*12 *sumj*(*yj*−*aLj*)2, dan

partial C / \\ partial a ^ L\_j = (a\_j ^ L-y\_j) $, yang jelas mudah
dihitung.

Persamaan (BP1) adalah ekspresi componentwise untuk  *deltaL*

. Ini ekspresi yang sangat bagus, tetapi bukan bentuk berbasis matriks
yang kita inginkan untuk backpropagation. Namun, mudah untuk menulis
ulang persamaan dalam bentuk berbasis matriks \\ begin {eqnarray} \\
delta ^ L = \\ nabla\_a C \\ odot \\ sigma '(z ^ L). \\ tag {BP1a} \\
end {eqnarray} Di sini,  *nablaaC* didefinisikan sebagai vektor yang
komponennya adalah turunan parsial  *partialC*/ *partialaLj*. Anda dapat
menganggap  *nablaaC* sebagai menyatakan tingkat perubahan *C*
sehubungan dengan aktivasi output. Sangat mudah untuk melihat bahwa
Persamaan (BP1a) dan (BP1) sama, dan untuk alasan itu mulai sekarang
kita akan menggunakan (BP1) secara bergantian mengacu pada kedua
persamaan. Sebagai contoh, dalam kasus biaya kuadratik kita memiliki
 *nablaaC*=(*aLy*)

, dan jadi bentuk sepenuhnya berbasis matriks (BP1) menjadi \\ begin
{eqnarray} \\ delta ^ L = (a ^ Ly) \\ odot \\ sigma '(z ^ L). \\ tag
{30} \\ end {eqnarray} Seperti yang Anda lihat, semua yang ada dalam
ekspresi ini memiliki bentuk vektor yang bagus, dan mudah dihitung
menggunakan pustaka seperti Numpy.

**Persamaan untuk kesalahan  *deltal***

**dalam hal kesalahan di lapisan berikutnya,  *deltal*+1:** Khususnya \\
begin {eqnarray} \\ delta ^ l = ((w ^ {l + 1}) ^ T \\ delta ^ {l + 1})
\\ odot \\ sigma '(z ^ l), \\ tag {BP2} \\ end { eqnarray} di mana
(*wl*+1)*T* adalah transpose dari matriks bobot *wl*+1 untuk
(*l*+1) *rmth* layer. Persamaan ini tampak rumit, tetapi setiap elemen
memiliki interpretasi yang bagus. Misalkan kita tahu kesalahan
 *deltal*+1 di *l*+1 *rmth* layer. Ketika kita menerapkan matriks bobot
transposisi, (*wl*+1)*T*, kita dapat berpikir secara intuitif ini
sebagai memindahkan kesalahan *ke belakang* melalui jaringan, memberi
kita semacam ukuran kesalahan pada output dari *l* *rmth* layer. Kami
kemudian mengambil produk Hadamard  *odot* *sigma*′(*zl*). Ini
memindahkan kesalahan ke belakang melalui fungsi aktivasi di lapisan
*l*, memberi kita kesalahan  *deltal* dalam input terbobot ke lapisan
*l*

.

Dengan menggabungkan (BP2) dengan (BP1) kita dapat menghitung kesalahan
 *deltal*

untuk setiap lapisan dalam jaringan. Kita mulai dengan menggunakan (BP1)
untuk menghitung  *deltaL*, lalu menerapkan Persamaan (BP2) untuk
menghitung  *deltaL*−1, lalu Persamaan (BP2) lagi untuk menghitung
 *deltaL*−2

, dan seterusnya, sepanjang perjalanan kembali melalui jaringan.

**Persamaan untuk tingkat perubahan biaya sehubungan dengan bias dalam
jaringan:** Khususnya: \\ begin {eqnarray} \\ frac {\\ partial C} {\\
partial b ^ l\_j} = \\ delta ^ l\_j. \\ tag {BP3} \\ end {eqnarray}
Artinya, kesalahan  *deltalj*

*persis sama* dengan laju perubahan  *partialC*/ *partialblj*. Ini
adalah berita bagus, karena (BP1) dan (BP2) telah memberi tahu kami cara
menghitung  *deltalj*. Kita dapat menulis ulang (BP3) di steno sebagai
\\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial b} = \\ delta, \\
tag {31} \\ end {eqnarray} di mana dipahami bahwa  *delta* sedang
dievaluasi pada neuron yang sama dengan bias *b*

.

**Persamaan untuk tingkat perubahan biaya sehubungan dengan bobot apa
pun dalam jaringan:** Khususnya: \\ begin {eqnarray} \\ frac {\\ partial
C} {\\ partial w ^ l\_ {jk}} = a ^ {l-1} \_k \\ delta ^ l\_j. \\ tag
{BP4} \\ end {eqnarray} Ini memberitahu kita bagaimana menghitung
turunan parsial  *partialC*/ *partialwljk*

dalam hal jumlah  *deltal* dan *al*−1, yang sudah kita ketahui cara
menghitung. Persamaan dapat ditulis ulang dalam notasi indeks-kurang
berat sebagai \\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial w}
= a \_ {\\ rm in} \\ delta \_ {\\ rm out}, \\ tag {32} \\ end {eqnarray}
di mana ia memahami bahwa *a* *rmin* adalah aktivasi input neuron ke
bobot *w*, dan  *delta* *rmout* adalah kesalahan output neuron dari
bobot *w*. Memperbesar untuk melihat hanya berat *w*

, dan dua neuron yang terhubung oleh bobot itu, kita dapat menggambarkan
ini sebagai:

![http://neuralnetworksanddeeplearning.com/images/tikz20.png](media/image46.png)

Konsekuensi yang bagus dari Persamaan (32) adalah bahwa ketika aktivasi
*a* *rmin* kecil, *a* *rmin* *sekitar*0, istilah gradien
 *partialC*/ *partialw* juga akan cenderung kecil. Dalam hal ini, kita
akan mengatakan bahwa berat *belajar perlahan* , artinya berat tidak
banyak berubah selama gradient descent. Dengan kata lain, salah satu
konsekuensi (BP4) adalah bahwa bobot hasil dari neuron aktivasi rendah
belajar lambat.

Ada wawasan lain di sepanjang baris ini yang dapat diperoleh dari (BP1)
- (BP4) . Mari kita mulai dengan melihat layer output. Pertimbangkan
istilah  *sigma*′(*zLj*)

in (BP1) . Ingatlah dari [grafik fungsi sigmoid di bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#sigmoid_graph)
bahwa fungsi  *sigma* menjadi sangat datar ketika  *sigma*(*zLj*)
kira-kira 0 atau 1. Ketika ini terjadi, kita akan memiliki
 *sigma*′(*zLj*) *sekitar*0. Jadi pelajarannya adalah bahwa berat
pada lapisan akhir akan belajar secara lambat jika neuron output baik
aktivasi rendah ( *approx*0) atau aktivasi tinggi ( *sekitar*1

). Dalam kasus ini, sudah umum untuk mengatakan bahwa neuron keluaran
telah *jenuh* dan, sebagai akibatnya, berat telah berhenti belajar (atau
sedang belajar perlahan). Pernyataan serupa juga berlaku untuk bias
neuron output.

Kami dapat memperoleh wawasan serupa untuk lapisan sebelumnya.
Khususnya, perhatikan  *sigma*′(*zl*)

term dalam (BP2) . Ini berarti bahwa  *deltalj* cenderung menjadi kecil
jika neuron mendekati saturasi. Dan ini, pada gilirannya, berarti bahwa
setiap masukan bobot ke neuron jenuh akan belajar perlahan \* \* Alasan
ini tidak akan berlaku jika *wl*+1*T* *deltal*+1 memiliki besar cukup
entri untuk mengkompensasi kecilnya  *sigma*′(*zlj*)

. Tetapi saya berbicara tentang kecenderungan umum. .

Kesimpulannya, kita telah belajar bahwa suatu beban akan belajar secara
lambat jika salah satu neuron input rendah aktivasi, atau jika neuron
output telah jenuh, yaitu, baik aktivasi tinggi atau rendah.

Tak satu pun dari pengamatan ini yang terlalu mengejutkan. Namun, mereka
membantu meningkatkan model mental kita tentang apa yang terjadi ketika
jaringan saraf (*neural networks*) belajar. Lebih jauh, kita bisa
membalikkan jenis pemikiran ini. Empat persamaan mendasar ternyata
berlaku untuk fungsi aktivasi apa pun, bukan hanya fungsi sigmoid
standar (itu karena, seperti yang akan kita lihat sebentar lagi,
buktinya tidak menggunakan properti khusus

sigma $). Jadi kita dapat menggunakan persamaan ini untuk *merancang*
fungsi aktivasi yang memiliki properti pembelajaran yang diinginkan.
Sebagai contoh untuk memberi Anda ide, anggaplah kami memilih fungsi
aktivasi (non-sigmoid)  *sigma* sehingga  *sigma*′

selalu positif, dan tidak pernah mendekati nol. Itu akan mencegah
lambatnya pembelajaran yang terjadi ketika neuron sigmoid biasa jenuh.
Kemudian dalam buku ini kita akan melihat contoh di mana modifikasi
semacam ini dibuat untuk fungsi aktivasi. Menyimpan keempat persamaan
(BP1) - (BP4) dalam pikiran dapat membantu menjelaskan mengapa
modifikasi semacam itu dicoba, dan apa dampaknya.

![http://neuralnetworksanddeeplearning.com/images/tikz21.png](media/image47.png)

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#problem_330679) 

  - **Presentasi alternatif persamaan backpropagation:** Saya telah
    menyatakan persamaan backpropagation (terutama (BP1) dan (BP2) )
    menggunakan produk Hadamard. Presentasi ini mungkin membingungkan
    jika Anda tidak terbiasa dengan produk Hadamard. Ada pendekatan
    alternatif, berdasarkan pada perkalian matriks konvensional, yang
    menurut beberapa pembaca mungkin mencerahkan. (1) Tunjukkan bahwa
    (BP1) dapat ditulis ulang sebagai \\ begin {eqnarray} \\ delta ^ L =
    \\ Sigma '(z ^ L) \\ nabla\_a C, \\ tag {33} \\ end {eqnarray} di
    mana  *Sigma*′(*zL*)

adalah matriks persegi dengan entri diagonal adalah nilai
 *sigma*′(*zLj*), dan entri off-diagonalnya nol. Perhatikan bahwa
matriks ini bekerja pada  *nablaaC*

  - dengan perkalian matriks konvensional. (2) Tunjukkan bahwa (BP2)
    dapat ditulis ulang sebagai \\ begin {eqnarray} \\ delta ^ l = \\
    Sigma '(z ^ l) (w ^ {l + 1}) ^ T \\ delta ^ {l + 1}. \\ tag {34} \\
    end {eqnarray} (3) Dengan menggabungkan pengamatan (1) dan (2)
    menunjukkan bahwa \\ begin {eqnarray} \\ delta ^ l = \\ Sigma '(z ^
    l) (w ^ {l + 1}) ^ T \\ ldots \\ Sigma' (z ^ {L-1}) (w ^ L) ^ T \\
    Sigma '(z ^ L) \\ nabla\_a C \\ tag {35} \\ end {eqnarray} Untuk
    pembaca yang nyaman dengan perkalian matriks, persamaan ini mungkin
    lebih mudah dipahami daripada (BP1) dan (BP2) . Alasan saya fokus
    pada (BP1) dan (BP2) karena pendekatan itu ternyata lebih cepat
    diimplementasikan secara numerik.

### [Bukti dari empat persamaan mendasar (opsional)](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#proof_of_the_four_fundamental_equations_\(optional\)) 

Sekarang kita akan membuktikan empat persamaan mendasar (BP1) - (BP4) .
Keempatnya adalah konsekuensi dari aturan rantai dari kalkulus
multivariabel. Jika Anda nyaman dengan aturan rantai, maka saya sangat
menyarankan Anda untuk mencoba derivasi sendiri sebelum membaca.

Mari kita mulai dengan Persamaan (BP1) , yang memberikan ekspresi untuk
kesalahan output,  *deltaL*

. Untuk membuktikan persamaan ini, ingatlah itu menurut definisi \\
begin {eqnarray} \\ delta ^ L\_j = \\ frac {\\ partial C} {\\ partial z
^ L\_j}. \\ tag {36} \\ end {eqnarray} Menerapkan aturan rantai, kita
dapat mengekspresikan kembali turunan parsial di atas dalam hal turunan
parsial sehubungan dengan aktivasi output, \\ begin {eqnarray} \\ delta
^ L\_j = \\ sum\_k \\ frac {\\ partial C} {\\ partial a ^ L\_k} \\ frac
{\\ partial a ^ L\_k} {\\ partial z ^ L\_j}, \\ tag {37} \\ end
{eqnarray} di mana jumlahnya lebih dari semua neuron *k* di lapisan
output. Tentu saja, aktivasi output *aLk* dari *k* *rmth* neuron hanya
bergantung pada input terbobot *zLj* untuk *j* *rmth* neuron ketika
*k*=*j*. Jadi  *partialaLk*/ *partialzLj* menghilang ketika *k* *neqj*.
Sebagai hasilnya, kita dapat menyederhanakan persamaan sebelumnya
menjadi \\ begin {eqnarray} \\ delta ^ L\_j = \\ frac {\\ partial C} {\\
partial a ^ L\_j} \\ frac {\\ partial a ^ L\_j} {\\ partial z ^ L\_j}.
\\ tag {38} \\ end {eqnarray} Mengingat bahwa *aLj*= *sigma*(*zLj*)
istilah kedua di sebelah kanan dapat ditulis sebagai  *sigma*′(*zLj*)

, dan persamaannya menjadi \\ begin {eqnarray} \\ delta ^ L\_j = \\ frac
{\\ partial C} {\\ partial a ^ L\_j} \\ sigma '(z ^ L\_j), \\ tag {39}
\\ end {eqnarray} yang hanya (BP1) , dalam bentuk komponen.

Selanjutnya, kami akan membuktikan (BP2) , yang memberikan persamaan
untuk kesalahan  *deltal*

dalam hal kesalahan di lapisan berikutnya,  *deltal*+1. Untuk melakukan
ini, kami ingin menulis ulang  *deltalj*= *partialC*/ *partialzlj* dalam
istilah  *deltal*+1*k*= *partialC*/ *partialzl*+1*k*. Kita bisa
melakukan ini menggunakan aturan rantai, \\ begin {eqnarray} \\ delta ^
l\_j & = & \\ frac {\\ partial C} {\\ partial z ^ l\_j} \\ tag {40} \\\\
& = & \\ sum\_k \\ frac {\\ partial C} {\\ partial z ^ {l + 1} \_k} \\
frac {\\ partial z ^ {l + 1} \_k} {\\ partial z ^ l\_j} \\ tag {41} \\\\
& = & \\ sum\_k \\ frac {\\ partial z ^ {l + 1} \_k} {\\ partial z ^
l\_j} \\ delta ^ {l + 1} \_k, \\ tag {42} \\ end {eqnarray} di mana pada
baris terakhir kita telah menukar kedua istilah di sisi kanan, dan
menggantikan definisi  *deltal*+1*k*

. Untuk mengevaluasi istilah pertama pada baris terakhir, perhatikan itu
\\ begin {eqnarray} z ^ {l + 1} \_k = \\ sum\_j w ^ {l + 1} \_ {kj} a ^
l\_j + b ^ {l + 1} \_k = \\ sum\_j w ^ {l + 1} \_ {kj} \\ sigma (z ^
l\_j) + b ^ {l + 1} \_k. \\ tag {43} \\ end {eqnarray} Membedakan, kita
dapatkan \\ begin {eqnarray} \\ frac {\\ partial z ^ {l + 1} \_k} {\\
partial z ^ l\_j} = w ^ {l + 1} \_ {kj} \\ sigma '(z ^ l\_j). \\ tag
{44} \\ end {eqnarray} Mengganti kembali ke (42) kami memperoleh \\
begin {eqnarray} \\ delta ^ l\_j = \\ sum\_k w ^ {l + 1} \_ {kj} \\
delta ^ {l + 1} \_k \\ sigma '(z ^ l\_j). \\ tag {45} \\ end {eqnarray}
Ini hanya (BP2) ditulis dalam bentuk komponen.

Dua persamaan terakhir yang ingin kita buktikan adalah (BP3) dan (BP4) .
Ini juga mengikuti dari aturan rantai, dengan cara yang mirip dengan
bukti dari dua persamaan di atas. Saya menyerahkannya kepada Anda
sebagai latihan.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#exercise_378831) 

  - Buktikan Persamaan (BP3) dan (BP4) .

Itu melengkapi bukti dari empat persamaan mendasar dari backpropagation.
Buktinya mungkin terlihat rumit. Tapi itu benar-benar hanya hasil dari
penerapan aturan rantai dengan hati-hati. Sedikit kurang ringkas, kita
dapat menganggap backpropagation sebagai cara menghitung gradien fungsi
biaya dengan secara sistematis menerapkan aturan rantai dari kalkulus
multi-variabel. Itu semua benar-benar untuk backpropagation - sisanya
adalah detail.

### [Algoritma backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_backpropagation_algorithm) 

Persamaan backpropagation memberi kita cara menghitung gradien fungsi
biaya. Mari kita secara eksplisit menuliskan ini dalam bentuk algoritma:

1.  **Input *x***

**:** Tetapkan aktivasi yang sesuai *a*1

• untuk lapisan input.

• **Umpan ke depan:** Untuk setiap *l*=2,3, *ldots*,*L* menghitung
*zl*=*wlal*−1+*bl* dan *al*= *sigma*(*zl*)

• .

• **Kesalahan keluaran  *deltaL*:** Hitung vektor
 *deltaL*= *nablaaC* *odot* *sigma*′(*zL*)

• .

• **Backpropagate kesalahan:** Untuk setiap *l*=*L*−1,*L*−2, *ldots*,2
compute  *deltal*=((*wl*+1)*T* *deltal*+1) *odot* *sigma*′(*zl*)

• .

• **Output:** Gradien fungsi biaya diberikan oleh
 *frac* *partialC* *partialwljk*=*al*−1*k* *deltalj* dan
 *frac* *partialC* *partialblj*= *deltalj*

5.  .

Meneliti algoritma Anda dapat melihat mengapa itu disebut propagasi
*kembali* . Kami menghitung vektor kesalahan  *deltal*

mundur, mulai dari lapisan terakhir. Tampaknya aneh bahwa kita akan
melalui jaringan mundur. Tetapi jika Anda berpikir tentang bukti
backpropagation, gerakan mundur adalah konsekuensi dari kenyataan bahwa
biaya adalah fungsi dari output dari jaringan. Untuk memahami bagaimana
biaya bervariasi dengan bobot dan bias sebelumnya kita perlu berulang
kali menerapkan aturan rantai, bekerja mundur melalui lapisan untuk
mendapatkan ekspresi yang dapat digunakan.

#### [Latihan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#exercises_675621) 

  - **Backpropagation dengan neuron yang dimodifikasi tunggal** Misalkan
    kita memodifikasi neuron tunggal dalam jaringan feedforward sehingga
    output dari neuron diberikan oleh *f*( *sumjwjxj*+*b*)

, di mana *f*

• adalah beberapa fungsi selain dari sigmoid. Bagaimana kita harus
memodifikasi algoritma backpropagation dalam kasus ini?

• **Backpropagation dengan linear neuron** Misalkan kita mengganti
fungsi  *sigma* non-linear yang biasa dengan  *sigma*(*z*)=*z*

  - di seluruh jaringan. Tulis ulang algoritma backpropagation untuk
    kasus ini.

Seperti yang saya jelaskan di atas, algoritma backpropagation menghitung
gradien dari fungsi biaya untuk contoh pelatihan tunggal, *C*=*Cx*

. Dalam praktiknya, menggabungkan backpropagation dengan algoritme
pembelajaran seperti stochastic gradient descent, di mana kami
menghitung gradien untuk banyak contoh pelatihan. Secara khusus,
diberikan mini-batch contoh pelatihan *m*

, algoritma berikut ini menerapkan langkah pembelajaran gradient descent
berdasarkan pada mini-batch tersebut:

1.  **Masukkan satu set contoh pelatihan**

2.  **Untuk setiap contoh pelatihan *x***

**:** Tetapkan aktivasi input terkait *ax*,1, dan lakukan
langkah-langkah berikut:

  - **Umpan ke depan:** Untuk setiap *l*=2,3, *ldots*,*L*

menghitung *zx*,*l*=*wlax*,*l*−1+*bl* dan *ax*,*l*= *sigma*(*zx*,*l*)

• .

• **Kesalahan keluaran  *deltax*,*L*:** Hitung vektor
 *deltax*,*L*= *nablaaCx* *odot* *sigma*′(*zx*,*L*)

• .

• **Backpropagate kesalahan:** Untuk setiap *l*=*L*−1,*L*−2, *ldots*,2
compute
 *deltax*,*l*=((*wl*+1)*T* *deltax*,*l*+1) *odot* *sigma*′(*zx*,*l*)

  - • .

• **Keturunan gradien:** Untuk setiap *l*=*L*,*L*−1, *ldots*,2 perbarui
bobot sesuai dengan aturan
*wl* *rightarrowwl*− *frac* *etam* *sumx* *deltax*,*l*(*ax*,*l*−1)*T*,
dan biasnya sesuai dengan aturan
*bl* *rightarrowbl*− *frac* *etam* *sumx* *deltax*,*l*

3.  .

Tentu saja, untuk menerapkan penurunan gradien stokastik dalam
praktiknya Anda juga memerlukan loop luar yang menghasilkan mini-batch
contoh pelatihan, dan loop luar melangkah melalui beberapa zaman
pelatihan. Saya telah menghilangkannya untuk kesederhanaan.

### [Kode untuk backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_code_for_backpropagation) 

Setelah memahami backpropagation secara abstrak, kita sekarang dapat
memahami kode yang digunakan dalam bab terakhir untuk
mengimplementasikan backpropagation. Ingat dari
[bab](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
itu bahwa kode itu terkandung dalam metode update\_mini\_batch dan
backprop kelas Jaringan . Kode untuk metode ini adalah terjemahan
langsung dari algoritma yang dijelaskan di atas. Secara khusus, metode
update\_mini\_batch memperbarui bobot dan bias Jaringan dengan
menghitung gradien untuk mini\_batch contoh pelatihan saat ini:

Jaringan kelas ( objek ):

...

def update\_mini\_batch ( self , mini\_batch , eta ):

"" "Perbarui bobot dan bias jaringan dengan menerapkan

gradient descent menggunakan backpropagation ke batch mini tunggal.

"Mini\_batch" adalah daftar tupel "(x, y)", dan "eta"

adalah tingkat belajar. "" "

nabla\_b = \[ np . nol ( bentuk b ) untuk b dalam diri . bias \]

nabla\_w = \[ np . nol ( bentuk w ) untuk w dalam diri . bobot \]

untuk x , y di mini\_batch :

delta\_nabla\_b , delta\_nabla\_w = mandiri . backprop ( x , y )

nabla\_b = \[ nb + dnb untuk nb , dnb dalam zip ( nabla\_b ,
delta\_nabla\_b )\]

nabla\_w = \[ nw + dnw untuk nw , dnw di zip ( nabla\_w ,
delta\_nabla\_w )\]

diri bobot = \[ w - ( eta / len ( mini\_batch )) \* nw

untuk w , nw in zip ( bobot mandiri , nabla\_w )\]

diri bias = \[ b - ( eta / len ( mini\_batch )) \* nb

untuk b , nb di zip ( self . bias , nabla\_b )\]

Sebagian besar pekerjaan dilakukan oleh baris delta\_nabla\_b,
delta\_nabla\_w = self.backprop (x, y) yang menggunakan metode backprop
untuk mengetahui turunan parsial  *partialCx*/ *partialblj* dan
 *partialCx*/ *parsialwljk*. Metode backprop mengikuti algoritma di
bagian terakhir dengan cermat. Ada satu perubahan kecil - kami
menggunakan pendekatan yang sedikit berbeda untuk mengindeks lapisan.
Perubahan ini dibuat untuk memanfaatkan fitur Python, yaitu penggunaan
indeks daftar negatif untuk menghitung mundur dari akhir daftar, jadi,
misalnya, l \[-3\] adalah entri terakhir ketiga dalam daftar l . Kode
untuk backprop di bawah ini, bersama dengan beberapa fungsi pembantu,
yang digunakan untuk menghitung fungsi  *sigma*, turunan  *sigma*′, dan
turunan dari fungsi biaya. Dengan penyertaan ini Anda harus dapat
memahami kode dengan cara mandiri. Jika ada sesuatu yang membuat Anda
tersandung, Anda mungkin perlu berkonsultasi [dengan deskripsi asli (dan
daftar lengkap) dari kode
tersebut](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
.

Jaringan kelas ( objek ):

...

def backprop ( self , x , y ):

"" "Kembalikan tuple" (nabla\_b, nabla\_w) "mewakili

gradien untuk fungsi biaya C\_x. "nabla\_b" dan

"nabla\_w" adalah daftar array numpy lapis demi lapis, serupa

untuk "self.biases" dan "self.weights". "" ""

nabla\_b = \[ np . nol ( bentuk b ) untuk b dalam diri . bias \]

nabla\_w = \[ np . nol ( bentuk w ) untuk w dalam diri . bobot \]

\# feedforward

aktivasi = x

activations = \[ x \] \# daftar untuk menyimpan semua aktivasi, lapis
demi lapis

zs = \[\] \# daftar untuk menyimpan semua vektor z, lapis demi lapis

untuk b , w di zip ( self . bias , self . weights ):

z = np . titik ( w , aktivasi ) + b

zs . tambahkan ( z )

aktivasi = sigmoid ( z )

aktivasi . tambahkan ( aktivasi )

\# umpan balik

delta = diri . cost\_derivative ( aktivasi \[ - 1 \], y ) \* \\

sigmoid\_prime ( zs \[ - 1 \])

nabla\_b \[ - 1 \] = delta

nabla\_w \[ - 1 \] = np . dot ( delta , aktivasi \[ - 2 \] . transpose
())

\# Perhatikan bahwa variabel l pada loop di bawah ini digunakan sedikit

\# berbeda dengan notasi dalam Bab 2 buku ini. Sini,

\# l = 1 berarti lapisan neuron terakhir, l = 2 adalah

\# lapisan kedua terakhir, dan seterusnya. Ini adalah nomor baru dari

\# Skema dalam buku, digunakan di sini untuk mengambil keuntungan dari
kenyataan

\# Bahwa Python dapat menggunakan indeks negatif dalam daftar.

untuk l in xrange ( 2 , self . num\_layers ):

z = zs \[ - l \]

sp = sigmoid\_prime ( z )

delta = np . dot ( self . timbangan \[ - l + 1 \] . transpose (), delta
) \* sp

nabla\_b \[ - l \] = delta

nabla\_w \[ - l \] = np . titik ( delta , aktivasi \[ - l - 1 \] .
transpose ())

return ( nabla\_b , nabla\_w )

...

def cost\_derivative ( self , output\_activations , y ):

"" "Kembalikan vektor turunan parsial \\ parsial C\_x /

\\ sebagian a untuk aktivasi keluaran. "" "

return ( output\_activations - y )

def sigmoid ( z ):

"" "Fungsi sigmoid." ""

return 1.0 / ( 1.0 + np . exp ( - z ))

def sigmoid\_prime ( z ):

"" "Turunan dari fungsi sigmoid." ""

return sigmoid ( z ) \* ( 1 - sigmoid ( z ))

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#problem_269962) 

  - **Pendekatan berbasis matriks sepenuhnya untuk backpropagation
    melalui batch mini** Implementasi kami dari penurunan gradien
    stokastik atas contoh-contoh pelatihan dalam batch mini.
    Dimungkinkan untuk memodifikasi algoritma backpropagation sehingga
    menghitung gradien untuk semua contoh pelatihan dalam mini-batch
    secara bersamaan. Idenya adalah bahwa alih-alih dimulai dengan
    vektor input tunggal, *x*

, kita dapat mulai dengan matriks *X*=\[*x*1*x*2 *ldotsxm*\]

  - yang kolomnya adalah vektor dalam mini-batch. Kami
    meneruskan-merambat dengan mengalikan dengan matriks bobot,
    menambahkan matriks yang cocok untuk persyaratan bias, dan
    menerapkan fungsi sigmoid di mana-mana. Kami backpropagate sepanjang
    garis yang sama. Tuliskan pseudocode secara eksplisit untuk
    pendekatan ini ke algoritma backpropagation. Ubah network.py
    sehingga menggunakan pendekatan berbasis matriks ini. Keuntungan
    dari pendekatan ini adalah bahwa ia mengambil keuntungan penuh dari
    pustaka modern untuk aljabar linier. Sebagai hasilnya, ini bisa
    menjadi sedikit lebih cepat daripada melompati mini-batch. (Di
    laptop saya, misalnya, percepatan adalah tentang faktor dua ketika
    dijalankan pada masalah klasifikasi MNIST seperti yang kita bahas
    dalam bab terakhir.) Dalam praktiknya, semua pustaka serius untuk
    backpropagation menggunakan pendekatan berbasis matriks penuh ini
    atau beberapa varian .

### [Dalam hal apa backpropagation algoritma cepat?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#in_what_sense_is_backpropagation_a_fast_algorithm) 

Dalam hal apa backpropagation algoritma cepat? Untuk menjawab pertanyaan
ini, mari pertimbangkan pendekatan lain untuk menghitung gradien.
Bayangkan ini adalah hari-hari awal penelitian jaringan saraf. Mungkin
tahun 1950-an atau 1960-an, dan Anda adalah orang pertama di dunia yang
berpikir untuk menggunakan gradient descent untuk belajar\! Tetapi untuk
membuat ide itu berfungsi, Anda perlu cara menghitung gradien fungsi
biaya. Anda mengingat kembali pengetahuan Anda tentang kalkulus, dan
memutuskan untuk melihat apakah Anda dapat menggunakan aturan rantai
untuk menghitung gradien. Tetapi setelah bermain-main sedikit, aljabar
terlihat rumit, dan Anda menjadi kecil hati. Jadi Anda mencoba mencari
pendekatan lain. Anda memutuskan untuk menganggap biaya sebagai fungsi
dari bobot *C*=*C*(*w*)

saja (kami akan kembali ke bias sebentar lagi). Anda menghitung bobot
*w*1,*w*2, *ldots*, dan ingin menghitung  *partialC*/ *partialwj* untuk
bobot tertentu *wj*. Cara yang jelas untuk melakukan itu adalah dengan
menggunakan perkiraan \\ begin {eqnarray} \\ frac {\\ partial C} {\\
partial w\_ {j}} \\ approx \\ frac {C (w + \\ epsilon e\_j) -C (w)} {\\
epsilon}, \\ tag {46} \\ end {eqnarray} di mana  *epsilon*\>0 adalah
angka positif kecil, dan *ej* adalah vektor satuan dalam arah
*j* *rmth*. Dengan kata lain, kita dapat memperkirakan
 *partialC*/ *partialwj* dengan menghitung biaya *C* untuk dua nilai
yang sedikit berbeda dari *wj*, dan kemudian menerapkan Persamaan (46) .
Gagasan yang sama akan memungkinkan kita menghitung derivatif parsial
 *partialC*/ *partialb*

sehubungan dengan bias.

Pendekatan ini terlihat sangat menjanjikan. Sederhana secara konseptual,
dan sangat mudah diimplementasikan, hanya menggunakan beberapa baris
kode. Tentu saja, ini terlihat jauh lebih menjanjikan daripada gagasan
menggunakan aturan rantai untuk menghitung gradien\!

Sayangnya, meskipun pendekatan ini tampak menjanjikan, ketika Anda
menerapkan kode itu ternyata sangat lambat. Untuk memahami alasannya,
bayangkan kita memiliki sejuta bobot dalam jaringan kita. Kemudian untuk
setiap bobot yang berbeda *wj*

kita perlu menghitung *C*(*w*+ *epsilonej*) untuk menghitung
 *partialC*/ *partialwj*. Itu berarti bahwa untuk menghitung gradien
kita perlu menghitung fungsi biaya satu juta kali berbeda, memerlukan
satu juta penerusan maju melalui jaringan (per contoh pelatihan). Kita
perlu menghitung *C*(*w*)

juga, jadi itu total satu juta dan satu melewati jaringan.

Apa yang pintar tentang backpropagation adalah memungkinkan kita untuk
secara bersamaan menghitung *semua* turunan parsial
 *partialC*/ *partialwj*

hanya menggunakan satu forward pass melalui jaringan, diikuti oleh satu
backward pass melalui jaringan. Secara kasar, biaya komputasi pass
mundur hampir sama dengan pass maju \* \* Ini harus masuk akal, tetapi
membutuhkan beberapa analisis untuk membuat pernyataan yang cermat. Ini
masuk akal karena biaya komputasi yang dominan di forward pass adalah
mengalikan dengan matriks bobot, sedangkan di backward itu mengalikan
dengan transpos dari matriks bobot. Operasi ini jelas memiliki biaya
komputasi yang sama. . Dan total biaya backpropagation kira-kira sama
dengan hanya membuat dua umpan ke depan melalui jaringan. Bandingkan
dengan jutaan dan satu umpan maju yang kami perlukan untuk pendekatan
berdasarkan (46) \! Dan meskipun backpropagation nampak lebih kompleks
daripada pendekatan berdasarkan pada (46) , sebenarnya jauh lebih cepat.

Speedup ini pertama kali sepenuhnya dihargai pada tahun 1986, dan itu
sangat memperluas berbagai masalah yang bisa diselesaikan oleh jaringan
saraf. Itu, pada gilirannya, menyebabkan terburu-buru orang menggunakan
jaringan saraf. Tentu saja, backpropagation bukanlah obat mujarab.
Bahkan pada akhir 1980-an orang berlari melawan batas, terutama ketika
mencoba menggunakan backpropagation untuk melatih *jaringan saraf
(neural networks)* yang dalam, yaitu jaringan dengan banyak lapisan
tersembunyi. Kemudian dalam buku ini kita akan melihat bagaimana
komputer modern dan beberapa ide baru yang pintar sekarang memungkinkan
untuk menggunakan backpropagation untuk melatih *jaringan saraf (neural
networks)* yang begitu dalam.

### [Backpropagation: gambaran besarnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#backpropagation_the_big_picture) 

Seperti yang sudah saya jelaskan, backpropagation menghadirkan dua
misteri. Pertama, apa yang sebenarnya dilakukan algoritma? Kami telah
mengembangkan gambar kesalahan yang dipropagandakan dari output. Tetapi
bisakah kita melangkah lebih dalam, dan membangun lebih banyak intuisi
tentang apa yang terjadi ketika kita melakukan semua perkalian matriks
dan vektor ini? Misteri kedua adalah bagaimana seseorang bisa menemukan
backpropagation sejak awal? Itu satu hal untuk mengikuti langkah-langkah
dalam suatu algoritma, atau bahkan untuk mengikuti bukti bahwa algoritma
bekerja. Tapi itu tidak berarti Anda memahami masalah dengan sangat baik
sehingga Anda bisa menemukan algoritma di tempat pertama. Apakah ada
garis penalaran yang masuk akal yang bisa membuat Anda menemukan
algoritma backpropagation? Di bagian ini saya akan membahas kedua
misteri ini.

Untuk meningkatkan intuisi kami tentang apa yang dilakukan algoritma,
mari bayangkan bahwa kami telah membuat perubahan kecil  *Deltawljk*

untuk beberapa bobot dalam jaringan, *wljk*

:

![http://neuralnetworksanddeeplearning.com/images/tikz22.png](media/image48.png)

Perubahan berat itu akan menyebabkan perubahan aktivasi output dari
neuron yang sesuai:

![http://neuralnetworksanddeeplearning.com/images/tikz23.png](media/image49.png)

Itu, pada gilirannya, akan menyebabkan perubahan dalam *semua* aktivasi
di lapisan berikutnya:

![http://neuralnetworksanddeeplearning.com/images/tikz24.png](media/image50.png)

Perubahan-perubahan itu pada gilirannya akan menyebabkan perubahan pada
lapisan berikutnya, dan kemudian berikutnya, dan seterusnya sepanjang
jalan hingga menyebabkan perubahan pada lapisan akhir, dan kemudian
dalam fungsi biaya:

![http://neuralnetworksanddeeplearning.com/images/tikz25.png](media/image51.png)

Perubahan  *DeltaC* dalam biaya terkait dengan perubahan  *Deltawljk*
dalam bobot dengan persamaan \\ begin {eqnarray} \\ Delta C \\ approx \\
frac {\\ partial C} {\\ partial w ^ l\_ {jk}} \\ Delta w ^ l\_ {jk}. \\
tag {47} \\ end {eqnarray} Ini menyarankan bahwa kemungkinan pendekatan
untuk menghitung  *frac* *partialC* *partialwljk* adalah untuk melacak
dengan cermat bagaimana perubahan kecil dalam *wljk* merambat
menyebabkan perubahan kecil dalam *C*. Jika kita bisa melakukan itu,
berhati-hati untuk mengekspresikan semuanya dalam hal jumlah yang mudah
dihitung, maka kita harus dapat menghitung  *partialC*/ *partialwljk*.

Mari kita coba lakukan ini. Perubahan  *Deltawljk*

menyebabkan perubahan kecil  *Deltaalj* dalam aktivasi *j* *rmth* neuron
di *l* *rmth* layer. Perubahan ini diberikan oleh \\ begin {eqnarray} \\
Delta a ^ l\_j \\ approx \\ frac {\\ partial a ^ l\_j} {\\ partial w ^
l\_ {jk}} \\ Delta w ^ l\_ {jk}. \\ tag {48} \\ end {eqnarray} Perubahan
dalam aktivasi  *Deltaalj* akan menyebabkan perubahan dalam *semua*
aktivasi di lapisan berikutnya, yaitu (*l*+1) *rmth* layer. Kami akan
berkonsentrasi pada cara satu saja dari aktivasi tersebut terpengaruh,
katakanlah *al*+1*q*

,

![http://neuralnetworksanddeeplearning.com/images/tikz26.png](media/image52.png)

Bahkan, itu akan menyebabkan perubahan berikut: \\ begin {eqnarray} \\
Delta a ^ {l + 1} \_q \\ approx \\ frac {\\ partial a ^ {l + 1} \_q} {\\
partial a ^ l\_j} \\ Delta a ^ l\_j. \\ tag {49} \\ end {eqnarray}
Mengganti ekspresi dari Persamaan (48) , kita mendapatkan: \\ begin
{eqnarray} \\ Delta a ^ {l + 1} \_q \\ approx \\ frac {\\ partial a ^ {l
+ 1} \_q} {\\ partial a ^ l\_j} \\ frac {\\ partial a ^ l\_j} {\\
partial w ^ l\_ {jk}} \\ Delta w ^ l\_ {jk}. \\ tag {50} \\ end
{eqnarray} Tentu saja, perubahan  *Deltaal*+1*q* akan, pada gilirannya,
akan menyebabkan perubahan dalam aktivasi di lapisan berikutnya.
Faktanya, kita bisa membayangkan jalur sepanjang jaringan dari *wljk* ke
*C*, dengan setiap perubahan dalam aktivasi menyebabkan perubahan pada
aktivasi berikutnya, dan, akhirnya, perubahan dalam biaya pada output.
Jika path melewati aktivasi *alj*,*al*+1*q*, *ldots*,*aL*−1*n*,*aLm*
maka ekspresi yang dihasilkan adalah \\ begin {eqnarray} \\ Delta C \\
approx \\ frac {\\ partial C} {\\ partial a ^ L\_m} \\ frac {\\ partial
a ^ L\_m} {\\ partial a ^ {L-1} \_n} \\ frac {\\ partial a ^ {L-1} \_n}
{\\ partial a ^ {L-2} \_p} \\ ldots \\ frac {\\ partial a ^ {l + 1} \_q}
{\\ partial a ^ l\_j} \\ frac {\\ partial a ^ l\_j} {\\ partial w ^ l\_
{jk}} \\ Delta w ^ l\_ {jk}, \\ tag {51} \\ end {eqnarray} yaitu, kami
telah mengambil  *partiala*/ *partiala* ketik istilah untuk setiap
neuron tambahan yang telah kami lewati, serta istilah
 *partialC*/ *partialaLm* di akhir. Ini mewakili perubahan dalam *C*
karena perubahan dalam aktivasi di sepanjang jalur khusus ini melalui
jaringan. Tentu saja, ada banyak jalur di mana perubahan *wljk* dapat
menyebar untuk memengaruhi biaya, dan kami telah mempertimbangkan hanya
satu jalur. Untuk menghitung perubahan total dalam *C* masuk akal bahwa
kita harus menjumlahkan semua jalur yang mungkin antara bobot dan biaya
akhir, yaitu, \\ begin {eqnarray} \\ Delta C \\ approx \\ sum\_ {mnp \\
ldots q} \\ frac {\\ partial C} {\\ partial a ^ L\_m} \\ frac {\\
partial a ^ L\_m} {\\ partial a ^ {L-1 } \_n} \\ frac {\\ partial a ^
{L-1} \_n} {\\ partial a ^ {L-2} \_p} \\ ldots \\ frac {\\ partial a ^
{l + 1} \_q} {\\ partial a ^ l\_j} \\ frac {\\ partial a ^ l\_j} {\\
partial w ^ l\_ {jk}} \\ Delta w ^ l\_ {jk}, \\ tag {52} \\ end
{eqnarray} di mana kami telah merangkum semua pilihan yang mungkin untuk
neuron menengah di sepanjang jalan. Membandingkan dengan (47) kami
melihat itu \\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial w ^
l\_ {jk}} = \\ sum\_ {mnp \\ ldots q} \\ frac {\\ partial C} {\\ partial
a ^ L\_m} \\ frac {\\ partial a ^ L\_m} {\\ partial a ^ {L-1} \_n} \\
frac {\\ partial a ^ {L-1} \_n} {\\ partial a ^ {L-2} \_p} \\ ldots \\
frac {\\ partial a ^ {l + 1} \_q} {\\ partial a ^ l\_j} \\ frac {\\
partial a ^ l\_j} {\\ partial w ^ l\_ {jk}}. \\ tag {53} \\ end
{eqnarray} Sekarang, Persamaan (53) terlihat rumit. Namun, ia memiliki
interpretasi intuitif yang bagus. Kami menghitung laju perubahan *C*
sehubungan dengan bobot dalam jaringan. Apa persamaan memberitahu kita
adalah bahwa setiap tepi antara dua neuron dalam jaringan dikaitkan
dengan faktor laju yang hanya turunan parsial dari aktivasi satu neuron
sehubungan dengan aktivasi neuron lainnya. Tepi dari bobot pertama ke
neuron pertama memiliki faktor laju  *partialalj*/ *partialwljk*. Faktor
laju untuk jalur hanyalah produk dari faktor laju di sepanjang jalur.
Dan total tingkat perubahan  *partialC*/ *partialwljk* hanya jumlah dari
faktor-faktor tingkat semua jalur dari bobot awal ke biaya akhir.
Prosedur ini diilustrasikan di sini, untuk satu jalur:

![http://neuralnetworksanddeeplearning.com/images/tikz27.png](media/image53.png)

Apa yang saya berikan sampai sekarang adalah argumen heuristik, cara
berpikir tentang apa yang terjadi ketika Anda mengganggu berat badan
dalam jaringan. Biarkan saya membuat garis pemikiran yang dapat Anda
gunakan untuk mengembangkan argumen ini lebih jauh. Pertama, Anda bisa
mendapatkan ekspresi eksplisit untuk semua turunan parsial individu
dalam Persamaan (53) . Itu mudah dilakukan dengan sedikit kalkulus.
Setelah melakukan itu, Anda kemudian dapat mencoba mencari cara untuk
menulis semua jumlah di atas indeks sebagai perkalian matriks. Ini
ternyata membosankan, dan membutuhkan kegigihan, tetapi bukan wawasan
yang luar biasa. Setelah melakukan semua ini, dan kemudian
menyederhanakan sebanyak mungkin, apa yang Anda temukan adalah bahwa
Anda benar-benar mendapatkan algoritma backpropagation\! Jadi Anda dapat
menganggap algoritma backpropagation sebagai cara menghitung jumlah
lebih dari faktor laju untuk semua jalur ini. Atau, dengan kata lain,
algoritma backpropagation adalah cara cerdas untuk melacak gangguan
kecil pada bobot (dan bias) ketika mereka menyebar melalui jaringan,
mencapai output, dan kemudian mempengaruhi biaya.

Sekarang, saya tidak akan menyelesaikan semua ini di sini. Ini
berantakan dan membutuhkan perawatan yang cukup untuk mengerjakan semua
detail. Jika Anda siap menghadapi tantangan, Anda dapat menikmati
mencobanya. Dan bahkan jika tidak, saya berharap garis pemikiran ini
memberi Anda beberapa wawasan tentang apa yang dicapai oleh
backpropagation.

Bagaimana dengan misteri lainnya - bagaimana backpropagation dapat
ditemukan? Bahkan, jika Anda mengikuti pendekatan yang baru saja saya
sketsa, Anda akan menemukan bukti backpropagation. Sayangnya, buktinya
sedikit lebih lama dan lebih rumit daripada yang saya jelaskan
sebelumnya dalam bab ini. Jadi bagaimana bukti singkat (tetapi lebih
misterius) itu ditemukan? Apa yang Anda temukan ketika Anda menuliskan
semua detail dari bukti yang panjang adalah bahwa, setelah faktanya, ada
beberapa penyederhanaan yang jelas menatap wajah Anda. Anda membuat
penyederhanaan itu, mendapatkan bukti yang lebih pendek, dan
menuliskannya. Dan kemudian beberapa penyederhanaan yang lebih jelas
muncul pada Anda. Jadi Anda ulangi lagi. Hasil setelah beberapa iterasi
adalah bukti yang kita lihat sebelumnya \* \* Ada satu langkah pintar
yang diperlukan. Dalam Persamaan (53) variabel perantara adalah aktivasi
seperti *al*+1*q*

. Gagasan cerdasnya adalah beralih menggunakan input terbobot, seperti
*zl*+1*q*, sebagai variabel perantara. Jika Anda tidak memiliki ide ini,
dan alih-alih terus menggunakan aktivasi *al*+1*q*

, bukti yang Anda peroleh ternyata sedikit lebih kompleks daripada bukti
yang diberikan sebelumnya dalam bab ini. - pendek, tetapi agak tidak
jelas, karena semua rambu-rambu untuk pembangunannya telah dihapus\!
Saya, tentu saja, meminta Anda untuk mempercayai saya tentang hal ini,
tetapi sebenarnya tidak ada misteri besar tentang asal-usul bukti
sebelumnya. Hanya banyak kerja keras yang menyederhanakan bukti yang
telah saya buat di bagian ini.

Dalam karya akademis, silakan kutip buku ini sebagai: Michael A.
Nielsen, "Neural Networks and Deep Learning", Determination Press,
2015  
  
Karya ini dilisensikan di bawah [Lisensi Creative Commons
Attribution-NonCommercial 3.0
Unported](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://creativecommons.org/licenses/by-nc/3.0/deed.en_GB&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh6tByBQCmRzRA1xiUcnuJcGw7WLw)
. Ini artinya Anda bebas menyalin, membagikan, dan membuat buku ini,
tetapi tidak untuk menjualnya. Jika Anda tertarik menggunakan komersial,
silakan [hubungi saya](mailto:mn@michaelnielsen.org) . Pembaruan
terakhir: Sel 11 Jun 16:58:53 2019  
  
  
![Lisensi Creative Commons](media/image33.png)

# [BAGIAN 3](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA) 

# [Meningkatkan cara belajar jaringan saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA) 

[jaringan saraf (*neural networks*) Tiruan dan Pembelajaran
Jauh](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhic73V7KqVjxIPGNbaQNJ2530s4GA)

[Tentang buku
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/about.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh4WEv8VZZCecHFGon_fBfEj9Fk-g)

[Tentang latihan dan
masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/exercises_and_problems.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgGXxYFYgdq20f8ymqVw5JGPzA2tA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Menggunakan
jaring saraf untuk mengenali angka tulisan
tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Cara
kerja algoritma
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Meningkatkan
cara belajar jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Bukti
visual bahwa jaring saraf dapat menghitung fungsi apa
pun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgzJKLAEjvxFJSTt899AGWkWymaQw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Mengapa
jaringan saraf (*neural networks*) yang dalam sulit untuk
dilatih?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[*Pembelajaran
dalam (deep
learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ)

[Lampiran: Apakah ada algoritma *sederhana* untuk
intelijen?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/sai.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi_r2W6B006rb7gK3F4bzy6prrdaQ)

[Ucapan Terima
Kasih](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/acknowledgements.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2YHKQpAuvZNHAiXn0Z6HVn-0KQA)

[Pertanyaan yang Sering
Diajukan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

Jika Anda mendapat manfaat dari buku ini, silakan berikan sumbangan
kecil. Saya menyarankan $ 5, tetapi Anda dapat memilih jumlahnya.

Top of Form

Bottom of Form

Sebagai alternatif, Anda dapat memberikan donasi dengan mengirimkan saya
Bitcoin, di alamat 1Kd6tXH5SDAmiFb49J9hknG5pqj7KStSAx

Sponsor  
![http://neuralnetworksanddeeplearning.com/assets/exxact.png](media/image36.png)

Workstation Deep Learning mulai dari $ 6.999: [pelajari lebih
lanjut](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.exxactcorp.com/Deep-Learning-NVIDIA-GPU-Solutions%3Futm_source%3Dneuralnetworksanddeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dsponsors&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj6rGsPToAcGlYjeEJXAHXJspW3eQ)

![http://neuralnetworksanddeeplearning.com/assets/lambda.png](media/image37.png)

[Workstation, Server, dan Laptop Belajar
dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://lambdalabs.com/%3Futm_source%3Dneuralnetworksdeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dblogin%26utm_content%3Drtext&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhmW9twAd-_7XhnUCemcjX98sl7gw)

![http://neuralnetworksanddeeplearning.com/assets/gsquared.png](media/image38.png)![http://neuralnetworksanddeeplearning.com/assets/tineye.png](media/image39.png)![http://neuralnetworksanddeeplearning.com/assets/visionsmarts.png](media/image40.png)

Terima kasih kepada semua
[pendukung](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/supporters.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj9HdVAwFQiYjPlo--NhrlXsSgZ2w)
yang memungkinkan buku ini, dengan terima kasih terutama kepada Pavel
Dudrenov. Terima kasih juga kepada semua kontributor di [Bugfinder Hall
of
Fame](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/bugfinder.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhbjVenylI9ODfotXyQdFoaBBrKaQ)
.

Sumber daya

[Michael Nielsen di
Twitter](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://twitter.com/michael_nielsen&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiM6kfoM32wXnoIMmahlwqfNqEWPg)

[Pesan
FAQ](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

[Repositori
kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhUDc58iR7PU8_gSuNnY9hUhxv0pw)

[Milis pengumuman proyek Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://eepurl.com/0Xxjb&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhCYC3lUQysyAb2pDyD_0ubQrqOeg)

[Deep
Learning](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.deeplearningbook.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhrv253n32Mv6Uv5S3BDOvpBcn5rg)
, buku karya Ian Goodfellow, Yoshua Bengio, dan Aaron Courville

[cognitivemedium.com](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://cognitivemedium.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgEBgr9y1U5WD3Da33Y88SX6zvRPA)

![http://neuralnetworksanddeeplearning.com/assets/Michael\_Nielsen\_Web\_Small.jpg](media/image41.jpeg)

Oleh [Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://michaelnielsen.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7zg7S5OLu9AePjnKFialijDRDZQ)
/ Jun 2019

Ketika seorang pemain golf pertama kali belajar bermain golf, mereka
biasanya menghabiskan sebagian besar waktu mereka mengembangkan ayunan
dasar. Hanya secara berangsur-angsur mereka mengembangkan tembakan lain,
belajar membuat chip, menggambar dan memudar bola, membangun dan
memodifikasi ayunan dasar mereka. Dengan cara yang sama, sampai sekarang
kami telah fokus pada pemahaman algoritma backpropagation. Ini adalah
"ayunan dasar" kami, fondasi untuk belajar di sebagian besar pekerjaan
di jaringan saraf. Dalam bab ini saya menjelaskan serangkaian teknik
yang dapat digunakan untuk meningkatkan implementasi backpropagation
vanilla kami, dan dengan demikian meningkatkan cara jaringan kami
belajar.

Teknik yang akan kami kembangkan dalam bab ini meliputi: pilihan fungsi
biaya yang lebih baik, yang dikenal sebagai fungsi biaya
[lintas-entropi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#the_cross-entropy_cost_function)
; empat apa yang disebut [metode
"regularisasi"](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#overfitting_and_regularization)
(
[regularisasi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#overfitting_and_regularization)
L1 dan L2, dropout, dan ekspansi buatan dari data pelatihan), yang
membuat jaringan kami lebih baik dalam generalisasi di luar data
pelatihan; [metode yang lebih baik untuk menginisialisasi
bobot](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
dalam jaringan; dan [seperangkat heuristik untuk membantu memilih
parameter-hiper yang
baik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#how_to_choose_a_neural_network's_hyper-parameters)
untuk jaringan. Saya juga akan meninjau [beberapa teknik
lain](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques)
dengan lebih mendalam. Diskusi sebagian besar independen satu sama lain,
sehingga Anda dapat melompat ke depan jika Anda mau. Kami juga akan
[menerapkan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#handwriting_recognition_revisited_the_code)
banyak teknik dalam menjalankan kode, dan menggunakannya untuk
meningkatkan hasil yang diperoleh pada masalah klasifikasi tulisan
tangan yang dipelajari pada
[Bab 1](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)
.

Tentu saja, kami hanya membahas sedikit dari sekian banyak, banyak
teknik yang telah dikembangkan untuk digunakan dalam jaring saraf.
Filosofi adalah bahwa hidangan terbaik untuk kebanyakan teknik yang
tersedia adalah studi mendalam tentang beberapa yang paling penting.
Menguasai teknik-teknik penting itu tidak hanya berguna dalam dirinya
sendiri, tetapi juga akan memperdalam pemahaman Anda tentang masalah apa
yang dapat muncul ketika Anda menggunakan jaringan saraf. Itu akan
membuat Anda siap dengan cepat untuk mengambil teknik lain, karena Anda
membutuhkannya.

### [Fungsi biaya lintas-entropi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#the_cross-entropy_cost_function) 

Sebagian besar dari kita merasa tidak enak kalau salah. Segera setelah
mulai belajar piano, saya memberikan penampilan pertama saya di depan
penonton. Saya gugup, dan mulai memainkan lagu yang satu oktaf terlalu
rendah. Saya bingung, dan tidak bisa melanjutkan sampai seseorang
menunjukkan kesalahan saya. Saya sangat malu. Namun sementara tidak
menyenangkan, kita juga belajar dengan cepat ketika kita salah. Anda
bisa bertaruh bahwa lain kali saya bermain di depan penonton saya
bermain di oktaf yang benar\! Sebaliknya, kita belajar lebih lambat
ketika kesalahan kita kurang terdefinisi dengan baik.

Idealnya, kita berharap dan berharap bahwa *jaringan saraf (neural
networks)* kita akan belajar dengan cepat dari kesalahan mereka. Apakah
ini yang terjadi dalam praktik? Untuk menjawab pertanyaan ini, mari kita
lihat contoh mainan. Contohnya melibatkan neuron dengan hanya satu
input:

![http://neuralnetworksanddeeplearning.com/images/tikz28.png](media/image54.png)

Kami akan melatih neuron ini untuk melakukan sesuatu yang sangat mudah:
ambil input 1 ke output 0. Tentu saja, ini adalah tugas yang sepele
sehingga kita dapat dengan mudah menemukan bobot dan bias yang sesuai
dengan tangan, tanpa menggunakan algoritma pembelajaran. Namun, ternyata
menerangi untuk menggunakan gradient descent untuk mencoba mempelajari
bobot dan bias. Jadi mari kita lihat bagaimana neuron belajar.

Untuk membuat segalanya pasti, saya akan memilih bobot awal menjadi 0,6
dan bias awal menjadi 0,9. Ini adalah pilihan umum yang digunakan
sebagai tempat untuk mulai belajar, saya tidak memilih mereka untuk
menjadi spesial dengan cara apa pun. Output awal dari neuron adalah
0,82, jadi dibutuhkan sedikit pembelajaran sebelum neuron kita mendekati
output yang diinginkan, 0,0. Klik "Jalankan" di sudut kanan bawah di
bawah ini untuk melihat bagaimana neuron mempelajari output yang jauh
lebih dekat ke 0,0. Perhatikan bahwa ini bukan animasi yang direkam
sebelumnya, browser Anda sebenarnya menghitung gradien, lalu menggunakan
gradien untuk memperbarui bobot dan bias, dan menampilkan hasilnya.
Tingkat pembelajaran adalah  eta=0,15, yang ternyata cukup lambat
sehingga kita dapat mengikuti apa yang terjadi, tetapi cukup cepat
sehingga kita bisa mendapatkan pembelajaran yang substansial hanya dalam
beberapa detik. Biaya adalah fungsi biaya kuadratik, C, diperkenalkan
kembali di Bab 1. Saya akan mengingatkan Anda tentang bentuk persis dari
fungsi biaya sesaat, jadi tidak perlu pergi dan menggali definisi.
Perhatikan bahwa Anda dapat menjalankan animasi beberapa kali dengan
mengeklik "Jalankan" lagi.

Seperti yang Anda lihat, neuron dengan cepat mempelajari bobot dan bias
yang menurunkan biaya, dan memberikan output dari neuron sekitar 0,09.
Itu bukan hasil yang diinginkan, 0,0, tetapi itu cukup bagus. Namun,
anggaplah kita memilih bobot awal dan bias awal menjadi 2.0. Dalam hal
ini output awal adalah 0,98, yang sangat salah. Mari kita lihat
bagaimana neuron belajar menghasilkan 0 dalam hal ini. Klik "Jalankan"
lagi:

Meskipun contoh ini menggunakan tingkat pembelajaran yang sama
( eta=0,15), kita dapat melihat bahwa pembelajaran dimulai jauh lebih
lambat. Memang, untuk 150 atau lebih zaman belajar pertama, bobot dan
bias tidak banyak berubah sama sekali. Kemudian pembelajaran dimulai
dan, seperti pada contoh pertama kami, output neuron dengan cepat
bergerak mendekati 0,0.

Perilaku ini aneh ketika dikontraskan dengan pembelajaran manusia.
Seperti yang saya katakan di awal bagian ini, kita sering belajar paling
cepat ketika kita salah tentang sesuatu. Tapi kita baru saja melihat
bahwa neuron buatan kita memiliki banyak kesulitan belajar ketika itu
sangat salah - jauh lebih sulit daripada ketika itu hanya sedikit salah.
Terlebih lagi, ternyata perilaku ini terjadi tidak hanya dalam model
mainan ini, tetapi di jaringan yang lebih umum. Mengapa belajar sangat
lambat? Dan bisakah kita menemukan cara menghindari perlambatan ini?

Untuk memahami asal usul masalah, pertimbangkan bahwa neuron kita
belajar dengan mengubah berat dan bias pada tingkat yang ditentukan oleh
turunan parsial dari fungsi biaya,  partialC/ partialw dan
 partialC/ partialb. Jadi mengatakan "belajar itu lambat" benar-benar
sama dengan mengatakan bahwa turunan parsial itu kecil. Tantangannya
adalah memahami mengapa mereka kecil. Untuk memahami itu, mari kita
hitung turunan parsial. Ingatlah bahwa kita menggunakan fungsi biaya
kuadratik, yang, dari Persamaan (6) , diberikan oleh \\ begin {eqnarray}
C = \\ frac {(ya) ^ 2} {2}, \\ tag {54} \\ end {eqnarray} di mana a
adalah output neuron ketika input pelatihan x=1 digunakan, dan y=0
adalah output yang diinginkan yang sesuai. Untuk menulis ini lebih
eksplisit dalam hal bobot dan bias, ingat bahwa a= sigma(z), di mana
z=wx+b. Menggunakan aturan rantai untuk membedakan sehubungan dengan
berat dan bias yang kita dapatkan \\ begin {eqnarray} \\ frac {\\
partial C} {\\ partial w} & = & (ay) \\ sigma '(z) x = a \\ sigma' (z)
\\ tag {55} \\\\ \\ frac {\\ partial C} {\\ partial b} & = & (ay) \\
sigma '(z) = a \\ sigma' (z), \\ tag {56} \\ end {eqnarray} di mana saya
telah mengganti x=1 dan y=0. Untuk memahami perilaku ekspresi ini, mari
kita lihat lebih dekat pada istilah $ \\ sigma '(z) di sebelah kanan.
Ingat bentuk fungsi  sigma:

Kita dapat melihat dari grafik ini bahwa ketika output neuron mendekati
1, kurva menjadi sangat datar, dan sigma '(z) $ menjadi sangat kecil.
Persamaan (55) dan (56) kemudian beri tahu kami bahwa
 partialC/ partialw dan  partialC/ partialb menjadi sangat kecil. Ini
adalah asal dari perlambatan belajar. Terlebih lagi, seperti yang akan
kita lihat nanti, perlambatan belajar terjadi karena alasan yang sama
pada jaringan saraf (*neural networks*) yang lebih umum, bukan hanya
contoh mainan yang telah kita gunakan.

#### [Memperkenalkan fungsi biaya lintas-entropi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#introducing_the_cross-entropy_cost_function) 

Bagaimana kita mengatasi perlambatan belajar? Ternyata kita bisa
menyelesaikan masalah dengan mengganti biaya kuadratik dengan fungsi
biaya yang berbeda, yang dikenal sebagai cross-entropy. Untuk memahami
lintas-entropi, mari kita bergerak sedikit menjauh dari model mainan
super-sederhana kami. Kami akan mengira sebaliknya bahwa kami mencoba
untuk melatih neuron dengan beberapa variabel input, x1,x2, ldots, bobot
yang sesuai w1,w2, ldots, dan bias, b:

![http://neuralnetworksanddeeplearning.com/images/tikz29.png](media/image55.png)

Output dari neuron, tentu saja, a= sigma(z), di mana z= sumjwjxj+b
adalah jumlah bobot dari input. Kami mendefinisikan fungsi biaya
lintas-entropi untuk neuron ini oleh \\ begin {eqnarray} C = - \\ frac
{1} {n} \\ sum\_x \\ kiri \[y \\ ln a + (1-y) \\ ln (1-a) \\ kanan\], \\
tag {57} \\ end { eqnarray} di mana n adalah jumlah total item data
pelatihan, jumlahnya lebih dari semua input pelatihan, x, dan y adalah
output yang diinginkan yang sesuai.

Tidak jelas bahwa ungkapan (57) memperbaiki masalah perlambatan belajar.
Sebenarnya, sejujurnya, bahkan tidak jelas bahwa masuk akal untuk
menyebutnya sebagai fungsi biaya\! Sebelum membahas perlambatan belajar,
mari kita lihat dalam arti apa cross-entropy dapat diartikan sebagai
fungsi biaya.

Dua properti khususnya membuatnya masuk akal untuk menginterpretasikan
cross-entropy sebagai fungsi biaya. Pertama, ini tidak negatif, yaitu,
C\>0. Untuk melihat ini, perhatikan bahwa: (a) semua istilah individual
dalam jumlah dalam (57) negatif, karena kedua logaritma adalah angka
dalam kisaran 0 hingga 1; dan (b) ada tanda minus di bagian depan
jumlah.

Kedua, jika output aktual neuron dekat dengan output yang diinginkan
untuk semua input pelatihan, x, maka cross-entropy akan mendekati nol \*
\* Untuk membuktikan ini saya perlu mengasumsikan bahwa output yang
diinginkan y adalah semua 0 atau 1. Ini biasanya terjadi ketika
memecahkan masalah klasifikasi, misalnya, atau ketika menghitung fungsi
Boolean. Untuk memahami apa yang terjadi ketika kita tidak membuat
asumsi ini, lihat latihan di akhir bagian ini. . Untuk melihat ini,
misalkan misalnya y=0 dan a approx0 untuk beberapa input x. Ini adalah
kasus ketika neuron melakukan pekerjaan dengan baik pada input itu. Kita
melihat bahwa istilah pertama dalam ekspresi (57) untuk biaya
menghilang, karena y=0, sedangkan istilah kedua hanya
− ln(1−a) sekitar0. Analisis serupa berlaku ketika y=1 dan
a sekitar1. Dan kontribusi untuk biaya akan rendah asalkan output
aktual dekat dengan output yang diinginkan.

Kesimpulannya, cross-entropy adalah positif, dan cenderung ke arah nol
ketika neuron menjadi lebih baik dalam menghitung output yang
diinginkan, y, untuk semua input pelatihan, x. Ini adalah kedua properti
yang kami harapkan secara intuitif untuk fungsi biaya. Memang, kedua
properti juga puas dengan biaya kuadratik. Jadi itu berita bagus untuk
cross-entropy. Tetapi fungsi biaya lintas-entropi memiliki manfaat yang,
tidak seperti biaya kuadratik, ia menghindari masalah pembelajaran yang
melambat. Untuk melihat ini, mari kita hitung turunan parsial dari biaya
lintas-entropi sehubungan dengan bobot. Kami mengganti a= sigma(z) ke
(57) , dan menerapkan aturan rantai dua kali, memperoleh: \\ begin
{eqnarray} \\ frac {\\ partial C} {\\ partial w\_j} & = & - \\ frac {1}
{n} \\ sum\_x \\ kiri (\\ frac {y} {\\ sigma (z)} - \\ frac { (1-y)} {1-
\\ sigma (z)} \\ kanan) \\ frac {\\ partial \\ sigma} {\\ partial w\_j}
\\ tag {58} \\\\ & = & - \\ frac {1} {n} \\ sum\_x \\ kiri (\\ frac {y}
{\\ sigma (z)} - \\ frac {(1-y)} {1- \\ sigma (z)} \\ kanan) \\ sigma
'(z) x\_j. \\ tag {59} \\ end {eqnarray} Meletakkan semuanya di atas
penyebut yang sama dan menyederhanakannya menjadi: \\ begin {eqnarray}
\\ frac {\\ partial C} {\\ partial w\_j} & = & \\ frac {1} {n} \\ sum\_x
\\ frac {\\ sigma '(z) x\_j} {\\ sigma (z) (1- \\ sigma (z))} (\\ sigma
(z) -y). \\ tag {60} \\ end {eqnarray} Menggunakan definisi fungsi
sigmoid,  sigma(z)=1/(1+e−z), dan sedikit aljabar kita dapat menunjukkan
bahwa  sigma′(z)= sigma(z)(1− sigma(z)). Saya akan meminta Anda untuk
memverifikasi ini dalam latihan di bawah, tetapi untuk sekarang mari
kita menerimanya sebagaimana diberikan. Kita melihat bahwa sigma '(z)
dan \\ sigma (z) (1- \\ sigma (z)) $ dibatalkan dalam persamaan di atas,
dan menyederhanakan menjadi: \\ begin {eqnarray} \\ frac {\\ partial C}
{\\ partial w\_j} = \\ frac {1} {n} \\ sum\_x x\_j (\\ sigma (z) -y). \\
tag {61} \\ end {eqnarray} Ini adalah ekspresi yang indah. Ini
memberitahu kita bahwa tingkat di mana bobot belajar dikendalikan oleh
 sigma(z)−y, yaitu, oleh kesalahan dalam output. Semakin besar
kesalahan, semakin cepat neuron akan belajar. Inilah yang kami harapkan
secara intuitif. Secara khusus, ia menghindari perlambatan belajar yang
disebabkan oleh istilah  sigma′(z) dalam persamaan analog untuk biaya
kuadratik, Persamaan (55) . Ketika kita menggunakan lintas-entropi,
istilah  sigma′(z) akan dibatalkan, dan kita tidak perlu lagi khawatir
itu kecil. Pembatalan ini adalah keajaiban khusus yang dipastikan oleh
fungsi biaya lintas-entropi. Sebenarnya, itu bukan keajaiban. Seperti
yang akan kita lihat nanti, cross-entropy dipilih secara khusus untuk
memiliki properti ini.

Dengan cara yang sama, kita dapat menghitung turunan parsial untuk bias.
Saya tidak akan membahas semua detail lagi, tetapi Anda dapat dengan
mudah memverifikasi itu \\ begin {eqnarray} \\ frac {\\ partial C} {\\
partial b} = \\ frac {1} {n} \\ sum\_x (\\ sigma (z) -y). \\ tag {62} \\
end {eqnarray} Sekali lagi, ini menghindari perlambatan belajar yang
disebabkan oleh istilah  sigma′(z) dalam persamaan analog untuk biaya
kuadratik, Persamaan (56) .

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_35813) 

  - Verifikasi bahwa  sigma′(z)= sigma(z)(1− sigma(z)).

Mari kita kembali ke contoh mainan yang kita mainkan sebelumnya, dan
mengeksplorasi apa yang terjadi ketika kita menggunakan cross-entropy
alih-alih biaya kuadratik. Untuk mengarahkan kembali diri kita, kita
akan mulai dengan kasus di mana biaya kuadratik baik-baik saja, dengan
bobot mulai 0,6 dan bias mulai 0,9. Tekan "Run" untuk melihat apa yang
terjadi ketika kita mengganti biaya kuadratik dengan entropi silang:

Tidak mengherankan, neuron belajar dengan sangat baik dalam hal ini,
seperti yang terjadi sebelumnya. Dan sekarang mari kita lihat kasus di
mana neuron kita macet sebelumnya (
[tautan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#saturation2_anchor)
, untuk perbandingan), dengan bobot dan bias keduanya mulai dari 2,0:

Keberhasilan\! Kali ini neuron itu belajar dengan cepat, seperti yang
kami harapkan. Jika Anda amati dengan cermat, Anda dapat melihat bahwa
kemiringan kurva biaya awalnya jauh lebih curam daripada daerah datar
awal pada kurva yang sesuai untuk biaya kuadratik. Kecuraman itulah yang
dibeli oleh entropi silang, mencegah kita dari terjebak tepat ketika
kita mengharapkan neuron kita untuk belajar tercepat, yaitu, ketika
neuron mulai dengan sangat salah.

Saya tidak mengatakan tingkat pembelajaran apa yang digunakan dalam
contoh yang baru saja diilustrasikan. Sebelumnya, dengan biaya
kuadratik, kami menggunakan  eta=0,15. Haruskah kita menggunakan tingkat
pembelajaran yang sama dalam contoh-contoh baru? Faktanya, dengan
perubahan fungsi biaya, tidak mungkin untuk mengatakan dengan tepat apa
artinya menggunakan tingkat pembelajaran yang "sama"; ini adalah
perbandingan apel dan jeruk. Untuk kedua fungsi biaya, saya hanya
bereksperimen untuk menemukan tingkat pembelajaran yang memungkinkan
untuk melihat apa yang sedang terjadi. Jika Anda masih penasaran,
meskipun saya tidak setuju, berikut ini kesimpulannya: Saya menggunakan
 eta=0,005 dalam contoh yang baru saja diberikan.

Anda mungkin keberatan bahwa perubahan dalam tingkat pembelajaran
membuat grafik di atas tidak berarti. Siapa yang peduli seberapa cepat
neuron belajar, ketika pilihan tingkat belajar kita sewenang-wenang?
Keberatan itu salah sasaran. Titik grafik bukan tentang kecepatan
belajar absolut. Ini tentang bagaimana kecepatan belajar berubah. Secara
khusus, ketika kita menggunakan pembelajaran biaya kuadratik *lebih
lambat* ketika neuron jelas salah daripada nanti, karena neuron semakin
dekat dengan output yang benar; sementara dengan cross-entropy, belajar
lebih cepat ketika neuron salah. Pernyataan-pernyataan itu tidak
tergantung pada bagaimana tingkat pembelajaran diatur.

Kami telah mempelajari cross-entropy untuk satu neuron. Namun, mudah
untuk menggeneralisasi cross-entropy ke banyak jaringan multi-layer
neuron. Secara khusus, misalkan y=y1,y2, ldots adalah nilai yang
diinginkan pada neuron output, yaitu neuron pada lapisan akhir,
sedangkan aL1,aL2, ldots adalah nilai output aktual . Kemudian kita
mendefinisikan cross-entropy oleh \\ begin {eqnarray} C = - \\ frac {1}
{n} \\ sum\_x \\ sum\_j \\ kiri \[y\_j \\ ln a ^ L\_j + (1-y\_j) \\ ln
(1-a ^ L\_j) \\ kanan\]. \\ tag {63} \\ end {eqnarray} Ini sama dengan
persamaan kami sebelumnya, Persamaan (57) , kecuali sekarang kita
memiliki penjumlahan  sumj atas semua neuron keluaran. Saya tidak akan
secara eksplisit bekerja melalui derivasi, tetapi harus masuk akal bahwa
menggunakan ekspresi (63) menghindari perlambatan belajar di banyak
jaringan neuron. Jika Anda tertarik, Anda dapat mengatasi derivasi pada
masalah di bawah ini.

Kebetulan, saya menggunakan istilah "cross-entropy" dengan cara yang
telah membingungkan beberapa pembaca awal, karena tampaknya tampak
bertentangan dengan sumber lain. Secara khusus, umum untuk
mendefinisikan cross-entropy untuk dua distribusi probabilitas, pj dan
qj, sebagai  sumjpj lnqj. Definisi ini dapat dihubungkan ke (57) , jika
kita memperlakukan satu neuron sigmoid sebagai keluaran distribusi
probabilitas yang terdiri dari aktivasi neuron a dan komplemennya 1−a.

Namun, ketika kita memiliki banyak neuron sigmoid di lapisan akhir,
vektor aLj aktivasi biasanya tidak membentuk distribusi probabilitas.
Akibatnya, definisi seperti  sumjpj lnqj bahkan tidak masuk akal, karena
kami tidak bekerja dengan distribusi probabilitas. Sebagai gantinya,
Anda dapat memikirkan (63) sebagai kumpulan entropi silang per-neuron,
dengan aktivasi masing-masing neuron diinterpretasikan sebagai bagian
dari distribusi probabilitas dua elemen \* \* Tentu saja, di jaringan
kami tidak ada elemen probabilistik, jadi mereka tidak benar-benar
probabilitas . . Dalam pengertian ini, (63) adalah generalisasi dari
cross-entropy untuk distribusi probabilitas.

Kapan kita harus menggunakan cross-entropy alih-alih biaya kuadratik?
Faktanya, cross-entropy hampir selalu merupakan pilihan yang lebih baik,
asalkan neuron output adalah neuron sigmoid. Untuk mengetahui alasannya,
pertimbangkan bahwa ketika kita mengatur jaringan, kita biasanya
menginisialisasi bobot dan bias menggunakan semacam pengacakan. Bisa
jadi pilihan-pilihan awal itu mengakibatkan jaringan salah besar untuk
beberapa input pelatihan - yaitu, neuron output akan jenuh mendekati 1,
ketika seharusnya 0, atau sebaliknya. Jika kita menggunakan biaya
kuadratik yang akan memperlambat belajar. Ini tidak akan berhenti
belajar sepenuhnya, karena bobot akan terus belajar dari input pelatihan
lainnya, tetapi itu jelas tidak diinginkan.

#### [Latihan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercises_824189) 

  - Salah satu pijakan dengan cross-entropy adalah bahwa pada awalnya
    bisa sulit untuk mengingat peran masing-masing dari y s dan a s.
    Sangat mudah untuk bingung tentang apakah formulir yang benar adalah
    −\[y lna+(1−y) ln(1−a)\] atau −\[a lny+(1−a) ln(1−y)\]. Apa yang
    terjadi pada ekspresi kedua ketika y=0 atau 1? Apakah masalah ini
    menimpa ekspresi pertama? Mengapa atau mengapa tidak?

  - Dalam diskusi neuron tunggal pada awal bagian ini, saya berpendapat
    bahwa cross-entropy kecil jika  sigma(z) kira−kira untuk semua input
    pelatihan. Argumen ini mengandalkan y sama dengan 0 atau 1. Ini
    biasanya benar dalam masalah klasifikasi, tetapi untuk masalah lain
    (misalnya, masalah regresi) y kadang-kadang dapat mengambil nilai
    antara antara 0 dan 1. Tunjukkan bahwa cross-entropy masih
    diminimalkan ketika  sigma(z)=y untuk semua input pelatihan. Ketika
    hal ini terjadi, entropi silang memiliki nilai: \\ begin {eqnarray}
    C = - \\ frac {1} {n} \\ sum\_x \[y \\ ln y + (1-y) \\ ln (1-y)\].
    \\ tag {64} \\ end {eqnarray} Kuantitas −\[y lny+(1−y) ln(1−y)\]
    kadang-kadang dikenal sebagai [entropi
    biner](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Binary_entropy_function&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhAaQf2C3sPCZ2bQWsZubh8k7IRmw)
    .

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problems_382219) 

  - **Banyak-lapisan multi-neuron jaringan** Dalam notasi yang
    diperkenalkan pada [bab
    terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)
    , menunjukkan bahwa untuk biaya kuadrat turunan parsial sehubungan
    dengan bobot dalam lapisan output adalah \\ begin {eqnarray} \\ frac
    {\\ partial C} {\\ partial w ^ L\_ {jk}} & = & \\ frac {1} {n} \\
    sum\_x a ^ {L-1} \_k (a ^ L\_j-y\_j) \\ sigma '(z ^ L\_j). \\ tag
    {65} \\ end {eqnarray} Istilah  sigma′(zLj) menyebabkan perlambatan
    belajar setiap kali output neuron jenuh pada nilai yang salah.
    Tunjukkan bahwa untuk biaya lintas-entropi kesalahan output  deltaL
    untuk contoh pelatihan tunggal x diberikan oleh \\ begin {eqnarray}
    \\ delta ^ L = a ^ Ly. \\ tag {66} \\ end {eqnarray} Gunakan
    ungkapan ini untuk menunjukkan bahwa turunan parsial sehubungan
    dengan bobot pada lapisan output diberikan oleh \\ begin {eqnarray}
    \\ frac {\\ partial C} {\\ partial w ^ L\_ {jk}} & = & \\ frac {1}
    {n} \\ sum\_x a ^ {L-1} \_k (a ^ L\_j-y\_j) . \\ tag {67} \\ end
    {eqnarray} sigma '(z ^ L\_j) $ term telah menghilang, dan
    cross-entropy menghindari masalah belajar perlambatan, tidak hanya
    ketika digunakan dengan neuron tunggal, seperti yang kita lihat
    sebelumnya, tetapi juga di banyak jaringan multi-neuron. Variasi
    sederhana pada analisis ini juga berlaku untuk bias. Jika ini tidak
    jelas bagi Anda, maka Anda juga harus mengerjakan analisis itu.

  - **Menggunakan biaya kuadratik ketika kita memiliki neuron linier di
    lapisan keluaran** Misalkan kita memiliki banyak jaringan
    multi-neuron. Misalkan semua neuron pada lapisan terakhir adalah
    *neuron linier* , artinya fungsi aktivasi sigmoid tidak diterapkan,
    dan outputnya hanya aLj=zLj. Tunjukkan bahwa jika kita menggunakan
    fungsi biaya kuadrat maka kesalahan output  deltaL untuk contoh
    pelatihan tunggal x diberikan oleh \\ begin {eqnarray} \\ delta ^ L
    = a ^ Ly. \\ tag {68} \\ end {eqnarray} Demikian pula untuk masalah
    sebelumnya, gunakan ungkapan ini untuk menunjukkan bahwa turunan
    parsial berkenaan dengan bobot dan bias di lapisan output diberikan
    oleh \\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial w ^ L\_
    {jk}} & = & \\ frac {1} {n} \\ sum\_x a ^ {L-1} \_k (a ^ L\_j-y\_j)
    \\ tag {69} \\\\ \\ frac {\\ partial C} {\\ partial b ^ L\_ {j}} & =
    & \\ frac {1} {n} \\ sum\_x (a ^ L\_j-y\_j). \\ tag {70} \\ end
    {eqnarray} Ini menunjukkan bahwa jika output neuron adalah neuron
    linier maka biaya kuadratik tidak akan menimbulkan masalah dengan
    perlambatan belajar. Dalam hal ini, biaya kuadrat sebenarnya adalah
    fungsi biaya yang sesuai untuk digunakan.

#### [Menggunakan cross-entropy untuk mengklasifikasikan digit MNIST](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#using_the_cross-entropy_to_classify_mnist_digits) 

Cross-entropy mudah diterapkan sebagai bagian dari program yang belajar
menggunakan gradient descent dan backpropagation. Kami akan melakukannya
[nanti di bab
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#handwriting_recognition_revisited_the_code)
, mengembangkan versi yang lebih baik dari
[program](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
kami
[sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
untuk mengklasifikasikan digit tulisan tangan MNIST, network.py .
Program baru ini disebut network2.py , dan tidak hanya menggabungkan
lintas-entropi, tetapi juga beberapa teknik lain yang dikembangkan dalam
bab ini \* \* Kode ini tersedia [di
GitHub](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/network2.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgRrjNZoFbpGaWZDuSJCmUDrSWpCA)
. . Untuk saat ini, mari kita lihat seberapa baik program baru kami
mengklasifikasikan digit MNIST. Seperti yang terjadi pada Bab 1, kita
akan menggunakan jaringan dengan 30 neuron tersembunyi, dan kita akan
menggunakan ukuran mini-batch 10. Kami menetapkan tingkat pembelajaran
menjadi  eta=0,5 \* \* Dalam Bab 1 kami menggunakan biaya kuadratik dan
tingkat pembelajaran  eta=3,0. Seperti dibahas di atas, tidak mungkin
untuk mengatakan dengan tepat apa artinya menggunakan tingkat
pembelajaran "sama" ketika fungsi biaya diubah. Untuk kedua fungsi
biaya, saya bereksperimen untuk menemukan tingkat pembelajaran yang
memberikan kinerja mendekati optimal, mengingat pilihan parameter-hiper
lainnya.  
  
Secara kebetulan, ada heuristik umum yang sangat kasar untuk mengaitkan
tingkat pembelajaran lintas-entropi dan biaya kuadratik. Seperti yang
kita lihat sebelumnya, istilah gradien untuk biaya kuadratik memiliki
istilah  sigma′= sigma(1− sigma) tambahan. Misalkan kita nilai rata-rata
ini lebih dari  sigma,  int10d sigma sigma(1− sigma)=1/6. Kita melihat
bahwa (sangat kasar) biaya kuadratik belajar rata-rata 6 kali lebih
lambat, untuk tingkat pembelajaran yang sama. Ini menunjukkan bahwa
titik awal yang masuk akal adalah membagi tingkat pembelajaran untuk
biaya kuadrat sebesar 6. Tentu saja, argumen ini jauh dari keras, dan
tidak boleh dianggap terlalu serius. Meski begitu, terkadang bisa
menjadi titik awal yang berguna. dan kami melatih untuk 30 zaman.
Antarmuka ke network2.py sedikit berbeda dari network.py , tetapi masih
harus jelas apa yang sedang terjadi. Anda dapat, dengan cara,
mendapatkan dokumentasi tentang antarmuka network2.py dengan menggunakan
perintah seperti bantuan (network2.Network.SGD) dalam shell Python.

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

\>\>\> jaringan impor2

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \], biaya = jaringan2
. CrossEntropyCost )

\>\>\> bersih . large\_weight\_initializer ()

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0,5 , evaluation\_data
= test\_data ,

... monitor\_evaluation\_accuracy = Benar )

Perhatikan, omong-omong, bahwa perintah net.large\_weight\_initializer
() digunakan untuk menginisialisasi bobot dan bias dengan cara yang sama
seperti yang dijelaskan pada Bab 1. Kita perlu menjalankan perintah ini
karena nanti dalam bab ini kita akan mengubah bobot default inisialisasi
di jaringan kami. Hasil dari menjalankan urutan perintah di atas adalah
jaringan dengan akurasi $ 95,49 persen. Ini cukup dekat dengan hasil
yang kami peroleh di Bab 1, 95,42 persen, menggunakan biaya kuadratik.

Mari kita lihat juga kasus di mana kita menggunakan neuron tersembunyi $
100, cross-entropy, dan menjaga parameter tetap sama. Dalam hal ini kami
memperoleh akurasi 96,82 persen. Itu peningkatan substansial atas hasil
dari Bab 1, di mana kami memperoleh akurasi klasifikasi 96,59 persen,
menggunakan biaya kuadratik. Itu mungkin terlihat seperti perubahan
kecil, tetapi pertimbangkan bahwa tingkat kesalahan telah turun dari
3,41 persen menjadi 3,18 persen. Artinya, kami telah menghilangkan
sekitar satu dari empat belas kesalahan awal. Itu perbaikan yang cukup
berguna.

Sangat menggembirakan bahwa biaya lintas-entropi memberi kami hasil yang
sama atau lebih baik daripada biaya kuadratik. Namun, hasil ini tidak
secara meyakinkan membuktikan bahwa cross-entropy adalah pilihan yang
lebih baik. Alasannya adalah saya hanya berusaha sedikit untuk memilih
parameter-hiper seperti tingkat pembelajaran, ukuran mini-batch, dan
sebagainya. Agar peningkatannya benar-benar meyakinkan, kita perlu
melakukan pekerjaan menyeluruh dengan mengoptimalkan parameter-hiper
tersebut. Namun, hasilnya menggembirakan, dan memperkuat argumen
teoritis kami sebelumnya bahwa cross-entropy adalah pilihan yang lebih
baik daripada biaya kuadratik.

Ngomong-ngomong, ini adalah bagian dari pola umum yang akan kita lihat
melalui bab ini dan, memang, melalui sebagian besar sisa buku ini. Kami
akan mengembangkan teknik baru, kami akan mencobanya, dan kami akan
mendapatkan hasil yang "ditingkatkan". Tentu saja menyenangkan melihat
perbaikan seperti itu. Tetapi interpretasi dari perbaikan seperti itu
selalu bermasalah. Mereka hanya benar-benar meyakinkan jika kita melihat
peningkatan setelah melakukan upaya luar biasa untuk mengoptimalkan
semua parameter hiper lainnya. Itu banyak pekerjaan, membutuhkan banyak
daya komputasi, dan kami biasanya tidak akan melakukan penyelidikan yang
mendalam. Sebagai gantinya, kami akan melanjutkan berdasarkan tes
informal seperti yang dilakukan di atas. Namun, Anda harus tetap ingat
bahwa tes semacam itu tidak memiliki bukti definitif, dan tetap waspada
terhadap tanda-tanda bahwa argumennya mogok.

Sekarang, kita telah membahas cross-entropy secara panjang lebar.
Mengapa harus bersusah payah jika hanya memberikan sedikit peningkatan
pada hasil MNIST kami? Nanti dalam bab ini kita akan melihat teknik lain
- terutama,
[regularisasi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#overfitting_and_regularization)
- yang memberikan peningkatan yang jauh lebih besar. Jadi mengapa begitu
banyak fokus pada lintas-entropi? Sebagian alasannya adalah bahwa
cross-entropy adalah fungsi biaya yang banyak digunakan, dan juga layak
dipahami dengan baik. Tetapi alasan yang lebih penting adalah bahwa
kejenuhan neuron adalah masalah penting dalam jaring saraf, masalah yang
akan kita ulangi berulang kali di seluruh buku ini. Jadi saya telah
membahas cross-entropy panjang lebar karena ini adalah laboratorium yang
baik untuk mulai memahami saturasi neuron dan bagaimana hal itu dapat
diatasi.

#### [Apa yang dimaksud dengan lintas-entropi?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#what_does_the_cross-entropy_mean_where_does_it_come_from) [Dari mana asalnya?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#what_does_the_cross-entropy_mean_where_does_it_come_from) 

Diskusi kami tentang lintas-entropi berfokus pada analisis aljabar dan
implementasi praktis. Itu berguna, tetapi masih menyisakan pertanyaan
konseptual yang lebih luas, seperti: apa arti lintas-entropi? Apakah ada
cara berpikir intuitif tentang lintas-entropi? Dan bagaimana kita bisa
memimpikan entropi silang pada awalnya?

Mari kita mulai dengan pertanyaan terakhir: apa yang bisa memotivasi
kita untuk memikirkan cross-entropy? Misalkan kita menemukan perlambatan
belajar yang dijelaskan sebelumnya, dan memahami bahwa asalnya adalah
 sigma′(z) istilah dalam Persamaan (55) dan (56) . Setelah sedikit
memandang persamaan itu, kita mungkin bertanya-tanya apakah mungkin
untuk memilih fungsi biaya sehingga istilah  sigma′(z) menghilang. Dalam
hal ini, biaya C=Cx untuk contoh pelatihan tunggal x akan memuaskan \\
begin {eqnarray} \\ frac {\\ partial C} {\\ partial w\_j} & = & x\_j
(ay) \\ tag {71} \\\\ \\ frac {\\ partial C} {\\ partial b} & = & (ay).
\\ tag {72} \\ end {eqnarray} Jika kita dapat memilih fungsi biaya untuk
membuat persamaan ini benar, maka mereka akan menangkap dengan cara
sederhana intuisi bahwa semakin besar kesalahan awal, semakin cepat
neuron belajar. Mereka juga akan menghilangkan masalah perlambatan
belajar. Bahkan, mulai dari persamaan ini sekarang kita akan menunjukkan
bahwa dimungkinkan untuk mendapatkan bentuk entropi silang, cukup dengan
mengikuti hidung matematika kita. Untuk melihat ini, perhatikan bahwa
dari aturan rantai yang kita miliki \\ begin {eqnarray} \\ frac {\\
partial C} {\\ partial b} = \\ frac {\\ partial C} {\\ partial a} \\
sigma '(z). \\ tag {73} \\ end {eqnarray} Menggunakan
 sigma′(z)= sigma(z)(1− sigma(z))=a(1−a) persamaan terakhir menjadi
\\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial b} = \\ frac {\\
partial C} {\\ partial a} a (1-a). \\ tag {74} \\ end {eqnarray}
Membandingkan dengan Persamaan (72) kami memperoleh \\ begin {eqnarray}
\\ frac {\\ partial C} {\\ partial a} = \\ frac {ay} {a (1-a)}. \\ tag
{75} \\ end {eqnarray} Mengintegrasikan ungkapan ini sehubungan dengan a
give \\ begin {eqnarray} C = - \[y \\ ln a + (1-y) \\ ln (1-a)\] + {\\
rm constant}, \\ tag {76} \\ end {eqnarray} untuk beberapa konstanta
integrasi. Ini adalah kontribusi terhadap biaya dari satu contoh
pelatihan, x. Untuk mendapatkan fungsi biaya penuh, kita harus rata-rata
dibandingkan contoh pelatihan, memperoleh \\ begin {eqnarray} C = - \\
frac {1} {n} \\ sum\_x \[y \\ ln a + (1-y) \\ ln (1-a)\] + {\\ rm
constant}, \\ tag {77} \\ end {eqnarray} di mana konstanta di sini
adalah rata-rata konstanta individu untuk setiap contoh pelatihan. Jadi
kita melihat bahwa Persamaan (71) dan (72) secara unik menentukan bentuk
entropi silang, hingga istilah konstan keseluruhan. Entropi silang
bukanlah sesuatu yang secara ajaib ditarik keluar dari udara tipis.
Sebaliknya, itu adalah sesuatu yang bisa kita temukan dengan cara yang
sederhana dan alami.

Bagaimana dengan makna intuitif dari entropi silang? Bagaimana
seharusnya kita memikirkannya? Menjelaskan ini secara mendalam akan
membawa kita lebih jauh dari yang saya inginkan. Namun, perlu disebutkan
bahwa ada cara standar untuk menafsirkan entropi silang yang berasal
dari bidang teori informasi. Secara kasar, idenya adalah bahwa
cross-entropy adalah ukuran kejutan. Secara khusus, neuron kami mencoba
menghitung fungsi x rightarrowy=y(x). Tetapi ia menghitung fungsi
x rightarrowa=a(x). Misalkan kita menganggap a sebagai probabilitas
estimasi neuron kita bahwa y adalah 1, dan 1−a adalah perkiraan
probabilitas bahwa nilai yang tepat untuk y adalah 0. Kemudian
cross-entropy mengukur seberapa "mengejutkan" kita, secara rata-rata,
ketika kita mempelajari nilai sebenarnya untuk y. Kita mendapat kejutan
rendah jika outputnya sesuai harapan kita, dan kejutan tinggi jika
outputnya tidak terduga. Tentu saja, saya belum mengatakan apa arti
"kejutan", jadi ini mungkin seperti kata-kata kosong. Tetapi pada
kenyataannya ada cara informasi-teoretis yang tepat untuk mengatakan apa
yang dimaksud dengan kejutan. Sayangnya, saya tidak tahu diskusi yang
baik, singkat, dan lengkap tentang hal ini yang tersedia secara online.
Tetapi jika Anda ingin menggali lebih dalam, maka Wikipedia berisi
[ringkasan
singkat](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Cross_entropy&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjEVb-aWx2Ml0XfDeU8YGw97BLTAg#Motivation)
yang akan membantu Anda memulai di jalur yang benar. Dan detailnya dapat
diisi dengan mengerjakan materi tentang ketimpangan Kraft di bab 5 buku
tentang teori informasi oleh [Cover dan
Thomas](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://books.google.ca/books%3Fid%3DVWq5GG6ycxMC&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhijKocR2PyH107JNt38b2eNB9nWGg)
.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problem_240447) 

  - Kita telah membahas panjang lebar tentang perlambatan belajar yang
    dapat terjadi ketika neuron keluaran jenuh, dalam jaringan yang
    menggunakan biaya kuadratik untuk melatih. Faktor lain yang dapat
    menghambat pembelajaran adalah keberadaan istilah xj dalam Persamaan
    (61) . Karena istilah ini, ketika input xj mendekati nol, bobot yang
    sesuai wj akan belajar perlahan. Jelaskan mengapa tidak mungkin
    untuk menghilangkan istilah xj melalui pilihan fungsi biaya yang
    cerdas.

#### [Softmax](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#softmax) 

Dalam bab ini sebagian besar kita akan menggunakan biaya lintas-entropi
untuk mengatasi masalah perlambatan belajar. Namun, saya ingin
menjelaskan secara singkat pendekatan lain untuk masalah ini,
berdasarkan apa yang disebut lapisan *softmax* dari neuron. Kami
sebenarnya tidak akan menggunakan lapisan softmax di sisa bab ini, jadi
jika Anda sedang terburu-buru, Anda dapat melompat ke bagian
selanjutnya. Namun, softmax masih layak dipahami, sebagian karena itu
secara intrinsik menarik, dan sebagian karena kita akan menggunakan
lapisan softmax pada
[Bab 6](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ)
, dalam diskusi kita tentang jaringan saraf (*neural networks*) yang
dalam.

Gagasan softmax adalah untuk menentukan tipe baru dari lapisan keluaran
untuk jaringan saraf (*neural networks*) kita. Itu dimulai dengan cara
yang sama seperti dengan lapisan sigmoid, dengan membentuk input
terbobot \* \* Dalam menggambarkan softmax kita akan sering menggunakan
notasi yang diperkenalkan pada [bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)
. Anda mungkin ingin meninjau kembali bab itu jika Anda perlu
menyegarkan ingatan Anda tentang arti dari notasi tersebut.
zLj= sumkwLjkaL−1k+bLj. Namun, kami tidak menerapkan fungsi sigmoid
untuk mendapatkan output. Sebagai gantinya, dalam lapisan softmax kita
menerapkan apa yang disebut *fungsi softmax* ke zLj. Menurut fungsi ini,
aktivasi aLj dari j th output neuron adalah \\ begin {eqnarray} a ^ L\_j
= \\ frac {e ^ {z ^ L\_j}} {\\ sum\_k e ^ {z ^ L\_k}}, \\ tag {78} \\
end {eqnarray} di mana dalam penyebut kita menjumlahkan semua neuron
output.

Jika Anda tidak terbiasa dengan fungsi softmax, Persamaan (78) mungkin
terlihat cukup buram. Jelas tidak jelas mengapa kami ingin menggunakan
fungsi ini. Dan juga tidak jelas bahwa ini akan membantu kita mengatasi
masalah perlambatan belajar. Untuk lebih memahami Persamaan (78) ,
misalkan kita memiliki jaringan dengan empat neuron keluaran, dan empat
input terbobot yang sesuai, yang akan kami nyatakan zL1,zL2,zL3, dan
zL4. Yang ditunjukkan di bawah ini adalah bilah geser yang dapat
disesuaikan yang memperlihatkan nilai yang mungkin untuk input terbobot,
dan grafik dari aktivasi keluaran yang sesuai. Tempat yang baik untuk
memulai eksplorasi adalah dengan menggunakan bilah geser bawah untuk
menambah zL4:

|      |  |
| ---- |  |
| zL1= |  |

| aL1=  |  |
| ----- |  |
| zL2 = |  |

| aL2=  |  |
| ----- |  |
| zL3 = |  |

| aL3=  |  |
| ----- |  |
| zL4 = |  |

|      |
| ---- |
| aL4= |

Saat Anda meningkatkan zL4, Anda akan melihat peningkatan aktivasi
output yang sesuai, aL4, dan penurunan aktivasi output lainnya. Demikian
pula, jika Anda mengurangi zL4 maka aL4 akan berkurang, dan semua
aktivasi output lainnya akan meningkat. Bahkan, jika Anda melihat lebih
dekat, Anda akan melihat bahwa dalam kedua kasus, perubahan total dalam
aktivasi lain justru mengkompensasi perubahan dalam aL4. Alasannya
adalah bahwa aktivasi output dijamin selalu berjumlah hingga 1, karena
kita dapat membuktikan menggunakan Persamaan (78) dan aljabar kecil: \\
begin {eqnarray} \\ sum\_j a ^ L\_j & = & \\ frac {\\ sum\_j e ^ {z ^
L\_j}} {\\ sum\_k e ^ {z ^ L\_k}} = 1. \\ tag {79} \\ end {eqnarray}
Akibatnya, jika aL4 meningkat, maka aktivasi output lainnya harus
berkurang dengan jumlah total yang sama, untuk memastikan jumlah semua
aktivasi tetap 1. Dan, tentu saja, pernyataan serupa berlaku untuk semua
aktivasi lainnya.

Persamaan (78) juga menyiratkan bahwa aktivasi keluaran semuanya
positif, karena fungsi eksponensial positif. Menggabungkan ini dengan
pengamatan pada paragraf terakhir, kita melihat bahwa output dari
lapisan softmax adalah satu set angka positif yang berjumlah hingga 1.
Dengan kata lain, output dari lapisan softmax dapat dianggap sebagai
distribusi probabilitas.

Fakta bahwa lapisan softmax menghasilkan distribusi probabilitas agak
menyenangkan. Dalam banyak masalah, lebih mudah untuk
menginterpretasikan aktivasi output aLj sebagai estimasi jaringan dari
probabilitas bahwa output yang benar adalah j. Jadi, misalnya, dalam
masalah klasifikasi MNIST, kita dapat mengartikan aLj sebagai estimasi
estimasi jaringan bahwa klasifikasi digit yang benar adalah j.

Sebaliknya, jika lapisan output adalah lapisan sigmoid, maka kita tentu
tidak bisa berasumsi bahwa aktivasi membentuk distribusi probabilitas.
Saya tidak akan secara eksplisit membuktikannya, tetapi harus masuk akal
bahwa aktivasi dari lapisan sigmoid tidak akan secara umum membentuk
distribusi probabilitas. Dan dengan lapisan keluaran sigmoid kita tidak
memiliki interpretasi yang sederhana dari aktivasi keluaran.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_332838) 

  - Buat contoh yang menunjukkan secara eksplisit bahwa dalam jaringan
    dengan lapisan keluaran sigmoid, aktivasi keluaran aLj tidak akan
    selalu berjumlah 1.

Kami mulai membangun beberapa perasaan untuk fungsi softmax dan cara
lapisan softmax berperilaku. Hanya untuk meninjau di mana kita berada:
eksponensial dalam Persamaan (78) memastikan bahwa semua aktivasi output
positif. Dan jumlah dalam penyebut Persamaan (78) memastikan bahwa
output softmax berjumlah 1. Sehingga bentuk tertentu tidak lagi tampak
begitu misterius: melainkan merupakan cara alami untuk memastikan bahwa
aktivasi output membentuk distribusi probabilitas. Anda dapat menganggap
softmax sebagai cara men-rescaling zLj, dan kemudian menyatukannya untuk
membentuk distribusi probabilitas.

#### [Latihan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercises_193619) 

  - **Monotonisitas softmax** Tunjukkan bahwa  partialaLj/ partialzLk
    bernilai positif jika j=k dan negatif jika j neqk. Sebagai
    akibatnya, meningkatkan zLj dijamin untuk meningkatkan aktivasi
    output yang sesuai, aLj, dan akan mengurangi semua aktivasi output
    lainnya. Kami sudah melihat ini secara empiris dengan slider, tetapi
    ini adalah bukti yang kuat.

  - **Non-lokalitas softmax** Hal yang menyenangkan tentang lapisan
    sigmoid adalah bahwa output aLj adalah fungsi dari input terbobot
    yang sesuai, aLj= sigma(zLj). Jelaskan mengapa ini bukan kasus untuk
    lapisan softmax: aktivasi output tertentu aLj tergantung pada
    *semua* input terbobot.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problem_905066) 

  - **Membalik lapisan softmax** Misalkan kita memiliki *jaringan saraf
    (neural networks)* dengan lapisan keluaran softmax, dan aktivasi aLj
    diketahui. Tunjukkan bahwa input terbobot yang sesuai memiliki
    bentuk zLj= lnaLj+C, untuk beberapa konstanta C yang tidak
    tergantung pada j.

**Masalah pelambatan belajar:** Kami sekarang telah membangun keakraban
yang cukup dengan lapisan softmax dari neuron. Tapi kita belum melihat
bagaimana lapisan softmax memungkinkan kita mengatasi masalah
perlambatan belajar. Untuk memahami itu, mari kita mendefinisikan fungsi
biaya *log-likelihood* . Kami akan menggunakan x untuk menunjukkan input
pelatihan ke jaringan, dan y untuk menunjukkan output yang diinginkan
yang sesuai. Maka biaya log-kemungkinan yang terkait dengan input
pelatihan ini adalah \\ begin {eqnarray} C \\ equiv - \\ ln a ^ L\_y. \\
tag {80} \\ end {eqnarray} Jadi, misalnya, jika kita berlatih dengan
gambar MNIST, dan memasukkan gambar 7, maka biaya log-kemungkinan adalah
− lnaL7. Untuk melihat ini masuk akal, pertimbangkan kasus ketika
jaringan melakukan pekerjaan dengan baik, yaitu, yakin inputnya adalah
7. Dalam hal ini, ia akan memperkirakan nilai untuk probabilitas terkait
aL7 yang mendekati 1, sehingga biaya − lnaL7 akan menjadi kecil.
Sebaliknya, ketika jaringan tidak melakukan pekerjaan dengan baik,
probabilitas aL7 akan lebih kecil, dan biaya − lnaL7 akan lebih besar.
Jadi biaya log-kemungkinan berperilaku seperti yang kita harapkan fungsi
biaya untuk berperilaku.

Bagaimana dengan masalah perlambatan belajar? Untuk menganalisis itu,
ingat bahwa kunci untuk perlambatan belajar adalah perilaku kuantitas
 partialC/ partialwLjk dan  partialC/ partialbLj. Saya tidak akan
melalui derivasi secara eksplisit - saya akan meminta Anda untuk
melakukan dalam masalah, di bawah ini - tetapi dengan sedikit aljabar
Anda dapat menunjukkan bahwa \* \* Perhatikan bahwa saya menyalahgunakan
notasi di sini, menggunakan y dalam sedikit cara yang berbeda untuk
paragraf terakhir. Dalam paragraf terakhir, kami menggunakan y untuk
menunjukkan output yang diinginkan dari jaringan - misalnya,
menghasilkan "7" jika gambar 7 dimasukkan. Tetapi dalam persamaan yang
mengikuti saya menggunakan y untuk menunjukkan vektor aktivasi keluaran
yang sesuai dengan 7, yaitu, vektor yang semuanya 0 s, kecuali 1 di
lokasi 7 th. \\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial b ^
L\_j} & = & a ^ L\_j-y\_j \\ tag {81} \\\\ \\ frac {\\ partial C} {\\
partial w ^ L\_ {jk} } & = & a ^ {L-1} \_k (a ^ L\_j-y\_j) \\ tag {82}
\\ end {eqnarray} Persamaan ini sama dengan ekspresi analog yang
diperoleh dalam analisis awal kami dari cross-entropy. Bandingkan,
misalnya, Persamaan (82) ke Persamaan (67) . Itu persamaan yang sama,
meskipun dalam yang terakhir saya rata-rata lebih dari contoh pelatihan.
Dan, seperti dalam analisis sebelumnya, ungkapan-ungkapan ini memastikan
bahwa kita tidak akan menghadapi perlambatan belajar. Bahkan, akan
berguna untuk memikirkan lapisan output softmax dengan biaya
log-likelihood yang sangat mirip dengan lapisan output sigmoid dengan
biaya lintas-entropi.

Dengan adanya kesamaan ini, haruskah Anda menggunakan lapisan keluaran
sigmoid dan lintas-entropi, atau lapisan keluaran softmax dan
kemungkinan log? Faktanya, dalam banyak situasi kedua pendekatan bekerja
dengan baik. Melalui sisa bab ini kita akan menggunakan lapisan keluaran
sigmoid, dengan biaya lintas-entropi. Kemudian, di
[Bab 6](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ)
, kadang-kadang kita akan menggunakan lapisan output softmax, dengan
biaya log-likelihood. Alasan peralihan ini adalah untuk membuat beberapa
jaringan kami di kemudian hari lebih mirip dengan jaringan yang
ditemukan dalam makalah akademis berpengaruh tertentu. Sebagai poin
prinsip yang lebih umum, softmax plus log-likelihood layak digunakan
setiap kali Anda ingin mengartikan aktivasi output sebagai probabilitas.
Itu tidak selalu menjadi perhatian, tetapi dapat berguna dengan masalah
klasifikasi (seperti MNIST) yang melibatkan kelas-kelas terpisah.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problems_263173) 

  - Turunkan Persamaan (81) dan (82) .

  - **Dari mana asal nama "softmax"?** Misalkan kita mengubah fungsi
    softmax sehingga aktivasi keluaran diberikan oleh \\ begin
    {eqnarray} a ^ L\_j = \\ frac {e ^ {cz ^ L\_j}} {\\ sum\_k e ^ {cz ^
    L\_k}}, \\ tag {83} \\ end {eqnarray} di mana c adalah konstanta
    positif . Perhatikan bahwa c=1 sesuai dengan fungsi softmax standar.
    Tetapi jika kita menggunakan nilai berbeda dari c kita mendapatkan
    fungsi yang berbeda, yang secara kualitatif agak mirip dengan
    softmax. Secara khusus, menunjukkan bahwa aktivasi output membentuk
    distribusi probabilitas, seperti halnya untuk softmax biasa.
    Misalkan kita membiarkan c menjadi besar, yaitu c rightarrow infty.
    Berapa nilai pembatas untuk aktivasi output aLj? Setelah
    menyelesaikan masalah ini, harus jelas bagi Anda mengapa kami
    menganggap fungsi c=1 sebagai versi "lunak" dari fungsi maksimum.
    Ini adalah asal dari istilah "softmax".

  - **Backpropagation dengan softmax dan biaya log-likelihood** Dalam
    bab terakhir kami membuat algoritma backpropagation untuk jaringan
    yang mengandung lapisan sigmoid. Untuk menerapkan algoritma ke
    jaringan dengan lapisan softmax kita perlu mencari ekspresi untuk
    kesalahan  deltaLj equiv partialC/ partialzLj di lapisan terakhir.
    Tunjukkan bahwa ungkapan yang sesuai adalah: \\ begin {eqnarray} \\
    delta ^ L\_j = a ^ L\_j -y\_j. \\ tag {84} \\ end {eqnarray}
    Menggunakan ungkapan ini kita dapat menerapkan algoritma
    backpropagation ke jaringan menggunakan lapisan output softmax dan
    biaya kemungkinan log.

### [Overfitting dan regularisasi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#overfitting_and_regularization) 

Fisikawan pemenang hadiah Nobel, Enrico Fermi, pernah ditanya
pendapatnya tentang model matematika yang diajukan beberapa rekan
sebagai solusi untuk masalah fisika penting yang belum terpecahkan.
Model tersebut memberikan persetujuan yang sangat baik dengan
eksperimen, tetapi Fermi skeptis. Dia bertanya berapa banyak parameter
gratis yang dapat diatur dalam model. "Empat" adalah jawabannya. Fermi
menjawab \* \* Kutipan tersebut berasal dari sebuah artikel menawan oleh
[Freeman
Dyson](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.nature.com/nature/journal/v427/n6972/full/427297a.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjo7Z1uIq4ZqLw4W3PXuLTP_Ctxag)
, yang merupakan salah satu orang yang mengusulkan model cacat. Gajah
empat parameter dapat ditemukan di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.johndcook.com/blog/2011/06/21/how-to-fit-an-elephant/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgF7EjAp3XYsMHzTYTwWSUp1cXRQw)
. : "Saya ingat teman saya Johnny von Neumann dulu mengatakan, dengan
empat parameter saya dapat memuat seekor gajah, dan dengan lima saya
dapat membuatnya menggoyangkan belalainya."

Intinya, tentu saja, adalah bahwa model dengan sejumlah besar parameter
bebas dapat menggambarkan berbagai fenomena yang luar biasa luas. Bahkan
jika model seperti itu setuju dengan data yang tersedia, itu tidak
membuatnya menjadi model yang baik. Ini mungkin hanya berarti ada cukup
kebebasan dalam model yang dapat menggambarkan hampir semua kumpulan
data dari ukuran yang diberikan, tanpa menangkap wawasan asli ke dalam
fenomena yang mendasarinya. Ketika itu terjadi model akan bekerja dengan
baik untuk data yang ada, tetapi akan gagal untuk menggeneralisasi ke
situasi baru. Tes sebenarnya dari sebuah model adalah kemampuannya untuk
membuat prediksi dalam situasi yang belum pernah terpapar sebelumnya.

Fermi dan von Neumann curiga pada model dengan empat parameter. 30
jaringan neuron tersembunyi kami untuk mengklasifikasikan digit MNIST
memiliki hampir 24.000 parameter\! Itu banyak parameter. 100 jaringan
neuron tersembunyi kami memiliki hampir 80.000 parameter, dan jaring
saraf dalam yang canggih kadang-kadang berisi jutaan atau bahkan
milyaran parameter. Haruskah kita mempercayai hasilnya?

Mari kita pertajam masalah ini dengan membangun situasi di mana jaringan
kami melakukan pekerjaan yang buruk untuk menggeneralisasi situasi baru.
Kami akan menggunakan 30 jaringan neuron tersembunyi kami, dengan 23.860
parameternya. Tapi kami tidak akan melatih jaringan menggunakan 50.000
gambar pelatihan MNIST. Sebagai gantinya, kami hanya akan menggunakan
1.000 gambar latihan pertama. Menggunakan set terbatas itu akan membuat
masalah dengan generalisasi jauh lebih jelas. Kami akan berlatih dengan
cara yang sama seperti sebelumnya, menggunakan fungsi biaya
lintas-entropi, dengan tingkat pembelajaran  eta=0,5 dan ukuran
mini-batch 10. Namun, kami akan berlatih selama 400 zaman, jumlah yang
agak lebih besar dari sebelumnya, karena kami tidak menggunakan banyak
contoh pelatihan. Mari kita gunakan network2 untuk melihat cara
perubahan fungsi biaya:

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

\>\>\> jaringan impor2

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \], biaya = jaringan2
. CrossEntropyCost )

\>\>\> bersih . large\_weight\_initializer ()

\>\>\> bersih . SGD ( training\_data \[: 1000 \], 400 , 10 , 0,5 ,
evaluation\_data = test\_data ,

... monitor\_evaluation\_accuracy = Benar , monitor\_training\_cost =
Benar )

Dengan menggunakan hasil, kita dapat merencanakan cara perubahan biaya
saat jaringan mempelajari \* \* Ini dan empat grafik berikutnya
dihasilkan oleh program
[overfitting.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/overfitting.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjC8_dUCFd-B9PYjKIJKcCYTVmqRQ)
. :

![http://neuralnetworksanddeeplearning.com/images/overfitting1.png](media/image57.png)

Ini terlihat menggembirakan, menunjukkan penurunan biaya yang mulus,
seperti yang kami harapkan. Perhatikan bahwa saya hanya menunjukkan
zaman pelatihan 200 hingga 399. Ini memberi kita pandangan dekat yang
bagus tentang tahap-tahap pembelajaran selanjutnya, yang, seperti yang
akan kita lihat, ternyata merupakan tempat tindakan yang menarik.

Sekarang mari kita lihat bagaimana akurasi klasifikasi pada data uji
berubah seiring waktu:

![http://neuralnetworksanddeeplearning.com/images/overfitting2.png](media/image58.png)

Sekali lagi, saya telah memperbesar sedikit. Dalam 200 zaman pertama
(tidak diperlihatkan) keakuratannya meningkat hingga hanya di bawah 82
persen. Pembelajaran kemudian secara bertahap melambat. Akhirnya, pada
sekitar zaman 280 akurasi klasifikasi cukup banyak berhenti meningkat.
Zaman kemudian hanya melihat fluktuasi stokastik kecil di dekat nilai
akurasi pada zaman 280. Bandingkan ini dengan grafik sebelumnya, di mana
biaya yang terkait dengan data pelatihan terus turun dengan lancar. Jika
kita hanya melihat biaya itu, tampaknya model kita masih "lebih baik".
Tetapi hasil akurasi tes menunjukkan peningkatan itu ilusi. Sama seperti
model yang tidak disukai Fermi, apa yang dipelajari jaringan kami
setelah zaman 280 tidak lagi digeneralisasikan ke data uji. Dan itu
bukan pembelajaran yang berguna. Kami mengatakan jaringan *overfitting*
atau *overtraining di* luar zaman 280.

Anda mungkin bertanya-tanya apakah masalahnya di sini adalah saya
melihat *biaya* pada data pelatihan, yang bertentangan dengan *akurasi
klasifikasi* pada data uji. Dengan kata lain, mungkin masalahnya adalah
kita membuat perbandingan apel dan jeruk. Apa yang akan terjadi jika
kami membandingkan biaya pada data pelatihan dengan biaya pada data uji,
jadi kami membandingkan tindakan serupa? Atau mungkin kita bisa
membandingkan akurasi klasifikasi pada data pelatihan dan data uji?
Bahkan, pada dasarnya fenomena yang sama muncul tidak peduli bagaimana
kita melakukan perbandingan. Namun rinciannya memang berubah. Misalnya,
mari kita lihat biaya pada data uji:

![http://neuralnetworksanddeeplearning.com/images/overfitting3.png](media/image59.png)

Kita dapat melihat bahwa biaya pada data uji meningkat sampai sekitar
zaman 15, tetapi setelah itu benar-benar mulai memburuk, meskipun biaya
pada data pelatihan terus menjadi lebih baik. Ini adalah tanda lain
bahwa model kami terlalu cocok. Namun, hal itu menimbulkan teka-teki,
yaitu apakah kita harus menganggap zaman 15 atau zaman 280 sebagai titik
di mana overfitting akan mendominasi pembelajaran? Dari sudut pandang
praktis, yang benar-benar kami pedulikan adalah meningkatkan akurasi
klasifikasi pada data uji, sementara biaya pada data uji tidak lebih
dari proksi untuk akurasi klasifikasi. Maka, sangat masuk akal untuk
menganggap zaman 280 sebagai titik di mana overfitting mendominasi
pembelajaran dalam jaringan saraf (*neural networks*) kita.

Tanda overfitting lain mungkin terlihat pada ketepatan klasifikasi pada
data pelatihan:

![http://neuralnetworksanddeeplearning.com/images/overfitting4.png](media/image60.png)

Akurasi meningkat hingga 100 persen. Yaitu, jaringan kami dengan benar
mengklasifikasikan semua gambar pelatihan 1.000\! Sementara itu, akurasi
pengujian kami hanya mencapai $ 82,27 persen. Jadi jaringan kami
benar-benar mempelajari tentang kekhasan set pelatihan, bukan hanya
mengenali angka secara umum. Hampir seolah-olah jaringan kami hanya
menghafal set pelatihan, tanpa memahami angka dengan cukup baik untuk
digeneralisasikan ke set tes.

Overfitting adalah masalah utama dalam jaringan saraf. Ini terutama
benar dalam jaringan modern, yang sering memiliki jumlah bobot dan bias
yang sangat besar. Untuk melatih secara efektif, kita perlu cara
mendeteksi ketika overfitting sedang terjadi, jadi kita tidak berlatih
berlebihan. Dan kami ingin memiliki teknik untuk mengurangi efek
overfitting.

Cara yang jelas untuk mendeteksi overfitting adalah dengan menggunakan
pendekatan di atas, melacak keakuratan data uji saat jaringan kami
berlatih. Jika kita melihat bahwa keakuratan pada data tes tidak lagi
meningkat, maka kita harus berhenti berlatih. Tentu saja, secara tegas,
ini belum tentu merupakan tanda overfitting. Mungkin keakuratan pada
data uji dan data pelatihan keduanya berhenti meningkat pada saat yang
sama. Tetap saja, mengadopsi strategi ini akan mencegah overfitting.

Bahkan, kami akan menggunakan variasi pada strategi ini. Ingatlah bahwa
ketika kita memuat dalam data MNIST kita memuat dalam tiga set data:

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

Hingga kini kami telah menggunakan data training\_data dan test\_data ,
dan mengabaikan validation\_data . Validasi\_data berisi 10.000 gambar
digit, gambar yang berbeda dari 50.000 gambar dalam set pelatihan MNIST,
dan 10.000 gambar dalam set tes MNIST. Alih-alih menggunakan test\_data
untuk mencegah overfitting, kami akan menggunakan validation\_data .
Untuk melakukan ini, kita akan menggunakan banyak strategi yang sama
seperti yang dijelaskan di atas untuk test\_data . Artinya, kami akan
menghitung akurasi klasifikasi pada validation\_data di akhir setiap
zaman. Setelah akurasi klasifikasi pada validation\_data telah jenuh,
kami menghentikan pelatihan. Strategi ini disebut *penghentian dini* .
Tentu saja, dalam praktiknya kita tidak akan langsung tahu kapan
akurasinya telah jenuh. Sebagai gantinya, kami melanjutkan pelatihan
sampai kami yakin bahwa akurasinya telah jenuh \* \* Diperlukan
penilaian untuk menentukan kapan harus berhenti. Dalam grafik saya
sebelumnya saya mengidentifikasi zaman 280 sebagai tempat di mana
akurasi jenuh. Mungkin saja itu terlalu pesimistis. *Jaringan saraf
(neural networks)* kadang-kadang dataran tinggi untuk sementara waktu
dalam pelatihan, sebelum terus membaik. Saya tidak akan terkejut jika
lebih banyak pembelajaran dapat terjadi bahkan setelah zaman 400,
meskipun besarnya peningkatan lebih lanjut kemungkinan akan kecil. Jadi
mungkin untuk mengadopsi strategi yang kurang lebih agresif untuk
berhenti lebih awal. .

Mengapa menggunakan validation\_data untuk mencegah overfitting,
daripada test\_data ? Sebenarnya, ini adalah bagian dari strategi yang
lebih umum, yaitu menggunakan validation\_data untuk mengevaluasi
berbagai pilihan uji coba parameter-hiper seperti jumlah zaman untuk
dilatih, tingkat pembelajaran, arsitektur jaringan terbaik, dan
sebagainya. Kami menggunakan evaluasi tersebut untuk menemukan dan
menetapkan nilai yang baik untuk parameter-hiper. Memang, meskipun saya
belum menyebutkannya sampai sekarang, yaitu, sebagian, bagaimana saya
sampai pada pilihan hyper-parameter yang dibuat sebelumnya dalam buku
ini. (Lebih lanjut tentang ini
[nanti](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#how_to_choose_a_neural_network's_hyper-parameters)
.)

Tentu saja, itu sama sekali tidak menjawab pertanyaan mengapa kita
menggunakan validation\_data untuk mencegah overfitting, daripada
test\_data . Alih-alih, ini menggantikannya dengan pertanyaan yang lebih
umum, itulah mengapa kami menggunakan validation\_data daripada
test\_data untuk menetapkan parameter-hyper yang baik? Untuk memahami
alasannya, pertimbangkan bahwa ketika mengatur parameter-hiper kita
cenderung mencoba banyak pilihan berbeda untuk parameter-hiper. Jika
kita mengatur parameter-hiper berdasarkan evaluasi test\_data itu
mungkin kita akan berakhir overfitting parameter-hiper kita ke
test\_data . Yaitu, kita mungkin akhirnya menemukan hiper-parameter yang
sesuai dengan kekhasan test\_data , tetapi di mana kinerja jaringan
tidak akan menggeneralisasi ke set data lainnya. Kami mencegah hal itu
dengan mencari tahu parameter hiper menggunakan validation\_data . Lalu,
setelah kami mendapatkan parameter-hyper yang kami inginkan, kami
melakukan evaluasi akhir akurasi menggunakan test\_data . Itu memberi
kami keyakinan bahwa hasil kami pada test\_data adalah ukuran sebenarnya
dari seberapa baik jaringan saraf (*neural networks*) kami
menggeneralisasi. Dengan kata lain, Anda dapat menganggap data validasi
sebagai jenis data pelatihan yang membantu kami mempelajari
parameter-hiper yang baik. Pendekatan ini untuk menemukan
parameter-hiper yang baik kadang-kadang dikenal sebagai metode *tahan* ,
karena validation\_data dipisahkan atau " *ditangguhkan* " dari
training\_data .

Sekarang, dalam praktiknya, bahkan setelah mengevaluasi kinerja pada
test\_data kita dapat mengubah pikiran kita dan ingin mencoba pendekatan
lain - mungkin arsitektur jaringan yang berbeda - yang akan melibatkan
menemukan serangkaian parameter hiper baru. Jika kita melakukan ini,
bukankah ada bahaya kita akan berakhir pada test\_data juga? Apakah kita
memerlukan potensi kemunduran set data yang tak terbatas, sehingga kita
dapat yakin bahwa hasil kita akan digeneralisasi? Mengatasi masalah ini
sepenuhnya adalah masalah yang dalam dan sulit. Tetapi untuk tujuan
praktis kami, kami tidak akan terlalu khawatir tentang pertanyaan ini.
Sebagai gantinya, kami akan terjun ke depan, menggunakan metode dasar
tahan, berdasarkan pada training\_data , validation\_data , dan
test\_data , seperti dijelaskan di atas.

Kami telah melihat sejauh ini pada overfitting ketika kami hanya
menggunakan 1.000 gambar latihan. Apa yang terjadi ketika kita
menggunakan set pelatihan penuh 50.000 gambar? Kami akan menjaga semua
parameter lainnya tetap sama (30 neuron tersembunyi, kecepatan
pembelajaran 0,5, ukuran mini-batch 10), tetapi latih menggunakan semua
50.000 gambar selama 30 zaman. Berikut adalah grafik yang menunjukkan
hasil untuk akurasi klasifikasi pada data pelatihan dan data pengujian.
Perhatikan bahwa saya telah menggunakan data uji di sini, daripada data
validasi, untuk membuat hasilnya lebih langsung dibandingkan dengan
grafik sebelumnya.

![http://neuralnetworksanddeeplearning.com/images/overfitting\_full.png](media/image61.png)

Seperti yang Anda lihat, keakuratan pada tes dan data pelatihan tetap
lebih dekat bersama daripada saat kami menggunakan 1.000 contoh
pelatihan. Secara khusus, akurasi klasifikasi terbaik 97,86 persen pada
data pelatihan hanya 2,53 persen lebih tinggi dari 95,33 persen pada
data uji. Itu dibandingkan dengan kesenjangan 17,73 persen yang kami
miliki sebelumnya\! Overfitting masih terjadi, tetapi sudah sangat
berkurang. Jaringan kami menggeneralisasi jauh lebih baik dari data
pelatihan ke data uji. Secara umum, salah satu cara terbaik untuk
mengurangi overfitting adalah dengan menambah ukuran data pelatihan.
Dengan data pelatihan yang cukup, sulit bahkan untuk jaringan yang
sangat besar untuk berpakaian. Sayangnya, data pelatihan bisa mahal atau
sulit diperoleh, jadi ini tidak selalu merupakan pilihan praktis.

#### [Regularisasi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#regularization) 

Meningkatkan jumlah data pelatihan adalah salah satu cara untuk
mengurangi overfitting. Adakah cara lain kita bisa mengurangi sejauh
mana overfitting terjadi? Salah satu pendekatan yang mungkin adalah
mengurangi ukuran jaringan kami. Namun, jaringan besar memiliki potensi
untuk menjadi lebih kuat daripada jaringan kecil, jadi ini adalah
pilihan yang hanya kami adopsi dengan enggan.

Untungnya, ada teknik lain yang dapat mengurangi overfitting, bahkan
ketika kita memiliki jaringan tetap dan data pelatihan tetap. Ini
dikenal sebagai teknik *regularisasi* . Pada bagian ini saya menjelaskan
salah satu teknik regularisasi yang paling umum digunakan, teknik yang
kadang-kadang dikenal sebagai *pembusukan berat badan* atau
*regularisasi L2* . Gagasan regularisasi L2 adalah untuk menambahkan
istilah tambahan ke fungsi biaya, istilah yang disebut *istilah
regularisasi* . Inilah cross-entropy yang diatur:

\\ begin {eqnarray} C = - \\ frac {1} {n} \\ sum\_ {xj} \\ kiri \[y\_j
\\ ln a ^ L\_j + (1-y\_j) \\ ln (1-a ^ L\_j) \\ kanan\] + \\ frac {\\
lambda} {2n} \\ sum\_w w ^ 2. \\ tag {85} \\ end {eqnarray}

Istilah pertama hanyalah ungkapan biasa untuk lintas-entropi. Namun kami
menambahkan istilah kedua, yaitu jumlah kuadrat dari semua bobot dalam
jaringan. Ini diskalakan oleh faktor  lambda/2n, di mana  lambda\>0
dikenal sebagai *parameter regularisasi* , dan n adalah, seperti biasa,
ukuran set pelatihan kami. Saya akan membahas nanti bagaimana  lambda
dipilih. Perlu juga dicatat bahwa istilah regularisasi *tidak* termasuk
bias. Saya juga akan kembali ke yang di bawah ini.

Tentu saja, dimungkinkan untuk mengatur fungsi biaya lainnya, seperti
biaya kuadratik. Ini dapat dilakukan dengan cara yang serupa:

\\ begin {eqnarray} C = \\ frac {1} {2n} \\ sum\_x \\ | ya ^ L \\ | ^ 2
+ \\ frac {\\ lambda} {2n} \\ sum\_w w ^ 2. \\ tag {86} \\ end
{eqnarray}

Dalam kedua kasus tersebut kita dapat menuliskan fungsi biaya yang
diatur sebagai \\ begin {eqnarray} C = C\_0 + \\ frac {\\ lambda} {2n}
\\ sum\_w w ^ 2, \\ tag {87} \\ end {eqnarray} di mana C0 adalah fungsi
biaya asli, tidak diatur.

Secara intuitif, efek regularisasi adalah membuatnya sehingga jaringan
lebih memilih untuk belajar bobot kecil, semua hal lain dianggap sama.
Bobot besar hanya akan diizinkan jika mereka secara signifikan
meningkatkan bagian pertama dari fungsi biaya. Dengan kata lain,
regularisasi dapat dipandang sebagai cara kompromi antara menemukan
bobot kecil dan meminimalkan fungsi biaya asli. Kepentingan relatif dari
dua elemen kompromi tergantung pada nilai  lambda: ketika  lambda kecil
kita lebih suka meminimalkan fungsi biaya asli, tetapi ketika  lambda
besar kita lebih suka bobot kecil.

Sekarang, itu sama sekali tidak jelas mengapa membuat kompromi semacam
ini akan membantu mengurangi overfitting\! Tapi ternyata memang begitu.
Kami akan menjawab pertanyaan mengapa ini membantu di bagian
selanjutnya. Tapi pertama-tama, mari kita bekerja melalui contoh yang
menunjukkan bahwa regularisasi benar-benar mengurangi overfitting.

Untuk membangun contoh seperti itu, pertama-tama kita perlu mencari tahu
bagaimana menerapkan algoritma pembelajaran gradien keturunan stokastik
kami dalam jaringan saraf (*neural networks*) yang diatur. Secara
khusus, kita perlu tahu bagaimana menghitung derivatif parsial
 partialC/ partialw dan  partialC/ partialb untuk semua bobot dan bias
dalam jaringan. Mengambil sebagian turunan dari Persamaan (87) memberi

\\ begin {eqnarray} \\ frac {\\ partial C} {\\ partial w} & = & \\ frac
{\\ partial C\_0} {\\ partial w} + \\ frac {\\ lambda} {n} w \\ tag {88}
\\\\ \\ frac {\\ partial C} {\\ partial b} & = & \\ frac {\\ partial
C\_0} {\\ partial b}. \\ tag {89} \\ end {eqnarray}

Istilah  partialC0/ partialw dan  partialC0/ partialb dapat dihitung
dengan menggunakan backpropagation, seperti dijelaskan dalam [bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)
. Jadi kita melihat bahwa mudah untuk menghitung gradien dari fungsi
biaya yang diatur: cukup gunakan backpropagation, seperti biasa, dan
kemudian tambahkan  frac lambdanw ke turunan parsial dari semua
persyaratan bobot. Derivatif parsial sehubungan dengan bias tidak
berubah, sehingga aturan gradient descent learning untuk bias tidak
berubah dari aturan biasa:

\\ begin {eqnarray} b & \\ rightarrow & b - \\ eta \\ frac {\\ partial
C\_0} {\\ partial b}. \\ tag {90} \\ end {eqnarray}

Aturan pembelajaran untuk bobot menjadi:

\\ begin {eqnarray} w & \\ rightarrow & w- \\ eta \\ frac {\\ partial
C\_0} {\\ partial w} - \\ frac {\\ eta \\ lambda} {n} w \\ tag {91} \\\\
& = & \\ kiri (1- \\ frac {\\ eta \\ lambda} {n} \\ kanan) w - \\ eta \\
frac {\\ partial C\_0} {\\ partial w}. \\ tag {92} \\ end {eqnarray}

Ini persis sama dengan aturan pembelajaran gradient descent yang biasa,
kecuali kita pertama-tama menskala ulang bobot w dengan faktor
1− frac eta lambdan. Pengecilan ini kadang-kadang disebut sebagai
*pembusukan berat* , karena membuat bobot lebih kecil. Sepintas ini
terlihat seolah-olah ini berarti bobot didorong tanpa terhentikan menuju
nol. Tapi itu tidak benar, karena istilah lain dapat menyebabkan bobot
meningkat, jika hal itu menyebabkan penurunan fungsi biaya yang tidak
diatur.

Oke, begitulah cara kerja gradient descent. Bagaimana dengan penurunan
gradien stokastik? Seperti halnya dalam penurunan gradien stokastik yang
tidak diregulasi, kita dapat memperkirakan  partialC0/ partialw dengan
rata-rata lebih dari satu batch mini contohpelatihan m. Dengan demikian
aturan pembelajaran yang diatur untuk penurunan gradien stokastik
menjadi (cf Persamaan (20) )

\\ begin {eqnarray} w \\ rightarrow \\ left (1- \\ frac {\\ eta \\
lambda} {n} \\ kanan) w - \\ frac {\\ eta} {m} \\ sum\_x \\ frac {\\
partial C\_x} {\\ partial w}, \\ tag {93} \\ end {eqnarray}

di mana jumlahnya melebihi contoh pelatihan x dalam mini-batch, dan Cx
adalah biaya (tidak diatur) untuk setiap contoh pelatihan. Ini persis
sama dengan aturan biasa untuk penurunan gradien stokastik, kecuali
untuk 1− frac eta lambdan faktor peluruhan berat. Akhirnya, dan untuk
kelengkapannya, izinkan saya menyatakan aturan pembelajaran yang diatur
untuk bias. Ini, tentu saja, persis sama dengan dalam kasus yang tidak
diregulasi (lih Persamaan (21) ),

\\ begin {eqnarray} b \\ rightarrow b - \\ frac {\\ eta} {m} \\ sum\_x
\\ frac {\\ partial C\_x} {\\ partial b}, \\ tag {94} \\ end {eqnarray}
di mana penjumlahannya sudah lewat pelatihan contoh x dalam mini-batch.

Mari kita lihat bagaimana regularisasi mengubah kinerja *jaringan saraf
(neural networks)* kita. Kami akan menggunakan jaringan dengan 30 neuron
tersembunyi, ukuran mini-batch 10,tingkatpembelajaran 0,5 $, dan fungsi
biaya lintas-entropi. Namun, kali ini kami akan menggunakan parameter
regularisasi  lambda=0,1. Perhatikan bahwa dalam kode, kita menggunakan
nama variabel lmbda , karena lambda adalah kata yang disediakan dalam
Python, dengan makna yang tidak terkait. Saya juga menggunakan
test\_data lagi, bukan validation\_data . Sebenarnya, kita harus
menggunakan validation\_data , untuk semua alasan yang telah kita bahas
sebelumnya. Tapi saya memutuskan untuk menggunakan test\_data karena itu
membuat hasil lebih langsung dibandingkan dengan hasil kami sebelumnya,
yang tidak diatur. Anda dapat dengan mudah mengubah kode untuk
menggunakan validation\_data , dan Anda akan menemukan bahwa itu
memberikan hasil yang serupa.

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

\>\>\> jaringan impor2

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \], biaya = jaringan2
. CrossEntropyCost )

\>\>\> bersih . large\_weight\_initializer ()

\>\>\> bersih . SGD ( training\_data \[: 1000 \], 400 , 10 , 0,5 ,

... evaluation\_data = test\_data , lmbda = 0.1 ,

... monitor\_evaluation\_cost = Benar , monitor\_evaluation\_accuracy =
Benar ,

... monitor\_training\_cost = Benar , monitor\_training\_accuracy =
Benar )

Biaya data pelatihan berkurang sepanjang waktu, sama seperti yang
terjadi pada kasus sebelumnya, yang tidak diregulasi \* \* Ini dan dua
grafik berikutnya diproduksi dengan program
[overfitting.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/overfitting.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjC8_dUCFd-B9PYjKIJKcCYTVmqRQ)
. :

![http://neuralnetworksanddeeplearning.com/images/regularized1.png](media/image62.png)

Tapi kali ini akurasi pada test\_data terus meningkat untuk seluruh 400
zaman:

![http://neuralnetworksanddeeplearning.com/images/regularized2.png](media/image63.png)

Jelas, penggunaan regularisasi telah menekan overfitting. Terlebih lagi,
akurasinya jauh lebih tinggi, dengan akurasi klasifikasi puncak 87.1
persen, dibandingkan dengan puncak 82.27 persen diperoleh dalam kasus
yang tidak diregulasi. Memang, kami hampir pasti bisa mendapatkan hasil
yang jauh lebih baik dengan terus melatih 400 masa lalu. Tampaknya,
secara empiris, regularisasi menyebabkan jaringan kami menggeneralisasi
lebih baik, dan sangat mengurangi efek overfitting.

Apa yang terjadi jika kita keluar dari lingkungan buatan yang hanya
memiliki 1.000 gambar pelatihan, dan kembali ke set 50.000 gambar
pelatihan penuh? Tentu saja, kami telah melihat bahwa overfitting jauh
lebih sedikit dari masalah dengan 50.000 gambar penuh. Apakah
regularisasi membantu lebih jauh? Mari kita jaga hiper-parameter sama
seperti sebelumnya - 30 zaman, tingkat pembelajaran 0,5, ukuran
mini-batch 10. Namun, kita perlu memodifikasi parameter regularisasi.
Alasannya adalah karena ukuran n dari set pelatihan telah berubah dari
n=1.000 menjadi n=50.000, dan ini mengubah faktor pembusukan berat
1− frac eta lambdan. Jika kita terus menggunakan  lambda=0,1 itu
berarti penurunan berat badan yang jauh lebih sedikit, dan dengan
demikian jauh lebih sedikit dari efek regularisasi. Kami menggantinya
dengan mengubah ke  lambda=5.0.

Oke, mari latih jaringan kami, berhenti dulu untuk menginisialisasi
ulang bobot:

\>\>\> bersih . large\_weight\_initializer ()

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0,5 ,

... evaluation\_data = test\_data , lmbda = 5.0 ,

... monitor\_evaluation\_accuracy = Benar , monitor\_training\_accuracy
= Benar )

Kami memperoleh hasil:

![http://neuralnetworksanddeeplearning.com/images/regularized\_full.png](media/image64.png)

Ada banyak berita baik di sini. Pertama, akurasi klasifikasi kami pada
data uji naik, dari 95,49 persen ketika menjalankan tidak diatur,
menjadi 96,49 persen. Itu kemajuan besar. Kedua, kita dapat melihat
bahwa kesenjangan antara hasil pada pelatihan dan data uji jauh lebih
sempit dari sebelumnya, berjalan di bawah persen. Itu masih kesenjangan
yang signifikan, tetapi kami jelas telah membuat kemajuan besar
mengurangi overfitting.

Akhirnya, mari kita lihat apa akurasi klasifikasi klasifikasi yang kita
dapatkan ketika kita menggunakan 100 neuron tersembunyi dan parameter
regularisasi  lambda=5.0. Saya tidak akan melalui analisis terperinci
tentang overfitting di sini, ini murni untuk bersenang-senang, hanya
untuk melihat seberapa tinggi akurasi yang bisa kita dapatkan ketika
kita menggunakan trik baru kita: fungsi biaya lintas-entropi dan
regularisasi L2.

\>\>\> net = network2 . Jaringan (\[ 784 , 100 , 10 \], biaya =
jaringan2 . CrossEntropyCost )

\>\>\> bersih . large\_weight\_initializer ()

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0,5 , lmbda = 5.0 ,

... evaluation\_data = validation\_data ,

... monitor\_evaluation\_accuracy = Benar )

Hasil akhir adalah akurasi klasifikasi 97,92 persen pada data validasi.
Itu lompatan besar dari 30 kasus neuron tersembunyi. Bahkan, menyetel
sedikit lagi, untuk menjalankan selama 60 zaman di  eta=0,1 dan
 lambda=5,0 kami memecahkan penghalang 98 persen, mencapai akurasi
klasifikasi 98,04 persen pada data validasi. Tidak buruk untuk apa yang
ternyata menjadi 152 baris kode\!

Saya telah menggambarkan regularisasi sebagai cara untuk mengurangi
overfitting dan untuk meningkatkan akurasi klasifikasi. Padahal, itu
bukan satu-satunya manfaat. Secara empiris, ketika melakukan beberapa
kali menjalankan jaringan MNIST kami, tetapi dengan inisialisasi bobot
(acak) yang berbeda, saya telah menemukan bahwa proses yang tidak
teratur kadang-kadang akan "macet", tampaknya terperangkap dalam minimum
lokal fungsi biaya. Hasilnya adalah berbagai proses terkadang memberikan
hasil yang sangat berbeda. Sebaliknya, operasi yang diatur telah
memberikan hasil yang jauh lebih mudah ditiru.

Mengapa ini terjadi? Secara heuristik, jika fungsi biaya tidak diatur,
maka panjang vektor bobot kemungkinan akan bertambah, semua hal lain
dianggap sama. Seiring waktu, ini dapat menyebabkan vektor bobot menjadi
sangat besar. Ini dapat menyebabkan vektor bobot macet menunjuk ke arah
yang kurang lebih sama, karena perubahan karena gradient descent hanya
membuat perubahan kecil ke arah, ketika panjangnya panjang. Saya percaya
fenomena ini mempersulit algoritma pembelajaran kami untuk
mengeksplorasi ruang bobot dengan benar, dan akibatnya lebih sulit untuk
menemukan minimum yang baik dari fungsi biaya.

#### [Mengapa regularisasi membantu mengurangi overfitting?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#why_does_regularization_help_reduce_overfitting) 

Kami telah melihat secara empiris bahwa regularisasi membantu mengurangi
overfitting. Itu menggembirakan, tetapi, sayangnya, tidak jelas mengapa
regularisasi membantu\! Sebuah kisah standar yang diceritakan
orang-orang untuk menjelaskan apa yang terjadi ada di sepanjang baris
berikut: bobot yang lebih kecil, dalam beberapa hal, kompleksitas yang
lebih rendah, dan dengan demikian memberikan penjelasan yang lebih
sederhana dan lebih kuat untuk data, dan karenanya harus lebih disukai.
Namun, itu cerita yang sangat singkat, dan mengandung beberapa elemen
yang mungkin tampak meragukan atau membingungkan. Mari kita buka cerita
dan memeriksanya dengan kritis. Untuk melakukan itu, anggaplah kita
memiliki set data sederhana yang ingin kita bangun model:

Secara implisit, kami mempelajari beberapa fenomena dunia nyata di sini,
dengan x dan y mewakili data dunia nyata. Tujuan kami adalah untuk
membangun model yang memungkinkan kami memprediksi y sebagai fungsi dari
x. Kita dapat mencoba menggunakan jaringan saraf (*neural networks*)
untuk membangun model seperti itu, tetapi saya akan melakukan sesuatu
yang lebih sederhana: Saya akan mencoba memodelkan y sebagai polinomial
dalam x. Saya melakukan ini daripada menggunakan jaring saraf karena
menggunakan polinomial akan membuat hal-hal sangat transparan. Setelah
kami memahami kasus polinomial, kami akan menerjemahkannya ke jaringan
saraf. Sekarang, ada sepuluh poin dalam grafik di atas, yang berarti
kita dapat menemukan polinomial orde 9 unik y=a0x9+a1x8+ ldots+a9 yang
sesuai dengan data. Inilah grafik polinomial itu \* \* Saya tidak akan
menunjukkan koefisien secara eksplisit, meskipun mereka mudah ditemukan
menggunakan rutinitas seperti polyfit Numpy. Anda dapat melihat bentuk
persis polinomial dalam [kode sumber untuk
grafik](http://neuralnetworksanddeeplearning.com/js/polynomial_model.js)
jika Anda penasaran. Fungsi p (x) didefinisikan mulai pada baris 14 dari
program yang menghasilkan grafik. :

Itu memberikan kecocokan tepat. Tetapi kita juga bisa mendapatkan
kecocokan yang baik dengan menggunakan model linear y=2x:

Manakah dari ini adalah model yang lebih baik? Mana yang lebih mungkin
benar? Dan model mana yang lebih cenderung menggeneralisasi dengan baik
pada contoh-contoh lain dari fenomena dunia nyata yang mendasari yang
sama?

Ini pertanyaan sulit. Faktanya, kita tidak dapat menentukan dengan pasti
jawaban atas pertanyaan-pertanyaan di atas, tanpa lebih banyak informasi
tentang fenomena dunia nyata yang mendasarinya. Tetapi mari kita
pertimbangkan dua kemungkinan: (1) polinomial orde 9 sebenarnya adalah
model yang benar-benar menggambarkan fenomena dunia nyata, dan oleh
karena itu model tersebut akan menggeneralisasi dengan sempurna; (2)
model yang benar adalah y=2x, tetapi ada sedikit noise tambahan karena,
katakanlah, kesalahan pengukuran, dan itulah mengapa model tersebut
tidak sesuai.

Tidak mungkin untuk mengatakan mana dari dua kemungkinan ini yang benar.
(Atau, memang, jika ada kemungkinan ketiga berlaku). Logikanya, bisa
jadi benar. Dan itu bukan perbedaan sepele. Memang benar bahwa pada data
yang disediakan hanya ada perbedaan kecil antara kedua model. Tetapi
misalkan kita ingin memprediksi nilai y yang sesuai dengan beberapa
nilai besar x, jauh lebih besar daripada yang ditunjukkan pada grafik di
atas. Jika kita coba melakukan itu, akan ada perbedaan dramatis antara
prediksi kedua model, karena model polinomial pesanan 9 menjadi
didominasi oleh istilah x9, sementara model linier tetap, yah, linier .

Satu sudut pandang adalah mengatakan bahwa dalam sains kita harus pergi
dengan penjelasan yang lebih sederhana, kecuali dipaksa untuk tidak
melakukannya. Ketika kami menemukan model sederhana yang tampaknya
menjelaskan banyak poin data, kami tergoda untuk berteriak "Eureka\!"
Bagaimanapun, tampaknya tidak mungkin bahwa penjelasan sederhana harus
terjadi hanya karena kebetulan. Sebaliknya, kami menduga bahwa model
tersebut harus mengungkapkan beberapa kebenaran mendasar tentang
fenomena tersebut. Dalam kasus yang dihadapi, model y=2x+ rmnoise
tampaknya jauh lebih sederhana daripada y=a0x9+a1x8+ ldots. Akan
mengejutkan jika kesederhanaan itu terjadi secara kebetulan, dan kami
menduga bahwa y=2x+ rmnoise mengungkapkan beberapa kebenaran mendasar.
Dalam sudut pandang ini, model urutan 9 benar-benar hanya mempelajari
efek kebisingan lokal. Dan sementara model urutan ke-9 bekerja dengan
sempurna untuk titik-titik data khusus ini, model tersebut akan gagal
untuk menggeneralisasi ke titik-titik data lainnya, dan model linier
berisik akan memiliki daya prediksi yang lebih besar.

Mari kita lihat apa arti sudut pandang ini untuk jaringan saraf.
Misalkan jaringan kita sebagian besar memiliki bobot kecil, karena akan
cenderung terjadi dalam jaringan yang diatur. Kecilnya bobot berarti
bahwa perilaku jaringan tidak akan banyak berubah jika kita mengubah
beberapa input acak di sana-sini. Itu menyulitkan jaringan yang
teregulasi untuk mempelajari efek noise lokal dalam data. Anggap saja
sebagai cara untuk membuatnya sehingga bukti tunggal tidak terlalu
penting bagi hasil dari jaringan. Alih-alih, jaringan yang diatur
belajar untuk menanggapi jenis bukti yang sering terlihat di seluruh
rangkaian pelatihan. Sebaliknya, jaringan dengan bobot besar dapat
mengubah perilakunya sedikit dalam menanggapi perubahan kecil pada
input. Jadi jaringan yang tidak diregulasi dapat menggunakan bobot besar
untuk mempelajari model kompleks yang membawa banyak informasi tentang
kebisingan dalam data pelatihan. Singkatnya, jaringan yang diregulasi
dibatasi untuk membangun model yang relatif sederhana berdasarkan pola
yang sering terlihat dalam data pelatihan, dan tahan terhadap kekhasan
pembelajaran kebisingan dalam data pelatihan. Harapannya adalah ini akan
memaksa jaringan kami untuk melakukan pembelajaran nyata tentang
fenomena yang ada, dan untuk menggeneralisasi lebih baik dari apa yang
mereka pelajari.

Dengan mengatakan itu, gagasan memilih penjelasan yang lebih sederhana
ini akan membuat Anda gugup. Orang-orang kadang-kadang menyebut gagasan
ini sebagai "Pisau Cukur Occam", dan akan dengan bersemangat
menerapkannya seolah-olah memiliki status beberapa prinsip ilmiah umum.
Tapi, tentu saja, itu bukan prinsip ilmiah umum. Tidak ada alasan logis
*apriori* untuk lebih memilih penjelasan sederhana daripada penjelasan
yang lebih kompleks. Memang, terkadang penjelasan yang lebih kompleks
ternyata benar.

Izinkan saya menjelaskan dua contoh di mana penjelasan yang lebih
kompleks ternyata benar. Pada 1940-an, fisikawan Marcel Schein
mengumumkan penemuan partikel alam baru. Perusahaan tempat dia bekerja,
General Electric, sangat gembira, dan mempublikasikan penemuan itu
secara luas. Tetapi fisikawan Hans Bethe skeptis. Bethe mengunjungi
Schein, dan melihat lempengan-lempengan yang menunjukkan jejak partikel
baru Schein. Schein menunjukkan pelat Bethe setelah pelat, tetapi pada
setiap pelat Bethe mengidentifikasi beberapa masalah yang menyarankan
data harus dibuang. Akhirnya, Schein menunjukkan kepada Bethe sebuah
piring yang terlihat bagus. Bethe mengatakan itu mungkin hanya kebetulan
statistik. Schein: "Ya, tetapi kemungkinan ini adalah statistik, bahkan
menurut formula Anda sendiri, adalah satu dari lima." Bethe: "Tapi kita
sudah melihat lima piring." Akhirnya, Schein berkata: "Tetapi di piring
saya, masing-masing dari piring yang baik, masing-masing dari gambar
yang baik, Anda menjelaskan dengan teori yang berbeda, sedangkan saya
memiliki satu hipotesis yang menjelaskan semua lempeng, bahwa mereka
adalah \[partikel baru \]. " Bethe menjawab: "Satu-satunya perbedaan
antara penjelasan Anda dan saya adalah bahwa Anda salah dan semua milik
saya benar. Penjelasan tunggal Anda salah, dan semua banyak penjelasan
saya benar." Pekerjaan selanjutnya mengkonfirmasi bahwa Nature setuju
dengan Bethe, dan partikel Schein tidak ada lagi \* \* Kisah ini
diceritakan oleh fisikawan Richard Feynman dalam sebuah
[wawancara](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.aip.org/history-programs/niels-bohr-library/oral-histories/5020-4&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgqso8X0TlIjn7Aqm-WeHL8jSN3fQ)
dengan sejarawan Charles Weiner. .

Sebagai contoh kedua, pada 1859 astronom Urbain Le Verrier mengamati
bahwa orbit planet Merkurius tidak memiliki bentuk yang seharusnya
dimiliki oleh teori gravitasi Newton. Itu adalah penyimpangan kecil dari
teori Newton, dan beberapa penjelasan yang dikemukakan saat itu bermula
untuk mengatakan bahwa teori Newton kurang lebih benar, tetapi
membutuhkan perubahan kecil. Pada tahun 1916, Einstein menunjukkan bahwa
penyimpangan dapat dijelaskan dengan sangat baik menggunakan teori
relativitas umumnya, teori yang sangat berbeda dengan gravitasi Newton,
dan didasarkan pada matematika yang jauh lebih kompleks. Terlepas dari
kerumitan tambahan itu, hari ini diterima bahwa penjelasan Einstein
benar, dan gravitasi Newton, bahkan dalam bentuknya yang dimodifikasi,
adalah salah. Ini sebagian karena kita sekarang tahu bahwa teori
Einstein menjelaskan banyak fenomena lain yang sulit dihadapi oleh teori
Newton. Lebih jauh lagi, dan bahkan lebih mengesankan, teori Einstein
secara akurat memprediksi beberapa fenomena yang sama sekali tidak
diprediksi oleh gravitasi Newton. Tetapi kualitas-kualitas yang
mengesankan ini tidak sepenuhnya jelas pada masa-masa awal. Jika
seseorang menilai hanya dengan alasan kesederhanaan, maka beberapa
bentuk modifikasi dari teori Newton akan lebih menarik.

Ada tiga moral yang bisa ditarik dari kisah-kisah ini. Pertama, itu bisa
menjadi bisnis yang sangat halus memutuskan mana dari dua penjelasan
yang benar-benar "sederhana". Kedua, bahkan jika kita dapat membuat
penilaian seperti itu, kesederhanaan adalah panduan yang harus digunakan
dengan sangat hati-hati\! Ketiga, tes sejati suatu model bukanlah
kesederhanaan, melainkan seberapa baik itu dalam memprediksi fenomena
baru, dalam rezim perilaku baru.

Dengan mengatakan itu, dan mengingat perlunya kehati-hatian, itu adalah
fakta empiris bahwa jaringan saraf (*neural networks*) yang terregulasi
biasanya menggeneralisasi lebih baik daripada jaringan yang tidak
diatur. Dan melalui sisa buku ini kita akan sering menggunakan
regularisasi. Saya telah memasukkan kisah-kisah di atas hanya untuk
membantu menyampaikan mengapa belum ada yang mengembangkan penjelasan
teoretis yang sepenuhnya meyakinkan mengapa regularisasi membantu
jaringan menggeneralisasi. Memang, para peneliti terus menulis makalah
di mana mereka mencoba pendekatan yang berbeda untuk regularisasi,
membandingkannya untuk melihat mana yang lebih baik, dan berusaha untuk
memahami mengapa pendekatan yang berbeda bekerja lebih baik atau lebih
buruk. Jadi Anda dapat melihat regularisasi sebagai sesuatu yang kludge.
Meskipun sering membantu, kita tidak memiliki pemahaman sistematis
sepenuhnya memuaskan tentang apa yang terjadi, hanya heuristik tidak
lengkap dan aturan praktis.

Ada serangkaian masalah yang lebih dalam di sini, masalah yang masuk ke
jantung ilmu pengetahuan. Ini pertanyaan tentang bagaimana kita
menggeneralisasi. Regularisasi mungkin memberi kita tongkat ajaib
komputasi yang membantu jaringan kita menggeneralisasi lebih baik,
tetapi itu tidak memberi kita pemahaman prinsip tentang bagaimana
generalisasi bekerja, atau tentang apa pendekatan terbaiknya \*
Masalah-masalah ini kembali ke [masalah
induksi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Problem_of_induction&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjiIi57wYXcCHb33RTpxTFyXfi4kQ)
, terkenal dibahas oleh filsuf Skotlandia David Hume dalam ["An Enquiry
Concerning Human
Understanding"](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.gutenberg.org/ebooks/9662&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiThI0fZMvondYIlUXyjPNgBub26Q)
(1748). Masalah induksi telah diberikan bentuk pembelajaran mesin modern
dalam teorema makan siang tanpa-bebas dari David Wolpert dan William
Macready (1997). .

Ini sangat menyakitkan karena dalam kehidupan sehari-hari, kita manusia
menggeneralisasi dengan sangat baik. Ditampilkan hanya beberapa gambar
gajah, anak-anak akan dengan cepat belajar mengenali gajah lain. Tentu
saja, mereka kadang-kadang membuat kesalahan, mungkin membingungkan
badak untuk gajah, tetapi secara umum proses ini bekerja sangat akurat.
Jadi kami memiliki sistem - otak manusia - dengan sejumlah besar
parameter gratis. Dan setelah ditunjukkan hanya satu atau beberapa
gambar pelatihan yang dipelajari sistem untuk digeneralisasi ke gambar
lain. Our brains are, in some sense, regularizing amazingly well\!
Bagaimana kita melakukannya? At this point we don't know. I expect that
in years to come we will develop more powerful techniques for
regularization in artificial neural networks, techniques that will
ultimately enable neural nets to generalize well even from small data
sets.

Faktanya, jaringan kami sudah menggeneralisasi lebih baik daripada yang
diperkirakan *apriori* . Jaringan dengan 100 neuron tersembunyi memiliki
hampir 80.000 parameter. Kami hanya memiliki 50.000 gambar dalam data
pelatihan kami. Ini seperti mencoba menyesuaikan polinomial tingkat
80.000 dengan 50.000 titik data. Dengan semua hak, jaringan kami harus
sangat berpakaian. Namun, seperti yang kita lihat sebelumnya, jaringan
semacam itu sebenarnya melakukan generalisasi yang cukup baik. Kenapa
begitu? Itu tidak dipahami dengan baik. Itu telah terkira \* \* Dalam
[Pembelajaran Berbasis Gradien Diterapkan pada Pengakuan
Dokumen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/publis/pdf/lecun-01a.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgeMAlGEsJ2YXxEpmu4XiD_6CCESA)
, oleh Yann LeCun, Léon Bottou, Yoshua Bengio, dan Patrick Haffner
(1998). bahwa "dinamika pembelajaran gradient descent pada jaring
multilayer memiliki efek\` self-regularisasi '". Ini sangat beruntung,
tetapi juga agak membingungkan karena kami tidak mengerti mengapa itu
terjadi. Sementara itu, kami akan mengadopsi pendekatan pragmatis dan
menggunakan regularisasi kapan pun kami bisa. *Jaringan saraf (neural
networks)* kita akan menjadi lebih baik untuk itu.

Biarkan saya menyimpulkan bagian ini dengan kembali ke detail yang saya
tinggalkan tidak dijelaskan sebelumnya: fakta bahwa regularisasi L2
*tidak* membatasi bias. Tentu saja, akan mudah untuk memodifikasi
prosedur regularisasi untuk mengatur bias. Secara empiris, melakukan hal
ini seringkali tidak banyak mengubah hasil, jadi sampai batas tertentu
itu hanya sebuah konvensi apakah akan mengatur bias atau tidak. Namun,
perlu dicatat bahwa memiliki bias yang besar tidak membuat neuron
sensitif terhadap inputnya dengan cara yang sama seperti memiliki bobot
yang besar. Dan jadi kita tidak perlu khawatir tentang bias besar yang
memungkinkan jaringan kita untuk mempelajari kebisingan dalam data
pelatihan kita. Pada saat yang sama, memungkinkan bias besar memberi
jaringan kami lebih banyak fleksibilitas dalam perilaku - khususnya,
bias besar memudahkan neuron untuk jenuh, yang kadang-kadang diinginkan.
Untuk alasan ini, kami biasanya tidak memasukkan istilah bias saat
mengatur.

#### [Teknik lain untuk regularisasi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques_for_regularization) 

Ada banyak teknik regularisasi selain L2 regularisasi. Faktanya, begitu
banyak teknik telah dikembangkan sehingga saya tidak mungkin merangkum
semuanya. Pada bagian ini saya menjelaskan secara singkat tiga
pendekatan lain untuk mengurangi overfitting: regularisasi L1, dropout,
dan secara artifisial meningkatkan ukuran set pelatihan. Kami tidak akan
mempelajari teknik-teknik ini sedekat yang kami lakukan sebelumnya.
Sebaliknya, tujuannya adalah untuk membiasakan diri dengan ide-ide
utama, dan untuk menghargai sesuatu dari keragaman teknik regularisasi
yang tersedia.

**Regulator L1:** Dalam pendekatan ini kami memodifikasi fungsi biaya
yang tidak diatur dengan menambahkan jumlah nilai absolut dari bobot:

\\ begin {eqnarray} C = C\_0 + \\ frac {\\ lambda} {n} \\ sum\_w | w |.
\\ tag {95} \\ end {eqnarray}

Secara intuitif, ini mirip dengan regularisasi L2, menghukum bobot
besar, dan cenderung membuat jaringan lebih memilih bobot kecil. Tentu
saja, istilah regularisasi L1 tidak sama dengan istilah regularisasi L2,
jadi kita seharusnya tidak berharap untuk mendapatkan perilaku yang
persis sama. Mari kita coba memahami bagaimana perilaku jaringan yang
dilatih menggunakan regularisasi L1 berbeda dari jaringan yang dilatih
menggunakan regularisasi L2.

Untuk melakukan itu, kita akan melihat turunan parsial dari fungsi
biaya. Membedakan (95) kami memperoleh: \\ begin {eqnarray} \\ frac {\\
partial C} {\\ partial w} = \\ frac {\\ partial C\_0} {\\ partial w} +
\\ frac {\\ lambda} {n} \\, {\\ rm sgn} (w) , \\ tag {96} \\ end
{eqnarray}

di mana  rmsgn(w) adalah tanda w, yaitu, +1 jika w positif, dan −1 jika
w negatif. Dengan menggunakan ungkapan ini, kita dapat dengan mudah
memodifikasi backpropagation untuk melakukan penurunan gradien stokastik
menggunakan regularisasi L1. Aturan pembaruan yang dihasilkan untuk
jaringan yang diatur L1 adalah \\ begin {eqnarray} w \\ rightarrow w '=
w- \\ frac {\\ eta \\ lambda} {n} \\ mbox {sgn} (w) - \\ eta \\ frac {\\
partial C\_0} {\\ partial w}, \\ tag {97} \\ end {eqnarray}

di mana, seperti biasa, kita dapat memperkirakan  partialC0/ partialw
menggunakan rata-rata mini-batch, jika kita mau. Bandingkan dengan
aturan pembaruan untuk regularisasi L2 (cf Persamaan (93) ), \\ begin
{eqnarray} w \\ rightarrow w '= w \\ left (1 - \\ frac {\\ eta \\
lambda} {n} \\ kanan) - \\ eta \\ frac {\\ partial C\_0} {\\ partial w}.
\\ tag {98} \\ end {eqnarray} Dalam kedua ungkapan ini efek dari
regularisasi adalah untuk mengecilkan bobot. Ini sesuai dengan intuisi
kita bahwa kedua jenis regularisasi menghukum bobot yang besar. Tetapi
cara bobot menyusut berbeda. Dalam regularisasi L1, bobot menyusut
dengan jumlah konstan menuju 0. Dalam regularisasi L2, bobot menyusut
dengan jumlah yang sebanding dengan w. Jadi ketika bobot tertentu
memiliki magnitudo besar, |w|, regularisasi L1 menyusut beratnya jauh
lebih sedikit daripada regularisasi L2. Sebaliknya, ketika |w| kecil,
regularisasi L1 menyusut bobot jauh lebih banyak daripada regularisasi
L2. Hasil akhirnya adalah bahwa regularisasi L1 cenderung memusatkan
bobot jaringan dalam sejumlah kecil koneksi dengan kepentingan tinggi,
sementara bobot lainnya didorong ke nol.

Saya telah membahas masalah dalam diskusi di atas, yaitu turunan parsial
 partialC/ partialw tidak ditentukan saat w=0. Alasannya adalah bahwa
fungsi |w| memiliki "sudut" yang tajam pada w=0, sehingga tidak dapat
dibedakan pada saat itu. Tapi tidak apa-apa. Apa yang akan kita lakukan
hanyalah menerapkan aturan biasa (tidak diatur) untuk penurunan gradien
stokastik ketika w=0. Itu seharusnya baik-baik saja - secara intuitif,
efek regularisasi adalah untuk mengecilkan bobot, dan jelas itu tidak
dapat mengecilkan bobot yang sudah 0. Untuk membuatnya lebih tepat, kita
akan menggunakan Persamaan (96) dan (97) dengan konvensi bahwa
 mboxsgn(0)=0. Itu memberikan aturan yang bagus dan ringkas untuk
melakukan penurunan gradien stokastik dengan regularisasi L1.

**Dropout:** Dropout adalah teknik yang sangat berbeda untuk
regularisasi. Tidak seperti regularisasi L1 dan L2, dropout tidak
bergantung pada modifikasi fungsi biaya. Sebagai gantinya, dalam dropout
kami memodifikasi jaringan itu sendiri. Izinkan saya menjelaskan
mekanika dasar tentang cara kerja dropout, sebelum membahas mengapa itu
berhasil, dan apa hasilnya.

Misalkan kita mencoba untuk melatih jaringan:

![http://neuralnetworksanddeeplearning.com/images/tikz30.png](media/image65.png)

Secara khusus, misalkan kita memiliki input pelatihan x dan output yang
diinginkan sesuai y. Biasanya, kami akan berlatih dengan memajukan ke
depan x melalui jaringan, dan kemudian melakukan backpropagating untuk
menentukan kontribusi pada gradien. Dengan putus sekolah, proses ini
dimodifikasi. Kita mulai dengan secara acak (dan sementara) menghapus
setengah dari neuron yang tersembunyi dalam jaringan, sambil membiarkan
neuron input dan output tidak tersentuh. Setelah melakukan ini, kita
akan berakhir dengan jaringan di sepanjang baris berikut. Perhatikan
bahwa neuron yang putus, yaitu neuron yang telah dihapus sementara,
masih dibenci oleh:

![http://neuralnetworksanddeeplearning.com/images/tikz31.png](media/image66.png)

Kami meneruskan propagasi input x melalui jaringan yang dimodifikasi,
dan kemudian mempropagandakan hasilnya, juga melalui jaringan yang
dimodifikasi. Setelah melakukan ini melalui sejumlah kecil contoh, kami
memperbarui bobot dan bias yang sesuai. Kami kemudian mengulangi
prosesnya, pertama mengembalikan neuron putus, kemudian memilih subset
acak baru dari neuron tersembunyi untuk dihapus, memperkirakan gradien
untuk batch-mini yang berbeda, dan memperbarui bobot dan bias dalam
jaringan.

Dengan mengulangi proses ini berulang-ulang, jaringan kami akan
mempelajari serangkaian bobot dan bias. Tentu saja, bobot dan bias itu
akan dipelajari di bawah kondisi di mana setengah neuron yang
tersembunyi dikeluarkan. Ketika kita benar-benar menjalankan jaringan
penuh itu berarti neuron tersembunyi dua kali lebih banyak akan aktif.
Untuk mengimbangi itu, kami membagi dua bobot keluar dari neuron
tersembunyi.

Prosedur putus sekolah ini mungkin aneh dan *ad hoc* . Mengapa kita
mengharapkannya membantu dengan regularisasi? Untuk menjelaskan apa yang
terjadi, saya ingin Anda berhenti sejenak berpikir tentang putus
sekolah, dan alih-alih bayangkan melatih *jaringan saraf (neural
networks)* dengan cara standar (tidak putus sekolah). Secara khusus,
bayangkan kita melatih beberapa jaringan saraf (*neural networks*) yang
berbeda, semua menggunakan data pelatihan yang sama. Tentu saja,
jaringan mungkin tidak mulai identik, dan sebagai hasilnya setelah
pelatihan mereka kadang-kadang dapat memberikan hasil yang berbeda.
Ketika itu terjadi, kita dapat menggunakan semacam skema rata-rata atau
pemungutan suara untuk memutuskan output mana yang akan diterima.
Sebagai contoh, jika kita telah melatih lima jaringan, dan tiga dari
mereka mengklasifikasikan digit sebagai "3", maka itu mungkin
benar-benar adalah "3". Dua jaringan lainnya mungkin hanya membuat
kesalahan. Skema rata-rata semacam ini sering ditemukan sebagai cara
yang kuat (meskipun mahal) untuk mengurangi overfitting. Alasannya
adalah bahwa jaringan yang berbeda mungkin mengenakan pakaian dengan
cara yang berbeda, dan rata-rata dapat membantu menghilangkan
overfitting semacam itu.

Apa hubungannya dengan putus sekolah? Secara heuristik, ketika kita
menjatuhkan set neuron yang berbeda, itu seperti kita melatih *jaringan
saraf (neural networks)* yang berbeda. Jadi, prosedur putus sekolah
seperti rata-rata efek dari sejumlah besar jaringan yang berbeda.
Jaringan yang berbeda akan mengenakan pakaian dengan cara yang berbeda,
dan, semoga saja, efek bersih dari putus sekolah adalah mengurangi
overfitting.

Penjelasan heuristik terkait untuk putus sekolah diberikan di salah satu
makalah paling awal untuk menggunakan teknik \* \* [Klasifikasi ImageNet
dengan Deep Nevolute Neural
Networks](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgMwoOHNTxxSW4n_THXCOcFaU4ULw)
, oleh Alex Krizhevsky, Ilya Sutskever, dan Geoffrey Hinton (2012). :
"Teknik ini mengurangi co-adaptasi kompleks neuron, karena neuron tidak
dapat bergantung pada keberadaan neuron tertentu lainnya. Oleh karena
itu, dipaksa untuk mempelajari fitur yang lebih kuat yang berguna dalam
hubungannya dengan banyak subset acak berbeda dari neuron lain. . "
Dengan kata lain, jika kita menganggap jaringan kita sebagai model yang
membuat prediksi, maka kita dapat menganggap putus sekolah sebagai cara
untuk memastikan bahwa model tersebut kuat terhadap hilangnya setiap
bukti. Dalam hal ini, ini agak mirip dengan regularisasi L1 dan L2, yang
cenderung mengurangi bobot, dan dengan demikian membuat jaringan lebih
kuat untuk kehilangan koneksi individu dalam jaringan.

Tentu saja, ukuran sebenarnya dari dropout adalah telah sangat berhasil
dalam meningkatkan kinerja jaringan saraf. Kertas asli \* \*
[Meningkatkan jaringan saraf (*neural networks*) dengan mencegah
co-adaptasi fitur
detektor](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://arxiv.org/pdf/1207.0580.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhWeDa7_7_pclOBNARpeVImGeQEQA)
oleh Geoffrey Hinton, Nitish Srivastava, Alex Krizhevsky, Ilya
Sutskever, dan Ruslan Salakhutdinov (2012). Perhatikan bahwa makalah ini
membahas sejumlah seluk-beluk yang telah saya bahas dalam pengantar
singkat ini. memperkenalkan teknik yang diterapkan pada banyak tugas
berbeda. Bagi kami, sangat menarik bahwa mereka menerapkan dropout ke
klasifikasi angka MNIST, menggunakan jaringan saraf (*neural networks*)
vanilla feedforward sepanjang garis yang serupa dengan yang telah kami
pertimbangkan. Makalah ini mencatat bahwa hasil terbaik yang dicapai
siapa pun hingga saat itu menggunakan arsitektur seperti itu adalah 98,4
akurasi klasifikasi persen pada set tes. Mereka meningkatkan keakuratan
98,7 persen menggunakan kombinasi putus sekolah dan bentuk modifikasi
dari L2 regularisasi. Demikian pula hasil yang mengesankan telah
diperoleh untuk banyak tugas lain, termasuk masalah dalam pengenalan
gambar dan ucapan, dan pemrosesan bahasa alami. Putus sekolah sangat
bermanfaat dalam melatih jaringan yang besar dan dalam, di mana masalah
overfitting seringkali akut.

Perluasan **data pelatihan secara artifisial:** Kami telah melihat
sebelumnya bahwa keakuratan klasifikasi MNIST kami turun hingga
persentase pada pertengahan 80-an ketika kami hanya menggunakan 1.000
gambar pelatihan. Tidak mengherankan jika ini masalahnya, karena data
pelatihan yang lebih sedikit berarti jaringan kita akan lebih sedikit
terkena variasi dalam cara manusia menulis angka. Mari kita coba melatih
30 jaringan neuron tersembunyi kami dengan berbagai ukuran data
pelatihan yang berbeda, untuk melihat bagaimana kinerja bervariasi. Kami
berlatih menggunakan ukuran mini-batch 10, tingkat pembelajaran
 eta=0,5, parameter regularisasi  lambda=5.0, dan fungsi biaya
lintas-entropi. Kami akan melatih selama 30 zaman ketika set data
pelatihan lengkap digunakan, dan meningkatkan jumlah zaman secara
proporsional ketika set pelatihan yang lebih kecil digunakan. Untuk
memastikan faktor pembusukan berat tetap sama di seluruh set pelatihan,
kami akan menggunakan parameter regularisasi  lambda=5.0 ketika set data
pelatihan lengkap digunakan, dan menurunkan  lambda secara proporsional
ketika set pelatihan yang lebih kecil digunakan \* \* Ini dan dua grafik
berikutnya diproduksi dengan program
[more\_data.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/more_data.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhwO1DgFWxPK0gp_aW4-qoMdgiIHQ)
. .

![http://neuralnetworksanddeeplearning.com/images/more\_data.png](media/image67.png)

Seperti yang Anda lihat, akurasi klasifikasi meningkat secara signifikan
karena kami menggunakan lebih banyak data pelatihan. Agaknya peningkatan
ini akan berlanjut lebih jauh jika lebih banyak data tersedia. Tentu
saja, melihat grafik di atas memang terlihat bahwa kita sudah hampir
jenuh. Namun, anggaplah kita mengulang grafik dengan ukuran set
pelatihan yang diplot secara logaritma:

![http://neuralnetworksanddeeplearning.com/images/more\_data\_log.png](media/image68.png)

Tampak jelas bahwa grafik masih naik menjelang akhir. Ini menunjukkan
bahwa jika kita menggunakan lebih banyak data pelatihan - katakanlah,
jutaan atau bahkan miliaran sampel tulisan tangan, bukan hanya 50.000 -
maka kita mungkin akan mendapatkan kinerja yang jauh lebih baik, bahkan
dari jaringan yang sangat kecil ini.

Memperoleh lebih banyak data pelatihan adalah ide bagus. Sayangnya, itu
bisa mahal, dan karena itu tidak selalu memungkinkan dalam praktik.
Namun, ada ide lain yang dapat bekerja hampir juga, dan itu adalah untuk
secara artifisial memperluas data pelatihan. Misalkan, misalnya, bahwa
kita mengambil gambar pelatihan MNIST dari lima,

![http://neuralnetworksanddeeplearning.com/images/more\_data\_5.png](media/image69.png)

dan putar dengan jumlah kecil, misalkan 15 derajat:

![http://neuralnetworksanddeeplearning.com/images/more\_data\_rotated\_5.png](media/image70.png)

Angka itu masih bisa dikenali sama. Namun pada tingkat piksel sangat
berbeda dengan gambar apa pun yang saat ini ada dalam data pelatihan
MNIST. Bisa dibayangkan bahwa menambahkan gambar ini ke data pelatihan
dapat membantu jaringan kami mempelajari lebih lanjut tentang cara
mengklasifikasikan digit. Terlebih lagi, jelas kami tidak terbatas hanya
menambahkan gambar yang satu ini. Kami dapat memperluas data pelatihan
kami dengan membuat *banyak* rotasi kecil dari *semua* gambar pelatihan
MNIST, dan kemudian menggunakan data pelatihan yang diperluas untuk
meningkatkan kinerja jaringan kami.

Ide ini sangat kuat dan telah banyak digunakan. Mari kita lihat beberapa
hasil dari makalah \* \* [Praktik Terbaik untuk *Jaringan saraf (neural
networks)* (neural networks)Konvolusional yang Diterapkan pada Analisis
Dokumen
Visual](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://dx.doi.org/10.1109/ICDAR.2003.1227801&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiooJioOnuXJpBF8GklOZQW5jxw0g)
, oleh Patrice Simard, Dave Steinkraus, dan John Platt (2003). yang
menerapkan beberapa variasi ide ke MNIST. Salah satu arsitektur
jaringan saraf (*neural networks*) yang mereka anggap sejalan dengan apa
yang telah kami gunakan, jaringan feedforward dengan 800 neuron
tersembunyi dan menggunakan fungsi biaya lintas-entropi. Menjalankan
jaringan dengan data pelatihan MNIST standar, mereka mencapai akurasi
klasifikasi 98,4 persen pada set tes mereka. Tapi kemudian mereka
memperluas data pelatihan, tidak hanya menggunakan rotasi, seperti yang
saya jelaskan di atas, tetapi juga menerjemahkan dan mengubah gambar.
Dengan melatih set data yang diperluas, mereka meningkatkan akurasi
jaringan mereka menjadi 98,9 persen. Mereka juga bereksperimen dengan
apa yang mereka sebut "distorsi elastis", jenis distorsi gambar khusus
yang dimaksudkan untuk meniru osilasi acak yang ditemukan pada otot-otot
tangan. Dengan menggunakan distorsi elastis untuk memperluas data mereka
mencapai akurasi yang lebih tinggi, 99,3 persen. Secara efektif, mereka
memperluas pengalaman jaringan mereka dengan memaparkannya pada jenis
variasi yang ditemukan dalam tulisan tangan nyata.

Variasi pada ide ini dapat digunakan untuk meningkatkan kinerja pada
banyak tugas belajar, tidak hanya pengenalan tulisan tangan. Prinsip
umum adalah memperluas data pelatihan dengan menerapkan operasi yang
mencerminkan variasi dunia nyata. Tidak sulit memikirkan cara untuk
melakukan ini. Misalkan, misalnya, Anda sedang membangun *jaringan saraf
(neural networks)* untuk melakukan pengenalan ucapan. Kita manusia dapat
mengenali pembicaraan bahkan di hadapan distorsi seperti kebisingan
latar belakang. Sehingga Anda dapat memperluas data Anda dengan
menambahkan kebisingan latar belakang. Kita juga bisa mengenali ucapan
jika dipercepat atau diperlambat. Jadi itu cara lain kita dapat
memperluas data pelatihan. Teknik-teknik ini tidak selalu digunakan -
misalnya, alih-alih memperluas data pelatihan dengan menambahkan
kebisingan, mungkin lebih efisien untuk membersihkan input ke jaringan
dengan terlebih dahulu menerapkan filter pengurangan kebisingan. Tetap
saja, ada baiknya mengingat ide untuk memperluas data pelatihan, dan
mencari peluang untuk menerapkannya.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_195778) 

  - Seperti dibahas di atas, salah satu cara memperluas data pelatihan
    MNIST adalah dengan menggunakan rotasi kecil gambar pelatihan. Apa
    masalah yang mungkin terjadi jika kita mengizinkan rotasi besar dari
    gambar pelatihan?

**Selain data besar dan apa artinya membandingkan akurasi klasifikasi:**
Mari kita lihat lagi bagaimana akurasi *jaringan saraf (neural
networks)* kita berbeda dengan ukuran set pelatihan:

![http://neuralnetworksanddeeplearning.com/images/more\_data\_log.png](media/image68.png)

Misalkan alih-alih menggunakan jaringan saraf (*neural networks*) kita
menggunakan beberapa teknik pembelajaran mesin lainnya untuk
mengklasifikasikan angka. Sebagai contoh, mari kita coba menggunakan
mesin vektor dukungan (SVM) yang kita temui secara singkat di
[Bab 1](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#SVM)
. Seperti halnya pada Bab 1, jangan khawatir jika Anda tidak terbiasa
dengan SVM, kami tidak perlu memahami detailnya. Sebagai gantinya, kami
akan menggunakan SVM yang disediakan oleh [pustaka
scikit-learn](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://scikit-learn.org/stable/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiCSA54_2L6tWtexMwP0MyXVEGLTw)
. Berikut ini perbedaan kinerja SVM sebagai fungsi ukuran set pelatihan.
Saya telah merencanakan hasil neural net, untuk memudahkan perbandingan
\* \* Grafik ini dibuat dengan program
[more\_data.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/more_data.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhwO1DgFWxPK0gp_aW4-qoMdgiIHQ)
(seperti beberapa grafik terakhir). :

![http://neuralnetworksanddeeplearning.com/images/more\_data\_comparison.png](media/image71.png)

Mungkin hal pertama yang mengejutkan Anda tentang grafik ini adalah
bahwa jaringan saraf (*neural networks*) kami mengungguli SVM untuk
setiap ukuran set pelatihan. Itu bagus, meskipun Anda tidak boleh
membaca terlalu banyak tentang itu, karena saya hanya menggunakan
pengaturan out-of-the-box dari scikit-learn's SVM, sementara kami telah
melakukan sedikit pekerjaan memperbaiki *jaringan saraf (neural
networks)* kami. Fakta yang lebih halus tetapi lebih menarik tentang
grafik adalah bahwa jika kita melatih SVM kita menggunakan 50.000 gambar
maka itu sebenarnya memiliki kinerja yang lebih baik (akurasi 94,48
persen) daripada jaringan saraf (*neural networks*) kita ketika dilatih
menggunakan 5.000 gambar (akurasi 93,24 persen). Dengan kata lain, lebih
banyak data pelatihan terkadang dapat mengompensasi perbedaan dalam
algoritma pembelajaran mesin yang digunakan.

Sesuatu yang bahkan lebih menarik dapat terjadi. Misalkan kita sedang
mencoba untuk menyelesaikan masalah menggunakan dua algoritma
pembelajaran mesin, algoritma A dan algoritma B. Kadang-kadang terjadi
bahwa algoritma A akan mengungguli algoritma B dengan satu set data
pelatihan, sedangkan algoritma B akan mengungguli algoritma A dengan set
yang berbeda dari data pelatihan. Kami tidak melihat bahwa di atas - itu
akan memerlukan dua grafik untuk menyeberang - tetapi itu memang terjadi
\* \* Contoh mencolok dapat ditemukan di [Scaling ke korpora yang sangat
besar untuk disambiguasi bahasa
alami](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://dx.doi.org/10.3115/1073012.1073017&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhp5H4YHdR_WIEgWKp1-aV_gg-etg)
, oleh Michele Banko dan Eric Brill (2001). . Jawaban yang benar untuk
pertanyaan "Apakah algoritma A lebih baik daripada algoritma B?"
benar-benar: "Kumpulan data pelatihan apa yang Anda gunakan?"

Semua ini merupakan peringatan untuk diingat, baik ketika melakukan
pengembangan, maupun saat membaca makalah penelitian. Banyak makalah
fokus pada menemukan trik baru untuk meredam peningkatan kinerja pada
set data patokan standar. "Teknik jagoan kami memberi kami peningkatan X
persen pada tolok ukur standar Y" adalah bentuk kanonik dari klaim
penelitian. Klaim semacam itu seringkali benar-benar menarik, tetapi
klaim tersebut harus dipahami sebagai penerapan hanya dalam konteks
rangkaian data pelatihan khusus yang digunakan. Bayangkan sebuah sejarah
alternatif di mana orang-orang yang awalnya membuat kumpulan data
benchmark memiliki dana penelitian lebih besar. Mereka mungkin
menggunakan uang ekstra untuk mengumpulkan lebih banyak data pelatihan.
Sangat mungkin bahwa "peningkatan" karena teknik jagoan-bang akan
menghilang pada kumpulan data yang lebih besar. Dengan kata lain,
perbaikan yang konon mungkin hanya kebetulan sejarah. Pesan yang harus
diambil, terutama dalam aplikasi praktis, adalah apa yang kita inginkan
adalah algoritma yang lebih baik *dan* data pelatihan yang lebih baik.
Tidak apa-apa untuk mencari algoritma yang lebih baik, tetapi pastikan
Anda tidak fokus pada algoritma yang lebih baik dengan mengesampingkan
kemenangan mudah mendapatkan data pelatihan yang lebih banyak atau lebih
baik.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problem_455958) 

  - **(Masalah penelitian)** Bagaimana kinerja algoritma pembelajaran
    mesin kami dalam batas kumpulan data yang sangat besar? Untuk
    algoritme apa pun yang diberikan, wajar untuk mencoba mendefinisikan
    gagasan kinerja asimptotik dalam batas data yang benar-benar besar.
    Pendekatan cepat dan kotor untuk masalah ini adalah dengan hanya
    mencoba mencocokkan kurva ke grafik seperti yang ditunjukkan di
    atas, dan kemudian untuk memperkirakan kurva yang dipasang hingga
    tak terbatas. Keberatan terhadap pendekatan ini adalah bahwa
    pendekatan yang berbeda untuk pemasangan kurva akan memberikan
    gagasan yang berbeda tentang kinerja asimptotik. Dapatkah Anda
    menemukan justifikasi berprinsip untuk menyesuaikan dengan beberapa
    kelas kurva tertentu? Jika demikian, bandingkan kinerja asimptotik
    dari beberapa algoritma pembelajaran mesin yang berbeda.

**Kesimpulannya:** Kami sekarang telah menyelesaikan penyelaman kami
menjadi overfitting dan regularisasi. Tentu saja, kami akan kembali lagi
ke masalah ini. Seperti yang telah saya sebutkan beberapa kali,
overfitting adalah masalah utama dalam jaringan saraf, terutama ketika
komputer menjadi lebih kuat, dan kami memiliki kemampuan untuk melatih
jaringan yang lebih besar. Akibatnya ada kebutuhan mendesak untuk
mengembangkan teknik regularisasi yang kuat untuk mengurangi
overfitting, dan ini adalah bidang yang sangat aktif dari pekerjaan saat
ini.

### [Inisialisasi berat](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization) 

Ketika kita membuat jaringan saraf (*neural networks*) kita, kita harus
membuat pilihan untuk bobot dan bias awal. Hingga kini, kami telah
memilih mereka berdasarkan resep yang saya diskusikan secara singkat [di
Bab 1](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#weight_initialization)
. Sekadar mengingatkan Anda, resep itu adalah untuk memilih bobot dan
bias menggunakan variabel acak Gaussian independen, dinormalisasi dengan
rata-rata 0 dan standar deviasi 1. Meskipun pendekatan ini telah bekerja
dengan baik, itu cukup *ad hoc* , dan perlu ditinjau kembali untuk
melihat apakah kita dapat menemukan cara yang lebih baik untuk mengatur
bobot dan bias awal kita, dan mungkin membantu *jaringan saraf (neural
networks)* kita belajar lebih cepat.

Ternyata kita bisa melakukan sedikit lebih baik daripada
menginisialisasi dengan Gaussi yang dinormalisasi. Untuk mengetahui
alasannya, misalkan kita bekerja dengan jaringan dengan jumlah besar -
katakan 1.000 - neuron input. Dan misalkan kita telah menggunakan
Gaussians yang dinormalisasi untuk menginisialisasi bobot yang terhubung
ke lapisan tersembunyi pertama. Untuk saat ini saya akan berkonsentrasi
secara khusus pada bobot yang menghubungkan neuron input ke neuron
pertama di lapisan tersembunyi, dan mengabaikan sisa jaringan:

![http://neuralnetworksanddeeplearning.com/images/tikz32.png](media/image72.png)

Kami akan mengandaikan untuk kesederhanaan bahwa kami mencoba untuk
melatih menggunakan input pelatihan x di mana setengah neuron input
aktif, yaitu, ditetapkan menjadi 1, dan setengah neuron input dimatikan,
yaitu, ditetapkan ke 0 . Argumen berikut berlaku lebih umum, tetapi Anda
akan mendapatkan inti dari kasus khusus ini. Mari kita pertimbangkan
jumlah terbobot z= sumjwjxj+b input ke neuron tersembunyi kita. Istilah
500 dalam jumlah ini lenyap, karena input xj yang sesuai adalah nol.
Jadi z adalah jumlah dari total 501 variabel acak Gaussian yang
dinormalisasi, terhitung untuk persyaratan bobot 500 dan istilah bias
tambahan 1. Jadi z sendiri didistribusikan sebagai Gaussian dengan mean
nol dan standar deviasi  sqrt501 sekitar22,4. Yaitu, z memiliki
distribusi Gaussian yang sangat luas, tidak memuncak tajam sama sekali:

Secara khusus, kita dapat melihat dari grafik ini bahwa sangat mungkin
|z| akan cukup besar, yaitu z gg1 atau z ll−1. Jika itu masalahnya maka
output  sigma(z) dari neuron tersembunyi akan sangat dekat dengan 1 atau
0. Itu berarti neuron tersembunyi kita akan jenuh. Dan ketika itu
terjadi, seperti yang kita tahu, membuat perubahan kecil pada bobot
hanya akan membuat perubahan sangat kecil dalam aktivasi neuron
tersembunyi kita. Perubahan sangat kecil dalam aktivasi neuron
tersembunyi akan, pada gilirannya, hampir tidak mempengaruhi sisa neuron
dalam jaringan sama sekali, dan kita akan melihat perubahan sangat kecil
dalam fungsi biaya. Akibatnya, bobot tersebut hanya akan belajar dengan
sangat lambat ketika kami menggunakan algoritma gradient descent \* \*
Kami membahas ini secara lebih rinci di Bab 2, di mana kami menggunakan
[persamaan
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_four_fundamental_equations_behind_backpropagation)
untuk menunjukkan bahwa bobot input ke neuron jenuh dipelajari secara
lambat. . Ini mirip dengan masalah yang kita bahas sebelumnya dalam bab
ini, di mana neuron keluaran yang jenuh pada nilai yang salah
menyebabkan pembelajaran melambat. Kami membahas masalah sebelumnya
dengan pilihan fungsi biaya yang cerdas. Sayangnya, sementara itu
membantu dengan neuron output jenuh, itu tidak melakukan apa-apa untuk
masalah dengan neuron tersembunyi jenuh.

Saya sudah bicara tentang input bobot ke lapisan tersembunyi pertama.
Tentu saja, argumen serupa juga berlaku untuk lapisan tersembunyi di
kemudian hari: jika bobot di lapisan tersembunyi kemudian diinisialisasi
menggunakan Gaussians yang dinormalisasi, maka aktivasi akan sering
sangat dekat dengan 0 atau 1, dan pembelajaran akan berjalan sangat
lambat.

Apakah ada beberapa cara kita dapat memilih inisialisasi untuk bobot dan
bias, sehingga kita tidak mendapatkan kejenuhan seperti ini, dan
menghindari perlambatan belajar? Misalkan kita memiliki neuron dengan
n rmin input weight. Kemudian kita akan menginisialisasi bobot tersebut
sebagai variabel acak Gaussian dengan rata-rata 0 dan standar deviasi
1/ sqrtn rmin. Artinya, kita akan menekan Gaussians ke bawah, sehingga
kecil kemungkinan neuron kita akan jenuh. Kami akan terus memilih bias
sebagai Gaussian dengan mean 0 dan standar deviasi 1, untuk alasan saya
akan kembali sebentar lagi. Dengan pilihan-pilihan ini, jumlah terbobot
z= sumjwjxj+b akan kembali menjadi variabel acak Gaussian dengan
rata-rata $ 0, tetapi akan memuncak lebih tajam daripada sebelumnya.
Misalkan, seperti yang kita lakukan sebelumnya, 500 input adalah nol dan
500 adalah 1. Maka mudah untuk menunjukkan (lihat latihan di bawah)
bahwa z memiliki distribusi Gaussian dengan rata-rata 0 dan deviasi
standar  sqrt3/2=1.22 ldots. Ini jauh lebih tajam daripada sebelumnya,
sedemikian rupa sehingga bahkan grafik di bawah ini mengecilkan situasi,
karena saya harus mengubah skala sumbu vertikal, jika dibandingkan
dengan grafik sebelumnya:

Neuron seperti itu jauh lebih kecil kemungkinannya untuk jenuh, dan
lebih kecil kemungkinannya untuk mengalami masalah dengan kelambatan
belajar.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_319349) 

  - Verifikasi bahwa standar deviasi z= sumjwjxj+b dalam paragraf di
    atas adalah  sqrt3/2. Mungkin membantu untuk mengetahui bahwa: (a)
    varians dari jumlah variabel acak independen adalah jumlah varian
    dari variabel acak individu; dan (b) varians adalah kuadrat dari
    deviasi standar.

Saya menyatakan di atas bahwa kami akan terus menginisialisasi bias
seperti sebelumnya, sebagai variabel acak Gaussian dengan rata-rata 0
dan standar deviasi 1. Ini baik-baik saja, karena itu tidak membuatnya
lebih mungkin neuron kita akan jenuh. Sebenarnya, tidak masalah
bagaimana kita menginisialisasi bias, asalkan kita menghindari masalah
dengan saturasi. Beberapa orang bertindak lebih jauh dengan
menginisialisasi semua bias menjadi 0, dan mengandalkan gradient descent
untuk mempelajari bias yang sesuai. Tetapi karena tidak mungkin membuat
banyak perbedaan, kami akan melanjutkan dengan prosedur inisialisasi
yang sama seperti sebelumnya.

Mari kita bandingkan hasilnya untuk pendekatan lama dan baru kami untuk
inisialisasi bobot, menggunakan tugas klasifikasi digit MNIST. Seperti
sebelumnya, kita akan menggunakan 30 neuron tersembunyi, ukuran
mini-batch 10,parameterregularisasi \\ lambda = 5.0 $, dan fungsi biaya
lintas-entropi. Kami akan mengurangi tingkat pembelajaran sedikit dari
 eta=0,5 menjadi 0,1, karena itu membuat hasil sedikit lebih mudah
terlihat dalam grafik. Kita bisa berlatih menggunakan metode
inisialisasi berat yang lama:

\>\>\> impor mnist\_loader \>\>\> training\_data , validation\_data ,
test\_data = \\ ... mnist\_loader . load\_data\_wrapper () \>\>\> import
network2 \>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \], biaya =
jaringan2 . CrossEntropyCost ) \>\>\> bersih .
large\_weight\_initializer () \>\>\> bersih . SGD ( training\_data , 30
, 10 , 0.1 , lmbda = 5.0 , ... evaluation\_data = validation\_data , ...
monitor\_evaluation\_accuracy = Benar )

Kita juga bisa berlatih menggunakan pendekatan baru untuk inisialisasi
bobot. Ini sebenarnya lebih mudah, karena cara standar network2 untuk
menginisialisasi bobot menggunakan pendekatan baru ini. Itu berarti kita
dapat menghilangkan panggilan net.large\_weight\_initializer () di atas:

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \], biaya = jaringan2
. CrossEntropyCost )

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0.1 , lmbda = 5.0 ,

... evaluation\_data = validation\_data ,

... monitor\_evaluation\_accuracy = Benar )

Merencanakan hasil \* \* Program yang digunakan untuk menghasilkan ini
dan grafik berikutnya adalah
[weight\_initialization.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/weight_initialization.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjs5vuCf0mdsV6qAP0u65AGAO-V0A)
. , kami memperoleh:

![http://neuralnetworksanddeeplearning.com/images/weight\_initialization\_30.png](media/image73.png)

Dalam kedua kasus, kami berakhir dengan akurasi klasifikasi agak di atas
96 persen. Akurasi klasifikasi akhir hampir persis sama dalam dua kasus.
Tetapi teknik inisialisasi baru membawa kita ke sana, jauh lebih cepat.
Pada akhir zaman pelatihan, pendekatan lama terhadap inisialisasi bobot
memiliki akurasi klasifikasi di bawah 87 persen, sedangkan pendekatan
baru sudah hampir 93 persen. Apa yang tampaknya sedang terjadi adalah
bahwa pendekatan baru kami untuk inisialisasi bobot memulai kami dalam
rezim yang jauh lebih baik, yang memungkinkan kami mendapatkan hasil
yang baik lebih cepat. Fenomena yang sama juga terlihat jika kita
memplot hasil dengan neuron tersembunyi $ 100:

![http://neuralnetworksanddeeplearning.com/images/weight\_initialization\_100.png](media/image74.png)

Dalam hal ini, kedua kurva tidak cukup bertemu. Namun, percobaan saya
menunjukkan bahwa dengan hanya beberapa zaman pelatihan (tidak
ditampilkan) akurasi menjadi hampir persis sama. Jadi berdasarkan
percobaan ini, sepertinya inisialisasi peningkatan berat hanya
mempercepat pembelajaran, itu tidak mengubah kinerja akhir jaringan
kami. Namun, pada Bab 4 kita akan melihat contoh *jaringan saraf (neural
networks)* di mana perilaku jangka panjang secara signifikan lebih baik
dengan 1/ sqrtn rmin inisialisasi berat. Jadi bukan hanya kecepatan
belajar yang ditingkatkan, kadang-kadang juga kinerja akhir.

Pendekatan $ 1 / \\ sqrt {n \_ {\\ rm in}} untuk inisialisasi bobot
membantu meningkatkan cara belajar jaring saraf kita. Teknik lain untuk
inisialisasi berat juga telah diusulkan, banyak membangun ide dasar ini.
Saya tidak akan meninjau pendekatan lain di sini, karena 1/ sqrtn rmin
berfungsi cukup baik untuk tujuan kita. Jika Anda tertarik untuk melihat
lebih jauh, saya sarankan untuk melihat diskusi di halaman 14 dan 15
makalah 2012 oleh Yoshua Bengio \* \* [Rekomendasi Praktis untuk
Pelatihan Arsitektur Mendalam
Gradien](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://arxiv.org/pdf/1206.5533v2.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgXY3164lUKuSlrF-YAqAueSGA5kw)
, oleh Yoshua Bengio (2012). , serta referensi di dalamnya.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problem_735589) 

  - **Menghubungkan regularisasi dan metode peningkatan inisialisasi
    berat** L2 regularisasi kadang-kadang secara otomatis memberi kita
    sesuatu yang mirip dengan pendekatan baru untuk inisialisasi berat.
    Misalkan kita menggunakan pendekatan lama untuk inisialisasi bobot.
    Buat sketsa argumen heuristik bahwa: (1) seandainya  lambda tidak
    terlalu kecil, zaman pertama pelatihan akan didominasi hampir
    seluruhnya oleh penurunan berat badan; (2) asalkan  eta lambda lln
    bobot akan membusuk dengan faktor  exp(− eta lambda/m) per zaman;
    dan (3) seandainya  lambda tidak terlalu besar, pembusukan berat
    akan berkurang ketika bobot turun ke ukuran sekitar 1/ sqrtn, di
    mana n adalah jumlah total bobot dalam jaringan. Berargumen bahwa
    kondisi ini semua puas dalam contoh yang digambarkan di bagian ini.

### [Pengenalan tulisan tangan ditinjau kembali: kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#handwriting_recognition_revisited_the_code) 

Mari kita terapkan ide-ide yang telah kita diskusikan di bab ini. Kami
akan mengembangkan program baru,
[<span class="underline">network2.py</span>](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/network2.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgRrjNZoFbpGaWZDuSJCmUDrSWpCA)
, yang merupakan versi perbaikan dari program
[<span class="underline">network.py
yang</span>](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/network.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiNx3KkAQ3VPdoWpuTIZ_EurT-rqQ)
kami kembangkan di
[Bab 1](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
. Jika Anda belum melihat network.py dalam beberapa saat maka Anda
mungkin merasa perlu untuk menghabiskan beberapa menit dengan cepat
membaca diskusi sebelumnya. Ini hanya 74 baris kode, dan mudah
dimengerti.

Seperti halnya di network.py , bintang dari network2.py adalah kelas
Network , yang kami gunakan untuk mewakili *jaringan saraf (neural
networks)* kami. Kami menginisialisasi instance dari Jaringan dengan
daftar ukuran untuk masing-masing lapisan dalam jaringan, dan pilihan
untuk biaya yang akan digunakan, default ke lintas-entropi:

Jaringan kelas ( objek ):

def \_\_init\_\_ ( mandiri , ukuran , biaya = CrossEntropyCost ):

diri num\_layers = len ( ukuran )

diri ukuran = ukuran

diri default\_weight\_initializer ()

diri biaya = biaya

Beberapa baris pertama dari metode \_\_init\_\_ sama dengan di
network.py , dan cukup jelas. Tetapi dua baris berikutnya adalah baru,
dan kita perlu memahami apa yang mereka lakukan secara detail.

Mari kita mulai dengan memeriksa metode default\_weight\_initializer .
Ini memanfaatkan
[pendekatan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
kami yang [baru dan lebih
baik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
untuk inisialisasi bobot. Seperti yang telah kita lihat, dalam
pendekatan itu input bobot ke neuron diinisialisasi sebagai variabel
acak Gaussian dengan mean 0 dan standar deviasi 1 dibagi dengan akar
kuadrat dari jumlah koneksi input ke neuron. Juga dalam metode ini kita
akan menginisialisasi bias, menggunakan variabel acak Gaussian dengan
rata-rata 0danstandardeviasi 1 $. Ini kodenya:

def default\_weight\_initializer ( mandiri ):

diri bias = \[ np . acak . randn ( y , 1 ) untuk y dalam diri . ukuran
\[ 1 :\]\]

diri bobot = \[ np . acak . randn ( y , x ) / np . sqrt ( x )

untuk x , y dalam zip ( ukuran diri \[: - 1 \], ukuran diri . \[ 1
:\])\]

Untuk memahami kode, mungkin membantu untuk mengingat bahwa np adalah
pustaka Numpy untuk melakukan aljabar linier. Kami akan mengimpor Numpy
di awal program kami. Juga, perhatikan bahwa kami tidak menginisialisasi
bias apa pun untuk lapisan neuron pertama. Kami menghindari melakukan
ini karena lapisan pertama adalah lapisan input, dan karenanya bias
tidak akan digunakan. Kami melakukan hal yang persis sama di network.py
.

Melengkapi default\_weight\_initializer kami juga akan menyertakan
metode large\_weight\_initializer . Metode ini menginisialisasi bobot
dan bias menggunakan pendekatan lama dari Bab 1, dengan bobot dan bias
diinisialisasi sebagai variabel acak Gaussian dengan mean
0danstandardeviasi 1 $. Kode ini, tentu saja, hanya sedikit berbeda dari
default\_weight\_initializer :

def large\_weight\_initializer ( mandiri ):

diri bias = \[ np . acak . randn ( y , 1 ) untuk y dalam diri . ukuran
\[ 1 :\]\]

diri bobot = \[ np . acak . Randand ( y , x )

untuk x , y dalam zip ( ukuran diri \[: - 1 \], ukuran diri . \[ 1
:\])\]

Saya telah memasukkan metode large\_weight\_initializer sebagian besar
sebagai kemudahan untuk membuatnya lebih mudah untuk membandingkan hasil
dalam bab ini dengan yang ada di Bab 1. Saya tidak bisa memikirkan
banyak situasi praktis di mana saya akan merekomendasikan
menggunakannya\!

Hal baru kedua dalam metode Network \_\_init\_\_ adalah bahwa kita
sekarang menginisialisasi atribut biaya . Untuk memahami cara kerjanya,
mari kita lihat kelas yang kita gunakan untuk mewakili biaya
lintas-entropi \* \* Jika Anda tidak terbiasa dengan metode statis
Python, Anda dapat mengabaikan dekorator metoda metoda , dan hanya
memperlakukan fn dan delta sebagai metode biasa. Jika Anda ingin tahu
tentang detail, semua metode @static lakukan adalah memberi tahu juru
bahasa Python bahwa metode yang mengikuti tidak bergantung pada objek
dengan cara apa pun. Itu sebabnya self tidak dilewatkan sebagai
parameter ke metode fn dan delta . :

class CrossEntropyCost ( objek ):

@staticmethod

def fn ( a , y ):

kembali np . jumlah ( np . nan\_to\_num ( - y \* np . log ( a ) - ( 1 -
y ) \* np . log ( 1 - a )))

@staticmethod

def delta ( z , a , y ):

return ( a - y )

Mari kita hancurkan ini. Hal pertama yang harus diperhatikan adalah
meskipun cross-entropy adalah, secara matematis, sebuah fungsi, kami
telah mengimplementasikannya sebagai kelas Python, bukan fungsi Python.
Mengapa saya membuat pilihan itu? Alasannya adalah karena biaya
memainkan dua peran yang berbeda dalam jaringan kami. Peran yang jelas
adalah bahwa itu adalah ukuran seberapa baik aktivasi output, a , cocok
dengan output yang diinginkan, y . Peran ini ditangkap oleh metode
CrossEntropyCost.fn . (Catat, omong-omong, panggilan np.nan\_to\_num di
dalam CrossEntropyCost.fn memastikan bahwa Numpy menangani dengan benar
angka-angka log yang mendekati nol.) Tetapi ada juga cara kedua fungsi
biaya memasuki jaringan kami. Ingat dari
[Bab 2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_four_fundamental_equations_behind_backpropagation)
bahwa ketika menjalankan algoritma backpropagation kita perlu menghitung
kesalahan output jaringan,  deltaL. Bentuk kesalahan output tergantung
pada pilihan fungsi biaya: fungsi biaya berbeda, bentuk berbeda untuk
kesalahan output. Untuk cross-entropy kesalahan output adalah, seperti
yang kita lihat di Persamaan (66) ,

\\ begin {eqnarray} \\ delta ^ L = a ^ Ly. \\ tag {99} \\ end {eqnarray}
Untuk alasan ini kami mendefinisikan metode kedua,
CrossEntropyCost.delta , yang tujuannya adalah untuk memberi tahu
jaringan kami cara menghitung kesalahan keluaran. Lalu kami
menggabungkan kedua metode ini menjadi satu kelas yang berisi semua yang
perlu diketahui jaringan kami tentang fungsi biaya.

Dengan cara yang sama, network2.py juga mengandung kelas untuk mewakili
fungsi biaya kuadratik. Ini termasuk untuk perbandingan dengan hasil Bab
1, karena ke depan kita sebagian besar akan menggunakan cross entropy.
Kodenya persis di bawah. Metode QuadraticCost.fn adalah perhitungan
langsung dari biaya kuadratik yang terkait dengan output aktual, a , dan
output yang diinginkan, y . Nilai yang dikembalikan oleh
QuadraticCost.delta didasarkan pada ekspresi (30) untuk kesalahan output
untuk biaya kuadratik, yang kami peroleh kembali pada Bab 2.

class QuadraticCost ( objek ):

@staticmethod

def fn ( a , y ):

kembali 0,5 \* np . linalg . norma ( a - y ) \*\* 2

@staticmethod

def delta ( z , a , y ):

return ( a - y ) \* sigmoid\_prime ( z )

Kami sekarang telah memahami perbedaan utama antara network2.py dan
network.py . Itu semua hal yang sangat sederhana. Ada sejumlah perubahan
kecil, yang akan saya bahas di bawah ini, termasuk implementasi
regularisasi L2. Sebelum membahasnya , mari kita lihat kode lengkap
untuk network2.py . Anda tidak perlu membaca semua kode secara detail,
tetapi perlu memahami struktur yang luas, dan khususnya membaca string
dokumentasi, sehingga Anda memahami apa yang dilakukan setiap bagian
dari program. Tentu saja, Anda juga dipersilakan untuk menggali sedalam
yang Anda inginkan\! Jika Anda tersesat, Anda mungkin ingin terus
membaca prosa di bawah ini, dan kembali ke kode nanti. Bagaimanapun, ini
kodenya:

"" "network2.py

\~\~\~\~\~\~\~\~\~\~\~\~\~\~

Versi peningkatan network.py, menerapkan stokastik

algoritma pembelajaran gradient descent untuk *jaringan saraf (neural
networks)* feedforward.

Perbaikan termasuk penambahan fungsi biaya lintas-entropi,

regularisasi, dan inisialisasi bobot jaringan yang lebih baik. Catatan

bahwa saya telah fokus membuat kode sederhana, mudah dibaca, dan

mudah dimodifikasi. Itu tidak dioptimalkan, dan menghilangkan banyak
yang diinginkan

fitur.

"" "

\#\#\#\# Pustaka

\# Pustaka standar

impor json

impor acak

impor sys

\# Pustaka pihak ketiga

impor numpy sebagai np

\#\#\#\# Menentukan fungsi biaya kuadratik dan lintas-entropi

class QuadraticCost ( objek ):

@staticmethod

def fn ( a , y ):

"" "Kembalikan biaya yang terkait dengan output\` \`a\`\` dan output
yang diinginkan

\`\` y\`\`.

"" "

kembali 0,5 \* np . linalg . norma ( a - y ) \*\* 2

@staticmethod

def delta ( z , a , y ):

"" "Kembalikan delta kesalahan dari lapisan keluaran." ""

return ( a - y ) \* sigmoid\_prime ( z )

class CrossEntropyCost ( objek ):

@staticmethod

def fn ( a , y ):

"" "Kembalikan biaya yang terkait dengan output\` \`a\`\` dan output
yang diinginkan

\`\` y\`\`. Perhatikan bahwa np.nan\_to\_num digunakan untuk memastikan
angka

stabilitas. Khususnya, jika keduanya \`\` a\`\` dan \`\` y\`\` memiliki
1.0

di slot yang sama, lalu ekspresi (1-y) \* np.log (1-a)

mengembalikan nan. Np.nan\_to\_num memastikan bahwa itu dikonversi

ke nilai yang benar (0,0).

"" "

kembali np . jumlah ( np . nan\_to\_num ( - y \* np . log ( a ) - ( 1 -
y ) \* np . log ( 1 - a )))

@staticmethod

def delta ( z , a , y ):

"" "Kembalikan delta kesalahan dari lapisan keluaran. Perhatikan bahwa

parameter \`\` z\`\` tidak digunakan oleh metode ini. Itu termasuk dalam

parameter metode untuk membuat antarmuka

konsisten dengan metode delta untuk kelas biaya lainnya.

"" "

return ( a - y )

\#\#\#\# Kelas Jaringan Utama

Jaringan kelas ( objek ):

def \_\_init\_\_ ( mandiri , ukuran , biaya = CrossEntropyCost ):

"" "Daftar\` \`ukuran\`\` berisi jumlah neuron di masing-masing

lapisan jaringan. Misalnya, jika daftarnya \[2, 3, 1\]

maka itu akan menjadi jaringan tiga lapis, dengan lapisan pertama

mengandung 2 neuron, neuron lapis 3, dan

neuron lapisan 1 ketiga. Bias dan bobot untuk jaringan

diinisialisasi secara acak, menggunakan

\`\` self.default\_weight\_initializer\`\` (lihat mendokumentasikan
untuk itu

metode).

"" "

diri num\_layers = len ( ukuran )

diri ukuran = ukuran

diri default\_weight\_initializer ()

diri biaya = biaya

def default\_weight\_initializer ( mandiri ):

"" "Inisialisasi setiap bobot menggunakan distribusi Gaussian dengan
rata-rata 0

dan standar deviasi 1 pada akar kuadrat dari jumlah

bobot terhubung ke neuron yang sama. Inisialisasi bias

menggunakan distribusi Gaussian dengan rata-rata 0 dan standar

penyimpangan 1.

Perhatikan bahwa lapisan pertama diasumsikan sebagai lapisan input, dan

oleh konvensi kita tidak akan menetapkan bias untuk neuron-neuron itu,
karena

bias hanya pernah digunakan dalam menghitung output dari nanti

lapisan.

"" "

diri bias = \[ np . acak . randn ( y , 1 ) untuk y dalam diri . ukuran
\[ 1 :\]\]

diri bobot = \[ np . acak . randn ( y , x ) / np . sqrt ( x )

untuk x , y dalam zip ( ukuran diri \[: - 1 \], ukuran diri . \[ 1
:\])\]

def large\_weight\_initializer ( mandiri ):

"" "Inisialisasi bobot menggunakan distribusi Gaussian dengan rata-rata
0

dan standar deviasi 1. Inisialisasi bias menggunakan a

Distribusi Gaussian dengan rata-rata 0 dan standar deviasi 1.

Perhatikan bahwa lapisan pertama diasumsikan sebagai lapisan input, dan

oleh konvensi kita tidak akan menetapkan bias untuk neuron-neuron itu,
karena

bias hanya pernah digunakan dalam menghitung output dari nanti

lapisan.

Inisialisasi bobot dan bias ini menggunakan pendekatan yang sama seperti
pada

Bab 1, dan dimasukkan untuk tujuan perbandingan. Itu

biasanya akan lebih baik menggunakan initializer weight default

sebagai gantinya.

"" "

diri bias = \[ np . acak . randn ( y , 1 ) untuk y dalam diri . ukuran
\[ 1 :\]\]

diri bobot = \[ np . acak . Randand ( y , x )

untuk x , y dalam zip ( ukuran diri \[: - 1 \], ukuran diri . \[ 1
:\])\]

def feedforward ( self , a ):

"" "Kembalikan output jaringan jika\` \`a\`\` adalah input." ""

untuk b , w di zip ( self . bias , self . weights ):

a = sigmoid ( np . dot ( w , a ) + b )

mengembalikan a

def SGD ( self , training\_data , epochs , mini\_batch\_size , eta ,

lmbda = 0,0 ,

evaluation\_data = Tidak Ada ,

monitor\_evaluation\_cost = Salah ,

monitor\_evaluation\_accuracy = Salah ,

monitor\_training\_cost = Salah ,

monitor\_training\_accuracy = Salah ):

"" "Latih jaringan saraf (*neural networks*) menggunakan gradien
stokastik mini-batch

keturunan. \`\` Training\_data\`\` adalah daftar tuples \`\` (x, y) \`\`

mewakili input pelatihan dan output yang diinginkan. Itu

parameter non-opsional lainnya cukup jelas, seperti halnya

parameter regularisasi \`\` lmbda\`\`. Metode ini juga menerima

\`\` evaluation\_data\`\`, biasanya berupa validasi atau tes

data. Kami dapat memantau biaya dan keakuratan pada salah satu

data evaluasi atau data pelatihan, dengan menetapkan

bendera yang sesuai. Metode mengembalikan tuple yang berisi empat

daftar: biaya (per-zaman) pada data evaluasi, data

akurasi pada data evaluasi, biaya pelatihan

data, dan akurasi data pelatihan. Semua nilai adalah

dievaluasi pada akhir setiap periode pelatihan. Jadi, misalnya,

jika kita berlatih selama 30 zaman, maka elemen pertama dari tuple

akan menjadi daftar 30 elemen yang berisi biaya pada

data evaluasi pada akhir setiap zaman. Perhatikan bahwa daftar

kosong jika bendera yang sesuai tidak disetel.

"" "

if evaluation\_data : n\_data = len ( evaluation\_data )

n = len ( training\_data )

evaluation\_cost , evaluation\_accuracy = \[\], \[\]

training\_cost , training\_accuracy = \[\], \[\]

untuk j in xrange ( zaman ):

acak . shuffle ( training\_data )

mini\_batches = \[

training\_data \[ k : k + mini\_batch\_size \]

untuk k dalam xrange ( 0 , n , mini\_batch\_size )\]

untuk mini\_batch di mini\_batches :

diri update\_mini\_batch (

mini\_batch , eta , lmbda , len ( training\_data ))

cetak " Pelatihan Epoch % s selesai" % j

jika monitor\_training\_cost :

biaya = diri . total\_cost ( training\_data , lmbda )

training\_cost . tambahkan ( biaya )

cetak "Biaya data pelatihan: {}" . format ( biaya )

jika monitor\_training\_accuracy :

akurasi = diri . akurasi ( training\_data , convert = True )

pelatihan\_akurasi . tambahkan ( akurasi )

cetak "Akurasi data pelatihan: {} / {}" . format (

akurasi , n )

jika monitor\_evaluation\_cost :

biaya = diri . total\_cost ( evaluation\_data , lmbda , convert = True )

evaluation\_cost . tambahkan ( biaya )

cetak "Biaya data evaluasi: {}" . format ( biaya )

jika monitor\_evaluation\_accuracy :

akurasi = diri . akurasi ( evaluation\_data )

evaluasi\_akurasi . tambahkan ( akurasi )

cetak "Akurasi data evaluasi: {} / {}" . format (

diri akurasi ( evaluation\_data ), n\_data )

mencetak

kembalikan evaluasi\_kost , evaluasi\_kurasi , \\

training\_cost , training\_accuracy

def update\_mini\_batch ( self , mini\_batch , eta , lmbda , n ):

"" "Perbarui bobot dan bias jaringan dengan menerapkan gradien

keturunan menggunakan backpropagation ke satu batch mini. Itu

\`\` mini\_batch\`\` adalah daftar tuple \`\` (x, y) \`\`, \`\` eta\`\`
adalah

tingkat belajar, \`\` lmbda\`\` adalah parameter regularisasi, dan

\`\` n\`\` adalah ukuran total dari set data pelatihan.

"" "

nabla\_b = \[ np . nol ( bentuk b ) untuk b dalam diri . bias \]

nabla\_w = \[ np . nol ( bentuk w ) untuk w dalam diri . bobot \]

untuk x , y di mini\_batch :

delta\_nabla\_b , delta\_nabla\_w = mandiri . backprop ( x , y )

nabla\_b = \[ nb + dnb untuk nb , dnb dalam zip ( nabla\_b ,
delta\_nabla\_b )\]

nabla\_w = \[ nw + dnw untuk nw , dnw di zip ( nabla\_w ,
delta\_nabla\_w )\]

diri bobot = \[( 1 - eta \* ( lmbda / n )) \* w - ( eta / len (
mini\_batch )) \* nw

untuk w , nw in zip ( bobot mandiri , nabla\_w )\]

diri bias = \[ b - ( eta / len ( mini\_batch )) \* nb

untuk b , nb di zip ( self . bias , nabla\_b )\]

def backprop ( self , x , y ):

"" "Kembalikan tuple\` \`(nabla\_b, nabla\_w)\` \`mewakili

gradien untuk fungsi biaya C\_x. \`\` nabla\_b\`\` dan

\`\` nabla\_w\`\` adalah daftar susunan numpy lapis demi lapis, serupa

ke \`\` self.biases\`\` dan \`\` self.weights\`\`. "" "

nabla\_b = \[ np . nol ( bentuk b ) untuk b dalam diri . bias \]

nabla\_w = \[ np . nol ( bentuk w ) untuk w dalam diri . bobot \]

\# feedforward

aktivasi = x

activations = \[ x \] \# daftar untuk menyimpan semua aktivasi, lapis
demi lapis

zs = \[\] \# daftar untuk menyimpan semua vektor z, lapis demi lapis

untuk b , w di zip ( self . bias , self . weights ):

z = np . titik ( w , aktivasi ) + b

zs . tambahkan ( z )

aktivasi = sigmoid ( z )

aktivasi . tambahkan ( aktivasi )

\# umpan balik

delta = ( biaya sendiri ) . delta ( zs \[ - 1 \], aktivasi \[ - 1 \], y
)

nabla\_b \[ - 1 \] = delta

nabla\_w \[ - 1 \] = np . dot ( delta , aktivasi \[ - 2 \] . transpose
())

\# Perhatikan bahwa variabel l pada loop di bawah ini digunakan sedikit

\# berbeda dengan notasi dalam Bab 2 buku ini. Sini,

\# l = 1 berarti lapisan neuron terakhir, l = 2 adalah

\# lapisan kedua terakhir, dan seterusnya. Ini adalah nomor baru dari

\# Skema dalam buku, digunakan di sini untuk mengambil keuntungan dari
kenyataan

\# Bahwa Python dapat menggunakan indeks negatif dalam daftar.

untuk l in xrange ( 2 , self . num\_layers ):

z = zs \[ - l \]

sp = sigmoid\_prime ( z )

delta = np . dot ( self . timbangan \[ - l + 1 \] . transpose (), delta
) \* sp

nabla\_b \[ - l \] = delta

nabla\_w \[ - l \] = np . titik ( delta , aktivasi \[ - l - 1 \] .
transpose ())

return ( nabla\_b , nabla\_w )

akurasi def ( diri , data , konversi = Salah ):

"" "Kembalikan jumlah input dalam\` \`data\`\` yang neural

jaringan mengeluarkan hasil yang benar. Jaringan saraf

output diasumsikan sebagai indeks dari neuron mana saja di

lapisan terakhir memiliki aktivasi tertinggi.

Bendera \`\` convert\`\` harus disetel ke False jika kumpulan data

validasi atau data uji (kasus biasa), dan True jika

set data adalah data pelatihan. Kebutuhan akan bendera ini muncul

karena perbedaan dalam cara hasil \`\` y\`\`

terwakili dalam set data yang berbeda. Secara khusus, itu

memberi tanda apakah kita perlu mengonversi antara yang berbeda

representasi. Mungkin aneh menggunakan yang berbeda

representasi untuk set data yang berbeda. Mengapa tidak menggunakan

representasi yang sama untuk ketiga set data? Ini dilakukan untuk

alasan efisiensi - program biasanya mengevaluasi biaya

pada data pelatihan dan akurasi pada set data lainnya.

Ini adalah berbagai jenis perhitungan, dan menggunakan yang berbeda

representasi mempercepat segalanya. Lebih detail tentang

representasi dapat ditemukan di

mnist\_loader.load\_data\_wrapper.

"" "

jika dikonversi :

hasil = \[( np . argmax ( self . feedforward ( x )), np . argmax ( y ))

untuk ( x , y ) dalam data \]

lain :

results = \[( np . argmax ( self . feedforward ( x )), y )

untuk ( x , y ) dalam data \]

return sum ( int ( x == y ) untuk ( x , y ) dalam hasil )

def total\_cost ( mandiri , data , lmbda , convert = False ):

"" "Kembalikan total biaya untuk set data\` \`data\`\`. Bendera

\`\` convert\`\` harus disetel ke False jika kumpulan data adalah

data pelatihan (kasus biasa), dan True jika kumpulan data

validasi atau data uji. Lihat komentar serupa di (tetapi

dibalik) konvensi untuk metode \`\` akurasi\`\`, di atas.

"" "

biaya = 0,0

untuk x , y dalam data :

a = diri . feedforward ( x )

jika dikonversi : y = vectorized\_result ( y )

biaya + = sendiri . biaya . fn ( a , y ) / len ( data )

biaya + = 0,5 \* ( lmbda / len ( data )) \* jumlah (

np . linalg . norma ( w ) \*\* 2 untuk w dalam diri . bobot )

biaya pengembalian

def save ( self , filename ):

"" "Simpan jaringan saraf (*neural networks*) ke file\` \`nama
file\`\`." ""

data = { "ukuran" : mandiri . ukuran ,

"Bobot" : \[ w . tolist () untuk w dalam diri . bobot \],

"bias" : \[ b . tolist () untuk b dalam diri . bias \],

"cost" : str ( self . cost . \_\_name\_\_ )}

f = terbuka ( nama file , "w" )

json . dump ( data , f )

f . tutup ()

\#\#\#\# Memuat Jaringan

def load ( nama file ):

"" "Muat jaringan saraf (*neural networks*) dari file\` \`nama file\`\`.
Mengembalikan sebuah

contoh dari Jaringan.

"" "

f = buka ( nama file , "r" )

data = json . memuat ( f )

f . tutup ()

cost = getattr ( sys . modules \[ \_\_name\_\_ \], data \[ "cost" \])

net = Jaringan ( data \[ "ukuran" \], biaya = biaya )

bersih bobot = \[ np . array ( w ) untuk w dalam data \[ "bobot" \]\]

bersih bias = \[ np . array ( b ) untuk b dalam data \[ "bias" \]\]

kembali bersih

\#\#\#\# Fungsi lain-lain

def vectorized\_result ( j ):

"" "Kembalikan vektor satuan 10-dimensi dengan 1,0 di posisi ke-j

dan nol di tempat lain. Ini digunakan untuk mengonversi angka (0 ... 9)

menjadi output yang diinginkan yang sesuai dari jaringan saraf.

"" "

e = np . nol (( 10 , 1 ))

e \[ j \] = 1.0

kembali e

def sigmoid ( z ):

"" "Fungsi sigmoid." ""

return 1.0 / ( 1.0 + np . exp ( - z ))

def sigmoid\_prime ( z ):

"" "Turunan dari fungsi sigmoid." ""

return sigmoid ( z ) \* ( 1 - sigmoid ( z ))

Salah satu perubahan yang lebih menarik dalam kode adalah memasukkan
regularisasi L2. Meskipun ini adalah perubahan konseptual utama, itu
sangat sepele untuk diterapkan sehingga mudah untuk dilewatkan dalam
kode. Sebagian besar itu hanya melibatkan melewati parameter lmbda ke
berbagai metode, terutama metode Network.SGD . Pekerjaan nyata dilakukan
dalam satu baris program, baris keempat terakhir dari metode
Network.update\_mini\_batch . Di situlah kami memodifikasi aturan
pembaruan gradient descent untuk memasukkan pembusukan berat. Tetapi
meskipun modifikasinya kecil, ia memiliki dampak besar pada hasil\!

Ngomong-ngomong, ini biasa terjadi ketika menerapkan teknik baru dalam
jaringan saraf. Kami telah menghabiskan ribuan kata untuk membahas
regularisasi. Secara konseptual cukup halus dan sulit dipahami. Namun
itu sepele untuk ditambahkan ke program kami\! Sangat sering terjadi
bahwa teknik canggih dapat diimplementasikan dengan perubahan kecil pada
kode.

Perubahan kecil tapi penting lainnya pada kode kami adalah penambahan
beberapa flag opsional ke metode gradient descent stochastic,
Network.SGD . Bendera ini memungkinkan untuk memantau biaya dan
keakuratan baik pada data training\_data atau pada set evaluation\_data
yang dapat diteruskan ke Network.SGD . Kami telah menggunakan flag-flag
ini lebih awal dalam bab ini, tetapi izinkan saya memberi contoh
bagaimana kerjanya, hanya untuk mengingatkan Anda:

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

\>\>\> jaringan impor2

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \], biaya = jaringan2
. CrossEntropyCost )

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0,5 ,

... lmbda = 5.0 ,

... evaluation\_data = validation\_data ,

... monitor\_evaluation\_accuracy = Benar ,

... monitor\_evaluation\_cost = Benar ,

... monitor\_training\_accuracy = Benar ,

... monitor\_training\_cost = Benar )

Di sini, kami menetapkan data evaluasi menjadi data validation . Tapi
kami juga bisa memantau kinerja pada test\_data atau kumpulan data
lainnya. Kami juga memiliki empat bendera yang memberi tahu kami untuk
memantau biaya dan keakuratan pada data evaluation\_data dan data
training\_data . Bendera-bendera itu False secara default, tetapi sudah
dinyalakan di sini untuk memantau kinerja Jaringan kami. Selanjutnya,
metode Network.SGD network2.py mengembalikan tuple empat elemen yang
mewakili hasil pemantauan. Kita dapat menggunakan ini sebagai berikut:

\>\>\> evaluation\_cost , evaluation\_accuracy ,

... training\_cost , training\_accuracy = net . SGD ( training\_data ,
30 , 10 , 0,5 ,

... lmbda = 5.0 ,

... evaluation\_data = validation\_data ,

... monitor\_evaluation\_accuracy = Benar ,

... monitor\_evaluation\_cost = Benar ,

... monitor\_training\_accuracy = Benar ,

... monitor\_training\_cost = Benar )

Jadi, misalnya, evaluation\_cost akan menjadi daftar 30 elemen yang
berisi biaya pada data evaluasi di akhir setiap zaman. Informasi semacam
ini sangat berguna dalam memahami perilaku jaringan. Misalnya, dapat
digunakan untuk menggambar grafik yang menunjukkan bagaimana jaringan
belajar dari waktu ke waktu. Memang, itulah tepatnya bagaimana saya
membuat semua grafik di awal bab ini. Namun, perhatikan bahwa jika salah
satu flag pemantauan tidak diatur, maka elemen yang sesuai dalam tuple
akan menjadi daftar kosong.

Tambahan lain pada kode termasuk metode Network.save , untuk menyimpan
objek Network ke disk, dan fungsi untuk memuatnya kembali nanti.
Perhatikan bahwa penyimpanan dan pemuatan dilakukan menggunakan JSON,
bukan modul acar atau cPickle Python, yang merupakan cara biasa kita
menyimpan dan memuat objek ke dan dari disk dengan Python. Menggunakan
JSON membutuhkan lebih banyak kode daripada acar atau cPickle . Untuk
memahami mengapa saya menggunakan JSON, bayangkan bahwa pada suatu waktu
di masa depan kami memutuskan untuk mengubah kelas Jaringan kami untuk
memungkinkan neuron selain neuron sigmoid. Untuk menerapkan perubahan
itu, kami kemungkinan besar akan mengubah atribut yang didefinisikan
dalam metode Network .\_\_ init\_\_ . Jika kita hanya memilih objek yang
akan menyebabkan fungsi beban kita gagal. Menggunakan JSON untuk
melakukan serialisasi secara eksplisit membuatnya mudah untuk memastikan
bahwa Jaringan lama akan tetap dimuat .

Ada banyak perubahan kecil lainnya dalam kode untuk network2.py , tetapi
semuanya variasi sederhana di network.py . Hasil akhirnya adalah
memperluas program 74-line kami menjadi 152 baris yang jauh lebih mampu.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problems_201277) 

  - Ubah kode di atas untuk menerapkan regularisasi L1, dan gunakan
    regularisasi L1 untuk mengklasifikasikan digit MNIST menggunakan
    jaringan neuron tersembunyi senilai $ 30. Dapatkah Anda menemukan
    parameter regularisasi yang memungkinkan Anda melakukan lebih baik
    daripada menjalankan yang tidak diatur?

  - Lihatlah metode Network.cost\_derivative di
    [<span class="underline">network.py</span>](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/network.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiNx3KkAQ3VPdoWpuTIZ_EurT-rqQ)
    . Metode itu ditulis untuk biaya kuadratik. Bagaimana Anda menulis
    ulang metode untuk biaya lintas-entropi? Bisakah Anda memikirkan
    masalah yang mungkin muncul dalam versi lintas-entropi? Di
    network2.py kami telah menghapus seluruhnya metode
    Network.cost\_derivative , alih-alih memasukkan fungsionalitasnya ke
    dalam metode CrossEntropyCost.delta . Bagaimana ini memecahkan
    masalah yang baru saja Anda identifikasi?

### [Bagaimana cara memilih parameter hiper jaringan saraf?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#how_to_choose_a_neural_network's_hyper-parameters) 

Sampai sekarang saya belum menjelaskan bagaimana saya telah memilih
nilai untuk parameter-hiper seperti tingkat pembelajaran,  eta,
parameter regularisasi,  lambda, dan sebagainya. Saya baru saja memasok
nilai-nilai yang bekerja dengan cukup baik. Dalam praktiknya, ketika
Anda menggunakan jaring saraf untuk menyerang masalah, mungkin sulit
untuk menemukan parameter hiper yang baik. Bayangkan, misalnya, bahwa
kita baru saja diperkenalkan dengan masalah MNIST, dan sudah mulai
mengatasinya, sama sekali tidak mengetahui tentang parameter apa yang
digunakan. Mari kita anggap bahwa dengan keberuntungan dalam percobaan
pertama kita, kita memilih banyak parameter hiper dengan cara yang sama
seperti yang dilakukan sebelumnya bab ini: 30 neuron tersembunyi, ukuran
10-batch mini, pelatihan untuk 30 zaman menggunakan cross-entropy .
Tetapi kami memilih tingkat pembelajaran  eta=10.0 dan parameter
regularisasi  lambda=1000.0. Inilah yang saya lihat pada satu kesempatan
seperti itu:

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

\>\>\> jaringan impor2

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \])

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 10.0 , lmbda = 1000.0 ,

... evaluation\_data = validation\_data , monitor\_evaluation\_accuracy
= Benar )

Pelatihan Epoch 0 selesai

Akurasi pada data evaluasi : 1030/10000

Pelatihan Epoch 1 selesai

Akurasi pada data evaluasi : 990/10000

Pelatihan Epoch 2 selesai

Akurasi pada data evaluasi : 1009/10000

...

Pelatihan Epoch 27 selesai

Akurasi pada data evaluasi : 1009/10000

Pelatihan Epoch 28 selesai

Akurasi pada data evaluasi : 983/10000

Pelatihan Epoch 29 selesai

Akurasi pada data evaluasi : 967/10000

Akurasi klasifikasi kami tidak lebih baik dari kebetulan\! Jaringan kami
bertindak sebagai penghasil derau acak\!

"Yah, itu mudah diperbaiki," Anda mungkin berkata, "kurangi saja tingkat
pembelajaran dan parameter hiper regularisasi". Sayangnya, Anda tidak
*apriori* tahu itu adalah hiper-parameter yang perlu Anda sesuaikan.
Mungkin masalah sebenarnya adalah bahwa 30 jaringan neuron tersembunyi
kita tidak akan pernah bekerja dengan baik, tidak peduli bagaimana
parameter hiper lainnya dipilih? Mungkin kita benar-benar membutuhkan
setidaknya 100 neuron tersembunyi? Atau 300 neuron tersembunyi? Atau
beberapa lapisan tersembunyi? Atau pendekatan yang berbeda untuk
pengkodean output? Mungkin jaringan kita sedang belajar, tetapi kita
perlu melatih untuk lebih banyak zaman? Mungkin mini-batch terlalu
kecil? Mungkin kita sebaiknya beralih kembali ke fungsi biaya kuadratik?
Mungkin kita perlu mencoba pendekatan berbeda untuk inisialisasi bobot?
Dan seterusnya, terus dan terus. Sangat mudah untuk merasa tersesat
dalam ruang hyper-parameter. Ini bisa sangat frustasi jika jaringan Anda
sangat besar, atau menggunakan banyak data pelatihan, karena Anda dapat
berlatih selama berjam-jam atau berhari-hari atau berminggu-minggu,
hanya untuk tidak mendapatkan hasil. Jika situasinya berlanjut, itu
merusak kepercayaan diri Anda. Mungkin *jaringan saraf (neural
networks)* adalah pendekatan yang salah untuk masalah Anda? Mungkin Anda
harus berhenti dari pekerjaan Anda dan mengambil perlebahan?

Pada bagian ini saya menjelaskan beberapa heuristik yang dapat digunakan
untuk mengatur parameter-hyper dalam jaringan saraf. Tujuannya adalah
untuk membantu Anda mengembangkan alur kerja yang memungkinkan Anda
untuk melakukan pengaturan parameter yang sangat baik. Tentu saja, saya
tidak akan membahas semuanya tentang optimasi parameter-hiper. Itu
adalah subjek yang sangat besar, dan bagaimanapun juga, itu bukanlah
masalah yang sepenuhnya diselesaikan, juga tidak ada kesepakatan
universal di antara para praktisi tentang strategi yang tepat untuk
digunakan. Selalu ada satu trik lagi yang bisa Anda coba untuk
meningkatkan kinerja dari jaringan Anda. Tetapi heuristik di bagian ini
harus membantu Anda memulai.

**Strategi luas:** Ketika menggunakan jaringan saraf (*neural networks*)
untuk menyerang masalah baru, tantangan pertama adalah mendapatkan
pembelajaran non-sepele, yaitu agar jaringan mencapai hasil yang lebih
baik daripada kebetulan. Ini bisa sangat sulit, terutama ketika
menghadapi kelas masalah baru. Mari kita lihat beberapa strategi yang
dapat Anda gunakan jika Anda mengalami masalah seperti ini.

Misalkan, misalnya, Anda menyerang MNIST untuk pertama kalinya. Anda
mulai antusias, tetapi sedikit berkecil hati ketika jaringan pertama
Anda gagal sepenuhnya, seperti dalam contoh di atas. Cara untuk pergi
adalah untuk menghilangkan masalah. Singkirkan semua gambar pelatihan
dan validasi kecuali gambar yang 0s atau 1s. Kemudian cobalah untuk
melatih jaringan untuk membedakan 0s dari 1s. Tidak hanya masalah yang
secara inheren lebih mudah daripada membedakan semua sepuluh digit, itu
juga mengurangi jumlah data pelatihan hingga 80 persen, mempercepat
pelatihan dengan faktor 5. Itu memungkinkan eksperimen yang jauh lebih
cepat, dan dengan demikian memberi Anda wawasan yang lebih cepat tentang
cara membangun jaringan yang baik.

Anda selanjutnya dapat mempercepat eksperimen dengan melepas jaringan
Anda ke jaringan yang paling sederhana yang mungkin melakukan
pembelajaran yang bermakna. Jika Anda yakin suatu jaringan \[784, 10\]
kemungkinan dapat melakukan klasifikasi digit MNIST yang lebih baik
daripada peluang, maka mulailah eksperimen Anda dengan jaringan
tersebut. Ini akan jauh lebih cepat daripada melatih jaringan \[784, 30,
10\] , dan Anda dapat membangun kembali hingga yang terakhir.

Anda bisa mendapatkan kecepatan lain dalam eksperimen dengan
meningkatkan frekuensi pemantauan. Di network2.py kami memantau kinerja
di akhir setiap zaman pelatihan. Dengan 50.000 gambar per zaman, itu
berarti menunggu sebentar - sekitar sepuluh detik per zaman, di laptop
saya, saat melatih jaringan \[784, 30, 10\] - sebelum mendapatkan umpan
balik tentang seberapa baik jaringan itu belajar. Tentu saja, sepuluh
detik tidak terlalu lama, tetapi jika Anda ingin mencoba puluhan pilihan
hiper-parameter itu menyebalkan, dan jika Anda ingin mencoba ratusan
atau ribuan pilihan, ia mulai melemahkan. Kami dapat memperoleh umpan
balik lebih cepat dengan memantau akurasi validasi lebih sering,
katakanlah, setelah setiap 1.000 gambar pelatihan. Selain itu, alih-alih
menggunakan 10.000 validasi gambar penuh yang diatur untuk memantau
kinerja, kita bisa mendapatkan perkiraan yang jauh lebih cepat
menggunakan hanya 100 gambar validasi. Yang penting adalah bahwa
jaringan melihat gambar yang cukup untuk melakukan pembelajaran nyata,
dan untuk mendapatkan perkiraan kinerja yang cukup baik. Of course, our
program network2.py doesn't currently do this kind of monitoring. But as
a kludge to achieve a similar effect for the purposes of illustration,
we'll strip down our training data to just the first 1,000 MNIST
training images. Let's try it and see what happens. (To keep the code
below simple I haven't implemented the idea of using only 0 and 1
images. Of course, that can be done with just a little more work.)

\>\>\> net = network2 . Network (\[ 784 , 10 \])

\>\>\> net . SGD ( training\_data \[: 1000 \], 30 , 10 , 10.0 , lmbda =
1000.0 , \\

... evaluation\_data = validation\_data \[: 100 \], \\

... monitor\_evaluation\_accuracy = True )

Epoch 0 training complete

Accuracy on evaluation data : 10 / 100

Epoch 1 training complete

Accuracy on evaluation data : 10 / 100

Epoch 2 training complete

Accuracy on evaluation data : 10 / 100

...

We're still getting pure noise\! But there's a big win: we're now
getting feedback in a fraction of a second, rather than once every ten
seconds or so. That means you can more quickly experiment with other
choices of hyper-parameter, or even conduct experiments trialling many
different choices of hyper-parameter nearly simultaneously.

In the above example I left λ as λ=1000.0, as we used earlier. But since
we changed the number of training examples we should really change λ to
keep the weight decay the same. That means changing λ to 20.0. If we do
that then this is what happens:

\>\>\> net = network2 . Network (\[ 784 , 10 \])

\>\>\> net . SGD ( training\_data \[: 1000 \], 30 , 10 , 10.0 , lmbda =
20.0 , \\

... evaluation\_data = validation\_data \[: 100 \], \\

... monitor\_evaluation\_accuracy = True )

Epoch 0 training complete

Accuracy on evaluation data : 12 / 100

Epoch 1 training complete

Accuracy on evaluation data : 14 / 100

Epoch 2 training complete

Accuracy on evaluation data : 25 / 100

Epoch 3 training complete

Accuracy on evaluation data : 18 / 100

...

Ah ah\! We have a signal. Not a terribly good signal, but a signal
nonetheless. That's something we can build on, modifying the
hyper-parameters to try to get further improvement. Maybe we guess that
our learning rate needs to be higher. (As you perhaps realize, that's a
silly guess, for reasons we'll discuss shortly, but please bear with
me.) So to test our guess we try dialing η up to 100.0:

\>\>\> net = network2 . Network (\[ 784 , 10 \])

\>\>\> net . SGD ( training\_data \[: 1000 \], 30 , 10 , 100.0 , lmbda =
20.0 , \\

... evaluation\_data = validation\_data \[: 100 \], \\

... monitor\_evaluation\_accuracy = True )

Epoch 0 training complete

Accuracy on evaluation data : 10 / 100

Epoch 1 training complete

Accuracy on evaluation data : 10 / 100

Epoch 2 training complete

Accuracy on evaluation data : 10 / 100

Epoch 3 training complete

Accuracy on evaluation data : 10 / 100

...

Itu tidak baik\! It suggests that our guess was wrong, and the problem
wasn't that the learning rate was too low. So instead we try dialing η
down to η=1.0:

\>\>\> net = network2 . Network (\[ 784 , 10 \])

\>\>\> net . SGD ( training\_data \[: 1000 \], 30 , 10 , 1.0 , lmbda =
20.0 , \\

... evaluation\_data = validation\_data \[: 100 \], \\

... monitor\_evaluation\_accuracy = True )

Epoch 0 training complete

Accuracy on evaluation data : 62 / 100

Epoch 1 training complete

Accuracy on evaluation data : 42 / 100

Epoch 2 training complete

Accuracy on evaluation data : 43 / 100

Epoch 3 training complete

Accuracy on evaluation data : 61 / 100

...

Itu lebih baik\! And so we can continue, individually adjusting each
hyper-parameter, gradually improving performance. Once we've explored to
find an improved value for η, then we move on to find a good value for
λ. Then experiment with a more complex architecture, say a network with
10 hidden neurons. Then adjust the values for η and λ again. Then
increase to 20 hidden neurons. And then adjust other hyper-parameters
some more. And so on, at each stage evaluating performance using our
held-out validation data, and using those evaluations to find better and
better hyper-parameters. As we do so, it typically takes longer to
witness the impact due to modifications of the hyper-parameters, and so
we can gradually decrease the frequency of monitoring.

This all looks very promising as a broad strategy. However, I want to
return to that initial stage of finding hyper-parameters that enable a
network to learn anything at all. In fact, even the above discussion
conveys too positive an outlook. It can be immensely frustrating to work
with a network that's learning nothing. You can tweak hyper-parameters
for days, and still get no meaningful response. And so I'd like to
re-emphasize that during the early stages you should make sure you can
get quick feedback from experiments. Intuitively, it may seem as though
simplifying the problem and the architecture will merely slow you down.
In fact, it speeds things up, since you much more quickly find a network
with a meaningful signal. Once you've got such a signal, you can often
get rapid improvements by tweaking the hyper-parameters. As with many
things in life, getting started can be the hardest thing to do.

Okay, that's the broad strategy. Let's now look at some specific
recommendations for setting hyper-parameters. I will focus on the
learning rate, η, the L2 regularization parameter, λ, and the mini-batch
size. However, many of the remarks apply also to other hyper-parameters,
including those associated to network architecture, other forms of
regularization, and some hyper-parameters we'll meet later in the book,
such as the momentum co-efficient.

**Learning rate:** Suppose we run three MNIST networks with three
different learning rates, η=0.025, η=0.25 and η=2.5, respectively. We'll
set the other hyper-parameters as for the experiments in earlier
sections, running over 30 epochs, with a mini-batch size of 10, and with
λ=5.0. We'll also return to using the full 50,000 training images.
Here's a graph showing the behaviour of the training cost as we train\*
\*The graph was generated by
[multiple\_eta.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/multiple_eta.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgt3S-VVN0bA6x1hOazFtHHm0SFGQ)
. :

![http://neuralnetworksanddeeplearning.com/images/multiple\_eta.png](media/image75.png)

Dengan  eta=0,025 biaya berkurang dengan lancar sampai zaman akhir.
Dengan  eta=0,25 biaya awalnya menurun, tetapi setelah sekitar 20 zaman
itu mendekati kejenuhan, dan setelah itu sebagian besar perubahan
hanyalah osilasi kecil dan tampaknya acak. Akhirnya, dengan  eta=2,5
biaya membuat osilasi besar langsung dari awal. Untuk memahami alasan
osilasi, ingat bahwa penurunan gradien stokastik seharusnya menurunkan
kita secara bertahap ke lembah fungsi biaya,

![http://neuralnetworksanddeeplearning.com/images/tikz33.png](media/image76.png)

Namun, jika  eta terlalu besar maka langkah-langkahnya akan sangat besar
sehingga mereka mungkin benar-benar melampaui batas minimum, menyebabkan
algoritma naik keluar dari lembah sebagai gantinya. Itu mungkin \* \*
Gambar ini bermanfaat, tetapi ini dimaksudkan sebagai ilustrasi
pembangun intuisi tentang apa yang mungkin terjadi, bukan sebagai
penjelasan yang lengkap dan menyeluruh. Secara singkat, penjelasan yang
lebih lengkap adalah sebagai berikut: gradient descent menggunakan
pendekatan orde pertama untuk fungsi biaya sebagai panduan cara
mengurangi biaya. Untuk  eta besar, persyaratan tingkat tinggi dalam
fungsi biaya menjadi lebih penting, dan mungkin mendominasi perilaku,
menyebabkan penurunan gradien turun. Ini sangat mungkin ketika kita
mendekati minima dan quasi-minima dari fungsi biaya, karena mendekati
titik-titik tersebut gradien menjadi kecil, sehingga lebih mudah untuk
istilah tingkat tinggi untuk mendominasi perilaku. apa yang menyebabkan
biaya terombang-ambing ketika  eta=2,5. Ketika kita memilih  eta=0,25
langkah-langkah awal memang membawa kita ke minimum fungsi biaya, dan
hanya sekali kita mendekati minimum itu kita mulai menderita masalah
overshooting. Dan ketika kita memilih  eta=0,025 kita tidak menderita
masalah ini sama sekali selama 30zaman pertama. Tentu saja, memilih  eta
sangat kecil menciptakan masalah lain, yaitu, bahwa itu memperlambat
penurunan gradien stokastik. Pendekatan yang lebih baik lagi adalah
mulai dengan  eta=0,25, latih untuk 20 zaman, dan kemudian beralih ke
 eta=0,025. Kami akan membahas jadwal tingkat pembelajaran variabel
tersebut nanti. Untuk saat ini, mari kita mencari tahu bagaimana
menemukan nilai bagus tunggal untuk tingkat pembelajaran,  eta.

Dengan mengingat gambar ini, kita dapat menetapkan  eta sebagai berikut.
Pertama, kami memperkirakan nilai ambang untuk  eta di mana biaya pada
data pelatihan segera mulai berkurang, bukannya berosilasi atau
meningkat. Perkiraan ini tidak perlu terlalu akurat. Anda dapat
memperkirakan urutan besarnya dengan mulai dengan  eta=0,01. Jika biaya
berkurang selama beberapa zaman pertama, maka Anda harus berturut-turut
mencoba  eta=0,1,1,0, ldots hingga Anda menemukan nilai untuk  eta di
mana biaya berosilasi atau meningkat selama beberapa zaman pertama.
Bergantian, jika biaya berosilasi atau meningkat selama beberapa zaman
pertama ketika  eta=0,01, maka coba  eta=0,001,0,0001, ldots hingga Anda
menemukan nilai untuk  eta di mana biaya berkurang selama beberapa zaman
pertama. Mengikuti prosedur ini akan memberi kami urutan estimasi
besarnya untuk nilai ambang eta $. Anda dapat memperbaiki estimasi Anda
secara opsional, untuk memilih nilai terbesar dari  eta di mana biaya
berkurang selama beberapa zaman pertama, katakanlah  eta=0,5 atau
 eta=0,2 (tidak perlu untuk ini untuk menjadi super-akurat). Ini
memberi kami perkiraan untuk nilai ambang eta $.

Jelas, nilai aktual  eta yang Anda gunakan tidak boleh lebih besar dari
nilai ambang. Faktanya, jika nilai  eta tetap dapat digunakan di banyak
zaman, maka Anda mungkin ingin menggunakan nilai untuk  eta yang lebih
kecil, katakanlah, faktor dua di bawah ambang batas. Pilihan seperti itu
biasanya akan memungkinkan Anda untuk berlatih di banyak zaman, tanpa
menyebabkan terlalu banyak kemunduran dalam belajar.

Dalam kasus data MNIST, mengikuti strategi ini mengarah ke perkiraan 0,1
untuk urutan besarnya nilai ambang eta $. Setelah perbaikan lagi, kami
memperoleh nilai ambang eta = 0,5 $. Mengikuti resep di atas, ini
menyarankan menggunakan  eta=0,25 sebagai nilai kami untuk tingkat
pembelajaran. Bahkan, saya menemukan bahwa menggunakan  eta=0,5 bekerja
cukup baik selama 30 zaman sehingga sebagian besar saya tidak khawatir
tentang menggunakan nilai yang lebih rendah dari  eta.

Ini semua tampaknya cukup mudah. Namun, menggunakan biaya pelatihan
untuk memilih  eta tampaknya bertentangan dengan apa yang saya katakan
sebelumnya di bagian ini, yaitu, bahwa kami akan memilih parameter-hiper
dengan mengevaluasi kinerja menggunakan data validasi yang kami
keluarkan. Faktanya, kita akan menggunakan akurasi validasi untuk
memilih parameter hiper regularisasi, ukuran mini-batch, dan parameter
jaringan seperti jumlah layer dan neuron tersembunyi, dan sebagainya.
Mengapa hal-hal berbeda untuk tingkat pembelajaran? Terus terang,
pilihan ini adalah preferensi estetika pribadi saya, dan mungkin agak
istimewa. Alasannya adalah bahwa parameter-hiper lainnya dimaksudkan
untuk meningkatkan akurasi klasifikasi akhir pada set tes, dan karenanya
masuk akal untuk memilihnya berdasarkan akurasi validasi. Namun, tingkat
pembelajaran hanya secara kebetulan dimaksudkan untuk mempengaruhi
akurasi klasifikasi akhir. Tujuan utamanya adalah untuk benar-benar
mengontrol ukuran langkah dalam gradient descent, dan memantau biaya
pelatihan adalah cara terbaik untuk mendeteksi jika ukuran langkah
terlalu besar. Dengan mengatakan itu, ini adalah preferensi estetika
pribadi. Sejak awal selama belajar, biaya pelatihan biasanya hanya
berkurang jika akurasi validasi meningkat, dan dalam praktiknya tidak
mungkin membuat banyak perbedaan kriteria mana yang Anda gunakan.

**Gunakan penghentian awal untuk menentukan jumlah zaman pelatihan:**
Seperti yang telah kita bahas sebelumnya dalam bab ini, penghentian awal
berarti bahwa pada akhir setiap zaman kita harus menghitung akurasi
klasifikasi pada data validasi. Ketika itu berhenti membaik, hentikan.
Ini membuat pengaturan jumlah zaman sangat sederhana. Secara khusus, ini
berarti bahwa kita tidak perlu khawatir tentang mencari tahu secara
eksplisit bagaimana jumlah zaman tergantung pada parameter-hiper
lainnya. Sebaliknya, itu ditangani secara otomatis. Selain itu,
penghentian dini juga secara otomatis mencegah kita dari overfitting.
Ini, tentu saja, adalah hal yang baik, meskipun pada tahap awal
eksperimen dapat membantu untuk mematikan penghentian awal, sehingga
Anda dapat melihat tanda-tanda overfitting, dan menggunakannya untuk
menginformasikan pendekatan Anda terhadap regularisasi.

Untuk menerapkan penghentian awal, kita perlu mengatakan lebih tepatnya
apa artinya bahwa ketepatan klasifikasi telah berhenti meningkat.
Seperti yang telah kita lihat, keakuratannya bisa melonjak sedikit,
bahkan ketika tren secara keseluruhan membaik. Jika kita berhenti
pertama kali keakuratannya menurun maka kita hampir pasti akan berhenti
ketika ada lebih banyak perbaikan yang bisa didapat. Aturan yang lebih
baik adalah untuk menghentikan jika akurasi klasifikasi terbaik tidak
membaik untuk beberapa waktu. Misalkan, misalnya, kita melakukan MNIST.
Maka kita mungkin memilih untuk mengakhiri jika akurasi klasifikasi
tidak meningkat selama sepuluh zaman terakhir. Ini memastikan bahwa kita
tidak berhenti terlalu cepat, sebagai tanggapan terhadap nasib buruk
dalam pelatihan, tetapi juga bahwa kita tidak menunggu selamanya untuk
perbaikan yang tidak pernah datang.

Aturan no-improvement-in-ten ini bagus untuk eksplorasi awal MNIST.
Namun, jaringan kadang-kadang dapat berada di dekat akurasi klasifikasi
tertentu untuk beberapa waktu, hanya untuk kemudian mulai membaik lagi.
Jika Anda mencoba untuk mendapatkan kinerja yang sangat baik, aturan
no-improvement-in-ten mungkin terlalu agresif untuk berhenti. Dalam hal
ini, saya sarankan menggunakan aturan no-improvement-in-ten untuk
eksperimen awal, dan secara bertahap mengadopsi aturan yang lebih lunak,
karena Anda lebih memahami cara jaringan Anda melatih:
no-improvement-in-twenty, no-improvement-in -lima puluh, dan seterusnya.
Tentu saja, ini memperkenalkan parameter-hiper baru untuk dioptimalkan\!
Namun dalam praktiknya, biasanya mudah untuk mengatur parameter-hiper
ini untuk mendapatkan hasil yang cukup bagus. Demikian pula, untuk
masalah selain MNIST, aturan no-improvement-in-ten mungkin terlalu
agresif atau tidak cukup agresif, tergantung pada detail masalah. Namun,
dengan sedikit eksperimen biasanya mudah menemukan strategi yang cukup
baik untuk berhenti lebih awal.

Kami belum menggunakan penghentian awal dalam percobaan MNIST kami
sampai saat ini. Alasannya adalah bahwa kami telah melakukan banyak
perbandingan antara berbagai pendekatan pembelajaran. Untuk perbandingan
seperti itu, sangat membantu untuk menggunakan jumlah zaman yang sama
dalam setiap kasus. Namun, perlu memodifikasi network2.py untuk
mengimplementasikan penghentian lebih awal:

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#problem_831601) 

  - Ubah network2.py sehingga mengimplementasikan penghentian awal
    menggunakan strategi no-improvement-in-n epochs, di mana n adalah
    parameter yang dapat diatur.

  - Bisakah Anda memikirkan aturan untuk berhenti lebih awal selain
    tidak ada perbaikan dalam n? Idealnya, aturan tersebut harus
    berkompromi antara mendapatkan akurasi validasi tinggi dan tidak
    berlatih terlalu lama. Tambahkan aturan Anda ke network2.py , dan
    jalankan tiga percobaan yang membandingkan akurasi validasi dan
    jumlah masa pelatihan hingga 10 tanpa perbaikan.

**Jadwal tingkat pembelajaran:** Kami telah mempertahankan tingkat
pembelajaran  eta konstan. Namun, sering kali menguntungkan untuk
memvariasikan tingkat pembelajaran. Sejak awal selama proses
pembelajaran, kemungkinan bobotnya sangat salah. Jadi, yang terbaik
adalah menggunakan tingkat pembelajaran yang besar yang menyebabkan
bobot berubah dengan cepat. Kemudian, kita dapat mengurangi tingkat
pembelajaran karena kita membuat penyesuaian yang lebih baik untuk bobot
kita.

Bagaimana seharusnya kita mengatur jadwal tingkat belajar kita? Banyak
pendekatan yang mungkin dilakukan. Salah satu pendekatan alami adalah
menggunakan ide dasar yang sama dengan penghentian dini. Idenya adalah
untuk mempertahankan tingkat pembelajaran konstan sampai akurasi
validasi mulai memburuk. Kemudian kurangi tingkat belajar dengan jumlah
tertentu, katakan faktor dua atau sepuluh. Kami mengulangi ini
berkali-kali, sampai, katakanlah, tingkat pembelajaran adalah faktor
1,024 (atau 1.000) kali lebih rendah dari nilai awal. Lalu kami
mengakhiri.

Jadwal belajar yang bervariasi dapat meningkatkan kinerja, tetapi juga
membuka dunia pilihan yang memungkinkan untuk jadwal belajar.
Pilihan-pilihan itu bisa menjadi sakit kepala - Anda dapat menghabiskan
waktu selamanya untuk mencoba mengoptimalkan jadwal belajar Anda. Untuk
percobaan pertama, saran saya adalah menggunakan nilai tunggal yang
konstan untuk tingkat pembelajaran. Itu akan memberi Anda perkiraan
pertama yang baik. Kemudian, jika Anda ingin mendapatkan kinerja terbaik
dari jaringan Anda, ada baiknya bereksperimen dengan jadwal belajar, di
sepanjang baris yang saya jelaskan \* \* Makalah baru-baru ini dapat
dibaca yang menunjukkan manfaat dari tingkat belajar variabel dalam
menyerang MNIST adalah [Deep, Big , Excel Neural Nets Sederhana pada
Pengenalan Digit Tulisan Tangan](http://arxiv.org/abs/1003.0358) , oleh
Dan Claudiu Cireșan, Ueli Meier, Luca Maria Gambardella, dan Jürgen
Schmidhuber (2010). .

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_336628) 

  - Ubah network2.py sehingga mengimplementasikan jadwal pembelajaran
    yang: membagi dua tingkat pembelajaran setiap kali keakuratan
    validasi memenuhi aturan no-improvement-in- 10; dan berakhir ketika
    tingkat pembelajaran turun menjadi 1/128 dari nilai aslinya.

**Parameter regularisasi,  lambda:** Saya sarankan memulai awalnya tanpa
regularisasi ( lambda=0,0), dan menentukan nilai untuk  eta, seperti di
atas. Dengan menggunakan pilihan  eta, kita dapat menggunakan data
validasi untuk memilih nilai yang baik untuk  lambda. Mulailah dengan
menguji coba  lambda=1.0 \* \* Saya tidak memiliki justifikasi
berprinsip yang baik untuk menggunakan ini sebagai nilai awal. Jika ada
yang tahu tentang diskusi berprinsip yang baik dari mana harus mulai
dengan  lambda, saya akan senang mendengarnya (mn@michaelnielsen.org). ,
dan kemudian naik atau turun dengan faktor 10, sesuai kebutuhan untuk
meningkatkan kinerja pada data validasi. Setelah Anda menemukan urutan
besarnya yang baik, Anda dapat menyesuaikan nilai Anda sebesar  lambda.
Setelah selesai, Anda harus kembali dan mengoptimalkan kembali  eta
lagi.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_281746) 

  - Sangat tergoda untuk menggunakan gradient descent untuk mencoba
    mempelajari nilai-nilai bagus untuk parameter-hyper seperti  lambda
    dan  eta. Bisakah Anda memikirkan hambatan untuk menggunakan
    gradient descent untuk menentukan  lambda? Bisakah Anda memikirkan
    hambatan untuk menggunakan gradient descent untuk menentukan  eta?

**Bagaimana saya memilih hiper-parameter sebelumnya dalam buku ini:**
Jika Anda menggunakan rekomendasi di bagian ini Anda akan menemukan
bahwa Anda mendapatkan nilai untuk  eta dan  lambda yang tidak selalu
sama persis dengan nilai yang saya gunakan sebelumnya dalam buku ini.
Alasannya adalah bahwa buku ini memiliki kendala naratif yang terkadang
membuatnya tidak praktis untuk mengoptimalkan parameter-hiper. Pikirkan
semua perbandingan yang telah kami buat dari berbagai pendekatan
pembelajaran, misalnya, membandingkan fungsi biaya kuadratik dan
lintas-entropi, membandingkan metode inisialisasi bobot yang lama dan
baru, berjalan dengan dan tanpa regularisasi, dan sebagainya. Untuk
membuat perbandingan seperti itu bermakna, saya biasanya mencoba menjaga
hiper-parameter konstan di seluruh pendekatan yang dibandingkan (atau
menskalakannya dengan cara yang sesuai). Tentu saja, tidak ada alasan
untuk parameter-hiper yang sama menjadi optimal untuk semua pendekatan
pembelajaran yang berbeda, jadi parameter-hiper yang saya gunakan adalah
sesuatu yang kompromi.

Sebagai alternatif untuk kompromi ini, saya bisa mencoba untuk
mengoptimalkan parameter-parameter untuk setiap pendekatan pembelajaran.
Pada prinsipnya itu akan menjadi pendekatan yang lebih baik, lebih adil,
sejak itu kita akan melihat yang terbaik dari setiap pendekatan untuk
belajar. Namun, kami telah membuat puluhan perbandingan di sepanjang
garis ini, dan dalam praktiknya saya menganggapnya terlalu mahal secara
komputasi. Itu sebabnya saya mengadopsi kompromi untuk menggunakan
pilihan yang cukup bagus (tapi belum tentu optimal) untuk
parameter-hyper.

**Ukuran mini-batch:** Bagaimana kita mengatur ukuran mini-batch? Untuk
menjawab pertanyaan ini, pertama mari kita anggap kita melakukan
pembelajaran online, yaitu, bahwa kita menggunakan ukuran mini-batch 1.

Kekhawatiran yang jelas tentang pembelajaran online adalah bahwa
menggunakan mini-batch yang hanya berisi satu contoh pelatihan akan
menyebabkan kesalahan signifikan dalam estimasi gradien kami. Namun
faktanya, kesalahan itu ternyata bukan masalah. Alasannya adalah bahwa
estimasi gradien individu tidak perlu super-akurat. Yang kita butuhkan
hanyalah perkiraan yang cukup akurat sehingga fungsi biaya kita
cenderung terus menurun. Seolah-olah Anda mencoba untuk sampai ke Kutub
Magnetik Utara, tetapi memiliki kompas miring yang 10-20 derajat setiap
kali Anda melihatnya. Asalkan Anda berhenti untuk sering memeriksa
kompas, dan kompas mendapatkan arah yang benar-benar rata, Anda akan
berakhir di Kutub Utara Magnetik dengan baik.

Berdasarkan argumen ini, sepertinya kita harus menggunakan pembelajaran
online. Faktanya, situasinya ternyata lebih rumit dari itu. Dalam
[masalah di bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#backprop_over_minibatch)
saya menunjukkan bahwa dimungkinkan untuk menggunakan teknik matriks
untuk menghitung pembaruan gradien untuk *semua* contoh dalam batch mini
secara bersamaan, daripada mengulanginya. Bergantung pada perincian
perangkat keras dan pustaka aljabar linier Anda, ini dapat membuatnya
sedikit lebih cepat untuk menghitung estimasi gradien untuk mini-batch
ukuran (misalnya)
100,daripadamenghitungestimasigradienmini−batchdenganmengulangicontohpelatihan
100 $ secara terpisah. Mungkin butuh (katakanlah) hanya 50 kali lebih
lama, daripada 100 kali lebih lama.

Sekarang, pada awalnya sepertinya ini tidak banyak membantu kita. Dengan
mini-batch kami ukuran 100 aturan pembelajaran untuk bobot terlihat
seperti: \\ begin {eqnarray} w \\ rightarrow w '= w- \\ eta \\ frac {1}
{100} \\ sum\_x \\ nabla C\_x, \\ tag {100} \\ end {eqnarray} di mana
jumlah tersebut melebihi contoh pelatihan dalam mini- batch Ini versus
\\ begin {eqnarray} w \\ rightarrow w '= w- \\ eta \\ nabla C\_x \\ tag
{101} \\ end {eqnarray} untuk pembelajaran online. Bahkan jika hanya
membutuhkan $ 50 kali selama melakukan pembaruan mini-batch, sepertinya
masih lebih baik untuk melakukan pembelajaran online, karena kami akan
memperbarui jauh lebih sering. Namun, anggaplah bahwa dalam kasus
mini-batch kami meningkatkan tingkat pembelajaran dengan faktor $ 100,
sehingga aturan pembaruan menjadi \\ begin {eqnarray} w \\ rightarrow w
'= w- \\ eta \\ sum\_x \\ nabla C\_x. \\ tag {102} \\ end {eqnarray} Itu
sangat mirip dengan melakukan 100 pembelajaran online terpisah dengan
tingkat pembelajaran  eta. Tetapi hanya membutuhkan $ 50 kali selama
melakukan satu contoh pembelajaran online. Tentu saja, itu tidak
benar-benar sama dengan 100 contoh pembelajaran online, karena dalam
mini-batch nabla C\_x $ semuanya dievaluasi untuk set bobot yang sama,
sebagai lawan dari pembelajaran kumulatif yang terjadi di kasing online.
Namun, tampaknya sangat mungkin bahwa menggunakan mini-batch yang lebih
besar akan mempercepat.

Dengan mempertimbangkan faktor-faktor ini, memilih ukuran mini-batch
terbaik adalah kompromi. Terlalu kecil, dan Anda tidak bisa memanfaatkan
sepenuhnya manfaat pustaka matriks yang baik yang dioptimalkan untuk
perangkat keras yang cepat. Terlalu besar dan Anda tidak cukup sering
memperbarui bobot Anda. Yang Anda butuhkan adalah memilih nilai kompromi
yang memaksimalkan kecepatan belajar. Untungnya, pilihan ukuran
mini-batch di mana kecepatan dimaksimalkan relatif independen dari
parameter-hiper lainnya (terlepas dari arsitektur keseluruhan), sehingga
Anda tidak perlu mengoptimalkan parameter-parameter hiper untuk
menemukan ukuran mini-batch yang bagus. Oleh karena itu, cara untuk
pergi adalah menggunakan beberapa nilai yang dapat diterima (tetapi
tidak harus optimal) untuk parameter-parameter hiper lainnya, dan
kemudian mencoba sejumlah ukuran mini-batch yang berbeda, menskalakan
 eta seperti di atas. Plot akurasi validasi versus *waktu* (seperti
dalam, waktu berlalu sebenarnya, bukan zaman\!), Dan pilih ukuran
mini-batch mana saja yang memberi Anda peningkatan kinerja paling cepat.
Dengan ukuran mini-batch yang dipilih, Anda dapat melanjutkan untuk
mengoptimalkan parameter-hiper lainnya.

Tentu saja, seperti yang Anda sadari, saya belum melakukan optimasi ini
dalam pekerjaan kami. Memang, implementasi kami tidak menggunakan
pendekatan yang lebih cepat untuk pembaruan mini-batch sama sekali. Saya
hanya menggunakan ukuran mini-batch 10 tanpa komentar atau penjelasan di
hampir semua contoh. Karena itu, kita bisa mempercepat pembelajaran
dengan mengurangi ukuran mini-batch. Saya belum melakukan ini, sebagian
karena saya ingin mengilustrasikan penggunaan mini-batch melebihi ukuran
1, dan sebagian karena percobaan awal saya menyarankan speedup akan agak
sederhana. Namun, dalam implementasi praktis, kami pasti akan menerapkan
pendekatan yang lebih cepat untuk pembaruan mini-batch, dan kemudian
berupaya mengoptimalkan ukuran mini-batch, untuk memaksimalkan kecepatan
kami secara keseluruhan.

**Teknik otomatis:** Saya telah menggambarkan heuristik ini seolah-olah
Anda mengoptimalkan parameter hiper Anda dengan tangan. Optimalisasi
tangan adalah cara yang baik untuk membangun perasaan tentang bagaimana
jaringan saraf (*neural networks*) berperilaku. Namun, dan tidak
mengejutkan, banyak pekerjaan telah dilakukan untuk mengotomatisasi
proses. Teknik yang umum adalah *pencarian kisi* , yang mencari secara
sistematis melalui kisi di ruang hyper-parameter. Tinjauan tentang
pencapaian dan keterbatasan pencarian grid (dengan saran untuk
alternatif yang mudah diimplementasikan) dapat ditemukan dalam makalah
2012 \* \* [Pencarian acak untuk optimasi
parameter-hiper](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://dl.acm.org/citation.cfm%3Fid%3D2188395&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjTZAePfcgZYlwdIs4jpgEestbEmA)
, oleh James Bergstra dan Yoshua Bengio (2012). oleh James Bergstra dan
Yoshua Bengio. Banyak pendekatan yang lebih canggih juga telah
diusulkan. Saya tidak akan meninjau semua pekerjaan di sini, tetapi
ingin menyebutkan makalah 2012 yang sangat menjanjikan yang menggunakan
pendekatan Bayesian untuk secara otomatis mengoptimalkan hyper-parameter
\* \* [Praktis Bayesian optimasi algoritma pembelajaran
mesin](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-learning-algorithms.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgq8xGgUIhhMotB5m--Q1cibKJSHg)
, oleh Jasper Snoek, Hugo Larochelle, dan Ryan Adams. . Kode dari
makalah ini [tersedia untuk
umum](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/jaberg/hyperopt&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg171FTi355kEPNML6U_lPXgfwaQA)
, dan telah digunakan dengan beberapa keberhasilan oleh peneliti lain.

**Kesimpulannya:** Mengikuti aturan praktis yang saya jelaskan tidak
akan memberi Anda hasil terbaik semaksimal mungkin dari *jaringan saraf
(neural networks)* Anda. Tapi itu mungkin akan memberi Anda awal yang
baik dan dasar untuk perbaikan lebih lanjut. Secara khusus, saya telah
membahas parameter hiper sebagian besar secara independen. Dalam
praktiknya, ada hubungan antara parameter-hiper. Anda dapat
bereksperimen dengan  eta, merasa bahwa Anda telah melakukannya dengan
benar, kemudian mulai untuk mengoptimalkan untuk  lambda, hanya untuk
menemukan bahwa itu mengacaukan optimasi Anda untuk  eta. Dalam
praktiknya, ini membantu untuk memantul ke belakang dan ke depan, secara
bertahap mendekati nilai-nilai yang baik. Di atas semua itu, perlu
diingat bahwa heuristik yang saya jelaskan adalah aturan praktis, bukan
aturan yang dilemparkan ke batu. Anda harus waspada terhadap tanda-tanda
bahwa segala sesuatu tidak berfungsi, dan bersedia untuk bereksperimen.
Secara khusus, ini berarti memonitor dengan cermat perilaku jaringan
Anda, terutama keakuratan validasinya.

Kesulitan memilih parameter-hyper diperburuk oleh fakta bahwa
pengetahuan tentang bagaimana memilih parameter-hyper tersebar luas, di
banyak makalah penelitian dan program perangkat lunak, dan seringkali
hanya tersedia di dalam kepala praktisi individu. Ada banyak, banyak
makalah yang menjabarkan (kadang-kadang kontradiktif) rekomendasi untuk
bagaimana melanjutkan. Namun, ada beberapa makalah yang sangat berguna
yang mensintesis dan menyaring banyak pengetahuan ini. Yoshua Bengio
memiliki makalah 2012 \* \* [Rekomendasi praktis untuk pelatihan
berbasis arsitektur gradien](http://arxiv.org/abs/1206.5533) , oleh
Yoshua Bengio (2012). yang memberikan beberapa rekomendasi praktis untuk
menggunakan backpropagation dan gradient descent untuk melatih jaringan
saraf, termasuk jaring saraf yang dalam. Bengio membahas banyak masalah
dengan lebih detail daripada yang saya miliki, termasuk bagaimana
melakukan pencarian hiper-parameter yang lebih sistematis. Makalah bagus
lainnya adalah makalah tahun 1998 \* \* [BackProp
Efisien](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7krQ9ckyTEee78DYEPaCT_4ZSNA)
, oleh Yann LeCun, Léon Bottou, Genevieve Orr dan Klaus-Robert Müller
(1998) oleh Yann LeCun, Léon Bottou, Léon Bottou, Genevieve Orr dan
Klaus-Robert Müller. Kedua makalah ini muncul dalam buku 2012 yang
sangat berguna yang mengumpulkan banyak trik yang biasa digunakan dalam
jaring saraf \* \* [Jaringan Saraf: Trik
Perdagangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.springer.com/computer/theoretical%2Bcomputer%2Bscience/book/978-3-642-35288-1&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjtzxInX_vUyPzGdQuAG6mgvXinWg)
, diedit oleh Grégoire Montavon, Geneviève Orr, dan Klaus-Robert Müller.
. Buku itu mahal, tetapi banyak artikel telah ditempatkan secara online
oleh penulis masing-masing dengan, satu anggapan, berkah dari penerbit,
dan dapat ditemukan menggunakan mesin pencari.

Satu hal yang menjadi jelas ketika Anda membaca artikel-artikel ini dan,
terutama, ketika Anda terlibat dalam percobaan Anda sendiri, adalah
bahwa optimasi hyper-parameter bukanlah masalah yang pernah sepenuhnya
diselesaikan. Selalu ada trik lain yang dapat Anda coba untuk
meningkatkan kinerja. Ada pepatah umum di kalangan penulis bahwa buku
tidak pernah selesai, hanya ditinggalkan. Hal yang sama juga berlaku
untuk optimasi jaringan saraf: ruang parameter-hiper begitu besar
sehingga orang tidak pernah benar-benar selesai mengoptimalkan, orang
hanya meninggalkan jaringan untuk anak cucu. Jadi, tujuan Anda adalah
mengembangkan alur kerja yang memungkinkan Anda melakukan pekerjaan
optimasi dengan cukup baik, sambil memberi Anda fleksibilitas untuk
mencoba optimasi yang lebih terperinci, jika itu penting.

Tantangan pengaturan hyper-parameter telah membuat beberapa orang
mengeluh bahwa jaringan saraf (*neural networks*) membutuhkan banyak
pekerjaan bila dibandingkan dengan teknik pembelajaran mesin lainnya.
Saya telah mendengar banyak variasi pada keluhan berikut: "Ya, *jaringan
saraf (neural networks)* yang ditala dengan baik mungkin mendapatkan
kinerja terbaik pada masalah tersebut. Di sisi lain, saya dapat mencoba
hutan acak \[atau SVM atau  ldots masukkan Anda punya teknik favorit\]
dan itu hanya berhasil. Saya tidak punya waktu untuk mencari tahu
jaringan saraf (*neural networks*) yang tepat. " Tentu saja, dari sudut
pandang praktis, ada baiknya memiliki teknik yang mudah diterapkan. Ini
terutama benar ketika Anda baru memulai masalah, dan mungkin tidak jelas
apakah pembelajaran mesin dapat membantu memecahkan masalah sama sekali.
Di sisi lain, jika mendapatkan kinerja optimal adalah penting, maka Anda
mungkin perlu mencoba pendekatan yang membutuhkan pengetahuan khusus.
Meskipun alangkah baiknya jika pembelajaran mesin selalu mudah, tidak
ada alasan *apriori* itu harus sederhana.

### [Teknik lainnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques) 

Setiap teknik yang dikembangkan dalam bab ini berharga untuk diketahui
sendiri, tetapi itu bukan satu-satunya alasan saya menjelaskannya. Poin
yang lebih besar adalah membiasakan Anda dengan beberapa masalah yang
dapat terjadi dalam jaringan saraf, dan dengan gaya analisis yang dapat
membantu mengatasi masalah tersebut. Dalam arti tertentu, kami telah
belajar cara berpikir tentang jaring saraf. Selama sisa bab ini saya
secara singkat membuat sketsa beberapa teknik lainnya. Sketsa ini kurang
mendalam daripada diskusi sebelumnya, tetapi harus menyampaikan perasaan
untuk keragaman teknik yang tersedia untuk digunakan dalam jaringan
saraf.

#### [Variasi pada penurunan gradien stokastik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#variations_on_stochastic_gradient_descent) 

Penurunan gradien stokastik oleh backpropagation telah membantu kami
dengan baik dalam menyerang masalah klasifikasi digit MNIST. Namun, ada
banyak pendekatan lain untuk mengoptimalkan fungsi biaya, dan
kadang-kadang pendekatan-pendekatan lain menawarkan kinerja lebih unggul
daripada keturunan gradien stokastik stok-mini. Pada bagian ini saya
membuat sketsa dua pendekatan seperti itu, teknik Goni dan momentum.

**Teknik Hessian:** Untuk memulai diskusi kita, ada baiknya kita
mengesampingkan jaringan saraf (*neural networks*) sebentar. Sebagai
gantinya, kita hanya akan mempertimbangkan masalah abstrak dari
meminimalkan fungsi biaya C yang merupakan fungsi dari banyak variabel,
w=w1,w2, ldots, jadi C=C(w). Dengan teorema Taylor, fungsi biaya dapat
diperkirakan mendekati titik w pada \\ begin {eqnarray} C (w + \\ Delta
w) & = & C (w) + \\ sum\_j \\ frac {\\ parsial C} {\\ partial w\_j} \\
Delta w\_j \\ bukan nomor \\\\ & & + frac {1} { 2} \\ sum\_ {jk} \\
Delta w\_j \\ frac {\\ partial ^ 2 C} {\\ partial w\_j \\ partial w\_k}
\\ Delta w\_k + \\ ldots \\ tag {103} \\ end {eqnarray} Kita dapat
menulis ulang ini dengan lebih kompak sebagai \\ begin {eqnarray} C (w +
\\ Delta w) = C (w) + \\ nabla C \\ cdot \\ Delta w + \\ frac {1} {2} \\
Delta w ^ TH \\ Delta w + \\ ldots, \\ tag { 104} \\ end {eqnarray} di
mana  nablaC adalah vektor gradien biasa, dan H adalah matriks yang
dikenal sebagai *matriks Hessian* , yang entri jk th adalah
 partial2C/ partialwj sebagianwk. Misalkan kita memperkirakan C dengan
membuang persyaratan tingkat tinggi yang diwakili oleh  ldots di atas,
\\ begin {eqnarray} C (w + \\ Delta w) \\ approx C (w) + \\ nabla C \\
cdot \\ Delta w + \\ frac {1} {2} \\ Delta w ^ TH \\ Delta w. \\ tag
{105} \\ end {eqnarray} Dengan menggunakan kalkulus kita dapat
menunjukkan bahwa ekspresi di sisi kanan dapat diminimalisasi \* \*
Sebenarnya, untuk ini menjadi minimum, dan bukan hanya ekstrem, kita
perlu mengasumsikan bahwa matriks Hessian adalah definitif positif.
Secara intuitif, ini berarti bahwa fungsi C terlihat seperti lembah
lokal, bukan gunung atau pelana. dengan memilih \\ begin {eqnarray} \\
Delta w = -H ^ {- 1} \\ nabla C. \\ tag {106} \\ end {eqnarray}
Disediakan (105) adalah ekspresi perkiraan yang baik untuk fungsi biaya,
maka kami berharap bahwa beralih dari titik w ke w+ Deltaw=wH−1 nablaC
akan secara signifikan mengurangi fungsi biaya. Itu menunjukkan
kemungkinan algoritma untuk meminimalkan biaya:

  - Pilih titik awal, w.

  - Perbarui w ke titik baru w′=wH−1 nablaC, di mana Hessian H dan
     nablaC dihitung pada w.

  - Perbarui w′ ke titik baru w′′=w′−H′−1 nabla′C, di mana H H' dan \\
    nabla 'C dihitungdengan w '$.

  -  ldots

Dalam praktiknya, (105) hanyalah perkiraan, dan lebih baik mengambil
langkah yang lebih kecil. Kami melakukan ini dengan berulang kali
mengubah w dengan jumlah  Deltaw=− etaH−1 nablaC, di mana  eta dikenal
sebagai tingkat *pembelajaran* .

Pendekatan ini untuk meminimalkan fungsi biaya dikenal sebagai *teknik*
*Hessian* atau *optimasi Hessian* . Ada hasil teoritis dan empiris yang
menunjukkan bahwa metode Hessian bertemu pada langkah minimum yang lebih
sedikit daripada penurunan gradien standar. Secara khusus, dengan
memasukkan informasi tentang perubahan orde kedua dalam fungsi biaya,
dimungkinkan untuk pendekatan Hessian untuk menghindari banyak patologi
yang dapat terjadi pada gradient descent. Selain itu, ada versi
algoritma backpropagation yang dapat digunakan untuk menghitung Hessian.

Jika optimasi Hessian begitu hebat, mengapa kita tidak menggunakannya di
jaringan saraf (*neural networks*) kita? Sayangnya, meski memiliki
banyak properti yang diinginkan, ia memiliki satu properti yang sangat
tidak diinginkan: sangat sulit untuk diterapkan dalam praktik. Bagian
dari masalahnya adalah ukuran tipis dari matriks Hessian. Misalkan Anda
memiliki jaringan saraf (*neural networks*) dengan bobot dan bias 107.
Kemudian matriks Hessian yang sesuai akan berisi 107 kali107=1014 entri.
Itu banyak entri\! Dan itu membuat komputasi H−1 nablaC sangat sulit
dalam prakteknya. Namun, itu tidak berarti bahwa itu tidak berguna untuk
dipahami. Sebenarnya, ada banyak variasi pada gradient descent yang
terinspirasi oleh optimisasi Hessian, tetapi yang menghindari masalah
dengan matriks yang terlalu besar. Mari kita lihat satu teknik seperti
itu, gradient descent berbasis momentum.

**Turunnya gradien berbasis momen:** Secara intuitif, keuntungan yang
dimiliki optimisasi Hessian adalah bahwa ia tidak hanya memasukkan
informasi tentang gradien, tetapi juga informasi tentang bagaimana
perubahan gradien. Turunan gradien berbasis momen didasarkan pada
intuisi yang sama, tetapi menghindari matriks besar turunan kedua. Untuk
memahami teknik momentum, pikirkan kembali [gambaran
asli](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#gradient_descent)
kami tentang gradient descent, di mana kami menganggap bola bergulir ke
lembah. Pada saat itu, kami mengamati bahwa gradient descent, terlepas
dari namanya, hanya sedikit mirip dengan bola yang jatuh ke dasar
lembah. Teknik momentum memodifikasi gradient descent dengan dua cara
yang membuatnya lebih mirip dengan gambar fisik. Pertama, ini
memperkenalkan gagasan "kecepatan" untuk parameter yang kami coba
optimalkan. Gradien bertindak untuk mengubah kecepatan, bukan (langsung)
"posisi", dalam banyak cara yang sama seperti kekuatan fisik mengubah
kecepatan, dan hanya secara tidak langsung mempengaruhi posisi. Kedua,
metode momentum memperkenalkan semacam istilah gesekan, yang cenderung
mengurangi kecepatan secara bertahap.

Mari kita berikan deskripsi matematis yang lebih tepat. Kami
memperkenalkan variabel kecepatan v=v1,v2, ldots, satu untuk setiap wj
variabel yang sesuai \* \* Dalam neural net, variabel wj tentu saja akan
mencakup semua bobot dan bias. . Kemudian kita mengganti aturan
pembaruan gradient descent w rightarroww′=w− eta nablaC oleh \\ begin
{eqnarray} v & \\ rightarrow & v '= \\ mu v - \\ eta \\ nabla C \\ tag
{107} \\\\ w & \\ rightarrow & w' = w + v '. \\ tag {108} \\ end
{eqnarray} Dalam persamaan ini,  mu adalah parameter-hiper yang
mengontrol jumlah redaman atau gesekan dalam sistem. Untuk memahami arti
dari persamaan, ada baiknya untuk terlebih dahulu mempertimbangkan kasus
di mana  mu=1, yang sesuai dengan tidak ada gesekan. Ketika itu terjadi,
pemeriksaan persamaan menunjukkan bahwa "gaya"  nablaC sekarang
memodifikasi kecepatan, v, dan kecepatan mengendalikan laju perubahan w.
Secara intuitif, kami membangun kecepatan dengan berulang kali
menambahkan istilah gradien ke dalamnya. Itu berarti bahwa jika gradien
berada dalam (kira-kira) arah yang sama melalui beberapa putaran
pembelajaran, kita dapat membangun sedikit uap bergerak ke arah itu.
Pikirkan, misalnya, tentang apa yang terjadi jika kita bergerak lurus ke
bawah:

![http://neuralnetworksanddeeplearning.com/images/tikz34.png](media/image76.png)

Dengan setiap langkah, kecepatan semakin besar menuruni lereng, jadi
kami bergerak semakin cepat ke dasar lembah. Ini dapat memungkinkan
teknik momentum bekerja lebih cepat daripada penurunan gradien standar.
Tentu saja, masalahnya adalah begitu kita mencapai dasar lembah, kita
akan melampaui batas. Atau, jika gradien berubah dengan cepat, maka kita
bisa menemukan diri kita bergerak ke arah yang salah. That's the reason
for the μ hyper-parameter in (107) . I said earlier that μ controls the
amount of friction in the system; to be a little more precise, you
should think of 1−μ as the amount of friction in the system. When μ=1,
as we've seen, there is no friction, and the velocity is completely
driven by the gradient ∇C. By contrast, when μ=0 there's a lot of
friction, the velocity can't build up, and Equations (107) and (108)
reduce to the usual equation for gradient descent, w→w′=w−η∇C. In
practice, using a value of μ intermediate between 0 and 1 can give us
much of the benefit of being able to build up speed, but without causing
overshooting. We can choose such a value for μ using the held-out
validation data, in much the same way as we select η and λ.

I've avoided naming the hyper-parameter μ up to now. The reason is that
the standard name for μ is badly chosen: it's called the *momentum
co-efficient* . This is potentially confusing, since μ is not at all the
same as the notion of momentum from physics. Rather, it is much more
closely related to friction. However, the term momentum co-efficient is
widely used, so we will continue to use it.

A nice thing about the momentum technique is that it takes almost no
work to modify an implementation of gradient descent to incorporate
momentum. We can still use backpropagation to compute the gradients,
just as before, and use ideas such as sampling stochastically chosen
mini-batches. In this way, we can get some of the advantages of the
Hessian technique, using information about how the gradient is changing.
But it's done without the disadvantages, and with only minor
modifications to our code. In practice, the momentum technique is
commonly used, and often speeds up learning.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#exercise_603875) 

  - What would go wrong if we used μ\>1 in the momentum technique?

  - Apa yang salah jika kami menggunakan  mu\<0 dalam teknik momentum?

#### [Masalah](http://neuralnetworksanddeeplearning.com/chap3.html#problem_713937) 

  - Tambahkan penurunan gradien stokastik berbasis momentum ke
    network2.py .

**Pendekatan lain untuk meminimalkan fungsi biaya:** Banyak pendekatan
lain untuk meminimalkan fungsi biaya telah dikembangkan, dan tidak ada
kesepakatan universal yang merupakan pendekatan terbaik. Saat Anda masuk
lebih dalam ke jaringan saraf, ada baiknya menggali teknik lain,
memahami cara kerjanya, kekuatan dan kelemahannya, dan cara
menerapkannya dalam praktik. Sebuah makalah yang saya sebutkan
sebelumnya \* \* [Efisien
BackProp](http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf) , oleh
Yann LeCun, Léon Bottou, Genevieve Orr dan Klaus-Robert Müller (1998).
memperkenalkan dan membandingkan beberapa teknik ini, termasuk penurunan
gradien konjugat dan metode BFGS (lihat juga metode BFGS memori terbatas
terkait erat, yang dikenal sebagai
[L-BFGS](http://en.wikipedia.org/wiki/Limited-memory_BFGS) ). Teknik
lain yang baru-baru ini menunjukkan hasil yang menjanjikan. \* Lihat,
misalnya, [tentang pentingnya inisialisasi dan momentum dalam
*pembelajaran dalam (deep
learning)*](http://www.cs.toronto.edu/~hinton/absps/momentum.pdf) , oleh
Ilya Sutskever, James Martens, George Dahl, dan Geoffrey Hinton (2012).
adalah teknik gradien yang dipercepat Nesterov, yang meningkatkan teknik
momentum. Namun, untuk banyak masalah, penurunan gradien stokastik polos
berfungsi dengan baik, terutama jika momentum digunakan, dan karenanya
kami akan tetap berpegang pada penurunan gradien stokastik melalui sisa
buku ini.

#### [Model lain dari neuron buatan](http://neuralnetworksanddeeplearning.com/chap3.html#other_models_of_artificial_neuron) 

Hingga kini kami telah membangun jaringan saraf (*neural networks*) kami
menggunakan neuron sigmoid. Pada prinsipnya, jaringan yang dibangun dari
neuron sigmoid dapat menghitung fungsi apa pun. Namun dalam praktiknya,
jaringan yang dibangun menggunakan model neuron lain kadang-kadang
mengungguli jaringan sigmoid. Tergantung pada aplikasinya, jaringan yang
didasarkan pada model alternatif semacam itu dapat belajar lebih cepat,
menggeneralisasi lebih baik untuk menguji data, atau mungkin melakukan
keduanya. Izinkan saya menyebutkan beberapa neuron model alternatif,
untuk memberi Anda rasa beberapa variasi yang umum digunakan.

Mungkin variasi paling sederhana adalah neuron tanh (diucapkan "tanch"),
yang menggantikan fungsi sigmoid dengan fungsi tangen hiperbolik. Output
dari neuron tanh dengan input x, vektor berat w, dan bias b diberikan
oleh \\ begin {eqnarray} \\ tanh (w \\ cdot x + b), \\ tag {109} \\ end
{eqnarray} di mana  tanh adalah, tentu saja, fungsi tangen hiperbolik.
Ternyata ini sangat erat kaitannya dengan neuron sigmoid. Untuk melihat
ini, ingat bahwa fungsi  tanh ditentukan oleh \\ begin {eqnarray} \\
tanh (z) \\ equiv \\ frac {e ^ ze ^ {- z}} {e ^ z + e ^ {- z}}. \\ tag
{110} \\ end {eqnarray} Dengan sedikit aljabar, dapat dengan mudah
diverifikasi \\ begin {eqnarray} \\ sigma (z) = \\ frac {1+ \\ tanh (z /
2)} {2}, \\ tag {111} \\ end {eqnarray} yaitu,  tanh hanyalah versi yang
diskala ulang dari fungsi sigmoid. Kita juga dapat melihat secara grafis
bahwa fungsi  tanh memiliki bentuk yang sama dengan fungsi sigmoid,

Satu perbedaan antara tanh neuron dan neuron sigmoid adalah bahwa output
dari tanh neuron berkisar dari -1 hingga 1, bukan 0 hingga 1. Ini
berarti bahwa jika Anda akan membangun jaringan berdasarkan tanh neuron,
Anda mungkin perlu menormalkan output Anda (dan, tergantung pada detail
aplikasi, mungkin input Anda) sedikit berbeda dari pada jaringan
sigmoid.

Mirip dengan neuron sigmoid, jaringan neuron tanh dapat, pada
prinsipnya, menghitung fungsi apa pun. \* Ada beberapa peringatan teknis
untuk pernyataan ini untuk neuron tanh dan sigmoid, serta untuk neuron
linear yang diperbaiki yang dibahas di bawah ini. Namun, secara informal
biasanya baik-baik saja untuk berpikir bahwa *jaringan saraf (neural
networks)* (neural networks)bisa memperkirakan fungsi apa pun dengan
akurasi sewenang-wenang. memetakan input ke kisaran -1 hingga 1.
Selanjutnya, ide-ide seperti backpropagation dan stochastic gradient
descent dapat dengan mudah diterapkan pada jaringan neuron tanh ke
jaringan neuron sigmoid.

#### [Olahraga](http://neuralnetworksanddeeplearning.com/chap3.html#exercise_244827) 

  - Buktikan identitas dalam Persamaan (111) .

Jenis neuron apa yang harus Anda gunakan di jaringan Anda, tanh atau
sigmoid? *A priori* jawabannya tidak jelas, secara sederhana\! Namun,
ada argumen teoretis dan beberapa bukti empiris yang menunjukkan bahwa
tanh kadang berkinerja lebih baik \* \* Lihat, misalnya, [BackProp
Efisien](http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf) , oleh
Yann LeCun, Léon Bottou, Genevieve Orr dan Klaus-Robert Müller (1998),
dan [Memahami kesulitan pelatihan deep feedforward
networks](http://jmlr.org/proceedings/papers/v9/glorot10a/glorot10a.pdf)
, oleh Xavier Glorot dan Yoshua Bengio (2010). . Biarkan saya memberi
Anda secara singkat rasa dari salah satu argumen teoretis untuk neuron
tanh. Misalkan kita menggunakan neuron sigmoid, jadi semua aktivasi di
jaringan kita positif. Mari kita perhatikan bobot wl+1jk input ke neuron
j th di lapisan l+1 th. Aturan untuk backpropagation (lihat di
[sini](http://neuralnetworksanddeeplearning.com/chap2.html#eqtnBP4) )
memberi tahu kami bahwa gradien yang terkait adalah alk deltal+1j.
Karena aktivasi positif, tanda gradien ini akan sama dengan tanda
 deltal+1j. Apakah ini berarti bahwa jika  deltal+1j positif maka
*semua* bobot wl+1jk akan berkurang selama gradient descent, sedangkan
jika  deltal+1j negatif maka *semua* bobot wl+1jk akan meningkat selama
gradient descent. Dengan kata lain, semua bobot pada neuron yang sama
harus meningkat bersama atau menurun bersama. Itu masalah, karena
beberapa bobot mungkin perlu meningkat sementara yang lain perlu
dikurangi. Itu hanya dapat terjadi jika beberapa aktivasi input memiliki
tanda yang berbeda. Itu menyarankan mengganti sigmoid dengan fungsi
aktivasi, seperti  tanh, yang memungkinkan aktivasi positif dan negatif.
Memang, karena  tanh simetris tentang nol,  tanh(−z)=− tanh(z), kita
bahkan dapat berharap bahwa, secara kasar, aktivasi di lapisan
tersembunyi akan sama-sama seimbang antara positif dan negatif . Itu
akan membantu memastikan bahwa tidak ada bias sistematis untuk pembaruan
berat menjadi satu atau lain cara.

Seberapa serius kita harus menerima argumen ini? Sementara argumennya
sugestif, itu heuristik, bukan bukti yang kuat bahwa tanh neuron
mengungguli neuron sigmoid. Mungkin ada sifat lain dari neuron sigmoid
yang mengkompensasi masalah ini? Memang, untuk banyak tugas tanh
ditemukan secara empiris hanya memberikan sedikit atau tidak ada
peningkatan kinerja dibandingkan neuron sigmoid. Sayangnya, kami belum
memiliki aturan keras dan cepat untuk mengetahui tipe neuron mana yang
akan belajar paling cepat, atau memberikan kinerja generalisasi terbaik,
untuk aplikasi tertentu.

Variasi lain pada neuron sigmoid adalah *neuron* *linear yang
diperbaiki* atau *unit linear yang diperbaiki* . Output dari unit linear
yang diperbaiki dengan input x, vektor berat w, dan bias b diberikan
oleh \\ begin {eqnarray} \\ maks (0, w \\ cdot x + b). \\ tag {112} \\
end {eqnarray} Secara grafik, fungsi perbaikan  max(0,z) terlihat
seperti ini:

Jelas sekali neuron semacam itu sangat berbeda dari neuron sigmoid dan
tanh. Namun, seperti sigmoid dan tanh neuron, unit linear yang
diperbaiki dapat digunakan untuk menghitung fungsi apa pun, dan mereka
dapat dilatih menggunakan ide-ide seperti backpropagation dan stochastic
gradient descent.

Kapan Anda harus menggunakan unit linear yang diperbaiki alih-alih
neuron sigmoid atau tanh? Beberapa karya terbaru tentang pengenalan
gambar \* \* Lihat, misalnya, [Apa Arsitektur Multi-Tahap Terbaik untuk
Pengenalan
Objek?](http://yann.lecun.com/exdb/publis/pdf/jarrett-iccv-09.pdf) ,
oleh Kevin Jarrett, Koray Kavukcuoglu, Marc'Aurelio Ranzato dan Yann
LeCun (2009), [Deep Neural
Networks](http://www.jmlr.org/proceedings/papers/v15/glorot11a.html)
Rectifer ﬁ rer, oleh Xavier Glorot, Antoine Bordes, dan Yoshua Bengio
(2011), dan [Klasifikasi ImageNet dengan Deep Neural
Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
, oleh Alex Krizhevsky, Ilya Sutskever, dan Geoffrey Hinton (2012).
Perhatikan bahwa makalah ini mengisi rincian penting tentang cara
mengatur lapisan keluaran, fungsi biaya, dan regularisasi dalam jaringan
menggunakan unit linear yang diperbaiki. Saya telah membahas semua
detail ini di akun singkat ini. Makalah juga membahas secara lebih rinci
manfaat dan kelemahan menggunakan unit linear yang diperbaiki. Makalah
informatif lainnya adalah [Unit Linier yang Diperbaiki Tingkatkan Mesin
Boltzmann
Terbatas](https://www.cs.toronto.edu/~hinton/absps/reluICML.pdf) , oleh
Vinod Nair dan Geoffrey Hinton (2010), yang menunjukkan manfaat
menggunakan unit linear yang diperbaiki dalam pendekatan yang agak
berbeda dengan jaringan saraf. telah menemukan banyak manfaat dalam
menggunakan unit linear yang diperbaiki melalui sebagian besar jaringan.
Namun, seperti halnya dengan tanh neuron, kami belum memiliki pemahaman
yang sangat mendalam tentang kapan, tepatnya, unit linear yang
diperbaiki lebih disukai, atau mengapa. Untuk memberi Anda rasa dari
beberapa masalah, ingat bahwa neuron sigmoid berhenti belajar ketika
mereka jenuh, yaitu, ketika output mereka dekat baik 0 atau 1. Seperti
yang telah kita lihat berulang kali dalam bab ini, masalahnya adalah
sigma 'istilah mengurangi gradien, dan itu memperlambat belajar. Tanh
neuron menderita masalah yang sama ketika mereka jenuh. Sebaliknya,
meningkatkan input terbobot ke unit linier yang diperbaiki tidak akan
pernah menyebabkannya jenuh, sehingga tidak ada perlambatan pembelajaran
yang sesuai. Di sisi lain, ketika input terbobot ke unit linear yang
diperbaiki negatif, gradien menghilang, dan neuron berhenti belajar
sepenuhnya. Ini hanyalah dua dari banyak masalah yang membuatnya tidak
sepele untuk memahami kapan dan mengapa unit linear yang diperbaiki
memiliki kinerja yang lebih baik daripada neuron sigmoid atau tanh.

Saya telah melukis gambar ketidakpastian di sini, menekankan bahwa kami
belum memiliki teori yang kuat tentang bagaimana fungsi aktivasi harus
dipilih. Memang, masalahnya lebih sulit daripada yang saya jelaskan,
karena ada banyak kemungkinan fungsi aktivasi. Mana yang terbaik untuk
masalah apa pun? Yang akan menghasilkan jaringan yang belajar tercepat?
Yang mana yang akan memberikan akurasi tes tertinggi? Saya terkejut
betapa sedikit sekali penyelidikan yang mendalam dan sistematis yang
telah dilakukan atas pertanyaan-pertanyaan ini. Idealnya, kami memiliki
teori yang memberi tahu kami, secara terperinci, cara memilih (dan
mungkin memodifikasi sambil jalan) fungsi aktivasi kami. Di sisi lain,
kita seharusnya tidak membiarkan kurangnya teori lengkap menghentikan
kita\! Kami memiliki alat-alat canggih yang sudah ada, dan dapat membuat
banyak kemajuan dengan alat-alat itu. Melalui sisa buku ini, saya akan
terus menggunakan neuron sigmoid sebagai neuron utama kami, karena
mereka kuat dan memberikan ilustrasi konkret tentang ide-ide inti
tentang jaring saraf. Namun perlu diingat bahwa gagasan yang sama ini
dapat diterapkan pada jenis neuron lain, dan terkadang ada
keuntungannya.

#### [Tentang cerita dalam jaringan saraf](http://neuralnetworksanddeeplearning.com/chap3.html#on_stories_in_neural_networks) 

***Pertanyaan:** Bagaimana pendekatan Anda menggunakan dan meneliti
teknik pembelajaran mesin yang didukung hampir seluruhnya secara
empiris, yang bertentangan dengan matematika?* *Juga dalam situasi apa
Anda memperhatikan beberapa teknik ini gagal?*

**Jawaban:** Anda harus menyadari bahwa alat teoritis kami sangat lemah.
Terkadang, kita memiliki intuisi matematis yang bagus mengapa teknik
tertentu harus bekerja. Kadang-kadang intuisi kita akhirnya salah
\[...\] Pertanyaannya menjadi: seberapa baik metode saya bekerja pada
masalah khusus ini, dan seberapa besar seperangkat masalah yang bekerja
dengan baik.

\- [Tanya
jawab](http://www.reddit.com/r/MachineLearning/comments/25lnbt/ama_yann_lecun/chivdv7)
dengan peneliti jaringan saraf (*neural networks*) Yann LeCun

Suatu ketika, menghadiri konferensi tentang dasar-dasar mekanika
kuantum, saya perhatikan apa yang menurut saya merupakan kebiasaan
verbal yang paling aneh: ketika pembicaraan selesai,
pertanyaan-pertanyaan dari audiens sering dimulai dengan "Saya sangat
bersimpati pada sudut pandang Anda, tetapi \[. ..\] ". Fondasi Quantum
bukan bidang yang biasa saya, dan saya perhatikan gaya bertanya ini
karena di konferensi ilmiah lain saya jarang atau tidak pernah mendengar
seorang penanya mengungkapkan simpati mereka terhadap sudut pandang
pembicara. Pada saat itu, saya pikir prevalensi dari pertanyaan itu
menunjukkan bahwa sedikit kemajuan nyata sedang dibuat di yayasan
kuantum, dan orang-orang hanya memutar roda mereka. Kemudian, saya
menyadari bahwa penilaian itu terlalu keras. Para pembicara bergulat
dengan beberapa masalah tersulit yang pernah dihadapi manusia. Tentu
saja kemajuannya lambat\! Tetapi masih ada nilai dalam mendengar
pembaruan tentang bagaimana orang berpikir, bahkan jika mereka tidak
selalu memiliki kemajuan baru yang tidak dapat dilaporkan.

Anda mungkin telah memperhatikan tic verbal yang mirip dengan "Saya
sangat simpatik \[...\]" dalam buku ini. Untuk menjelaskan apa yang kami
lihat, saya sering tidak suka mengatakan "Heuristically, \[...\]", atau
"Secara kasar, \[...\]", menindaklanjuti dengan sebuah cerita untuk
menjelaskan beberapa fenomena atau lainnya. Kisah-kisah ini masuk akal,
tetapi bukti empiris yang saya sampaikan seringkali sangat tipis. Jika
Anda melihat melalui literatur penelitian Anda akan melihat bahwa cerita
dengan gaya yang sama muncul di banyak makalah penelitian tentang jaring
saraf, seringkali dengan bukti pendukung yang tipis. Apa yang harus kita
pikirkan tentang cerita seperti itu?

Dalam banyak bagian ilmu pengetahuan - terutama bagian-bagian yang
berhubungan dengan fenomena sederhana - dimungkinkan untuk mendapatkan
bukti yang sangat kuat dan sangat andal untuk hipotesis yang cukup umum.
Tetapi dalam jaringan saraf (*neural networks*) ada sejumlah besar
parameter dan hiper-parameter, dan interaksi yang sangat kompleks di
antara mereka. Dalam sistem yang luar biasa rumit seperti itu, sangat
sulit untuk membuat pernyataan umum yang andal. Memahami *jaringan saraf
(neural networks)* dalam generalitas penuhnya adalah masalah yang,
seperti halnya yayasan kuantum, menguji batas-batas pikiran manusia.
Sebagai gantinya, kita sering puas dengan bukti untuk atau terhadap
beberapa contoh spesifik dari pernyataan umum. Akibatnya,
pernyataan-pernyataan itu kadang-kadang nanti perlu diubah atau
ditinggalkan, ketika bukti baru terungkap.

Salah satu cara melihat situasi ini adalah bahwa setiap cerita heuristik
tentang jaringan saraf (*neural networks*) membawa serta tantangan
tersirat. Sebagai contoh, perhatikan pernyataan yang saya [kutip
sebelumnya](http://neuralnetworksanddeeplearning.com/chap3.html#dropout_explanation)
, yang menjelaskan mengapa dropout bekerja \* \* Dari [Klasifikasi
ImageNet dengan Deep Nevoltural Neural
Networks](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)
oleh Alex Krizhevsky, Ilya Sutskever, dan Geoffrey Hinton (2012). :
"Teknik ini mengurangi co-adaptasi kompleks neuron, karena neuron tidak
dapat bergantung pada keberadaan neuron tertentu lainnya. Oleh karena
itu, dipaksa untuk mempelajari fitur yang lebih kuat yang berguna dalam
hubungannya dengan banyak subset acak berbeda dari neuron lain. . " Ini
adalah pernyataan yang kaya dan provokatif, dan seseorang dapat
membangun program penelitian yang bermanfaat sepenuhnya dengan
membongkar pernyataan itu, mencari tahu apa isinya benar, apa yang
salah, apa yang perlu variasi dan perbaikan. Memang, sekarang ada
industri kecil peneliti yang menyelidiki putus sekolah (dan banyak
variasi), mencoba memahami cara kerjanya, dan apa batasannya. Demikian
juga dengan banyak heuristik yang telah kita diskusikan. Setiap
heuristik bukan hanya penjelasan (potensial), tetapi juga tantangan
untuk menyelidiki dan memahami lebih detail.

Tentu saja, tidak ada waktu bagi siapa pun untuk menyelidiki semua
penjelasan heuristik ini secara mendalam. Diperlukan waktu beberapa
dekade (atau lebih lama) bagi komunitas peneliti *jaringan saraf (neural
networks)* untuk mengembangkan teori berbasis bukti yang kuat tentang
bagaimana jaringan saraf (*neural networks*) belajar. Apakah ini berarti
Anda harus menolak penjelasan heuristik sebagai tidak menarik, dan tidak
berbasis bukti? Tidak\! Sebenarnya, kita membutuhkan heuristik semacam
itu untuk menginspirasi dan membimbing pemikiran kita. Ini seperti zaman
penjelajahan yang luar biasa: para penjelajah awal terkadang menjelajahi
(dan membuat penemuan-penemuan baru) berdasarkan kepercayaan yang salah
dalam hal-hal penting. Belakangan, kesalahan-kesalahan itu diperbaiki
ketika kami mengisi pengetahuan kami tentang geografi. Ketika Anda
memahami sesuatu dengan buruk - seperti penjelajah memahami geografi,
dan seperti yang kita pahami jaring saraf hari ini - lebih penting untuk
mengeksplorasi dengan berani daripada benar-benar benar dalam setiap
langkah pemikiran Anda. Jadi, Anda harus melihat cerita-cerita ini
sebagai panduan yang berguna untuk bagaimana berpikir tentang jaring
saraf, sambil mempertahankan kesadaran yang sehat tentang keterbatasan
cerita-cerita seperti itu, dan dengan cermat melacak seberapa kuat bukti
untuk setiap jalur penalaran tertentu. Dengan kata lain, kita perlu
cerita-cerita bagus untuk membantu memotivasi dan menginspirasi kita,
dan investigasi mendalam untuk mengungkap fakta sebenarnya dari masalah
tersebut.

Dalam karya akademis, silakan kutip buku ini sebagai: Michael A.
Nielsen, "Neural Networks and Deep Learning", Determination Press,
2015  
  
Karya ini dilisensikan di bawah [Lisensi Creative Commons
Attribution-NonCommercial 3.0
Unported](http://creativecommons.org/licenses/by-nc/3.0/deed.en_GB) .
Ini artinya Anda bebas menyalin, membagikan, dan membuat buku ini,
tetapi tidak untuk menjualnya. Jika Anda tertarik menggunakan komersial,
silakan [hubungi saya](mailto:mn@michaelnielsen.org) . Pembaruan
terakhir: Sel 11 Jun 16:58:53 2019  
  
  
![Lisensi Creative Commons](media/image33.png)

# [BAB 4](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgSBa_AceI0ZORphepSgTSmPyayiw) 

# [Bukti visual bahwa jaring saraf dapat menghitung fungsi apa pun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgSBa_AceI0ZORphepSgTSmPyayiw) 

[jaringan saraf (*neural networks*) Tiruan dan Pembelajaran
Jauh](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhSmctqJxJo-ili9uCZFWaMmD_ZwA)

[Tentang buku
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/about.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgXQxMXCkc-VqJjrgRGTqMioFXKJQ)

[Tentang latihan dan
masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/exercises_and_problems.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiKViWYCfm5wTll2rNCdKflvpHhWw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Menggunakan
jaring saraf untuk mengenali angka tulisan
tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjAvXu19z5AnD1CAZT6LZ-Zcx2TNQ)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Cara
kerja algoritma
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhTWTlO-QUXLcxN4imdGEJP3uv12g)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Meningkatkan
cara belajar jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhoxYDL_Zv_bP8O27CAL2RxC2uLUQ)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Bukti
visual bahwa jaring saraf dapat menghitung fungsi apa
pun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgSBa_AceI0ZORphepSgTSmPyayiw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Mengapa
jaringan saraf (*neural networks*) yang dalam sulit untuk
dilatih?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiSet-fjtv6rxE7BVkvektedEQ2Pg)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[*Pembelajaran
dalam (deep
learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgmociIff_mA4xu3tVaNKtDxnPP1A)

[Lampiran: Apakah ada algoritma *sederhana* untuk
intelijen?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/sai.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhDBwiqlw0s3ytt8hA8lT5Y6iLqwQ)

[Ucapan Terima
Kasih](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/acknowledgements.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiG2gfdFUv5AZrRImnBFdbTaCb58g)

[Pertanyaan yang Sering
Diajukan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgWnHsxteqPXO-YJY1hx9rV_hRkIw)

Jika Anda mendapat manfaat dari buku ini, silakan berikan sumbangan
kecil. Saya menyarankan $ 5, tetapi Anda dapat memilih jumlahnya.

Top of Form

Bottom of Form

Sebagai alternatif, Anda dapat memberikan donasi dengan mengirimkan saya
Bitcoin, di alamat 1Kd6tXH5SDAmiFb49J9hknG5pqj7KStSAx

Sponsor  
![http://neuralnetworksanddeeplearning.com/assets/exxact.png](media/image36.png)

Workstation Deep Learning mulai dari $ 6.999: [pelajari lebih
lanjut](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.exxactcorp.com/Deep-Learning-NVIDIA-GPU-Solutions%3Futm_source%3Dneuralnetworksanddeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dsponsors&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7OobqZnEZveBnox14nkIJYLvpwA)

![http://neuralnetworksanddeeplearning.com/assets/lambda.png](media/image37.png)

[Workstation, Server, dan Laptop Belajar
dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://lambdalabs.com/%3Futm_source%3Dneuralnetworksdeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dblogin%26utm_content%3Drtext&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhBXMrCHMAsFiT2ntkOrJtiW6IYZQ)

![http://neuralnetworksanddeeplearning.com/assets/gsquared.png](media/image38.png)![http://neuralnetworksanddeeplearning.com/assets/tineye.png](media/image39.png)![http://neuralnetworksanddeeplearning.com/assets/visionsmarts.png](media/image40.png)

Terima kasih kepada semua
[pendukung](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/supporters.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhutgmH2J5_R4doustpZAv4sJL4yw)
yang memungkinkan buku ini, dengan terima kasih terutama kepada Pavel
Dudrenov. Terima kasih juga kepada semua kontributor di [Bugfinder Hall
of
Fame](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/bugfinder.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiqxqXeT9W645rMHHY4leGZZToyVw)
.

Sumber daya

[Michael Nielsen di
Twitter](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://twitter.com/michael_nielsen&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjwqRemkcQCrGULkA7r3BA5uNDbmQ)

[Pesan
FAQ](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgWnHsxteqPXO-YJY1hx9rV_hRkIw)

[Repositori
kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjB9B2BdAr0WL-JeSyKa5KbPTbbHA)

[Milis pengumuman proyek Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://eepurl.com/0Xxjb&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiJkSZ786fGXNHOTtdqSSgHn3jjfA)

[Deep
Learning](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.deeplearningbook.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjOnCicIqWcPQyNk6U05u4MIJe_9w)
, buku karya Ian Goodfellow, Yoshua Bengio, dan Aaron Courville

[cognitivemedium.com](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://cognitivemedium.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjCT99IyV7sYC1FoYAQ7-lETADr9w)

![http://neuralnetworksanddeeplearning.com/assets/Michael\_Nielsen\_Web\_Small.jpg](media/image41.jpeg)

Oleh [Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://michaelnielsen.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj1QFa-jZKIL13kRVa5y4Hyn77YAQ)
/ Jun 2019

Salah satu fakta paling mencolok tentang *jaringan saraf (neural
networks)* adalah bahwa mereka dapat menghitung fungsi apa pun. Yaitu,
anggaplah seseorang memberi Anda beberapa fungsi rumit yang tidak pasti,
f(x):

Apa pun fungsinya, dijamin ada jaringan saraf (*neural networks*)
sehingga untuk setiap input yang mungkin, x, nilai f(x) (atau perkiraan
dekat) adalah output dari jaringan, misalnya:

Hasil ini berlaku bahkan jika fungsi memiliki banyak input,
f=f(x1, ldots,xm), dan banyak output. Misalnya, inilah jaringan yang
menghitung fungsi dengan m=3 input dan n=2 output:

Hasil ini memberi tahu kita bahwa jaringan saraf (*neural networks*)
memiliki semacam *universalitas* . Tidak peduli fungsi apa yang ingin
kita hitung, kita tahu bahwa ada jaringan saraf (*neural networks*) yang
dapat melakukan pekerjaan itu.

Terlebih lagi, teorema universalitas ini berlaku bahkan jika kita
membatasi jaringan kita hanya memiliki satu lapisan perantara antara
input dan neuron keluaran - yang disebut lapisan tersembunyi tunggal.
Jadi bahkan arsitektur jaringan yang sangat sederhana pun bisa sangat
kuat.

Teorema universalitas terkenal oleh orang-orang yang menggunakan
jaringan saraf. Tapi mengapa itu benar tidak begitu dipahami secara
luas. Sebagian besar penjelasan yang tersedia cukup teknis. Sebagai
contoh, salah satu makalah asli membuktikan hasil \* \* [Perkiraan oleh
superposisi dari fungsi
sigmoidal](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.dartmouth.edu/~gvc/Cybenko_MCSS.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi0kmNGz_b1BySdHLgAprQ5YsTz6A)
, oleh George Cybenko (1989). Hasilnya sangat mengudara pada saat itu,
dan beberapa kelompok membuktikan hasil yang terkait erat. Makalah
Cybenko berisi diskusi yang bermanfaat tentang banyak pekerjaan itu.
Makalah awal penting lainnya adalah [jaringan feedforward Multilayer
adalah aproksimator
universal](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.sciencedirect.com/science/article/pii/0893608089900208&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgrXNdESVV7gvYzMj7Q8iU6by9ubg)
, oleh Kurt Hornik, Maxwell Stinchcombe, dan Halbert White (1989).
Makalah ini menggunakan teorema Stone-Weierstrass untuk sampai pada
hasil yang sama. melakukannya dengan menggunakan teorema Hahn-Banach,
teorema Representasi Riesz, dan beberapa analisis Fourier. Jika Anda
seorang ahli matematika, argumennya tidak sulit untuk diikuti, tetapi
itu tidak mudah bagi kebanyakan orang. Sayang sekali, karena alasan yang
mendasari universalitas itu sederhana dan indah.

Dalam bab ini saya memberikan penjelasan sederhana dan sebagian besar
visual dari teorema universalitas. Kami akan pergi selangkah demi
selangkah melalui ide-ide yang mendasarinya. Anda akan mengerti mengapa
benar bahwa jaringan saraf (*neural networks*) dapat menghitung fungsi
apa pun. Anda akan memahami beberapa batasan dari hasilnya. Dan Anda
akan memahami bagaimana hasilnya berhubungan dengan *jaringan saraf
(neural networks)* yang dalam.

Untuk mengikuti materi dalam bab ini, Anda tidak perlu membaca bab-bab
sebelumnya dalam buku ini. Sebaliknya, bab ini disusun untuk menjadi
menyenangkan sebagai esai mandiri. Asalkan Anda hanya memiliki sedikit
pengetahuan dasar dengan jaringan saraf, Anda harus dapat mengikuti
penjelasannya. Namun, saya akan memberikan tautan sesekali ke materi
sebelumnya, untuk membantu mengisi setiap celah dalam pengetahuan Anda.

Teorema universalitas adalah hal yang biasa dalam ilmu komputer,
sedemikian rupa sehingga kita terkadang lupa betapa menakjubkannya
mereka. Tapi ada baiknya mengingatkan diri kita sendiri: kemampuan untuk
menghitung fungsi arbitrer benar-benar luar biasa. Hampir setiap proses
yang dapat Anda bayangkan dapat dianggap sebagai perhitungan fungsi.
Pertimbangkan masalah penamaan karya musik berdasarkan sampel pendek
karya tersebut. Itu bisa dianggap sebagai komputasi fungsi. Atau
pertimbangkan masalah menerjemahkan teks berbahasa Mandarin ke bahasa
Inggris. Sekali lagi, itu dapat dianggap sebagai komputasi fungsi \* \*
Sebenarnya, menghitung salah satu dari banyak fungsi, karena sering ada
terjemahan yang dapat diterima dari selembar teks yang diberikan. . Atau
pertimbangkan masalah mengambil file film mp4 dan menghasilkan deskripsi
plot film, dan diskusi tentang kualitas akting. Sekali lagi, itu dapat
dianggap sebagai semacam penghitungan fungsi. \* \* Mengucapkan komentar
tentang terjemahan dan ada banyak fungsi yang mungkin. . Universalitas
berarti bahwa, pada prinsipnya, jaringan saraf (*neural networks*) dapat
melakukan semua hal ini dan banyak lagi.

Tentu saja, hanya karena kita tahu ada *jaringan saraf (neural
networks)* yang dapat (misalnya) menerjemahkan teks China ke dalam
bahasa Inggris, itu tidak berarti kita memiliki teknik yang baik untuk
membangun atau bahkan mengenali jaringan semacam itu. Batasan ini
berlaku juga untuk teorema universalitas tradisional untuk model seperti
sirkuit Boolean. Tetapi, seperti yang telah kita lihat sebelumnya dalam
buku ini, jaringan saraf (*neural networks*) memiliki algoritma yang
kuat untuk fungsi pembelajaran. Kombinasi dari algoritma pembelajaran +
universalitas merupakan campuran yang menarik. Hingga kini, buku ini
telah berfokus pada algoritma pembelajaran. Dalam bab ini, kami fokus
pada universalitas, dan apa artinya.

### [Dua peringatan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgSBa_AceI0ZORphepSgTSmPyayiw#two_caveats) 

Sebelum menjelaskan mengapa teorema universalitas itu benar, saya ingin
menyebutkan dua peringatan pada pernyataan informal "*jaringan saraf
(neural networks)* dapat menghitung fungsi apa pun".

Pertama, ini tidak berarti bahwa jaringan dapat digunakan untuk secara
*tepat* menghitung fungsi apa pun. Sebaliknya, kita bisa mendapatkan
*perkiraan* yang sebaik yang kita inginkan. Dengan meningkatkan jumlah
neuron tersembunyi kita dapat meningkatkan perkiraannya. Sebagai contoh,
[sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgSBa_AceI0ZORphepSgTSmPyayiw#basic_network_precursor)
saya menggambarkan sebuah jaringan yang menghitung beberapa fungsi f(x)
menggunakan tiga neuron tersembunyi. Untuk sebagian besar fungsi, hanya
perkiraan kualitas rendah yang dimungkinkan menggunakan tiga neuron
tersembunyi. Dengan meningkatkan jumlah neuron yang tersembunyi
(misalnya, menjadi lima) kita biasanya bisa mendapatkan perkiraan yang
lebih baik:

Dan kita bisa melakukan yang lebih baik lagi dengan meningkatkan jumlah
neuron yang tersembunyi.

Untuk membuat pernyataan ini lebih tepat, anggaplah kita diberi fungsi
f(x) yang ingin kita hitung dengan akurasi yang diinginkan  epsilon\>0.
Jaminannya adalah bahwa dengan menggunakan neuron tersembunyi yang
cukup, kita selalu dapat menemukan jaringan saraf (*neural networks*)
yang outputnya g(x) memuaskan $ | g (x) - f (x) | \<\\ epsilon
,untuksemuainput x $. Dengan kata lain, perkiraan akan baik untuk
keakuratan yang diinginkan untuk setiap input yang mungkin.

Peringatan kedua adalah bahwa kelas fungsi yang dapat diperkirakan
dengan cara yang dijelaskan adalah fungsi *kontinu* . Jika suatu fungsi
terputus-putus, yaitu membuat lompatan tajam dan tiba-tiba, maka secara
umum tidak mungkin untuk memperkirakan menggunakan jaring saraf. Ini
tidak mengherankan, karena jaringan saraf (*neural networks*) kita
menghitung fungsi kontinu dari input mereka. Namun, bahkan jika fungsi
yang ingin kita hitung adalah diskontinyu, sering kali terjadi bahwa
perkiraan terus menerus cukup baik. Jika begitu, maka kita dapat
menggunakan jaringan saraf. Dalam praktiknya, ini biasanya bukan batasan
penting.

Kesimpulannya, pernyataan yang lebih tepat dari teorema universalitas
adalah bahwa jaringan saraf (*neural networks*) dengan lapisan
tersembunyi tunggal dapat digunakan untuk memperkirakan setiap fungsi
kontinu dengan presisi yang diinginkan. Dalam bab ini kita akan
benar-benar membuktikan versi yang sedikit lebih lemah dari hasil ini,
menggunakan dua lapisan tersembunyi, bukan satu. Dalam masalah saya akan
secara singkat menguraikan bagaimana penjelasan dapat, dengan beberapa
penyesuaian, diadaptasi untuk memberikan bukti yang hanya menggunakan
satu lapisan tersembunyi.

### [Universalitas dengan satu input dan satu output](http://neuralnetworksanddeeplearning.com/chap4.html#universality_with_one_input_and_one_output) 

Untuk memahami mengapa teorema universalitas itu benar, mari kita mulai
dengan memahami bagaimana membangun jaringan saraf (*neural networks*)
yang mendekati suatu fungsi hanya dengan satu input dan satu output:

Ternyata inilah inti masalah universalitas. Setelah kami memahami kasus
khusus ini, sebenarnya cukup mudah untuk memperluas ke fungsi dengan
banyak input dan banyak output.

Untuk membangun wawasan tentang bagaimana membangun jaringan untuk
menghitung f, mari kita mulai dengan jaringan yang hanya mengandung satu
lapisan tersembunyi, dengan dua neuron tersembunyi, dan lapisan keluaran
yang mengandung satu neuron keluaran:

Untuk mengetahui bagaimana komponen dalam jaringan bekerja, mari fokus
pada neuron tersembunyi teratas. Pada diagram di bawah ini, klik pada
bobot, w, dan seret mouse sedikit cara ke kanan untuk menambah w. Anda
dapat segera melihat bagaimana fungsi yang dikomputasi oleh perubahan
neuron tersembunyi atas:

Seperti yang kita pelajari [sebelumnya dalam buku
ini](http://neuralnetworksanddeeplearning.com/chap1.html#sigmoid_neurons)
, apa yang dihitung oleh neuron tersembunyi adalah  sigma(wx+b), di mana
 sigma(z) equiv1/(1+e−z) adalah fungsi sigmoid. Hingga kini, kami telah
sering menggunakan bentuk aljabar ini. Tetapi untuk bukti universalitas,
kita akan memperoleh lebih banyak wawasan dengan mengabaikan aljabar
sepenuhnya, dan alih-alih memanipulasi dan mengamati bentuk yang
ditunjukkan dalam grafik. Ini tidak hanya memberi kita perasaan yang
lebih baik tentang apa yang sedang terjadi, itu juga akan memberi kita
bukti \* \* Sebenarnya, pendekatan visual yang saya ambil bukanlah apa
yang secara tradisional dianggap sebagai bukti. Tapi saya percaya
pendekatan visual memberi lebih banyak wawasan mengapa hasilnya benar
daripada bukti tradisional. Dan, tentu saja, wawasan seperti itu adalah
tujuan sebenarnya di balik bukti. Kadang-kadang, akan ada celah kecil
dalam alasan yang saya sajikan: tempat di mana saya membuat argumen
visual yang masuk akal, tetapi tidak terlalu ketat. Jika ini mengganggu
Anda, maka anggap tantangan untuk mengisi langkah-langkah yang hilang.
Tetapi jangan lupa tujuan sebenarnya: untuk memahami mengapa teorema
universalitas itu benar. universalitas yang berlaku untuk fungsi
aktivasi selain fungsi sigmoid.

Untuk memulai bukti ini, coba klik pada bias, b, pada diagram di atas,
dan seret ke kanan untuk meningkatkannya. Anda akan melihat bahwa ketika
bias meningkatkan grafik bergerak ke kiri, tetapi bentuknya tidak
berubah.

Selanjutnya, klik dan seret ke kiri untuk mengurangi bias. Anda akan
melihat bahwa ketika bias menurun, grafik bergerak ke kanan, tetapi,
sekali lagi, bentuknya tidak berubah.

Selanjutnya, kurangi bobot menjadi sekitar 2 atau 3. Anda akan melihat
bahwa saat Anda menurunkan berat badan, kurva melebar. Anda mungkin
perlu mengubah bias juga, agar kurva tetap dalam bingkai.

Akhirnya, tambah bobot hingga w=100. Saat Anda melakukannya, kurva akan
semakin curam, hingga akhirnya mulai terlihat seperti fungsi langkah.
Cobalah untuk menyesuaikan bias sehingga langkah terjadi di dekat x=0,3.
Klip pendek berikut ini menunjukkan seperti apa hasil Anda seharusnya.
Klik tombol putar untuk memutar (atau memutar ulang) video:

![http://neuralnetworksanddeeplearning.com/images/play.png](media/image77.png)

Kita dapat menyederhanakan analisis kita sedikit dengan menambah bobot
sedemikian rupa sehingga output benar-benar merupakan fungsi langkah,
hingga perkiraan yang sangat baik. Di bawah ini saya telah merencanakan
output dari neuron tersembunyi teratas ketika beratnya adalah w=999.
Perhatikan bahwa plot ini statis, dan Anda tidak dapat mengubah
parameter seperti bobot.

![http://neuralnetworksanddeeplearning.com/images/high\_weight\_function.jpg](media/image78.jpeg)

Ini sebenarnya sedikit lebih mudah untuk bekerja dengan fungsi langkah
daripada fungsi sigmoid umum. Alasannya adalah bahwa pada lapisan output
kami menambahkan kontribusi dari semua neuron tersembunyi. Sangat mudah
untuk menganalisis jumlah dari sejumlah fungsi langkah, tetapi lebih
sulit untuk menjelaskan tentang apa yang terjadi ketika Anda menambahkan
sekelompok kurva berbentuk sigmoid. Dan itu membuat segalanya lebih
mudah untuk mengasumsikan bahwa neuron tersembunyi kita menghasilkan
fungsi langkah. Lebih konkretnya, kita melakukan ini dengan memperbaiki
bobot w menjadi beberapa nilai yang sangat besar, dan kemudian mengatur
posisi langkah dengan memodifikasi bias. Tentu saja, memperlakukan
output sebagai fungsi langkah adalah perkiraan, tapi ini perkiraan yang
sangat baik, dan untuk saat ini kami akan memperlakukannya sebagai
tepat. Saya akan kembali lagi nanti untuk membahas dampak penyimpangan
dari perkiraan ini.

Pada nilai x berapa langkah tersebut terjadi? Dengan kata lain,
bagaimana posisi langkah tergantung pada berat dan bias?

Untuk menjawab pertanyaan ini, cobalah memodifikasi bobot dan bias dalam
diagram di atas (Anda mungkin perlu sedikit menggulir ke belakang).
Bisakah Anda mengetahui bagaimana posisi langkah tergantung pada w dan
b? Dengan sedikit kerja Anda harus dapat meyakinkan diri sendiri bahwa
posisi langkah *sebanding* dengan b, dan *berbanding terbalik* dengan w.

Faktanya, langkahnya ada pada posisi s=−b/w, seperti yang dapat Anda
lihat dengan memodifikasi bobot dan bias dalam diagram berikut:

Ini akan sangat menyederhanakan hidup kita untuk menggambarkan neuron
tersembunyi hanya dengan menggunakan satu parameter, s, yang merupakan
posisi langkah, s=−b/w. Coba ubah s dalam diagram berikut, agar terbiasa
dengan parameterisasi baru:

Seperti disebutkan di atas, kami secara implisit menetapkan bobot w pada
input menjadi beberapa nilai besar - cukup besar sehingga fungsi
langkahnya merupakan perkiraan yang sangat baik. Kita dapat dengan mudah
mengkonversi parameter neuron dengan cara ini kembali ke model
konvensional, dengan memilih bias b=−ws.

Hingga kini kami telah berfokus pada output dari hanya neuron
tersembunyi teratas. Mari kita lihat perilaku seluruh jaringan. Secara
khusus, kita anggap neuron tersembunyi menghitung fungsi langkah yang
diparameterisasi oleh titik langkah s1 (neuron atas) dan s2 (neuron
bawah). Dan mereka akan memiliki bobot keluaran masing-masing w1 dan w2.
Inilah jaringannya:

Apa yang diplot di sebelah kanan adalah *output terbobot* w1a1+w2a2 dari
lapisan tersembunyi. Di sini, a1 dan a2 adalah output dari neuron
tersembunyi atas dan bawah, masing-masing \* \* Perhatikan, omong-omong,
bahwa output dari seluruh jaringan adalah  sigma(w1a1+w2a2+b) , di mana
b adalah bias pada neuron output. Jelas, ini tidak sama dengan output
terbobot dari lapisan tersembunyi, yang kami rencanakan di sini. Kita
akan fokus pada output terbobot dari lapisan tersembunyi saat ini, dan
hanya nanti kita akan memikirkan bagaimana hal itu berkaitan dengan
output dari seluruh jaringan. . Output ini dilambangkan dengan a s
karena mereka sering dikenal sebagai *aktivasi* neuron.

Coba tambah dan kurangi titik langkah s1 dari neuron tersembunyi
teratas. Dapatkan merasakan bagaimana ini mengubah output terbobot dari
lapisan tersembunyi. Sangat berharga untuk memahami apa yang terjadi
ketika s1 melampaui s2. Anda akan melihat bahwa grafik berubah bentuk
ketika ini terjadi, karena kami telah beralih dari situasi di mana
neuron tersembunyi atas adalah yang pertama kali diaktifkan ke situasi
di mana neuron tersembunyi bawah adalah yang pertama kali diaktifkan.

Demikian pula, cobalah memanipulasi titik langkah s2 dari neuron
tersembunyi bawah, dan rasakan bagaimana ini mengubah output gabungan
dari neuron tersembunyi.

Cobalah menambah dan mengurangi masing-masing bobot keluaran. Perhatikan
bagaimana ini meningkatkan kembali kontribusi dari masing-masing neuron
tersembunyi. Apa yang terjadi ketika salah satu bobotnya nol?

Terakhir, coba atur w1 menjadi 0,8 dan w2 menjadi −0,8. Anda mendapatkan
fungsi "bump", yang dimulai pada titik s1, berakhir pada titik s2, dan
memiliki tinggi 0,8. Misalnya, output terbobot mungkin terlihat seperti
ini:

![http://neuralnetworksanddeeplearning.com/images/bump\_function.jpg](media/image79.jpeg)

Tentu saja, kita dapat menskalakan kembali benjolan tersebut untuk
ketinggian sama sekali. Mari kita gunakan satu parameter, h, untuk
menunjukkan tinggi. Untuk mengurangi kekacauan, saya juga akan menghapus
notasi "s1= ldots" dan "w1= ldots".

Coba ubah nilai h atas dan ke bawah, untuk melihat bagaimana ketinggian
gundukan berubah. Coba ubah ketinggiannya jadi negatif, dan amati apa
yang terjadi. Dan cobalah mengubah titik langkah untuk melihat bagaimana
itu mengubah bentuk benjolan.

Ngomong-ngomong, Anda akan melihat bahwa kami menggunakan neuron kami
dengan cara yang dapat dipikirkan tidak hanya dalam hal grafis, tetapi
dalam istilah pemrograman yang lebih konvensional, sebagai semacam
pernyataan if-then-else , misalnya:

jika input\> = titik langkah:

tambahkan 1 ke output terbobot

lain :

tambahkan 0 ke output terbobot

Sebagian besar saya akan tetap dengan sudut pandang grafis. Tetapi dalam
apa yang Anda ikuti kadang-kadang Anda mungkin merasa perlu untuk
mengubah sudut pandang, dan memikirkan hal-hal dengan kata lain .

Kita dapat menggunakan trik pembuatan benjolan untuk mendapatkan dua
tonjolan, dengan menempelkan dua pasang neuron tersembunyi ke dalam
jaringan yang sama:

Saya telah menekan bobot di sini, cukup menulis nilai h untuk setiap
pasangan neuron tersembunyi. Coba tambah dan kurangi nilai h, dan amati
bagaimana hal itu mengubah grafik. Pindahkan gundukan di sekitar dengan
mengubah titik langkah.

Secara umum, kita dapat menggunakan ide ini untuk mendapatkan puncak
sebanyak yang kita inginkan, dengan ketinggian berapa pun. Secara
khusus, kita dapat membagi interval \[0,1\] menjadi sejumlah besar, N,
dari subintervals, dan menggunakan N pasang neuron tersembunyi untuk
mengatur puncak dari ketinggian yang diinginkan. Mari kita lihat
bagaimana ini bekerja untuk N=5. Itu beberapa neuron, jadi saya akan
mengemas beberapa hal. Permintaan maaf untuk kompleksitas diagram: Saya
bisa menyembunyikan kerumitan dengan mengabstraksi lebih jauh, tapi saya
pikir ada baiknya memasang sedikit kompleksitas, demi mendapatkan rasa
yang lebih konkret untuk bagaimana jaringan ini bekerja.

Anda dapat melihat bahwa ada lima pasang neuron tersembunyi. Poin
langkah untuk masing-masing pasangan neuron adalah 0,1/5, lalu 1/5,2/5,
dan seterusnya, hingga 4/5,5/5. Nilai-nilai ini adalah tetap - mereka
membuatnya jadi kami mendapatkan lima benjolan yang berjarak sama secara
merata pada grafik.

Setiap pasangan neuron memiliki nilai h yang terkait dengannya. Ingat,
output koneksi dari neuron memiliki bobot h dan −h (tidak ditandai).
Klik salah satu dari nilai h, dan seret mouse ke kanan atau kiri untuk
mengubah nilai. Saat Anda melakukannya, perhatikan fungsinya berubah.
Dengan mengubah bobot keluaran, kami sebenarnya *merancang* fungsinya\!

Sebaliknya, coba klik pada grafik, dan seret naik atau turun untuk
mengubah ketinggian fungsi bump. Saat Anda mengubah ketinggian, Anda
dapat melihat perubahan terkait dalam nilai h. Dan, meskipun tidak
ditampilkan, ada juga perubahan dalam bobot output yang sesuai, yaitu +h
dan −h.

Dengan kata lain, kita dapat secara langsung memanipulasi fungsi yang
muncul dalam grafik di sebelah kanan, dan melihat yang tercermin dalam
nilai h di sebelah kiri. Hal yang menyenangkan untuk dilakukan adalah
menahan tombol mouse ke bawah dan menarik mouse dari satu sisi grafik ke
sisi yang lain. Ketika Anda melakukan ini, Anda menggambar suatu fungsi,
dan bisa menonton parameter dalam jaringan saraf (*neural networks*)
beradaptasi.

Saatnya tantangan.

Mari kita pikirkan kembali fungsi yang saya rencanakan di awal bab ini:

Saya tidak mengatakannya pada saat itu, tetapi yang saya rencanakan
sebenarnya adalah fungsinya \\ begin {eqnarray} f (x) = 0,2 + 0,4 x ^ 2
+ 0,3x \\ sin (15 x) + 0,05 \\ cos (50 x), \\ tag {113} \\ end
{eqnarray} diplot lebih dari x dari 0 hingga 1, dan dengan sumbu y
mengambil nilai dari 0 hingga 1.

Itu jelas bukan fungsi yang sepele.

Anda akan mengetahui cara menghitungnya menggunakan jaringan saraf.

Di jaringan kami di atas kami telah menganalisis kombinasi terbobot
 sumjwjaj output dari neuron tersembunyi. Kami sekarang tahu cara
mendapatkan banyak kendali atas jumlah ini. Tetapi, seperti yang saya
sebutkan sebelumnya, kuantitas ini bukan apa yang dihasilkan dari
jaringan. Apa yang keluar dari jaringan adalah  sigma( sumjwjaj+b) di
mana b adalah bias pada neuron output. Apakah ada cara agar kita dapat
mengontrol output aktual dari jaringan?

Solusinya adalah merancang jaringan saraf (*neural networks*) yang
lapisan tersembunyinya memiliki keluaran terbobot yang diberikan oleh
 sigma−1 circf(x), di mana  sigma−1 hanya kebalikan dari  sigma
function. Artinya, kami ingin keluaran terbobot dari lapisan tersembunyi
adalah:

Jika kita bisa melakukan ini, maka output dari jaringan secara
keseluruhan akan menjadi perkiraan yang baik untuk f(x) \* \* Perhatikan
bahwa saya telah menetapkan bias pada neuron output menjadi 0. .

Tantangan Anda, maka, adalah untuk merancang *jaringan saraf (neural
networks)* untuk memperkirakan fungsi tujuan yang ditunjukkan di atas.
Untuk belajar sebanyak mungkin, saya ingin Anda menyelesaikan masalah
dua kali. Pertama kali, silakan klik pada grafik, langsung menyesuaikan
ketinggian fungsi benjolan yang berbeda. Anda harus menemukannya cukup
mudah untuk mendapatkan kecocokan yang baik dengan fungsi tujuan.
Seberapa baik yang Anda lakukan diukur dengan *penyimpangan rata* -
*rata* antara fungsi tujuan dan fungsi jaringan yang sebenarnya
dikomputasi. Tantangan Anda adalah untuk mendorong penyimpangan
rata-rata *serendah* mungkin. Anda menyelesaikan tantangan ketika Anda
menggerakkan penyimpangan rata-rata ke $ 0,40 atau lebih rendah.

Setelah Anda selesai melakukannya, klik "Reset" untuk menginisialisasi
ulang benjolan secara acak. Kali kedua Anda memecahkan masalah, tahan
dorongan untuk mengklik pada grafik. Sebagai gantinya, modifikasi nilai
h di sebelah kiri, dan lagi-lagi usahakan untuk mengarahkan penyimpangan
rata-rata ke $ 0,40 atau lebih rendah.

Anda sekarang telah menemukan semua elemen yang diperlukan untuk
jaringan untuk kira-kira menghitung fungsi f(x)\! Itu hanya perkiraan
kasar, tetapi kita bisa dengan mudah melakukan jauh lebih baik, hanya
dengan meningkatkan jumlah pasangan neuron tersembunyi, memungkinkan
lebih banyak tonjolan.

Secara khusus, mudah untuk mengkonversi semua data yang kami temukan
kembali ke parameterisasi standar yang digunakan untuk jaringan saraf.
Biarkan saya rekap cepat bagaimana cara kerjanya.

Lapisan pertama dari bobot semua memiliki nilai besar dan konstan,
katakanlah w=1000.

Bias pada neuron tersembunyi hanya b=−ws. Jadi, misalnya, untuk neuron
tersembunyi kedua s=0,2 menjadi b=−1000 kali0,2=−200.

Lapisan akhir bobot ditentukan oleh nilai h. Jadi, misalnya, nilai yang
Anda pilih di atas untuk h pertama, h= , berarti bobot keluaran dari dua
neuron tersembunyi teratas dan masing-masing. Dan seterusnya, untuk
seluruh lapisan bobot keluaran.

Akhirnya, bias pada neuron output adalah 0.

Itu segalanya: kami sekarang memiliki deskripsi lengkap tentang
jaringan saraf (*neural networks*) yang melakukan pekerjaan yang cukup
baik menghitung fungsi tujuan awal kami. Dan kami mengerti bagaimana
meningkatkan kualitas perkiraan dengan meningkatkan jumlah neuron yang
tersembunyi.

Terlebih lagi, tidak ada yang istimewa tentang fungsi tujuan awal kami,
f(x)=0,2+0,4x2+0,3 sin(15x)+0,05 cos(50x). Kami dapat menggunakan
prosedur ini untuk fungsi kontinu dari \[0,1\] hingga \[0,1\]. Intinya,
kami menggunakan jaringan saraf (*neural networks*) single-layer kami
untuk membangun tabel pencarian fungsi. Dan kita akan dapat membangun
ide ini untuk memberikan bukti umum tentang universalitas.

### [Banyak variabel input](http://neuralnetworksanddeeplearning.com/chap4.html#many_input_variables) 

Mari kita memperluas hasil kami ke kasus banyak variabel input. Ini
kedengarannya rumit, tetapi semua ide yang kita butuhkan dapat dipahami
hanya dengan dua input. Jadi mari kita membahas kasus dua input.

Kami akan mulai dengan mempertimbangkan apa yang terjadi ketika kami
memiliki dua input ke neuron:

Di sini, kami memiliki input x dan y, dengan bobot yang sesuai w1 dan
w2, dan bias b pada neuron. Mari kita atur bobot w2 menjadi 0, dan
kemudian bermain-main dengan bobot pertama, w1, dan biasnya, b, untuk
melihat bagaimana mereka memengaruhi output dari neuron:

Seperti yang Anda lihat, dengan w2=0 input y tidak membuat perbedaan
pada output dari neuron. Seolah-olah x adalah satu-satunya input.

Mengingat ini, menurut Anda apa yang terjadi ketika kami menambah bobot
w1 menjadi w1=100, dengan w2 tersisa 0? Jika Anda tidak segera melihat
jawabannya, renungkan pertanyaannya sebentar, dan lihat apakah Anda
dapat mengetahui apa yang terjadi. Kemudian cobalah dan lihat apakah
Anda benar. Saya telah menunjukkan apa yang terjadi di film berikut:

![http://neuralnetworksanddeeplearning.com/images/play.png](media/image77.png)

Seperti pada pembahasan kami sebelumnya, saat bobot input bertambah
besar output mendekati fungsi langkah. Perbedaannya adalah bahwa
sekarang fungsi langkah dalam tiga dimensi. Juga seperti sebelumnya,
kita dapat memindahkan lokasi titik langkah dengan memodifikasi bias.
Lokasi sebenarnya dari titik langkah adalah sx equiv−b/w1.

Mari kita ulangi langkah di atas menggunakan posisi langkah sebagai
parameter:

Di sini, kami menganggap bobot pada x input memiliki nilai besar - Saya
telah menggunakan w1=1000 - dan bobot w2=0. Angka pada neuron adalah
titik langkah, dan x di atas angka tersebut mengingatkan kita bahwa
langkahnya ada di arah x. Tentu saja, juga dimungkinkan untuk
mendapatkan fungsi langkah dalam arah y, dengan membuat bobot pada y
input sangat besar (katakanlah, w2=1000), dan bobot pada x sama dengan
0, yaitu, w1=0:

Angka pada neuron sekali lagi adalah titik langkah, dan dalam kasus ini
y kecil di atas angka mengingatkan kita bahwa langkahnya ada di arah y.
Saya bisa secara eksplisit menandai bobot pada x dan y input, tetapi
memutuskan untuk tidak, karena itu akan membuat diagram agak berantakan.
Tetapi perlu diingat bahwa penanda y kecil secara implisit memberi tahu
kita bahwa y beratnya besar, dan x beratnya adalah 0.

Kita dapat menggunakan fungsi langkah yang baru saja kita bangun untuk
menghitung fungsi benjolan tiga dimensi. Untuk melakukan ini, kami
menggunakan dua neuron, masing-masing menghitung fungsi langkah dalam
arah x. Lalu kami menggabungkan fungsi langkah tersebut dengan bobot h
dan −h, masing-masing, di mana h adalah ketinggian bump yang diinginkan.
Itu semua diilustrasikan dalam diagram berikut:

Coba ubah nilai ketinggian, h. Amati bagaimana kaitannya dengan bobot
dalam jaringan. Dan lihat bagaimana ia mengubah ketinggian fungsi bump
di sebelah kanan.

Juga, coba ubah titik langkah $ 0,30 yang terkait dengan neuron
tersembunyi teratas. Saksikan bagaimana perubahan bentuk benjolan. Apa
yang terjadi ketika Anda memindahkannya melewati titik langkah $ 0,70
yang terkait dengan neuron tersembunyi bawah?

Kami telah menemukan cara untuk membuat fungsi bump di arah x. Tentu
saja, kita dapat dengan mudah membuat fungsi bump di arah y, dengan
menggunakan dua fungsi langkah dalam arah y. Ingatlah bahwa kita
melakukan ini dengan membuat bobot menjadi besar pada input y, dan bobot
0 pada input x. Inilah hasilnya:

Ini terlihat hampir identik dengan jaringan sebelumnya\! Satu-satunya
hal yang secara eksplisit ditunjukkan sebagai perubahan adalah sekarang
ada sedikit y marker pada neuron tersembunyi kita. Itu mengingatkan kita
bahwa mereka menghasilkan fungsi y step, bukan fungsi x step, sehingga
bobotnya sangat besar pada input y, dan nol pada input x, bukan
sebaliknya. Seperti sebelumnya, saya memutuskan untuk tidak menunjukkan
ini secara eksplisit, untuk menghindari kekacauan.

Mari kita perhatikan apa yang terjadi ketika kita menjumlahkan dua
fungsi bump, satu di arah x, yang lain di arah y, keduanya tingginya h:

Untuk menyederhanakan diagram, saya telah menjatuhkan koneksi dengan
bobot nol. Untuk saat ini, saya telah meninggalkan tanda x dan y kecil
pada neuron tersembunyi, untuk mengingatkan Anda ke arah mana fungsi
bump dihitung. Kami bahkan akan menjatuhkan penanda tersebut, karena
tersirat oleh variabel input.

Cobalah memvariasikan parameter h. Seperti yang Anda lihat, ini
menyebabkan bobot output berubah, dan juga ketinggian fungsi bump x dan
y.

Apa yang kami bangun tampak seperti fungsi *menara* :

Jika kita dapat membangun fungsi menara seperti itu, maka kita dapat
menggunakannya untuk memperkirakan fungsi sewenang-wenang, hanya dengan
menambahkan banyak menara dengan ketinggian yang berbeda, dan di lokasi
yang berbeda:

Tentu saja, kami belum menemukan cara membangun fungsi menara. Apa yang
kami bangun tampak seperti menara pusat, dengan tinggi 2j, dengan
dataran tinggi di sekitarnya, dengan tinggi h.

Tapi kita bisa membuat fungsi menara. Ingat bahwa sebelumnya kita
melihat neuron dapat digunakan untuk mengimplementasikan jenis
pernyataan if-then-else :

jika input\> = ambang batas:

output 1

lain :

output 0

Itu untuk neuron dengan hanya satu input. Apa yang kita inginkan adalah
menerapkan ide serupa ke output gabungan dari neuron tersembunyi:

jika gabungan output dari neuron tersembunyi\> = ambang batas:

output 1

lain :

output 0

Jika kita memilih ambang batas dengan tepat - katakanlah, nilai 3j/2,
yang diapit antara ketinggian dataran tinggi dan ketinggian menara pusat
- kita bisa meremas dataran tinggi hingga nol, dan meninggalkan menara
saja .

Bisakah Anda melihat bagaimana melakukan ini? Coba bereksperimen dengan
jaringan berikut untuk mengetahuinya. Perhatikan bahwa kita sekarang
merencanakan keluaran dari seluruh jaringan, bukan hanya keluaran
terbobot dari lapisan tersembunyi. Ini berarti kami menambahkan istilah
bias ke output terbobot dari lapisan tersembunyi, dan menerapkan fungsi
sigma. Bisakah Anda menemukan nilai untuk h dan b yang menghasilkan
menara? Ini agak sulit, jadi jika Anda berpikir tentang hal ini untuk
sementara waktu dan tetap macet, inilah dua petunjuk: (1) Untuk
mendapatkan neuron output untuk menunjukkan jenis perilaku if-then-else
yang tepat , kita membutuhkan bobot input ( semua h atau −h) menjadi
besar; dan (2) nilai b menentukan skala ambang if-then-else .

Dengan parameter awal kami, output terlihat seperti versi rata dari
diagram sebelumnya, dengan menara dan dataran tinggi. Untuk mendapatkan
perilaku yang diinginkan, kami meningkatkan parameter h hingga menjadi
besar. Itu memberikan perilaku thresholding jika-maka-yang lain . Kedua,
untuk mendapatkan ambang batas yang benar, kami akan memilih
b approx−3h/2. Cobalah, dan lihat cara kerjanya\!

Ini seperti apa, ketika kita menggunakan h=10:

![http://neuralnetworksanddeeplearning.com/images/play.png](media/image77.png)

Bahkan untuk nilai h yang relatif sederhana ini, kami mendapatkan fungsi
menara yang cukup bagus. Dan, tentu saja, kita dapat membuatnya sebagus
yang kita inginkan dengan meningkatkan h lebih jauh, dan menjaga biasnya
menjadi b=−3j/2.

Mari kita coba menempelkan dua jaringan seperti itu bersama-sama, untuk
menghitung dua fungsi menara yang berbeda. Untuk memperjelas peran
masing-masing dari dua sub-jaringan, saya telah menempatkannya dalam
kotak terpisah, di bawah ini: setiap kotak menghitung fungsi menara,
menggunakan teknik yang dijelaskan di atas. Grafik di sebelah kanan
menunjukkan keluaran terbobot dari lapisan *kedua yang* tersembunyi,
yaitu, kombinasi fungsi menara yang terbobot.

Secara khusus, Anda dapat melihat bahwa dengan memodifikasi bobot di
lapisan akhir Anda dapat mengubah ketinggian menara keluaran.

Ide yang sama dapat digunakan untuk menghitung menara sebanyak yang kita
suka. Kita juga bisa membuatnya setipis yang kita mau, dan berapa pun
tinggi yang kita suka. Sebagai hasilnya, kami dapat memastikan bahwa
keluaran terbobot dari lapisan tersembunyi kedua mendekati fungsi apa
pun yang diinginkan dari dua variabel:

Secara khusus, dengan membuat output terbobot dari lapisan tersembunyi
kedua sebagai pendekatan yang baik untuk  sigma−1 circf, kami memastikan
output dari jaringan kami akan menjadi perkiraan yang baik untuk fungsi
yang diinginkan, f .

Bagaimana dengan fungsi lebih dari dua variabel?

Mari kita coba tiga variabel x1,x2,x3. Jaringan berikut dapat digunakan
untuk menghitung fungsi menara dalam empat dimensi:

Di sini, x1,x2,x3 menunjukkan input ke jaringan. S1,t1 dan seterusnya
adalah titik langkah untuk neuron - yaitu, semua bobot di lapisan
pertama besar, dan bias ditetapkan untuk memberikan poin langkah
s1,t1,s2, ldots. Bobot pada lapisan kedua bergantian +h,−h, di mana h
adalah angka yang sangat besar. Dan bias output adalah −5j/2.

Jaringan ini menghitung fungsi yang 1 asalkan tiga persyaratan dipenuhi:
x1 adalah antara s1 dan t1; x2 adalah antara s2 dan t2; dan x3 adalah
antara s3 dan t3. Jaringannya adalah 0 di tempat lain. Yaitu, ini
semacam menara yang 1 di wilayah input kecil, dan 0 di tempat lain.

Dengan menempelkan banyak jaringan seperti itu, kita bisa mendapatkan
menara sebanyak yang kita inginkan, dan memperkirakan fungsi
sewenang-wenang dari tiga variabel. Ide yang sama persis bekerja dalam
dimensi m. Satu-satunya perubahan yang diperlukan adalah membuat bias
output (−m+1/2)h, untuk mendapatkan perilaku sandwich yang tepat untuk
menaikkan level dataran tinggi.

Oke, jadi sekarang kita tahu cara menggunakan *jaringan saraf (neural
networks)* untuk memperkirakan fungsi nyata dari banyak variabel.
Bagaimana dengan fungsi bernilai vektor f(x1, ldots,xm) dalamRn? Tentu
saja, fungsi seperti itu dapat dianggap sebagai hanya n fungsi bernilai
riil yang terpisah, f1(x1, ldots,xm),f2(x1, ldots,xm), dan sebagainya.
Jadi kami membuat jaringan yang mendekati f1, jaringan lain untuk f2,
dan seterusnya. Dan kemudian kita cukup merekatkan semua jaringan
bersama. Jadi itu juga mudah diatasi.

#### [Masalah](http://neuralnetworksanddeeplearning.com/chap4.html#problem_863961) 

  - Kami telah melihat cara menggunakan jaringan dengan dua lapisan
    tersembunyi untuk memperkirakan fungsi sewenang-wenang. Dapatkah
    Anda menemukan bukti yang menunjukkan bahwa itu mungkin hanya dengan
    satu lapisan tersembunyi? Sebagai petunjuk, cobalah bekerja dalam
    kasus hanya dua variabel input, dan tunjukkan bahwa: (a)
    dimungkinkan untuk mendapatkan fungsi langkah tidak hanya dalam arah
    x atau y, tetapi dalam arah yang sewenang-wenang; (B) dengan
    menambahkan banyak konstruksi dari bagian (a) itu mungkin untuk
    memperkirakan fungsi menara yang berbentuk bundar, daripada persegi
    panjang; (c) menggunakan menara bundar ini, dimungkinkan untuk
    memperkirakan fungsi yang sewenang-wenang. Untuk melakukan bagian
    (c) mungkin membantu menggunakan ide-ide dari [sedikit kemudian
    dalam bab
    ini](http://neuralnetworksanddeeplearning.com/chap4.html#fixing_up_the_step_functions)
    .

### [Perluasan di luar neuron sigmoid](http://neuralnetworksanddeeplearning.com/chap4.html#extension_beyond_sigmoid_neurons) 

Kami telah membuktikan bahwa jaringan yang terdiri dari neuron sigmoid
dapat menghitung fungsi apa pun. Ingat bahwa dalam neuron sigmoid input
x1,x2, ldots menghasilkan output  sigma( sumjwjxj+b), di mana wj adalah
bobot, b adalah bias, dan  sigma adalah fungsi sigmoid:

Bagaimana jika kita mempertimbangkan jenis neuron yang berbeda, yang
menggunakan beberapa fungsi aktivasi lainnya, s(z):

Yaitu, kita akan berasumsi bahwa jika neuron kita memasukkan
x1,x2, ldots, bobot w1,w2, ldots dan bias b, maka outputnya adalah
s( sumjwjxj+b).

Kita dapat menggunakan fungsi aktivasi ini untuk mendapatkan fungsi
langkah, seperti yang kita lakukan dengan sigmoid. Coba tingkatkan bobot
berikut ini, katakanlah ke w=100:

Sama seperti dengan sigmoid, ini menyebabkan fungsi aktivasi
berkontraksi, dan akhirnya itu menjadi pendekatan yang sangat baik untuk
fungsi langkah. Coba ubah bias, dan Anda akan melihat bahwa kita dapat
mengatur posisi langkah ke mana pun yang kita pilih. Jadi kita bisa
menggunakan semua trik yang sama seperti sebelumnya untuk menghitung
fungsi yang diinginkan.

Properti apa yang dibutuhkan s(z) untuk dipenuhi agar ini berfungsi?
Kita perlu mengasumsikan bahwa s(z) didefinisikan dengan baik sebagai
z rightarrow− infty dan z rightarrow infty. Dua batas ini adalah dua
nilai yang diambil oleh fungsi langkah kita. Kita juga perlu
mengasumsikan bahwa batas-batas ini berbeda satu sama lain. Jika tidak,
tidak akan ada langkah, hanya grafik datar\! Tetapi asalkan fungsi
aktivasi s(z) memenuhi sifat-sifat ini, neuron yang didasarkan pada
fungsi aktivasi tersebut bersifat universal untuk perhitungan.

#### [Masalah](http://neuralnetworksanddeeplearning.com/chap4.html#problems_963556) 

  - Sebelumnya dalam buku ini kami bertemu jenis neuron lain yang
    dikenal sebagai [unit linear yang
    diperbaiki](http://neuralnetworksanddeeplearning.com/chap3.html#other_models_of_artificial_neuron)
    . Jelaskan mengapa neuron semacam itu tidak memenuhi kondisi yang
    baru saja diberikan untuk universalitas. Temukan bukti universalitas
    yang menunjukkan bahwa unit linear yang diperbaiki adalah universal
    untuk perhitungan.

  - Misalkan kita mempertimbangkan neuron linier, yaitu neuron dengan
    fungsi aktivasi s(z)=z. Jelaskan mengapa neuron linier tidak
    memenuhi kondisi yang baru saja diberikan untuk universalitas.
    Tunjukkan bahwa neuron semacam itu tidak dapat digunakan untuk
    melakukan perhitungan universal.

### [Memperbaiki fungsi langkah](http://neuralnetworksanddeeplearning.com/chap4.html#fixing_up_the_step_functions) 

Hingga saat ini, kami mengasumsikan bahwa neuron kami dapat menghasilkan
fungsi langkah dengan tepat. Itu perkiraan yang cukup bagus, tetapi itu
hanya perkiraan. Bahkan, akan ada jendela kegagalan yang sempit, yang
diilustrasikan dalam grafik berikut, di mana fungsi tersebut berperilaku
sangat berbeda dari fungsi langkah:

Di jendela kegagalan ini penjelasan yang saya berikan untuk
universalitas akan gagal.

Sekarang, ini bukan kegagalan yang mengerikan. Dengan membuat bobot
masukan ke neuron cukup besar kita dapat membuat jendela kegagalan ini
sekecil yang kita mau. Tentu saja, kita bisa membuat jendela jauh lebih
sempit daripada yang saya tunjukkan di atas - lebih sempit, memang,
daripada yang bisa dilihat mata kita. Jadi mungkin kita tidak perlu
terlalu khawatir tentang masalah ini.

Meskipun demikian, alangkah baiknya memiliki beberapa cara untuk
mengatasi masalah tersebut.

Padahal, masalahnya ternyata mudah diperbaiki. Mari kita lihat perbaikan
untuk fungsi komputasi jaringan saraf (*neural networks*) hanya dengan
satu input dan satu output. Gagasan yang sama juga berfungsi untuk
mengatasi masalah ketika ada lebih banyak input dan output.

Secara khusus, misalkan kita ingin jaringan kita menghitung beberapa
fungsi, f. Seperti sebelumnya, kami melakukan ini dengan mencoba
mendesain jaringan kami sehingga keluaran terbobot dari lapisan neuron
tersembunyi kami adalah  sigma−1 circf(x):

Jika kita melakukan ini menggunakan teknik yang dijelaskan sebelumnya,
kita akan menggunakan neuron tersembunyi untuk menghasilkan urutan
fungsi benjolan:

Sekali lagi, saya telah melebih-lebihkan ukuran jendela kegagalan, agar
lebih mudah dilihat. Seharusnya cukup jelas bahwa jika kita menambahkan
semua fungsi bump ini ke atas kita akan berakhir dengan perkiraan yang
masuk akal ke  sigma−1 circf(x), kecuali di dalam jendela kegagalan.

Misalkan alih-alih menggunakan perkiraan yang baru saja dijelaskan, kami
menggunakan satu set neuron tersembunyi untuk menghitung perkiraan
menjadi *setengah dari* fungsi tujuan awal kami, yaitu, ke
 sigma−1 circf(x)/2. Tentu saja, ini terlihat seperti versi grafik
terakhir yang diperkecil:

Dan anggaplah kita menggunakan set neuron tersembunyi lainnya untuk
menghitung perkiraan menjadi  sigma−1 circf(x)/2, tetapi dengan basis
gundukan *bergeser* setengah dari lebar gundukan:

Sekarang kita memiliki dua pendekatan berbeda ke  sigma−1 circf(x)/2.
Jika kita menjumlahkan dua perkiraan kita akan mendapatkan perkiraan
keseluruhan ke  sigma−1 circf(x). Perkiraan keseluruhan itu masih akan
mengalami kegagalan di jendela kecil. Tetapi masalahnya akan jauh lebih
sedikit dari sebelumnya. Alasannya adalah bahwa titik-titik di jendela
kegagalan untuk satu perkiraan tidak akan berada di jendela kegagalan
untuk yang lain. Dan perkiraannya akan menjadi faktor sekitar 2 lebih
baik di jendela itu.

Kita dapat melakukan lebih baik lagi dengan menambahkan sejumlah besar,
M, dari perkiraan yang tumpang tindih ke fungsi  sigma−1 circf(x)/M.
Asalkan jendela kegagalan cukup sempit, suatu titik hanya akan ada dalam
satu jendela kegagalan. Dan asalkan kita menggunakan sejumlah besar M
perkiraan yang tumpang tindih, hasilnya akan menjadi perkiraan
keseluruhan yang sangat baik.

### [Kesimpulan](http://neuralnetworksanddeeplearning.com/chap4.html#conclusion) 

Penjelasan untuk universalitas yang telah kita bahas tentu bukan resep
praktis untuk bagaimana menghitung menggunakan jaringan saraf\! Dalam
hal ini, ini seperti bukti universalitas untuk gerbang NAND dan
sejenisnya.Untuk alasan ini, saya lebih fokus pada upaya membuat
konstruksi jelas dan mudah diikuti, dan bukan pada mengoptimalkan detail
konstruksi. Namun, Anda mungkin menganggapnya sebagai latihan yang
menyenangkan dan instruktif untuk melihat apakah Anda dapat meningkatkan
konstruksinya.

Meskipun hasilnya tidak langsung berguna dalam membangun jaringan, ini
penting karena menghilangkan pertanyaan apakah fungsi tertentu dapat
dihitung menggunakan jaringan saraf. Jawaban untuk pertanyaan itu selalu
"ya". Jadi pertanyaan yang tepat untuk ditanyakan bukanlah apakah fungsi
tertentu dapat dihitung, melainkan apa cara yang *baik* untuk menghitung
fungsi.

The universality construction we've developed uses just two hidden
layers to compute an arbitrary function. Furthermore, as we've
discussed, it's possible to get the same result with just a single
hidden layer. Given this, you might wonder why we would ever be
interested in deep networks, ie, networks with many hidden layers. Can't
we simply replace those networks with shallow, single hidden layer
networks?

**Ucapan** terima kasih **Bab:** Terima kasih kepada [Jen
Dodd](http://jendodd.com) dan [Chris
Olah](http://colah.github.io/about.html) untuk banyak diskusi tentang
universalitas dalam jaringan saraf. Terima kasih saya, khususnya, kepada
Chris karena menyarankan penggunaan tabel pencarian untuk membuktikan
universalitas. Bentuk visual interaktif bab ini terinspirasi oleh karya
orang-orang seperti [Mike
Bostock](http://bost.ocks.org/mike/algorithms/) , [Amit
Patel](http://www-cs-students.stanford.edu/~amitp/) , [Bret
Victor](http://worrydream.com) , dan [Steven Wittens](http://acko.net/)
.

Meskipun pada prinsipnya itu mungkin, ada alasan praktis yang baik untuk
menggunakan jaringan yang dalam. Sebagaimana dikemukakan dalam
[Bab 1](http://neuralnetworksanddeeplearning.com/chap1.html#toward_deep_learning),
jaringan yang dalam memiliki struktur hierarkis yang membuatnya
beradaptasi dengan baik untuk mempelajari hierarki pengetahuan yang
tampaknya berguna dalam menyelesaikan masalah dunia nyata. Secara lebih
konkret, ketika menyerang masalah seperti pengenalan gambar, ada baiknya
menggunakan sistem yang tidak hanya memahami piksel individual, tetapi
juga konsep yang semakin kompleks: mulai dari tepi hingga bentuk
geometris sederhana, sampai pada adegan multi-objek yang kompleks. .
Dalam bab-bab selanjutnya, kita akan melihat bukti yang menunjukkan
bahwa jaringan yang dalam melakukan pekerjaan yang lebih baik daripada
jaringan yang dangkal untuk mempelajari hierarki pengetahuan semacam
itu. Singkatnya: universalitas memberi tahu kita bahwa *jaringan saraf
(neural networks)* dapat menghitung fungsi apa pun; dan bukti empiris
menunjukkan bahwa jaringan yang dalam adalah jaringan yang paling baik
diadaptasi untuk mempelajari fungsi-fungsi yang berguna dalam memecahkan
banyak masalah di dunia nyata.

. .

Dalam karya akademis, silakan kutip buku ini sebagai: Michael A.
Nielsen, "Neural Networks and Deep Learning", Determination Press,
2015  
  
Karya ini dilisensikan di bawah [Lisensi Creative Commons
Attribution-NonCommercial 3.0
Unported](http://creativecommons.org/licenses/by-nc/3.0/deed.en_GB) .
Ini artinya Anda bebas menyalin, membagikan, dan membuat buku ini,
tetapi tidak untuk menjualnya. Jika Anda tertarik menggunakan komersial,
silakan [hubungi saya](mailto:mn@michaelnielsen.org) . Pembaruan
terakhir: Sel 11 Jun 16:58:53 2019  
  
  
![Lisensi Creative Commons](media/image33.png)

# [BAB 5](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw) 

# [Mengapa jaringan saraf (*neural networks*) yang dalam sulit untuk dilatih?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw) 

[jaringan saraf (*neural networks*) Tiruan dan Pembelajaran
Jauh](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhic73V7KqVjxIPGNbaQNJ2530s4GA)

[Tentang buku
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/about.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh4WEv8VZZCecHFGon_fBfEj9Fk-g)

[Tentang latihan dan
masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/exercises_and_problems.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgGXxYFYgdq20f8ymqVw5JGPzA2tA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Menggunakan
jaring saraf untuk mengenali angka tulisan
tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Cara
kerja algoritma
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Meningkatkan
cara belajar jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Bukti
visual bahwa jaring saraf dapat menghitung fungsi apa
pun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgzJKLAEjvxFJSTt899AGWkWymaQw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Mengapa
jaringan saraf (*neural networks*) yang dalam sulit untuk
dilatih?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[*Pembelajaran
dalam (deep
learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ)

[Lampiran: Apakah ada algoritma *sederhana* untuk
intelijen?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/sai.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi_r2W6B006rb7gK3F4bzy6prrdaQ)

[Ucapan Terima
Kasih](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/acknowledgements.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2YHKQpAuvZNHAiXn0Z6HVn-0KQA)

[Pertanyaan yang Sering
Diajukan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

Jika Anda mendapat manfaat dari buku ini, silakan berikan sumbangan
kecil. Saya menyarankan $ 5, tetapi Anda dapat memilih jumlahnya.

Top of Form

Bottom of Form

Sebagai alternatif, Anda dapat memberikan donasi dengan mengirimkan saya
Bitcoin, di alamat 1Kd6tXH5SDAmiFb49J9hknG5pqj7KStSAx

Sponsor  
![http://neuralnetworksanddeeplearning.com/assets/exxact.png](media/image36.png)

Workstation Deep Learning mulai dari $ 6.999: [pelajari lebih
lanjut](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.exxactcorp.com/Deep-Learning-NVIDIA-GPU-Solutions%3Futm_source%3Dneuralnetworksanddeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dsponsors&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj6rGsPToAcGlYjeEJXAHXJspW3eQ)

![http://neuralnetworksanddeeplearning.com/assets/lambda.png](media/image37.png)

[Workstation, Server, dan Laptop Belajar
dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://lambdalabs.com/%3Futm_source%3Dneuralnetworksdeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dblogin%26utm_content%3Drtext&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhmW9twAd-_7XhnUCemcjX98sl7gw)

![http://neuralnetworksanddeeplearning.com/assets/gsquared.png](media/image38.png)![http://neuralnetworksanddeeplearning.com/assets/tineye.png](media/image39.png)![http://neuralnetworksanddeeplearning.com/assets/visionsmarts.png](media/image40.png)

Terima kasih kepada semua
[pendukung](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/supporters.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj9HdVAwFQiYjPlo--NhrlXsSgZ2w)
yang memungkinkan buku ini, dengan terima kasih terutama kepada Pavel
Dudrenov. Terima kasih juga kepada semua kontributor di [Bugfinder Hall
of
Fame](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/bugfinder.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhbjVenylI9ODfotXyQdFoaBBrKaQ)
.

Sumber daya

[Michael Nielsen di
Twitter](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://twitter.com/michael_nielsen&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiM6kfoM32wXnoIMmahlwqfNqEWPg)

[Pesan
FAQ](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

[Repositori
kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhUDc58iR7PU8_gSuNnY9hUhxv0pw)

[Milis pengumuman proyek Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://eepurl.com/0Xxjb&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhCYC3lUQysyAb2pDyD_0ubQrqOeg)

[Deep
Learning](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.deeplearningbook.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhrv253n32Mv6Uv5S3BDOvpBcn5rg)
, buku karya Ian Goodfellow, Yoshua Bengio, dan Aaron Courville

[cognitivemedium.com](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://cognitivemedium.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgEBgr9y1U5WD3Da33Y88SX6zvRPA)

![http://neuralnetworksanddeeplearning.com/assets/Michael\_Nielsen\_Web\_Small.jpg](media/image41.jpeg)

Oleh [Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://michaelnielsen.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7zg7S5OLu9AePjnKFialijDRDZQ)
/ Jun 2019

Bayangkan Anda seorang insinyur yang diminta mendesain komputer dari
awal. Suatu hari Anda sedang bekerja di kantor Anda, merancang sirkuit
logis, mengatur AND gerbang, OR gerbang, dan sebagainya, ketika bos Anda
berjalan dengan berita buruk. Pelanggan baru saja menambahkan
persyaratan desain yang mengejutkan: sirkuit untuk seluruh komputer
harus sedalam dua lapis:

![http://neuralnetworksanddeeplearning.com/images/shallow\_circuit.png](media/image80.png)

Anda tercengang, dan memberi tahu atasan Anda: "Pelanggan itu gila\!"

Bos Anda menjawab: "Saya pikir mereka juga gila. Tapi apa yang
diinginkan pelanggan, mereka dapatkan."

Bahkan, ada perasaan terbatas di mana pelanggan tidak gila. Misalkan
Anda diizinkan untuk menggunakan gerbang logika khusus yang memungkinkan
Anda AND bersama-sama input sebanyak yang Anda inginkan. Dan Anda juga
diizinkan gerbang NAND banyak-input, yaitu gerbang yang dapat AND
beberapa input dan kemudian meniadakan output. Dengan gerbang khusus ini
ternyata memungkinkan untuk menghitung fungsi apa pun menggunakan
sirkuit yang dalamnya hanya dua lapisan.

Tetapi hanya karena sesuatu itu mungkin tidak membuatnya menjadi ide
yang baik. Dalam praktiknya, ketika memecahkan masalah desain sirkuit
(atau sebagian besar masalah algoritma apa pun), kita biasanya mulai
dengan mencari tahu bagaimana menyelesaikan sub-masalah, dan kemudian
secara bertahap mengintegrasikan solusi. Dengan kata lain, kami
membangun solusi melalui berbagai lapisan abstraksi.

Sebagai contoh, misalkan kita sedang mendesain rangkaian logis untuk
melipatgandakan dua angka. Kemungkinannya adalah kita ingin membangunnya
dari sub-sirkuit yang melakukan operasi seperti menambahkan dua angka.
Sub-sirkuit untuk menambahkan dua angka pada gilirannya akan dibangun
dari sub-sub-sirkuit untuk menambahkan dua bit. Secara kasar, sirkuit
kita akan terlihat seperti:

![http://neuralnetworksanddeeplearning.com/images/circuit\_multiplication.png](media/image81.png)

Artinya, rangkaian terakhir kami mengandung setidaknya tiga lapisan
elemen rangkaian. Bahkan, itu mungkin akan berisi lebih dari tiga
lapisan, karena kita memecah sub-tugas menjadi unit yang lebih kecil
daripada yang saya jelaskan. Tetapi Anda mendapatkan ide umum.

Jadi sirkuit yang dalam membuat proses desain lebih mudah. Tapi mereka
tidak hanya membantu desain. Sebenarnya, ada bukti matematis yang
menunjukkan bahwa untuk beberapa fungsi, sirkuit yang sangat dangkal
membutuhkan elemen sirkuit yang lebih banyak untuk menghitung daripada
sirkuit yang dalam. Sebagai contoh, serangkaian makalah terkenal di awal
1980-an \* \* Sejarahnya agak rumit, jadi saya tidak akan memberikan
referensi rinci. Lihat makalah Johan Håstad 2012 [tentang korelasi
paritas dan sirkuit
kecil](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://eccc.hpi-web.de/report/2012/137/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg13u83U5Gt80pTlCk1HVWj7x7RiQ)
untuk penjelasan sejarah awal dan referensi. menunjukkan bahwa
menghitung paritas seperangkat bit membutuhkan banyak gerbang secara
eksponensial, jika dilakukan dengan rangkaian yang dangkal. Di sisi
lain, jika Anda menggunakan sirkuit yang lebih dalam, mudah untuk
menghitung paritas menggunakan sirkuit kecil: Anda hanya menghitung
paritas pasangan bit, kemudian menggunakan hasil tersebut untuk
menghitung paritas pasangan pasangan bit, dan seterusnya, membangun
dengan cepat ke paritas keseluruhan. Jadi, sirkuit dalam dapat secara
intrinsik jauh lebih kuat daripada sirkuit dangkal.

Hingga sekarang, buku ini telah mendekati *jaringan saraf (neural
networks)* seperti pelanggan gila. Hampir semua jaringan yang bekerja
sama dengan kami hanya memiliki satu lapisan neuron yang tersembunyi
(ditambah lapisan input dan output):

![http://neuralnetworksanddeeplearning.com/images/tikz35.png](media/image82.png)

Jaringan sederhana ini sangat berguna: pada bab-bab sebelumnya kami
menggunakan jaringan seperti ini untuk mengklasifikasikan angka tulisan
tangan dengan akurasi lebih dari 98 persen\! Meskipun demikian, secara
intuitif kami berharap jaringan dengan banyak lapisan tersembunyi
menjadi lebih kuat:

![http://neuralnetworksanddeeplearning.com/images/tikz36.png](media/image83.png)

Jaringan seperti itu dapat menggunakan lapisan perantara untuk membangun
beberapa lapisan abstraksi, seperti yang kita lakukan di sirkuit
Boolean. Sebagai contoh, jika kita melakukan pengenalan pola visual,
maka neuron pada lapisan pertama mungkin belajar mengenali tepi, neuron
pada lapisan kedua dapat belajar mengenali bentuk yang lebih kompleks,
misalnya segitiga atau persegi panjang, dibangun dari tepi. Lapisan
ketiga akan mengenali bentuk yang lebih kompleks. Dan seterusnya.
Abstraksi berlapis-lapis ini nampaknya memberikan jaringan yang kuat
keuntungan menarik dalam pembelajaran untuk memecahkan masalah
pengenalan pola yang kompleks. Selain itu, seperti halnya dalam kasus
sirkuit, ada hasil teoritis yang menunjukkan bahwa jaringan yang dalam
secara intrinsik lebih kuat daripada jaringan dangkal \* \* Untuk
masalah dan arsitektur jaringan tertentu hal ini terbukti dalam [Jumlah
daerah respons dari jaringan umpan maju dengan potongan Aktivasi
linier-bijaksana](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://arxiv.org/pdf/1312.6098.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjJu04Fwh1QOOa9abtotkoisSQbtg)
, oleh Razvan Pascanu, Guido Montúfar, dan Yoshua Bengio (2014). Lihat
juga diskusi yang lebih informal di bagian 2 dari [Learning deep
architecture untuk
AI](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.iro.umontreal.ca/~bengioy/papers/ftml_book.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhNkWZlNREqJGpSN6Zu82vPT_ENDw)
, oleh Yoshua Bengio (2009). .

Bagaimana kita bisa melatih jaringan yang begitu dalam? Dalam bab ini,
kita akan mencoba melatih jaringan yang dalam menggunakan algoritma
pembelajaran pekerja keras kami - [keturunan gradien
stokastik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#learning_with_gradient_descent)
dengan
[backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)
. Tapi kami akan mengalami masalah, dengan jaringan kami yang dalam
tidak berkinerja lebih baik (jika ada) lebih baik dari jaringan yang
dangkal.

Kegagalan itu tampaknya mengejutkan dalam terang diskusi di atas.
Daripada menyerah pada jaringan yang dalam, kami akan menggali dan
mencoba memahami apa yang membuat jaringan mendalam kami sulit untuk
dilatih. Ketika kita melihat lebih dekat, kita akan menemukan bahwa
berbagai lapisan dalam jaringan kita yang dalam belajar dengan kecepatan
yang sangat berbeda. Secara khusus, ketika lapisan kemudian dalam
jaringan belajar dengan baik, lapisan awal sering macet selama
pelatihan, belajar hampir tidak ada sama sekali. Kesulitan ini bukan
hanya karena nasib buruk. Sebaliknya, kita akan menemukan ada alasan
mendasar perlambatan belajar terjadi, terhubung dengan penggunaan teknik
pembelajaran berbasis gradien kami.

Ketika kita mempelajari masalah lebih dalam, kita akan belajar bahwa
fenomena yang berlawanan juga dapat terjadi: lapisan awal mungkin
belajar dengan baik, tetapi lapisan selanjutnya bisa menjadi macet.
Bahkan, kita akan menemukan bahwa ada ketidakstabilan intrinsik yang
terkait dengan pembelajaran dengan penurunan gradien dalam *jaringan
saraf (neural networks)* banyak lapisan. Ketidakstabilan ini cenderung
menyebabkan lapisan awal atau lapisan berikutnya menjadi macet selama
pelatihan.

Ini semua terdengar seperti berita buruk. Tetapi dengan mempelajari
kesulitan-kesulitan ini, kita dapat mulai mendapatkan wawasan tentang
apa yang diperlukan untuk melatih jaringan yang dalam secara efektif.
Jadi penyelidikan ini adalah persiapan yang baik untuk bab selanjutnya,
di mana kita akan menggunakan *pembelajaran dalam (deep learning)* untuk
menyerang masalah pengenalan gambar.

### [Masalah gradien menghilang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw#the_vanishing_gradient_problem) 

Jadi, apa yang salah ketika kita mencoba melatih jaringan yang dalam?

Untuk menjawab pertanyaan itu, pertama mari kita kembali kasus jaringan
dengan hanya satu lapisan tersembunyi. Seperti biasa, kami akan
menggunakan masalah klasifikasi digit MNIST sebagai taman bermain kami
untuk pembelajaran dan eksperimen \* \* Saya memperkenalkan masalah dan
data MNIST di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#learning_with_gradient_descent)
dan di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#implementing_our_network_to_classify_digits)
. .

Jika mau, Anda dapat mengikuti dengan melatih jaringan di komputer Anda.
Tentu saja juga baik untuk membaca bersama. Jika Anda ingin mengikuti
siaran langsung, maka Anda memerlukan Python 2.7, Numpy, dan salinan
kode, yang bisa Anda dapatkan dengan mengkloning repositori yang relevan
dari baris perintah:

git clone
https://github.com/mnielsen/neural-networks-and-deep-learning.git

Jika Anda tidak menggunakan git maka Anda dapat mengunduh data dan kode
di
[sini](https://github.com/mnielsen/neural-networks-and-deep-learning/archive/master.zip)
. Anda harus berganti ke subdirektori src .

Kemudian, dari shell Python kami memuat data MNIST:

\>\>\> impor mnist\_loader

\>\>\> training\_data , validation\_data , test\_data = \\

... mnist\_loader . load\_data\_wrapper ()

Kami mengatur jaringan kami:

\>\>\> jaringan impor2

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 10 \])

Jaringan ini memiliki 784 neuron pada lapisan input, sesuai dengan
28 *kali*28=784

piksel pada gambar input. Kami menggunakan 30 neuron tersembunyi, serta
10 neuron keluaran, yang sesuai dengan 10 klasifikasi yang mungkin untuk
digit MNIST ('0', '1', '2',  *ldots*

, '9').

Mari kita coba melatih jaringan kita selama 30 zaman lengkap,
menggunakan mini-batch 10 contoh pelatihan sekaligus, tingkat
pembelajaran  *eta*=0,1

, dan parameter regularisasi  *lambda*=5,0

. Saat kami berlatih, kami akan memantau keakuratan klasifikasi pada
validation\_data \* \* Perhatikan bahwa jaringan kemungkinan akan
membutuhkan beberapa menit untuk berlatih, tergantung pada kecepatan
mesin Anda. Jadi, jika Anda menjalankan kode, Anda mungkin ingin
melanjutkan membaca dan kembali lagi nanti, jangan menunggu kode
tersebut selesai dieksekusi. :

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0.1 , lmbda = 5.0 ,

... evaluation\_data = validation\_data , monitor\_evaluation\_accuracy
= Benar )

Kami mendapatkan akurasi klasifikasi 96,48 persen (atau sekitar itu -
itu akan sedikit berbeda dari menjalankan ke menjalankan), dibandingkan
dengan hasil kami sebelumnya dengan konfigurasi yang sama.

Sekarang, mari kita tambahkan layer tersembunyi lainnya, juga dengan 30
neuron di dalamnya, dan coba pelatihan dengan parameter-hyper yang sama:

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 30 , 10 \])

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0.1 , lmbda = 5.0 ,

... evaluation\_data = validation\_data , monitor\_evaluation\_accuracy
= Benar )

Ini memberikan akurasi klasifikasi yang ditingkatkan, 96,90 persen. Itu
membesarkan hati: sedikit lebih dalam adalah membantu. Mari kita
tambahkan lapisan tersembunyi 30-neuron lainnya:

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 30 , 30 , 10 \])

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0.1 , lmbda = 5.0 ,

... evaluation\_data = validation\_data , monitor\_evaluation\_accuracy
= Benar )

Itu sama sekali tidak membantu. Bahkan, hasilnya turun kembali ke 96,57
persen, dekat dengan jaringan kami yang dangkal. Dan misalkan kita
menyisipkan satu lapisan tersembunyi lebih lanjut:

\>\>\> net = network2 . Jaringan (\[ 784 , 30 , 30 , 30 , 30 , 10 \])

\>\>\> bersih . SGD ( training\_data , 30 , 10 , 0.1 , lmbda = 5.0 ,

... evaluation\_data = validation\_data , monitor\_evaluation\_accuracy
= Benar )

Akurasi klasifikasi turun lagi, menjadi 96,53 persen. Itu mungkin bukan
penurunan yang signifikan secara statistik, tetapi juga tidak
menggembirakan.

Perilaku ini sepertinya aneh. Secara intuitif, lapisan tersembunyi
tambahan harus membuat jaringan mampu mempelajari fungsi klasifikasi
yang lebih kompleks, dan dengan demikian melakukan klasifikasi pekerjaan
yang lebih baik. Tentu saja, hal-hal yang seharusnya tidak menjadi lebih
buruk, karena lapisan tambahan dapat, dalam kasus terburuk, tidak
melakukan apa-apa \* \* Lihat [masalah ini
nanti](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw#identity_neuron)
untuk memahami bagaimana membangun lapisan tersembunyi yang tidak
melakukan apa-apa. . Tapi bukan itu yang terjadi.

Jadi apa yang terjadi? Mari kita asumsikan bahwa lapisan tersembunyi
ekstra benar-benar dapat membantu secara prinsip, dan masalahnya adalah
bahwa algoritma pembelajaran kami tidak menemukan bobot dan bias yang
tepat. Kami ingin mencari tahu apa yang salah dalam algoritma
pembelajaran kami, dan bagaimana melakukan lebih baik.

Untuk mendapatkan wawasan tentang apa yang salah, mari kita bayangkan
bagaimana jaringan belajar. Di bawah ini, saya telah merencanakan bagian
dari jaringan \[784,30,30,10\]

, yaitu jaringan dengan dua lapisan tersembunyi, masing-masing berisi
neuron tersembunyi $ 30. Setiap neuron dalam diagram memiliki bilah
kecil di atasnya, yang menunjukkan seberapa cepat neuron itu berubah
saat jaringan belajar. Bilah besar berarti bobot dan bias neuron berubah
dengan cepat, sedangkan bilah kecil berarti bobot dan bias berubah
perlahan. Lebih tepatnya, bar menunjukkan gradien
 *partialC*/ *partialb*

untuk setiap neuron, yaitu laju perubahan biaya sehubungan dengan bias
neuron. Kembali di
[Bab 2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_four_fundamental_equations_behind_backpropagation)
kita melihat bahwa kuantitas gradien ini mengontrol tidak hanya seberapa
cepat bias berubah selama pembelajaran, tetapi juga seberapa cepat bobot
input ke perubahan neuron juga. Jangan khawatir jika Anda tidak
mengingat detailnya: hal yang perlu diingat hanyalah bilah-bilah ini
menunjukkan seberapa cepat bobot dan bias masing-masing neuron berubah
ketika jaringan belajar.

Untuk menjaga diagram tetap sederhana, saya telah menunjukkan hanya enam
neuron teratas di dua lapisan tersembunyi. Saya telah menghilangkan
neuron input, karena mereka tidak memiliki bobot atau bias untuk
dipelajari. Saya juga menghilangkan neuron keluaran, karena kami
melakukan perbandingan lapisan-bijaksana, dan masuk akal untuk
membandingkan lapisan dengan jumlah neuron yang sama. Hasilnya diplot
pada awal pelatihan, yaitu, segera setelah jaringan diinisialisasi. Ini
mereka \* \* Data yang diplot dihasilkan menggunakan program
[generate\_gradient.py](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/fig/generate_gradient.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj3o7_o-3QF5pjcmXwrLJ6_gP7tzA)
. Program yang sama juga digunakan untuk menghasilkan hasil yang dikutip
kemudian di bagian ini. :

Jaringan diinisialisasi secara acak, sehingga tidak mengherankan bahwa
ada banyak variasi dalam seberapa cepat neuron belajar. Namun, satu hal
yang melompat keluar adalah bahwa bar di lapisan kedua yang tersembunyi
sebagian besar jauh lebih besar daripada bar di lapisan pertama yang
tersembunyi. Akibatnya, neuron di lapisan tersembunyi kedua akan belajar
sedikit lebih cepat daripada neuron di lapisan tersembunyi pertama.
Apakah ini hanya kebetulan, atau apakah neuron di lapisan tersembunyi
kedua cenderung belajar lebih cepat daripada neuron di lapisan
tersembunyi pertama secara umum?

Untuk menentukan apakah ini masalahnya, akan membantu jika ada cara
global untuk membandingkan kecepatan belajar di lapisan tersembunyi
pertama dan kedua. Untuk melakukan ini, mari kita menyatakan gradien
sebagai  *deltalj*= *partialC*/ *partialblj*

, yaitu gradien untuk neuron *j* th di *l* th layer \* \* Kembali ke
[Bab 2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_four_fundamental_equations_behind_backpropagation)
kami menyebutnya sebagai kesalahan, tetapi di sini kami akan mengadopsi
istilah informal "gradien". Saya katakan "informal" karena tentu saja
ini tidak secara eksplisit memasukkan turunan sebagian dari biaya
sehubungan dengan bobot,  *parsialC*/ *parsialw*. . Kita dapat
menganggap gradien  *delta*1 sebagai vektor yang entri-entrinya
menentukan seberapa cepat lapisan tersembunyi pertama belajar, dan
 *delta*2 sebagai vektor yang entri-entrinya menentukan seberapa cepat
lapisan tersembunyi kedua itu pelajari. Kami kemudian akan menggunakan
panjang vektor-vektor ini sebagai (kasar\!) Pengukuran global kecepatan
di mana lapisan belajar. Jadi, misalnya, panjangnya $ \\ | \\ delta ^ 1
\\ |
*mengukurkecepatanpembelajaranlayertersembunyipertama*,*sementarapanjangnya*

\\ | \\ delta ^ 2 \\ | $ mengukur kecepatan pembelajaran lapisan
tersembunyi kedua.

Dengan definisi ini, dan dalam konfigurasi yang sama seperti yang
diplotkan di atas, kami menemukan $ \\ | \\ delta ^ 1 \\ | = 0,07 \\
ldots *dan*

\\ | \\ delta ^ 2 \\ | = 0,31 \\ ldots $. Jadi ini mengkonfirmasi
kecurigaan kami sebelumnya: neuron di lapisan tersembunyi kedua
benar-benar belajar lebih cepat daripada neuron di lapisan tersembunyi
pertama.

Apa yang terjadi jika kita menambahkan lebih banyak lapisan tersembunyi?
Jika kita memiliki tiga lapisan tersembunyi, dalam jaringan
\[784,30,30,30,10\]

, maka kecepatan pembelajaran masing-masing berubah menjadi 0,012,
0,060, dan 0,283. Sekali lagi, lapisan tersembunyi sebelumnya belajar
lebih lambat dari lapisan tersembunyi nanti. Misalkan kita menambahkan
lapisan lain dengan 30

neuron tersembunyi. Dalam hal itu, kecepatan belajar masing-masing
adalah 0,003, 0,017, 0,070, dan 0,285. Pola ini berlaku: lapisan awal
belajar lebih lambat dari lapisan selanjutnya.

Kami telah melihat kecepatan belajar di awal pelatihan, yaitu, tepat
setelah jaringan diinisialisasi. Bagaimana kecepatan belajar berubah
saat kita melatih jaringan kita? Mari kita kembali untuk melihat
jaringan hanya dengan dua lapisan tersembunyi. Kecepatan belajar berubah
sebagai berikut:

![http://neuralnetworksanddeeplearning.com/images/training\_speed\_2\_layers.png](media/image84.png)

Untuk menghasilkan hasil ini, saya menggunakan keturunan gradien batch
dengan hanya 1.000 gambar pelatihan, melatih lebih dari 500 zaman. Ini
sedikit berbeda dari cara yang biasa kita latih - Saya tidak menggunakan
mini-batch, dan hanya 1.000 gambar pelatihan, daripada 50.000 set
pelatihan gambar penuh. Saya tidak mencoba melakukan sesuatu secara
diam-diam, atau menarik wol ke atas mata Anda, tetapi ternyata
menggunakan keturunan stochastic gradient mini-batch memberikan hasil
yang jauh lebih ribut (walaupun sangat mirip, ketika Anda menghilangkan
noise). Menggunakan parameter yang saya pilih adalah cara mudah
menghaluskan hasilnya, jadi kita bisa melihat apa yang terjadi.

Dalam hal apa pun, seperti yang Anda lihat, kedua lapisan mulai belajar
dengan kecepatan yang sangat berbeda (seperti yang sudah kita ketahui).
Kecepatan di kedua lapisan kemudian turun dengan sangat cepat, sebelum
rebound. Tetapi melalui itu semua, lapisan tersembunyi pertama belajar
jauh lebih lambat daripada lapisan tersembunyi kedua.

Bagaimana dengan jaringan yang lebih kompleks? Inilah hasil dari
percobaan serupa, tetapi kali ini dengan tiga lapisan tersembunyi
(\[784,30,30,30,10\]

network):

![http://neuralnetworksanddeeplearning.com/images/training\_speed\_3\_layers.png](media/image85.png)

Sekali lagi, lapisan tersembunyi awal belajar jauh lebih lambat daripada
lapisan tersembunyi nanti. Terakhir, mari kita tambahkan lapisan
tersembunyi keempat (\[784,30,30,30,30,10\]

jaringan), dan lihat apa yang terjadi ketika kita melatih:

![http://neuralnetworksanddeeplearning.com/images/training\_speed\_4\_layers.png](media/image86.png)

Sekali lagi, lapisan tersembunyi awal belajar jauh lebih lambat daripada
lapisan tersembunyi nanti. Dalam hal ini, lapisan tersembunyi pertama
belajar sekitar 100 kali lebih lambat dari lapisan tersembunyi terakhir.
Tidak heran kami mengalami kesulitan melatih jaringan ini sebelumnya\!

Di sini kita memiliki pengamatan penting: setidaknya dalam beberapa
jaringan saraf (*neural networks*) yang dalam, gradien cenderung semakin
kecil ketika kita bergerak mundur melalui lapisan tersembunyi. Ini
berarti bahwa neuron di lapisan sebelumnya belajar jauh lebih lambat
daripada neuron di lapisan kemudian. Dan sementara kita telah melihat
ini hanya dalam satu jaringan, ada alasan mendasar mengapa ini terjadi
di banyak jaringan saraf. Fenomena ini dikenal sebagai *masalah gradien
yang hilang* \* Lihat [aliran Gradien dalam jaring berulang: kesulitan
mempelajari dependensi jangka
panjang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://citeseerx.ist.psu.edu/viewdoc/summary%3Fdoi%3D10.1.1.24.7321&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjI9Py1z_awk7jNI3tqkqHNMIpKnA)
, oleh Sepp Hochreiter, Yoshua Bengio, Paolo Frasconi, dan Jürgen
Schmidhuber (2001). Makalah ini mempelajari jaring saraf berulang,
tetapi fenomena penting adalah sama seperti pada jaringan feedforward
yang sedang kita pelajari. Lihat juga Tesis Diploma Sepp Hochreiter
sebelumnya, [Untersuchungen zu dynamischen neuronalen
Netzen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.idsia.ch/~juergen/SeppHochreiter1991ThesisAdvisorSchmidhuber.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj9lLv4_6unhu7tMQdKWb5Yl6ugmg)
(1991, dalam bahasa Jerman). .

Mengapa masalah gradien hilang terjadi? Adakah cara kita bisa
menghindarinya? Dan bagaimana kita harus menghadapinya dalam melatih
jaringan saraf (*neural networks*) yang dalam? Bahkan, kita akan segera
belajar bahwa itu tidak bisa dihindari, meskipun alternatifnya tidak
terlalu menarik, kadang-kadang: gradien menjadi jauh lebih besar di
lapisan sebelumnya\! Ini adalah *masalah gradien yang meledak* , dan itu
bukan berita yang jauh lebih baik daripada masalah gradien yang hilang.
Lebih umum, ternyata gradien dalam jaringan saraf (*neural networks*)
yang dalam *tidak stabil* , cenderung meledak atau menghilang di lapisan
sebelumnya. Ketidakstabilan ini merupakan masalah mendasar untuk
pembelajaran berbasis gradien dalam jaringan saraf (*neural networks*)
yang mendalam. Itu adalah sesuatu yang perlu kita pahami, dan, jika
mungkin, mengambil langkah-langkah untuk mengatasi.

Satu respons untuk menghilangkan gradien (atau tidak stabil) adalah
bertanya-tanya apakah mereka benar-benar masalah. Untuk sesaat menjauh
dari jaring saraf, bayangkan kami mencoba meminimalkan fungsi *f*(*x*)

dari variabel tunggal. Bukankah ini berita baik jika turunannya
*f*′(*x*)

kecil? Bukankah itu berarti kita sudah berada di dekat ekstrem? Dengan
cara yang sama, mungkinkah gradien kecil pada lapisan awal jaringan yang
dalam berarti kita tidak perlu melakukan banyak penyesuaian bobot dan
bias?

Tentu saja, ini bukan masalahnya. Ingatlah bahwa kami secara acak
menginisialisasi berat dan bias dalam jaringan. Sangat tidak mungkin
bobot dan bias awal kami akan melakukan pekerjaan dengan baik apa pun
yang kami inginkan untuk dilakukan jaringan kami. Agar konkret,
pertimbangkan lapisan pertama bobot dalam jaringan \[784,30,30,30,10\]

untuk masalah MNIST. Inisialisasi acak berarti lapisan pertama membuang
sebagian besar informasi tentang gambar input. Bahkan jika
lapisan-lapisan selanjutnya telah dilatih secara ekstensif, mereka masih
akan merasa sangat sulit untuk mengidentifikasi gambar input, hanya
karena mereka tidak memiliki informasi yang cukup. Dan itu tidak mungkin
menjadi kasus bahwa tidak banyak pembelajaran yang perlu dilakukan di
lapisan pertama. Jika kita akan melatih jaringan yang dalam, kita perlu
mencari cara untuk mengatasi masalah gradien menghilang.

### [Apa yang menyebabkan masalah gradien menghilang?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw#what's_causing_the_vanishing_gradient_problem_unstable_gradients_in_deep_neural_nets) [Gradien yang tidak stabil di jaring saraf dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw#what's_causing_the_vanishing_gradient_problem_unstable_gradients_in_deep_neural_nets) 

Untuk mengetahui mengapa masalah gradien hilang terjadi, mari kita
pertimbangkan jaringan saraf (*neural networks*) dalam yang paling
sederhana: satu dengan hanya satu neuron di setiap lapisan. Inilah
jaringan dengan tiga lapisan tersembunyi:

![http://neuralnetworksanddeeplearning.com/images/tikz37.png](media/image87.png)

Di sini, *w*1,*w*2, *ldots*

adalah bobot, *b*1,*b*2, *ldots* adalah bias, dan *C* adalah beberapa
fungsi biaya. Sekadar mengingatkan Anda bagaimana cara kerjanya, output
*aj* dari neuron *j* th adalah  *sigma*(*zj*), di mana  *sigma* adalah
[fungsi aktivasi sigmoid
yang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#sigmoid_neurons)
biasa, dan *zj*=*wjaj*−1+*bj* adalah input terbobot ke neuron. Saya
telah menarik biaya *C* pada akhir untuk menekankan bahwa biaya adalah
fungsi dari output jaringan, *a*4​​

: jika output aktual dari jaringan dekat dengan output yang diinginkan,
maka biayanya akan rendah, sedangkan jika jauh, biayanya akan tinggi.

Kita akan mempelajari gradien  *partialC*/ *partialb*1

yang terkait dengan neuron tersembunyi pertama. Kami akan mencari
ekspresi untuk  *partialC*/ *partialb*1

, dan dengan mempelajari ekspresi itu, kami akan memahami mengapa
masalah gradien hilang terjadi.

Saya akan mulai dengan hanya menunjukkan kepada Anda ekspresi untuk
 *partialC*/ *partialb*1

. Ini terlihat terlarang, tetapi sebenarnya memiliki struktur sederhana,
yang akan saya jelaskan sebentar lagi. Inilah ungkapan (abaikan
jaringan, untuk saat ini, dan perhatikan bahwa  *sigma*′ hanyalah
turunan dari fungsi  *sigma*

):

![http://neuralnetworksanddeeplearning.com/images/tikz38.png](media/image88.png)

Struktur dalam ekspresi adalah sebagai berikut: ada istilah $ \\ sigma
'(z\_j) dalam produk untuk setiap neuron dalam jaringan; istilah *wj*

berat untuk setiap berat dalam jaringan; dan istilah

partial C / \\ partial a\_4 $, sesuai dengan fungsi biaya di akhir.
Perhatikan bahwa saya telah menempatkan setiap istilah dalam ekspresi di
atas bagian jaringan yang sesuai. Jadi jaringan itu sendiri adalah
mnemonik untuk ekspresi.

Anda dapat menerima ungkapan ini begitu saja, dan langsung ke [diskusi
tentang bagaimana hubungannya dengan masalah gradien yang
hilang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw#discussion_why)
. Tidak ada salahnya melakukan hal ini, karena ungkapan ini adalah kasus
khusus dari [diskusi sebelumnya tentang propaganda
balik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#the_four_fundamental_equations_behind_backpropagation)
. Tetapi ada juga penjelasan sederhana tentang mengapa ungkapan itu
benar, jadi menyenangkan (dan mungkin mencerahkan) untuk melihat
penjelasan itu.

Bayangkan kita melakukan perubahan kecil  *Deltab*1

dalam bias *b*1. Itu akan memicu serangkaian perubahan yang mengalir di
seluruh jaringan. Pertama, itu menyebabkan perubahan  *Deltaa*1 dalam
output dari neuron tersembunyi pertama. Itu, pada gilirannya, akan
menyebabkan perubahan  *Deltaz*2 pada input terbobot ke neuron
tersembunyi kedua. Kemudian perubahan  *Deltaa*2 dalam output dari
neuron tersembunyi kedua. Dan seterusnya, sampai pada perubahan
 *DeltaC* dalam biaya pada output. Kita punya \\ begin {eqnarray} \\
frac {\\ partial C} {\\ partial b\_1} \\ approx \\ frac {\\ Delta C} {\\
Delta b\_1}. \\ tag {114} \\ end {eqnarray} Ini menunjukkan bahwa kita
dapat mengetahui ekspresi untuk gradien  *partialC*/ *partialb*1

dengan melacak efek setiap langkah dalam kaskade ini dengan cermat.

Untuk melakukan ini, mari kita pikirkan bagaimana  *Deltab*1

menyebabkan output *a*1 dari neuron tersembunyi pertama berubah. Kami
memiliki *a*1= *sigma*(*z*1)= *sigma*(*w*1*a*0+*b*1), jadi \\ begin
{eqnarray} \\ Delta a\_1 & \\ approx & \\ frac {\\ partial \\ sigma
(w\_1 a\_0 + b\_1)} {\\ partial b\_1} \\ Delta b\_1 \\ tag {115} \\\\ &
= & \\ sigma '(z\_1) \\ Delta b\_1. \\ tag {116} \\ end {eqnarray} Bahwa
 *sigma*′(*z*1) istilah akan terlihat familier: ini adalah istilah
pertama dalam ekspresi yang diklaim untuk gradien
 *partialC*/ *partialb*1. Secara intuitif, istilah ini mengubah
perubahan  *Deltab*1 dalam bias menjadi perubahan  *Deltaa*1 dalam
aktivasi output. Perubahan  *Deltaa*1 pada gilirannya menyebabkan
perubahan pada input terbobot *z*2=*w*2*a*1+*b*2 ke neuron tersembunyi
kedua: \\ begin {eqnarray} \\ Delta z\_2 & \\ approx & \\ frac {\\
partial z\_2} {\\ partial a\_1} \\ Delta a\_1 \\ tag {117} \\\\ & = &
w\_2 \\ Delta a\_1. \\ tag {118} \\ end {eqnarray} Menggabungkan
ekspresi kami untuk  *Deltaz*2 dan  *Deltaa*1, kami melihat bagaimana
perubahan dalam bias *b*1 merambat di sepanjang jaringan untuk
mempengaruhi *z*2: \\ begin {eqnarray} \\ Delta z\_2 & \\ approx & \\
sigma '(z\_1) w\_2 \\ Delta b\_1. \\ tag {119} \\ end {eqnarray} Sekali
lagi, itu akan terlihat familier: kita sekarang memiliki dua istilah
pertama dalam ekspresi yang diklaim untuk gradien
 *partialC*/ *partialb*1

.

Kita bisa terus seperti ini, melacak bagaimana perubahan menyebar
melalui seluruh jaringan. Pada setiap neuron kita mengambil istilah
 *sigma*′(*zj*)

, dan melalui setiap bobot kita mengambil istilah *wj*. Hasil akhirnya
adalah ekspresi yang menghubungkan perubahan akhir  *DeltaC* dalam biaya
dengan perubahan awal  *Deltab*1 dalam bias: \\ begin {eqnarray} \\
Delta C & \\ approx & \\ sigma '(z\_1) w\_2 \\ sigma' (z\_2) \\ ldots \\
sigma '(z\_4) \\ frac {\\ partial C} {\\ partial a\_4} \\ Delta b\_1. \\
tag {120} \\ end {eqnarray} Membagi dengan  *Deltab*1

kami memang mendapatkan ekspresi yang diinginkan untuk gradien: \\ begin
{eqnarray} \\ frac {\\ partial C} {\\ partial b\_1} = \\ sigma '(z\_1)
w\_2 \\ sigma' (z\_2) \\ ldots \\ sigma '(z\_4) \\ frac {\\ partial C}
{\\ partial a\_4 }. \\ tag {121} \\ end {eqnarray}

**Mengapa masalah gradien hilang terjadi:** Untuk memahami mengapa
masalah gradien hilang terjadi, mari kita secara eksplisit menuliskan
seluruh ekspresi untuk gradien: \\ begin {eqnarray} \\ frac {\\ partial
C} {\\ partial b\_1} = \\ sigma '(z\_1) \\, w\_2 \\ sigma' (z\_2) \\,
w\_3 \\ sigma '(z\_3) \\, w\_4 \\ sigma' (z\_4 ) \\, \\ frac {\\ partial
C} {\\ partial a\_4}. \\ tag {122} \\ end {eqnarray} Kecuali istilah
terakhir, ungkapan ini adalah produk dari istilah dalam bentuk
*wj* *sigma*′(*zj*)

. Untuk memahami bagaimana masing-masing istilah itu berperilaku, mari
kita lihat plot dari fungsi

sigma '$:

Derivatif mencapai maksimum pada  *sigma*′(0)=1/4

. Sekarang, jika kita menggunakan [pendekatan
standar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
untuk menginisialisasi bobot dalam jaringan, maka kita akan memilih
bobot menggunakan Gaussian dengan rata-rata 0 dan standar deviasi 1.
Jadi bobot biasanya akan memuaskan $ | w\_j | \<1 $. Menyatukan
pengamatan ini, kita melihat bahwa istilah *wj* *sigma*′(*zj*)

biasanya akan memuaskan $ | w\_j \\ sigma' (z\_j) | \<1/4 $. Dan ketika
kita mengambil produk dari banyak istilah seperti itu, produk akan
cenderung menurun secara eksponensial: semakin banyak istilah, semakin
kecil produk tersebut. Ini mulai berbau seperti penjelasan yang mungkin
untuk masalah gradien menghilang.

Untuk menjadikan ini semua lebih eksplisit, mari kita bandingkan
ekspresi untuk  *partialC*/ *partialb*1

dengan ekspresi untuk gradien sehubungan dengan bias nanti, katakanlah
 *partialC*/ *partialb*3. Tentu saja, kami belum secara eksplisit
membuat ekspresi untuk  *partialC*/ *partialb*3, tetapi ia mengikuti
pola yang sama seperti dijelaskan di atas untuk  *partialC*/ *partialb*1

. Berikut perbandingan kedua ekspresi:

![http://neuralnetworksanddeeplearning.com/images/tikz39.png](media/image89.png)

Kedua ungkapan itu memiliki banyak istilah. Tetapi gradien
 *partialC*/ *partialb*1 mencakup dua istilah tambahan masing-masing
dari bentuk *wj* *sigma*′(*zj*). Seperti yang telah kita lihat,
istilah-istilah tersebut biasanya kurang dari 1/4 besarnya. Maka gradien
 *partialC*/ *partialb*1 biasanya akan menjadi faktor 16 (atau lebih)
lebih kecil dari  *partialC*/ *partialb*3. Ini adalah asal penting dari
masalah gradien menghilang.

Tentu saja, ini adalah argumen informal, bukan bukti kuat bahwa masalah
gradien menghilang akan terjadi. Ada beberapa kemungkinan klausul
pelarian. Secara khusus, kita mungkin bertanya-tanya apakah bobot *wj*

dapat tumbuh selama pelatihan. Jika ya, mungkin istilah
*wj* *sigma*′(*zj*) dalam produk tidak akan lagi memenuhi $ | w\_j \\
sigma' (z\_j) | \<1/4 $. Memang, jika persyaratannya menjadi cukup besar
- lebih dari 1

\- maka kita tidak akan lagi memiliki masalah gradien menghilang.
Alih-alih, gradien akan benar-benar tumbuh secara eksponensial saat kita
bergerak mundur menembus lapisan. Alih-alih masalah gradien menghilang,
kita akan memiliki masalah gradien meledak.

**Masalah gradien meledak:** Mari kita lihat contoh eksplisit di mana
gradien meledak terjadi. Contohnya agak dibuat-buat: Saya akan
memperbaiki parameter dalam jaringan dengan cara yang benar untuk
memastikan kami mendapatkan gradien yang meledak. Tetapi meskipun
contohnya dibuat, ia memiliki keutamaan dengan tegas menetapkan bahwa
gradien yang meledak bukan hanya kemungkinan hipotetis, mereka
benar-benar dapat terjadi.

Ada dua langkah untuk mendapatkan gradien yang meledak. Pertama, kami
memilih semua bobot dalam jaringan untuk menjadi besar, katakanlah
*w*1=*w*2=*w*3=*w*4=100

. Kedua, kami akan memilih bias sehingga istilah $ \\ sigma '(z\_j)
tidak terlalu kecil. Itu sebenarnya cukup mudah dilakukan: yang perlu
kita lakukan hanyalah memilih bias untuk memastikan bahwa input terbobot
untuk setiap neuron adalah *zj*=0 (dan *ssigma*′(*zj*)=1/4). Jadi,
misalnya, kami ingin *z*1=*w*1*a*0+*b*1=0. Kita dapat mencapai ini
dengan menetapkan *b*1=−100∗*a*0. Kita dapat menggunakan ide yang sama
untuk memilih bias lainnya. Ketika kita melakukan ini, kita melihat
bahwa semua istilah *wj* *sigma*′(*zj*) sama dengan 100∗ *frac*14=25

. Dengan pilihan ini kita mendapatkan gradien yang meledak.

**Masalah gradien yang tidak stabil:** Masalah mendasar di sini bukanlah
masalah gradien yang hilang atau masalah gradien yang meledak. Itu bahwa
gradien di lapisan awal adalah produk dari syarat dari semua lapisan
kemudian. Ketika ada banyak lapisan, itu adalah situasi yang secara
intrinsik tidak stabil. Satu-satunya cara semua lapisan dapat belajar
dengan kecepatan yang sama adalah jika semua produk istilah mendekati
keseimbangan. Tanpa adanya mekanisme atau alasan yang mendasari
keseimbangan itu terjadi, sangat tidak mungkin terjadi hanya karena
kebetulan. Singkatnya, masalah sebenarnya di sini adalah bahwa *jaringan
saraf (neural networks)* menderita *masalah gradien yang tidak stabil* .
Akibatnya, jika kita menggunakan teknik pembelajaran berbasis gradien
standar, lapisan yang berbeda dalam jaringan akan cenderung belajar
dengan kecepatan yang sangat berbeda.

#### [Olahraga](http://neuralnetworksanddeeplearning.com/chap5.html#exercise_255808) 

  - Dalam diskusi kami tentang masalah gradien menghilang, kami
    menggunakan fakta bahwa $ | \\ sigma '(z) | \<1/4 $. Misalkan kita
    menggunakan fungsi aktivasi yang berbeda, yang turunannya bisa jauh
    lebih besar. Apakah itu membantu kita menghindari masalah gradien
    yang tidak stabil?

**Prevalensi masalah gradien menghilang:** Kami telah melihat bahwa
gradien dapat menghilang atau meledak di lapisan awal jaringan yang
dalam. Bahkan, ketika menggunakan neuron sigmoid gradien biasanya akan
hilang. Untuk mengetahui alasannya, perhatikan kembali ungkapan
|*w* *sigma*′(*z*)|

. Untuk menghindari masalah gradien yang hilang kita perlu $ | w \\
sigma '(z) | \\ geq 1 $. Anda mungkin berpikir ini bisa terjadi dengan
mudah jika *w* sangat besar. Namun, ini lebih sulit daripada yang
terlihat. Alasannya adalah bahwa istilah  *sigma*′(*z*) juga tergantung
pada *w*:  *sigma*′(*z*)= *sigma*′(*wa*+*b*), di mana *a* adalah
aktivasi input. Jadi ketika kita menghasilkan *w* besar, kita perlu
berhati-hati bahwa kita tidak secara bersamaan menghasilkan
 *sigma*′(*wa*+*b*) kecil. Itu ternyata menjadi kendala yang cukup
besar. Alasannya adalah ketika kita menghasilkan *w* besar, kita
cenderung menghasilkan *wa*+*b* sangat besar. Melihat grafik  *sigma*′
Anda dapat melihat bahwa ini menempatkan kita dalam "sayap" fungsi

sigma', di mana ia mengambil nilai yang sangat kecil. Satu-satunya cara
untuk menghindari ini adalah jika aktivasi input berada dalam kisaran
nilai yang cukup sempit (penjelasan kualitatif ini dibuat kuantitatif
dalam masalah pertama di bawah). Terkadang hal itu akan terjadi. Namun,
lebih sering hal itu tidak terjadi. Dan dalam kasus generik kita
memiliki gradien yang hilang.

#### [Masalah](http://neuralnetworksanddeeplearning.com/chap5.html#problems_778071) 

  - Pertimbangkan produk |*w* *sigma*′(*wa*+*b*)|

. Misalkan $ | w \\ sigma '(wa + b) | \\ geq 1 $. (1) Berargumen bahwa
ini hanya dapat terjadi jika $ | w | \\ geq 4 $. (2) Misalkan $ | w | \\
geq 4 ,*pertimbangkansekumpulanaktivasiinput* a *yang* | w \\ sigma '(wa
+ b) | \\ geq 1 $. Tunjukkan bahwa himpunan *a* yang memuaskan batasan
itu dapat berkisar pada suatu interval yang lebarnya tidak lebih besar
dari \\ begin {eqnarray} \\ frac {2} {| w |} \\ ln \\ kiri (\\ frac {| w
| (1+ \\ sqrt {1-4 / | w |})} {2} -1 \\ kanan) . \\ tag {123} \\ end
{eqnarray} (3) Perlihatkan secara numerik bahwa ekspresi di atas yang
membatasi lebar rentang paling besar di $ | w | \\ kira-kira 6,9
,*dimanadibutuhkannilai*

• \\ sekitar 0,45 $. Dan bahkan mengingat bahwa semuanya berbaris dengan
sempurna, kami masih memiliki rentang aktivasi input yang cukup sempit
yang dapat menghindari masalah gradien yang hilang.

• **Neuron identitas:** Pertimbangkan neuron dengan input tunggal, *x*,
bobot yang sesuai, *w*1, bias *b*, dan bobot *w*2 pada output. Tunjukkan
bahwa dengan memilih bobot dan bias dengan tepat, kami dapat memastikan
*w*2 *sigma*(*w*1*x*+*b*) *sekitarx* untuk *x* *dalam*\[0,1\]. Neuron
yang demikian dapat digunakan sebagai sejenis neuron identitas, yaitu
neuron yang hasilnya sama (hingga diubah oleh faktor bobot) sebagai
inputnya. *Petunjuk: Menulis ulang x=1/2+ Delta, untuk menganggap w1
kecil, dan menggunakan ekspansi deret Taylor dalam w1 Delta*

  - *.*

### [Gradien yang tidak stabil di jaringan yang lebih kompleks](http://neuralnetworksanddeeplearning.com/chap5.html#unstable_gradients_in_more_complex_networks) 

Kami telah mempelajari jaringan mainan, dengan hanya satu neuron di
setiap lapisan tersembunyi. Bagaimana dengan jaringan dalam yang lebih
kompleks, dengan banyak neuron di setiap lapisan tersembunyi?

![http://neuralnetworksanddeeplearning.com/images/tikz40.png](media/image90.png)

Bahkan, banyak perilaku yang sama terjadi di jaringan tersebut.Dalam bab
sebelumnya pada backpropagation kita melihat bahwa gradien dalam *l*

th lapisan dari *L*

lapisan jaringan [diberikan
oleh](http://neuralnetworksanddeeplearning.com/chap2.html#alternative_backprop)
:

*δl*=Σ′(*zl*)(*wl*+1)*T*Σ′(*zl*+1)(*wl*+2)*T*…Σ′(*zL*)∇*aC*(124)

Di sini, adalah matriks diagonal yang isinya adalah nilai σ ′ ( z )
untuk input terbobot ke lapisan ke- l . The w l adalah matriks berat
untuk lapisan yang berbeda. Dan ∇ sebuah C adalah vektor derivatif
parsial C sehubungan dengan aktivasi output.Σ′(*zl*)

*σ*′(*z*)*lwl*∇*aCC*

Ini adalah ekspresi yang jauh lebih rumit daripada dalam kasus neuron
tunggal. Namun, jika Anda melihat dekat, bentuk penting sangat mirip,
dengan banyak pasang bentuk . Terlebih lagi, matriks Σ ′ ( z j )
memiliki entri kecil pada diagonal, tidak ada yang lebih besar dari
1(*wj*)*T*Σ′(*zj*)

Σ′(*zj*) . Disediakan matriks beratwjtidak terlalu besar, setiap istilah
tambahan(wj)TΣ'(zl)cenderung membuat vektor gradien yang lebih kecil,
yang mengarah ke gradien menghilang. Secara lebih umum, sejumlah besar
istilah dalam produk cenderung mengarah ke gradien yang tidak stabil,
seperti pada contoh kami sebelumnya. Dalam praktiknya, secara empiris
biasanya ditemukan dalam jaringan sigmoid yang gradiennya menghilang
secara cepat di lapisan sebelumnya. Akibatnya, pembelajaran melambat di
lapisan itu. Perlambatan ini bukan hanya kecelakaan atau
ketidaknyamanan: itu adalah konsekuensi mendasar dari pendekatan yang
kami ambil untuk belajar.14*wj*(*wj*)*T*Σ′(*zl*)

### [Hambatan lain untuk *pembelajaran dalam (deep learning)*](http://neuralnetworksanddeeplearning.com/chap5.html#other_obstacles_to_deep_learning) 

Dalam bab ini kami telah fokus pada lenyapnya gradien - dan, lebih umum,
gradien tidak stabil - sebagai penghambat *pembelajaran dalam (deep
learning)*. Faktanya, gradien yang tidak stabil hanyalah satu hambatan
untuk *pembelajaran dalam (deep learning)*, meskipun merupakan hambatan
mendasar yang penting. Banyak penelitian yang sedang berlangsung
bertujuan untuk lebih memahami tantangan yang dapat terjadi ketika
melatih jaringan yang mendalam. Saya tidak akan meringkas pekerjaan itu
secara komprehensif di sini, tetapi hanya ingin secara singkat
menyebutkan beberapa makalah, untuk memberi Anda rasa dari beberapa
pertanyaan yang diajukan orang.

Sebagai contoh pertama, pada tahun 2010 Glorot dan Bengio \* \*
[Memahami kesulitan melatih jaringan saraf (*neural networks*) deep
feedforward](http://jmlr.org/proceedings/papers/v9/glorot10a/glorot10a.pdf)
, oleh Xavier Glorot dan Yoshua Bengio (2010). Lihat juga diskusi
sebelumnya tentang penggunaan sigmoids di [Efficient
BackProp](http://yann.lecun.com/exdb/publis/pdf/lecun-98b.pdf) , oleh
Yann LeCun, Léon Bottou, Genevieve Orr dan Klaus-Robert Müller (1998).
menemukan bukti yang menunjukkan bahwa penggunaan fungsi aktivasi
sigmoid dapat menyebabkan masalah melatih jaringan yang dalam. Secara
khusus, mereka menemukan bukti bahwa penggunaan sigmoids akan
menyebabkan aktivasi di lapisan tersembunyi akhir jenuh mendekati di
awal pelatihan, secara substansial memperlambat pembelajaran. Mereka
menyarankan beberapa fungsi aktivasi alternatif, yang tampaknya tidak
terlalu menderita dari masalah saturasi ini.0

Sebagai contoh kedua, pada tahun 2013 Sutskever, Martens, Dahl dan
Hinton \* \* [Tentang pentingnya inisialisasi dan momentum dalam
*pembelajaran dalam (deep
learning)*](http://www.cs.toronto.edu/~hinton/absps/momentum.pdf) , oleh
Ilya Sutskever, James Martens, George Dahl dan Geoffrey Hinton (2013).
mempelajari dampak pada *pembelajaran dalam (deep learning)* dari
inisialisasi bobot acak dan jadwal momentum dalam penurunan gradien
stokastik stokastik. Dalam kedua kasus, membuat pilihan yang baik
membuat perbedaan besar dalam kemampuan untuk melatih jaringan yang
mendalam.

Contoh-contoh ini menunjukkan bahwa "Apa yang membuat jaringan dalam
sulit untuk dilatih?" adalah pertanyaan yang kompleks. Dalam bab ini,
kami berfokus pada ketidakstabilan yang terkait dengan pembelajaran
berbasis gradien di jaringan yang dalam. Hasil dalam dua paragraf
terakhir menunjukkan bahwa ada juga peran yang dimainkan oleh pilihan
fungsi aktivasi, cara bobot diinisialisasi, dan bahkan detail tentang
bagaimana pembelajaran dengan gradient descent diimplementasikan. Dan,
tentu saja, pilihan arsitektur jaringan dan parameter-hiper lainnya juga
penting. Dengan demikian, banyak faktor yang dapat berperan dalam
membuat jaringan yang dalam menjadi sulit untuk dilatih, dan memahami
semua faktor tersebut masih menjadi subjek penelitian yang sedang
berlangsung. Ini semua tampaknya agak suram dan memicu pesimisme. Tetapi
kabar baiknya adalah bahwa dalam bab berikutnya kita akan membalikkan
itu,dan mengembangkan beberapa pendekatan untuk *pembelajaran dalam
(deep learning)* yang sampai batas tertentu berhasil mengatasi atau
mengarahkan semua tantangan ini.

Dalam karya akademis, silakan kutip buku ini sebagai: Michael A.
Nielsen, "Neural Networks and Deep Learning", Determination Press,
2015  
  
Karya ini dilisensikan di bawah [Lisensi Creative Commons
Attribution-NonCommercial 3.0
Unported](http://creativecommons.org/licenses/by-nc/3.0/deed.en_GB) .
Ini artinya Anda bebas menyalin, membagikan, dan membuat buku ini,
tetapi tidak untuk menjualnya. Jika Anda tertarik menggunakan komersial,
silakan [hubungi saya](mailto:mn@michaelnielsen.org) . Pembaruan
terakhir: Sel 11 Jun 16:58:53 2019  
  
  
![Lisensi Creative Commons](media/image33.png)

# [BAB 6](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ) 

# [*Pembelajaran dalam (deep learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ) 

[jaringan saraf (*neural networks*) Tiruan dan Pembelajaran
Jauh](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhic73V7KqVjxIPGNbaQNJ2530s4GA)

[Tentang buku
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/about.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh4WEv8VZZCecHFGon_fBfEj9Fk-g)

[Tentang latihan dan
masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/exercises_and_problems.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgGXxYFYgdq20f8ymqVw5JGPzA2tA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Menggunakan
jaring saraf untuk mengenali angka tulisan
tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Cara
kerja algoritma
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Meningkatkan
cara belajar jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Bukti
visual bahwa jaring saraf dapat menghitung fungsi apa
pun](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap4.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgzJKLAEjvxFJSTt899AGWkWymaQw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[Mengapa
jaringan saraf (*neural networks*) yang dalam sulit untuk
dilatih?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)

![http://neuralnetworksanddeeplearning.com/images/arrow.png](media/image34.png)[*Pembelajaran
dalam (deep
learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ)

[Lampiran: Apakah ada algoritma *sederhana* untuk
intelijen?](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/sai.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi_r2W6B006rb7gK3F4bzy6prrdaQ)

[Ucapan Terima
Kasih](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/acknowledgements.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2YHKQpAuvZNHAiXn0Z6HVn-0KQA)

[Pertanyaan yang Sering
Diajukan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

Jika Anda mendapat manfaat dari buku ini, silakan berikan sumbangan
kecil. Saya menyarankan $ 5, tetapi Anda dapat memilih jumlahnya.

Top of Form

Bottom of Form

Sebagai alternatif, Anda dapat memberikan donasi dengan mengirimkan saya
Bitcoin, di alamat 1Kd6tXH5SDAmiFb49J9hknG5pqj7KStSAx

Sponsor  
![http://neuralnetworksanddeeplearning.com/assets/exxact.png](media/image36.png)

Workstation Deep Learning mulai dari $ 6.999: [pelajari lebih
lanjut](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.exxactcorp.com/Deep-Learning-NVIDIA-GPU-Solutions%3Futm_source%3Dneuralnetworksanddeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dsponsors&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj6rGsPToAcGlYjeEJXAHXJspW3eQ)

![http://neuralnetworksanddeeplearning.com/assets/lambda.png](media/image37.png)

[Workstation, Server, dan Laptop Belajar
dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://lambdalabs.com/%3Futm_source%3Dneuralnetworksdeeplearning%26utm_medium%3Dbanner%26utm_campaign%3Dblogin%26utm_content%3Drtext&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhmW9twAd-_7XhnUCemcjX98sl7gw)

![http://neuralnetworksanddeeplearning.com/assets/gsquared.png](media/image38.png)![http://neuralnetworksanddeeplearning.com/assets/tineye.png](media/image39.png)![http://neuralnetworksanddeeplearning.com/assets/visionsmarts.png](media/image40.png)

Terima kasih kepada semua
[pendukung](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/supporters.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj9HdVAwFQiYjPlo--NhrlXsSgZ2w)
yang memungkinkan buku ini, dengan terima kasih terutama kepada Pavel
Dudrenov. Terima kasih juga kepada semua kontributor di [Bugfinder Hall
of
Fame](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/bugfinder.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhbjVenylI9ODfotXyQdFoaBBrKaQ)
.

Sumber daya

[Michael Nielsen di
Twitter](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://twitter.com/michael_nielsen&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiM6kfoM32wXnoIMmahlwqfNqEWPg)

[Pesan
FAQ](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/faq.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgjmiiZUNKF3mAkS3Ho8oICtk13Xg)

[Repositori
kode](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhUDc58iR7PU8_gSuNnY9hUhxv0pw)

[Milis pengumuman proyek Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://eepurl.com/0Xxjb&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhCYC3lUQysyAb2pDyD_0ubQrqOeg)

[Deep
Learning](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.deeplearningbook.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhrv253n32Mv6Uv5S3BDOvpBcn5rg)
, buku karya Ian Goodfellow, Yoshua Bengio, dan Aaron Courville

[cognitivemedium.com](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://cognitivemedium.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgEBgr9y1U5WD3Da33Y88SX6zvRPA)

![http://neuralnetworksanddeeplearning.com/assets/Michael\_Nielsen\_Web\_Small.jpg](media/image41.jpeg)

Oleh [Michael
Nielsen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://michaelnielsen.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7zg7S5OLu9AePjnKFialijDRDZQ)
/ Jun 2019

Dalam [bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)
kami belajar bahwa jaringan saraf (*neural networks*) yang dalam sering
kali jauh lebih sulit untuk dilatih daripada *jaringan saraf (neural
networks)* yang dangkal. Sangat disayangkan, karena kita memiliki alasan
kuat untuk percaya bahwa *jika* kita bisa melatih jaring yang dalam,
mereka akan jauh lebih kuat daripada jaring yang dangkal. Tetapi
sementara berita dari bab terakhir mengecewakan, kami tidak akan
membiarkannya menghentikan kami. Dalam bab ini, kita akan mengembangkan
teknik yang dapat digunakan untuk melatih jaringan yang dalam, dan
menerapkannya dalam praktik. Kami juga akan melihat gambar yang lebih
luas, meninjau secara singkat kemajuan terkini dalam menggunakan jaring
yang dalam untuk pengenalan gambar, pengenalan suara, dan aplikasi
lainnya. Dan kita akan melihat, spekulatif singkat apa yang akan terjadi
di masa depan untuk jaring saraf, dan untuk kecerdasan buatan.

Bab ini panjang. Untuk membantu Anda menavigasi, mari ikuti tur.
Bagian-bagian ini hanya digabungkan secara longgar, jadi asalkan Anda
memiliki pengetahuan dasar dengan jaring saraf, Anda dapat melompat ke
apa pun yang paling menarik minat Anda.

Bagian [utama dari
bab](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#convolutional_networks)
ini adalah pengantar salah satu jenis jaringan dalam yang paling banyak
digunakan: jaringan konvolusional dalam. Kami akan bekerja melalui
contoh terperinci - kode dan semua - menggunakan jaring konvolusional
untuk menyelesaikan masalah klasifikasi angka tulisan tangan dari set
data MNIST:

![http://neuralnetworksanddeeplearning.com/images/digits.png](media/image1.png)

Kami akan memulai akun kami tentang jaringan konvolusional dengan
jaringan dangkal yang digunakan untuk menyerang masalah ini sebelumnya
dalam buku ini. Melalui banyak iterasi kami akan membangun jaringan yang
lebih kuat. Seiring kita melangkah, kita akan mengeksplorasi banyak
teknik canggih: konvolusi, penyatuan, penggunaan GPU untuk melakukan
lebih banyak pelatihan daripada yang kita lakukan dengan jaringan
dangkal kami, perluasan algoritmik data pelatihan kami (untuk mengurangi
overfitting), penggunaan dropout teknik (juga untuk mengurangi
overfitting), penggunaan ansambel jaringan, dan lainnya. Hasilnya akan
menjadi sistem yang menawarkan kinerja yang mendekati manusia. Dari
10.000 gambar uji MNIST - gambar yang tidak terlihat selama pelatihan\!
- sistem kami akan mengklasifikasikan 9.967 dengan benar. Berikut ini
intip 33 gambar yang salah klasifikasi. Perhatikan bahwa klasifikasi
yang benar ada di kanan atas; klasifikasi program kami ada di kanan
bawah:

![http://neuralnetworksanddeeplearning.com/images/ensemble\_errors.png](media/image91.png)

Banyak dari ini sulit bahkan bagi manusia untuk mengklasifikasikan.
Perhatikan, misalnya, gambar ketiga di baris atas. Bagi saya itu lebih
mirip "9" daripada "8", yang merupakan klasifikasi resmi. Jaringan kami
juga menganggap itu "9". "Kesalahan" semacam ini paling tidak bisa
dimengerti, dan mungkin bahkan patut dipuji. Kami menyimpulkan diskusi
kami tentang pengenalan gambar dengan [survei terhadap beberapa kemajuan
terbaru yang
spektakuler](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#recent_progress_in_image_recognition)
menggunakan jaringan (khususnya jaring konvolusional) untuk melakukan
pengenalan gambar.

Bagian selanjutnya dari bab ini membahas *pembelajaran dalam (deep
learning)* dari perspektif yang lebih luas dan kurang terperinci. Kami
akan [secara singkat mensurvei model lain dari jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#things_we_didn't_cover_but_which_you'll_eventually_want_to_know)
, seperti jaring saraf berulang dan unit memori jangka pendek, dan
bagaimana model tersebut dapat diterapkan untuk masalah dalam pengenalan
suara, pemrosesan bahasa alami, dan area lainnya. Dan kami akan
[berspekulasi tentang masa depan jaringan saraf (*neural networks*) dan
*pembelajaran dalam (deep
learning)*](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#on_the_future_of_neural_networks)
, mulai dari ide-ide seperti antarmuka pengguna yang digerakkan oleh
niat, hingga peran *pembelajaran dalam (deep learning)* dalam kecerdasan
buatan.

Bab ini dibangun berdasarkan bab-bab sebelumnya dalam buku ini,
memanfaatkan dan mengintegrasikan ide-ide seperti backpropagation,
regularisasi, fungsi softmax, dan sebagainya. Namun, untuk membaca bab
ini Anda tidak perlu bekerja secara detail melalui semua bab sebelumnya.
Akan tetapi, akan membantu jika telah membaca
[Bab 1](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g)
, tentang dasar-dasar jaringan saraf. Ketika saya menggunakan konsep
dari Bab 2 sampai 5, saya memberikan tautan sehingga Anda dapat
membiasakan diri, jika perlu.

Perlu dicatat apa yang bukan bab ini. Ini bukan tutorial tentang pustaka
jaringan saraf (*neural networks*) terbaru dan terhebat. Kita juga tidak
akan melatih jaringan dalam dengan puluhan lapisan untuk menyelesaikan
masalah di ujung tombak. Alih-alih, fokusnya adalah memahami beberapa
prinsip inti di balik jaringan saraf (*neural networks*) yang dalam, dan
menerapkannya dalam konteks masalah MNIST yang sederhana dan mudah
dipahami. Dengan kata lain: bab ini tidak akan membawa Anda langsung ke
perbatasan. Sebaliknya, maksud dari bab ini dan bab sebelumnya adalah
untuk fokus pada fundamental, dan untuk mempersiapkan Anda untuk
memahami berbagai pekerjaan saat ini.

### [Memperkenalkan jaringan konvolusional](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#introducing_convolutional_networks) 

Dalam bab-bab sebelumnya, kami mengajarkan *jaringan saraf (neural
networks)* kami untuk melakukan pekerjaan yang cukup baik mengenali
gambar dari angka tulisan tangan:

![http://neuralnetworksanddeeplearning.com/images/digits.png](media/image1.png)

Kami melakukan ini menggunakan jaringan di mana lapisan jaringan yang
berdekatan sepenuhnya terhubung satu sama lain. Artinya, setiap neuron
dalam jaringan terhubung ke setiap neuron di lapisan yang berdekatan:

![http://neuralnetworksanddeeplearning.com/images/tikz41.png](media/image92.png)

Secara khusus, untuk setiap piksel dalam gambar input, kami menyandikan
intensitas piksel sebagai nilai untuk neuron yang sesuai di lapisan
input. Untuk 28 *kali*28

piksel gambar yang kami gunakan, ini berarti jaringan kami memiliki 784
(=28 *kali*28

) input neuron. Kami kemudian melatih bobot dan bias jaringan sehingga
keluaran jaringan akan - kami harap\! - identifikasi gambar input dengan
benar: '0', '1', '2', ..., '8', atau '9'.

Jaringan kami sebelumnya bekerja sangat baik: kami telah [memperoleh
akurasi klasifikasi yang lebih baik daripada 98
persen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#98percent)
, menggunakan pelatihan dan data uji dari [set data digit tulisan tangan
MNIST](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#learning_with_gradient_descent)
. Tetapi saat refleksi, aneh untuk menggunakan jaringan dengan lapisan
yang terhubung sepenuhnya untuk mengklasifikasikan gambar. Alasannya
adalah bahwa arsitektur jaringan seperti itu tidak memperhitungkan
struktur spasial gambar. Misalnya, ia memperlakukan piksel input yang
berjauhan dan berdekatan pada pijakan yang sama persis. Konsep struktur
ruang seperti itu harus disimpulkan dari data pelatihan. Tetapi
bagaimana jika, alih-alih memulai dengan arsitektur jaringan yang
merupakan *tabula rasa* , kami menggunakan arsitektur yang mencoba
memanfaatkan struktur spasial? Pada bagian ini saya menggambarkan
*jaringan saraf (neural networks) convolutional* \* \* Asal-usul
jaringan saraf (*neural networks*) convolutional kembali ke tahun
1970-an. Tetapi makalah mani menetapkan subjek modern dari jaringan
konvolusional adalah makalah tahun 1998, ["Pembelajaran berbasis gradien
diterapkan pada pengakuan
dokumen"](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh6CrOyDf1vdAsvuoDie_zS3ReEJg)
, oleh Yann LeCun, Léon Bottou, Yoshua Bengio, dan Patrick Haffner.
LeCun sejak itu membuat [komentar
yang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.facebook.com/yann.lecun/posts/10152348155137143&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiN9jav6ca8qGXIV2CpOyv_Ohv3rA)
menarik tentang terminologi untuk jaring konvolusional: "Inspirasi saraf
\[biologis\] dalam model seperti jaring konvolusional sangat lemah.
Itulah mengapa saya menyebutnya 'jaring convolutional' bukan 'jaring
saraf convolutional', dan mengapa kami menyebutnya node 'unit' dan bukan
'neuron' ". Terlepas dari pernyataan ini, jaring konvolusional
menggunakan banyak ide yang sama dengan *jaringan saraf (neural
networks)* yang telah kita pelajari sampai sekarang: ide-ide seperti
backpropagation, gradient descent, regularisasi, fungsi aktivasi
non-linear, dan sebagainya. Jadi kita akan mengikuti praktik umum, dan
menganggap mereka semacam jaringan saraf. Saya akan menggunakan istilah
"jaringan saraf (*neural networks*) convolutional" dan "jaring
convolutional (pekerjaan)" secara bergantian. Saya juga akan menggunakan
istilah "\[buatan\] neuron" dan "unit" secara bergantian. . Jaringan ini
menggunakan arsitektur khusus yang disesuaikan dengan baik untuk
mengklasifikasikan gambar. Menggunakan arsitektur ini membuat jaringan
konvolusional cepat untuk dilatih. Ini, pada gilirannya, membantu kami
melatih jaringan yang dalam dan banyak lapisan, yang sangat baik dalam
mengklasifikasikan gambar. Saat ini, jaringan konvolusional yang dalam
atau beberapa varian dekat digunakan di sebagian besar *jaringan saraf
(neural networks)* untuk pengenalan gambar.

jaringan saraf (*neural networks*) konvolusional menggunakan tiga ide
dasar: *bidang reseptif lokal* , *bobot bersama* , dan *pengumpulan* .
Mari kita lihat masing-masing ide ini secara bergantian.

**Bidang reseptif lokal:** Pada lapisan yang sepenuhnya terhubung yang
ditunjukkan sebelumnya, input digambarkan sebagai garis vertikal neuron.
Dalam jaring konvolusional, ini akan membantu untuk berpikir alih-alih
input sebagai 28 *kali*28

kuadrat neuron, yang nilainya sesuai dengan 28 *kali*28

piksel intensitas yang kita gunakan sebagai input:

![http://neuralnetworksanddeeplearning.com/images/tikz42.png](media/image93.png)

Seperti biasa, kami akan menghubungkan piksel input ke lapisan neuron
tersembunyi. Tapi kami tidak akan menghubungkan setiap piksel input ke
setiap neuron tersembunyi. Alih-alih, kami hanya membuat koneksi di
wilayah input gambar kecil yang dilokalkan.

Untuk lebih tepatnya, setiap neuron di lapisan tersembunyi pertama akan
terhubung ke wilayah kecil dari neuron input, katakanlah, misalnya,
5 *kali*5

wilayah, sesuai dengan 25

piksel input. Jadi, untuk neuron tersembunyi tertentu, kita mungkin
memiliki koneksi yang terlihat seperti ini:

![http://neuralnetworksanddeeplearning.com/images/tikz43.png](media/image94.png)

Wilayah itu dalam gambar input disebut *bidang reseptif lokal* untuk
neuron tersembunyi. Ini adalah jendela kecil pada piksel input. Setiap
koneksi belajar berat. Dan neuron yang tersembunyi mempelajari bias
secara keseluruhan juga. Anda dapat menganggap neuron tersembunyi
tertentu sebagai pembelajaran menganalisis bidang reseptif lokal
tertentu.

Kami kemudian menggeser bidang penerimaan lokal di seluruh gambar input.
Untuk setiap bidang penerimaan lokal, ada neuron tersembunyi yang
berbeda di lapisan tersembunyi pertama. Untuk mengilustrasikan hal ini
secara konkret, mari kita mulai dengan bidang reseptif lokal di sudut
kiri atas:

![http://neuralnetworksanddeeplearning.com/images/tikz44.png](media/image95.png)

Kemudian kami menggeser bidang penerimaan lokal lebih dari satu piksel
ke kanan (yaitu, dengan satu neuron), untuk terhubung ke neuron
tersembunyi kedua:

![http://neuralnetworksanddeeplearning.com/images/tikz45.png](media/image96.png)

Dan seterusnya, membangun lapisan tersembunyi pertama. Perhatikan bahwa
jika kita memiliki 28 *kali*28

input gambar, dan 5 *kali*5 bidang reseptif lokal, maka akan ada
24 *kali*24 neuron di lapisan tersembunyi. Ini karena kita hanya dapat
memindahkan bidang penerima lokal 23 neuron melintasi (atau 23

neuron ke bawah), sebelum bertabrakan dengan sisi kanan (atau bawah)
dari gambar input.

Saya telah menunjukkan bidang penerimaan lokal yang dipindahkan oleh
satu piksel pada satu waktu. Bahkan, kadang-kadang *panjang langkah
yang* berbeda digunakan. Misalnya, kami mungkin memindahkan bidang
penerimaan lokal 2

piksel ke kanan (atau ke bawah), dalam hal ini kami akan mengatakan
panjang langkah 2 digunakan. Dalam bab ini sebagian besar kita akan
tetap dengan panjang langkah 1, tetapi perlu diketahui bahwa orang
kadang-kadang bereksperimen dengan panjang langkah yang berbeda \* \*
Seperti yang telah dilakukan pada bab sebelumnya, jika kita tertarik
untuk mencoba panjang langkah yang berbeda maka kita dapat menggunakan
validasi data untuk memilih langkah panjang yang memberikan kinerja
terbaik. Untuk lebih jelasnya, lihat [diskusi sebelumnya
tentang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#how_to_choose_a_neural_network's_hyper-parameters)
bagaimana memilih parameter-hiper dalam jaringan saraf. Pendekatan yang
sama juga dapat digunakan untuk memilih ukuran bidang penerimaan lokal -
tentu saja, tidak ada yang istimewa tentang menggunakan bidang
penerimaan lokal 5 *kali*5 lokal. Secara umum, bidang penerimaan lokal
yang lebih besar cenderung membantu ketika gambar input secara
signifikan lebih besar dari 28 *kali*28

piksel gambar MNIST. .

**Bobot dan bias yang dibagi:** Saya telah mengatakan bahwa setiap
neuron yang tersembunyi memiliki bias dan bobot 5 *kali*5

yang terhubung ke bidang penerimaan lokalnya. Yang belum saya sebutkan
adalah bahwa kita akan menggunakan bobot dan bias yang sama untuk
masing-masing neuron tersembunyi 24 *kali*24. Dengan kata lain, untuk
neuron tersembunyi *j*,*k* th, hasilnya adalah: \\ begin {eqnarray} \\
sigma \\ kiri (b + \\ sum\_ {l = 0} ^ 4 \\ sum\_ {m = 0} ^ 4 w\_ {l, m}
a\_ {j + l, k + m} \\ kanan). \\ tag {125} \\ end {eqnarray} Di sini,
 *sigma* adalah fungsi aktivasi saraf - mungkin [fungsi sigmoid
yang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap1.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuKm-zit1CBgbMg-r-MaNpJ6fF9g#sigmoid_neurons)
kami gunakan di bab-bab sebelumnya. *b* adalah nilai bersama untuk bias.
*wl*,*m* adalah array 5 *kali*5 dari bobot bersama. Dan, akhirnya, kami
menggunakan *ax*,*y* untuk menunjukkan aktivasi input pada posisi
*x*,*y*

.

Ini berarti bahwa semua neuron di lapisan tersembunyi pertama mendeteksi
fitur yang persis sama \* \* Saya belum secara tepat mendefinisikan
gagasan fitur. Secara informal, pikirkan fitur yang terdeteksi oleh
neuron tersembunyi sebagai jenis pola input yang akan menyebabkan neuron
aktif: misalnya tepi pada gambar, misalnya, atau mungkin beberapa jenis
bentuk lainnya. , hanya di lokasi berbeda di gambar input. Untuk melihat
mengapa ini masuk akal, anggaplah bobot dan bias sedemikian sehingga
neuron yang tersembunyi dapat memilih, katakanlah, tepi vertikal dalam
bidang reseptif lokal tertentu. Kemampuan itu juga mungkin berguna di
tempat lain dalam gambar. Maka sangat berguna untuk menerapkan fitur
detektor yang sama di mana saja pada gambar. Singkatnya, istilah
konvolusional disesuaikan dengan terjemahan invarian gambar: pindahkan
gambar kucing (katakanlah) sedikit cara, dan itu masih gambar kucing \*
\* Faktanya, untuk MNIST masalah klasifikasi digit yang telah kita
pelajari, gambarnya terpusat dan ukurannya dinormalisasi. Jadi, MNIST
memiliki lebih sedikit invarian terjemahan daripada gambar yang
ditemukan "di alam liar", begitulah. Namun, fitur seperti tepi dan sudut
cenderung berguna di sebagian besar ruang input. .

Untuk alasan ini, kami terkadang menyebut peta dari lapisan input ke
lapisan tersembunyi sebagai *fitur peta* . Kami menyebut bobot yang
mendefinisikan fitur memetakan *bobot yang dibagi* . Dan kami
menyebutnya bias mendefinisikan peta fitur dengan cara ini *bias
bersama* . Bobot dan bias yang dibagi sering dikatakan untuk
mendefinisikan *kernel* atau *filter* . Dalam literatur, orang kadang
menggunakan istilah-istilah ini dengan cara yang sedikit berbeda, dan
untuk alasan itu saya tidak akan lebih tepat; alih-alih, sebentar lagi,
kita akan melihat beberapa contoh nyata.

Struktur jaringan yang saya jelaskan sejauh ini dapat mendeteksi hanya
satu jenis fitur terlokalisasi. Untuk melakukan pengenalan gambar kita
membutuhkan lebih dari satu peta fitur. Dan lapisan konvolusional yang
lengkap terdiri dari beberapa peta fitur yang berbeda:

![http://neuralnetworksanddeeplearning.com/images/tikz46.png](media/image97.png)

Dalam contoh yang ditampilkan, ada 3 fitur peta. Setiap peta fitur
ditentukan oleh seperangkat bobot dibagi 5 *kali*5 bersama, dan satu
bias berbagi tunggal. Hasilnya adalah bahwa jaringan dapat mendeteksi 3
berbagai jenis fitur, dengan masing-masing fitur terdeteksi di seluruh
gambar.

Saya telah menunjukkan hanya 3

peta fitur, untuk menjaga diagram di atas sederhana. Namun, dalam
praktiknya jaringan konvolusional dapat menggunakan lebih banyak (dan
mungkin lebih banyak) peta fitur. Salah satu jaringan konvolusional
awal, LeNet-5, menggunakan 6 fitur peta, masing-masing terkait dengan
bidang penerimaan lokal 5 *kali*5, untuk mengenali angka MNIST. Jadi
contoh yang digambarkan di atas sebenarnya cukup dekat dengan LeNet-5.
Dalam contoh yang kita kembangkan nanti di bab ini kita akan menggunakan
lapisan konvolusional dengan fitur peta 20*dan*

40\. Mari kita intip beberapa fitur yang dipelajari \* \* Peta fitur
yang diilustrasikan berasal dari jaringan konvolusional terakhir yang
kita latih, lihat di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#final_conv)
. :

![http://neuralnetworksanddeeplearning.com/images/net\_full\_layer\_0.png](media/image98.png)

20

gambar sesuai dengan 20 peta fitur yang berbeda (atau filter, atau
kernel). Setiap peta direpresentasikan sebagai gambar blok 5 *kali*5,
sesuai dengan bobot 5 *kali*5

di bidang penerimaan lokal. Blok yang lebih putih berarti bobot yang
lebih kecil (biasanya, lebih negatif), sehingga peta fitur merespons
lebih sedikit terhadap piksel input yang sesuai. Blok yang lebih gelap
berarti bobot yang lebih besar, sehingga peta fitur merespons lebih
banyak pada piksel input yang sesuai. Secara kasar, gambar di atas
menunjukkan jenis fitur yang direspons lapisan konvolusional.

Jadi apa yang bisa kita simpulkan dari peta fitur ini? Jelas ada
struktur spasial di sini di luar apa yang kita harapkan secara acak:
banyak fitur memiliki sub-wilayah yang jelas antara terang dan gelap.
Itu menunjukkan jaringan kami benar-benar mempelajari hal-hal yang
berkaitan dengan struktur spasial. Namun, lebih dari itu, sulit untuk
melihat apa yang dipelajari oleh fitur detektor ini. Tentu saja, kita
tidak belajar (katakanlah) [filter
Gabor](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Gabor_filter&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgR57XsjmReX8qUR3BUeWKxws2Jg)
yang telah digunakan dalam banyak pendekatan tradisional untuk
pengenalan gambar. Bahkan, sekarang ada banyak pekerjaan untuk lebih
memahami fitur yang dipelajari oleh jaringan konvolusional. Jika Anda
tertarik untuk menindaklanjuti pekerjaan itu, saya sarankan memulai
dengan makalah [Visualisasi dan Memahami Jaringan
Konvolusional](http://arxiv.org/abs/1311.2901) oleh Matthew Zeiler dan
Rob Fergus (2013).

Keuntungan besar berbagi bobot dan bias adalah sangat mengurangi jumlah
parameter yang terlibat dalam jaringan convolutional. Untuk setiap peta
fitur kita membutuhkan 25=5 *kali*5

bobot bersama, ditambah satu bias berbagi. Jadi setiap peta fitur
memerlukan $ 26 parameter. Jika kita memiliki 20 fitur peta itu total
20 *kali*26=520 parameter mendefinisikan lapisan convolutional. Sebagai
perbandingan, anggaplah kita memiliki lapisan pertama yang sepenuhnya
terhubung, dengan 784=28 *kali*28 neuron input, dan neuron tersembunyi $
30 yang relatif sederhana, seperti yang kami gunakan dalam banyak contoh
sebelumnya dalam buku ini. Itu total 784 *kalibobot* 30, ditambah bias
30 tambahan, dengan total 23.550

parameter. Dengan kata lain, lapisan yang terhubung sepenuhnya akan
memiliki parameter lebih dari $ 40 kali lebih banyak daripada lapisan
konvolusional.

Tentu saja, kami tidak dapat benar-benar melakukan perbandingan langsung
antara jumlah parameter, karena kedua model berbeda dalam hal yang
penting. Tetapi, secara intuitif, tampaknya penggunaan invarian
terjemahan oleh lapisan konvolusional akan mengurangi jumlah parameter
yang diperlukan untuk mendapatkan kinerja yang sama dengan model yang
sepenuhnya terhubung. Itu, pada gilirannya, akan menghasilkan pelatihan
yang lebih cepat untuk model konvolusional, dan, pada akhirnya, akan
membantu kami membangun jaringan yang dalam menggunakan lapisan
konvolusional.

Kebetulan, nama *convolutional* berasal dari fakta bahwa operasi dalam
Persamaan (125) kadang-kadang dikenal sebagai *konvolusi* . Sedikit
lebih tepatnya, orang kadang-kadang menulis persamaan itu sebagai
*a*1= *sigma*(*b*+*w*∗*a*0)

, di mana *a*1 menunjukkan set aktivasi keluaran dari satu peta fitur,
*a*0 adalah rangkaian aktivasi input, dan ∗

disebut operasi konvolusi. Kami tidak akan menggunakan matematika
konvolusi secara mendalam, jadi Anda tidak perlu terlalu khawatir
tentang koneksi ini. Tapi ada baiknya setidaknya mengetahui dari mana
nama itu berasal.

**Pooling layers:** Selain layer convolutional yang baru saja
dijelaskan, jaringan saraf (*neural networks*) convolutional juga
mengandung *layer pooling* . Lapisan penyatuan biasanya digunakan segera
setelah lapisan konvolusional. Apa yang dilakukan pooling layer adalah
menyederhanakan informasi dalam output dari lapisan convolutional.

Secara detail, layer pooling mengambil setiap peta fitur \* \*
Nomenklatur ini digunakan secara longgar di sini. Secara khusus, saya
menggunakan "peta fitur" bukan berarti fungsi yang dihitung oleh lapisan
konvolusional, melainkan aktivasi output neuron tersembunyi dari
lapisan. Jenis penyalahgunaan nomenklatur yang ringan ini cukup umum
dalam literatur penelitian. output dari lapisan konvolusional dan
menyiapkan peta fitur kental. Sebagai contoh, setiap unit dalam lapisan
penyatuan dapat meringkas wilayah (katakanlah) 2 *kali*2

neuron di lapisan sebelumnya. Sebagai contoh konkret, satu prosedur umum
untuk pooling dikenal sebagai *max-pooling* . Dalam max-pooling, unit
pooling hanya mengeluarkan aktivasi maksimum di wilayah input 2 *kali*2

, seperti yang diilustrasikan dalam diagram berikut:

![http://neuralnetworksanddeeplearning.com/images/tikz47.png](media/image99.png)

Perhatikan bahwa karena kita memiliki 24 *kali*24

neuron output dari lapisan konvolusional, setelah mengumpulkan kita
memiliki 12 *kali*12

neuron.

Seperti disebutkan di atas, lapisan convolutional biasanya melibatkan
lebih dari satu peta fitur tunggal. Kami menerapkan max-pooling untuk
setiap peta fitur secara terpisah. Jadi jika ada tiga peta fitur,
lapisan konvolusional dan max-pooling gabungan akan terlihat seperti:

![http://neuralnetworksanddeeplearning.com/images/tikz48.png](media/image100.png)

Kita dapat menganggap max-pooling sebagai cara jaringan untuk bertanya
apakah fitur yang diberikan ditemukan di mana saja di wilayah gambar.
Itu kemudian membuang informasi posisi yang tepat. Intuisi adalah bahwa
sekali fitur telah ditemukan, lokasi pastinya tidak sepenting lokasi
kasar relatif terhadap fitur lainnya. Manfaat besar adalah bahwa ada
banyak fitur yang dikumpulkan lebih sedikit, dan karenanya ini membantu
mengurangi jumlah parameter yang diperlukan di lapisan selanjutnya.

Max-pooling bukan satu-satunya teknik yang digunakan untuk pooling.
Pendekatan umum lainnya dikenal sebagai *pooling L2* . Di sini,
alih-alih mengambil aktivasi maksimum wilayah neuron 2 *kali*2

, kami mengambil akar kuadrat dari jumlah kuadrat aktivasi di wilayah
2 *kali*2

. Walaupun detailnya berbeda, intuisi ini mirip dengan max-pooling: L2
pooling adalah cara mengembunkan informasi dari lapisan convolutional.
Dalam praktiknya, kedua teknik ini telah banyak digunakan. Dan
kadang-kadang orang menggunakan jenis operasi pengumpulan lainnya. Jika
Anda benar-benar mencoba untuk mengoptimalkan kinerja, Anda dapat
menggunakan data validasi untuk membandingkan beberapa pendekatan yang
berbeda untuk menggabungkan, dan memilih pendekatan mana yang paling
berhasil. Tetapi kita tidak akan khawatir tentang optimasi terinci
semacam itu.

**Menyatukan semuanya:** Kita sekarang dapat menggabungkan semua ide ini
untuk membentuk jaringan saraf (*neural networks*) convolutional yang
lengkap. Ini mirip dengan arsitektur yang baru saja kita lihat, tetapi
memiliki penambahan lapisan 10

output neuron, sesuai dengan 10

nilai yang mungkin untuk digit MNIST ('0', '1', '2', *dll* ):

![http://neuralnetworksanddeeplearning.com/images/tikz49.png](media/image101.png)

Jaringan dimulai dengan 28 *kali*28

neuron input, yang digunakan untuk menyandikan intensitas piksel untuk
gambar MNIST. Ini kemudian diikuti oleh lapisan konvolusional
menggunakan bidang penerimaan lokal 5 *kali*5 dan peta fitur 3. Hasilnya
adalah lapisan 3 *kali*24 *kali*24 neuron fitur tersembunyi. Langkah
selanjutnya adalah lapisan penggabungan maksimal, diterapkan ke
2 *kali*2 wilayah, di masing-masing peta fitur 3. Hasilnya adalah
lapisan 3 *kali*12 *kali*12

fitur tersembunyi neuron.

Lapisan terakhir koneksi dalam jaringan adalah lapisan yang sepenuhnya
terhubung. Yaitu, lapisan ini menghubungkan *setiap* neuron dari lapisan
max-pooled ke setiap satu dari 10

output neuron. Arsitektur yang sepenuhnya terhubung ini sama dengan yang
kami gunakan di bab-bab sebelumnya. Namun, perhatikan bahwa dalam
diagram di atas, saya telah menggunakan panah tunggal, untuk
kesederhanaan, daripada menunjukkan semua koneksi. Tentu saja, Anda
dapat dengan mudah membayangkan hubungannya.

Arsitektur konvolusional ini sangat berbeda dengan arsitektur yang
digunakan pada bab-bab sebelumnya. Tapi gambaran keseluruhannya serupa:
jaringan yang terbuat dari banyak unit sederhana, yang perilakunya
ditentukan oleh bobot dan biasnya. Dan tujuan keseluruhan masih sama:
untuk menggunakan data pelatihan untuk melatih bobot dan bias jaringan
sehingga jaringan melakukan pekerjaan dengan baik mengklasifikasikan
digit input.

Khususnya, seperti sebelumnya dalam buku ini, kami akan melatih jaringan
kami menggunakan penurunan gradien stokastik dan backpropagation. Ini
sebagian besar hasil dengan cara yang persis sama seperti pada bab-bab
sebelumnya. Namun, kami perlu melakukan beberapa modifikasi pada
prosedur backpropagation. Alasannya adalah [turunan
backpropagation](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)
kami sebelumnya adalah untuk jaringan dengan lapisan yang sepenuhnya
terhubung. Untungnya, sangat mudah untuk memodifikasi derivasi untuk
lapisan convolutional dan max-pooling. Jika Anda ingin memahami
detailnya, maka saya mengundang Anda untuk mengatasi masalah berikut
ini. Berhati-hatilah karena masalah akan membutuhkan waktu untuk
diselesaikan, kecuali Anda benar-benar menginternalisasi [derivasi
backpropagation
sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw)
(dalam hal ini mudah).

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#problem_377948) 

  - **Backpropagation dalam jaringan convolutional** Persamaan inti dari
    backpropagation dalam jaringan dengan lapisan yang sepenuhnya
    terhubung adalah (BP1) - (BP4) (
    [tautan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#backpropsummary)
    ). Misalkan kita memiliki jaringan yang mengandung lapisan
    convolutional, lapisan max-pooling, dan lapisan output yang
    sepenuhnya terhubung, seperti dalam jaringan yang dibahas di atas.
    Bagaimana persamaan backpropagation dimodifikasi?

### [jaringan saraf (*neural networks*) convolutional dalam praktek](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#convolutional_neural_networks_in_practice) 

Kami sekarang telah melihat ide-ide inti di balik *jaringan saraf
(neural networks)* convolutional. Mari kita lihat bagaimana mereka
bekerja dalam praktiknya, dengan mengimplementasikan beberapa jaringan
konvolusional, dan menerapkannya pada masalah klasifikasi digit MNIST.
Program yang akan kita gunakan untuk melakukan ini disebut network3.py ,
dan ini merupakan versi yang ditingkatkan dari program-program
network.py dan network2.py yang dikembangkan di bab-bab sebelumnya \* \*
Perhatikan juga bahwa network3.py menggabungkan ide-ide dari dokumentasi
pustaka Theano di jaring saraf konvolusional (terutama implementasi
[LeNet-5](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/tutorial/lenet.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhij_DGGt96Se47Rdvt6pLxK0oU0xw)
), dari [penerapan
dropout](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mdenil/dropout&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhFk4QZAK5ACj-TIaoIbWl6iFNtnQ)
Misha Denil, dan dari [Chris
Olah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://colah.github.io/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjYH34OdCtpxyi7Gq0MUuMpxFJpzQ)
. . Jika Anda ingin mengikuti, kode ini tersedia [di
GitHub](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/network3.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi0qoB0D8GHF5BV-U-dsfFRyNTWzA)
. Perhatikan bahwa kami akan mengerjakan sendiri kode untuk network3.py
di bagian selanjutnya. Di bagian ini, kita akan menggunakan network3.py
sebagai pustaka untuk membangun jaringan convolutional.

Program-program network.py dan network2.py diimplementasikan menggunakan
Python dan pustaka matriks Numpy. Program-program tersebut bekerja dari
prinsip-prinsip pertama, dan langsung sampai ke rincian backpropagation,
stochastic gradient descent, dan sebagainya. Tetapi sekarang setelah
kita memahami perincian itu, untuk network3.py kita akan menggunakan
pustaka pembelajaran mesin yang dikenal sebagai
[Theano](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/software/theano/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgDB9vKmB4MV9qaZ9lxIAaPCWrdZQ)
\* \* Lihat [Theano: Kompiler Ekspresi Matematika CPU dan GPU dalam
Python](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.iro.umontreal.ca/~lisa/pointeurs/theano_scipy2010.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg5j_mhVdtRBjy_kbTLLK6rRPx5hw)
, oleh James Bergstra, Olivier Breuleux, Frederic Bastien, Pascal
Lamblin, Ravzan Pascanu, Guillaume Desjardins, Joseph Turian, David
Warde-Farley, dan Yoshua Bengio (2010). Theano juga merupakan basis bagi
pustaka jaringan neural
[Pylearn2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/software/pylearn2/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgY9gCVg0xKInn9TuURAZAIvIWWCQ)
dan
[Keras](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://keras.io/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgh7rRMM0SygW7KcFJSy3cU36L5cg)
. Pustaka jaringan saraf (*neural networks*) populer lainnya pada saat
penulisan ini termasuk
[Caffe](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://caffe.berkeleyvision.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgepSHHDYKR-xvFgb2IV3T9WZVjfA)
dan
[Torch](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://torch.ch/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhsiCpSP8SWV1L90vLNQZIvGwNnyQ)
. . Menggunakan Theano membuatnya mudah untuk menerapkan backpropagation
untuk jaringan saraf (*neural networks*) convolutional, karena secara
otomatis menghitung semua pemetaan yang terlibat. Theano juga sedikit
lebih cepat daripada kode kami sebelumnya (yang ditulis agar mudah
dimengerti, bukan cepat), dan ini membuatnya praktis untuk melatih
jaringan yang lebih kompleks. Secara khusus, salah satu fitur hebat
Theano adalah dapat menjalankan kode pada CPU atau, jika tersedia, GPU.
Berjalan pada GPU memberikan peningkatan yang substansial dan, sekali
lagi, membantu membuatnya praktis untuk melatih jaringan yang lebih
kompleks.

Jika Anda ingin mengikuti, maka Anda harus membuat Theano berjalan di
sistem Anda. Untuk menginstal Theano, ikuti instruksi di
[beranda](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/software/theano/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgDB9vKmB4MV9qaZ9lxIAaPCWrdZQ)
proyek. Contoh-contoh berikut dijalankan menggunakan Theano 0.6 \* \*
Ketika saya merilis bab ini, versi Theano saat ini telah berubah menjadi
versi 0.7. Saya sebenarnya telah menjalankan kembali contoh-contoh di
bawah Theano 0.7 dan mendapatkan hasil yang sangat mirip dengan yang
dilaporkan dalam teks. . Beberapa dijalankan di bawah Mac OS X Yosemite,
tanpa GPU. Beberapa dijalankan di Ubuntu 14.04, dengan GPU NVIDIA. Dan
beberapa percobaan dijalankan di bawah keduanya. Untuk menjalankan
network3.py Anda harus mengatur flag GPU ke True atau False (sebagaimana
diperlukan) di sumber network3.py . Di luar itu, untuk membuat Theano
aktif dan berjalan pada GPU Anda dapat menemukan [instruksi di
sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/software/theano/tutorial/using_gpu.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhA5P0kuzqG3Q6QplFxcq8w93BTwA)
bermanfaat. Ada juga tutorial di web, mudah ditemukan menggunakan
Google, yang dapat membantu Anda menyelesaikan pekerjaan. Jika Anda
tidak memiliki GPU yang tersedia secara lokal, maka Anda mungkin ingin
melihat contoh spot [Amazon Web
Services](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://aws.amazon.com/ec2/instance-types/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhog9CmxftvFFYOHpcnPBhSNdRF7Q)
EC2 G2. Perhatikan bahwa meskipun dengan GPU kode ini akan membutuhkan
waktu untuk dijalankan. Banyak percobaan berlangsung dari menit hingga
jam untuk berjalan. Pada CPU, mungkin perlu berhari-hari untuk
menjalankan eksperimen yang paling kompleks. Seperti pada bab-bab
sebelumnya, saya sarankan mengatur hal-hal berjalan, dan terus membaca,
kadang-kadang kembali untuk memeriksa output dari kode. Jika Anda
menggunakan CPU, Anda mungkin ingin mengurangi jumlah periode pelatihan
untuk eksperimen yang lebih kompleks, atau mungkin menghilangkannya sama
sekali.

Untuk mendapatkan garis dasar, kita akan mulai dengan arsitektur yang
dangkal menggunakan hanya satu lapisan tersembunyi, yang mengandung
neuron tersembunyi $ 100. Kami akan melatih untuk 60

zaman, menggunakan tingkat pembelajaran  *eta*=0,1, ukuran mini-batch 10

, dan tidak ada regularisasi. Di sini kita pergi \* \* Kode untuk
percobaan di bagian ini dapat ditemukan [dalam skrip
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/conv.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjVAu11zIksiShwXSV3DDdOSpErgg)
. Perhatikan bahwa kode dalam skrip hanya duplikat dan paralel dengan
diskusi di bagian ini.  
  
Perhatikan juga bahwa di seluruh bagian saya telah secara eksplisit
menentukan jumlah zaman pelatihan. Saya telah melakukan ini untuk
kejelasan tentang bagaimana kita berlatih. Dalam praktiknya, ada baiknya
menggunakan [penghentian
dini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#early_stopping)
, yaitu melacak akurasi pada set validasi, dan menghentikan pelatihan
ketika kami yakin akurasi validasi telah berhenti meningkat. :

\>\>\> jaringan impor3

\>\>\> dari network3 import Network

\>\>\> dari network3 impor ConvPoolLayer , FullyConnectedLayer ,
SoftmaxLayer

\>\>\> training\_data , validation\_data , test\_data = network3 .
load\_data\_shared ()

\>\>\> mini\_batch\_size = 10

\>\>\> net = Jaringan (\[

FullyConnectedLayer ( n\_in = 784 , n\_out = 100 ),

SoftmaxLayer ( n\_in = 100 , n\_out = 10 )\], mini\_batch\_size )

\>\>\> bersih . SGD ( training\_data , 60 , mini\_batch\_size , 0.1 ,

validation\_data , test\_data )

Saya memperoleh akurasi klasifikasi terbaik 97,80

persen. Ini adalah akurasi klasifikasi pada test\_data , dievaluasi pada
saat pelatihan di mana kami mendapatkan akurasi klasifikasi terbaik pada
validation\_data . Menggunakan data validasi untuk memutuskan kapan
harus mengevaluasi keakuratan pengujian membantu menghindari overfitting
ke data uji (lihat [diskusi sebelumnya
tentang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#validation_explanation)
penggunaan data validasi). Kami akan mengikuti latihan ini di bawah ini.
Hasil Anda mungkin sedikit berbeda, karena bobot dan bias jaringan
diinisialisasi secara acak \* \* Faktanya, dalam percobaan ini saya
benar-benar melakukan tiga running terpisah yang melatih jaringan dengan
arsitektur ini. Saya kemudian melaporkan akurasi pengujian yang sesuai
dengan akurasi validasi terbaik dari salah satu dari tiga proses.
Menggunakan banyak proses membantu mengurangi variasi dalam hasil, yang
berguna ketika membandingkan banyak arsitektur, seperti yang kami
lakukan. Saya telah mengikuti prosedur di bawah ini, kecuali jika
disebutkan. Dalam praktiknya, itu membuat sedikit perbedaan dengan hasil
yang diperoleh. .

Akurasi 97,80

persen ini mendekati akurasi 98,04 persen yang diperoleh kembali pada
[Bab 3](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#chap3_98_04_percent)
, menggunakan arsitektur jaringan yang sama dan mempelajari
parameter-hiper. Secara khusus, kedua contoh menggunakan jaringan
dangkal, dengan satu lapisan tersembunyi yang berisi neuron tersembunyi
$ 100. Keduanya juga dilatih untuk 60 zaman, menggunakan ukuran
mini-batch 10, dan tingkat pembelajaran  *eta*=0,1

.

Namun, ada dua perbedaan dalam jaringan sebelumnya. Pertama, kami
[mengatur](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#overfitting_and_regularization)
jaringan sebelumnya, untuk membantu mengurangi efek overfitting.
Meregulasi jaringan saat ini memang meningkatkan akurasi, tetapi
keuntungannya hanya kecil, jadi kami akan menunda mengkhawatirkan
tentang regularisasi sampai nanti. Kedua, sementara lapisan terakhir
dalam jaringan sebelumnya menggunakan aktivasi sigmoid dan fungsi biaya
lintas-entropi, jaringan saat ini menggunakan lapisan akhir softmax, dan
fungsi biaya log-likelihood. Sebagaimana
[dijelaskan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#softmax)
dalam Bab 3 ini bukan perubahan besar. Saya belum membuat peralihan ini
untuk alasan yang sangat mendalam - kebanyakan, saya sudah melakukannya
karena softmax plus biaya log-kemungkinan lebih umum di jaringan
klasifikasi gambar modern.

Bisakah kita melakukan lebih baik daripada hasil ini menggunakan
arsitektur jaringan yang lebih dalam?

Mari kita mulai dengan menyisipkan lapisan konvolusional, tepat di awal
jaringan. Kami akan menggunakan 5

dengan 5 bidang penerimaan lokal, panjang langkah 1, dan 20 fitur peta.
Kami juga akan menyisipkan lapisan max-pooling, yang menggabungkan
fitur-fitur menggunakan 2 dengan 2

pooling windows. Jadi arsitektur jaringan secara keseluruhan terlihat
sangat mirip dengan arsitektur yang dibahas di bagian terakhir, tetapi
dengan lapisan yang sepenuhnya terhubung:

![http://neuralnetworksanddeeplearning.com/images/simple\_conv.png](media/image102.png)

Dalam arsitektur ini, kita dapat menganggap lapisan konvolusional dan
penyatuan sebagai pembelajaran tentang struktur spasial lokal dalam
gambar pelatihan input, sementara lapisan selanjutnya yang terhubung
sepenuhnya belajar pada tingkat yang lebih abstrak, mengintegrasikan
informasi global dari seluruh gambar. Ini adalah pola umum dalam
jaringan saraf (*neural networks*) convolutional.

Mari kita latih jaringan semacam itu, dan lihat kinerjanya. \* \* Saya
terus menggunakan ukuran mini-batch 10

di sini. Faktanya, seperti yang telah kita [diskusikan
sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#mini_batch_size)
, dimungkinkan untuk mempercepat pelatihan menggunakan mini-batch yang
lebih besar. Saya terus menggunakan ukuran mini-batch yang sama sebagian
besar untuk konsistensi dengan percobaan pada bab-bab sebelumnya. :

\>\>\> net = Jaringan (\[

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 1 , 28 , 28 ),

filter\_shape = ( 20 , 1 , 5 , 5 ),

poolsize = ( 2 , 2 )),

FullyConnectedLayer ( n\_in = 20 \* 12 \* 12 , n\_out = 100 ),

SoftmaxLayer ( n\_in = 100 , n\_out = 10 )\], mini\_batch\_size )

\>\>\> bersih . SGD ( training\_data , 60 , mini\_batch\_size , 0.1 ,

validation\_data , test\_data )

Itu membuat kami mendapatkan akurasi 98,78

persen, yang merupakan peningkatan yang cukup besar dari hasil kami
sebelumnya. Memang, kami telah mengurangi tingkat kesalahan lebih dari
sepertiga, yang merupakan peningkatan besar.

Dalam menentukan struktur jaringan, saya telah memperlakukan layer
convolutional dan pooling sebagai satu layer. Apakah mereka dianggap
sebagai lapisan yang terpisah atau sebagai lapisan tunggal adalah
masalah selera. network3.py memperlakukan mereka sebagai satu lapisan
karena membuat kode untuk network3.py sedikit lebih kompak. Namun, mudah
untuk memodifikasi network3.py sehingga lapisan dapat ditentukan secara
terpisah, jika diinginkan.

#### [Olahraga](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#exercise_683491) 

  - Keakuratan klasifikasi apa yang Anda dapatkan jika Anda
    menghilangkan lapisan yang sepenuhnya terhubung, dan cukup gunakan
    lapisan penggabungan convolutional dan lapisan softmax? Apakah
    dimasukkannya lapisan yang terhubung sepenuhnya membantu?

Bisakah kita meningkatkan akurasi klasifikasi $ 98,78 persen?

Mari kita coba menyisipkan lapisan penggabungan konvolusional kedua.
Kami akan membuat penyisipan antara lapisan penyatuan konvolusional yang
ada dan lapisan tersembunyi yang terhubung sepenuhnya. Sekali lagi, kami
akan menggunakan bidang penerimaan lokal 5 *kali*5

lokal, dan mengumpulkan lebih dari 2 *kali*2

wilayah. Mari kita lihat apa yang terjadi ketika kita berlatih
menggunakan parameter hiper yang serupa dengan sebelumnya:

\>\>\> net = Jaringan (\[

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 1 , 28 , 28 ),

filter\_shape = ( 20 , 1 , 5 , 5 ),

poolsize = ( 2 , 2 )),

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 20 , 12 , 12 ),

filter\_shape = ( 40 , 20 , 5 , 5 ),

poolsize = ( 2 , 2 )),

FullyConnectedLayer ( n\_in = 40 \* 4 \* 4 , n\_out = 100 ),

SoftmaxLayer ( n\_in = 100 , n\_out = 10 )\], mini\_batch\_size )

\>\>\> bersih . SGD ( training\_data , 60 , mini\_batch\_size , 0.1 ,

validation\_data , test\_data )

Sekali lagi, kita mendapatkan peningkatan: kita sekarang berada pada
akurasi klasifikasi 99,06

persen\!

Ada dua pertanyaan alami untuk ditanyakan pada saat ini. Pertanyaan
pertama adalah: apa artinya menerapkan lapisan penyatuan konvolusional
kedua? Bahkan, Anda dapat menganggap lapisan penggabungan konvolusional
kedua sebagai memiliki input 12 *kali*12

"gambar", yang "piksel" -nya mewakili keberadaan (atau tidak adanya)
fitur-fitur lokal tertentu dalam gambar input asli. Jadi Anda dapat
menganggap layer ini sebagai input versi gambar input asli. Versi itu
diabstraksikan dan dipadatkan, tetapi masih memiliki banyak struktur
spasial, dan karenanya masuk akal untuk menggunakan lapisan penggabungan
konvolusional kedua.

Itu sudut pandang yang memuaskan, tetapi memunculkan pertanyaan kedua.
Output dari lapisan sebelumnya melibatkan 20

fitur peta yang terpisah, dan ada 20 *kali*12 *kali*12 input ke lapisan
pengumpulan-konvolusional kedua. Seolah-olah kita punya 20 input gambar
terpisah ke lapisan pooling convolutional, bukan gambar tunggal, seperti
halnya untuk layer pooling convolutional pertama. Bagaimana seharusnya
neuron pada lapisan penggabungan konvolusional kedua merespons beberapa
gambar input ini? Faktanya, kami akan mengizinkan setiap neuron di
lapisan ini untuk belajar dari *semua* 20 *kali*5 *kali*5

input neuron di bidang penerimaan lokalnya. Lebih informal: pendeteksi
fitur pada lapisan penggabungan konvolusional kedua memiliki akses ke
*semua* fitur dari lapisan sebelumnya, tetapi hanya dalam bidang
penerimaan lokal khusus mereka \* \* Masalah ini akan muncul di lapisan
pertama jika gambar input berwarna. . Dalam hal ini kami akan memiliki 3
fitur input untuk setiap piksel, yang sesuai dengan saluran merah, hijau
dan biru di gambar input. Jadi kami akan mengizinkan pendeteksi fitur
memiliki akses ke semua informasi warna, tetapi hanya di dalam bidang
penerimaan lokal yang diberikan. .

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#problem_834310) 

  - **Menggunakan fungsi aktivasi tanh** Beberapa kali sebelumnya dalam
    buku ini saya telah menyebutkan argumen bahwa [fungsi
    tanh](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_models_of_artificial_neuron)
    mungkin merupakan fungsi aktivasi yang lebih baik daripada fungsi
    sigmoid. Kami tidak pernah menindaklanjuti saran-saran itu, karena
    kami sudah membuat banyak kemajuan dengan sigmoid tersebut. Tapi
    sekarang mari kita coba beberapa eksperimen dengan tanh sebagai
    fungsi aktivasi kami. Coba latih jaringan dengan aktivasi tanh di
    lapisan convolutional dan sepenuhnya terhubung \* \* Perhatikan
    bahwa Anda dapat melewatkan aktivasi\_fn = tanh sebagai parameter ke
    kelas ConvPoolLayer dan FullyConnectedLayer . . Mulailah dengan
    parameter-hiper yang sama seperti untuk jaringan sigmoid, tetapi
    latihlah untuk 20

zaman daripada 60. Seberapa baik kinerja jaringan Anda? Bagaimana jika
Anda melanjutkan ke 60 zaman? Cobalah memplot akurasi validasi per-epoch
untuk jaringan berbasis tanh dan sigmoid, hingga 60 epochs. Jika hasil
Anda mirip dengan milik saya, Anda akan menemukan jaringan tanh berlatih
sedikit lebih cepat, tetapi akurasi akhirnya sangat mirip. Bisakah Anda
jelaskan mengapa jaringan tanh bisa berlatih lebih cepat? Bisakah Anda
mendapatkan kecepatan pelatihan yang sama dengan sigmoid, mungkin dengan
mengubah tingkat pembelajaran, atau melakukan beberapa penyelamatan \*
\* Anda mungkin menemukan inspirasi dalam mengingat bahwa
 *sigma*(*z*)=(1+ *tanh*(*z*/2))/2

  - . ? Coba setengah lusin iterasi pada parameter hiper-belajar atau
    arsitektur jaringan, mencari cara yang mungkin lebih unggul daripada
    sigmoid. *Catatan: Ini adalah masalah terbuka.* *Secara pribadi,
    saya tidak menemukan banyak keuntungan dalam beralih ke tanh,
    meskipun saya belum bereksperimen secara mendalam, dan mungkin Anda
    dapat menemukan cara.* *Bagaimanapun, suatu saat kita akan menemukan
    keuntungan dalam beralih ke fungsi aktivasi linier yang telah
    diperbaiki, sehingga kita tidak akan membahas penggunaan tanh lebih
    dalam lagi.*

**Menggunakan unit linear yang diperbaiki:** Jaringan yang kami
kembangkan pada saat ini sebenarnya merupakan varian dari salah satu
jaringan yang digunakan dalam makalah seminal 1998 \* \* ["Pembelajaran
berbasis gradien diterapkan pada pengenalan
dokumen"](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh6CrOyDf1vdAsvuoDie_zS3ReEJg)
, oleh Yann LeCun, Léon Bottou, Yoshua Bengio, dan Patrick Haffner
(1998). Ada banyak perbedaan detail, tetapi secara umum jaringan kami
sangat mirip dengan jaringan yang dijelaskan dalam makalah ini.
memperkenalkan masalah MNIST, jaringan yang dikenal sebagai LeNet-5. Ini
adalah dasar yang baik untuk eksperimen lebih lanjut, dan untuk
membangun pemahaman dan intuisi. Secara khusus, ada banyak cara kami
dapat memvariasikan jaringan dalam upaya meningkatkan hasil kami.

Sebagai permulaan, mari kita ubah neuron kita sehingga alih-alih
menggunakan fungsi aktivasi sigmoid, kita menggunakan [unit linear yang
diperbaiki](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_models_of_artificial_neuron)
. Artinya, kami akan menggunakan fungsi aktivasi
*f*(*z*) *equiv* *max*(0,*z*)

. Kami akan melatih untuk 60 zaman, dengan tingkat pembelajaran
 *eta*=0,03. Saya juga menemukan bahwa sedikit membantu menggunakan
beberapa [regularisasi
l2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#overfitting_and_regularization)
, dengan parameter regularisasi  *lambda*=0,1

:

\>\>\> dari network3 import ReLU

\>\>\> net = Jaringan (\[

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 1 , 28 , 28 ),

filter\_shape = ( 20 , 1 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 20 , 12 , 12 ),

filter\_shape = ( 40 , 20 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

FullyConnectedLayer ( n\_in = 40 \* 4 \* 4 , n\_out = 100 , aktivasi\_fn
= ReLU ),

SoftmaxLayer ( n\_in = 100 , n\_out = 10 )\], mini\_batch\_size )

\>\>\> bersih . SGD ( training\_data , 60 , mini\_batch\_size , 0,03 ,

validation\_data , test\_data , lmbda = 0.1 )

Saya memperoleh akurasi klasifikasi 99,23

persen. Ini adalah peningkatan sederhana atas hasil sigmoid (99,06

). Namun, di semua eksperimen saya, saya menemukan bahwa jaringan yang
didasarkan pada unit linear yang diperbaiki secara konsisten mengungguli
jaringan berdasarkan fungsi aktivasi sigmoid. Tampaknya ada keuntungan
nyata dalam pindah ke unit linear yang diperbaiki untuk masalah ini.

Apa yang membuat fungsi aktivasi linier yang diperbaiki lebih baik
daripada fungsi sigmoid atau tanh? Saat ini, kami memiliki pemahaman
yang buruk tentang jawaban untuk pertanyaan ini. Memang, unit linier
yang diperbaiki hanya mulai digunakan secara luas dalam beberapa tahun
terakhir. Alasan untuk adopsi baru-baru ini adalah empiris: beberapa
orang mencoba unit linear diperbaiki, sering berdasarkan firasat atau
argumen heuristik \* \* Pembenaran umum adalah bahwa  *max*(0,*z*)

tidak jenuh dalam batas *z*

besar, tidak seperti neuron sigmoid, dan ini membantu unit linear yang
diperbaiki melanjutkan pembelajaran. Argumennya baik-baik saja, sejauh
ini berjalan, tapi itu bukan pembenaran yang terperinci, lebih dari
sekadar cerita biasa. Perhatikan bahwa kita telah membahas masalah
dengan saturasi kembali di
[Bab 2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap2.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjhQjx4SnMKjaBdH_Xy4McNVMcxFw#saturation)
. . Mereka mendapat hasil yang baik mengklasifikasikan set data
benchmark, dan praktiknya telah menyebar. Dalam dunia ideal kita akan
memiliki teori yang memberi tahu kita fungsi aktivasi mana yang harus
dipilih untuk aplikasi mana. Tetapi saat ini kita jauh dari dunia
seperti itu. Saya seharusnya tidak terkejut sama sekali jika perbaikan
besar lebih lanjut dapat diperoleh dengan pilihan yang lebih baik dari
fungsi aktivasi. Dan saya juga berharap bahwa dalam beberapa dekade
mendatang teori fungsi aktivasi yang kuat akan dikembangkan. Hari ini,
kita masih harus mengandalkan aturan praktis dan pengalaman yang kurang
dipahami.

**Memperluas data pelatihan:** Cara lain yang mungkin kami harapkan
untuk meningkatkan hasil kami adalah dengan memperluas data pelatihan
secara algoritmik. Cara sederhana untuk memperluas data pelatihan adalah
mengganti setiap gambar pelatihan dengan satu piksel, baik naik satu
piksel, turun satu piksel, kiri satu piksel, atau satu piksel kanan.
Kita dapat melakukan ini dengan menjalankan program expand\_mnist.py
dari prompt shell \* \* Kode untuk expand\_mnist.py tersedia di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/mnielsen/neural-networks-and-deep-learning/blob/master/src/expand_mnist.py&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgd4jpRNy0QID4U7XPQy-PdZ70gSw)
. :

$ python expand\_mnist.py

Menjalankan program ini mengambil gambar pelatihan MNIST
50.000,*danmenyiapkanrangkaianpelatihanyangdiperluas*,*dengangambarpelatihan*

250.000. Kami kemudian dapat menggunakan gambar-gambar pelatihan untuk
melatih jaringan kami. Kami akan menggunakan jaringan yang sama seperti
di atas, dengan unit linear yang diperbaiki. Dalam percobaan awal saya,
saya mengurangi jumlah zaman pelatihan - ini masuk akal, karena kita
berlatih dengan 5 kali lebih banyak data. Tetapi, pada kenyataannya,
memperluas data ternyata sangat mengurangi efek overfitting. Jadi,
setelah beberapa percobaan, saya akhirnya kembali ke pelatihan untuk 60

zaman. Bagaimanapun, mari kita latih:

\>\>\> extended\_training\_data , \_ , \_ = network3 . load\_data\_share
(

"../data/mnist\_expanded.pkl.gz" )

\>\>\> net = Jaringan (\[

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 1 , 28 , 28 ),

filter\_shape = ( 20 , 1 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 20 , 12 , 12 ),

filter\_shape = ( 40 , 20 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

FullyConnectedLayer ( n\_in = 40 \* 4 \* 4 , n\_out = 100 , aktivasi\_fn
= ReLU ),

SoftmaxLayer ( n\_in = 100 , n\_out = 10 )\], mini\_batch\_size )

\>\>\> bersih . SGD ( extended\_training\_data , 60 , mini\_batch\_size
, 0,03 ,

validation\_data , test\_data , lmbda = 0.1 )

Dengan menggunakan data pelatihan yang diperluas, saya memperoleh
akurasi pelatihan $ 99,37 persen. Jadi perubahan yang hampir sepele ini
memberikan peningkatan substansial dalam akurasi klasifikasi. Memang,
seperti yang kita [bahas
sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques_for_regularization)
ide ini secara algoritmik memperluas data dapat diambil lebih lanjut.
Sekadar mengingatkan Anda akan aroma beberapa hasil dalam diskusi
sebelumnya: pada tahun 2003 Simard, Steinkraus dan Platt \* \* [Praktik
Terbaik untuk jaringan saraf (*neural networks*) (neural
networks)Konvolusional yang Diterapkan untuk Analisis Dokumen
Visual](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://dx.doi.org/10.1109/ICDAR.2003.1227801&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiooJioOnuXJpBF8GklOZQW5jxw0g)
, oleh Patrice Simard, Dave Steinkraus, dan John Platt (2003 ).
meningkatkan kinerja MNIST mereka menjadi 99,6

persen menggunakan jaringan saraf (*neural networks*) jika tidak sangat
mirip dengan kita, menggunakan dua lapisan penyatuan convolutional,
diikuti oleh lapisan yang terhubung sepenuhnya tersembunyi dengan neuron
$ 100. Ada beberapa perbedaan detail dalam arsitektur mereka - mereka
tidak memiliki keuntungan menggunakan unit linear yang diperbaiki,
misalnya - tetapi kunci untuk peningkatan kinerja mereka adalah
memperluas data pelatihan. Mereka melakukan ini dengan memutar,
menerjemahkan, dan memiringkan gambar pelatihan MNIST. Mereka juga
mengembangkan proses "distorsi elastis", suatu cara meniru osilasi acak
yang dialami otot-otot tangan ketika seseorang sedang menulis. Dengan
menggabungkan semua proses ini, mereka secara substansial meningkatkan
ukuran efektif data pelatihan mereka, dan itulah cara mereka mencapai
akurasi 99,6

persen.

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#problem_437600) 

  - Gagasan lapisan konvolusional adalah untuk berperilaku dengan cara
    yang berbeda di seluruh gambar. Maka, mungkin mengejutkan, bahwa
    jaringan kami dapat belajar lebih banyak ketika semua yang kami
    lakukan adalah menerjemahkan data input. Bisakah Anda menjelaskan
    mengapa ini sebenarnya cukup masuk akal?

**Memasukkan lapisan ekstra yang sepenuhnya terhubung:** Bisakah kita
melakukannya lebih baik? Satu kemungkinan adalah menggunakan prosedur
yang persis sama seperti di atas, tetapi untuk memperluas ukuran lapisan
yang sepenuhnya terhubung. Saya mencoba dengan 300

dan 1.000 neuron, memperoleh hasil 99,46 dan 99,43

persen, masing-masing. Itu menarik, tetapi tidak benar-benar kemenangan
meyakinkan atas hasil sebelumnya ($ 99,37 persen).

Bagaimana dengan menambahkan lapisan yang sepenuhnya terhubung ekstra?
Mari kita coba menyisipkan lapisan yang sepenuhnya terhubung ekstra,
sehingga kita memiliki dua lapisan neuron yang terhubung sepenuhnya

$:

\>\>\> net = Jaringan (\[

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 1 , 28 , 28 ),

filter\_shape = ( 20 , 1 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 20 , 12 , 12 ),

filter\_shape = ( 40 , 20 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

FullyConnectedLayer ( n\_in = 40 \* 4 \* 4 , n\_out = 100 , aktivasi\_fn
= ReLU ),

FullyConnectedLayer ( n\_in = 100 , n\_out = 100 , aktivasi\_fn = ReLU
),

SoftmaxLayer ( n\_in = 100 , n\_out = 10 )\], mini\_batch\_size )

\>\>\> bersih . SGD ( extended\_training\_data , 60 , mini\_batch\_size
, 0,03 ,

validation\_data , test\_data , lmbda = 0.1 )

Melakukan ini, saya memperoleh akurasi tes 99,43

persen. Sekali lagi, jaring yang diperluas tidak banyak membantu.
Menjalankan eksperimen serupa dengan lapisan yang sepenuhnya terhubung
yang berisi 300 dan 1.000 neuron menghasilkan hasil 99,48 dan 99,47

persen. Itu menggembirakan, tetapi masih kalah dari kemenangan yang
benar-benar menentukan.

Apa yang terjadi di sini? Apakah itu lapisan yang diperluas atau yang
sepenuhnya terhubung sepenuhnya benar-benar tidak membantu dengan MNIST?
Atau mungkinkah jaringan kita memiliki kapasitas untuk melakukan yang
lebih baik, tetapi kita akan belajar dengan cara yang salah? Misalnya,
mungkin kita bisa menggunakan teknik regularisasi yang lebih kuat untuk
mengurangi kecenderungan untuk berpakaian berlebihan. Salah satu
kemungkinannya adalah teknik [putus
sekolah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques_for_regularization)
yang diperkenalkan kembali di Bab 3. Ingatlah bahwa ide dasar putus
sekolah adalah menghapus masing-masing aktivasi secara acak saat melatih
jaringan. Hal ini membuat model lebih kuat untuk menghilangkan bukti
individual, dan dengan demikian lebih kecil kemungkinannya untuk
bergantung pada keanehan tertentu dari data pelatihan. Mari coba
terapkan dropout ke lapisan akhir yang terhubung sepenuhnya:

\>\>\> net = Jaringan (\[

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 1 , 28 , 28 ),

filter\_shape = ( 20 , 1 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

ConvPoolLayer ( image\_shape = ( mini\_batch\_size , 20 , 12 , 12 ),

filter\_shape = ( 40 , 20 , 5 , 5 ),

poolsize = ( 2 , 2 ),

aktivasi\_fn = ReLU ),

FullyConnectedLayer (

n\_in = 40 \* 4 \* 4 , n\_out = 1000 , aktivasi\_fn = ReLU , p\_dropout
= 0,5 ),

FullyConnectedLayer (

n\_in = 1000 , n\_out = 1000 , aktivasi\_fn = ReLU , p\_dropout = 0.5 ),

SoftmaxLayer ( n\_in = 1000 , n\_out = 10 , p\_dropout = 0.5 )\],

mini\_batch\_size )

\>\>\> bersih . SGD ( extended\_training\_data , 40 , mini\_batch\_size
, 0,03 ,

validation\_data , test\_data )

Dengan menggunakan ini, kami memperoleh akurasi 99,60

persen, yang merupakan peningkatan substansial atas hasil kami
sebelumnya, terutama tolok ukur utama kami, jaringan dengan
100*neurontersembunyi*,*dimanakamimencapai*

99,37 $ persen.

Ada dua perubahan yang perlu diperhatikan.

Pertama, saya mengurangi jumlah waktu pelatihan menjadi 40

: dropout mengurangi overfitting, jadi kami belajar lebih cepat.

Kedua, lapisan tersembunyi yang terhubung sepenuhnya memiliki neuron
1.000,*bukan*

100 yang digunakan sebelumnya. Tentu saja, dropout secara efektif
menghilangkan banyak neuron saat latihan, sehingga beberapa ekspansi
diharapkan. Sebenarnya, saya mencoba eksperimen dengan neuron
tersembunyi 300*dan*

1.000, dan memperoleh (sangat sedikit) kinerja validasi yang lebih baik
dengan neuron tersembunyi $ 1.000.

**Menggunakan ansambel jaringan:** Cara mudah untuk meningkatkan kinerja
lebih jauh adalah dengan membuat beberapa jaringan saraf, dan kemudian
meminta mereka untuk memilih untuk menentukan klasifikasi terbaik.
Misalkan, misalnya, kami melatih 5

jaringan saraf (*neural networks*) yang berbeda menggunakan resep di
atas, dengan masing-masing mencapai akurasi mendekati 99,6

persen. Meskipun semua jaringan memiliki akurasi yang sama, mereka
mungkin membuat kesalahan yang berbeda, karena inisialisasi acak yang
berbeda. Masuk akal jika memilih di antara jaringan $ 5 kami mungkin
menghasilkan klasifikasi yang lebih baik daripada jaringan individual
mana pun.

Ini kedengarannya terlalu bagus untuk menjadi kenyataan, tetapi ansambel
semacam ini adalah trik umum dengan jaringan saraf (*neural networks*)
dan teknik pembelajaran mesin lainnya. Dan itu memang menghasilkan
perbaikan lebih lanjut: kita berakhir dengan akurasi 99,67

persen. Dengan kata lain, rangkaian jaringan kami mengklasifikasikan
semua, kecuali 33

dari $ 10.000 gambar uji dengan benar.

Kesalahan yang tersisa dalam set tes ditunjukkan di bawah ini. Label di
kanan atas adalah klasifikasi yang benar, menurut data MNIST, sedangkan
di kanan bawah adalah label keluaran oleh ansambel jaring kami:

![http://neuralnetworksanddeeplearning.com/images/ensemble\_errors.png](media/image91.png)

Ada baiknya melihat ini secara rinci. Dua digit pertama, 6 dan 5, adalah
kesalahan asli oleh ansambel kami. Namun, itu juga kesalahan yang bisa
dimengerti, jenis yang bisa dibuat manusia secara masuk akal. Itu 6
benar-benar terlihat sangat seperti 0, dan 5 terlihat sangat seperti 3.
Gambar ketiga, seharusnya 8, sebenarnya terlihat lebih mirip dengan saya
9. Jadi saya berpihak pada jaringan ansambel di sini: Saya berpikir itu
melakukan pekerjaan yang lebih baik daripada siapa pun yang awalnya
menggambar angka. Di sisi lain, gambar keempat, 6, benar-benar terlihat
sangat buruk oleh jaringan kami.

Dan seterusnya. Dalam kebanyakan kasus, pilihan jaringan kami tampaknya
paling tidak masuk akal, dan dalam beberapa kasus mereka telah melakukan
klasifikasi pekerjaan yang lebih baik daripada orang asli yang menulis
digit. Secara keseluruhan, jaringan kami menawarkan kinerja yang luar
biasa, terutama ketika Anda menganggap bahwa mereka mengklasifikasikan
dengan benar 9.967 gambar yang tidak ditampilkan. Dalam konteks itu,
beberapa kesalahan yang jelas di sini tampaknya cukup dapat dimengerti.
Bahkan manusia yang berhati-hati membuat kesalahan sesekali. Jadi saya
berharap hanya manusia yang sangat hati-hati dan metodis yang bisa
melakukan lebih baik. Jaringan kami semakin dekat dengan kinerja
manusia.

**Mengapa kami hanya menerapkan dropout ke lapisan yang sepenuhnya
terhubung:** Jika Anda perhatikan dengan saksama kode di atas, Anda akan
melihat bahwa kami menerapkan dropout hanya pada bagian jaringan yang
sepenuhnya terhubung, bukan ke lapisan convolutional. Pada prinsipnya
kita bisa menerapkan prosedur serupa ke lapisan konvolusional. Tetapi,
pada kenyataannya, tidak perlu: lapisan konvolusional memiliki
resistensi inbuilt yang cukup besar terhadap overfitting. Alasannya
adalah bahwa bobot bersama berarti bahwa filter konvolusional dipaksa
untuk belajar dari seluruh gambar. Hal ini membuat mereka cenderung
menangkap keanehan lokal dalam data pelatihan. Sehingga ada sedikit
kebutuhan untuk menerapkan regulator lain, seperti putus sekolah.

**Melangkah lebih jauh:** Adalah mungkin untuk meningkatkan kinerja pada
MNIST lebih jauh. Rodrigo Benenson telah menyusun [halaman ringkasan
informatif](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://rodrigob.github.io/are_we_there_yet/build/classification_datasets_results.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2zCmpgcIPmhagGDna_w7ji_Am9Q)
, menunjukkan kemajuan selama bertahun-tahun, dengan tautan ke makalah.
Banyak dari makalah ini menggunakan jaringan konvolusional yang dalam di
sepanjang garis yang mirip dengan jaringan yang telah kami gunakan. Jika
Anda menggali makalah Anda akan menemukan banyak teknik menarik, dan
Anda dapat menikmati menerapkan beberapa dari mereka. Jika Anda
melakukannya, sebaiknya mulai implementasi dengan jaringan sederhana
yang dapat dilatih dengan cepat, yang akan membantu Anda lebih cepat
memahami apa yang sedang terjadi.

Sebagian besar, saya tidak akan mencoba mensurvei karya terbaru ini.
Tapi saya tidak bisa menolak membuat satu pengecualian. Ini adalah
makalah 2010 oleh Cireșan, Meier, Gambardella, dan Schmidhuber \* \*
[Excel Neural Nets Deep, Big, Simple tentang Pengakuan Digit Tulisan
Tangan](http://arxiv.org/abs/1003.0358) , oleh Dan Claudiu Cireșan, Ueli
Meier, Luca Maria Gambardella, dan Jürgen Schmidhuber (2010). . Yang
saya sukai dari makalah ini adalah betapa sederhananya. Jaringan adalah
jaringan saraf (*neural networks*) banyak-lapisan, hanya menggunakan
lapisan yang sepenuhnya terhubung (tidak ada konvolusi). Jaringan mereka
yang paling sukses memiliki lapisan tersembunyi yang masing-masing
berisi neuron 2.500,

2.000, 1.500, 1.000, dan 500. Mereka menggunakan ide-ide yang mirip
dengan Simard *et al* untuk memperluas data pelatihan mereka. Namun
terlepas dari itu, mereka menggunakan beberapa trik lain, termasuk tidak
ada lapisan konvolusional: itu adalah jaringan vanilla yang sederhana,
dari jenis yang, dengan cukup kesabaran, bisa dilatih pada 1980-an (jika
set data MNIST ada), diberi daya komputasi yang cukup. Mereka mencapai
akurasi klasifikasi 99,65 persen, kurang lebih sama dengan kita.
Kuncinya adalah menggunakan jaringan yang sangat besar, sangat dalam,
dan menggunakan GPU untuk mempercepat pelatihan. Ini membiarkan mereka
berlatih untuk banyak zaman. Mereka juga memanfaatkan waktu pelatihan
yang panjang untuk secara bertahap menurunkan tingkat pembelajaran dari
10−3 menjadi 10−6

. Latihan yang menyenangkan untuk mencoba mencocokkan hasil ini
menggunakan arsitektur seperti milik mereka.

**Kenapa kita bisa berlatih?** Kami melihat dalam [bab
terakhir](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)
bahwa ada penghalang mendasar untuk pelatihan dalam, *jaringan saraf
(neural networks)* banyak-lapisan. Secara khusus, kami melihat bahwa
gradien cenderung sangat tidak stabil: ketika kami bergerak dari lapisan
output ke lapisan sebelumnya, gradien cenderung menghilang (masalah
gradien hilang) atau meledak (masalah gradien meledak). Karena gradien
adalah sinyal yang kami gunakan untuk berlatih, ini menyebabkan masalah.

Bagaimana kita menghindari hasil itu?

Tentu saja, jawabannya adalah bahwa kami belum menghindari hasil ini.
Sebaliknya, kami telah melakukan beberapa hal yang membantu kami
melanjutkan. Secara khusus: (1) Menggunakan lapisan konvolusional sangat
mengurangi jumlah parameter di lapisan tersebut, membuat masalah
pembelajaran lebih mudah; (2) Menggunakan teknik regularisasi yang lebih
kuat (terutama dropout dan lapisan convolutional) untuk mengurangi
overfitting, yang sebaliknya lebih merupakan masalah dalam jaringan yang
lebih kompleks; (3) Menggunakan unit linear yang diperbaiki alih-alih
neuron sigmoid, untuk mempercepat pelatihan - secara empiris, seringkali
dengan faktor 3

\- 5; (4) Menggunakan GPU dan bersedia melatih untuk jangka waktu yang
lama. Secara khusus, dalam percobaan terakhir kami, kami melatih untuk
40 zaman menggunakan data yang ditetapkan 5 kali lebih besar dari data
pelatihan MNIST mentah. Sebelumnya dalam buku ini kami sebagian besar
dilatih untuk 30 zaman hanya menggunakan data pelatihan mentah.
Menggabungkan faktor (3) dan (4) seolah-olah kita telah melatih faktor
mungkin 30

kali lebih lama dari sebelumnya.

Tanggapan Anda mungkin "Apakah itu? Apakah hanya itu yang harus kita
lakukan untuk melatih jaringan yang dalam? Apa yang diributkan?"

Tentu saja, kami juga menggunakan ide-ide lain: memanfaatkan set data
yang cukup besar (untuk membantu menghindari overfitting); menggunakan
fungsi biaya yang tepat (untuk [menghindari perlambatan
belajar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#the_cross\\-entropy_cost_function)
); menggunakan [inisialisasi berat badan yang
baik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
(juga untuk menghindari perlambatan belajar, karena saturasi neuron);
[memperluas data pelatihan secara
algoritmik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques_for_regularization)
. Kami membahas ide-ide ini dan lainnya di bab-bab sebelumnya, dan
sebagian besar telah mampu menggunakan kembali ide-ide ini dengan
sedikit komentar dalam bab ini.

Dengan itu, ini sebenarnya adalah kumpulan ide yang agak sederhana.
Sederhana, tetapi kuat, saat digunakan dalam konser. Memulai dengan
*pembelajaran dalam (deep learning)* ternyata sangat mudah\!

**Seberapa dalam jaringan ini?** Menghitung lapisan penggabungan
convolutional sebagai satu lapisan, arsitektur terakhir kami memiliki 4

lapisan tersembunyi. Apakah jaringan seperti itu benar-benar layak
disebut jaringan yang *dalam* ? Tentu saja, 4 lapisan tersembunyi jauh
lebih banyak daripada di jaringan dangkal yang kita pelajari sebelumnya.
Sebagian besar jaringan itu hanya memiliki satu lapisan tersembunyi,
atau kadang-kadang 2 lapisan tersembunyi. Di sisi lain, pada 2015
jaringan terdalam yang canggih terkadang memiliki puluhan lapisan
tersembunyi. Saya kadang-kadang mendengar orang-orang mengadopsi sikap
yang lebih dalam daripada Anda, berpendapat bahwa jika Anda tidak
mengikuti jejak Jones dalam hal jumlah lapisan tersembunyi, maka Anda
tidak benar-benar melakukan *pembelajaran dalam (deep learning)*. Saya
tidak bersimpati pada sikap ini, sebagian karena itu membuat definisi
*pembelajaran dalam (deep learning)* menjadi sesuatu yang tergantung
pada hasil saat itu. Terobosan nyata dalam *pembelajaran dalam (deep
learning)* adalah untuk menyadari bahwa praktis untuk melampaui jaringan
layer 1*yangdangkal*−*dan*

2 yang mendominasi pekerjaan hingga pertengahan tahun 2000-an. Itu
benar-benar terobosan yang signifikan, membuka eksplorasi model yang
jauh lebih ekspresif. Tetapi di luar itu, jumlah lapisan bukanlah
kepentingan fundamental utama. Sebaliknya, penggunaan jaringan yang
lebih dalam adalah alat yang digunakan untuk membantu mencapai tujuan
lain - seperti akurasi klasifikasi yang lebih baik.

**Sepatah kata mengenai prosedur:** Pada bagian ini, kami telah dengan
lancar pindah dari jaringan dangkal lapisan tersembunyi tunggal ke
jaringan konvolusional banyak lapisan. Semua tampak begitu mudah\! Kami
melakukan perubahan dan, sebagian besar, kami mendapat peningkatan. Jika
Anda mulai bereksperimen, saya dapat menjamin hal-hal tidak akan selalu
mulus. Alasannya adalah karena saya telah menyajikan narasi yang sudah
dibersihkan, menghilangkan banyak percobaan - termasuk banyak percobaan
yang gagal. Narasi yang sudah dibersihkan ini diharapkan akan membantu
Anda menjelaskan ide-ide dasar. Tetapi juga berisiko membawa kesan yang
tidak lengkap. Mendapatkan jaringan yang baik dan berfungsi bisa
melibatkan banyak trial and error, dan terkadang frustrasi. Dalam
praktiknya, Anda harus melakukan sedikit eksperimen. Untuk mempercepat
proses itu, Anda mungkin perlu meninjau kembali diskusi Bab 3 tentang
[bagaimana memilih hyper-parameter jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#how_to_choose_a_neural_network's_hyper-parameters)
, dan mungkin juga untuk melihat beberapa bacaan lebih lanjut yang
disarankan di bagian itu.

### [Kode untuk jaringan konvolusional kami](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#the_code_for_our_convolutional_networks) 

Baiklah, mari kita lihat kode untuk program kami, network3.py . Secara
struktural, ini mirip dengan network2.py , program yang kami kembangkan
di
[Bab 3](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA)
, walaupun detailnya berbeda, karena penggunaan Theano. Kami akan mulai
dengan melihat kelas FullyConnectedLayer , yang mirip dengan lapisan
yang dipelajari sebelumnya dalam buku ini. Berikut kode (diskusi di
bawah ini) \* \* Catatan ditambahkan November 2016: beberapa pembaca
telah mencatat bahwa di baris inisialisasi diri.w , saya menetapkan
skala = np.sqrt (1.0 / n\_out) , ketika argumen Bab 3 menyarankan
inisialisasi yang lebih baik mungkin skala = np.sqrt (1.0 / n\_in) . Ini
hanyalah kesalahan saya. Di dunia yang ideal, saya akan menjalankan
kembali semua contoh dalam bab ini dengan kode yang benar. Tetap saja,
saya sudah pindah ke proyek lain, jadi saya akan membiarkan kesalahan
pergi. :

kelas FullyConnectedLayer ( objek ):

def \_\_init\_\_ ( mandiri , n\_in , n\_out , aktivasi\_fn = sigmoid ,
p\_dropout = 0,0 ):

diri n\_in = n\_in

diri n\_out = n\_out

diri aktivasi\_fn = aktivasi\_fn

diri p\_dropout = p\_dropout

\# Inisialisasi bobot dan bias

diri w = theano . dibagikan (

np . asarray (

np . acak . normal (

loc = 0,0 , skala = np . sqrt ( 1.0 / n\_out ), size = ( n\_in , n\_out
)),

dtype = theano . konfigurasi floatX ),

name = 'w' , meminjam = Benar )

diri b = theano . dibagikan (

np . asarray ( np . acak . normal ( loc = 0.0 , skala = 1.0 , size = (
n\_out ,)),

dtype = theano . konfigurasi floatX ),

name = 'b' , meminjam = Benar )

diri params = \[ sendiri . w , diri sendiri . b \]

def set\_inpt ( self , inpt , inpt\_dropout , mini\_batch\_size ):

diri inpt = inpt . membentuk kembali (( mini\_batch\_size , self . n\_in
))

diri output = sendiri . aktivasi\_fn (

( 1 - diri . P\_dropout ) \* T. dot ( self . inpt , self . w ) + self .
b )

diri y\_out = T. argmax ( output mandiri , sumbu = 1 )

diri inpt\_dropout = dropout\_layer (

inpt\_dropout . membentuk kembali (( mini\_batch\_size , self . n\_in
)), self . p\_dropout )

diri output\_dropout = mandiri . aktivasi\_fn (

T. dot ( self . inpt\_dropout , self . w ) + self . b )

akurasi def ( diri , y ):

"Kembalikan keakuratan untuk mini-batch."

kembali T. berarti ( T. eq ( y , self . y\_out ))

Sebagian besar metode \_\_init\_\_ cukup jelas, tetapi beberapa komentar
dapat membantu memperjelas kode. Seperti biasa, kami menginisialisasi
bobot dan bias secara acak sebagai variabel acak normal dengan standar
deviasi yang sesuai. Garis-garis yang melakukan ini terlihat agak
menakutkan. Namun, sebagian besar komplikasi hanya memuat bobot dan bias
ke dalam apa yang Theano sebut sebagai variabel bersama. Ini memastikan
bahwa variabel-variabel ini dapat diproses pada GPU, jika tersedia. Kami
tidak akan terlalu banyak membahas detail ini. Jika Anda tertarik, Anda
dapat menggali [dokumentasi
Theano](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/software/theano/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgf6RWrOvRYsIFHucUjk4QsIdd-PA)
. Perhatikan juga bahwa inisialisasi bobot dan bias ini dirancang untuk
fungsi aktivasi sigmoid (seperti [dibahas
sebelumnya](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
). Idealnya, kita menginisialisasi bobot dan bias agak berbeda untuk
fungsi aktivasi seperti fungsi linier tanh dan diperbaiki. Ini dibahas
lebih lanjut dalam masalah di bawah ini. Metode \_\_init\_\_ selesai
dengan self.params = \[self.w, self.b\] . Ini adalah cara praktis untuk
menggabungkan semua parameter yang bisa dipelajari terkait dengan layer.
Kemudian, metode Network.SGD akan menggunakan atribut params untuk
mencari tahu variabel apa yang dapat dipelajari dalam instance Network .

Metode set\_inpt digunakan untuk mengatur input ke layer, dan untuk
menghitung output yang sesuai. Saya menggunakan nama inpt daripada input
karena input adalah fungsi bawaan di Python, dan mengacaukan built-in
cenderung menyebabkan perilaku yang tidak dapat diprediksi dan bug yang
sulit didiagnosis. Perhatikan bahwa kami benar-benar mengatur input
dalam dua cara terpisah: sebagai self.inpt dan self.inpt\_dropout . Ini
dilakukan karena selama pelatihan kita mungkin ingin menggunakan
dropout. Jika itu masalahnya maka kami ingin menghapus sebagian kecil
self.p\_dropout dari neuron. Itulah yang dilakukan fungsi dropout\_layer
di baris kedua-terakhir metode set\_inpt . Jadi self.inpt\_dropout dan
self.output\_dropout digunakan selama pelatihan, sedangkan
self.inpt\_dropout digunakan untuk semua tujuan lain, misalnya
mengevaluasi akurasi pada validasi dan data uji.

Definisi kelas ConvPoolLayer dan SoftmaxLayer mirip dengan
FullyConnectedLayer . Memang, mereka sangat dekat sehingga saya tidak
akan mengutip kode di sini. Jika Anda tertarik, Anda dapat melihat
daftar lengkap untuk network3.py , nanti di bagian ini.

Namun, beberapa perbedaan kecil detail patut disebutkan. Paling jelas,
di kedua ConvPoolLayer dan SoftmaxLayer kami menghitung aktivasi output
dengan cara yang sesuai dengan jenis lapisan itu. Untungnya, Theano
membuatnya mudah, menyediakan operasi bawaan untuk menghitung konvolusi,
max-pooling, dan fungsi softmax.

Kurang jelas, ketika kami [memperkenalkan lapisan
softmax](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#softmax)
, kami tidak pernah membahas bagaimana menginisialisasi bobot dan bias.
Di tempat lain kami berpendapat bahwa untuk lapisan sigmoid kita harus
menginisialisasi bobot menggunakan variabel acak normal parameter yang
sesuai. Tapi argumen heuristik itu khusus untuk neuron sigmoid (dan,
dengan beberapa perubahan, untuk neuron tanh). Namun, tidak ada alasan
khusus argumen tersebut berlaku untuk lapisan softmax. Jadi tidak ada
alasan *apriori* untuk menerapkan inisialisasi itu lagi. Daripada
melakukan itu, saya akan menginisialisasi semua bobot dan bias menjadi 0

. Ini adalah prosedur yang agak *ad hoc* , tetapi cukup berhasil dalam
praktiknya.

Oke, kita sudah melihat semua kelas layer. Bagaimana dengan kelas
Jaringan ? Mari kita mulai dengan melihat metode \_\_init\_\_ :

Jaringan kelas ( objek ):

def \_\_init\_\_ ( self , layers , mini\_batch\_size ):

"" "Mengambil daftar\` lapisan\`, menjelaskan arsitektur jaringan, dan

nilai untuk \`mini\_batch\_size\` yang akan digunakan selama pelatihan

oleh keturunan gradien stokastik.

"" "

diri lapisan = lapisan

diri mini\_batch\_size = mini\_batch\_size

diri params = \[ param untuk layer dalam diri . lapisan untuk param di
lapisan . params \]

diri x = T. matriks ( "x" )

diri y = T. ivector ( "y" )

init\_layer = diri . lapisan \[ 0 \]

init\_layer . set\_inpt ( self . x , self . x , self . mini\_batch\_size
)

untuk j in xrange ( 1 , len ( self . layers )):

prev\_layer , layer = diri . lapisan \[ j - 1 \], mandiri . lapisan \[ j
\]

lapisan . set\_inpt (

prev\_layer . output , prev\_layer . output\_dropout , mandiri .
mini\_batch\_size )

diri output = sendiri . lapisan \[ - 1 \] . keluaran

diri output\_dropout = mandiri . lapisan \[ - 1 \] . output\_dropout

Sebagian besar sudah jelas, atau hampir seperti itu. Baris self.params =
\[param untuk lapisan dalam ...\] bundel parameter untuk setiap lapisan
ke dalam satu daftar. Seperti yang diantisipasi di atas, metode
Network.SGD akan menggunakan self.params untuk mencari tahu variabel apa
yang dapat dipelajari dalam Jaringan . Baris self.x = T.matrix ("x") dan
self.y = T.ivector ("y") mendefinisikan variabel simbolik Theano bernama
x dan y . Ini akan digunakan untuk mewakili input dan output yang
diinginkan dari jaringan.

Sekarang, ini bukan tutorial Theano, jadi kami tidak akan terlalu
mendalam tentang apa artinya ini adalah variabel simbolik \* \*
[Dokumentasi
Theano](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://deeplearning.net/software/theano/index.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgf6RWrOvRYsIFHucUjk4QsIdd-PA)
memberikan pengantar yang baik untuk Theano. Dan jika Anda buntu, Anda
mungkin akan terbantu untuk melihat salah satu tutorial lain yang
tersedia secara online. Misalnya, [tutorial
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://nbviewer.ipython.org/github/craffel/theano-tutorial/blob/master/Theano%2520Tutorial.ipynb&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgLs7j1_CTULLOeM_Ot9QZo0Jmwkw)
mencakup banyak dasar. . Tetapi gagasan kasarnya adalah bahwa ini
mewakili variabel matematika, *bukan* nilai eksplisit. Kita dapat
melakukan semua hal yang biasa dilakukan seseorang dengan
variabel-variabel seperti: menambah, mengurangi, dan mengalikannya,
menerapkan fungsi, dan sebagainya. Memang, Theano menyediakan banyak
cara untuk memanipulasi variabel simbolik seperti itu, melakukan hal-hal
seperti konvolusi, penyatuan maksimum, dan sebagainya. Tetapi kemenangan
besar adalah kemampuan untuk melakukan diferensiasi simbolik cepat,
menggunakan bentuk yang sangat umum dari algoritma backpropagation. Ini
sangat berguna untuk menerapkan keturunan gradien stokastik ke berbagai
arsitektur jaringan. Secara khusus, beberapa baris kode berikutnya
menentukan keluaran simbolik dari jaringan. Kami mulai dengan mengatur
input ke lapisan awal, dengan garis

init\_layer . set\_inpt ( self . x , self . x , self . mini\_batch\_size
)

Perhatikan bahwa input ditetapkan satu mini-batch sekaligus, itulah
mengapa ukuran mini-batch ada. Perhatikan juga bahwa kami melewatkan
input self.x dua kali: ini karena kami dapat menggunakan jaringan dengan
dua cara berbeda (dengan atau tanpa putus). For for kemudian menyebarkan
variabel simbolis self.x ke depan melalui lapisan-lapisan Jaringan . Ini
memungkinkan kita untuk mendefinisikan atribut final output dan
output\_dropout , yang secara simbolis mewakili output dari Jaringan .

Sekarang kita telah mengerti bagaimana sebuah Jaringan diinisialisasi,
mari kita lihat bagaimana ia dilatih, menggunakan metode SGD . Kode
terlihat panjang, tetapi strukturnya sebenarnya agak sederhana. Komentar
penjelasan setelah kode.

def SGD ( self , training\_data , epochs , mini\_batch\_size , eta ,

validation\_data , test\_data , lmbda = 0.0 ):

"" "Latih jaringan menggunakan mini-batch gradient descent stochastic."
""

training\_x , training\_y = training\_data

validation\_x , validation\_y = validation\_data

test\_x , test\_y = test\_data

\# hitung jumlah minibatch untuk pelatihan, validasi dan pengujian

num\_training\_batches = size ( training\_data ) / mini\_batch\_size

num\_validation\_batches = size ( validation\_data ) / mini\_batch\_size

num\_test\_batches = size ( test\_data ) / mini\_batch\_size

\# mendefinisikan fungsi biaya (diatur), gradien simbolik, dan pembaruan

l2\_norm\_squared = jumlah (\[( lapisan . w \*\* 2 ) . jumlah () untuk
lapisan dalam lapisan . \]

biaya = diri . lapisan \[ - 1 \] . biaya ( mandiri ) + \\

0,5 \* lmbda \* l2\_norm\_squared / num\_training\_batches

lulusan = T. lulusan ( biaya , par . mandiri )

pembaruan = \[( param , param - eta \* grad )

untuk param , lulusan zip ( self . params , grads )\]

\# tentukan fungsi untuk melatih batch-mini, dan untuk menghitung

\# akurasi dalam validasi dan uji mini-batch.

i = T. lscalar () \# indeks mini-batch

train\_mb = theano . fungsi (

\[ i \], biaya , pembaruan = pembaruan ,

givens = {

diri x :

training\_x \[ saya \* sendiri . mini\_batch\_size : ( i +1 ) \* mandiri
. mini\_batch\_size \],

diri y :

training\_y \[ i \* self . mini\_batch\_size : ( i +1 ) \* mandiri .
mini\_batch\_size \]

})

validate\_mb\_accuracy = theano . fungsi (

\[ i \], sendiri . lapisan \[ - 1 \] . akurasi ( self . y ),

givens = {

diri x :

validation\_x \[ i \* self . mini\_batch\_size : ( i +1 ) \* mandiri .
mini\_batch\_size \],

diri y :

validation\_y \[ i \* self . mini\_batch\_size : ( i +1 ) \* mandiri .
mini\_batch\_size \]

})

test\_mb\_accuracy = theano . fungsi (

\[ i \], sendiri . lapisan \[ - 1 \] . akurasi ( self . y ),

givens = {

diri x :

test\_x \[ saya \* sendiri . mini\_batch\_size : ( i +1 ) \* mandiri .
mini\_batch\_size \],

diri y :

test\_y \[ i \* self . mini\_batch\_size : ( i +1 ) \* mandiri .
mini\_batch\_size \]

})

diri test\_mb\_predictions = theano . fungsi (

\[ i \], sendiri . lapisan \[ - 1 \] . y\_out ,

givens = {

diri x :

test\_x \[ saya \* sendiri . mini\_batch\_size : ( i +1 ) \* mandiri .
mini\_batch\_size \]

})

\# Lakukan pelatihan yang sebenarnya

best\_validation\_accuracy = 0,0

untuk zaman di xrange ( zaman ):

untuk minibatch\_index di xrange ( num\_training\_batches ):

iteration = num\_training\_batches \* zaman + minibatch\_index

jika iterasi

print ( " Format mini-batch number {0}" . ( iterasi ))

cost\_ij = train\_mb ( minibatch\_index )

jika ( iterasi + 1 )

validation\_accuracy = np . berarti (

\[ validate\_mb\_accuracy ( j ) untuk j in xrange (
num\_validation\_batches )\])

print ( "Epoch {0}: akurasi validasi {1: .2

zaman , validation\_accuracy ))

jika validation\_accuracy \> = best\_validation\_accuracy :

print ( "Ini adalah akurasi validasi terbaik hingga saat ini." )

best\_validation\_accuracy = validation\_accuracy

best\_iteration = iterasi

jika test\_data :

test\_accuracy = np . berarti (

\[ test\_mb\_accuracy ( j ) untuk j in xrange ( num\_test\_batches )\])

print ( 'Akurasi pengujian yang sesuai adalah {0: .2

test\_accuracy ))

print ( "Jaringan pelatihan jadi." )

print ( "Akurasi validasi terbaik dari {0: .2

best\_validation\_accuracy , best\_iteration ))

print ( "Akurasi uji yang sesuai dari {0: .2

Beberapa baris pertama bersifat langsung, memisahkan dataset menjadi
komponen *x*

dan *y*

, dan menghitung jumlah mini-batch yang digunakan dalam setiap dataset.
Beberapa baris berikutnya lebih menarik, dan tunjukkan beberapa hal yang
membuat Theano menyenangkan untuk dikerjakan. Mari secara eksplisit
mengutip garis-garis di sini:

\# mendefinisikan fungsi biaya (diatur), gradien simbolik, dan pembaruan

l2\_norm\_squared = jumlah (\[( lapisan . w \*\* 2 ) . jumlah () untuk
lapisan dalam lapisan . \]

biaya = diri . lapisan \[ - 1 \] . biaya ( mandiri ) + \\

0,5 \* lmbda \* l2\_norm\_squared / num\_training\_batches

lulusan = T. lulusan ( biaya , par . mandiri )

pembaruan = \[( param , param - eta \* grad )

untuk param , lulusan zip ( self . params , grads )\]

Dalam baris ini kita secara simbolis mengatur fungsi biaya
log-likelihood yang diatur, menghitung turunan yang sesuai dalam fungsi
gradien, serta pembaruan parameter yang sesuai. Theano memungkinkan kita
mencapai semua ini hanya dalam beberapa baris berikut. Satu-satunya hal
yang disembunyikan adalah bahwa penghitungan biaya melibatkan panggilan
ke metode biaya untuk lapisan keluaran; kode itu ada di tempat lain di
network3.py . Tetapi kode itu pendek dan sederhana. Dengan semua hal ini
didefinisikan, tahap ditetapkan untuk mendefinisikan fungsi train\_mb ,
fungsi simbol Theano yang menggunakan pembaruan untuk memperbarui
parameter Jaringan , diberi indeks mini-batch. Demikian pula,
validate\_mb\_accuracy dan test\_mb\_accuracy menghitung akurasi
Jaringan pada setiap mini-batch validasi atau data uji yang diberikan.
Dengan rata-rata atas fungsi-fungsi ini, kita akan dapat menghitung
akurasi pada seluruh set validasi dan data uji.

Sisa dari metode SGD cukup jelas - kami hanya mengulangi zaman, berulang
kali melatih jaringan pada mini-batch data pelatihan, dan menghitung
validasi dan akurasi pengujian.

Oke, sekarang kita telah memahami bagian kode yang paling penting di
network3.py . Mari kita lihat keseluruhan program. Anda tidak perlu
membaca ini secara terperinci, tetapi Anda mungkin menikmati meliriknya,
dan mungkin menyelam ke bagian mana pun yang sesuai dengan keinginan
Anda. Cara terbaik untuk benar-benar memahaminya adalah, tentu saja,
dengan memodifikasinya, menambahkan fitur tambahan, atau refactoring apa
pun yang Anda pikir dapat dilakukan dengan lebih elegan. Setelah kode,
ada beberapa masalah yang berisi beberapa saran pemula untuk hal-hal
yang harus dilakukan. Ini kode \* \* Menggunakan Theano di GPU bisa
sedikit rumit. Secara khusus, mudah untuk membuat kesalahan dengan
menarik data dari GPU, yang dapat memperlambat banyak hal. Saya sudah
mencoba menghindari ini. Dengan demikian, kode ini tentu saja dapat
dipercepat sedikit lebih jauh dengan optimasi konfigurasi Theano yang
cermat. Lihat dokumentasi Theano untuk lebih jelasnya. :

"" "network3.py \~\~\~\~\~\~\~\~\~\~\~\~\~\~ Program berbasis Theano
untuk pelatihan dan menjalankan jaringan saraf (*neural networks*)
sederhana . Mendukung beberapa tipe layer (terhubung penuh,
convolutional, max pooling, softmax), dan fungsi aktivasi (sigmoid,
tanh, dan unit linear yang diperbaiki, dengan lebih mudah ditambahkan).
Ketika dijalankan pada CPU, program ini jauh lebih cepat daripada
network.py dan network2.py. Namun, tidak seperti network.py dan
network2.py ia dapat juga dapat dijalankan pada GPU, yang membuatnya
tetap lebih cepat, karena kodenya didasarkan pada Theano, kodenya
berbeda dalam banyak hal dari network.py dan network2.py. Namun, jika
memungkinkan saya telah mencoba mempertahankan konsistensi dengan yang
sebelumnya. program. Secara khusus, API mirip dengan network2.py.
Perhatikan bahwa saya telah fokus pada membuat kode sederhana, mudah
dibaca, dan mudah dimodifikasi. Itu tidak dioptimalkan, dan
menghilangkan banyak fitur yang diinginkan. Program ini menggabungkan
ide-ide dari Theano dokumentasi tentang jaring saraf convolutional
(terutama, http://deeplearning.net/tutorial/lenet.html), dari penerapan
dropout Misha Denil (https://github.com/mdenil/dropout), dan dari Chris
Olah (http://colah.github.io). Ditulis untuk Theano 0.6 dan 0.7, perlu
beberapa perubahan untuk versi terbaru Theano. "" " \#\#\#\# Pustaka \#
Impor pustaka standar cPickle import gzip \# Pustaka pihak ketiga
mengimpor numpy sebagai impor np theano mengimpor theano.tensor sebagai
T dari theano.tensor.nnet impor konv dari theano.tensor.nnet impor
softmax dari theano .tensor import shared\_randomstreams dari
theano.tensor.signal import downsample \# Fungsi aktivasi untuk neuron
def linear ( z ): return z def ReLU ( z ): pengembalian maksimum T ( 0,0
, z ) dari theano.tensor.nnet impor sigmoid dari theano .tensor import
tanh \#\#\#\# Constants GPU = Benar jika GPU : cetak "Mencoba dijalankan
di bawah GPU. Jika ini tidak diinginkan, maka modifikasi " + \\ "
network3.py \\ n untuk mengatur flag GPU ke False. " Coba : theano .
Config . Device = 'gpu' kecuali : pass \# ini sudah mengatur theano .
Config . FloatX = 'float32' lain : cetak "Berjalan dengan CPU. Jika ini
tidak diinginkan, maka modifikasi " + \\ " network3.py untuk mengatur \\
n flag GPU ke True. " \#\#\#\# Muat def data MNIST load\_data\_share (
nama file = " ../data/mnist.pkl. gz " ): f = gzip . open ( nama file ,
'rb' ) training\_data , validation\_data , test\_data = cPickle . memuat
( f ) f . close () def shared ( data ): " "" Tempatkan data ke dalam
variabel yang dibagi. Ini memungkinkan Theano untuk menyalin data ke
GPU, jika ada. "" " shared\_x = theano . shared ( np . asarray ( data \[
0 \], dtype = theano . config . floatX ), pinjam = True ) shared\_y =
theano . shared ( np . asarray ( data \[ 1 \], dtype = theano . config .
floatX ), meminjam = True ) return shared\_x , cast T. ( shared\_y ,
"int32" ) return \[ shared ( training\_data ), shared ( validation\_data
), shared ( test\_data )\] \#\#\#\# Kelas utama digunakan untuk
membangun dan melatih kelas jaringan Jaringan ( objek ): def
\_\_init\_\_ ( mandiri , lapisan , mini\_batch\_size ): "" "Mengambil
daftar\` lapisan\`, menggambarkan arsitektur jaringan, dan nilai untuk
\`mini\_batch\_size\` yang akan digunakan selama pelatihan dengan
penurunan gradien stokastik . "" " self . layers = layers self .
mini\_batch\_size = mini\_batch\_size self . params = \[ param untuk
layer di self . layers untuk param di layer . params \] self . x = T.
matrix ( " x " ) self . y = T. ivector ( "y" ) init\_layer = self .
layers \[ 0 \] init\_layer . set\_inpt ( self . x , self . x , self .
mini\_batch\_size ) untuk j in xrange ( 1 , len ( self . layers )):
prev\_layer , layer = self layer \[ j - 1 \], self . layer \[ j \] layer
. set\_inpt ( prev\_layer . output , prev\_layer . output\_dropout ,
self . mini\_batch\_size ) self . output = self . layers \[ - 1 \] .
self output . output\_dropout = self . layers \[ - 1 \] .
Output\_dropout def SGD ( self , training\_data , epochs ,
mini\_batch\_size , eta , validation\_data , test\_data , lmbda = 0.0 ):
"" "Latih jaringan menggunakan mini-batch gradient gradient descent." ""
Training\_x , training\_y = training\_data. " validation\_x ,
validation\_y = validation\_data test\_x , test\_y = test\_data \#
hitung jumlah minibatch untuk pelatihan, validasi dan pengujian num\_
training\_batches = size ( training\_data ) / mini\_batch\_size
num\_validation\_batches = size ( validation\_data ) / mini\_batch\_size
num\_test\_batches = ukuran ( test\_data ) / mini\_batch\_size \#
menentukan fungsi biaya, pengaturan simbol, gradien simbol, ( jumlah
pembaruan) w \*\* 2 ) . jumlah () untuk layer dalam diri . lapisan \])
biaya = mandiri . lapisan \[ - 1 \] . biaya ( mandiri ) + \\ 0,5 \*
lmbda \* l2\_norm\_squared / num\_training\_batches kelulusan = T.
pembaruan grad ( biaya , par . mandiri ) = \[( param , param - eta \*
grad ) untuk param , grad dalam zip ( mandiri . params , lulusan )\] \#
mendefinisikan fungsi untuk melatih bets-mini, dan untuk menghitung
akurasi \# dalam validasi dan uji mini-batch. i = T. lscalar () \#
mini-batch index train\_mb = theano . fungsi ( \[ i \], biaya ,
pembaruan = pembaruan , givens = { self . x : training\_x \[ i \* self .
mini\_batch\_size : ( i + 1 ) \* mandiri . mini\_batch\_size \], mandiri
. y : training\_y \[ i \* self . mini\_batch\_size : ( i + 1 ) \*
mandiri . mini\_batch\_size \] }) validate\_mb\_accuracy = theano .
function ( \[ i \], self . layers \[ - 1 \] . akurasi ( self . y ),
givens = { self . x : validation\_x \[ i \* self . mini\_batch\_size : (
i + 1 ) \* self . mini\_batch\_size \], self . y : validation\_y \[ i \*
self . mini\_batch\_size : ( i + 1 ) \* self . mini\_batch\_size \] })
test\_mb\_accuracy = theano . function ( \[ i \], self . layers \[ - 1
\] . akurasi ( self . y ), givens = { self . x : test\_x \[ i \* self .
mini\_batch\_size : ( i + 1 ) \* self . mini\_batch\_size \], self . y :
test\_y \[ i \* self . mini\_batch\_size : ( i +1 ) \* self .
mini\_batch\_size \] }) mandiri . test\_mb\_predictions = theano .
function ( \[ i \], self . layers \[ - 1 \] . y\_out , givens = { self .
x : test\_x \[ i \* self . mini\_batch\_size : ( i + 1 ) \* self .
mini\_batch\_size \] }) \# Lakukan pelatihan aktual
best\_validation\_accuracy = 0,0 untuk epoch in xrange ( epochs ): untuk
minibatch\_index di xrange ( num\_training\_batches ): iterasi =
num\_training\_batches \* epoch + minibatch\_index jika iterasi % 1000
== 0 : cetak ( "Nomor mini-batch pelatihan {0}" . Format ( iterasi ))
cost\_ij = train\_mb ( minibatch\_index ) jika ( iterasi + 1 ) %
num\_training\_batches == 0 : validation\_accuracy = np . mean ( \[
validate\_mb\_accuracy ( j ) untuk j in xrange (
num\_validation\_batches )\]) mencetak ( "Epoch {0}: akurasi validasi
{1: .2%}" . format ( epoch , validation\_accuracy )) jika
validation\_accuracy \> = best\_validation\_accuracy : print ( "Ini
adalah akurasi validasi terbaik hingga saat ini." )
Best\_validation\_accuracy = validation\_accuracy best\_iteration =
iterasi jika test\_data : test\_accuracy = np . mean ( \[
test\_mb\_accuracy ( j ) untuk j in xrange ( num\_test\_batches )\])
print ( 'Akurasi pengujian yang sesuai adalah {0: .2%}' . format (
test\_accuracy )) print ( "Jaringan pelatihan jadi." ) print ( " Akurasi
validasi terbaik dari {0: .2%} diperoleh pada format iterasi {1} " . (
Best\_validation\_accuracy , best\_iteration )) cetak ( " Akurasi uji
yang sesuai dari format {0: .2%} " . ( Test\_accuracy )) \#\#\# \#
Tentukan kelas jenis lapisan ConvPoolLayer ( objek ): "" "Digunakan
untuk membuat kombinasi lapisan convolutional dan max-pooling .
Implementasi yang lebih canggih akan memisahkan keduanya, tetapi untuk
tujuan kami, kami akan selalu menggunakannya bersama, dan itu
menyederhanakan kode, jadi masuk akal untuk menggabungkannya. "" " def
\_\_init\_\_ ( self , filter\_shape , image\_shape , poolsize = ( 2 , 2
), activation\_fn = sigmoid ): " "" \`filter\_shape\` adalah tuple
dengan panjang 4 , yang isinya adalah jumlah filter, jumlah peta fitur
input, tinggi filter, dan lebar filter. \`image\_shape\` adalah tupel
panjang 4, yang isinya adalah ukuran mini-batch, jumlah peta fitur
input, tinggi gambar , dan lebar gambar. \`poolsize\` adalah tuple
dengan panjang 2, yang isinya adalah ukuran pooling y dan x. "" " self .
filter\_shape = filter\_shape self . image\_shape = image\_shape self .
poolsize = poolsize self . aktivasi\_fn = aktivasi\_fn \# inisialisasi
bobot dan bias n\_out = ( filter\_shape \[ 0 \] \* np . prod (
filter\_shape \[ 2 :\]) / np . prod ( kumpulan ukuran )) diri .w =
theano . dibagikan ( np . asarray ( np . acak . normal ( loc = 0 , skala
= np . sqrt ( 1.0 / n\_out ), ukuran = filter\_shape ), dtype = theano .
config . floatX ) , pinjam = Benar ) diri .b = theano . dibagikan ( np .
asarray ( np . acak . normal ( loc = 0 , skala = 1.0 , ukuran = (
filter\_shape \[ 0 \],)), dtype = theano . config . floatX ) , pinjam =
True ) mandiri . params = \[ mandiri . w , mandiri . b \] def set\_inpt
( self , inpt , inpt\_dropout , mini\_batch\_size ): self . inpt = inpt
. pembentukan ulang ( self . image\_shape ) conv\_out = conv . conv2d (
input = self . inpt , filter = self . w , filter\_shape = self .
filter\_shape , image\_shape = self . image\_shape ) pooled\_out =
downsample . max\_pool\_2d ( input = conv\_out , ds = self . poolsize ,
i gnore\_border = Benar ) sendiri . output = sendiri . activation\_fn (
pooled\_out + self . b . dimshuffle ( 'x' , 0 , 'x' , 'x' )) mandiri .
output\_dropout = mandiri . output \# no dropout di kelas lapisan
konvolusional FullyConnectedLayer ( objek ): def \_\_init\_\_ ( self ,
n\_in , n\_out , aktivasi\_fn = sigmoid , p\_dropout = 0,0 ): self .
n\_in = n\_in sendiri . n\_out = n\_out self . aktivasi\_fn =
aktivasi\_fn sendiri . p\_dropout = p\_dropout \# Inisialisasi bobot dan
bias sendiri . w = theano . dibagikan ( np . asarray ( np . acak .
normal ( loc = 0,0 , skala = np . sqrt ( 1.0 / n\_out ), size = ( n\_in
, n\_out )), dtype = theano . config . floatX ), name = 'w' , pinjam =
Benar ) sendiri . b = theano . dibagikan ( np . asarray ( np . acak .
normal ( loc = 0,0 , skala = 1.0 , ukuran = ( n\_out ,)), dtype = theano
. config . floatX ), nama = 'b' , pinjam = Benar ) sendiri . params = \[
sendiri . w , diri sendiri . b \] def set\_inpt ( self , inpt ,
inpt\_dropout , mini\_batch\_size ): self . inpt = inpt . membentuk
kembali (( mini\_batch\_size , self . n\_in )) sendiri . output =
sendiri . activation\_fn ( ( 1 - self . p\_dropout ) \* T. dot ( self .
inpt , self . w ) + self . b ) self . y\_out = T. argmax ( self . output
, axis = 1 ) sendiri . inpt\_dropout = dropout\_layer ( inpt\_dropout .
membentuk kembali (( mini\_batch\_size , self . n\_in )), self .
p\_dropout ) sendiri . output\_dropout = mandiri . activation\_fn ( T.
dot ( self . inpt\_dropout , self . w ) + self . b ) keakuratan def (
self , y ): "Kembalikan akurasi untuk mini-batch." kembali T. mean ( T.
eq ( y , self . y\_out )) kelas SoftmaxLayer ( objek ): def \_\_init\_\_
( self , n\_in , n\_out , p\_dropout = 0.0 ): mandiri . n\_in = n\_in
sendiri . n\_out = n\_out self . p\_dropout = p\_dropout \# Inisialisasi
bobot dan bias sendiri . w = theano . dibagikan ( np . nol (( n\_in ,
n\_out ), dtype = theano . config . floatX ), name = 'w' , meminjam =
Benar ) sendiri . b = theano . dibagikan ( np . nol (( n\_out ,), dtype
= theano . config . floatX ), name = 'b' , pinjam = Benar ) sendiri .
params = \[ sendiri . w , diri sendiri . b \] def set\_inpt ( self ,
inpt , inpt\_dropout , mini\_batch\_size ): self . inpt = inpt .
membentuk kembali (( mini\_batch\_size , self . n\_in )) sendiri .
output = softmax (( 1 - self . p\_dropout ) \* T. dot ( self . inpt ,
self . w ) + self . b ) self . y\_out = T. argmax ( self . output , axis
= 1 ) sendiri . inpt\_dropout = dropout\_layer ( inpt\_dropout .
membentuk kembali (( mini\_batch\_size , self . n\_in )), self .
p\_dropout ) sendiri . output\_dropout = softmax ( T. dot ( self .
inpt\_dropout , self . w ) + self . b ) biaya def ( self , net ):
"Kembalikan biaya kemungkinan log." kembali - T. mean ( T. log ( self .
output\_dropout ) \[ T. arange ( net . y . shape \[ 0 \]), net . y \])
ketepatan def ( self , y ): "Kembalikan akurasi untuk mini-batch."
kembali T. mean ( T. eq ( y , self . y\_out )) \#\#\#\# Ukuran
miscellanea ( data ): "Kembalikan ukuran dataset\` data\`. " kembalikan
data \[ 0 \] . get\_value ( meminjam = Benar ) . bentuk \[ 0 \] def
dropout\_layer ( layer , p\_dropout ): srng = shared\_randomstreams .
RandomStreams ( np . Random . RandomState ( 0 ) . Randint ( 999999 ))
mask = srng . binomial ( n = 1 , p = 1 - p\_dropout , size = layer .
shape ) return layer \* T. cast ( mask , theano . config . floatX )

#### [Masalah](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#problems_269956) 

  - Saat ini, metode SGD mengharuskan pengguna untuk secara manual
    memilih jumlah zaman untuk dilatih. Sebelumnya dalam buku ini kami
    membahas cara otomatis memilih jumlah zaman untuk dilatih, yang
    dikenal sebagai [penghentian
    awal](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#early_stopping)
    . Ubah network3.py untuk mengimplementasikan penghentian dini.

  - Tambahkan metode Jaringan untuk mengembalikan akurasi pada set data
    yang sewenang-wenang.

  - Ubah metode SGD untuk memungkinkan tingkat pembelajaran  *eta*

• menjadi fungsi dari nomor zaman. *Petunjuk: Setelah mengatasi masalah
ini untuk sementara waktu, Anda mungkin merasa bermanfaat untuk melihat
diskusi di [tautan
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://groups.google.com/forum/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgVccwC_Ti7Kvn-a7Xdqk9rpckEvw#!topic/theano-users/NQ9NYLvleGc)
.*

• Sebelumnya dalam bab ini saya menjelaskan teknik untuk memperluas data
pelatihan dengan menerapkan rotasi (kecil), miring, dan terjemahan. Ubah
network3.py untuk menggabungkan semua teknik ini. *Catatan: Kecuali Anda
memiliki jumlah memori yang luar biasa, tidaklah praktis untuk secara
eksplisit menghasilkan seluruh rangkaian data yang diperluas.* *Jadi,
Anda harus mempertimbangkan pendekatan alternatif.*

• Tambahkan kemampuan untuk memuat dan menyimpan jaringan ke network3.py
.

• Kelemahan dari kode saat ini adalah bahwa ia menyediakan beberapa alat
diagnostik. Dapatkah Anda memikirkan diagnosa apa pun yang ditambahkan
yang akan membuatnya lebih mudah untuk memahami sampai sejauh mana suatu
jaringan mengalami overfitting? Tambahkan mereka.

• Kami telah menggunakan prosedur inisialisasi yang sama untuk unit
linear yang diperbaiki untuk neuron sigmoid (dan tanh).
[Argumen](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
kami [untuk
inisialisasi](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#weight_initialization)
itu khusus untuk fungsi sigmoid. Pertimbangkan jaringan yang seluruhnya
terbuat dari unit linear yang diperbaiki (termasuk output). Tunjukkan
bahwa men-rescaling semua bobot dalam jaringan dengan faktor konstan
*c*\>0 hanya menskors ulang output dengan faktor *cL*−1, di mana *L*

  - adalah jumlah lapisan. Bagaimana ini berubah jika lapisan terakhir
    adalah softmax? Apa pendapat Anda tentang menggunakan prosedur
    inisialisasi sigmoid untuk unit linear yang diperbaiki? Bisakah Anda
    memikirkan prosedur inisialisasi yang lebih baik? *Catatan: Ini
    adalah masalah yang sangat terbuka, bukan sesuatu dengan jawaban
    mandiri yang sederhana.* *Namun, mempertimbangkan masalah akan
    membantu Anda lebih memahami jaringan yang mengandung unit linear
    yang diperbaiki.*

  - [Analisis](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw#what's_causing_the_vanishing_gradient_problem_unstable_gradients_in_deep_neural_nets)
    kami tentang masalah gradien yang tidak stabil adalah untuk neuron
    sigmoid. Bagaimana perubahan analisis untuk jaringan yang terdiri
    dari unit linear yang diperbaiki? Bisakah Anda memikirkan cara yang
    baik untuk memodifikasi jaringan seperti itu sehingga tidak
    menderita masalah gradien yang tidak stabil? *Catatan: Kata baik di
    bagian kedua ini menjadikan masalah sebagai masalah penelitian.*
    *Sebenarnya mudah untuk memikirkan cara membuat modifikasi seperti
    itu.* *Tetapi saya belum menyelidiki secara mendalam untuk
    mengetahui teknik yang benar-benar bagus.*

### [Kemajuan terbaru dalam pengenalan gambar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#recent_progress_in_image_recognition) 

Pada tahun 1998, tahun MNIST diperkenalkan, butuh berminggu-minggu untuk
melatih stasiun kerja canggih untuk mencapai akurasi yang jauh lebih
buruk daripada yang bisa dicapai dengan menggunakan GPU dan kurang dari
satu jam pelatihan. Dengan demikian, MNIST tidak lagi menjadi masalah
yang mendorong batas-batas teknik yang tersedia; alih-alih, kecepatan
pelatihan berarti bahwa itu adalah masalah yang baik untuk tujuan
pengajaran dan pembelajaran. Sementara itu, fokus penelitian telah
beralih, dan pekerjaan modern melibatkan masalah pengenalan citra yang
jauh lebih menantang. Pada bagian ini, saya menjelaskan secara singkat
beberapa pekerjaan terbaru tentang pengenalan gambar menggunakan
jaringan saraf.

Bagian ini berbeda dengan sebagian besar buku. Melalui buku ini saya
fokus pada ide-ide yang cenderung menarik minat - ide-ide seperti
backpropagation, regularisasi, dan jaringan convolutional. Saya sudah
mencoba menghindari hasil yang modis saat saya menulis, tetapi nilai
jangka panjangnya tidak diketahui. Dalam ilmu pengetahuan, hasil seperti
itu lebih sering daripada tidak ephemera yang memudar dan memiliki
dampak jangka panjang. Mengingat hal ini, seorang skeptis mungkin
mengatakan: "Ya, tentu saja kemajuan terbaru dalam pengenalan gambar
adalah contoh dari ephemera seperti itu? Dalam dua atau tiga tahun ke
depan, segalanya akan berubah. Jadi, pasti hasil ini hanya menarik bagi
beberapa spesialis. yang ingin bersaing di perbatasan absolut? Kenapa
repot-repot mendiskusikannya? "

Skeptis semacam itu benar bahwa beberapa perincian yang lebih baik dari
makalah-makalah baru-baru ini secara bertahap akan berkurang dalam hal
kepentingan yang dirasakan. Dengan itu, beberapa tahun terakhir telah
melihat peningkatan luar biasa menggunakan jaring yang dalam untuk
menyerang tugas pengenalan gambar yang sangat sulit. Bayangkan seorang
sejarawan ilmu pengetahuan menulis tentang visi komputer pada tahun
2100. Mereka akan mengidentifikasi tahun 2011 hingga 2015 (dan mungkin
beberapa tahun ke depan) sebagai masa terobosan besar, didorong oleh
jaring konvolusional yang mendalam. Itu tidak berarti jaring
konvolusional yang dalam masih akan digunakan pada tahun 2100, ide-ide
yang kurang rinci seperti putus, unit linear yang diperbaiki, dan
sebagainya. Tetapi ini berarti bahwa transisi penting sedang terjadi,
saat ini, dalam sejarah ide. Ini seperti menonton penemuan atom, atau
penemuan antibiotik: penemuan dan penemuan dalam skala sejarah. Dan
sementara kita tidak akan menggali jauh ke dalam detail, ada baiknya
mendapatkan beberapa ide dari penemuan menarik yang sedang dibuat.

**Makalah LRMD 2012:** Mari saya mulai dengan makalah 2012 \* \*
[Membangun fitur tingkat tinggi menggunakan pembelajaran tanpa
pengawasan skala
besar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://research.google.com/pubs/pub38115.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgFdR4WxSXI1bQRtai0mvOMaxt53Q)
, oleh Quoc Le, Marc'Aurelio Ranzato, Rajat Monga, Matthieu Devin, Kai
Chen, Greg Corrado, Jeff Dean, dan Andrew Ng (2012). Perhatikan bahwa
arsitektur rinci jaringan yang digunakan dalam makalah ini berbeda dalam
banyak detail dari jaringan konvolusional mendalam yang telah kita
pelajari. Secara umum, LRMD didasarkan pada banyak ide serupa. dari
sekelompok peneliti dari Stanford dan Google. Saya akan menyebut makalah
ini sebagai LRMD, setelah nama belakang dari empat penulis pertama. LRMD
menggunakan jaringan saraf (*neural networks*) untuk mengklasifikasikan
gambar dari
[ImageNet](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.image-net.org/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhQNXrZagXzLOY0zd5cLe-oJJN3-Q)
, masalah pengenalan gambar yang sangat menantang. Data ImageNet 2011
yang mereka gunakan termasuk 16 juta gambar penuh warna, dalam 20 ribu
kategori. Gambar-gambar itu dirayapi dari jaring terbuka, dan
diklasifikasikan oleh pekerja dari layanan Mechanical Turk Amazon.
Berikut adalah beberapa gambar ImageNet \* \* Ini berasal dari dataset
2014, yang agak berubah dari 2011. Secara kualitatif, bagaimanapun,
dataset sangat mirip. Rincian tentang ImageNet tersedia dalam kertas
ImageNet asli, [ImageNet: database gambar hierarkis skala
besar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.image-net.org/papers/imagenet_cvpr09.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgpFBdkpPjFu03MqfE9j_Ty6sdNxg)
, oleh Jia Deng, Wei Dong, Richard Socher, Li-Jia Li, Kai Li, dan Li
Fei-Fei (2009). :

![http://neuralnetworksanddeeplearning.com/images/imagenet1.jpg](media/image103.jpeg)![http://neuralnetworksanddeeplearning.com/images/imagenet2.jpg](media/image104.jpeg)![http://neuralnetworksanddeeplearning.com/images/imagenet3.jpg](media/image105.jpeg)![http://neuralnetworksanddeeplearning.com/images/imagenet4.jpg](media/image106.jpeg)

Ini, masing-masing, dalam kategori untuk bidang manik-manik, jamur busuk
akar coklat, susu melepuh, dan cacing gelang biasa. Jika Anda mencari
tantangan, saya mendorong Anda untuk mengunjungi daftar [alat
tangan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.image-net.org/synset%3Fwnid%3Dn03489162&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiuxjF_VXN_DX5xkpvagRS_MxWaCA)
ImageNet, yang membedakan antara pesawat manik-manik, pesawat blok,
pesawat talang, dan sekitar selusin jenis pesawat lainnya, di antara
kategori lainnya. Saya tidak tahu tentang Anda, tetapi saya tidak dapat
dengan yakin membedakan antara semua jenis alat ini. Ini jelas merupakan
tugas pengenalan gambar yang jauh lebih menantang daripada MNIST\!
Jaringan LRMD memperoleh akurasi 15,8

persen terhormat untuk mengklasifikasikan gambar ImageNet dengan benar.
Itu mungkin kedengarannya tidak mengesankan, tetapi ini merupakan
peningkatan besar dibandingkan hasil terbaik sebelumnya dengan akurasi
9,3

persen. Lompatan itu menunjukkan bahwa *jaringan saraf (neural
networks)* mungkin menawarkan pendekatan yang kuat untuk tugas
pengenalan gambar yang sangat menantang, seperti ImageNet.

**Makalah KSH 2012:** Karya LRMD diikuti oleh makalah 2012 Krizhevsky,
Sutskever dan Hinton (KSH) \* \* [Klasifikasi ImageNet dengan *jaringan
saraf (neural networks)* convolutional yang
mendalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.cs.toronto.edu/~fritz/absps/imagenet.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhghao3UCzJmmM-YGbqTz8YTcoYbuQ)
, oleh Alex Krizhevsky, Ilya Sutskever, dan Geoffrey E. Hinton (2012). .
KSH melatih dan menguji jaringan saraf (*neural networks*) convolutional
yang mendalam menggunakan subset terbatas dari data ImageNet. Subset
yang mereka gunakan berasal dari kompetisi pembelajaran mesin yang
populer - Tantangan Pengenalan Visual Skala Besar (ILSVRC) ImageNet.
Menggunakan dataset kompetisi memberi mereka cara yang baik untuk
membandingkan pendekatan mereka dengan teknik terkemuka lainnya. Set
pelatihan ILSVRC-2012 berisi sekitar 1,2 juta gambar ImageNet, yang
diambil dari 1.000 kategori. Set validasi dan tes masing-masing berisi
50.000 dan 150.000 gambar, yang diambil dari 1.000 kategori yang sama.

Salah satu kesulitan dalam menjalankan kompetisi ILSVRC adalah bahwa
banyak gambar ImageNet berisi banyak objek. Misalkan sebuah gambar
menunjukkan seekor labrador retriever mengejar bola sepak. Yang disebut
"benar" klasifikasi ImageNet gambar mungkin sebagai labrador retriever.
Haruskah algoritma dihukum jika label gambar sebagai bola sepak? Karena
ambiguitas ini, suatu algoritma dianggap benar jika klasifikasi ImageNet
aktual adalah di antara 5

klasifikasi algoritma dianggap paling mungkin. Dengan kriteria 5 teratas
ini, jaringan konvolusional mendalam KSH mencapai akurasi 84,7 persen,
jauh lebih baik daripada entri kontes terbaik berikutnya, yang mencapai
akurasi 73,8 persen. Menggunakan metrik yang lebih ketat untuk
mendapatkan label dengan tepat, jaringan KSH mencapai akurasi 63,3

persen.

Ada baiknya menggambarkan secara singkat jaringan KSH, karena telah
mengilhami banyak pekerjaan berikutnya. Ini juga, seperti yang akan kita
lihat, terkait erat dengan jaringan yang kita latih sebelumnya dalam bab
ini, meskipun lebih rumit. KSH menggunakan *jaringan saraf (neural
networks)* convolutional yang mendalam, dilatih pada dua GPU. Mereka
menggunakan dua GPU karena jenis GPU tertentu yang mereka gunakan
(NVIDIA GeForce GTX 580) tidak memiliki cukup memori on-chip untuk
menyimpan seluruh jaringan mereka. Jadi mereka membagi jaringan menjadi
dua bagian, dipartisi di dua GPU.

Jaringan KSH memiliki 7

lapisan neuron tersembunyi. 5 hidden layer pertama adalah lapisan
convolutional (beberapa dengan max-pooling), sedangkan 2 berikutnya
adalah lapisan yang sepenuhnya terhubung. Lapisan output adalah lapisan
softmax 1.000 unit, sesuai dengan kelas gambar $ 1.000. Berikut ini
sketsa jaringan, yang diambil dari kertas KSH \* \* Terima kasih kepada
Ilya Sutskever. . Detailnya dijelaskan di bawah ini. Perhatikan bahwa
banyak lapisan dibagi menjadi 2 bagian, sesuai dengan 2

GPU.

![http://neuralnetworksanddeeplearning.com/images/KSH.jpg](media/image107.jpeg)

Lapisan input berisi 3 *kali*224 *kali*224

neuron, mewakili nilai RGB untuk 224 *kali*224 gambar. Ingatlah bahwa,
seperti yang disebutkan sebelumnya, ImageNet berisi gambar dengan
resolusi yang bervariasi. Ini menimbulkan masalah, karena lapisan input
jaringan saraf (*neural networks*) biasanya berukuran tetap. KSH
menangani ini dengan mengubah ukuran setiap gambar sehingga sisi yang
lebih pendek memiliki panjang 256. Mereka kemudian memotong area
256 *kali*256 di tengah gambar yang diperbesar ulang. Akhirnya, KSH
diekstraksi secara acak 224 *kali*224 subimage (dan refleksi horisontal)
dari 256 *kali*256 gambar. Mereka melakukan penanaman acak ini sebagai
cara memperluas data pelatihan, dan dengan demikian mengurangi
overfitting. Ini sangat membantu dalam jaringan besar seperti KSH.
224*ini* *kali*

224 gambar yang digunakan sebagai input ke jaringan. Dalam kebanyakan
kasus gambar yang dipangkas masih berisi objek utama dari gambar yang
tidak dipotong.

Pindah ke lapisan tersembunyi di jaringan KSH, lapisan tersembunyi
pertama adalah lapisan konvolusional, dengan langkah penyatuan maksimum.
Ini menggunakan bidang penerimaan lokal ukuran 11 *kali*11

, dan panjang langkah 4 piksel. Ada total *fitur* 96 peta fitur. Peta
fitur dibagi menjadi dua kelompok masing-masing 48, dengan peta fitur
48*pertamaberadadisatuGPU*,*danpetafitur* 48 kedua berada di GPU yang
lain. Max-pooling pada layer ini dan selanjutnya dilakukan dalam
3 *kali*3 region, tetapi region pooling diizinkan untuk tumpang tindih,
dan hanya 2

piksel terpisah.

Lapisan tersembunyi kedua juga merupakan lapisan konvolusional, dengan
langkah max-pooling. Ini menggunakan 5 *kali*5

bidang penerimaan lokal, dan ada total 256 fitur peta, dibagi menjadi
128 pada setiap GPU. Perhatikan bahwa peta fitur hanya menggunakan 48

saluran input, bukan $ 96 penuh output dari lapisan sebelumnya (seperti
yang biasanya terjadi). Ini karena setiap peta fitur tunggal hanya
menggunakan input dari GPU yang sama. Dalam hal ini, jaringan berangkat
dari arsitektur konvolusional yang telah kami jelaskan sebelumnya dalam
bab ini, meskipun ide dasarnya masih sama.

Lapisan tersembunyi ketiga, keempat dan kelima adalah lapisan
konvolusional, tetapi tidak seperti lapisan sebelumnya, mereka tidak
melibatkan max-pooling. Parameter penghormatan mereka adalah: (3) 384

peta fitur, dengan 3 *kali*3 bidang penerimaan lokal, dan 256 saluran
input; (4) 384 peta fitur, dengan 3 *kali*3 bidang penerimaan lokal, dan
192 saluran input; dan (5) 256 fitur peta, dengan 3 *kali*3 bidang
penerimaan lokal, dan 192 saluran input. Perhatikan bahwa lapisan ketiga
melibatkan beberapa komunikasi antar-GPU (seperti yang digambarkan dalam
gambar) agar peta fitur menggunakan semua saluran input 256

.

Lapisan tersembunyi keenam dan ketujuh adalah lapisan yang terhubung
penuh, dengan neuron $ 4.096 di setiap lapisan.

Lapisan output adalah lapisan softmax 1.000

\-unit.

Jaringan KSH memanfaatkan banyak teknik. Alih-alih menggunakan fungsi
aktivasi sigmoid atau tanh, KSH menggunakan unit linear yang diperbaiki,
yang mempercepat pelatihan secara signifikan. Jaringan KSH memiliki
sekitar 60 juta parameter yang dipelajari, dan karenanya, bahkan dengan
set pelatihan yang besar, rentan terhadap overfitting. Untuk
mengatasinya, mereka memperluas set pelatihan menggunakan strategi
penanaman acak yang kita bahas di atas. Mereka juga membahas overfitting
dengan menggunakan varian [regularisasi
l2](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#regularization)
, dan
[dropout](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#other_techniques_for_regularization)
. Jaringan itu sendiri dilatih menggunakan mini-batch gradien keturunan
gradien [berbasis
momentum](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap3.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj_LimLQUUrJHy5nkIC3sx5s_LOvA#variations_on_stochastic_gradient_descent)
.

Itulah gambaran dari banyak ide inti dalam makalah KSH. Saya telah
menghilangkan beberapa detail, dan Anda harus melihat kertasnya. Anda
juga dapat melihat cuda-convnet Alex Krizhevsky (dan penerusnya), yang
berisi kode yang mengimplementasikan banyak ide. Implementasi berbasis
Theano juga telah dikembangkan \* \* [Pengenalan visual berskala besar
berbasis Theano dengan beberapa GPU](http://arxiv.org/abs/1412.2302) ,
oleh Weiguang Ding, Ruoyan Wang, Fei Mao, dan Graham Taylor (2014). ,
dengan kode yang tersedia di
[sini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://github.com/uoguelph-mlrg/theano_alexnet&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj9dxLQ9as9-Vplb3-cbLjDsESSVw)
. Kode ini dapat dikenali sejalan dengan yang dikembangkan dalam bab
ini, meskipun penggunaan beberapa GPU agak menyulitkan banyak hal.
Kerangka kerja jaring saraf Caffe juga mencakup versi jaringan KSH,
lihat [Kebun Binatang
Model](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://caffe.berkeleyvision.org/model_zoo.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiDzOi5RND-cavEBdYjmkUOHUIPQg)
mereka untuk detailnya.

**Kompetisi ILSVRC 2014:** Sejak 2012, kemajuan pesat terus dibuat.
Pertimbangkan kompetisi ILSVRC 2014. Seperti pada tahun 2012, itu
melibatkan set pelatihan 1,2

juta gambar, dalam 1.000*kategori*,*danangkamanfaatnyaadalahapakah* 5
prediksi teratas termasuk kategori yang benar. Tim pemenang, berbasis di
Google \* \* [Melangkah lebih dalam dengan
konvolusi](http://arxiv.org/abs/1409.4842) , oleh Christian Szegedy, Wei
Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov,
Dumitru Erhan, Vincent Vanhoucke, dan Andrew Rabinovich (2014). ,
menggunakan jaringan konvolusional yang dalam dengan 22 lapisan neuron.
Mereka menyebut jaringan mereka GoogLeNet, sebagai penghormatan kepada
LeNet-5. GoogLeNet mencapai akurasi top-5 93,33 persen, peningkatan
raksasa atas pemenang 2013 (
[Clarifai](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.clarifai.com/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgo-L12RjO0bExWQLy_Zs82AX2RkA)
, dengan 88,3 persen), dan pemenang 2012 (KSH, dengan 84,7

persen).

Seberapa baik akurasi $ 93,33 persen GoogLeNet dari GoogLeNet? Pada
tahun 2014, tim peneliti menulis makalah survei tentang kompetisi ILSVRC
\* \* [ImageNet tantangan pengakuan visual skala
besar](http://arxiv.org/abs/1409.0575) , oleh Olga Russakovsky, Jia
Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang,
Andrej Karpathy, Aditya Khosla , Michael Bernstein, Alexander C. Berg,
dan Li Fei-Fei (2014). . Salah satu pertanyaan yang mereka jawab adalah
seberapa baik kinerja manusia di ILSVRC. Untuk melakukan ini, mereka
membangun sistem yang memungkinkan manusia mengklasifikasikan gambar
ILSVRC. Seperti yang dijelaskan oleh salah satu penulis, Andrej
Karpathy, dalam [posting blog
yang](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://karpathy.github.io/2014/09/02/what-i-learned-from-competing-against-a-convnet-on-imagenet/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiQAutr74B32z9icPLxaNqAKTvtqA)
informatif, banyak kesulitan untuk membuat manusia mencapai kinerja
GoogLeNet:

... tugas memberi label gambar dengan 5 dari 1000 kategori dengan cepat
ternyata sangat menantang, bahkan untuk beberapa teman di lab yang telah
mengerjakan ILSVRC dan kelas-kelasnya untuk sementara waktu. Pertama
kami pikir kami akan memasangnya di \[Amazon Mechanical Turk\]. Kemudian
kami pikir kami bisa merekrut undergrads berbayar. Kemudian saya
mengorganisir pesta pelabelan upaya pelabelan intens hanya di antara
(pelabelan ahli) di lab kami. Kemudian saya mengembangkan antarmuka yang
dimodifikasi yang menggunakan prediksi GoogLeNet untuk memangkas jumlah
kategori dari 1000 menjadi hanya sekitar 100. Itu masih terlalu sulit -
orang terus kehilangan kategori dan mendapatkan tingkat kesalahan
13-15%. Pada akhirnya saya menyadari bahwa untuk mencapai tempat yang
secara kompetitif dekat dengan GoogLeNet, akan lebih efisien jika saya
duduk dan melalui proses pelatihan yang sangat lama dan proses anotasi
yang cermat berikutnya ... Pelabelan terjadi pada tingkat sekitar 1 per
menit, tetapi ini menurun seiring waktu ... Beberapa gambar mudah
dikenali, sementara beberapa gambar (seperti breed anjing, burung, atau
monyet berbutir halus) dapat membutuhkan beberapa menit upaya
terkonsentrasi. Saya menjadi sangat baik dalam mengidentifikasi ras
anjing ... Berdasarkan sampel gambar yang saya kerjakan, kesalahan
klasifikasi GoogLeNet ternyata menjadi 6,8% ... Kesalahan saya sendiri
pada akhirnya berubah menjadi 5,1%, sekitar 1,7 % lebih baik.

Dengan kata lain, manusia yang ahli, yang bekerja dengan susah payah,
dengan usaha keras mampu mengalahkan jaringan saraf (*neural networks*)
yang dalam. Faktanya, Karpathy melaporkan bahwa seorang pakar manusia
kedua, yang dilatih dengan sampel gambar yang lebih kecil, hanya mampu
mencapai tingkat kesalahan lima besar 12,0

persen, jauh di bawah kinerja GoogLeNet. Sekitar setengah kesalahan itu
disebabkan oleh ahli "gagal menemukan dan menganggap label kebenaran
dasar sebagai pilihan".

Ini adalah hasil yang menakjubkan. Memang, sejak pekerjaan ini, beberapa
tim telah melaporkan sistem yang tingkat kesalahan top-5-nya sebenarnya
*lebih baik* dari 5,1%. Ini kadang-kadang dilaporkan di media sebagai
sistem yang memiliki visi yang lebih baik daripada manusia. Walaupun
hasilnya benar-benar menarik, ada banyak peringatan yang membuatnya
menyesatkan untuk menganggap sistem memiliki visi yang lebih baik
daripada manusia. Tantangan ILSVRC dalam banyak hal adalah masalah yang
agak terbatas - perayapan web terbuka tidak selalu mewakili gambar yang
ditemukan dalam aplikasi\! Dan, tentu saja, kriteria 5

teratas cukup artifisial. Kami masih jauh dari menyelesaikan masalah
pengenalan gambar atau, lebih luas lagi, visi komputer. Namun, sangat
menggembirakan melihat begitu banyak kemajuan yang dibuat pada masalah
yang menantang, hanya dalam beberapa tahun.

**Aktivitas lain:** Saya fokus pada ImageNet, tetapi ada banyak
aktivitas lain yang menggunakan jaring saraf untuk melakukan pengenalan
gambar. Biarkan saya jelaskan secara singkat beberapa hasil terbaru yang
menarik, hanya untuk memberikan rasa dari beberapa pekerjaan saat ini.

Satu set hasil praktis yang menggembirakan datang dari sebuah tim di
Google, yang menerapkan jaringan konvolusional yang dalam untuk masalah
mengenali nomor jalan dalam pencitraan Street View Google \* \*
[Pengakuan Angka Multi-digit dari Pencitraan Street View menggunakan
Jaringan Neural Konvolusioner Dalam](http://arxiv.org/abs/1312.6082) ,
oleh Ian J Goodfellow, Yaroslav Bulatov, Julian Ibarz, Sacha Arnoud, dan
Vinay Shet (2013). . Dalam makalah mereka, mereka melaporkan mendeteksi
dan secara otomatis menyalin hampir 100 juta nomor jalan dengan akurasi
yang sama dengan operator manusia. Sistemnya cepat: sistem mereka
menyalin semua gambar Street View tentang nomor jalan di Prancis dalam
waktu kurang dari satu jam\! Mereka mengatakan: "Memiliki dataset baru
ini secara signifikan meningkatkan kualitas geocoding Google Maps di
beberapa negara terutama yang belum memiliki sumber geocoding yang
baik." Dan mereka terus membuat klaim yang lebih luas: "Kami percaya
dengan model ini kami telah memecahkan \[pengenalan karakter optik\]
untuk urutan pendek \[karakter\] untuk banyak aplikasi."

Saya mungkin memberi kesan bahwa itu semua adalah parade hasil yang
menggembirakan. Tentu saja, beberapa karya paling menarik melaporkan
hal-hal mendasar yang belum kita pahami. Misalnya, sebuah makalah 2013
\* \* [Properti menarik dari jaringan
saraf](http://arxiv.org/abs/1312.6199) , oleh Christian Szegedy,
Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian
Goodfellow, dan Rob Fergus (2013) menunjukkan bahwa jaringan yang dalam
mungkin menderita dari apa yang secara efektif buta. bintik-bintik.
Perhatikan garis-garis gambar di bawah ini. Di sebelah kiri adalah
gambar ImageNet yang diklasifikasikan dengan benar oleh jaringan mereka.
Di sebelah kanan adalah gambar yang sedikit terganggu (perturbasi ada di
tengah) yang diklasifikasikan secara *salah* oleh jaringan. Para penulis
menemukan bahwa ada gambar "permusuhan" untuk setiap gambar sampel,
tidak hanya beberapa yang khusus.

![http://neuralnetworksanddeeplearning.com/images/adversarial.jpg](media/image108.jpeg)

Ini adalah hasil yang mengganggu. Makalah ini menggunakan jaringan
berdasarkan kode yang sama dengan jaringan KSH - yaitu, hanya jenis
jaringan yang semakin banyak digunakan. Sementara *jaringan saraf
(neural networks)* seperti itu menghitung fungsi yang, pada prinsipnya,
terus menerus, hasil seperti ini menunjukkan bahwa dalam praktiknya
mereka cenderung menghitung fungsi yang sangat hampir terputus-putus.
Lebih buruk lagi, mereka akan terputus dengan cara yang melanggar
intuisi kita tentang perilaku yang masuk akal. Itu memprihatinkan.
Selain itu, belum dipahami dengan baik apa yang menyebabkan
diskontinuitas: apakah ini tentang fungsi kerugian? Fungsi aktivasi yang
digunakan? Arsitektur jaringan? Sesuatu yang lain Kami belum tahu.

Sekarang, hasil ini tidak seburuk yang terdengar. Meskipun gambar
permusuhan seperti itu umum, mereka juga tidak mungkin dalam praktiknya.
Seperti catatan kertas:

Keberadaan negatif permusuhan tampaknya bertentangan dengan kemampuan
jaringan untuk mencapai kinerja generalisasi yang tinggi. Memang, jika
jaringan dapat menggeneralisasi dengan baik, bagaimana bisa dikacaukan
oleh hal negatif permusuhan ini, yang tidak dapat dibedakan dari contoh
biasa? Penjelasannya adalah bahwa himpunan negatif permusuhan adalah
probabilitas yang sangat rendah, dan dengan demikian tidak pernah (atau
jarang) diamati dalam set tes, namun padat (seperti angka-angka
rasional), sehingga ditemukan hampir di setiap tes kasus.

Meskipun demikian, sangat menyedihkan bahwa kita memahami jaring saraf
sangat buruk sehingga hasil semacam ini harus menjadi penemuan baru-baru
ini. Tentu saja, manfaat utama dari hasilnya adalah bahwa mereka telah
merangsang banyak pekerjaan lanjutan. Misalnya, satu makalah baru-baru
ini \* \* [Deep Neural Networks Mudah Dibodohi: Prediksi Keyakinan
Tinggi untuk Gambar yang Tidak](http://arxiv.org/abs/1412.1897)
Dikenali, oleh Anh Nguyen, Jason Yosinski, dan Jeff Clune (2014).
menunjukkan bahwa dengan diberi jaringan yang terlatih, dimungkinkan
untuk menghasilkan gambar yang terlihat seperti white noise manusia,
tetapi yang dikelompokkan sebagai kategori yang dikenal dengan tingkat
kepercayaan yang sangat tinggi. Ini adalah demonstrasi lain bahwa kita
memiliki jalan panjang dalam memahami jaringan saraf (*neural networks*)
dan penggunaannya dalam pengenalan gambar.

Meskipun hasilnya seperti ini, gambaran keseluruhannya menggembirakan.
Kami melihat kemajuan pesat pada tolok ukur yang sangat sulit, seperti
ImageNet. Kami juga melihat kemajuan pesat dalam solusi masalah dunia
nyata, seperti mengenali nomor jalan di StreetView. Tetapi sementara ini
menggembirakan, itu tidak cukup hanya dengan melihat peningkatan pada
tolok ukur, atau bahkan aplikasi dunia nyata. Ada fenomena mendasar yang
masih kita pahami dengan buruk, seperti adanya citra permusuhan. Ketika
masalah mendasar seperti itu masih ditemukan (apalagi dipecahkan),
terlalu dini untuk mengatakan bahwa kita hampir menyelesaikan masalah
pengenalan gambar. Pada saat yang sama masalah seperti itu merupakan
stimulus yang menarik untuk pekerjaan lebih lanjut.

### [Pendekatan lain untuk jaring saraf yang dalam](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#other_approaches_to_deep_neural_nets) 

Melalui buku ini, kami berkonsentrasi pada satu masalah: mengklasifikasi
angka MNIST. Ini adalah masalah besar yang memaksa kami untuk memahami
banyak ide kuat: penurunan gradien stokastik, backpropagation, jaring
konvolusional, regularisasi, dan banyak lagi. Tapi itu juga masalah
sempit. Jika Anda membaca literatur jaringan saraf, Anda akan menemukan
banyak ide yang belum kita diskusikan: *jaringan saraf (neural
networks)* berulang, mesin Boltzmann, model generatif, transfer
pembelajaran, pembelajaran penguatan, dan seterusnya, terus dan terus
pada  *ldots*

dan seterusnya \! jaringan saraf (*neural networks*) adalah bidang yang
luas. Namun, banyak ide penting adalah variasi dari ide yang telah kita
bahas, dan dapat dipahami dengan sedikit usaha. Pada bagian ini saya
memberikan sekilas tentang ini sebagai pemandangan yang belum terlihat.
Diskusi tidak terperinci, atau komprehensif - yang akan memperluas buku
ini. Sebaliknya, itu impresionistis, upaya untuk membangkitkan kekayaan
konseptual lapangan, dan untuk menghubungkan beberapa kekayaan itu
dengan apa yang telah kita lihat. Melalui bagian ini, saya akan
memberikan beberapa tautan ke sumber lain, sebagai makanan pembuka untuk
mempelajari lebih lanjut. Tentu saja, banyak dari tautan ini akan segera
digantikan, dan Anda mungkin ingin mencari literatur yang lebih baru.
Meskipun begitu, saya berharap banyak dari ide-ide yang mendasarinya
tetap menarik.

**jaringan saraf (*neural networks*) berulang (RNNs):** Di jaring umpan
maju kami telah menggunakan ada input tunggal yang sepenuhnya menentukan
aktivasi semua neuron melalui lapisan yang tersisa. Ini gambar yang
sangat statis: semua yang ada di jaringan diperbaiki, dengan kualitas
kristal yang beku. Tapi misalkan kita membiarkan elemen-elemen dalam
jaringan untuk terus berubah secara dinamis. Misalnya, perilaku neuron
tersembunyi mungkin tidak hanya ditentukan oleh aktivasi di lapisan
tersembunyi sebelumnya, tetapi juga oleh aktivasi pada waktu sebelumnya.
Memang, aktivasi neuron mungkin ditentukan sebagian oleh aktivasi
sendiri pada waktu sebelumnya. Tentu saja bukan itu yang terjadi di
jaringan feedforward. Atau mungkin aktivasi neuron tersembunyi dan
keluaran tidak akan ditentukan hanya oleh input saat ini ke jaringan,
tetapi juga oleh input sebelumnya.

jaringan saraf (*neural networks*) dengan jenis perilaku yang bervariasi
waktu ini dikenal sebagai *jaringan saraf (neural networks) berulang*
atau *RNN* . Ada banyak cara memformalkan secara matematis deskripsi
informal jaring berulang yang diberikan pada paragraf terakhir. Anda
bisa mendapatkan rasa dari beberapa model matematika ini dengan melirik
[artikel Wikipedia di
RNNs](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Recurrent_neural_network&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhT929t4Y3Ztc5dQPDw81FTHZ_4CA)
. Saat saya menulis, halaman itu mencantumkan tidak kurang dari 13 model
yang berbeda. Namun, selain rincian matematis, gagasan luasnya adalah
bahwa RNN adalah jaringan saraf (*neural networks*) di mana ada beberapa
gagasan tentang perubahan dinamis dari waktu ke waktu. Dan, tidak
mengherankan, mereka sangat berguna dalam menganalisis data atau proses
yang berubah seiring waktu. Data dan proses seperti itu muncul secara
alami dalam masalah seperti ucapan atau bahasa alami, misalnya.

Salah satu cara RNNs saat ini digunakan adalah untuk menghubungkan
jaringan saraf (*neural networks*) lebih dekat dengan cara berpikir
tradisional tentang algoritma, cara berpikir berdasarkan konsep seperti
mesin Turing dan bahasa pemrograman (konvensional). [Sebuah
makalah 2014](http://arxiv.org/abs/1410.4615) mengembangkan RNN yang
dapat mengambil sebagai input deskripsi karakter-per-karakter dari
program Python (sangat, sangat sederhana\!), Dan gunakan deskripsi itu
untuk memprediksi output. Secara informal, jaringan sedang belajar untuk
"memahami" program Python tertentu. [Makalah kedua, juga
dari 2014](http://arxiv.org/abs/1410.5401) , menggunakan RNNs sebagai
titik awal untuk mengembangkan apa yang mereka sebut mesin Turing saraf
(NTM). Ini adalah komputer universal yang seluruh strukturnya dapat
dilatih menggunakan gradient descent. Mereka melatih NTM mereka untuk
menyimpulkan algoritma untuk beberapa masalah sederhana, seperti
menyortir dan menyalin.

Seperti berdiri, ini adalah model mainan yang sangat sederhana. Belajar
untuk mengeksekusi cetak program Python (398345 + 42598) tidak membuat
jaringan menjadi juru bahasa Python yang lengkap\! Tidak jelas seberapa
jauh mungkin mendorong ide-ide itu. Meski begitu, hasilnya menarik.
Secara historis, jaringan saraf (*neural networks*) telah bekerja dengan
baik pada masalah pengenalan pola di mana pendekatan algoritmik
konvensional mengalami masalah. Begitu pula sebaliknya, pendekatan
algoritmik konvensional bagus dalam memecahkan masalah yang tidak begitu
bagus dalam jaring saraf. Tidak ada yang hari ini mengimplementasikan
server web atau program database menggunakan jaringan saraf\! Akan luar
biasa untuk mengembangkan model terpadu yang mengintegrasikan kekuatan
jaringan saraf (*neural networks*) dan pendekatan yang lebih tradisional
untuk algoritma. RNN dan gagasan yang terinspirasi oleh RNN dapat
membantu kita melakukan itu.

RNNs juga telah digunakan dalam beberapa tahun terakhir untuk menyerang
banyak masalah lainnya. Mereka sangat berguna dalam pengenalan ucapan.
Pendekatan berdasarkan RNNs, misalnya, telah [mengatur catatan untuk
keakuratan pengenalan fonem](http://arxiv.org/abs/1303.5778) . Mereka
juga telah digunakan untuk mengembangkan [model yang lebih baik dari
bahasa yang digunakan orang saat
berbicara](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.fit.vutbr.cz/~imikolov/rnnlm/thesis.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhij6nte4pyWl7aNVSKJ96C9yG84UQ)
. Model bahasa yang lebih baik membantu menyamarkan ucapan yang
sebaliknya terdengar sama. Model bahasa yang baik akan, misalnya,
memberi tahu kita bahwa "hingga tak terbatas dan lebih" jauh lebih
mungkin daripada "dua tak hingga dan", meskipun faktanya frasa terdengar
identik. RNNs telah digunakan untuk mengatur catatan baru untuk tolok
ukur bahasa tertentu.

Pekerjaan ini, kebetulan, merupakan bagian dari penggunaan yang lebih
luas dari jaring saraf dalam semua jenis, bukan hanya RNNs, dalam
pengenalan suara. Sebagai contoh, suatu pendekatan yang didasarkan pada
jaring yang dalam telah mencapai [hasil yang luar biasa pada pengenalan
ucapan terus menerus kosa kata yang
besar](http://arxiv.org/abs/1309.1501) . Dan sistem lain berdasarkan
jaring dalam telah digunakan di [sistem operasi Google
Android](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.wired.com/2013/02/android-neural-network/&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg-2T-guI7_sPhL7eWUlJUA1cjB7g)
(untuk pekerjaan teknis terkait, lihat [surat kabar Vincent
Vanhoucke 2012-2015](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://research.google.com/pubs/VincentVanhoucke.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhdL7vfiYh9yCm22mIy58b-LYeraA)
).

Saya sudah mengatakan sedikit tentang apa yang bisa dilakukan RNN,
tetapi tidak begitu banyak tentang cara kerjanya. Mungkin tidak akan
mengejutkan Anda untuk mengetahui bahwa banyak ide yang digunakan dalam
jaringan feedforward juga dapat digunakan di RNNs. Secara khusus, kita
dapat melatih RNN menggunakan modifikasi langsung ke gradient descent
dan backpropagation. Banyak ide lain yang digunakan dalam jaring
feedforward, mulai dari teknik regularisasi hingga konvolusi hingga
fungsi aktivasi dan biaya yang digunakan, juga berguna dalam jaring
berulang. Dan begitu banyak teknik yang kami kembangkan dalam buku ini
dapat diadaptasi untuk digunakan dengan RNNs.

**Unit memori jangka pendek (LSTM):** Salah satu tantangan yang
mempengaruhi RNN adalah bahwa model awal ternyata sangat sulit untuk
dilatih, lebih sulit daripada jaringan feedforward yang dalam. Alasannya
adalah masalah gradien tidak stabil yang dibahas pada
[Bab 5](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap5.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2rer3jc9YsTN2bK_2HJozK3sHrw)
. Ingatlah bahwa manifestasi biasa dari masalah ini adalah bahwa gradien
semakin kecil dan semakin kecil saat diperbanyak kembali melalui
lapisan. Ini membuat belajar di lapisan awal sangat lambat. Masalahnya
benar-benar semakin buruk di RNNs, karena gradien tidak hanya disebarkan
ke belakang melalui lapisan, mereka disebarkan ke belakang melalui
waktu. Jika jaringan berjalan untuk waktu yang lama, itu dapat membuat
gradien menjadi sangat tidak stabil dan sulit untuk dipelajari.
Untungnya, mungkin untuk memasukkan ide yang dikenal sebagai unit memori
jangka pendek (LSTM) ke dalam RNN. Unit diperkenalkan oleh [Hochreiter
dan Schmidhuber pada
tahun 1997](http://dx.doi.org/10.1162/neco.1997.9.8.1735) dengan tujuan
eksplisit membantu mengatasi masalah gradien yang tidak stabil. LSTM
membuat lebih mudah untuk mendapatkan hasil yang baik ketika melatih
RNN, dan banyak makalah baru-baru ini (termasuk banyak yang saya tautkan
di atas) memanfaatkan LSTM atau ide-ide terkait.

**Jaring kepercayaan mendalam, model generatif, dan mesin Boltzmann:**
Minat modern dalam *pembelajaran dalam (deep learning)* dimulai pada
2006, dengan makalah yang menjelaskan cara melatih jenis *jaringan saraf
(neural networks)* yang dikenal sebagai *jaringan keyakinan mendalam*
(DBN) \* \* Lihat [Algoritma pembelajaran cepat untuk keyakinan mendalam
jaring](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.cs.toronto.edu/~hinton/absps/fastnc.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhVHcagRStZKwXCTC5CptIQbiyxqQ)
, oleh Geoffrey Hinton, Simon Osindero, dan Yee-Whye Teh (2006), serta
pekerjaan terkait dalam [Mengurangi dimensi data dengan jaringan
saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.sciencemag.org/content/313/5786/504.short&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhj1n8y_ZGv1pQ-CUX4I3L-gjOrwqg)
, oleh Geoffrey Hinton dan Ruslan Salakhutdinov (2006). . DBN
berpengaruh selama beberapa tahun, tetapi sejak itu semakin berkurang
popularitasnya, sementara model seperti jaringan feedforward dan jaring
saraf berulang menjadi modis. Meskipun demikian, DBNs memiliki beberapa
properti yang membuatnya menarik.

Salah satu alasan DBN menarik adalah bahwa mereka adalah contoh dari apa
yang disebut *model generatif* . Di jaringan feedforward, kami
menentukan aktivasi input, dan mereka menentukan aktivasi neuron fitur
nanti di jaringan. Model generatif seperti DBN dapat digunakan dengan
cara yang serupa, tetapi juga memungkinkan untuk menentukan nilai dari
beberapa neuron fitur dan kemudian "menjalankan jaringan mundur",
menghasilkan nilai untuk aktivasi input. Lebih konkretnya, DBN yang
dilatih tentang gambar digit tulisan tangan dapat (berpotensi, dan
dengan hati-hati) juga digunakan untuk menghasilkan gambar yang tampak
seperti digit tulisan tangan. Dengan kata lain, DBN dalam beberapa hal
akan belajar menulis. Dalam hal ini, model generatif sangat mirip dengan
otak manusia: tidak hanya dapat membaca angka, tetapi juga dapat
menuliskannya. Dalam ungkapan Geoffrey Hinton yang berkesan, [untuk
mengenali bentuk, pertama-tama belajar menghasilkan
gambar](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.sciencedirect.com/science/article/pii/S0079612306650346&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhgj1iQMKYMXnHJ1-BH4vDEBPspUnw)
.

Alasan kedua DBN menarik adalah bahwa mereka dapat melakukan
pembelajaran tanpa pengawasan dan semi-diawasi. Misalnya, ketika dilatih
dengan data gambar, DBN dapat mempelajari fitur-fitur yang berguna untuk
memahami gambar lain, bahkan jika gambar pelatihan tidak diberi label.
Dan kemampuan untuk melakukan pembelajaran tanpa pengawasan sangat
menarik baik untuk alasan ilmiah mendasar, dan - jika dapat dibuat untuk
bekerja dengan cukup baik - untuk aplikasi praktis.

Dengan fitur-fitur yang menarik ini, mengapa DBN berkurang
popularitasnya sebagai model untuk *pembelajaran dalam (deep learning)*?
Sebagian alasannya adalah bahwa model seperti jaring feedforward dan
berulang telah mencapai banyak hasil yang spektakuler, seperti terobosan
mereka pada citra dan tolok ukur pengenalan suara. Tidak mengherankan
dan benar bahwa sekarang ada banyak perhatian yang dibayarkan kepada
model-model ini. Ada akibat wajar yang disayangkan. Pasar ide sering
kali berfungsi dalam mode pemenang-ambil-semua, dengan hampir semua
perhatian mengarah pada mode saat ini di area tertentu. Ini bisa menjadi
sangat sulit bagi orang untuk mengerjakan ide-ide yang tidak modern
untuk sementara waktu, bahkan ketika ide-ide itu jelas sangat menarik
untuk jangka panjang. Pendapat pribadi saya adalah bahwa DBN dan model
generatif lainnya kemungkinan pantas mendapat perhatian lebih dari yang
mereka terima saat ini. Dan saya tidak akan terkejut jika DBN atau model
terkait suatu hari melampaui model yang sedang populer. Untuk pengantar
DBN, lihat [ikhtisar
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.scholarpedia.org/article/Deep_belief_networks&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhbe9exniMSuHII_i-L5OSw3rmF5g)
. Saya juga menemukan [artikel
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.cs.toronto.edu/~hinton/absps/guideTR.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjL3YLqzIudZ258UBR1d4lERZqPDw)
bermanfaat. Ini bukan terutama tentang jaring kepercayaan mendalam,
tetapi juga mengandung banyak informasi berguna tentang mesin Boltzmann
terbatas, yang merupakan komponen kunci dari DBN.

**Gagasan lain:** Apa lagi yang terjadi dalam *jaringan saraf (neural
networks)* dan *pembelajaran dalam (deep learning)*? Nah, ada sejumlah
besar pekerjaan menarik lainnya. Bidang penelitian aktif termasuk
menggunakan jaringan saraf (*neural networks*) untuk melakukan
[pemrosesan bahasa
alami](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://machinelearning.org/archive/icml2008/papers/391.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiVZo4_IhvKbodaqRPOJ3VAZ0_9Fw)
(lihat [juga makalah tinjauan informatif
ini](http://arxiv.org/abs/1103.0398) ), [terjemahan
mesin](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/assets/MachineTranslation.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhhkvw1xC97H_-JLpRI_Skbn0EXBSA)
, dan mungkin aplikasi yang lebih mengejutkan seperti [informatika
musik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://yann.lecun.com/exdb/publis/pdf/humphrey-jiis-13.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh2DMuQlTSILL_bl7ldsLtZ6Z2fPw)
. Tentu saja ada banyak bidang lain juga. Dalam banyak kasus, setelah
membaca buku ini Anda harus dapat mulai mengikuti karya terbaru,
meskipun (tentu saja) Anda harus mengisi kekosongan dalam pengetahuan
latar belakang yang diduga.

Biarkan saya menyelesaikan bagian ini dengan menyebutkan kertas yang
sangat menyenangkan. Ini menggabungkan jaringan convolutional yang
mendalam dengan teknik yang dikenal sebagai penguatan pembelajaran untuk
belajar [bermain video game dengan
baik](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.cs.toronto.edu/~vmnih/docs/dqn.pdf&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjst26dxwBl_sbNTl_6meZlOJbtWA)
(lihat juga [tindak lanjut
ini](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://www.nature.com/nature/journal/v518/n7540/abs/nature14236.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg18yFgSsslQsskquQn_1z_gNsF8Q)
). Idenya adalah menggunakan jaringan konvolusional untuk
menyederhanakan data piksel dari layar game, mengubahnya menjadi
seperangkat fitur yang lebih sederhana, yang dapat digunakan untuk
memutuskan tindakan mana yang harus diambil: "ke kiri", "turun",
"tembak" ", dan seterusnya. Yang sangat menarik adalah bahwa satu
jaringan belajar memainkan tujuh video game klasik yang berbeda dengan
cukup baik, mengungguli ahli manusia pada tiga game. Sekarang, ini semua
kedengarannya seperti akrobat, dan tidak ada keraguan bahwa koran itu
dipasarkan dengan baik, dengan judul "Bermain Atari dengan pembelajaran
penguatan". Tapi melihat melewati permukaan gloss, pertimbangkan bahwa
sistem ini mengambil data piksel mentah - bahkan tidak tahu aturan
mainnya\! - dan dari data itu belajar untuk melakukan pengambilan
keputusan berkualitas tinggi di beberapa lingkungan yang sangat berbeda
dan sangat bermusuhan, masing-masing dengan seperangkat aturan yang
kompleks. Cukup rapi.

### [Tentang masa depan jaringan saraf](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/chap6.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhjgI0_uLTufnB8E11YqM1JH4XtuYQ#on_the_future_of_neural_networks) 

**Antarmuka pengguna yang didorong oleh niat:** Ada lelucon lama di mana
seorang profesor yang tidak sabar memberi tahu seorang siswa yang
bingung: "jangan dengarkan apa yang saya katakan; dengarkan apa yang
saya *maksudkan* ". Secara historis, komputer sering, seperti siswa yang
bingung, dalam kegelapan tentang apa yang pengguna maksudkan. Tapi ini
berubah. Saya masih ingat keterkejutan saya saat pertama kali salah
mengeja kueri penelusuran Google, hanya untuk meminta Google mengatakan,
"Maksud Anda \[kueri terkoreksi\]?" dan untuk menawarkan hasil pencarian
yang sesuai. CEO Google Larry Page [pernah menggambarkan mesin pencari
yang sempurna sebagai memahami dengan tepat apa artinya \[pertanyaan
Anda\] dan mengembalikan apa yang Anda
inginkan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://googleblog.blogspot.ca/2012/08/building-search-engine-of-future-one.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi7Np8d4uumc8IgW3oedvcnM1hwZA)
.

Ini adalah visi *antarmuka pengguna yang digerakkan oleh niat* . Dalam
visi ini, alih-alih menanggapi pertanyaan literal pengguna, pencarian
akan menggunakan pembelajaran mesin untuk mengambil input pengguna yang
tidak jelas, membedakan dengan tepat apa yang dimaksud, dan mengambil
tindakan berdasarkan wawasan tersebut.

Gagasan antarmuka yang digerakkan oleh niat dapat diterapkan jauh lebih
luas daripada pencarian. Selama beberapa dekade ke depan, ribuan
perusahaan akan membangun produk yang menggunakan pembelajaran mesin
untuk membuat antarmuka pengguna yang dapat mentolerir ketidaktepatan,
sementara menentukan dan bertindak atas niat sebenarnya pengguna. Kita
sudah melihat contoh awal dari antarmuka yang didorong oleh niat seperti
itu: Apple Siri; Wolfram Alpha; Watson IBM; sistem yang dapat [membubuhi
keterangan foto dan video](http://arxiv.org/abs/1411.4555) ; dan banyak
lagi.

Sebagian besar produk ini akan gagal. Desain antarmuka pengguna yang
terinspirasi sulit, dan saya berharap banyak perusahaan akan mengambil
teknologi pembelajaran mesin yang kuat dan menggunakannya untuk
membangun antarmuka pengguna yang hambar. Pembelajaran mesin terbaik di
dunia tidak akan membantu jika konsep antarmuka pengguna Anda bau.
Tetapi akan ada residu produk yang berhasil. Seiring waktu itu akan
menyebabkan perubahan besar dalam cara kita berhubungan dengan komputer.
Belum lama ini - katakanlah, 2005 - pengguna menerima begitu saja bahwa
mereka membutuhkan ketepatan dalam sebagian besar interaksi dengan
komputer. Memang, melek komputer sebagian besar berarti
menginternalisasi gagasan bahwa komputer sangat harfiah; semi-colon
tunggal yang salah tempat dapat sepenuhnya mengubah sifat interaksi
dengan komputer. Tetapi selama beberapa dekade ke depan saya berharap
kita akan mengembangkan banyak antarmuka pengguna yang digerakkan oleh
niat, dan itu akan secara dramatis mengubah apa yang kita harapkan
ketika berinteraksi dengan komputer.

**Pembelajaran mesin, ilmu data, dan lingkaran inovasi yang luhur:**
Tentu saja, pembelajaran mesin tidak hanya digunakan untuk membangun
antarmuka yang digerakkan oleh niat. Aplikasi penting lainnya adalah
dalam ilmu data, di mana pembelajaran mesin digunakan untuk menemukan
"diketahui tidak dikenal" yang tersembunyi dalam data. Ini sudah
merupakan area yang modis, dan banyak yang telah ditulis tentang hal
itu, jadi saya tidak akan banyak bicara. Tetapi saya ingin menyebutkan
satu konsekuensi dari mode ini yang tidak begitu sering dikomentari:
dalam jangka panjang mungkin saja terobosan terbesar dalam pembelajaran
mesin tidak akan menjadi terobosan konseptual tunggal. Sebaliknya,
terobosan terbesar adalah penelitian pembelajaran mesin menjadi
menguntungkan, melalui aplikasi ke ilmu data dan bidang lainnya. Jika
sebuah perusahaan dapat menginvestasikan 1 dolar dalam penelitian
pembelajaran mesin dan mendapatkan 1 dolar dan 10 sen kembali dengan
cepat, maka banyak uang akan berakhir dalam penelitian pembelajaran
mesin. Dengan kata lain, pembelajaran mesin adalah mesin yang mendorong
penciptaan beberapa pasar baru utama dan bidang pertumbuhan dalam
teknologi. Hasilnya akan menjadi tim besar orang-orang dengan keahlian
subjek yang mendalam, dan dengan akses ke sumber daya yang luar biasa.
Itu akan mendorong pembelajaran mesin lebih jauh ke depan, menciptakan
lebih banyak pasar dan peluang, lingkaran inovasi yang baik.

**Peran jaringan saraf (*neural networks*) dan *pembelajaran dalam (deep
learning)*:** Saya telah berbicara secara luas tentang pembelajaran
mesin sebagai pencipta peluang baru untuk teknologi. Apa yang akan
menjadi peran spesifik dari jaringan saraf (*neural networks*) dan
*pembelajaran dalam (deep learning)* dalam semua ini?

Untuk menjawab pertanyaan itu, ada baiknya melihat sejarah. Kembali pada
1980-an ada banyak kegembiraan dan optimisme tentang jaringan saraf,
terutama setelah backpropagation menjadi dikenal luas. Kegembiraan itu
memudar, dan pada 1990-an tongkat belajar mesin beralih ke teknik lain,
seperti mesin vektor dukungan. Hari ini, *jaringan saraf (neural
networks)* sekali lagi naik tinggi, mengatur segala macam catatan,
mengalahkan semua pendatang pada banyak masalah. Tetapi siapa yang
mengatakan bahwa besok beberapa pendekatan baru tidak akan dikembangkan
yang menyapu jaringan saraf (*neural networks*) lagi? Atau mungkin
kemajuan dengan jaringan saraf (*neural networks*) akan mandek, dan
tidak ada yang segera muncul untuk menggantikannya?

Untuk alasan ini, jauh lebih mudah untuk berpikir secara luas tentang
masa depan pembelajaran mesin daripada tentang *jaringan saraf (neural
networks)* secara khusus. Sebagian dari masalahnya adalah bahwa kita
memahami jaringan saraf (*neural networks*) sangat buruk. Mengapa
jaringan saraf (*neural networks*) bisa menggeneralisasi dengan sangat
baik? Bagaimana mereka menghindari overfitting sebaik mereka, mengingat
banyaknya parameter yang mereka pelajari? Mengapa penurunan gradien
stokastik bekerja sebaik itu? Seberapa baik kinerja *jaringan saraf
(neural networks)* saat set data ditingkatkan? Sebagai contoh, jika
ImageNet diperluas dengan faktor 10

, akankah kinerja jaringan saraf (*neural networks*) meningkat lebih
atau kurang dari teknik pembelajaran mesin lainnya? Ini semua adalah
pertanyaan sederhana dan mendasar. Dan, saat ini, kami memahami jawaban
atas pertanyaan-pertanyaan ini dengan sangat buruk. Sementara itu
masalahnya, sulit untuk mengatakan apa peran *jaringan saraf (neural
networks)* akan bermain di masa depan pembelajaran mesin.

Saya akan membuat satu prediksi: Saya percaya *pembelajaran dalam (deep
learning)* ada di sini untuk tinggal. Kemampuan untuk mempelajari
hierarki konsep, membangun banyak lapisan abstraksi, tampaknya sangat
mendasar untuk memahami dunia. Ini tidak berarti pembelajar dalam masa
depan tidak akan secara radikal berbeda dari hari ini. Kita bisa melihat
perubahan besar dalam unit penyusun yang digunakan, dalam arsitektur,
atau dalam algoritma pembelajaran. Perubahan itu mungkin cukup dramatis
sehingga kita tidak lagi memikirkan sistem yang dihasilkan sebagai
jaringan saraf. Tetapi mereka masih melakukan *pembelajaran dalam (deep
learning)*.

**Akankah jaringan saraf (*neural networks*) dan *pembelajaran dalam
(deep learning)* segera mengarah pada kecerdasan buatan?** Dalam buku
ini kami fokus menggunakan jaring saraf untuk melakukan tugas tertentu,
seperti mengklasifikasikan gambar. Mari kita memperluas ambisi kita, dan
bertanya: bagaimana dengan komputer berfikir umum? Dapatkah *jaringan
saraf (neural networks)* dan *pembelajaran dalam (deep learning)*
membantu kita memecahkan masalah kecerdasan buatan (umum) (AI)? Dan,
jika demikian, mengingat kemajuan pesat baru-baru ini dalam
*pembelajaran dalam (deep learning)*, dapatkah kita mengharapkan AI umum
dalam waktu dekat?

Mengatasi pertanyaan-pertanyaan ini secara komprehensif akan membutuhkan
buku yang terpisah. Sebagai gantinya, izinkan saya menawarkan satu
pengamatan. Ini didasarkan pada ide yang dikenal sebagai [hukum
Conway](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Conway%2527s_law&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiBRINECFrlBBNl--W4ZcZPre2l4w)
:

Setiap organisasi yang merancang sistem ... pasti akan menghasilkan
desain yang strukturnya merupakan salinan dari struktur komunikasi
organisasi.

Jadi, misalnya, hukum Conway menyarankan bahwa desain pesawat Boeing 747
akan mencerminkan struktur organisasi Boeing dan kontraktornya yang
diperluas pada saat 747 dirancang. Atau untuk contoh sederhana dan
spesifik, pertimbangkan sebuah perusahaan yang membangun aplikasi
perangkat lunak yang kompleks. Jika dasbor aplikasi seharusnya
diintegrasikan dengan beberapa algoritma pembelajaran mesin, orang yang
membangun dasbor sebaiknya berbicara dengan ahli pembelajaran mesin
perusahaan. Hukum Conway hanyalah observasi, tertulis besar.

Setelah pertama kali mendengar hukum Conway, banyak orang yang menjawab,
"Yah, bukankah itu dangkal dan jelas?" atau "Apakah itu tidak salah?"
Mari saya mulai dengan keberatan bahwa itu salah. Sebagai contoh
keberatan ini, pertimbangkan pertanyaan: di mana departemen akuntansi
Boeing muncul dalam desain 747? Bagaimana dengan departemen kebersihan
mereka? Katering internal mereka? Dan jawabannya adalah bahwa
bagian-bagian organisasi ini mungkin tidak muncul secara eksplisit di
mana pun di 747. Jadi kita harus memahami hukum Conway sebagai merujuk
hanya ke bagian-bagian organisasi yang secara eksplisit berkaitan dengan
desain dan rekayasa.

Bagaimana dengan keberatan lainnya, bahwa hukum Conway itu dangkal dan
jelas? Ini mungkin benar, tapi saya rasa tidak, karena organisasi
terlalu sering bertindak dengan mengabaikan hukum Conway. Tim yang
membangun produk baru sering dibengkak dengan karyawan lama atau,
sebaliknya, kekurangan seseorang dengan keahlian penting. Pikirkan semua
produk yang memiliki fitur rumit yang tidak berguna. Atau pikirkan semua
produk yang memiliki kekurangan utama yang jelas - misalnya, antarmuka
pengguna yang buruk. Masalah di kedua kelas sering disebabkan oleh
ketidaksesuaian antara tim yang diperlukan untuk menghasilkan produk
yang baik, dan tim yang benar-benar berkumpul. Hukum Conway mungkin
jelas, tetapi itu tidak berarti orang tidak secara rutin mengabaikannya.

Hukum Conway berlaku untuk desain dan rekayasa sistem di mana kita mulai
dengan pemahaman yang cukup baik tentang bagian-bagian penyusun yang
mungkin, dan bagaimana membangunnya. Itu tidak dapat diterapkan secara
langsung pada pengembangan kecerdasan buatan, karena AI belum (belum)
masalah seperti itu: kita tidak tahu apa bagian-bagian penyusunnya.
Memang, kami bahkan tidak yakin pertanyaan dasar apa yang akan diajukan.
Dengan kata lain, pada titik ini AI lebih merupakan masalah sains
daripada rekayasa. Bayangkan mulai desain 747 tanpa mengetahui tentang
mesin jet atau prinsip aerodinamika. Anda tidak akan tahu ahli seperti
apa yang dipekerjakan di organisasi Anda. Seperti yang dikatakan Wernher
von Braun, "penelitian dasar adalah apa yang saya lakukan ketika saya
tidak tahu apa yang saya lakukan". Apakah ada versi hukum Conway yang
berlaku untuk masalah yang lebih bersifat sains daripada rekayasa?

Untuk mendapatkan wawasan tentang pertanyaan ini, pertimbangkan sejarah
kedokteran. Pada hari-hari awal, obat-obatan adalah domain para praktisi
seperti Galen dan Hippocrates, yang mempelajari seluruh tubuh. Tetapi
seiring bertambahnya pengetahuan kami, orang-orang dipaksa untuk
berspesialisasi. Kami menemukan banyak ide baru yang dalam \* \*
Permintaan maaf saya karena kelebihan "dalam". Saya tidak akan
mendefinisikan "ide-ide yang mendalam" dengan tepat, tetapi secara
longgar saya maksud jenis ide yang merupakan dasar untuk bidang
penyelidikan yang kaya. Algoritma backpropagation dan teori kuman
penyakit adalah contoh yang baik. : pikirkan hal-hal seperti teori kuman
penyakit, misalnya, atau pemahaman tentang cara kerja antibodi, atau
pemahaman bahwa jantung, paru-paru, pembuluh darah dan arteri membentuk
sistem kardiovaskular yang lengkap. Wawasan mendalam seperti itu
membentuk dasar bagi subbidang seperti epidemiologi, imunologi, dan
kelompok bidang yang saling terkait di sekitar sistem kardiovaskular.
Dan struktur pengetahuan kita telah membentuk struktur sosial
kedokteran. Ini sangat mencolok dalam kasus imunologi: menyadari sistem
kekebalan ada dan merupakan sistem yang layak dipelajari adalah wawasan
yang sangat non-sepele. Jadi kita memiliki seluruh bidang kedokteran -
dengan spesialis, konferensi, bahkan hadiah, dan sebagainya -
diorganisir di sekitar sesuatu yang tidak hanya tidak terlihat, itu bisa
dibilang bukan hal yang berbeda sama sekali.

Ini adalah pola umum yang telah diulang dalam banyak ilmu yang sudah
mapan: tidak hanya kedokteran, tetapi fisika, matematika, kimia, dan
lain-lain. Ladang-ladang mulai monolitik, dengan hanya beberapa ide yang
mendalam. Pakar awal dapat menguasai semua gagasan itu. Tetapi seiring
berjalannya waktu, karakter monolitik berubah. Kami menemukan banyak ide
baru yang mendalam, terlalu banyak untuk dikuasai oleh satu orang.
Akibatnya, struktur sosial bidang ini mengatur kembali dan membagi
ide-ide itu. Alih-alih monolit, kami memiliki bidang dalam bidang dalam
bidang, struktur sosial yang kompleks, rekursif, dan referensial diri,
yang organisasinya mencerminkan hubungan antara wawasan terdalam kami.
*Dan struktur pengetahuan kita membentuk organisasi sosial sains.*
*Tetapi bentuk sosial itu pada gilirannya membatasi dan membantu
menentukan apa yang dapat kita temukan.* Ini adalah analog ilmiah hukum
Conway.

Jadi apa hubungannya dengan *pembelajaran dalam (deep learning)* atau
AI?

Nah, sejak awal AI ada argumen tentang hal itu, di satu sisi, "Hei, itu
tidak akan terlalu sulit, kita punya \[senjata super-spesial\] di pihak
kita", balas oleh " \[senjata super spesial\] tidak akan cukup ".
*Pembelajaran dalam (deep learning)* adalah senjata super spesial
terbaru yang saya dengar pernah digunakan dalam argumen seperti itu \*
\* Menariknya, seringkali tidak oleh para pakar terkemuka dalam
*pembelajaran dalam (deep learning)*, yang telah cukup terkendali.
Lihat, misalnya, [pos yang
dipikirkan](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=https://www.facebook.com/yann.lecun/posts/10152348155137143&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhiN9jav6ca8qGXIV2CpOyv_Ohv3rA)
oleh Yann LeCun ini. Ini adalah perbedaan dari banyak inkarnasi argumen
sebelumnya. ; versi sebelumnya dari argumen tersebut menggunakan logika,
atau Prolog, atau sistem pakar, atau teknik apa pun yang paling kuat
saat itu. Masalah dengan argumen seperti itu adalah bahwa mereka tidak
memberi Anda cara yang baik untuk mengatakan seberapa kuat setiap
senjata super-kandidat yang diberikan. Tentu saja, kami baru saja
menghabiskan satu bab meninjau bukti bahwa *pembelajaran dalam (deep
learning)* dapat memecahkan masalah yang sangat menantang. Ini tentu
terlihat sangat menarik dan menjanjikan. Tapi itu juga berlaku untuk
sistem seperti Prolog atau
[Eurisko](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://en.wikipedia.org/wiki/Eurisko&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhg4bQKJNwb89VKkm32T__UzOVN9IQ)
atau sistem pakar di zaman mereka. Dan fakta bahwa serangkaian ide
terlihat sangat menjanjikan tidak berarti banyak. Bagaimana kita dapat
mengetahui jika *pembelajaran dalam (deep learning)* benar-benar berbeda
dari ide-ide sebelumnya? Apakah ada cara untuk mengukur seberapa kuat
dan menjanjikan seperangkat ide? Hukum Conway menunjukkan bahwa sebagai
metrik proksi yang kasar dan heuristik, kita dapat mengevaluasi
kompleksitas struktur sosial yang terkait dengan ide-ide itu.

Jadi, ada dua pertanyaan untuk diajukan. Pertama, seberapa kuat
seperangkat ide yang terkait dengan *pembelajaran dalam (deep
learning)*, menurut metrik kompleksitas sosial ini? Kedua, seberapa kuat
teori yang akan kita butuhkan, untuk dapat membangun kecerdasan buatan
umum?

Adapun pertanyaan pertama: ketika kita melihat *pembelajaran dalam (deep
learning)* hari ini, itu adalah bidang yang menarik dan cepat tetapi
juga relatif monolitik. Ada beberapa ide mendalam, dan beberapa
konferensi utama, dengan tumpang tindih substansial antara beberapa
konferensi. Dan ada kertas setelah kertas memanfaatkan set ide dasar
yang sama: menggunakan keturunan gradien stokastik (atau variasi dekat)
untuk mengoptimalkan fungsi biaya. Fantastis, ide-ide itu begitu sukses.
Tetapi apa yang belum kita lihat adalah banyak subbidang yang berkembang
dengan baik, masing-masing mengeksplorasi set ide-ide mereka sendiri,
mendorong *pembelajaran dalam (deep learning)* ke berbagai arah. Jadi,
menurut metrik kompleksitas sosial, *pembelajaran dalam (deep learning)*
adalah, jika Anda akan memaafkan permainan kata-kata, masih bidang yang
agak dangkal. Masih mungkin bagi satu orang untuk menguasai sebagian
besar gagasan terdalam di bidangnya.

Pada pertanyaan kedua: seberapa kompleks dan sekuat ide dibutuhkan untuk
mendapatkan AI? Tentu saja, jawaban untuk pertanyaan ini adalah: tidak
ada yang tahu pasti. Namun dalam
[lampiran](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://neuralnetworksanddeeplearning.com/sai.html&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhi_r2W6B006rb7gK3F4bzy6prrdaQ)
saya memeriksa beberapa bukti yang ada pada pertanyaan ini. Saya
menyimpulkan bahwa, bahkan dengan optimis, akan dibutuhkan banyak,
banyak ide mendalam untuk membangun AI. Dan hukum Conway menyarankan
bahwa untuk sampai ke titik seperti itu kita tentu akan melihat
munculnya banyak disiplin ilmu yang saling terkait, dengan struktur yang
kompleks dan mengejutkan yang mencerminkan struktur dalam wawasan
terdalam kita. Kami belum melihat struktur sosial yang kaya ini dalam
penggunaan jaringan saraf (*neural networks*) dan *pembelajaran dalam
(deep learning)*. Jadi, saya percaya bahwa kita beberapa dekade
(setidaknya) dari menggunakan *pembelajaran dalam (deep learning)* untuk
mengembangkan AI umum.

Saya telah pergi ke banyak masalah untuk membangun argumen yang
tentatif, mungkin tampak agak jelas, dan yang memiliki kesimpulan yang
tidak terbatas. Tidak diragukan lagi ini akan membuat frustasi
orang-orang yang menginginkan kepastian. Membaca di internet, saya
melihat banyak orang yang dengan keras menyatakan pendapat yang sangat
pasti, sangat kuat tentang AI, seringkali berdasarkan alasan yang lemah
dan bukti yang tidak ada. Pendapat saya adalah ini: masih terlalu dini
untuk mengatakan. Seperti lelucon lama, jika Anda bertanya kepada
seorang ilmuwan seberapa jauh beberapa penemuan dan mereka mengatakan
"10 tahun" (atau lebih), yang mereka maksud adalah "Saya tidak tahu".
AI, seperti fusi terkontrol dan beberapa teknologi lainnya, telah 10
tahun lagi untuk 60 tahun lebih. Di sisi lain, apa yang benar-benar kita
miliki dalam *pembelajaran dalam (deep learning)* adalah teknik yang
kuat yang batasnya belum ditemukan, dan banyak masalah mendasar terbuka
lebar. Itu peluang kreatif yang mengasyikkan.

Dalam karya akademis, silakan kutip buku ini sebagai: Michael A.
Nielsen, "Neural Networks and Deep Learning", Determination Press,
2015  
  
Karya ini dilisensikan di bawah [Lisensi Creative Commons
Attribution-NonCommercial 3.0
Unported](https://translate.googleusercontent.com/translate_c?depth=1&rurl=translate.google.com&sl=en&sp=nmt4&tl=id&u=http://creativecommons.org/licenses/by-nc/3.0/deed.en_GB&xid=17259,15700022,15700186,15700191,15700256,15700259,15700262,15700265,15700271,15700283&usg=ALkJrhh6tByBQCmRzRA1xiUcnuJcGw7WLw)
. Ini artinya Anda bebas menyalin, membagikan, dan membuat buku ini,
tetapi tidak untuk menjualnya. Jika Anda tertarik menggunakan komersial,
silakan [hubungi saya](mailto:mn@michaelnielsen.org) . Pembaruan
terakhir: Sel 11 Jun 16:58:53 2019  
  
  
![Lisensi Creative Commons](media/image33.png)

![https://www.gstatic.com/images/branding/googlelogo/1x/googlelogo\_color\_48x16dp.png](media/image109.png)

**Original English text:**

AI, like controlled fusion and a few other technologies, has been 10
years away for 60 plus years.

![http://www.google.com/images/zippy\_plus\_sm.gif](media/image110.gif)<span class="underline">Contribute
a better translation</span>

## Lampiran: Apakah ada algoritma *sederhana* untuk intelijen?

Dalam buku ini, kami telah fokus pada mur dan baut dari jaringan saraf:
bagaimana mereka bekerja, dan bagaimana mereka dapat digunakan untuk
memecahkan masalah pengenalan pola. Ini adalah materi dengan banyak
aplikasi praktis langsung. Tapi, tentu saja, satu alasan untuk tertarik
pada jaring saraf adalah harapan bahwa suatu hari mereka akan jauh
melampaui masalah pengenalan pola dasar seperti itu. Mungkin mereka,
atau pendekatan lain yang didasarkan pada komputer digital, pada
akhirnya akan digunakan untuk membangun mesin berpikir, mesin yang cocok
atau melampaui kecerdasan manusia? Gagasan ini jauh melebihi materi yang
dibahas dalam buku ini - atau apa yang diketahui oleh setiap orang di
dunia. Tapi menyenangkan untuk berspekulasi.

Ada banyak perdebatan tentang apakah mungkin bagi komputer untuk
menyamai kecerdasan manusia. Saya tidak akan terlibat dengan pertanyaan
itu. Meskipun ada perselisihan yang sedang berlangsung, saya percaya itu
bukan keraguan serius bahwa komputer cerdas mungkin - meskipun mungkin
sangat rumit, dan mungkin jauh melampaui teknologi saat ini - dan
penentang saat ini suatu hari kelihatannya seperti kaum vitalis.

Sebaliknya, pertanyaan yang saya jelajahi di sini adalah apakah ada
seperangkat prinsip sederhana yang dapat digunakan untuk menjelaskan
kecerdasan? Khususnya, dan yang lebih konkret, apakah ada algoritma
sederhana untuk kecerdasan?

Gagasan bahwa ada algoritma yang benar-benar sederhana untuk kecerdasan
adalah ide yang berani. Mungkin kedengarannya terlalu optimis untuk
menjadi kenyataan. Banyak orang memiliki perasaan intuisi yang kuat
bahwa kecerdasan memiliki kompleksitas yang tidak dapat direduksi.
Mereka sangat terkesan dengan variasi yang luar biasa dan fleksibilitas
pemikiran manusia sehingga mereka menyimpulkan bahwa algoritma sederhana
untuk kecerdasan pasti tidak mungkin. Terlepas dari intuisi ini, saya
pikir tidak bijaksana untuk segera menghakimi. Sejarah sains dipenuhi
dengan contoh-contoh di mana sebuah fenomena awalnya tampak sangat
kompleks, tetapi kemudian dijelaskan oleh beberapa gagasan sederhana
namun kuat.

Pertimbangkan, misalnya, hari-hari awal astronomi. Manusia telah
mengetahui sejak zaman kuno bahwa ada sejumlah benda di langit:
matahari, bulan, planet-planet, komet, dan bintang-bintang. Objek-objek
ini berperilaku dengan cara yang sangat berbeda - bintang bergerak
dengan cara yang megah dan teratur melintasi langit, misalnya, sementara
komet muncul seolah-olah entah dari mana, melesat melintasi langit, dan
kemudian menghilang. Pada abad ke-16 hanya optimis bodoh yang bisa
membayangkan bahwa semua gerakan benda-benda ini dapat dijelaskan oleh
seperangkat prinsip sederhana. Tetapi pada abad ke-17 Newton merumuskan
teorinya tentang gravitasi universal, yang tidak hanya menjelaskan semua
gerakan ini, tetapi juga menjelaskan fenomena terestrial seperti pasang
surut dan perilaku proyektil yang terikat Bumi. Optimis bodoh abad ke-16
tampaknya dalam retrospeksi seperti pesimis, meminta terlalu sedikit.

Tentu saja, sains mengandung lebih banyak contoh seperti itu.
Pertimbangkan segudang zat kimia yang membentuk dunia kita, yang begitu
indah dijelaskan oleh tabel periodik Mendeleev, yang, pada gilirannya,
dijelaskan oleh beberapa aturan sederhana yang dapat diperoleh dari
mekanika kuantum. Atau teka-teki bagaimana ada begitu banyak kerumitan
dan keragaman di dunia biologis, yang asalnya ternyata terletak pada
prinsip evolusi melalui seleksi alam. Contoh-contoh ini dan banyak
lainnya menunjukkan bahwa tidak bijaksana untuk mengesampingkan
penjelasan sederhana tentang kecerdasan hanya dengan alasan bahwa apa
yang dilakukan otak kita - yang saat ini merupakan contoh terbaik
kecerdasan - tampaknya sangat rumit \* \* Melalui lampiran ini saya
berasumsi bahwa agar komputer dianggap cerdas, kemampuannya harus sesuai
atau melebihi kemampuan berpikir manusia. Jadi saya akan menjawab
pertanyaan "Apakah ada algoritma sederhana untuk kecerdasan?" sebagai
ekuivalen dengan "Apakah ada algoritma sederhana yang dapat\` berpikir
'di sepanjang garis yang pada dasarnya sama dengan otak manusia? " Perlu
dicatat, bagaimanapun, bahwa mungkin ada bentuk-bentuk kecerdasan yang
tidak termasuk pemikiran manusia, namun tetap melampauinya dengan cara
yang menarik ..

Sebaliknya, dan terlepas dari contoh-contoh optimistis ini, secara logis
juga dimungkinkan bahwa intelijen hanya dapat dijelaskan oleh sejumlah
besar mekanisme yang berbeda secara fundamental. Dalam kasus otak kita,
banyak mekanisme itu mungkin telah berevolusi sebagai respons terhadap
berbagai tekanan seleksi dalam sejarah evolusi spesies kita. Jika sudut
pandang ini benar, maka kecerdasan melibatkan kompleksitas yang tidak
dapat direduksi, dan tidak ada algoritma sederhana untuk kecerdasan yang
mungkin.

Manakah dari dua sudut pandang ini yang benar?

Untuk mendapatkan wawasan tentang pertanyaan ini, mari kita ajukan
pertanyaan yang berhubungan erat, yaitu apakah ada penjelasan sederhana
tentang cara kerja otak manusia. Secara khusus, mari kita lihat beberapa
cara untuk mengukur kompleksitas otak. Pendekatan pertama kami adalah
pandangan otak dari connectomics. Ini semua tentang kabel mentah: berapa
banyak neuron yang ada di otak, berapa banyak sel glial, dan berapa
banyak koneksi yang ada di antara neuron. Anda mungkin pernah mendengar
angka-angka sebelumnya - otak berisi urutan 100 miliar neuron, 100
miliar sel glial, dan 100 triliun koneksi antar neuron. Angka-angka itu
mengejutkan. Mereka juga mengintimidasi. Jika kita perlu memahami detail
semua koneksi itu (belum lagi neuron dan sel glial) untuk memahami cara
kerja otak, maka kita tentu tidak akan berakhir dengan algoritma
sederhana untuk kecerdasan.

Ada sudut pandang kedua, lebih optimis, pandangan otak dari biologi
molekuler. Idenya adalah untuk menanyakan berapa banyak informasi
genetik yang diperlukan untuk menggambarkan arsitektur otak. Untuk
menangani pertanyaan ini, kita akan mulai dengan mempertimbangkan
perbedaan genetik antara manusia dan simpanse. Anda mungkin pernah
mendengar suara menggigit bahwa "manusia adalah 98 persen simpanse".
Ungkapan ini terkadang bervariasi - variasi populer juga memberikan
angka 95 atau 99 persen. Variasi terjadi karena jumlah awalnya
diperkirakan dengan membandingkan sampel genom manusia dan simpanse,
bukan seluruh genom. Namun, pada 2007 seluruh genom simpanse diurutkan
(lihat juga di sini), dan kita sekarang tahu bahwa DNA manusia dan
simpanse berbeda pada sekitar 125 juta pasangan basa DNA. Itu dari total
sekitar 3 miliar pasangan basa DNA di setiap genom. Jadi tidak benar
untuk mengatakan bahwa manusia adalah 98 persen simpanse - kita lebih
seperti 96 persen simpanse.

Berapa banyak informasi dalam 125 juta pasangan basa itu? Setiap
pasangan basa dapat dilabeli dengan satu dari empat kemungkinan -
"huruf" dari kode genetik, basis adenin, sitosin, guanin, dan timin.
Jadi setiap pasangan basa dapat dideskripsikan menggunakan dua bit
informasi - cukup informasi untuk menentukan satu dari empat label. Jadi
125 juta pasangan basa setara dengan 250 juta bit informasi. Itulah
perbedaan genetik antara manusia dan simpanse\!

Tentu saja, 250 juta bit itu bertanggung jawab atas semua perbedaan
genetik antara manusia dan simpanse. Kami hanya tertarik pada perbedaan
yang terkait dengan otak. Sayangnya, tidak ada yang tahu fraksi apa dari
total perbedaan genetik yang diperlukan untuk menjelaskan perbedaan
antara otak. Tetapi mari kita asumsikan demi argumen bahwa sekitar
setengah dari 250 juta bit bertanggung jawab atas perbedaan otak. Itu
total 125 juta bit.

125 juta bit adalah jumlah yang sangat besar. Mari kita memahami
seberapa besar itu dengan menerjemahkannya ke dalam istilah yang lebih
manusiawi. Secara khusus, berapa jumlah yang setara dengan teks bahasa
Inggris? Ternyata isi informasi teks bahasa Inggris adalah sekitar 1 bit
per huruf. Kedengarannya rendah - setelah semua, alfabet memiliki 26
huruf - tetapi ada sejumlah besar redundansi dalam teks bahasa Inggris.
Tentu saja, Anda mungkin berpendapat bahwa genom kita juga berlebihan,
jadi dua bit per pasangan basa terlalu tinggi. Tetapi kita akan
mengabaikan itu, karena paling buruk itu berarti kita melebih-lebihkan
kompleksitas genetik otak kita. Dengan asumsi-asumsi ini, kita melihat
bahwa perbedaan genetik antara otak kita dan otak simpanse setara dengan
sekitar 125 juta huruf, atau sekitar 25 juta kata bahasa Inggris. Itu
sekitar 30 kali lebih banyak dari King James Bible.

Itu banyak informasi. Tapi itu tidak terlalu besar. Ini pada skala
manusia. Mungkin tidak ada satu manusia pun yang dapat memahami semua
yang tertulis dalam kode itu, tetapi sekelompok orang mungkin dapat
memahaminya secara kolektif, melalui spesialisasi yang sesuai. Dan
meskipun banyak informasi, sangat kecil jika dibandingkan dengan
informasi yang diperlukan untuk menggambarkan 100 miliar neuron, 100
miliar sel glial, dan 100 triliun koneksi di otak kita. Bahkan jika kita
menggunakan deskripsi kasar dan sederhana - misalnya, 10 angka floating
point untuk menandai setiap koneksi - yang membutuhkan sekitar 70
kuadriliun bit. Itu berarti deskripsi genetik adalah faktor sekitar
setengah miliar lebih kompleks daripada penghubung penuh untuk otak
manusia.

Apa yang kita pelajari dari hal ini adalah bahwa genom kita tidak
mungkin mengandung deskripsi terperinci dari semua koneksi saraf kita.
Sebaliknya, itu harus menentukan hanya arsitektur luas dan
prinsip-prinsip dasar yang mendasari otak. Tetapi arsitektur dan
prinsip-prinsip itu tampaknya cukup untuk menjamin bahwa kita manusia
akan tumbuh menjadi cerdas. Tentu saja, ada peringatan - anak-anak yang
sedang tumbuh membutuhkan lingkungan yang sehat dan menstimulasi serta
nutrisi yang baik untuk mencapai potensi intelektual mereka. Tetapi
asalkan kita tumbuh di lingkungan yang masuk akal, manusia yang sehat
akan memiliki kecerdasan yang luar biasa. Dalam beberapa hal, informasi
dalam gen kita mengandung esensi dari bagaimana kita berpikir. Dan lebih
jauh lagi, prinsip-prinsip yang terkandung dalam informasi genetik itu
nampaknya berada dalam kemampuan kita untuk memahami secara kolektif.

Semua angka di atas adalah perkiraan yang sangat kasar. Mungkin saja 125
juta bit adalah perkiraan terlalu tinggi, bahwa ada beberapa prinsip
inti yang jauh lebih kompak yang mendasari pemikiran manusia. Mungkin
sebagian besar dari 125 juta bit itu hanyalah penyempurnaan detail yang
relatif kecil. Atau mungkin kami terlalu konservatif dalam menghitung
jumlah. Jelas, itu akan bagus jika itu benar\! Untuk tujuan kita saat
ini, poin kuncinya adalah ini: arsitektur otak itu rumit, tetapi tidak
serumit yang Anda bayangkan berdasarkan jumlah koneksi di otak.
Pandangan otak dari biologi molekuler menunjukkan bahwa manusia pada
suatu hari harus dapat memahami prinsip-prinsip dasar di balik
arsitektur otak.

Dalam beberapa paragraf terakhir, saya mengabaikan fakta bahwa 125 juta
bit hanya mengukur perbedaan genetik antara otak manusia dan simpanse.
Tidak semua fungsi otak kita disebabkan oleh 125 juta bit itu. Simpanse
adalah pemikir yang luar biasa. Mungkin kunci kecerdasan sebagian besar
terletak pada kemampuan mental (dan informasi genetik) yang dimiliki
oleh simpanse dan manusia. Jika ini benar, maka otak manusia mungkin
hanya peningkatan kecil ke otak simpanse, setidaknya dalam hal
kompleksitas prinsip-prinsip yang mendasarinya. Terlepas dari
chauvinisme manusia konvensional tentang kemampuan unik kita, ini tidak
terbayangkan: simpanse dan garis genetik manusia menyimpang hanya 5 juta
tahun yang lalu, sebuah kedipan dalam rentang waktu evolusi. Namun,
dengan tidak adanya argumen yang lebih meyakinkan, saya bersimpati pada
chauvinisme manusia konvensional: dugaan saya adalah bahwa prinsip
paling menarik yang mendasari pemikiran manusia terletak pada 125 juta
bit, bukan pada bagian genom yang kita bagi dengan simpanse. .

Mengadopsi pandangan otak dari biologi molekuler memberi kami
pengurangan sekitar sembilan urutan besarnya dalam kompleksitas
deskripsi kami. Meskipun memberi semangat, itu tidak memberi tahu kami
apakah algoritma kecerdasan yang benar-benar sederhana atau tidak
mungkin dilakukan. Bisakah kita mendapatkan pengurangan kompleksitas
lebih lanjut? Dan, lebih tepatnya, bisakah kita menyelesaikan pertanyaan
apakah algoritma sederhana untuk kecerdasan mungkin?

Sayangnya, belum ada bukti yang cukup kuat untuk menyelesaikan
pertanyaan ini. Biarkan saya menggambarkan beberapa bukti yang tersedia,
dengan peringatan bahwa ini adalah gambaran yang sangat singkat dan
tidak lengkap, dimaksudkan untuk menyampaikan rasa dari beberapa karya
terbaru, bukan untuk secara komprehensif mensurvei apa yang diketahui.

Di antara bukti yang menunjukkan bahwa mungkin ada algoritma sederhana
untuk intelijen adalah percobaan yang dilaporkan pada bulan April 2000
di jurnal Nature. Sebuah tim ilmuwan yang dipimpin oleh Mriganka Sur
"mengembalikan" otak ferret yang baru lahir. Biasanya, sinyal dari mata
musang ditransmisikan ke bagian otak yang dikenal sebagai korteks
visual. Tetapi untuk ferret ini para ilmuwan mengambil sinyal dari mata
dan mengarahkannya kembali sehingga ia pergi ke korteks pendengaran,
yaitu daerah otak yang biasanya digunakan untuk pendengaran.

Untuk memahami apa yang terjadi ketika mereka melakukan ini, kita perlu
tahu sedikit tentang korteks visual. Korteks visual berisi banyak kolom
orientasi. Ini adalah lempengan kecil neuron, yang masing-masing
merespons rangsangan visual dari beberapa arah tertentu. Anda dapat
menganggap kolom orientasi sebagai sensor arah kecil: ketika seseorang
menyinari cahaya terang dari arah tertentu, kolom orientasi yang sesuai
diaktifkan. Jika lampu dipindahkan, kolom orientasi yang berbeda
diaktifkan. Salah satu struktur tingkat tinggi yang paling penting dalam
korteks visual adalah peta orientasi, yang memetakan bagaimana kolom
orientasi diletakkan.

Apa yang para ilmuwan temukan adalah ketika sinyal visual dari mata
musang dialihkan ke korteks pendengaran, korteks pendengaran berubah.
Kolom orientasi dan peta orientasi mulai muncul di korteks pendengaran.
Itu lebih tidak teratur daripada peta orientasi yang biasanya ditemukan
di korteks visual, tetapi sangat mirip. Selain itu, para ilmuwan
melakukan beberapa tes sederhana tentang bagaimana ferret merespon
rangsangan visual, melatih mereka untuk merespons secara berbeda ketika
lampu menyala dari arah yang berbeda. Tes ini menunjukkan bahwa musang
masih bisa belajar untuk "melihat", setidaknya dengan cara yang belum
sempurna, menggunakan korteks pendengaran.

Ini adalah hasil yang mencengangkan. Ini menunjukkan bahwa ada
prinsip-prinsip umum yang mendasari bagaimana berbagai bagian otak
belajar merespons data sensorik. Kesamaan itu memberikan setidaknya
beberapa dukungan untuk gagasan bahwa ada serangkaian prinsip sederhana
yang mendasari kecerdasan. Namun, kita tidak boleh membohongi diri
sendiri tentang seberapa baik visi musang dalam percobaan ini. Tes
perilaku hanya menguji aspek visi yang sangat kotor. Dan, tentu saja,
kita tidak bisa menanyakan musang apakah mereka telah "belajar melihat".
Jadi percobaan tidak membuktikan bahwa korteks pendengaran yang
dipulihkan memberikan pengalaman visual kesetiaan yang tinggi pada
ferrets. Dan karena itu mereka hanya memberikan bukti terbatas yang
mendukung gagasan bahwa prinsip-prinsip umum mendasari bagaimana
berbagai bagian otak belajar.

Bukti apa yang ada menentang gagasan algoritma sederhana untuk
intelijen? Beberapa bukti berasal dari bidang psikologi evolusi dan
neuroanatomi. Sejak 1960-an psikolog evolusi telah menemukan berbagai
universal manusia, perilaku kompleks umum untuk semua manusia, lintas
budaya dan didikan. Manusia universal ini termasuk tabu inses antara ibu
dan anak, penggunaan musik dan tarian, serta banyak struktur bahasa yang
kompleks, seperti penggunaan kata-kata umpatan (yaitu, kata-kata tabu),
kata ganti, dan bahkan struktur yang mendasar seperti kata kerja.
Melengkapi hasil ini, banyak bukti dari neuroanatomy menunjukkan bahwa
banyak perilaku manusia dikendalikan oleh area otak tertentu yang
terlokalisasi, dan area tersebut tampaknya serupa pada semua orang.
Secara keseluruhan, temuan-temuan ini menunjukkan bahwa banyak perilaku
yang sangat terspesialisasi telah ditanamkan pada bagian-bagian tertentu
dari otak kita.

Beberapa orang menyimpulkan dari hasil ini bahwa penjelasan yang
terpisah harus diperlukan untuk banyak fungsi otak ini, dan sebagai
konsekuensinya ada kompleksitas yang tidak dapat direduksi ke fungsi
otak, kompleksitas yang membuat penjelasan sederhana untuk operasi otak
(dan, mungkin, algoritma sederhana untuk kecerdasan) tidak mungkin.
Sebagai contoh, seorang peneliti kecerdasan buatan terkenal dengan sudut
pandang ini adalah Marvin Minsky. Pada 1970-an dan 1980-an Minsky
mengembangkan teorinya "Society of Mind", berdasarkan pada gagasan bahwa
kecerdasan manusia adalah hasil dari masyarakat besar proses komputasi
yang sederhana secara individual (tetapi sangat berbeda) yang oleh
Minsky disebut agen. Dalam bukunya yang menjelaskan teorinya, Minsky
meringkas apa yang dia lihat sebagai kekuatan dari sudut pandang ini:

Trik ajaib apa yang membuat kita pintar? Triknya adalah tidak ada trik.
Kekuatan kecerdasan berasal dari keragaman kita yang luas, bukan dari
prinsip tunggal mana pun yang sempurna.

Dalam tanggapan \* \* Dalam "Contemplating Minds: A Forum for Artificial
Intelligence", diedit oleh William J. Clancey, Stephen W. Smoliar, dan
Mark Stefik (MIT Press, 1994). untuk ulasan bukunya, Minsky menguraikan
motivasi untuk Society of Mind, memberikan argumen yang mirip dengan
yang dinyatakan di atas, berdasarkan neuroanatomy dan psikologi
evolusioner:

Kita sekarang tahu bahwa otak itu sendiri terdiri dari ratusan daerah
dan nukleus yang berbeda, masing-masing dengan elemen dan pengaturan
arsitektur yang sangat berbeda, dan bahwa banyak dari mereka yang
terlibat dengan aspek aktivitas mental kita yang sangat berbeda. Massa
pengetahuan modern ini menunjukkan bahwa banyak fenomena yang secara
tradisional digambarkan dengan istilah akal sehat seperti "kecerdasan"
atau "pemahaman" sebenarnya melibatkan perakitan mesin yang rumit.

Minsky, tentu saja, bukan satu-satunya orang yang memiliki sudut pandang
seperti ini; Saya hanya memberinya sebagai contoh pendukung garis
argumen ini. Saya menemukan argumen yang menarik, tetapi tidak percaya
bukti itu meyakinkan. Meskipun benar bahwa otak terdiri dari sejumlah
besar daerah yang berbeda, dengan fungsi yang berbeda, tidak berarti
bahwa penjelasan sederhana untuk fungsi otak tidak mungkin. Mungkin
perbedaan-perbedaan arsitektural itu muncul dari prinsip-prinsip dasar
yang sama, seperti halnya pergerakan komet, planet-planet, matahari dan
bintang-bintang semuanya muncul dari satu gaya gravitasi tunggal. Baik
Minsky maupun orang lain tidak berargumentasi dengan meyakinkan terhadap
prinsip-prinsip dasar tersebut.

Prasangka saya sendiri mendukung adanya algoritma sederhana untuk
kecerdasan. Dan alasan utama saya menyukai ide, di atas dan di luar
argumen (tidak meyakinkan) di atas, adalah bahwa itu adalah ide yang
optimis. Ketika sampai pada penelitian, optimisme yang tidak dapat
dibenarkan seringkali lebih produktif daripada pesimisme yang tampaknya
lebih baik, karena seorang optimis memiliki keberanian untuk berangkat
dan mencoba hal-hal baru. Itulah jalan menuju penemuan, bahkan jika apa
yang ditemukan mungkin bukan yang semula diharapkan. Seorang pesimis
mungkin lebih "benar" dalam arti sempit, tetapi akan menemukan lebih
sedikit daripada yang optimis.

Pandangan ini sangat kontras dengan cara kita menilai ide: dengan
mencoba mencari tahu apakah itu benar atau salah. Itu strategi yang
masuk akal untuk berurusan dengan hal-hal kecil rutin dari penelitian
sehari-hari. Tapi itu bisa menjadi cara yang salah untuk menilai ide
yang besar dan berani, jenis ide yang mendefinisikan seluruh program
penelitian. Terkadang, kami hanya memiliki bukti yang lemah tentang
apakah gagasan seperti itu benar atau tidak. Dengan patuh kita dapat
menolak untuk mengikuti ide itu, alih-alih menghabiskan seluruh waktu
kita menyipit bukti yang tersedia, mencoba untuk membedakan apa yang
benar. Atau kita dapat menerima bahwa belum ada yang tahu, dan
sebaliknya bekerja keras untuk mengembangkan gagasan besar dan berani,
dalam pemahaman bahwa sementara kita tidak memiliki jaminan kesuksesan,
hanya dengan demikian pemahaman kita maju.

Dengan semua yang dikatakan, dalam bentuk yang paling optimis, saya
tidak percaya kita akan pernah menemukan algoritma sederhana untuk
kecerdasan. Untuk lebih konkret, saya tidak percaya kita akan pernah
menemukan program Python yang sangat pendek (atau C atau Lisp, atau apa
pun) - katakanlah, di mana saja hingga ribuan baris kode - yang
mengimplementasikan kecerdasan buatan. Saya juga tidak berpikir kita
akan pernah menemukan jaringan saraf (*neural networks*) yang
benar-benar mudah digambarkan yang dapat mengimplementasikan kecerdasan
buatan. Tapi saya percaya itu layak bertindak seolah-olah kita dapat
menemukan program atau jaringan seperti itu. Itulah jalan menuju
wawasan, dan dengan menempuh jalan itu suatu hari kita mungkin cukup
memahami untuk menulis program yang lebih panjang atau membangun
jaringan yang lebih canggih yang menunjukkan kecerdasan. Karena itu, ada
baiknya bertindak seolah-olah ada algoritma yang sangat sederhana untuk
kecerdasan.

Pada 1980-an, ahli matematika dan komputer terkemuka Jack Schwartz
diundang ke debat antara para pendukung kecerdasan buatan dan skeptis
kecerdasan buatan. Perdebatan menjadi sulit, dengan para pendukung
membuat klaim berlebihan tentang hal-hal menakjubkan hanya di tikungan,
dan skeptis menggandakan pesimisme mereka, mengklaim kecerdasan buatan
sama sekali mustahil. Schwartz adalah orang luar dalam debat, dan tetap
diam saat diskusi memanas. Selama jeda, dia diminta untuk berbicara dan
menyatakan pikirannya tentang masalah yang sedang dibahas. Dia berkata:
"Yah, beberapa perkembangan ini mungkin terletak seratus hadiah Nobel"
(ref, halaman 22). Bagiku itu adalah respons yang sempurna. Kunci untuk
kecerdasan buatan adalah ide-ide yang sederhana dan kuat, dan kita dapat
dan harus mencari ide-ide itu secara optimis. Tetapi kita akan
membutuhkan banyak ide seperti itu, dan kita masih harus menempuh jalan
panjang\!

Ucapan Terima Kasih

Buku itu tumbuh dari serangkaian catatan yang saya siapkan untuk
kelompok belajar online tentang jaringan saraf (*neural networks*) dan
*pembelajaran dalam (deep learning)*. Terima kasih banyak kepada semua
peserta dalam kelompok studi itu: Paul Bloore, Chris Dawson, Andrew
Doherty, Ilya Grigorik, Alex Kosorukoff, Chris Olah, dan Rob Spekkens.
Saya belajar banyak dari Anda semua. Saya khususnya berterima kasih
kepada Rob, karena telah memberikan begitu banyak pertanyaan dan gagasan
yang mendalam, dan kepada Chris, yang terus membagikan pengetahuannya
yang berkembang pesat tentang jaringan saraf. Terima kasih juga kepada
Yoshua Bengio, yang membaca dan memberikan umpan balik pada sebuah bab.
