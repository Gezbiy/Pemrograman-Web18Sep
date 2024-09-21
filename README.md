# Pemrograman-Web18Sep
Tugas Pemrograman Web 1 (18 September 2024)
By Muhammad Zaidan Rafat / Informatika 3-A / 231730016

## Here is the list that is needed
```
fontawesome.com
https://getbootstrap.com/docs/5.0/components/accordion/
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```
## Head Syntax
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Biography</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/b8fb05f23f.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous">
</head>
```
## Body -> Navbar Syntax
```
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lq fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">D'Tech. Corp</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse text-right" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#service">Service</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Portofolio">Portofolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#AboutCompany">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#leader">Leader of Company</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Contact">Contact Us</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              More
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Instagram</a></li>
              <li><a class="dropdown-item" href="https://youtu.be/rd1fLUv9cPk?si=DgvE1K9yN3m-C9u1">Youtube</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
```
## Body -> Banner Syntax
```
 <div class="container-fluid banner">
    <div class="container text-center">
      <h4 class="display-6">Welcome To Our Company Web</h4>
      <h3 class="display-1">D'Tech. Corp</h3>
      <a href="layanan"></a>
      <button type=button class="btn btn-danger btn-lg">LETS START</button>
      </a>
    </div>
  </div>
```
## Body -> Service Syntax
```
<div class="container-fluid Service pt-5 pb-5">
    <div class="container text-center">
      <h2 class="display-3" id="service">Service</h2>
      <p>D'Tech. Corp menawarkan solusi teknologi komprehensif yang meliputi pengembangan website responsif, aplikasi
        web, dan optimasi SEO. Kami juga ahli dalam merancang dan mengimplementasikan jaringan komputer yang aman dan
        handal, termasuk virtualisasi dan pemeliharaan jaringan. Selain itu, kami memastikan kualitas perangkat lunak
        Anda melalui proses quality assurance yang ketat, meliputi pengujian fungsional, otomatisasi, dan manajemen bug.
        Dengan layanan kami, Anda dapat membangun kehadiran online yang kuat dan sistem IT yang efisien</p>
      <div class="row pt-4 pb-5 text-center">
        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
          <h3 class="mt-3">Programming</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam accusamus dicta totam necessitatibus
            perspiciatis odit sequi repellendus a facilis. Nam excepturi inventore commodi esse, ratione quia! A itaque
            alias repudiandae.</p>
        </div>
        <div class="col-md-4">
          <span class="lingkaran"><i class="fa-solid fa-network-wired fa-5x"></i></span>
          <h3 class="mt-3">Network Administration</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam accusamus dicta totam necessitatibus
            perspiciatis odit sequi repellendus a facilis. Nam excepturi inventore commodi esse, ratione quia! A itaque
            alias repudiandae.</p>
        </div>
        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-bath fa-5x"></i></span>
          <h3 class="mt-3">Quality Control</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam accusamus dicta totam necessitatibus
            perspiciatis odit sequi repellendus a facilis. Nam excepturi inventore commodi esse, ratione quia! A itaque
            alias repudiandae.</p>
        </div>
      </div>
    </div>
  </div>
```
## Body -> Portofolio Syntax
```
<div class="container-fluid pt-5 pb-5 bg-light">
    <div class="container text-center">
      <h2 class="display-3" id="Portofolio">Portofolio</h2>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga enim praesentium fugiat impedit aperiam! Rerum
        atque hic ea, at, recusandae facilis pariatur tempore eaque architecto omnis maxime quia, magni fuga.</p>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4BhpFKCJ0_LAl-WhYLzk-84c-uQCkvKNObg&s"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Web Development</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://trinetprimasolusi.net/wp-content/uploads/2019/11/Management-Information-System.jpg"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Network Architecture</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://www.softwebsolutions.com/wp-content/uploads/2017/11/qa-blog.jpg" class="card-img-top"
              width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Quality Automation</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://www.salimkho.com/wp-content/uploads/2021/02/Software-Quality-Assurance-1024x533-1.jpeg"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Quality Assurance</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLYGmNExnAMAe1Cd0WnoYlx6XZt4GCic_Skw&s"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Network Administration</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://raharja.ac.id/wp-content/uploads/2020/11/Cloud-Computing.png" class="card-img-top"
              width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Cloud Computing</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
