<template>
    <div>
        <nav class="navbar navbar-expand-lg fixed-top navbar-light top-nave">
            <router-link class="navbar-brand" to="/">Anime Fiddle</router-link>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item">
                        <router-link class="nav-link" to="/">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/hello">Seasonal Anime</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link class="nav-link" to="/hello">News</router-link>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name : 'navbar',
}
</script>

<style scoped>
.top-nave{
    background-color : var(--main-color);
}

</style>