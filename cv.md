# Anton Navitski

![MyPhoto](01.jpg "MyPhoto")

#### Student Junior Frontend Developer

___

### Contacts:
- __Location:__ Warsaw, Poland
- __Phone:__ [+48 511 483 113](tel:+48511483113 "phone")
- __e-mail:__ [navickiy1994@gmail.com](mailto:navickiy1994@gmail.com "mail")
- __Netlify:__ [Antonowka](https://app.netlify.com/teams/navickiy1994-3-imbsy/overview "netlify")
- __GitHub:__ [Antonowka](https://github.com/Antonowka "GitHub")
- __Discord:__ [@Shimmy#9464](https://discord.com/app "diskord")

___

### My Ambitions:
By the end of 2022, you will receive the necessary amount of knowledge and skills 
sufficient for employment in the Front end development studio.
To continue my studies and at the same time to work in a field that brings me pleasure.


___

### Soft Skills:
+ __Teamwork__
+ __GTD__
+ __Agile__
+ __Ability and striving for improvement__

___

### Tech Skills:
+ __Photoshop__
+ __HTML__
+ __CSS:__  *Flexbox, Adaptive layout, Animation*
+ __GIT__
+ __elementary JS:__ *integration into my code*

___

### Tools:
+ __Photoshop__
+ __VSCode__
+ __Figma__
+ __Git Desktop__

___

### Code Examples:

```
HTM:
  <h1>My First JS Slider</h1>
  <div class="container">

    <div class="slide" style="background-image: url(./img/1.jpg)">
      <h3>Salon</h3>
    </div>

    <div class="slide" style="background-image: url(./img/2.jpg)">
      <h3>Salon</h3>
    </div>
 
    <div class="slide active" style="background-image: url(./img/3.jpg)">
      <h3>Salon</h3>
    </div>

    <div class="slide" style="background-image: url(./img/4.jpg)">
      <h3>Salon</h3>
    </div>

    <div class="slide" style="background-image: url(./img/5.png)">
      <h3>Salon</h3>
    </div>
  
  </div>

CSS:
*{
  box-sizing: border-box;
}

body{
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  /* overflow: hidden; */
  margin: 0;
  background-color: #525252;
  /* height: 100vh; */
  max-width: 1200px;
  margin: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.container{
  width: 100%;
  display: flex;
  padding: 0 20px;
}

.slide {
  height: 80vh;
  border-radius: 20px;
  margin: 10px;
  cursor: pointer;
  color: #fff;
  flex: 1;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  position: relative;
  transition: all 500ms ease-in-out;
}

.slide h3{
  position: absolute;
  font-size: 24px;
  bottom: 20px;
  left: 20px;
  margin: 0;
  opacity: 0;
}

.slide.active{
  flex: 10;
}

.slide.active h3{
  opacity: 1;
  transition: opacity 0.3s ease-in 0.4s;
}

JS:
const slides = document.querySelectorAll('.slide')
for (const slide of slides) {
  slide.addEventListener('click', () => {
    clearActiveClasses()

    slide.classList.add('active')
  })
}

function clearActiveClasses() {
  slides.forEach((slide) => {
    slide.classList.remove('active')
  })
}

```
___

### Experience.
+ __HTML+CSS:__ *my introduction to frontend* - __[Netlify](https://lucky-taffy-961900.netlify.app/ "goit")__
+ __JS:__ *my introduction to JS* - __[Netlify](https://remarkable-kashata-ab03ae.netlify.app/ "js-slider")__
+ __HTML+CSS+JS:__ *My first solo project. Cv for my girl.* - __[Netlify](https://elaborate-florentine-1efb1e.netlify.app/ "my-solo-project")__

___

### Education:
+ __Сollege at the Belarusian-Russian University:__ *01.09.2010 - 21.03.2014 - "Industrial and civil construction".* "__Technic-Builder__."
+ __Belarusian-Russian University:__ *01.09.2014 - 25.01.2019 - "Industrial and civil construction".* "__Civil-Engineer__."
+ __GoIT Courses:__ *intensive Frontend course - start 22 end 30 March 2022*
+ __RS School:__ *«JavaScript/Front-end. Stage 0» - start 01.06.2022*

___

### Language:
+ __English__ __[EF SET](https://www.efset.org/ru/ "linkEnglish")__ - _Beginner_
+ __Polish__ - _B1_
+ __Russian__ - _Native_
+ __Belarusian and Ukraine__ - _Free understanding and read_