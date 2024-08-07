# Assignment 2: CSS and CSS3

**Q-1**:What are the benefits of using CSS?

**Ans**:CSS is a cascading style sheet which allows web designers to format and display their HTML documents.
Benefits of using CSS:
(1) We can give styling to our HTML page by using CSS.
(2)We can apply a specific repeated style for one element and can use it for multiple times and CSS will apply it automatically ti the required styles.
(3)We need to use few lines of programming for every page so it will improve the site speed.
(4)It simplifies the maintanance of website.
(5)CSS is device friendly as it has responsive web design.

**Q-2**: What are the disadvantages of CSS?

**Ans**:CSS is a cascading style sheet which allows web designers to format and display their HTML documents.
Disadvantages of CSS: 
(1)With CSS, what works with one browser might not always work with another. The web developers need to test for compatibility, running the program across multiple browsers.
(2) Browser compatibility as some styles sheet are supported and some are not.
(3)Cross browser issues.

**Q-3**:What is the difference between CSS2 and CSS3?

**Ans**:
| CSS2 | CSS3 |
|-------|-------|
|It is Capable of positioning texts and objects.|It is Capable of making web pages more attractive and takes less time to create. It is backward compatible with CSS|
|It does not support responsive design.|It supports responsive design.|
|It cannot be splited into modules|It can be splited into modules.|
|It does not support media queries.|It supports media queries.|
|It do not support 3D animation and transformation.|It Supports animation and 3D transformations.|
|It uses basic colour schemes.|It gives of HSL, RGBA and graident colours.|
|It is not supported by all types of modern browsers. |It is Supported by all modern browsers.|

**Q-4**:Name a few CSS style components.

**Ans**:CSS consists of two components: (1) Properties (2) Values

(1)**Properties**: They are identifiers that indicate which stylistic features we want to modify. For E.g. font-size, width, background-color.
(2)**Values**: Each property is assigned a value. This value indicates how to style the property.

E.g.

```
h1{
    color:blue;
    background-color:yellow;
}
p{
    color:red;
}
```

**Q-5**:What do you understand by CSS opacity?

**Ans**:It sets the opacity of an element. Opacity is the degree to which content behind an element is hidden.
Opacity applies to the element as a whole, including its contents.
**Syntax**: opacity:0.9;
Opacity in number ranges between 0 to 1.
Opacity in percentage ranges between 0% to 100%.
Example:
```
<html>
<head>
<style>
    .Box{
        height:300px;
        width:300px;
        background-color:pink;
        border: 2px solid grey;
        opacity:50%;
    }
</style>
<body>
<div class=Box>Box</div>
</body>
</head>
</html>
```
**Q-6**:How can the background color of an element be changed? 

**Ans**:We can change background color of an element by using syntax as:
**background-color:color_name;**
Example:
```
<html>
<head>
<style>
   .A1{
    background-color:pink;
   } 
   .A2{
    background-color:lightgreen;
   }
   .A3{
    background-color:lightblue;
   }
</style>
<body>
<div class=A1>This is the first background line.</div>
<div class=A2>This is the second background line.</div>
<div class=A3>This is the third background line.</div>
</body>
</head>
</html>
```

**Q-7**:How can image repetition of the backup be controlled?

**Ans**:We can control the image repetition by using background-repeat property.
**Syntax**:background-repeat: repeat | repeat-x | repeat-y | no-repeat | initial | inherit;
Example:
```
<html>
<head>
<style>
   .paragraph{
    background-image:url(data:image/jpeg;base64,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);
    background-repeat:no-repeat;
    background-size:cover;
    color:black;    
}
</style>
<body>
    <div class=paragraph>The background-repeat property in CSS is used to repeat the background image both horizontally and vertically. It also decides whether the background image will be repeated or not.</div>
</body>
</head>
</html>
```


**Q-8**:What is the use of the background-position property? 

**Ans**:The background-position property sets the starting position of a background image.
Values of background-position:
(1)left top
(2)left center
(3)left bottom
(4)right top
(5)right center
(6)right bottom
(7)center top
(8)center center
(9)center bottom