```
## Body -> About Company
```
<div class="container-fluid AboutCompany pt-5 pb-5">
    <div class="container text-center">
      <h2 class="display-3" id="AboutCompany">About Company</h2>
      <p>D'Tech. Corp Solutions didirikan pada tahun 2024 sebagai tanggapan atas permintaan akan solusi teknologi yang
        lebih inovatif dan efektif di pasar Indonesia. Dalam beberapa dekade terakhir, teknologi telah menjadi kunci
        kompetitif bagi perusahaan di berbagai industri, dan kebutuhan akan solusi yang terintegrasi dan efisien
        semakin
        meningkat.
        Pada awalnya, D'Tech. Corp Solutions didirikan sebagai sebuah tim kecil yang dipimpin oleh seorang pengembang
        web yang memiliki visi untuk menciptakan aplikasi web yang tidak hanya menarik dan responsif, tetapi juga
        mampu
        memberikan nilai tambah bagi pelanggan. Tim ini kemudian berkembang pesat dengan penambahan anggota yang
        memiliki expertise dalam bidang otomatisasi kualitas dan solusi jaringan.</p>
      <div class="clearfix pt-5">
        <img src="https://img.freepik.com/premium-photo/sculpture-man-with-laptop-pink-background_168171-5733.jpg"
          class="col-md-6 float-md-end mb-3 crop-img" width="200" height="300">
        <h3 class="mt-3">Misi</h3>
        <p style="text-align: left;">
          Kami fokus pada menciptakan aplikasi web yang tidak hanya menarik dan responsif, tetapi juga mampu memberikan
          nilai tambah bagi pelanggan melalui integrasi teknologi terbaru dan optimalisasi SEO. Tak hanya itu
          Dengan menggunakan sistem automasi proses yang canggih, kami membantu perusahaan meningkatkan efisiensi
          produksi dan kualitas produk mereka. Solusi Jaringan: Kami menyediakan solusi jaringan yang memadai, termasuk
          konfigurasi, manajemen, dan integrasi dengan teknologi terkini untuk meningkatkan keamanan dan performa.</p>
      </div>
    </div>
  </div>
```
## Body -> Our Leader Syntax
```
<div class="container-fluid pt-5 pb-5 bg-light">
    <div class="container text-center">
      <h2 class="display-3" id="leader">Our Leader</h2>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tenetur voluptas porro, quidem doloremque neque odit
        in illum eius esse sequi?</p>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col-md-4 text-center leader">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbX2Of8S6GQGvLXbXChIFXDGU9RpgFhcigrg&s"
            class="rounded-circle mb-3" alt="">
          <h4>Marcus Aurelius</h4>
          <p>Chief Technology Officer</p>
          <p><a href="" class="social"><i class="fa-brands fa-github fa-5"></i>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
              <a href="" class="social"><i class="fa-brands fa-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-facebook"></i></a></a></p>
        </div>
        <div class="col-md-4 text-center leader">
          <img src="https://t3.ftcdn.net/jpg/05/63/93/56/360_F_563935601_nMFYQ1QsI2vfX6jvGXpDXEBAnAhUmzvc.jpg"
            class="rounded-circle mb-3" alt="">
          <h4>Zaidan Rafat</h4>
          <p>Chief Executive Officer</p>
          <p><a href="" class="social"><i class="fa-brands fa-github fa-5"></i>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
              <a href="" class="social"><i class="fa-brands fa-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-facebook"></i></a></a></p>
        </div>
        <div class="col-md-4 text-center leader">
          <img src="https://png.pngtree.com/thumb_back/fh260/background/20230611/pngtree-aristotle-statues-and-portraits-image_2883959.jpg"
            class="rounded-circle mb-3" alt="">
          <h4>Aristoteles</h4>
          <p>Chief Financial Officer</p>
          <p><a href="" class="social"><i class="fa-brands fa-github fa-5"></i>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
              <a href="" class="social"><i class="fa-brands fa-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-facebook"></i></a></a></p>
        </div>
      </div>
    </div>
  </div>
