
<script>
export default {
    props:{loginOrRegister:Boolean}
}
</script>

<template>
    <div class="app">
            <form action="" method='POST' class='login-card'>
                <h1>{{loginOrRegister ? 'Login' : 'Register' }}</h1>
                <h2><label for="username">Username:</label>
                    <br>
                    
                    <input type="username" name='username'></h2>
                <h2><label for="password">Password:</label><br>
                    <input type="password" name='password'></h2>
                <button type='submit' value='submit'>Submit</button>
            </form>
    </div>
</template>

<style>

.app{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    width: 100%;
}

.login-card{
    display: flex;
    flex-direction: column;
    align-items: center;
    border: solid 1px white;
    border-radius: 5px;
    height: 400px;
    width: 400px;
    justify-content: center;
    align-items: center;
    margin-bottom: 150px ;
}

input{
    height: 25px;
    width: 320px;
    font-size: 0.8em;
}
</style>
