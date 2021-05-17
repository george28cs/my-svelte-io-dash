<script>

</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:wght@300&display=swap');  
    .Login {
        display: flex;
        height: 50%;
        width: 40%;
        background-color: rgba(255, 255, 255, 0.11);
        border-radius: 30px;
        justify-content: center;
        align-self: center;
        margin-top: 3rem
    }
    form {
        display: inline-flex;
        flex-direction: column;
        align-items: center;
    }
    .login-tittle {
        padding-top: 20px;
        padding-bottom: 30px;
    }

    .login-tittle h1 {
        text-align: center;
        font-family: 'Open Sans Condensed', sans-serif;
        font-weight: bold;
        color: white;
    }

    label {
        font-size: 10px;
        color: white;
        text-align: center;
        padding-bottom: 5px;
        padding-top: 10px;
    }
    form input {
        max-width: 80%;
        width: 90%;
    }
    form button {
        margin-top: 20px;
        width: 40%;
        background: rgb(18, 63, 122);
        color: rgb(214, 208, 208);
        border: none;
        font-size: 14px;
        font-weight: 650;
        border-radius: 3px;
    }
</style>


<div class="Login">
<!--     <img src="./logo.png" alt="">
 -->    <form>
        <div class="login-tittle">
            <h1> Automation.io </h1>
        </div>
        <label for="email"> E-MAIL </label>
        <input type="text" name="email" id="" placeholder="email@domain.com">
        <label for="password"> PASSWORD </label>
        <input type="text" name="password" id="" placeholder="your password">
        <button>LOG IN</button>
    </form>
</div>