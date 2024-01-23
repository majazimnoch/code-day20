# Website which dispalys a cookie consent banner
## Intro
This is the twentieth project of my 30-day coding challenge. The project includes following tech stuff: HTML, CSS, JavaScript.

## Idea
As I observe websites on the internet, they all have a privacy settings pop up banner. To be prepared to meet expectations in a reality, when creating a website, I wanted to recreate such popup banner myself.

## Breaking down the code
I started off by making a `div`with `id=cookiePopup` and then a made a variable `popUp` getting this element by its ID. A added an Event to the button which triggers a function when clicked. 
Function `checkCookie` reads the cookies. `Window Load Event` sets up an event to execute the checkCookie function two seconds (2000 milliseconds) after the window loads.

## Demo
Click <a href="https://zippy-ganache-685ed8.netlify.app/"> here </a>.