<script>
  import About from '$lib/components/about.svelte'
  import Header from '$lib/components/header.svelte'
  import Intro from '$lib/components/intro.svelte'
</script>

<div id="page" class="s-pagewrap">
  <Header />

  <!-- # site-content
    ================================================== -->
  <section id="content" class="s-content">
    <Intro />
    <About />
  </section>
</div>
