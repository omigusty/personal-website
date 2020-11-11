<style>
  .Header {
    background-color: #f8fafc;
    height: 75px;
  }

  .Header-link {
    margin-left: 8px;
    font-size: 14px;
    color: #2779bd;
    font-weight: normal;
  }

  .Header-link:hover {
    background-color: #fff382;
  }

  .active {
    height: 23px;
    width: 38px;
    background-color: #fff382;
    text-align: center;
    align-content: center;
  }

  @media only screen and (max-width: 768px) {
    .Header {
      height: 45px;
      width: 100%;
    }

    .Header-link {
      font-size: 12px;
    }
  }
</style>

<div class="Header d-flex flex-justify-center">
  <div class="Header-item"><a href="/" class="Header-link">Home</a></div>
  <div class="Header-item"><a href="/" class="Header-link">About</a></div>
  <div class="Header-item">
    <a href="/articles" class="Header-link">Articles</a>
  </div>
  <div class="Header-item">
    <a href="/" class="Header-link"><div class="active">Book</div></a>
  </div>
  <div class="Header-item">
    <a href="/newsletter" class="Header-link">Newsletter</a>
  </div>
</div>