Example:
```
<html>
<head>
<style>
   .paragraph{
    background-image:url(data:image/jpeg;base64,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);
    background-repeat:no-repeat;
    background-size:cover;
    color:black;
    background-position:top;    
}
</style>
<body>
    <div class=paragraph>The background-repeat property in CSS is used to repeat the background image both horizontally and vertically. It also decides whether the background image will be repeated or not.</div>
</body>
</head>
</html>
```

**Q-9**:Which property controls the image scroll in the background? 

**Ans**:Background-attachment property will control if the image will scroll in the background or not.
**syntax**:background-attachment: scroll | fixed | local |

Example:
```
<html>
<head>
<style>
    .para{
        height:100%;
        width:100%;
        background-image:url(data:image/jpeg;base64,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);
        background-attachment:fixed;
        background-repeat:repeat-y;
        background-size:cover;
        
    }
</style>
<body>
<div class=para>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).
Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC. This book is a treatise on the theory of ethics, very popular during the Renaissance. The first line of Lorem Ipsum, "Lorem ipsum dolor sit amet..", comes from a line in section 1.10.32
</div>
</body>
</head>
</html>
```


**Q-10**: Why should background and color be used as separate properties?

**Ans**: Background and color are used as seperate properties because,
**Background**
Defines the background color or image of an element, which includes the total size of the element, including padding and border, but not the margin. Background properties can include images, gradients, and positioning, attachment, etc.

**Color**
It sets the text color. 

Example:
```
<html>
<head>
<style>
    .color{
        background-image:linear-gradient(pink, lightgreen);
        color:blue;
    }
</style>
<body>
    <div class=color>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua</div>
</body>
</head>
</html>
```

**Q-11**:How to center block elements using CSS1?

**Ans**:To center the block elements we have to use **Margin** property.
By giving the value of margin as **auto** we can center the block elements.

Example:
```
<html>
<head>
<style>
    .box1{
        height:300px;
        width:300px;
        background-color:pink;
        border:2px solid blue;
    }
    .box2{
        height:100px;
        width:100px;
        background-color:lightgreen;
        border:2px solid blue;
        margin: 100px auto;
    }
</style>
<body>
<div class=box1>
    <div class=box2></div>
</div>
</body>
</head>
</html>
```

**Q-12**:How to maintain the CSS specifications?

**Ans**:The CSS Specifications are maintained by the W3C (World wide web consortium).Almost every browser supports CSS, but there are some inconsistiences in the supported specifications version. Some browsers even have their own implementations of the specification.

**Q-13**:What are the ways to integrate CSS as a web page?

**Ans**:There are three ways to integrate CSS as a webpage.
(1)Inline CSS
(2)Internal CSS
(3)External CSS

**Inline CSS**:
It allows to apply styles directly within HTML tags using the style attribute. 
This method is useful for small-scale styling or when you need to apply a unique style to a single element using the style attribute.

E.g.: ```<h1 style="color:blue;">This is heading tag using inline css.</h1>```


**Internal CSS**:
Internal CSS involves adding CSS styles directly within the HTML file by including them inside the ```<style>``` tags.

E.g.:
```
<html>
<head>
    <style>
        .heading{
            color:green;
        }
    </style>
</head>
<body>
    <h2 class=heading>This is the heading tag using internal css.</h2>
</body>
</html>
```

**External CSS**:
External CSS involves creating a separate CSS file with a .css extension and linking it to the HTML file using the ```<link>``` tag.

E.g.: 
```
<head>
<link rel="stylesheet" href="styles.css">
</head>
<body>
    <h2>This is the heading tag using external css.</h2>
</body>
```

**Q-14**:What is embedded style sheets?

**Ans**:Embedded style sheet is also known as Internal CSS. It is a type of CSS that is added to an HTML document to define styles to the entire document.
It is declared in the ```<head>``` element.  It is applied to the whole document rather than one element.
It has drawback that it makes necessary to make changes on every page to apply them.

**Q-15**:What are the external style sheets?

**Ans**:An External style sheet is a seperate CSS file that can be used to apply rules to multiples web pages.
A link of these external style sheet should be put in the link tag in the head section of the webpage.
Multiple webpages can use the same link to access the stylesheet.

**Q-16**:What are the advantages and disadvantages of using external style sheets?

