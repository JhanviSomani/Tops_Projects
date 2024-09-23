**Assignment-HTML5**

**Q-1**:What are the new tags added in HTML5?

**Ans**:The new added tags of HTML5 are
|Tags|Description|
|--------|-------|
| ```<article>``` |Represents an independent article with content separate from the rest of the site.|
|```<aside>```|Describes content related to the main object of the web page but not its main intent.|
|```<audio>```|Used to insert audio into an HTML webpage.|
|```<canvas>```|Used to draw graphics on a web page using JavaScript.|
|```<embed>```|Embeds external multimedia content like audio or video into an HTML document.|
|```<figure>```|Adds self-contained content like illustrations, diagrams, or photos.|
|```<mark>```|Defines marked text to highlight a part of the paragraph.|
|```<video>```|Embeds video content such as movie clips in a document.|
|```<svg>```|Used for scalable vector graphics.|
|```<source>```|Specifies multiple media resources for media elements.|

**Q-2**:How to embed audio and video in a webpage?

**Ans**:To embed audio we use ```<audio>``` tag of HTML5. By putting the audio source in the ```<audio>``` tag we can embed the audio in webpage.

```
<audio>
    <source src="../maxim.mp3">
</audio>
```
we can even give attributes to the audio tag, the attributes are:
autoplay
controls
loop
muted
preload

To embed video we use ```<video>``` tag of HTML5. By putting the video source in the ```<video>``` tag we can embed the video in webpage.

```
<video>
    <source src="../maxim.mp4">
</video>
```
we can even give attributes to the video tag, the attributes are:
autoplay
controls
loop
muted
poster
height
preload
width

**Q-3**:Semantic element in HTML5? 

**Ans**:Semantic elements provides more clearer and meaningful structure to the webpage. It improves accessibility, SEO, gives better understanding.
Some of the semantic element examples are:
```
<header>
<footer>
<section>
<article>
<nav>
<thead>
<main>
<summary>
etc.
```

**Q-4**:Canvas and SVG tags

**Ans**:**Canvas Tag**: The ```<canvas>``` tag in HTML5 is used to draw graphics on a web page using JavaScript. It can be used to draw paths, boxes, texts, gradients, and adding images.

```
<canvas id = "script"> 
    .....
</canvas>
```
Attributes we can use in ```<canvas>``` tag are height and weight.

**SVG Tag**: SVG stands for Scalable Vector Graphics .It is used to add vector based graphics to the webpage.

```
<SVG> 
    .....
</SVG>
```
We can give height and width attributes in the SVG tag. Inside the SVG tag we have to give the dimensions of the shape we want.