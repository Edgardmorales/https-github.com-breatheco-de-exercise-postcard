# https-github.com-breatheco-de-exercise-postcard
tarjeta postal MG
<!DOCTYPE html>
<html lang="ES">
<head>
    <meta charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document three</title>
    <link rel="stylesheet" href="./style.css"/>
</head>
<body>
    <div class="Postcard">
        <div class="postcard-header">
            <h1> My Postcard </h1>
            <img 
                 src="https://storage.googleapis.com/replit/images/1511936948186_53605a1f8e2f117b874504a42b735a7f.png"/>
        </div>
        <div class="postcard-body">
            <div class="postcard-left">
                 <p>look how awesome! this is a postcard that l created using HTML5 and CSS3 during my 4 geeks academy course! ,</p>
                 <p> this is so cool,can´t wait to start doing more stuff </p>
            </div>
            <div class="body-right">
                 <input type="text" placeholder="Some Name"/>
                 <input type="text" placeholder="Some Email"/>
                 <input type="text" placeholder="Some Comment/">
            </div>
        </div>
        <div class="postcard-footer">
            <button>Send My Postcard</button>==17600
        </div>
    </div>
</body>
</html>


body{
    background: black; 
    fond-family: "open sans condensed", sans-serif; 
}
.postcard{
    width: 400px;
    height: 600px;
    background: white;
    margin:auto;
}
.postcard-header{
    display:flex;
    padding:10px;
}
.postcard-header h1 {
    width:100;
    margin:0
    padding-top 10px;
}
.postcard-header img {
    width:50px;
    height:50px;
}
.postcard-body{
    display: flex;
}
.body-left p:first-child {
    margin-top:o;
}
.body-left,
.body-right{
    padding:10px
}
imput{
    border:none;
    border-bottom:1px grey solid;
}
.poscard-footer{
    text-align:center;
}
button{
    background-color: white;
    padding:5px 10px;
    border:none;
}


  

