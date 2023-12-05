<script>
import Header from "../components/Header.svelte"
import Footer from "../components/Footer.svelte"

</script>
  
<svelte:head>
  <link rel="stylesheet" href="../css/base.css?var=1.01">
  <link rel="stylesheet" href="../css/layout.css?var=1.01">
  <link rel="stylesheet" href="../css/main.css?var=1.00">
  <link rel="stylesheet" href="../css/prerendering.css?var=1.00">

</svelte:head>
  
  <div>

    <Header />
    <slot />
    <Footer />
  </div>
  