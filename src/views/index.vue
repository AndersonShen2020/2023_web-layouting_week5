<template>
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
            <span class="material-symbols-outlined me-4"> video_library </span>
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
        class="img-fluid object-fit-cover rounded-circle user-img"
        src="../assets/img/andychen.jpeg"
        alt=""
      />
      <div class="ms-4">
        <div class="user-name fw-bold">Andy Chen</div>
        <div class="user-email">andy0401@mail.com</div>
      </div>
    </div>
  </aside>
  <main>
    <header>
      <div class="container">
        <header class="d-flex justify-content-between py-8">
          <div class="d-flex align-items-center">
            <h2 class="fw-bold mb-0 me-12">Admin</h2>
            <div class="d-flex align-items-center">
              <span class="material-symbols-outlined text-success me-2">
                add
              </span>
              <button class="btn btn-add fw-bold">Add New Admin</button>
            </div>
          </div>
          <ul class="list-unstyled d-flex align-items-center gap-6 mb-0">
            <li>
              <RouterLink to="/">
                <span class="material-symbols-outlined"> search </span>
              </RouterLink>
            </li>
            <li>
              <RouterLink to="/">
                <span class="material-symbols-outlined">
                  notifications_active
                </span>
              </RouterLink>
            </li>
          </ul>
        </header>
      </div>
    </header>
    <div class="container">
      <table class="table table-hover">
        <thead>
          <tr>
            <th scope="col" class="d-flex align-items-center gap-1">
              ID <span class="material-symbols-outlined icon"> south </span>
            </th>
            <th scope="col">Name</th>
            <th scope="col">Email</th>
            <th scope="col">Verified</th>
            <th scope="col"></th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">#1</th>
            <td>Emir Wicks</td>
            <td>emir.wicks@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#2</th>
            <td>Zaina Goldsmith</td>
            <td>zaina.goldsmith@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#3</th>
            <td>Mahima Lopez</td>
            <td>mahima.lopez@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#4</th>
            <td>Pharrell Murray</td>
            <td>pharrell.murray@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#5</th>
            <td>Annika Mcbride</td>
            <td>annika.mcbride@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#6</th>
            <td>Fatimah Clark</td>
            <td>fatimah.clark@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#7</th>
            <td>Klaudia Rhodes</td>
            <td>klaudia.rhodes@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#8</th>
            <td>Tillie Lucero</td>
            <td>tillie.lucero@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#9</th>
            <td>Sabrina Stephenson</td>
            <td>sabrina.stephenson@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
          <tr>
            <th scope="row">#10</th>
            <td>Annie Smith</td>
            <td>annie.smith@mail.com</td>
            <td>Yes</td>
            <td class="d-flex justify-content-end align-items-center gap-6">
              <span class="material-symbols-outlined"> visibility </span>
              <span class="material-symbols-outlined"> edit </span>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="container">
      <nav aria-label="Page navigation" class="mt-16">
        <ul class="pagination justify-content-end">
          <li class="page-item">
            <RouterLink class="page-link" to="/" aria-label="Previous">
              <span class="material-symbols-outlined"> chevron_left </span>
            </RouterLink>
          </li>
          <li class="page-item">
            <RouterLink class="page-link active" to="/">1</RouterLink>
          </li>
          <li class="page-item">
            <RouterLink class="page-link" to="/">2</RouterLink>
          </li>
          <li class="page-item">
            <RouterLink class="page-link" to="/">3</RouterLink>
          </li>
          <li class="page-item">
            <RouterLink class="page-link" to="/" aria-label="Next">
              <span class="material-symbols-outlined"> chevron_right </span>
            </RouterLink>
          </li>
        </ul>
      </nav>
    </div>
  </main>
</template>
