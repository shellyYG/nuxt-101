<template>
  <h2>Home page of Nuxt</h2>
</template>

<script>
export default {
    head() {
        return {
            title: 'Welcome to the page',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'Best place to learn nuxt'
                }
            ]
        }
    }

}
</script>
