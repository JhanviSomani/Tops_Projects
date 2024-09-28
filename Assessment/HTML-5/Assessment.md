```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .navbar{
            display: flex;
            justify-content: space-between;
            padding: 2rem 2.5rem;
            background-color: rgb(38, 97, 156);
        }
        nav .links {
            display: flex;
            flex-direction: row;
            justify-content: space-evenly;
            gap: 2rem;
            cursor: pointer;
        }
        nav .links a{
            text-decoration: none;
            color: white;
            font-size: 1.2rem;
            font-weight: 600;
            font-family: Arial, Helvetica, sans-serif;
        }
        nav .links button {
            border: none;
            background: transparent;
            color: white;
            font-size: 1.2rem;
            font-weight: 600;
            font-family: Arial, Helvetica, sans-serif;
            cursor: pointer;
        }
        .btn-content{
            display: none;
            position: absolute;
            background-color: rgb(38, 97, 156);
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
        }
        .btn-content a{
            color: white;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: center;
        }
        .btn-content .more {
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .btn-content .more i{
            margin-left: 0.3rem;
            margin-top: 0.1rem;
        }
        .btn-content .more{
            color: white;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: center;
            display: flex;
            
        }
        .btn-content a:hover{
            background-color: rgb(53, 52, 167);
        }
        .btn-content .more:hover{
            background-color: rgb(53, 52, 167);
        }
        .Services:hover .btn-content{
            display: block;
        }
        .Services:hover .more-content{
            display: none;
        }
        .more-content{
            display: block;
            position: absolute;
            left: 10.6rem;
            top: 8.6rem;
            background-color: rgb(38, 97, 156);
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
            
        }
        .more:hover .more-content{
            display: block;
            
        }
        .Services i{
            display: none;
        }
       .Services:hover i{
            display: inline;
       }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="logo">
            <img src="" alt="Image not found">
        </div>
        <nav>
            <div class="links">
                <a href="">Home</a>
                <a href="">About</a>
                <div class="Services">
                    <button class="btn">Services <i class="fa-solid fa-caret-down"></i> </button>
                    <div class="btn-content">
                        <a href="#">Web Designing</a>
                        <a href="#">Marketing</a>
                        <a href="#">Wordpress</a>
                        <div class="more">
                        <button class="More">More<i class="fa-solid fa-arrow-right"></i></button>
                       
                        <div class="more-content">
                            <a href="">HTML</a>
                            <a href="">CSS</a>
                            <a href="">Javascript</a>
                            <a href="">jQuery</a>
                        </div>
                        </div>
                       </div>
                </div>
                <a href="">Blogs</a>
                <a href="">Contact</a>
                <button>Login</button>
            </div>
        </nav>
    </div>
        
    </div>
</body>
</html>
```
