**ASSIGNMENT-3**

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

**Q-3**:What are the default Bootstrap text settings?
**Ans**Bootstrap 5 uses a default 
font-size of 1rem (16px) 
line-height is 1.5.
All ```<p>``` elements have, 
margin-top: 0 
margin-bottom: 1rem (16px).

**Q-4**:What do you know about the Bootstrap Grid System? 
**Ans**:Bootstrap grid system is mobile-first flex-box grid to build layouts. It has 12 column system, 5 default responsive tiers and many predefined classes.

Working:
Bootstrap grid uses a series of containers, rows, and columns to layout and align content. It’s built with flex-box and is fully responsive.

Example:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
      crossorigin="anonymous"
    />
  </head>

  <body>
    <div
      class="container w-50 my-5 mx-auto m-5 text-center d-flex flex-column gap-2 fw-bolder"
    >
      <div class="row gap-2">
        <div class="col bg-success bg-opacity-75 p-2">1</div>
        <div class="col bg-success bg-opacity-75 p-2">2</div>
        <div class="col bg-success bg-opacity-75 p-2">3</div>
        <div class="col bg-success bg-opacity-75 p-2">4</div>
        <div class="col bg-success bg-opacity-75 p-2">5</div>
        <div class="col bg-success bg-opacity-75 p-2">6</div>
        <div class="col bg-success bg-opacity-75 p-2">7</div>
        <div class="col bg-success bg-opacity-75 p-2">8</div>
        <div class="col bg-success bg-opacity-75 p-2">9</div>
        <div class="col bg-success bg-opacity-75 p-2">10</div>
        <div class="col bg-success bg-opacity-75 p-2">11</div>
        <div class="col bg-success bg-opacity-75 p-2">12</div>
      </div>
      <div class="row gap-2">
        <div class="col bg-success p-2 bg-opacity-50">4</div>
        <div class="col bg-success p-2 bg-opacity-50">4</div>
        <div class="col bg-success p-2 bg-opacity-50">4</div>
      </div>
      <div class="row gap-2">
        <div class="col-4 bg-success p-2 bg-opacity-25">4</div>
        <div class="col bg-success p-2 bg-opacity-25">8</div>
      </div>
      <div class="row gap-2">
        <div class="col bg-success p-2 bg-opacity-10">6</div>
        <div class="col bg-success p-2 bg-opacity-10">6</div>
      </div>
      <div class="row">
        <div class="col bg-success p-2 bg-opacity-100">12</div>
      </div>
    </div>
  </body>
</html>
```
Bootstrap grid system also allows us to make it responsive:

(1)Extra Small- .col-	
(2)Small - .col-sm-	
(3)Medium - .col-md-	
(4)Large - .col-lg-	
(5)Extra large - .col-xl-

We can also set the column width according to our requirement:
```
<div class="row">
    <div class="col-8"></div>
    <div class="col-4"></div>
  </div>
```

We can also give alignments to the grid.
```
<div class="row align-items-start">
<div class="row align-items-center">
<div class="row align-items-end">
```

```
<div class="col align-self-start">
<div class="col align-self-center">
<div class="col align-self-end">
    
```
We can also give justify content property of flex box to the grid.
```
<div class="row justify-content-start"> 
<div class="row justify-content-center">
<div class="row justify-content-end">
<div class="row justify-content-around">
<div class="row justify-content-between">
    