```
## Body -> Client Syntax
```
<div class="container-fluid client pt-5 pb-5">
    <div class="container text-center">
      <h2 class="display-3" id="client">Our Client</h2>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col">
          <img src="https://www.krakatauposco.co.id/assets/images/logo-krakatau-posco-long.png" alt="">
        </div>
        <div class="col">
          <img src="https://www.krakatauposco.co.id/assets/images/logo-krakatau-posco-long.png" alt="">
        </div>
        <div class="col">
          <img src="https://www.krakatauposco.co.id/assets/images/logo-krakatau-posco-long.png"" alt="">
      </div>
    </div>
  </div>
 </div>
```
## Body -> Contact Us Syntax
```
 <div class=" container-fluid pt-5 pb-5 Contact">
          <div class="container">
            <h2 class="display-3 text-center" id="Contact">Contact Us</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure reiciendis commodi qui.
              Provident quis aperiam facere tenetur, praesentium sit possimus quidem in veritatis quisquam beatae quod
              voluptas officiis sint veniam.</p>
            <div class="row pb-3">
              <div class="col-md-6">
                <input type="text" class="form-control form-control-lg mb-3" placeholder="Name">
                <input type="text" class="form-control form-control-lg mb-3" placeholder="E-Mail">
                <input type="text" class="form-control form-control-lg mb-3" placeholder="Number Phone">
              </div>
              <div class="col-md-6">
                <textarea name="" id="" class="form-control form-control-lg" rows="5"></textarea>
              </div>
            </div>
            <div class="col-md-3 mx-auto text-center"><button type="button" class="btn btn-danger btn-lg">Submit</button></div>
          </div>
        </div>
        <div class="container text-center pt-5 pb-5">All Right Reserved &copy;2024</div>
        <!-- Contact End -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
          crossorigin="anonymous"></script>
