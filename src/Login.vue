<template>
    <div>
    <h1>Hello Guys</h1>
    <h2>How are you all!!!</h2>
    <h3>Please Login here!!</h3>
    <form action="/" method="POST">
        <label for="email"> Email</label><input name="email" class="email" type="email">
        <br>
        <br>
        <label for="password"> Password</label><input name="password" class="password" type="password">
        <br>
        <br>
        <button type="submit">Login</button>
    </form>
    </div>
</template>

<script>
export default {
    name:"App1",
}
</script>