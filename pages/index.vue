<template>
  <div class="is-dark">
    <section class="hero is-large is-dark">
      <div class="hero-head">
        <nav class="navbar">
          <div class="container">
            <div class="navbar-brand">
              <span class="navbar-burger burger" data-target="navbarMenuHeroB">
                <span></span>
                <span></span>
                <span></span>
              </span>
            </div>
            <div id="navbarMenuHeroB" class="navbar-menu">
              <div class="navbar-end">
                <span class="navbar-item">
                  <a
                    class="button  is-primary  has-text-centered"
                    href="https://gitcoin.co/grants/451/future-bank-is-lego-bank?tab=description"
                  >
                    <span>Donate</span>
                  </a>
                </span>
              </div>
            </div>
          </div>
        </nav>
      </div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <p class="title is-primary">
            FutureBank
          </p>
          <figure>
            <p>
              <img
                src="https://avatars2.githubusercontent.com/u/60450216?s=200&v=4"
                alt="FutureBank"
                class="center-image is-64x64"
              />
            </p>
          </figure>

          <p class="subtitle">
            A bank or a lego? You in control.
          </p>
        </div>
      </div>
    </section>
    <footer class="footer is-dark">
      <div class="content has-text-centered is-pink">
        <p>
          <strong>FutureBank</strong> by
          <a href="https://twitter.com/codingsh">@codingsh</a>.
        </p>
      </div>
    </footer>
  </div>
</template>
<style lang="scss">
.futurebank {
  font-family: Tomorow;
  color: #fe65c4;
}
.hero-image {
  background-image: url('https://images.unsplash.com/photo-1501549629324-babe362ea542?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1950&q=80');
}
.center-image {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  max-width: 6%;
  margin-bottom: 10px;
}
</style>
<script>
import Hero from '../components/Hero'
import Footer from '../components/Footer'

export default {
  Hero,
  Footer
}
</script>
