<template>
  <div class="container py-4 px-3 mx-auto">
    <nav class="navbar navbar-expand-md bg-primary-subtle">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Titel</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <NuxtLink to="/" class="nav-link" activeClass="active" ariaCurrentValue="page">Ferienwohnung</NuxtLink>
            <NuxtLink to="/anfahrt" class="nav-link" activeClass="active">Anfahrt</NuxtLink>
            <NuxtLink to="/kontakt" class="nav-link" activeClass="active">Kontakt</NuxtLink>
            <NuxtLink to="/impressum" class="nav-link" activeClass="active">Impressum</NuxtLink>
            <NuxtLink to="/datenschutz" class="nav-link" activeClass="active">Datenschutz</NuxtLink>
          </div>
        </div>
      </div>
    </nav>

    <NuxtPage />
    
    <div class="container">
      <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
        <div class="col-md-4 d-flex align-items-center">
          <span class="mb-3 mb-md-0 text-muted">© 2022 Company, Inc</span>
        </div>
    
        <ul class="nav col-md-4 justify-content-end list-unstyled d-flex">
          <li class="ms-3"><a class="text-muted" href="https://www.instagram.com/farmingsimulator/"><Icon name="uil:instagram"/></a></li>
          <li class="ms-3"><a class="text-muted" href="https://www.facebook.com/MakitaDeutschland/"><Icon name="uil:facebook"/></a></li>
        </ul>
      </footer>
    </div>
  </div>
</template>
