# Anton Navitski

![MyPhoto](01.jpg "My Photo")

#### Student Junior Frontend Developer

___

### Contacts:
- Location: Warsaw, Poland
- Phone: [+48 511 483 113](tel:+48511483113 "phone")
- e-mail: [navickiy1994@gmail.com](mailto:navickiy1994@gmail.com "mail")
- Netlify: [Antonowka](https://app.netlify.com/teams/navickiy1994-3-imbsy/overview "mail")
- GitHub: [Antonowka](https://github.com/Antonowka "GitHub")
- Discord: [@Shimmy#9464](https://discord.com/app "mail")

___

### My Ambitions:
By the end of 2022, you will receive the necessary amount of knowledge and skills 
sufficient for employment in the Front end development studio.
To continue my studies and at the same time to work in a field that brings me pleasure.


___

### Soft Skills:
+ Teamwork
+ GTD
+ Agile
+ Ability and striving for improvement

___

### Tech Skills:
+ Photoshop
+ HTML
+ CSS:  *Flexbox, Adaptive layout, Animation*
+ GIT
+ elementary JS: *integration into my code*

___

### Tools:
+ Photoshop
+ VSCode
+ Figma
+ Git Desktop

___

### Code Examples:

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
 

___

### Experience.
+ HTML+CSS: *my introduction to frontend* - [Netlify](https://lucky-taffy-961900.netlify.app/ "goit")
+ JS: *my introduction to JS* - [Netlify](https://remarkable-kashata-ab03ae.netlify.app/ "js-slider")


___

### Education:
+ Сollege at the Belarusian-Russian University: *01.09.2010 - 21.03.2014 - "Industrial and civil construction".* "Technic-Builder."
+ Belarusian-Russian University: *01.09.2014 - 25.01.2019 - "Industrial and civil construction".* "Civil-Engineer."
+ GoIT Courses: *intensive Frontend course - start 22 end 30 March 2022*


___

### Language:
+ English [EF SET](https://www.efset.org/ru/ "phone") - _Beginner_