```
We can give almost each and every property of flex-box property to the grid of bootstrap.
For e.g. align-items, justify-content, align-self, gap, etc.

**Q-5**:What is the difference between Bootstrap 4 and Bootstrap 5?
**Ans**:
|Bootstrap 4|Bootstrap 5|
|----------|----------|
|It has 5 tier (xs, sm, md, lg, xl).|It has 6 tier (xs, sm, md, lg, xl, xxl).|
|It has jquery and all related plugins.|Jquery is removed and switched to vanilla JS with some working plugins.|
|Radio buttons, checkboxes have different look in different OS and browsers. The form uses whatever default browsers provide.|The look of form elements will not change, on different OS or browser. The forms can be customized and form controls can be added, they would not depend on browser. |
|We cannot modify utilities in bootstrap 4|Bootstrap 5 gave freedom to modify and also create our own utility.|
|Bootstrap 4 doesn’t have its own SVG icons, we have to use font-awesome for icons.|Bootstrap 5 have its own SVG icons|
|The card deck is used to create a set of cards with equal width and height.|Card deck class in removed in bootstrap.|

**Q-6**:What is a Button Group, and what is the class for a basic Button Group? 
**Ans**: Button Group in Bootstrap is a class of name “btn-group” which is used to create a series of buttons in groups vertically or horizontally.
This is the basic syntax of the button group class where each button has its own class of “btn".
Example:
```
<div class="btn-group">
    <button type="button" class="btn">Read More</button>
</div>
```
We can also add styles to the buttons by giving different classes to them.

(1)To give color to the button we give the following classes:

.btn-default
.btn-primary
.btn-success
.btn-info
.btn-warning
.btn-danger

Example: 
```
<div class="btn-group">
    <button type="button" class="btn btn-danger">Click</button>
</div>
```
(2)Bootstrap provides 4 button sizes which you can add directly to the "btn-group" class.
```
<div class="btn-group btn-group-lg">
<div class="btn-group btn-group-sm">
<div class="btn-group btn-group-xs">
<div class="btn-group btn-group">
```
(3)Bootstrap also supports vertical button groups stacked in a vertical manner rather than horizontally. Use the class “btn-group-vertical”.

Example:
```
<div class="btn-group-vertical">
        <button type="button" class="btn btn-danger">Click</button>
        <button type="button" class="btn btn-warning">Click</button>
</div>
```
**Q-7**:How can you use Bootstrap to make thumbnails? 
**Ans**:To make Image a thumbnail we use the class of img-thumbnail in the image tag.
Example:
```
<body>
    <img
      src="https://images.pexels.com/photos/13010254/pexels-photo-13010254.jpeg?auto=compress&cs=tinysrgb&w=600"
      class="img-fluid img-thumbnail m-5"
      alt=""
    />
  </body>
  ```

**Q-8**:In Bootstrap 4, what is flexbox? 
**Ans**:In Bootstrap 4 flex-box is used instead of float to handle the layout.
The Flexible Box Layout Module, makes it easier to design flexible responsive layout structure without using float or positioning. 
To make flex we have to use class name "d-flex".

Example:
```
<div class="d-flex p-3 bg-secondary text-white">
  <div class="p-2 bg-info">Flex item 1</div>
  <div class="p-2 bg-warning">Flex item 2</div>
  <div class="p-2 bg-primary">Flex item 3</div>
</div>
```
**Q-9**:How can one create an alert in Bootstrap?  
**Ans**:Alert can be created by writing .alert class.
To give the styling to the alert we need to give some styling classes. For e.g.
``` 
<div class="alert alert-success">
<div class="alert alert-info">
<div class="alert alert-warning">
<div class="alert alert-danger">
```
Example:
```
<div class="alert alert-danger">
      This is some danger alert <i class="fa-solid fa-xmark"></i>
</div>
```
**Q-10**:What is a bootstrap card and how would you create one? 
**Ans**:A card is a flexible and extensible content container. It includes options for headers and footers, a wide variety of content, contextual background colors, and powerful display options.
The most basic approach to make a card in bootstrap is by applying  .card class to a div element and then nesting content within it.

Example:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="card mx-5 my-5" style="width: 18rem;">
        <img src="https://images.pexels.com/photos/6398585/pexels-photo-6398585.jpeg?auto=compress&cs=tinysrgb&w=600" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card title</h5>
          <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
      </div>
</body>
</html>
```
