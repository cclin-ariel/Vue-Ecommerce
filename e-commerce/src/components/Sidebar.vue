<template>
  <nav
    id="sidebarMenu"
    class="col-md-3 col-lg-2 d-md-block bg-light sidebar collapse"
  >
    <div class="position-sticky pt-3">
      <h6
        class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted"
      >
        <span>Order Managment</span>
        <a class="link-secondary" href="#" aria-label="Add a new report">
          <span data-feather="plus-circle"></span>
        </a>
      </h6>
      <ul class="nav flex-column mb-2">
        <li class="nav-item">
          <router-link to="/admin/products" class="nav-link" href="#">
            <span data-feather="file-text"></span>
            <i class="fas fa-box-open"></i>
            Product List
          </router-link>
        </li>
        <li class="nav-item">
          <router-link to="/admin/order_list" class="nav-link" href="#">
            <span data-feather="file-text"></span>
            <i class="far fa-list-alt"></i>
            Order List
          </router-link>
        </li>

        <li class="nav-item">
          <router-link to="/admin/coupon_list" class="nav-link" href="#">
            <span data-feather="file-text"></span>
            <i class="fas fa-ticket-alt"></i>
            Coupon List
          </router-link>
        </li>
      </ul>
      <h6
        class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted"
      >
        <span>Simulation</span>
        <a class="link-secondary" href="#" aria-label="Add a new report">
          <span data-feather="plus-circle"></span>
        </a>
      </h6>
      <ul class="nav flex-column mb-2">
        <li class="nav-item">
          <router-link to="/customer_orders" class="nav-link" href="#">
            <span data-feather="file-text"></span>
            <i class="far fa-list-alt"></i>
            Cumstomer Order
          </router-link>
        </li>
      </ul>
      <h6
        class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted"
      >
        <span>Official Release</span>
        <a class="link-secondary" href="#" aria-label="Add a new report">
          <span data-feather="plus-circle"></span>
        </a>
      </h6>
      <ul class="nav flex-column mb-2">
        <li class="nav-item">
          <router-link to="/customer_home" class="nav-link" href="#">
            <span data-feather="file-text"></span>
            <i class="fas fa-sitemap"></i>
            Home
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
