




## About
I'm a teen who is currently interested in Web and App Development. I am also learning JavaScript and Python!
I hope you enjoy you time here!

## Mad Libs Game

Here is a game I made using JavaScript.
<style>
        
#madlibsbox{
overflow: hidden;
            }
            
            
#madlibshead {
text-align: center;
background-color: #44b891;
color: #fff;
text-shadow: 2px 3px 5px rgb(0, 0, 0, 0.15);
border-radius: 5px;
padding: 7px;
}

input {
border-radius: 2px;
border: solid;
border-width: 1px;
border-color: rgb(201, 201, 201);
}

.inputs {
font-weight: bold;
padding: 8px;
color: rgb(87, 87, 87);
}

#lib-button {
border: none;
padding: 9px;
background-color: #44b891;
color: #fff;
font-size: 15px;
border-radius: 5px;
transition: 0.2s;
}

#lib-button:hover {
cursor: pointer;
box-shadow: 0px 5px 10px rgb(0, 0, 0, 0.2);
}

#story{
padding:20px;
width:80%;
}
            
#storybox{
background-color:rgb(232, 232, 232);
color:rgb(84, 84, 84);
padding: 20px;
border-radius: 5px;
text-align:left;
margin-top:10px;
overflow-y: scroll;
height: 90px;
}
            
</style>
<div id = "madlibsbox">
<body>
<h1 id = "madlibshead">Mad Libs</h1>

<ol>
<li class="inputs">Persons Name: <input type="text" id="person"></li>
<li class="inputs">Food: <input type="text" id="food"></li>
<li class="inputs">Action: <input type="text" id="act"></li>
<li class="inputs">Place: <input type="text" id="place"></li>
<li class="inputs">Color: <input type="text" id="color"></li>
<li class="inputs">Thing: <input type="text" id="thing"></li>
<li class="inputs">Action <input type="text" id="act2"></li>

</ol>

<button id="lib-button">Generate Story</button>

<p id = "storybox"><b>Story:</b><br>
<span id="story"></span>
</p>
</body>
</div>
<script>

var libButton = document.getElementById('lib-button');
var libIt = function () {
var storyDiv = document.getElementById("story");

var person = document.getElementById("person").value;

 var food = document.getElementById("food").value;

var act = document.getElementById("act").value;

var place = document.getElementById("place").value;

var color = document.getElementById("color").value;

var thing = document.getElementById("thing").value;

var act2 = document.getElementById("act2").value;




storyDiv.innerHTML = person + " ate a whole bowl of " + food + " before they went " + act + " all the way to " + place + " an bought a " + color + " " + thing + " then went " + act2 + " all the way back home. ";
            };
libButton.addEventListener('click', libIt);



</script>
[Vote it UP](https://www.khanacademy.org/computer-programming/mad-libs/5821356050382848)
<br>

## Scrible Paint App
<br>
A paint app I made on KhanAcademy using p5.js
<script src="https://www.khanacademy.org/computer-programming/scribble/6160303581200384/embed.js?width=600&height=600&editor=no&buttons=yes&author=yes&embed=yes"></script>

[Vote it UP](https://www.khanacademy.org/computer-programming/scribble/6160303581200384)
<br>

### Markdown styling

```markdown 
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


### Find me on:
<br>
_KhanAcademy_:[@Foxbyte14](https://www.khanacademy.org/profile/Foxbyte14/)
<br>
_OpenProcessing_:[@intelligence](https://www.openprocessing.org/user/164755)
<br>
_GitHub_:[@Foxbyte14](https://github.com/Foxbyte14)
<br>
