<template>
    <h1>Sign Up</h1>
    <img src="../assets/cactus.png" alt="logo of signup" class="logo">
    <div class="register">
        <input type="text" placeholder="Your Name">
        <br>
        <input type="text" placeholder="Your Email">
        <button>Sign Up</button>
    </div>
</template>
<script>
export default{
    name:'SignUp'
}
</script>
<style>
.logo{
    width:200px;
    height: 100px;
};
.register{
    width: 300px;
    height: 40px;
    padding: 20px;
    display: block;
}
</style>