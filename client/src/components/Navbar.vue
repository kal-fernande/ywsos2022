<template>
<nav class="navbar navbar-expand-lg bg-light d-flex justify-content-start">
  <div class="container-fluid">
    <a class="navbar-brand" href="/">YWSOS</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link"  :class = "{'active':$route.path.includes('register')}" aria-current="page" href="/register">Register</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" :class = "{'active':$route.path.includes('login')}" href="/login">Login</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>