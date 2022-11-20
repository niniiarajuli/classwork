<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            background-color: lightgray;
        }
            div{
                margin: 15px;
                border:3px solid black ; 
                font-size: 25px;
                height: auto;
    
            }
            #header{
                background-color: rgb(131, 133, 132);
            }
    
            #sidebarR{
                background-color: rgb(182, 133, 133);
                float: right;
                width: 100px;
            }
            
            #sidebarL{
                background-color: rgb(121, 96, 96);
                float: left;
                width: 100px;
            }
            #main{
                background-color: rgb(3, 104, 138);
                height: 180px;
                margin-right: 130px;
                margin-left: 130px;
            }
            #footer{
                background-color: rgb(155, 211, 155);
            
            }
    
            img{
                border-radius: 50%;
            }
    
            .centre{
                display: block;
                margin-left: auto;
                margin-right: auto;
            }
    
        </style>
</head>
<body>
    <div class="box">
        <form action="action_page.php">
      
          <label for="firstname">სახელი</label>
          <input type="text" id="firstname" name="First Name" placeholder="შენი სახელი..">
      
          <label for="lastname">გვარი</label>
          <input type="text" id="lastname" name="Last Name" placeholder="შენი გვარი..">
      
          <label for="ქვეყანა">ქვეყანა</label>
          <select id="ქვეყანა" name="ქვეყანა">
            <option value="Georgia">Georgia</option>
            <option value="Russia">Russia</option>
            <option value="Usa">USA</option>
          </select>
      
          <label for="subject">კომენტარი</label>
          <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
      
          <input type="submit" value="Submit">
      
        </form>
      </div>
</body>
</html>
