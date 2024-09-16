**Q-1**:What are the advantages of Bootstrap? 
**Ans**:(1)Speedy Development as it provides ready made components.
(2)Responsive designs by the support of grid system.
(3)Consistent UI Elements as it maintain consistent look.
(4)Cross-Browser Compatibility.

**Q-2**:What is a Bootstrap Container, and how does it work? 
**Ans**:Containers are the most basic layout element in Bootstrap and are required when using our default grid system.
Containers are used to contain, pad, and center the content within them.
There are 3 types of container:
(1)Default container:
```
<div class="container">
  
</div>
```

(2)Responsive Containers:
```
<div class="container-sm"></div>
<div class="container-md"></div>
<div class="container-lg"></div>
<div class="container-xl"></div>
<div class="container-xxl"></div>
```

(3)Fluid containers:
```
<div class="container-fluid">
    
</div>
```

**Q-3**:Create website using bootstrap

**Ans**:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
    <style>
        .cards{
            padding: 50px 150px;
            gap: 150px;
        }
        
        .cards .card img{
            height: 150px;
            width: 150px;
            border-radius: 50%;
            padding: 20px;
            margin-left: 60px;
        }
        .carousel-inner .carousel-item .carousel-caption h5{
            margin-top: 50px;
        }
        .layouts .image img{
            height: 500px;
            width: 500px;
        }
        .layouts{
            padding: 100px;
        }
        #carouselExampleCaptions img{
            height: 500px;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-dark" data-bs-theme="dark">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Carousel</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" aria-disabled="true">Disabled</a>
              </li>
            </ul>
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>

      <div id="carouselExampleCaptions" class="carousel slide ">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block text-end">
              <h5 class="fs-1 fw-bold">One more for good measure.</h5>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius corporis delectus cum voluptates ipsam doloremque!</p>
              <button class="bg-primary px-2 py-2 text-white rounded text-decoration-none">Browse Gallery1</button>
            </div>
          </div>
          <div class="carousel-item active">
            <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block text-end">
              <h5>One more for good measure.</h5>
              <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus odio sequi, cum molestias voluptate mollitia?</p>
              <button class="bg-primary px-2 py-2 text-white rounded text-decoration-none">Browse Gallery2</button>
            </div>
          </div>
          <div class="carousel-item active">
            <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block text-end">
              <h5>One more for good measure.</h5>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Natus est quae modi sunt recusandae accusamus.</p>
              <button class="bg-primary px-2 py-2 text-white rounded text-decoration-none">Browse Gallery3</button>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

<div class="cards d-flex ">
      <div class="card" style="width: 18rem;" >
        <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" class="card-img-top " alt="..." >
        <div class="card-body text-center">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" class="card-img-top " alt="...">
        <div class="card-body text-center">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      <div class="card" style="width: 18rem;">
        <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" class="card-img-top" alt="...">
        <div class="card-body text-center">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
      </div>

      <div class="layouts d-flex flex-row gap-5">
        <div class="content d-flex flex-column justify-content-center">
            <div class="heading fs-1 w-50">First featurette heading. It'll
                blow your mind.</div>
            <div class="data">
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet quibusdam ullam deleniti! Iste totam ipsa, eveniet consequuntur labore ex commodi omnis reprehenderit neque, voluptatem sit.</p>
            </div>
        </div>
        <div class="image">
            <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" alt="">
        </div>
      </div>

      <div class="layouts d-flex flex-row-reverse gap-5">
        <div class="content d-flex flex-column justify-content-center">
            <div class="heading fs-1 w-50">Oh yeah, it's that good. See
                for yourself.</div>
            <div class="data">
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet quibusdam ullam deleniti! Iste totam ipsa, eveniet consequuntur labore ex commodi omnis reprehenderit neque, voluptatem sit.</p>
            </div>
        </div>
        <div class="image">
            <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" alt="">
        </div>
      </div>

      <div class="layouts d-flex flex-row gap-5">
        <div class="content d-flex flex-column justify-content-center">
            <div class="heading fs-1 w-50">And lastly, this one.
                Checkmate.</div>
            <div class="data">
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Amet quibusdam ullam deleniti! Iste totam ipsa, eveniet consequuntur labore ex commodi omnis reprehenderit neque, voluptatem sit.</p>
            </div>
        </div>
        <div class="image">
            <img src="https://wallpapers.com/images/featured/plain-grey-background-ydlwqztavi78gl24.jpg" alt="">
        </div>
      </div>
      
</body>
</html>
```

**Q-4**:Create layout

**Ans**:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
</head>
<body>
    <div class="container w-50 my-5 d-flex gap-2 flex-column">
        <div class="row ">
            <div class="col w-100 bg-primary py-3 rounded-3 text-center fs-1 fw-semibold">Header</div>
        </div>
        <div class="row gap-2">
            <div class="col bg-success rounded-4 px-5 py-5 text-center fs-3 fw-semibold">column 1</div>
            <div class="col bg-danger rounded-4 px-5 py-5 text-center fs-3 fw-semibold">column 2</div>
            <div class="col bg-warning rounded-4 px-5 py-5 text-center fs-3 fw-semibold">column 3</div>
        </div>
        <div class="row">
            <div class="col w-100 bg-primary bg-gradient py-1 rounded-3 text-center fs-3 fw-semibold">Footer</div>
        </div>
    </div>
</body>
</html>
```






























