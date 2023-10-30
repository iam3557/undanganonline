# undanganonline
<!DOCTYPE html>
<html>
<head>
<title>undangan-1
</title>
<script src="https://polyfill.io/v3/polyfill.min.js?features=default"></script>

    <link rel="stylesheet" type="text/css" href="./style.css" />
    <script type="module" src="./index.js"></script>

  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
<style>
 body{
 margin:0;
 padding:0;
 }
.page {
  height: auto;
  text-align: center;
  font-size: 24px;
}

.page:nth-child(1) {
}
.background1 {
  background: url('https://penganten.com/wp-content/uploads/2019/05/prewedding.jpg') no-repeat center center ;
  background-size: cover;
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.overlay {
   position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  flex-direction: column; /* Menetapkan tata letak teks secara vertikal */
  justify-content: center; /* Menetapkan tata letak elemen ke posisi tengah secara vertikal */
  align-items: center; /* Menetapkan elemen ke posisi tengah secara horizontal */
  text-align: center; /* Menetapkan teks ke posisi tengah pada layar yang lebih lebar */
	-webkit-animation: text-focus-in 1s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
	        animation: text-focus-in 1s cubic-bezier(0.550, 0.085, 0.680, 0.530) both;
}
@-webkit-keyframes text-focus-in {
  0% {
    -webkit-filter: blur(12px);
            filter: blur(12px);
    opacity: 0;
  }
  100% {
    -webkit-filter: blur(0px);
            filter: blur(0px);
    opacity: 1;
  }
}
@keyframes text-focus-in {
  0% {
    -webkit-filter: blur(12px);
            filter: blur(12px);
    opacity: 0;
  }
  100% {
    -webkit-filter: blur(0px);
            filter: blur(0px);
    opacity: 1;
  }
}

h1, p, h3 {
  color: white;
}

/* Media queries untuk tata letak responsif */
@media screen and (max-width: 768px) {
  .overlay {
    padding: 0px; /* Atur jarak untuk layar yang lebih kecil */
  }
}

.page:nth-child(2) {
  background-color: #DCDCDC;
  background-size: cover;
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  justify-content: center;
}
.dnks0{
position: absolute;
  top: 0;
  left: 0;
  right:0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.0);
  display: flex;
  flex-direction: column; /* Menetapkan tata letak teks secara vertikal */
  justify-content: center; /* Menetapkan tata letak elemen ke posisi tengah secara vertikal */
  align-items: center; /* Menetapkan elemen ke posisi tengah secara horizontal */ 
}
.page:nth-child(3) {
  background-color: #DCDCDC;
  
}
.product-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 10px;
  }

  .product {
    flex-basis: 30%;
    margin: 10px;
    position: relative;
    overflow: hidden;
  }

  .product img {
    width: 250px;
    height: 250px;
  }

  @media screen and (max-width: 768px) {
    .product {
      flex-basis: 45%;
    }
  }

  @media screen and (max-width: 480px) {
    .product {
      flex-basis: 100%;
    }
    .product img {
    width: 200px;
    height: 200px;
  }
  }
.page:nth-child(4) {
  background-color: #FFF8DC;
}
.dmskiaodx {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
  }

  .productasdw {
    flex-basis: 30%;
    margin: 10px;
    position: relative;
    overflow: hidden;
  }

  .productasdw img {
    width: 100%;
    height: 100%;
  }

  @media screen and (max-width: 768px) {
    .productasdw {
      flex-basis: 45%;
    }
  }

  @media screen and (max-width: 480px) {
    .productasdw {
      flex-basis: 100%;
    }
  }
  .card {
  box-sizing: border-box;
  width: 90%;
  height: auto;
  background: rgba(217, 217, 217, 0.58);
  border: 1px solid white;
  box-shadow: 12px 17px 51px rgba(0, 0, 0, 0.5);
  backdrop-filter: blur(10px);
  border-radius: 17px;
  text-align: center;
  cursor: pointer;
  transition: all 0.5s;
  display: flex;
  align-items: center;
  justify-content: center;
  user-select: none;
  font-weight: bolder;
  color: black;
}
button {
padding-bottom:10px;
  max-width: 320px;
  padding: 0.5rem 1.4rem;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  text-align: center;
  text-transform: uppercase;
  vertical-align: middle;
  align-items: center;
  border-radius: 0.5rem;
  border: 1px solid rgba(0, 0, 0, 0.25);
  gap: 0.75rem;
  color: rgb(65, 63, 63);
  background-color: #fff;
  cursor: pointer;
  transition: all .6s ease;
  
}

.button img {
  height: 29px;
}

