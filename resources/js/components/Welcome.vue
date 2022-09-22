<template>
    <div class="d-flex flex-column w-100 align-items-center text-warning p-5">
        <h1 class="" >{{ title }}</h1>
        <p class="fs-3 text">{{ message }}</p>
    </div>


</template>
<script>
export default {
    setup: () => ({
        title: 'Vue, Laravel, and bootStrap ',
        message: 'This is a simple example of how to use Vue 3 in Laravel 8 with Bootstrap 5.2.1'
    })
}
</script>
