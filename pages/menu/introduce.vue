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
            <div class="title">이 사이트는 이런 녀석이 만들었어요</div><br>
            <div class="subtitle">자기 소개</div>
            <div class="hero is-warning">
                <div class="container">
                    안녕하세요. 사이트 제작자 gonewbie입니다.<br>
                    개발자와 함께 성장하는 페이지라는 컨셉으로 포트폴리오 페이지를 제작해 보았습니다.<br><br>
                    개발자 github 주소: <a href="https://github.com/gonewbie">https://github.com/gonewbie</a>
                </div>
            </div>
            <br>
            <div class="subtitle">취미</div>
            <div class="hero is-warning">
                <div class="container">
                    평소에는 주로 음악을 듣거나 코딩을 합니다.<br>
                    음악은 장르 불문하고 듣지만 좋아하는 가수 중 하나는 Radiohead입니다.
                </div>
            </div>
            <br>
            <article class="message is-danger">
            <div class="message-header">
                <p>Radiohead의 참가 음반 (from https://freemusicarchive.org)</p>
            </div>
            <div class="message-body">
                <ol>
                    <li v-for="album in albumList" :key="album">
                        {{album}}
                    </li>
                </ol>
            </div>
        </article>
        </div>
    </div>
  </div>
  </section>
</template>

<script>
import axios from 'axios';

export default {
    data() {
      return {};
    },
    async asyncData() {
    
    const list = await axios.get(`https://freemusicarchive.org/api/trackSearch?q=radiohead&limit=10`);
        return {albumList: list.data.aRows};
    }
}; 
</script>
