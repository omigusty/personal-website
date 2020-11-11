<script>
  import Footer from "../Components/Footer.svelte";
  import Header from "../Components/Header.svelte";
</script>

<style>
  h2 {
    color: #152c5b;
    font-size: 24px;
    font-weight: 700 !important;
  }

  p {
    margin-top: 25px;
    font-size: 16px;
    line-height: 30px;
    font-weight: 100 !important;
    color: #3d4852;
    word-spacing: 2px;
  }

  .the-best {
    margin-top: 50px;
    margin-bottom: 15px;
  }

  .profile-photo {
    width: 64px;
    height: 64px;
    border-radius: 50%;
  }

  h4 {
    font-size: 16px;
    margin-top: 50px;
    font-weight: 400;
    word-spacing: 4px;
    color: #b8c2cc;
    margin-bottom: 15px;
  }

  li {
    height: 56px;
    width: 334px;
  }

  .no-symbol {
    list-style-type: none;
  }

  .title-articles {
    color: #2779bd;
    font-size: 16px;
    line-height: 25px;
  }

  .title-articles a {
    text-decoration: none;
  }
  .title-articles a:hover {
    background-color: #fff382;
  }

  .icon img {
    width: 17px;
    color: #2779bd;
    margin-bottom: -12px;
  }

  .icon p {
    color: #2779bd;
    margin-left: 15px;
  }

  .icon a {
    text-decoration: none;
  }

  .icon p:hover {
    background-color: #fff382;
  }

  .icon {
    height: 30px;
    margin-left: 20px;
  }

  h6 {
    color: #ffff;
    font-size: 16px;
    font-weight: 100;
    margin-bottom: 20px;
  }

  .btn-large {
    height: 45px;
    width: 95px;
    background-color: #fff382;
    font-size: 16px;
    font-weight: 600;
    text-align: center;
    margin-left: 20px;
    border-radius: 6px;
    padding-left: 12px;
    color: rgb(94, 76, 54);
  }

  .form-control {
    height: 45px;
    width: 220px;
  }

  .bg-gray-dark {
    transform: rotate(-5deg);
    margin-bottom: 50px;
    width: 536px;
    margin-left: 3px !important;
  }

  .title-best-published {
    margin-left: 35px;
  }

  .title-best-published a {
    font-size: 16px;
    letter-spacing: 0.2px;
    text-decoration: none;
    color: #2779bd;
  }

  .title-best-published a:hover {
    background-color: #fff382;
  }
  .best-published-articles {
    margin-bottom: 20px;
    width: 480px;
    height: 20px;
  }

  .omi {
    width: 960px;
    margin-top: 50px;
  }

  .best-published-articles:before {
    content: "●"; /* Insert content that looks like bullets */
    color: #000; /* Or a color you prefer */
    margin-right: 10px;
    width: 10px;
  }

  ul {
    list-style-type: none;
  }

  @media only screen and (max-width: 768px) {
    .omi {
      width: 100%;
    }

    p {
      font-size: 12px;
      line-height: 22px;
      margin-top: 18px;
    }

    h2 {
      font-size: 22px;
    }

    h4 {
      font-size: 14px;
      margin-top: 30px;
      font-weight: 500;
      margin-bottom: 10px;
    }

    li {
      height: 56px;
      width: 165px;
      margin-bottom: -5px;
    }

    .title-articles {
      font-size: 12px;
      line-height: 20px;
    }

    .omi {
      margin-top: 30px;
    }

    .profile-photo {
      width: 50px;
      height: 50px;
    }

    .social-media {
      display: none;
    }

    .no-symbol li {
      height: 75px;
    }

    .p {
      margin-top: 15px;
    }

    .best-published-articles {
      margin-top: 30px;
      width: 170px;
      list-style-type: disc;
    }

    .best-published-articles a {
      font-size: 12px;
    }

    .best-published-articles:before {
      display: none;
    }

    .email-octopus {
      display: none;
    }
  }
</style>

