<template>
  <b-container>
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="/profile">岡田 譜彦のページ</b-navbar-brand>
    </b-navbar>
    <b-navbar toggleable="lg" type="dark" variant="info">
   <b-navbar-brand href="/profile">岡田 譜彦のページ</b-navbar-brand>
   <b-navbar-nav>
    <b-nav-item href="https://www.vantan-game.com/">バンタンのWebページ</b-nav-item>
   </b-navbar-nav>
  </b-navbar>

    <p>私の通っている学校はバンタンゲームアカデミーで、学科はゲームプログラム総合です。</p>
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