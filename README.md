# Animated-login-window

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
             background-color: #898ae4;
             display: flex;
             justify-content: center;
             align-items: center;
             height: 100vh;
        }

        .form{
            width: 350px;
            height: 400px;
            background-color: #fff;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 30px;
            padding-bottom: 50px;
            gap: 10px;
            
            
        }
        .user img{
            width: 50px;
        }
         .field{
            display: flex;
            flex-direction: column;
            width: 100%;
            
         } 
         
         .field input{
            width: 100%;
            outline: none;
            border: 2px solid #93899e91;
            border-radius: 5px;
            padding: 10px;
        
             
         }

         input:focus{
            border-color: #898ae4;
         }
          button{
            border: none;
            outline: none;
            background-color: #898ae4;
            width: 100%;
            padding: 5px;
            color: #fff;
            border-radius: 5px;
            cursor: pointer;
            opacity: 0.8;
          }
          button:hover{
            opacity: 1;
          }

    </style>
</head>
<body>
    <div class="form">

        <div class="user">
            <img src="./user.png" alt="">
        </div>

        <div class="field">
            <label >Email</label>
            <input type="text" placeholder="xyz@gmail.com">
        </div>
        <div class="field">
            <label >password</label>
            <input type="password"="****">
        </div>

        <button>Login</button>
        
    </div>
</body>
</html>