button:hover {
  transform: scale(1.02);
}
.page:nth-child(5) {
  background-color: #F8F8FF;
}

.page:nth-child(6) {
  background-color: #2c3e50;
}
div.scroll-container {
  background-color: #333;
  overflow: auto;
  white-space: nowrap;
  padding: 10px;
  height:100%;
}

div.scroll-container img {
  padding: 10px;
}
.page:nth-child(7) {
  background-color: #A9A9A9;
}
.product-listqwe {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 30px;
  }

  .productqwe {
    flex-basis: 30%;
    margin: 10px;
    position: relative;
    overflow: hidden;
    height:200px;
    
  }

  .productqwe img {
    width: 100%;
    height: 100%;
    transition: transform 0.5s;
  }

  .productqwe:hover img {
    transform: scale(1.3);
  }

  @media screen and (max-width: 768px) {
    .productqwe {
      flex-basis: 45%;
    }
  }

  @media screen and (max-width: 480px) {
    .productqwe {
      flex-basis: 100%;
    }
  }
.page:nth-child(8) {
  background-color: #F8F8FF;
}
</style>
</head>
<body>

<div class="page">
 <div class="background1">
    <div class="overlay">
      <h1>undangan</h1>
      <p>23 desember 2023</p>
      <h3>Nanang pajar & nobela sintia veronika</h3>
    </div>
      <br>
  </div>
</div>
<div class="page">
<div class="dnks0"data-aos="fade-up"data-aos-delay="80"data-aos-duration="1000"style="margin-botom:30%;">

<p style="color:#2F4F4F;font-size:100%;padding-left:10%;padding-right:10%;">asalamualaikum warohmatuulahi wabarokatu</p>
<p class="mdski08"style="color:#2F4F4F;padding-right:10%;padding-left:10%;font-size:80%;">maha suci Allah.swt yang telah menciptakan makhluk-Nya berpasang-pasangan.Ya Allah perkenankanlah kami merangkaikan kasih dan sayang yang kau ciptakan di antara kami untuk mengikuti sunah Rasul-Mu dalam rangkak membentuk keluarga yang sakinah,mawadah warohmah</p>
<p class="mdski08"style="color:#2F4F4F;padding-right:10%;padding-left:10%;font-size:80%;">Dengan memohon Ridho dan Rahmat Allah SWT,
kami mengharapkan kehadiran Bapak/Ibu/Saudara/i
pada acara pernikahan putra dan putri kami yang bernama:</p>
</div>
</div>
<div class="page">
<div class="product-list">

    <div class="product"data-aos="fade-right"data-aos-delay="80"data-aos-duration="1000">
    <div class="si89y8">
      <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.PjXtuRpuYdwl3qvodjkPggHaEo%26pid%3DApi%26h%3D160&f=1&ipt=7cd99953b01b0b5ad1a983454501a1f1e69b6a8257b22a368f68ebe2544cdb09&ipo=images"style="border-radius:50%;" alt="Product 1" onclick="handleClick('link_tujuan_produk_1')">
    </div>
    <p style="color:#2F4F4F;font-size:80%;padding:15px;">nanang pajar, anakk dari bapak(...) dan ibu (...)dsfghjtrer dfghggdfd</p>
    </div>
    <div class="product"data-aos="fade-left"data-aos-delay="80"data-aos-duration="1000">
    <div class="sid9s8">
      <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.MX4VdORPU7VdLUlrKcLLAAHaKd%26pid%3DApi%26h%3D160&f=1&ipt=09de91f31ee576eeb8652601c499333bdd52a14eeead023bd0e91fb5182f98a8&ipo=images" alt="Product 2" style="border-radius:50%;"onclick="handleClick('link_tujuan_produk_2')">
    </div>
    <p style="color:#2F4F4F;font-size:80%;padding:15px;">nanang pajar, anakk dari bapak(...) dan ibu (...)asdsdfiluyt rytyuio654esvx hjkjg</p>
    </div>
    </div>
</div>
<div class="page">
<div class="dmskiaodx">
    <div class="card"data-aos="zoom-in-up"ata-aos-delay="80"data-aos-duration="1000">
    <div class="sid9s8">
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">Akad nikah</P>
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.MX4VdORPU7VdLUlrKcLLAAHaKd%26pid%3DApi%26h%3D160&f=1&ipt=09de91f31ee576eeb8652601c499333bdd52a14eeead023bd0e91fb5182f98a8&ipo=images" alt="Product 2" style="border-radius:50%;"onclick="handleClick('link_tujuan_produk_2')">
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">minggu 30 desember 2023</P>
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">11.00 WIB s/d selesai</p>
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">di tempat kediaman memepelai wanita dari bapak (...) desa (...) kelurahan(...) kecamatan(...) kabupaten(...) provinsi(...)</p>
  <br>
  <button class="button">
  <img src="https://developers.google.com/static/maps/images/maps-icon.svg">
