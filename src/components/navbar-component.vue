<template>
    <b-navbar toggleable="lg" type="dark" variant="dark">
        <b-navbar-brand href="#">TechShop</b-navbar-brand>
        
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        
        <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
                <b-nav-item href="#" class="active">Home</b-nav-item>
                <b-nav-item href="#">Catalog</b-nav-item>
                <b-nav-item href="#">About Us</b-nav-item>
            </b-navbar-nav>
        </b-collapse>

    </b-navbar>
</template>

<script>
export default {
    name: 'navbar-component'
}
</script>

<style scoped>
    .navbar-collapse {
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
    }
</style>