<template>
  <div>
    <Header />
    <header>
      <div
        id="carouselExampleIndicators"
        class="carousel slide"
        data-ride="carousel"
      >
        <!-- <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol> -->
        <div class="carousel-inner" role="listbox">
          <!-- Slide One -->
          <div
            class="carousel-item active"
            style="background-image: url('/img/demacia-lor-10.jpg')"
          >
            <div class="carousel-caption d-none d-md-block">
              <h3 class="display-4">Weekly news!</h3>
              <p class="lead">This is a quick description for the news.</p>
            </div>
          </div>
          <!-- Slide Two -->
          <div class="carousel-item" style="background-image: url('')">
            <div class="carousel-caption d-none d-md-block">
              <h3 class="display-4">Second Slide</h3>
              <p class="lead">This is a description for the second slide.</p>
            </div>
          </div>
          <!-- Slide Three -->
          <div class="carousel-item" style="background-image: url('')">
            <div class="carousel-caption d-none d-md-block">
              <h3 class="display-4">Third Slide</h3>
              <p class="lead">This is a description for the third slide.</p>
            </div>
          </div>
        </div>
        <!-- <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a> -->
      </div>
    </header>

    <!-- Page Content -->
    <section class="py-2">
      <div class="container">
        <div>
          <b-card
            title="Ezreal"
            img-src="img/c-o-champion-ezreal-battle-academia-splash.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem"
            class="mb-2"
          >
            <b-card-text>
              some card description
            </b-card-text>

            <b-button href="/cards/detail" variant="primary">See details/Buy</b-button>
          </b-card>
        </div>
        <div>
          <b-card
            title="Aatrox"
            img-src="img/champion-aatrox-splash.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem"
            class="mb-2"
          >
            <b-card-text>
              some card description
            </b-card-text>

            <b-button href="/cards/detail" variant="primary">See details/Buy</b-button>
          </b-card>
        </div>
                <div>
          <b-card
            title="Zed"
            img-src="img/champion-zed-shockblade-splash.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem"
            class="mb-2"
          >
            <b-card-text>
              some card description
            </b-card-text>

            <b-button href="/cards/detail" variant="primary">See details/Buy</b-button>
          </b-card>
        </div>
                <div>
          <b-card
            title="Zoe"
            img-src="img/champion-classic-zoe-splash.jpg"
            img-alt="Image"
            img-top
            tag="article"
            style="max-width: 20rem"
            class="mb-2"
          >
            <b-card-text>
              some card description
            </b-card-text>

            <b-button href="/cards/detail" variant="primary">See details/Buy</b-button>
          </b-card>
        </div>
        
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style>
.container {
  display: flex;
}
.container > div {
  margin: 5px;
}
.carousel-item {
  height: 65vh;
  min-height: 350px;
  background: no-repeat center center scroll;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
</style>
