<template>
  <main>
    <aside class="vh-100 d-flex flex-column justify-content-between p-8">
      <nav>
        <h1 class="mb-8">
          <RouterLink to="/">
            <img src="../assets/img/logo-ANSWER.svg" alt="logo" />
          </RouterLink>
        </h1>
        <ul class="list-unstyled d-flex flex-column gap-6 mb-0">
          <li>
            <RouterLink class="d-flex align-items-center fw-bold" to="/">
              <span class="material-symbols-outlined me-4"> insert_chart </span>
              Dashboard
            </RouterLink>
          </li>
          <li>
            <RouterLink class="d-flex align-items-center fw-bold" to="/">
              <span class="material-symbols-outlined me-4"> forum </span>
              Question
            </RouterLink>
          </li>
          <li>
            <RouterLink class="d-flex align-items-center fw-bold" to="/">
              <span class="material-symbols-outlined me-4"> assignment </span>
              Assignment
            </RouterLink>
          </li>
          <li>
            <RouterLink class="d-flex align-items-center fw-bold" to="/">
              <span class="material-symbols-outlined me-4">
                video_library
              </span>
              Course
            </RouterLink>
          </li>
          <li>
            <RouterLink class="d-flex align-items-center fw-bold active" to="/">
              <span class="material-symbols-outlined me-4"> person </span>
              Admin
            </RouterLink>
          </li>
          <li>
            <RouterLink class="d-flex align-items-center fw-bold" to="/">
              <span class="material-symbols-outlined me-4"> settings </span>
              Settings
            </RouterLink>
          </li>
        </ul>
      </nav>
      <div class="d-flex">
        <img
          class="img-fluid rounded-circle user-img"
          src="../assets/img/andychen.jpeg"
          alt=""
        />
        <div class="ms-4">
          <div class="user-name fw-bold">Andy Chen</div>
          <div class="user-email">andy0401@mail.com</div>
        </div>
      </div>
    </aside>
  </main>
</template>