</svg>
  Continue with Google
</button>
</div>
</div>
      </div>
    <div class="dmskiaodx">
    <div class="card"data-aos="zoom-in-up"data-aos-delay="80"data-aos-duration="1000">
    <div class="sid9s8">
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">acara</P>
  <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.MX4VdORPU7VdLUlrKcLLAAHaKd%26pid%3DApi%26h%3D160&f=1&ipt=09de91f31ee576eeb8652601c499333bdd52a14eeead023bd0e91fb5182f98a8&ipo=images" alt="Product 2" style="border-radius:50%;"onclick="handleClick('link_tujuan_produk_2')">
   <p style="color:#2F4F4F;font-size:80%;padding:15px;">minggu 31 desember 2023</P>
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">menyambut tamu undangan dengan hiburan organ tunggal</P>
  <p style="color:#2F4F4F;font-size:80%;padding:15px;">11.00 WIB s/d selesai</p>
  <button class="button">
  <img src="https://developers.google.com/static/maps/images/maps-icon.svg">
</svg>
  Continue with Google
</button>
</div>
</div>
      </div>
    <br>
</div>

<div class="page">
<div class="dmskiaodx"data-aos="zoom-in"data-aos-delay="80"data-aos-duration="1000">
<p style="color:#2F4F4F;font-size:70%;padding:10%;">"Dan di antara tanda-tanda kebesaran-Nya ialah diciptakan-Nya untukmu pasangan hidup dari jenismu sendiri supaya kamu mendapatkan ketenangan hati dan di jadikan-Nya kasih sayang diantara kamu.sesungguhknya yang demikian itu menjadi tanda kebesaran -Nya bagi orang-orang berifikir"<p>
</div>
</div>
<div class="page">
 <div class="scroll-container">
  <img src="https://penganten.com/wp-content/uploads/2019/05/prewedding.jpg" alt="Cinque Terre"height="500px">
  <img src="https://penganten.com/wp-content/uploads/2019/04/prewedding-outdoor-hobi.jpg" alt="Forest"height="500px">
  <img src="https://penganten.com/wp-content/uploads/2019/04/prewedding-outdoor-jalanan.jpg" alt="Northern Lights"height="500px">
  <img src="https://penganten.com/wp-content/uploads/2019/05/prewedding.jpg" alt="Mountains"height="500px">
</div> 
</div>
<div class="page">
<br>
<p style="color:#FFFAF;font-size:70%;padding:10%;">Doa dan restu anda merupakan karunia yang sangat berarti bagi kami dan jika memberi adalah unkapan terima kasih,maka anda dapat memberi kado ataupun amplop digital secara transfer pada akun di bawah ini</p>
<div class="product-listqwe">
    <div class="productqwe">
    <a href="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse1.mm.bing.net%2Fth%3Fid%3DOIP.038qfA6ccuNfwVCElvL45wHaEK%26pid%3DApi&f=1&ipt=0f5fb2c85e7dc6579d866d5a8ed86bb1d4f59b9fefe9b1c2147c2a2356350d10&ipo=images">
      <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.eb-6tf08Im14LF4Gf8TqnwHaE8%26pid%3DApi&f=1&ipt=227090c67e2b044189618475288552c2579cafcb138a9f6db04f3d9fdefdbb7f&ipo=images" alt="Product 1" onclick="handleClick('link_tujuan_produk_1')"></a>
    </div>
    <div class="productqwe"style="background-color:white;">
      <img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.8Pf2yaaFBjW0SpuvClFmIwHaEo%26pid%3DApi&f=1&ipt=32636421497de03609769856ab32209528d2bf365f66dca78e2d09dc2a56cf54&ipo=images" alt="Product 2" onclick="handleClick('link_tujuan_produk_2')">
    </div>
    
    </div>
</div>
<div class="page">
<div class="dksoa08s9ud">
<p style="color:#2F4F4F;font-size:70%;padding:10%;">Doa restu anda merupakan karuna yang sangat berarti bagi kami dan kami sangat berminta maaf apabila ada kata salah ataupun perlakuan dari kamu yang kurang berkenan,dan kepada Allah kami mohon ampun.</p>
<p  style="color:#2F4F4F;font-size:70%;padding:10%;">Terima kasih</P>  
</div>
</div>
 <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
