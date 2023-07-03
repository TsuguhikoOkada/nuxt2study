<template>
  <b-container>
    <b-navbar toggleable="lg" type="dark" variant="info">
   <b-navbar-brand href="/profile">岡田 譜彦のページ</b-navbar-brand>
   <b-navbar-nav>
    <b-nav-item href="https://www.vantan-game.com/">バンタンのWebページ</b-nav-item>
   </b-navbar-nav>
  </b-navbar>
    <h1>プロフィール情報</h1>
    <b-card img-src="https://placekitten.com/1000/300" img-alt="Card image" img-top>
      <b-card-text>
      私の名前は岡田 譜彦です。 趣味は映画鑑賞で、好きな食べ物はリンゴです。
      </b-card-text>
    </b-card>
    <b-link to="/info/age">年齢情報</b-link>
    <b-link to="/info/school">学校情報</b-link>
  </b-container>
</template>

<script>
import myheader from '~/components/myheader'
export default {
  components: {
    myheader,
  }
}
</script>