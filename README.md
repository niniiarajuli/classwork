<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="mystyle.css">
    <style>
      *{
          background-color: beige;
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
