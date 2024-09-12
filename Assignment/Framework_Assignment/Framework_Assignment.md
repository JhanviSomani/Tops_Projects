**Q-1**: Make a card using Tailwind CSS.

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
**Q-2**: Create slider

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

**Q-3**: Create table using tailwind

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