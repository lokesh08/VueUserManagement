<template>
    <nav class="col-md-2 d-none d-md-block bg-light sidebar">
        <div class="sidebar-sticky">
            <ul class="nav flex-column">
                <li class="nav-item">
                    <router-link to="/users/create" class="dropdown-item">Create</router-link>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Orders
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Products
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Customers
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Reports
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Integrations
                    </a>
                </li>
            </ul>

            <h6 class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted">
                <span>Saved reports</span>
                <a class="d-flex align-items-center text-muted" href="#">
                    
                </a>
            </h6>
            <ul class="nav flex-column mb-2">
                <li class="nav-item">
                    <a class="nav-link" href="#">
                    
                        Current month
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                    
                        Last quarter
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Social engagement
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">
                        
                        Year-end sale
                    </a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "Sidebar"
    }
</script>

<style scoped>

</style>