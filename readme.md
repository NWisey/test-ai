Hello
This site was created with the help of open.ai technology.
Using AI I generated a simple webpage, and by asking it prompt, I created a theme.
This site is for showcasing some of my favourite internet music, the images and music are by an artist called Macroblank.
I designed to site to be experimental/ retro in apperance, this played well into my knowledge of css as it made it easier to style.
For the aesthetic I added a marquee footer.
It is responsive to other screen sizes.

Production process.
-ask chatgbt to generate a basic site.
-With the generated code, I changed it so it worked and then styled it to look how I wanted.
-I used some of the frameworks on W3C school to help speed my process up. I didn't use other ones because the wheren't able to give the look I wanted.
-For some elements I referenced similar code to my other projects as it helped in knowing what the code should look like/ what was valid.
-When I was stuck I asked how to fix the problem and it usually gave a valid solution.
-When I needed to add a new element I first asked chatgbt what it should look like first. I then copy the code over.

My biggest takeaway from the assignment is that the AI tools aren't yet able to write code unsupervised. However I see the potential for it to be an amazing learning tool for those who have less experience like me. I often found that asking it questions about what parts of my code do what gave me better inside into how html and css actuall function. It was more effective asking it questions on how code works, then writing it myself,  than just asking it to write the code you need.

I found the most effective prompt was giving it all my code and asking it to change it so it was responsive. The generated code was not responsive, but I was able to change some values on it to make it work properly.

Enjoy listening to some chill tunes !

Prompts:
Hello
Are you able to help me program a simple website?
Using html and css, Maybe Java Script but I don't know that language. So we might only use a small amount.
Thats amazing! Are you familiar with the music and visual aesthetic "Vapourwave"?
What about a website with that aesthetic? There would be a home page with a logo, the other pages have a music player on them, keep that in mind for later. 
Are you familiar with pixel art aesthetic?
Is it possible to create a website that looks like it's made with pixel art?
can you create a website with css that aligns the elements to the pixel grid?
you forgot to link the font in the head to the google fonts page. you can access the code needed for a valid site there
thats great, how would I code a header with was sticky to the top of the page horizontally, stretched end to end, had a red background colour and white text.
can you change the header to include navigation to another page?
can you change it so the header is flexbox and the text aligns horrizontally, with one nav page on either sides of the logo and centre all elements to the middle of the header.
re-write this to create a horizontal nav header
<!--
<header class="sticky-header">
        <div class=".sticky-header">
            <nav>
                <ul>                
                    <a href="#">Page 1</a>
                    <h1>Logo</h1>
                    <a href="#">Page 2</a>
                </ul>
              </nav>
        </div>

      </header> 
-->
create a consistent border around the enitre page.
how do i make asimple static site using grids to divide the <main> into 2 columns. 
in a list <li> how would i place an <img> tag in between 2 <a> tags?
how to i style the elements as to make a static page which fills the browser?
how to style padding to be visible
How do i add a favicon?
how do I use javascript to insert an audio file?
My music file is not connecting to the button. Is there aanother way to have a music button?
The audio isn't playing, here is my code.
<!--
<audio id="myAudio" src="assets/audio/Macroblank- あなたを許すのは難しい.mp3"></audio>
<button onclick="toggleAudio()">Play Music</button>

<script>
var audio = document.getElementById("myAudio");

function toggleAudio() {
  if (audio.paused) {
    audio.play();
  } else {
    audio.pause();
  }
}
</script>
-->
how do i use java script
how do i link new fonts to the head
how would I change the code to make it responsive to different screen sizes, as make all content visible on the page. Here is my code.
<!--<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Responsive Site</title>
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
  <title>Pixel Grid Website</title>
  <link rel="icon" type="image/png" href="assets/images/icon.png">
  <link rel="stylesheet" href="assets/reset.css">
  <link rel="stylesheet" href="assets/style.css">
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<div class="border">
  <body>
    <header>
        <div class="inner" >
         <nav> 
            <ul>
                <ul><a href="page2.html">back</a></ul>
                <ul><a href="index.html"><img src="assets/images/logo2.png" alt="Website Logo"></li></ul>
                <ul><a href="index.html">next</a></ul>
                
            </ul>
        </nav>
       </div>
     </header>
     
     <main>
       <div class="elements">
         <div class="inner">
         <img src="assets/images/death.png" alt="I have this albumn on vynal" class="image">
       </div>
     </div>
       <div class="elements-right">
        <div class="audiobar">
            <audio controls autoplay>
            <source src="assets/audio/Death.mp3" type="audio/mpeg">
            Macroblank- あなたを許すのは難しい
          </audio>
        </div>
         <h1>Show no Mercy</h1>
         <h2>行​方​不​明
        </h2>
       </div>
       </main>
     </main>
     <marquee>
       <footer>
       <div class="footer-inner">
        <a href="https://macroblank.bandcamp.com/music">@macroblank</a>
       </div>
      </footer>
      </marquee>
</body>
</div>
</html>
</html>

html, body {
  margin: 0;
  padding: 0;
  max-height: 100%;
}

body {
  background-color: rgb(235, 96, 45);
  font-family: 'Press Start 2P', Hans sans, sans-serif;
  color: rgb(39,58,152);
  margin: 0;
  display: grid;
  grid-template-rows: 1fr;
  height:max-content;
  max-height: 100%;
}

main {
  display: grid;
    grid-template-columns: 1fr 1fr;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 20px;
    padding-bottom: 0px;
}

.inner {
    max-width: 80%;
    margin: 0 auto;
    justify-content: space-between;
}

.border {
  padding-left:10px;
  padding-right:10px;
  padding-bottom:10px;
  background-color: rgb(190, 182, 193);
}

.elements {
padding: 20px;
margin:20px;
max-height: 100%;
text-align: center;
}

.elements-right {
padding: 20px;
margin:20px;
max-height: 100%;
}

.image {
max-height:500px;
padding:10px;
background-color: rgb(220,27,44);
}

header {
  background-color: rgb(235, 96, 45);
  display: flex;
  padding: top 0;

}

header .inner {
  display: flex;
  justify-content: center;
  align-items: center;
  max-height: 4em;
}
header nav ul {
  display: inline;
  margin-left: 1.5em;
  padding:15px;
}

header nav ul a {
color: black;
text-decoration: none;
text-transform: uppercase;
}

header nav ul a:hover {
  color: grey;
}

h1 {
  font-size: 30px;
  margin: 0;
}

.audiobar{
  padding:40px;
  padding-left:0;
  padding-top:0;
}

marquee {
  position:relative;
  bottom:0;
  right:0;
  left:0;
  height:auto;
  padding-top:5px;
  padding-bottom:10px;
  width:100%;
  color:white;
  background-color: #25242d;
}

.footer-inner a {
display:flex;
align-items:center;
justify-content:center;
flex-direction: column;
text-align:center;
text-decoration: none;
color: white;
}


@media (max-width: 768px) {
  /* Styles for smaller screens */
  body {
    grid-template-columns: 1fr;
    max-width: 100%;
    max-height: none;
  }
}
-->
can you change that code but so that all items are centred on the page with 10px padding inbetween them vertically?
-----------