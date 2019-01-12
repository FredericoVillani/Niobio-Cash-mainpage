<template>
    <div>
        <div id="wrapper" class="pb-5">
            <slot></slot>
        </div>
        <footer class="container-fluid mt-3 py-4 px-5">
            <div class="row text-center">
                <div class="col-12">
                    <a class="p-0 pr-2" href="mailto:contato@niobiocash.com">Contact us</a>
                </div>
                <div class="col-12 mt-2">
                    <p class="text-white m-0">Copyright 2019 Niobio Cash, all rights reserved</p>
                </div>
            </div>
        </footer>
    </div>
</template>

<script>
    export default {
        name: "MainLayout"
    }
</script>
