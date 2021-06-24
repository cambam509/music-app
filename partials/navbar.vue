
<template>
  <header>
    <nav class="navbar navbar-expand-lg navbar-light bg-info">
      <div class="container">
        <a class="navbar-brand" href="/">Music App</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#">Player</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="/manager">Manager</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>
<style scoped>
.nav-link,
.navbar-brand {
  color: #ffff !important;
}
</style>