**Ans**:
**Advantages of external style sheets**:
(1)Improved maintainability and code organization.
(2)Enhanced reusability across multiple HTML files.
(3)Efficient caching and faster page load times.
**Disadvantages of external style sheet**:
(1)Pages may not render correctly until the external CSS is loaded.
(2)Uploading or linking to multiple CSS files may increase your site’s download time, affecting its overall performance.
(3)Large-scale projects may face versioning and caching challenges when using external CSS.

**Q-17**:What is the meaning of the CSS selector?

**Ans**:CSS selectors are used to select the elements we want to style.
There are many different types of selectors:
(1)tag selector
(2)class selector
(3)id selector
(4)Universal selector
(5)Group selector
(6)Attribute selector
(7)Psuedo-class selector
(8)combinator selector,etc.

**Q-18**:What are the media types allowed by CSS? 

**Ans**:
|Media type|Description|
|----------|-----------|
|all|Suitable for all media devices|
|print|Used for printers|
|screen|Targeted at computer screens, tablets, smartphones, etc.|
|speech|Designed for screen readers that read the content aloud.|

**Q-19**:What is the rule set?  

**Ans**:Each declaration block is preceded by one or more comma-separated selectors, which are conditions selecting some elements of the page. A selector list and an associated declarations block, together, are called a ruleset.
E.g. 
```
header, p .intro{
    background-color:red;
    border-radius:5px;
}
```
**Q-20**:Create Layout:

**Ans**:
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .Cards{
            height: 750px;
            width: 1000px;
            margin:auto;
            display: flex;
            flex-wrap: wrap;
            justify-content:space-around;
            align-items: center;
            padding: 10px;
        }
        .Cards .card{
            width: 300px;
            height: fit-content;
            border-radius: 8px;
            box-shadow: rgba(50, 50, 93, 0.25) 0px 6px 12px -2px, rgba(0, 0, 0, 0.3) 0px 3px 7px -3px;
        }
        .Cards img{
            width: 100%;
            height: 200px;
            border-top-left-radius: 8px;
            border-top-right-radius: 8px;
        }
        .Cards .content{
            padding: 15px;
        }
        .Cards .btn{
            margin-top: 15px;
        }
        .Cards .btn button{
            width: 50px;
            background-color: whitesmoke;
            border-radius: 5px;
            border: 1px solid grey;
        }
        
    </style>
</head>
<body>
    <div class="Cards">
        <div class="card1 card">
            <img src="https://images.pexels.com/photos/417074/pexels-photo-417074.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
            <div class="content">
                <p>This is the wider card with supporting text below as a natural lead-in to additional content. This content is a bit longer.</p>
            <div class="btn">
                <button>View</button>
                <button>Edit</button>
            </div>
            </div>
        </div>

        <div class="card2 card">
            <img src="https://images.pexels.com/photos/994605/pexels-photo-994605.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
            <div class="content">
                <p>This is the wider card with supporting text below as a natural lead-in to additional content. This content is a bit longer.</p>
            <div class="btn">
                <button>View</button>
                <button>Edit</button>
            </div>
            </div>
        </div>

        <div class="card3 card">
            <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            <div class="content">
                <p>This is the wider card with supporting text below as a natural lead-in to additional content. This content is a bit longer.</p>
            <div class="btn">
                <button>View</button>
                <button>Edit</button>
            </div>
            </div>
        </div>

        <div class="card4 card">
            <img src="https://images.pexels.com/photos/21787/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=600" alt="">
            <div class="content">
                <p>This is the wider card with supporting text below as a natural lead-in to additional content. This content is a bit longer.</p>
            <div class="btn">
                <button>View</button>
                <button>Edit</button>
            </div>
            </div>
        </div>

        <div class="card5 card">
            <img src="https://images.pexels.com/photos/715134/pexels-photo-715134.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="">
            <div class="content">
                <p>This is the wider card with supporting text below as a natural lead-in to additional content. This content is a bit longer.</p>
            <div class="btn">
                <button>View</button>
                <button>Edit</button>
            </div>
            </div>
        </div>

        <div class="card6 card">
            <img src="https://images.pexels.com/photos/547115/pexels-photo-547115.jpeg?auto=compress&cs=tinysrgb&w=600" alt="">
            <div class="content">
                <p>This is the wider card with supporting text below as a natural lead-in to additional content. This content is a bit longer.</p>
            <div class="btn">
                <button>View</button>
                <button>Edit</button>
            </div>
            </div>
        </div>
        
    </div>
</body>
</html>
```
