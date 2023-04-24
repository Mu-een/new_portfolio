<template>
  <footer class="container-fluid">
        <div class="footerText text-center">
            <p> &copy; {{ currentYear }} ALL RIGHTS RESERVED</p>
        </div> 
    </footer>
</template>

<script>
    export default {
        name: 'FooterC',
        data(){
        return {
            currentYear : new Date().getFullYear(),
        }
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Urbanist:wght@700&display=swap');

footer {
    font-family: 'Urbanist', sans-serif;
    background-color: #ECF2FF;
    height: 10vh;
    padding: 25px;
}
</style>