**Q-5**: Make a card using Tailwind CSS.

**Ans**:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class=" my-80 mx-80 flex gap-4 ">
    <div class="card1 w-64  border border-5 border-slate-700 shadow-xl rounded-md p-4 flex flex-col items-start">
        <h1 class="font-semibold text-lg text-slate-700">Card Title</h1>
        <p class="mt-2.5 text-start">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molestiae ratione harum, ad obcaecati alias nihil!</p>
        <div class="btn text-white w-24 px-1 py-2 bg-blue-700 rounded-md mt-2.5 text-center">Know More</div>
    </div> 
    <div class="card2 w-64  border border-5 border-slate-700 shadow-xl rounded-md p-4 flex flex-col items-center">
        <h1 class="font-semibold text-lg text-slate-700">Card Title</h1>
        <p class="mt-2.5 text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molestiae ratione harum, ad obcaecati alias nihil!</p>
        <div class="btn text-white w-24 px-1 py-2 bg-blue-700 rounded-md mt-2.5 text-center">Know More</div>
    </div>
    <div class="card3 w-64  border border-5 border-slate-700 shadow-xl rounded-md p-4 flex flex-col items-end">
        <h1 class="font-semibold text-lg text-slate-700">Card Title</h1>
        <p class="mt-2.5 text-end">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molestiae ratione harum, ad obcaecati alias nihil!</p>
        <div class="btn text-white w-24 px-1 py-2 bg-blue-700 rounded-md mt-2.5 text-center">Know More</div>
    </div>

```
**Q-6**: Create slider

**Ans**:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css"
    />
  </head>
  <body>
    <div class="wrapper w-[900px] h-[500px] bg-slate-800 mx-auto my-28 flex flex-col ">
      <div class="slider flex flex-row justify-around mt-40">
        <div class="icon1">
          <i class="fa-solid fa-arrow-left text-4xl text-white"></i>
        </div>
        <div class="slide px-16 py-3 bg-emerald-700 text-white font-semibold text-xl rounded drop-shadow-[0_35px_35px_rgba(0,0,0,3.25)]">Slide</div>
        <div class="icon2">
          <i class="fa-solid fa-arrow-right text-4xl text-white"></i>
        </div>
      </div>
      <div class="boxes flex flex-row justify-center mt-32 gap-1">
        <div class="box1 h-1 w-8 bg-white "></div>
        <div class="box2 h-1 w-8 bg-slate-500"></div>
        <div class="box3 h-1 w-8 bg-slate-500"></div>
      </div>
    </div>
  </body>
</html>

```

**Q-7**: Create table using tailwind

**Ans**:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class=" mx-auto my-64 w-fit border-2 border-slate-400 shadow-xl p-4">
    <table class="">
        <caption class="caption-top text-start text-black font-semibold px-6 ">
            Basic Table
        </caption>
        <caption class="caption-top text-start text-slate-500 font-semibold px-6 ">
            Basic Table with card
        </caption>
        
            <tr class="border-b-2 border-slate-400">
                <th scope ="col" class="py-3">NAME</th>
                <th scope ="col" class="py-3">ID NO.</th>
                <th scope ="col" class="py-3">CREATED ON</th>
                <th scope ="col" class="py-3">STATUS</th>
            </tr> 
         
            <tr class="border-b-2 border-slate-400">
                <td class="px-10 py-4">Samso Park</td>
                <td class="px-10 py-4">34424433</td>
                <td class="px-10 py-4">12 May 2017</td>
                <td class="px-10 py-4"><button class="bg-red-500 p-2 rounded text-white text-sm text-center">pending</button></td>
            </tr>
            <tr class="border-b-2 border-slate-400">
                <td class="px-10 py-4">Marlo Sanki</td>
                <td class="px-10 py-4">53425532</td>
                <td class="px-10 py-4">15 May 2015</td>
                <td class="px-10 py-4"><button class="bg-yellow-500 p-2 rounded text-black text-sm text-center">in progress</button></td>
            </tr>
            <tr class="border-b-2 border-slate-400">
                <td class="px-10 py-4">John ryte</td>
                <td class="px-10 py-4">53275533</td>
                <td class="px-10 py-4">14 May 2017</td>
                <td class="px-10 py-4"><button class="bg-blue-500 p-2 rounded text-black text-sm text-center">Fixed</button></td>
            </tr>
            <tr class="border-b-2 border-slate-400">
                <td class="px-10 py-4">Peter mark</td>
                <td class="px-10 py-4">53275534</td>
                <td class="px-10 py-4">16 May 2017</td>
                <td class="px-10 py-4"><button class="bg-green-500 p-2 rounded text-black text-sm text-center">Completed</button></td>
            </tr>
            <tr>
                <td class="px-10 py-4">Dave</td>
                <td class="px-10 py-4">53275535</td>
                <td class="px-10 py-4">20 May 2017</td>
                <td class="px-10 py-4"><button class="bg-yellow-500 p-2 rounded text-black text-sm text-center">In progress</button></td>
            </tr>
      
    </table>
</body>
</html>
```