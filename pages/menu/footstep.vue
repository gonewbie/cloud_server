<template>
  <section class="section">
  <div class="columns">
    <div class="column is-one-fifth">
      <aside class="menu">
      <p class="menu-label">소개</p>
      <ul class="menu-list">
        <li><nuxt-link to="/menu/introduce">자기 소개</nuxt-link></li>
        <li><nuxt-link to="/menu/introduce">취미</nuxt-link></li>
      </ul>
      <p class="menu-label">발자취</p>
      <ul class="menu-list">
        <li><nuxt-link to="/menu/footstep">과거</nuxt-link></li>
        <li><nuxt-link to="/menu/footstep">현재</nuxt-link></li>
        <li><nuxt-link to="/menu/footstep">향후 계획</nuxt-link></li>
      </ul>
      <p class="menu-label">자기 계발</p>
     <ul class="menu-list">
        <li><nuxt-link to="/menu/self-improvement">자격증</nuxt-link></li>
       <li><nuxt-link to="/menu/self-improvement">어학</nuxt-link></li>
     </ul>
    </aside>
    </div>
    <div class="column">
        <div class="container">
            <div class="title">이 개발자의 족적(Footstep)</div><br>
            <div class="subtitle">과거</div>
            <div class="hero is-warning">
                <div class="container">
                    LED 테트리스<br>
                    스마트 엘리베이터<br>
                </div>
            </div>
            <br>
            <div class="subtitle">현재</div>
            <div class="hero is-warning">
                <div class="container">
                    EYE-TOUCH (초보부모들을 의한 영유아 행동분석 장치)
                </div>
            </div>
            <br>
            <div class="subtitle">향후 계획</div>
            <div class="hero is-warning">
                <div class="container">
                    IPP 연계 Internship 예정
                </div>
            </div>
        </div>
    </div>
  </div>
  </section>
</template>