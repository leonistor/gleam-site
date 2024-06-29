<script>
  import logo from '$lib/assets/logo-gleam-placeholder.svg'
</script>

<header class="s-header">
  <div class="row s-header__inner">
    <div class="s-header__block">
      <div class="s-header__logo">
        <a class="logo" href="index.html">
          <img src={logo} alt="Homepage" />
        </a>
      </div>

      <a class="s-header__menu-toggle" href="#0"><span>Menu</span></a>
    </div>

    <nav class="s-header__nav">
      <ul>
        <li class="current"><a href="#intro" class="smoothscroll">Intro</a></li>
        <li><a href="#about" class="smoothscroll">About</a></li>
        <li><a href="#pricing" class="smoothscroll">Pricing</a></li>
        <li><a href="#download" class="smoothscroll">Download</a></li>
      </ul>
    </nav>

    <div class="s-header__cta">
      <a href="#download" class="btn btn--stroke s-header__cta-btn smoothscroll">Get The App</a>
    </div>
  </div>
</header>
