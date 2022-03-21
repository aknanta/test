<template>
    <footer>
        <p>© 2021 ELEMES ID.ALL RIGHTS RESERVED</p>
    </footer>
</template>

<script>
export default ({
    name: 'Footer'
})
</script>


<style scoped>
footer{
    padding: 20px;
}
footer p{
    text-align: center;
}
@media screen and (max-width: 480px) {
    footer{
        display: none;
    }
}
</style>