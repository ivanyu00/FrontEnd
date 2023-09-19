<template>
            <nav class="main-header navbar navbar-expand navbar-white navbar-light">

<ul class="navbar-nav">
    <li class="nav-item">
        <a class="nav-link" data-widget="pushmenu" href="#" role="button"><i class="fas fa-bars"></i></a>
    </li>
</ul>



<div class="navbar-collapse collapse w-100 order-3 dual-collapse2">
        <ul class="navbar-nav ml-auto">
            <li class="nav-item dropdown">
        <a class="nav-link" data-toggle="dropdown" href="#">
            <button type="button" class="btn btn-block btn-outline-secondary btn-sm">Role</button>
        </a>
        <div class="dropdown-menu dropdown-menu-right">
            <a href="#" class="dropdown-item">
                <i class="fas fa-user mr-2"></i> Pulami Admin
            </a>
            <div class="dropdown-divider"></div>
            <a href="#" class="dropdown-item">
                <i class="fas fa-user mr-2"></i> Coordinator
            </a>
            <div class="dropdown-divider"></div>
            <a href="#" class="dropdown-item">
                <i class="fas fa-user mr-2"></i> Supervisor
            </a>
           
        </div>
    </li>

            <li class="nav-item dropdown">
        <a class="nav-link" data-toggle="dropdown" href="#">
            <i class="far fa-user"></i>
        </a>
        <div class="dropdown-menu dropdown-menu-right">
            <a href="#" class="dropdown-item">
                <i class="fas fa-user mr-2"></i> My Profile
            </a>
            <div class="dropdown-divider"></div>
            <a href="/login" class="dropdown-item">
                <i class="fas fa-sign-out-alt mr-2"></i> Logout
            </a>
           
        </div>
    </li>
        </ul>
    </div>



</nav>
</template>