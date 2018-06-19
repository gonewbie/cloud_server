<template>
  <div>
    <div class="hero is-dark">
      <div class="hero-head">
        <div class="container">
          <nav class="navbar">
            <div class="navbar-brand">
              <nuxt-link to="/" class="navbar-item">
                Main
              </nuxt-link>
              <span class="navbar-burger burger" data-target="navbarMenuHeroB">
                <span></span>
                <span></span>
                <span></span>
              </span>
        </div>
        <div id="navbarMenuHeroB" class="navbar-menu">
          <div class="navbar-end">
            <nuxt-link to="/menu/introduce" class="navbar-item is-active">
              소개
            </nuxt-link>
            <nuxt-link to="/menu/footstep" class="navbar-item">
              발자취
            </nuxt-link>
            <nuxt-link to="/menu/self-improvement" class="navbar-item">
              자기 계발
            </nuxt-link>
          </div>
            </div>
          </nav>
        </div>
      </div>
      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title">First Step</h1>
          <h2 class="subtitle">My portfolio</h2>
        </div>
      </div>
    </div>
    <nuxt/>
      <footer class="footer has-text-centered">
        <p>2018</p>
      </footer>
  </div>
</template>