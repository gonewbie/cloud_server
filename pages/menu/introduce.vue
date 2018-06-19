<template>
  <section class="section">
  <div class="columns">
    <div class="column is-one-fifth">
      <aside class="menu">
      <p class="menu-label">소개</p>
      <ul class="menu-list">
        <li><nuxt-link to="/menu/introduce">자기 소개</nuxt-link></li>
        <li><a>취미</a></li>
      </ul>
      <p class="menu-label">발자취</p>
      <ul class="menu-list">
        <li><nuxt-link to="/menu/footstep">과거</nuxt-link></li>
        <li><a>현재</a></li>
        <li><a>향후 계획</a></li>
      </ul>
      <p class="menu-label">자기 계발</p>
     <ul class="menu-list">
        <li><nuxt-link to="/menu/self-improvement">자격증</nuxt-link></li>
       <li><a>어학</a></li>
     </ul>
    </aside>
    </div>
    <div class="column">
        <div class="container">
            <div class="title">이 사이트는 이런 녀석이 만들었어요</div>
            <div class="subtitle">자기 소개</div>
            <div class="hero is-warning">
                <div class="container">
                    안녕하세요. 사이트 제작자 gonewbie입니다.<br>
                    개발자와 함께 성장하는 페이지라는 컨셉으로 포트폴리오 페이지를 제작해 보았습니다.<br><br>
                    개발자 github 주소: <a href="https://github.com/gonewbie">주소</a>
                </div>
            </div>
            <div class="subtitle">취미</div>
            <div class="hero is-warning">
                <div class="container">
                    평소에는 주로 음악을 듣거나 코딩을 합니다.
                </div>
            </div>
        </div>
    </div>
  </div>
  </section>
</template>