<script>
import Header from "../components/Header.svelte"
import Footer from "../components/Footer.svelte"

</script>
  
<svelte:head>
  <link rel="stylesheet" href="../css/base.css?var=1.02">
  <link rel="stylesheet" href="../css/layout.css?var=1.02">
  <link rel="stylesheet" href="../css/main.css?var=1.00">
  <link rel="stylesheet" href="../css/prerendering.css?var=1.00">
  <script src="https://webfont.fontplus.jp/accessor/script/fontplus.js?kqbwQX--jVA%3D&box=2bQkUFfZnEc%3D&aa=1&ab=2"></script>
</svelte:head>
  
  <div>

    <Header />
    <slot />
    <Footer />
  </div>
  