<!-- Start Header -->
<Header />
<!-- End Footer -->
<section class="d-flex flex-justify-center">
  <div class="d-flex flex-justify-center omi">
    <div class="col-5 float-left">
      <img src="/assets/img/profile-photo.jpg" class="profile-photo" alt="" />
      <h4 class="p">RECENT ARTICLES</h4>
      <ul>
        <li class="d-flex flex-items-center title-articles">
          <a href="">Mengenal Svelte,Sebuah Komponen Framework</a>
        </li>
        <li class="d-flex flex-items-center title-articles">
          <a href="">Setup Windows Bagian Pertama</a>
        </li>
        <li class="d-flex flex-items-center title-articles">
          <a href="">Panduan Melakukan Persentasi Online</a>
        </li>
      </ul>
      <!-- Start On The Web -->
      <h4>ON THE WEB</h4>
      <ul class="no-symbol">
        <li>
          <div class="d-flex flex-items-center icon">
            <a href="https://www.instagram.com/omigusty.r"><img
                src="/assets/img/instagram.svg"
                alt="" /></a>
            <a
              href="https://www.instagram.com/omigusty.r"
              class="social-media"><p>instagram.com/omigusty.r</p></a>
          </div>
        </li>
        <li>
          <div class="d-flex flex-items-center icon">
            <a href="https://github.com/omigusty/"><img
                src="/assets/img/github.svg"
                alt="" /></a>
            <a href="https://github.com/omigusty/" class="social-media"><p>
                github.com/omigusty
              </p></a>
          </div>
        </li>
        <li>
          <div class="d-flex flex-items-center icon">
            <a
              href="https://emailoctopus.com/lists/2c7f8874-fc08-11ea-a3d0-06b4694bee2a/forms/subscribe"><img
                src="/assets/img/email.svg"
                alt="" /></a>
            <a
              href="https://emailoctopus.com/lists/2c7f8874-fc08-11ea-a3d0-06b4694bee2a/forms/subscribe"
              class="social-media"><p>Email Newsletter</p></a>
          </div>
        </li>
      </ul>
    </div>
    <div class="col-7 float-right">
      <h2>Hi, I'm Gusty.</h2>
      <!-- <p>
        Sekarang saya adalah murid kelas 12 di SMKN 1 banyuwangi.mengambil
        jurusan Rekayasa Perangkat Lunak,dan disinilah awal pertama kali saya
        mengenal dunia pemograman.
      </p>
      <p>
        Pertama kali mengenal pemograman saat saya duduk di bangku kelas 1
        SMK,saat itu bahasa pemograman yang diajarkan adalah C++."Rumit..."ya
        itulah yang saya rasakan saat pertama kali ngoding,tetapi saat berhasil
        membuat program akan ada kepuasaan tersendiri yang membuat kita untuk
        terus belajar di pemograman.
      </p>
      <p class="mb-5">
        Lanjut di kelas 2 smester I,saat itu kami diajarkan bahasa pemograman
        Java,menurut saya Java lebih mudah daripada C++,karena kemudahan itulah
        saya tertarik untuk belajar lebih dalam tentang pemograman.Hingga pada
        akhirnya saat kelas 2 semester II sampai saat ini saya cenderung
        menyukai pemograman web khususnya disisi Frontend.
      </p> -->
      <div class="bg-gray-dark p-3 mt-n3 ml-n3 mr-n3 email-octopus">
        <h6>
          Ocassionally, I send an email to my list. I talk about all
          tech-related, making stuff, tips and tricks for developers, and
          interesting events.
        </h6>
        <form action="">
          <input class="form-control" type="email" placeholder="me@email.com" />
          <a
            href="https://emailoctopus.com/lists/2c7f8874-fc08-11ea-a3d0-06b4694bee2a/forms/subscribe"
            class="btn btn-large"
            type="submit">Subscribe</a>
        </form>
      </div>

      <p>
        Awal mula menyukai pemograman web saat kami diberi tugas membuat website
        untuk kenaikan kelas,menurut saya yang membuat pemograman web menarik
        adalah code yang kita tulis hasilnya dapat dilihat langsung di web
        browser.Sejak saat itulah saya menyukai pemograman
      </p>

      <p>
        Bagi saya pemograman adalah gaya hidup tentang bagaimana kita menemukan
        masalah dan mencari solusi dari masalah tersebut
      </p>
      <h2 class="the-best">The Best Things I've Published</h2>

      <div>
        <ul class="title-best-published">
          <li class="best-published-articles">
            <a href="">Mengenal Svelte,Sebuah Komponen Framework</a>
          </li>
        </ul>
        <ul class="title-best-published">
          <li class="best-published-articles">
            <a href="">Setup Windows Bagian Pertama</a>
          </li>
        </ul>
        <ul class="title-best-published">
          <li class="best-published-articles">
            <a href="">Panduan Melakukan Persentasi Online</a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</section>

<Footer />