</body>
</html>
```
## Full Version Syntax
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Biography</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/b8fb05f23f.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css"
    integrity="sha384-AYMEC3Yw5cVb3ZcuHt0A93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous">
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark shadow-lq fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">D'Tech. Corp</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse text-right" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="#service">Service</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Portofolio">Portofolio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#AboutCompany">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#leader">Leader of Company</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Contact">Contact Us</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              More
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Instagram</a></li>
              <li><a class="dropdown-item" href="https://youtu.be/rd1fLUv9cPk?si=DgvE1K9yN3m-C9u1">Youtube</a></li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!--Banner start-->
  <div class="container-fluid banner">
    <div class="container text-center">
      <h4 class="display-6">Welcome To Our Company Web</h4>
      <h3 class="display-1">D'Tech. Corp</h3>
      <a href="layanan"></a>
      <button type=button class="btn btn-danger btn-lg">LETS START</button>
      </a>
    </div>
  </div>
  <!--Banner start-->
  <!--service start-->>
  <div class="container-fluid Service pt-5 pb-5">
    <div class="container text-center">
      <h2 class="display-3" id="service">Service</h2>
      <p>D'Tech. Corp menawarkan solusi teknologi komprehensif yang meliputi pengembangan website responsif, aplikasi
        web, dan optimasi SEO. Kami juga ahli dalam merancang dan mengimplementasikan jaringan komputer yang aman dan
        handal, termasuk virtualisasi dan pemeliharaan jaringan. Selain itu, kami memastikan kualitas perangkat lunak
        Anda melalui proses quality assurance yang ketat, meliputi pengujian fungsional, otomatisasi, dan manajemen bug.
        Dengan layanan kami, Anda dapat membangun kehadiran online yang kuat dan sistem IT yang efisien</p>
      <div class="row pt-4 pb-5 text-center">
        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-code fa-5x"></i></span>
          <h3 class="mt-3">Programming</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam accusamus dicta totam necessitatibus
            perspiciatis odit sequi repellendus a facilis. Nam excepturi inventore commodi esse, ratione quia! A itaque
            alias repudiandae.</p>
        </div>
        <div class="col-md-4">
          <span class="lingkaran"><i class="fa-solid fa-network-wired fa-5x"></i></span>
          <h3 class="mt-3">Network Administration</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam accusamus dicta totam necessitatibus
            perspiciatis odit sequi repellendus a facilis. Nam excepturi inventore commodi esse, ratione quia! A itaque
            alias repudiandae.</p>
        </div>
        <div class="col-md-4">
          <span class="lingkaran"><i class="fas fa-bath fa-5x"></i></span>
          <h3 class="mt-3">Quality Control</h3>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam accusamus dicta totam necessitatibus
            perspiciatis odit sequi repellendus a facilis. Nam excepturi inventore commodi esse, ratione quia! A itaque
            alias repudiandae.</p>
        </div>
      </div>
    </div>
  </div>
  <!--Service End-->
  <!--Portofolio Start-->
  <div class="container-fluid pt-5 pb-5 bg-light">
    <div class="container text-center">
      <h2 class="display-3" id="Portofolio">Portofolio</h2>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Fuga enim praesentium fugiat impedit aperiam! Rerum
        atque hic ea, at, recusandae facilis pariatur tempore eaque architecto omnis maxime quia, magni fuga.</p>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4BhpFKCJ0_LAl-WhYLzk-84c-uQCkvKNObg&s"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Web Development</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://trinetprimasolusi.net/wp-content/uploads/2019/11/Management-Information-System.jpg"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Network Architecture</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://www.softwebsolutions.com/wp-content/uploads/2017/11/qa-blog.jpg" class="card-img-top"
              width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Quality Automation</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://www.salimkho.com/wp-content/uploads/2021/02/Software-Quality-Assurance-1024x533-1.jpeg"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Quality Assurance</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQLYGmNExnAMAe1Cd0WnoYlx6XZt4GCic_Skw&s"
              class="card-img-top" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Network Administration</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card" crop-img>
            <img src="https://raharja.ac.id/wp-content/uploads/2020/11/Cloud-Computing.png" class="card-img-top"
              width="200" height="200">
            <div class="card-body">
              <h5 class="card-title">Cloud Computing</h5>
              <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's
                content.</p>
              <a href="#" class="btn btn-primary">More....</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!--Portofolio End-->
  <!--About Company Start-->
  <div class="container-fluid AboutCompany pt-5 pb-5">
    <div class="container text-center">
      <h2 class="display-3" id="AboutCompany">About Company</h2>
      <p>D'Tech. Corp Solutions didirikan pada tahun 2024 sebagai tanggapan atas permintaan akan solusi teknologi yang
        lebih inovatif dan efektif di pasar Indonesia. Dalam beberapa dekade terakhir, teknologi telah menjadi kunci
        kompetitif bagi perusahaan di berbagai industri, dan kebutuhan akan solusi yang terintegrasi dan efisien
        semakin
        meningkat.
        Pada awalnya, D'Tech. Corp Solutions didirikan sebagai sebuah tim kecil yang dipimpin oleh seorang pengembang
        web yang memiliki visi untuk menciptakan aplikasi web yang tidak hanya menarik dan responsif, tetapi juga
        mampu
        memberikan nilai tambah bagi pelanggan. Tim ini kemudian berkembang pesat dengan penambahan anggota yang
        memiliki expertise dalam bidang otomatisasi kualitas dan solusi jaringan.</p>
      <div class="clearfix pt-5">
        <img src="https://img.freepik.com/premium-photo/sculpture-man-with-laptop-pink-background_168171-5733.jpg"
          class="col-md-6 float-md-end mb-3 crop-img" width="200" height="300">
        <h3 class="mt-3">Misi</h3>
        <p style="text-align: left;">
          Kami fokus pada menciptakan aplikasi web yang tidak hanya menarik dan responsif, tetapi juga mampu memberikan
          nilai tambah bagi pelanggan melalui integrasi teknologi terbaru dan optimalisasi SEO. Tak hanya itu
          Dengan menggunakan sistem automasi proses yang canggih, kami membantu perusahaan meningkatkan efisiensi
          produksi dan kualitas produk mereka. Solusi Jaringan: Kami menyediakan solusi jaringan yang memadai, termasuk
          konfigurasi, manajemen, dan integrasi dengan teknologi terkini untuk meningkatkan keamanan dan performa.</p>
      </div>
    </div>
  </div>
  <!--About Company End-->
  <!-- Leader Start -->
  <div class="container-fluid pt-5 pb-5 bg-light">
    <div class="container text-center">
      <h2 class="display-3" id="leader">Our Leader</h2>
      <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tenetur voluptas porro, quidem doloremque neque odit
        in illum eius esse sequi?</p>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col-md-4 text-center leader">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbX2Of8S6GQGvLXbXChIFXDGU9RpgFhcigrg&s"
            class="rounded-circle mb-3" alt="">
          <h4>Marcus Aurelius</h4>
          <p>Chief Technology Officer</p>
          <p><a href="" class="social"><i class="fa-brands fa-github fa-5"></i>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
              <a href="" class="social"><i class="fa-brands fa-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-facebook"></i></a></a></p>
        </div>
        <div class="col-md-4 text-center leader">
          <img src="https://t3.ftcdn.net/jpg/05/63/93/56/360_F_563935601_nMFYQ1QsI2vfX6jvGXpDXEBAnAhUmzvc.jpg"
            class="rounded-circle mb-3" alt="">
          <h4>Zaidan Rafat</h4>
          <p>Chief Executive Officer</p>
          <p><a href="" class="social"><i class="fa-brands fa-github fa-5"></i>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
              <a href="" class="social"><i class="fa-brands fa-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-facebook"></i></a></a></p>
        </div>
        <div class="col-md-4 text-center leader">
          <img src="https://png.pngtree.com/thumb_back/fh260/background/20230611/pngtree-aristotle-statues-and-portraits-image_2883959.jpg"
            class="rounded-circle mb-3" alt="">
          <h4>Aristoteles</h4>
          <p>Chief Financial Officer</p>
          <p><a href="" class="social"><i class="fa-brands fa-github fa-5"></i>
              <a href="" class="social"><i class="fa-brands fa-linkedin"></i></a>
              <a href="" class="social"><i class="fa-brands fa-instagram"></i></a>
              <a href="" class="social"><i class="fa-brands fa-facebook"></i></a></a></p>
        </div>
      </div>
    </div>
  </div>
  <!-- Leader End -->
  <!-- client start -->
  <div class="container-fluid client pt-5 pb-5">
    <div class="container text-center">
      <h2 class="display-3" id="client">Our Client</h2>
      <div class="row pt-4 gx-4 gy-4">
        <div class="col">
          <img src="https://www.krakatauposco.co.id/assets/images/logo-krakatau-posco-long.png" alt="">
        </div>
        <div class="col">
          <img src="https://www.krakatauposco.co.id/assets/images/logo-krakatau-posco-long.png" alt="">
        </div>
        <div class="col">
          <img src="https://www.krakatauposco.co.id/assets/images/logo-krakatau-posco-long.png"" alt="">
      </div>
    </div>
  </div>
 </div>
<!-- client end -->
<!-- Contact Start -->
 <div class=" container-fluid pt-5 pb-5 Contact">
          <div class="container">
            <h2 class="display-3 text-center" id="Contact">Contact Us</h2>
            <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure reiciendis commodi qui.
              Provident quis aperiam facere tenetur, praesentium sit possimus quidem in veritatis quisquam beatae quod
              voluptas officiis sint veniam.</p>
            <div class="row pb-3">
              <div class="col-md-6">
                <input type="text" class="form-control form-control-lg mb-3" placeholder="Name">
                <input type="text" class="form-control form-control-lg mb-3" placeholder="E-Mail">
                <input type="text" class="form-control form-control-lg mb-3" placeholder="Number Phone">
              </div>
              <div class="col-md-6">
                <textarea name="" id="" class="form-control form-control-lg" rows="5"></textarea>
              </div>
            </div>
            <div class="col-md-3 mx-auto text-center"><button type="button" class="btn btn-danger btn-lg">Submit</button></div>
          </div>
        </div>
        <div class="container text-center pt-5 pb-5">All Right Reserved &copy;2024</div>
        <!-- Contact End -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
          integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
          crossorigin="anonymous"></script>
</body>
</html>
```
