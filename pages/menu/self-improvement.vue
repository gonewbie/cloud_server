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
            <div class="title">이 녀석은 이런 거도 할 줄 알아요</div>
            <div class="subtitle">자격증</div>
            <div class="hero is-warning">
                <div class="container">
                    JLPT N1 취득<br>
                    TOEIC Score: 825 (만료)
                </div>
            </div>
            <div class="subtitle">어학 능력</div>
            <div class="hero is-warning">
                <div class="container">
                    영어: 영어로 된 문서를 읽고 이를 어느 정도 이해하여 실제 적용이 가능하다.<br>
                    일본어: 일본어로 된 서적을 읽거나 의사소통하는 것이 가능하다.
                </div>
            </div>
        </div>
    </div>
  </div>
  </section>
</template>