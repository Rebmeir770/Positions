# Positions
positions
html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Positioning</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <div class="mega-wrapper">
    <div class="wrapper">

       <div class="box"></div>
       <div class="box move">+</div>
       <div class="box move2"></div>
       <div class="box"></div>
       <div class="box "></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box"></div>
       <div class="box stiky "></div>
       <div class="box"></div>
       <div class="box"></div>

       


    </div>
    </div>
</body>

</html>


css:

.mega-wrapper{
    position: relative;
    border: 1px dashed gray;
    width: 200px;
    margin: auto;
}
.wrapper{

    
    border: 1px solid gray;
    background-color: wheat;
    width: fit-content;
    margin: auto;
    
}
.box{
    width: 100px;
    height: 100px;
    background-color: rgb(0, 205, 205);
    border: 1px solid green;
}
.move2{
    position: fixed;
    top: 0px;
    left: 0px;
    width: 100vw;
    background-color: orange;
}
.move{
    position: fixed;
    bottom: 16px;
    right: 16px;
    color: white;
    background-color: rgb(0, 47, 255);
    border-radius: 100px;
    width: 50px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 3rem;    
}
.stiky{
    position: sticky;
   bottom: 0px;
    background-color: rgb(255, 217, 0);
}


