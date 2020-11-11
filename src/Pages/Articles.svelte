<script>
  import Header from "../Components/Header.svelte";
  import Footer from "../Components/Footer.svelte";
</script>

<style>
  section {
    margin-top: 50px;
  }

  h1 {
    font-size: 32px;
    font-weight: 700;
    text-align: center;
    height: 60px;
  }

  p {
    font-size: 16px;
    line-height: 32px;
    color: #3d4852;
    height: 56px;
  }

  .articles-items {
    margin-left: 20px;
    /* list-style-image: url("/assets/img/email.svg"); */
  }
  .articles {
    width: 960px;
  }

  a {
    font-size: 16px;
    line-height: 32px;
    text-decoration: none;
    color: #2779bd;
  }

  li:before {
    content: "●"; /* Insert content that looks like bullets */
    color: #000; /* Or a color you prefer */
    margin-right: 10px;
    width: 10px;
  }

  ul {
    list-style-type: none;
  }

  @media only screen and (max-width: 768px) {
    h1 {
      font-size: 22px;
    }

    p {
      margin-left: 5px;
    }

    a {
      font-size: 12px;
      line-height: 20px;
    }

    li:before {
      display: none;
    }

    li {
      list-style-type: disc;
      margin-bottom: 16px;
      margin-left: 10px;
    }

    .articles {
      margin-top: -15px;
    }

    .articles-items {
      margin-top: -10px;
    }
  }
</style>

<Header />

<section class="d-flex flex-justify-center">
  <div class="articles">
    <h1>ARTICLES</h1>
    <p class="d-flex flex-items-center">
      Hi, I'm Gusty. These are my articles.
    </p>
    <ul class="articles-items">
      <li type="disc 90px"><a href="">Setup Windows Bagian Pertama</a></li>
      <li><a href="">Panduan Melakukan Presentasi Online</a></li>
      <li><a href=""> Svelte, Sebuah Komponen Framework</a></li>
    </ul>
  </div>
</section>

<Footer />
