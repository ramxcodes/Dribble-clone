#Dribble Clone

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation / Fork](#installation--fork)
4. [Star the GitHub Repo](#star-the-github-repo)
5. [Code of the Website](#code-of-the-website)

---

## Introduction

Welcome to RamxCodes' Dribble Clone project! This project aims to recreate the Dribbble website with a responsive design and some creative elements. Feel free to explore the code and use it as a reference for your own projects.

<img src="https://drive.google.com/uc?export=view&id=1WtwpXiI7CUF2ImBdO2DEcAxI0q9Sbs8p" alt="Gojo Satoru Image" style="width: 100%; max-width: 600px; height: auto; margin: 20px 0;">
<a target="_blank" href="https://ramxcodes.github.io/Dribble-clone/" style="display: inline-block; padding: 10px 20px; background-color: #3498db; color: #fff; text-decoration: none; border-radius: 5px; font-weight: bold; font-size: 16px; margin-bottom: 20px;">Visit Website ↗</a>


---

## Features

- Responsive design for a seamless user experience on various devices.
- Navigation bar with links for finding talent, inspiration, learning design, job opportunities, and going pro.
- Engaging content section showcasing the platform's features.
- Explore inspiring designs section with interactive boxes displaying images and videos.

---

## Installation / Fork

To get started with the project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/ramxcodes/dribble-clone.git
   ```

2. Navigate to the project directory:

   ```bash
   cd dribble-clone
   ```

3. Open the `index.html` file in your preferred web browser.

---

## Star the GitHub Repo

If you find this project interesting or useful, show your support by starring the [GitHub repository](https://github.com/ramxcodes/dribble-clone). Your feedback and contributions are always welcome!

---

## Code of the Website

Below is the HTML and CSS code that constitutes the Anime Hunt website. Feel free to explore and modify the code as needed.

### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribble Clone</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Scada:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
</head>

<body>
    <div id="page1">
        <div id="nav">
            <div id="nav-part1">
                <h4>Find Talent</h4>
                <h4>Inspiration</h4>
                <h4>Learn design</h4>
                <h4>Jobs</h4>
                <h4>Go Pro</h4>
            </div>
            <img src="https://miro.medium.com/v2/resize:fit:1256/1*PhdAw7Tu0Zac-V3MxzEJNw.png" alt="">
            <div id="nav-part2">
                <button>Log in</button>
                <button>Sign up</button>
            </div>
        </div>
        <div id="content">
            <h3>Over 3 million ready-to-work creatives!</h3>
            <h1>Work with the world’s top <br> creative talent.</h1>
            <h4>Connect with millions of top-rated designers & agencies around the world.</h4>
            <button>Start hiring today</button>
            <div id="bottom">
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47172/original/d85ae8c7db2421e9a01ecac942978d4b.png?1685645079&format=webp&resize=320x399&vertical=center" alt="">
                    <div class="text-bottom"></div>
                </div>
                <div class="elem">
                    <video autoplay loop muted src="https://cdn.dribbble.com/uploads/47180/original/1def7b9fb30832c4af4353b325d9c3af.mp4?1685645402"></video>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47174/original/4f02d72fe701b15b2168a4954332427f.png?1685645150&format=webp&resize=320x399&vertical=center" alt="">
                </div>
                <div class="elem">
                    <video autoplay loop muted src="https://cdn.dribbble.com/uploads/47179/original/35d07cfebd303e05e688078015da0cc2.mp4?1685645373"></video>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47173/original/Vladimir_Gruev.png?1689174896&format=webp&resize=320x399&vertical=center" alt="">
                </div>
                <div class="elem">
                    <video autoplay loop muted src="https://cdn.dribbble.com/uploads/47181/original/1e3a73a174484bef522b620c401cd00a.mp4?1685645427"></video>
                </div>
                <div class="elem">
                    <img src="https://cdn.dribbble.com/uploads/47170/original/cd3266dde4f00a5d6a509c7375ddaecd.png?1685644840&format=webp&resize=320x399&vertical=center" alt="">
                </div>
                <div class="elem">
                    <video autoplay loop muted src="https://cdn.dribbble.com/uploads/47180/original/1def7b9fb30832c4af4353b325d9c3af.mp4?1685645402"></video>
                </div>
            </div>
          
        </div>
    </div>
    <div id="page2">
        <h1>Explore inspiring designs</h1>
        <div class="box">
            <img src="https://cdn.dribbble.com/userupload/10985667/file/original-3c6c333c2edf24f7613e4823249fe423.png?resize=400x300&vertical=center" alt="">
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>


        <div class="box">
            <img src="https://cdn.dribbble.com/userupload/11097471/file/original-4b4e762d9728e45cc96664cd1965d844.jpg?resize=400x300&vertical=center" alt="">
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
        <div class="box">
            <video autoplay loop muted src="https://cdn.dribbble.com/userupload/9405278/file/large-f61d369f6a6a46c88dceb098c65c3a10.mp4"></video>
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
        <div class="box">
            <img src="https://cdn.dribbble.com/userupload/10990040/file/original-9edbdf806cb2d90933c6aedf96ec1dd7.png?resize=400x300&vertical=center" alt="">
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
        <div class="box">
            <img src="https://cdn.dribbble.com/userupload/10985667/file/original-3c6c333c2edf24f7613e4823249fe423.png?resize=400x300&vertical=center" alt="">
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
        <div class="box">
            <img src="https://cdn.dribbble.com/userupload/11097471/file/original-4b4e762d9728e45cc96664cd1965d844.jpg?resize=400x300&vertical=center" alt="">
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
        <div class="box">
            <video autoplay loop muted src="https://cdn.dribbble.com/userupload/9405278/file/large-f61d369f6a6a46c88dceb098c65c3a10.mp4"></video>
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
        <div class="box">
            <img src="https://cdn.dribbble.com/userupload/10990040/file/original-9edbdf806cb2d90933c6aedf96ec1dd7.png?resize=400x300&vertical=center" alt="">
            <div class="box-bottom">
                <h5>Productivity</h5>
                <i class="ri-heart-3-line"></i>
            </div>
        </div>
    </div>
</body>

</html>
```

### CSS (style.css)

```css
@font-face {
    font-family: Gilroy;
    src: url(./fonts/Gilroy-Medium.otf);
}
@font-face {
    font-family: "Source Serif 4";
    src: url(./fonts/source\ serrif\ 4.ttf);
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Gilroy';
}

html, body {
    height: 103%;
    width: 100%;
}
#page1{
    height: 102%;
    width: 100%;
}
#nav{
    height: 120px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 40px;
}

#nav-part1{
    width: 26%;
    display: flex;
    align-items:center ;
    justify-content: space-between;
}
#nav-part1 h4{
    font-size: 16px;
    font-weight: 500;
}
#nav-part2{
    width: 26%;
    display: flex;
    align-items:center ;
    justify-content: flex-end;
}
#nav-part2 button{
    padding: 15px 22px;
    font-weight: 600;
    border: none;
    background-color: black;
    color: #fff;
    border-radius: 50px;
    font-size: 17px;
    margin: 0 10px;
}
#nav-part2 button:nth-child(1){
    background-color: transparent;
    color: #000;
}
#nav img{
    height: 110px;
}


#content{
    height: calc(100% - 100px);
    width: 100%;
    padding-top: 90px;
}
#content h3{
    background-color: #F2B0EA;
    padding: 10px 16px;
    border-radius: 50px;
    width: fit-content;
    position: relative;
    left: 50%;
    font-weight: 100;
    transform: translateX(-50%);
    font-size: 17px;
    font-family: "Source Serif 4";
    
}
#content h1{
    font-size: 80px;
    text-align: center;
    margin: 40px 0;
    font-family: "Source Serif 4";
    font-weight: 100;
    line-height: 80px;
}
#content h4{
    font-size: 22px;
    text-align: center;
    font-weight: 500;
}

#content button{
    padding: 20px 28px;
    font-weight: 600;
    border: none;
    background-color: black;
    color: #fff;
    border-radius: 50px;
    font-size: 18px;
    margin: 50px 0px;
    position: relative;
    left: 50%;
    transform: translateX(-50%);
    margin-bottom: 70px;
}
#bottom{
    height: 380px;
    width: 100%;
    padding: 5px;
    white-space: nowrap;
    overflow-x: auto;
    overflow-y: hidden;
}
#bottom::-webkit-scrollbar{
    display: none;
}
.elem{
    display: inline-block;
    position: relative;
    height: 100%;
    width: 320px;
    margin-right: 30px;
    background-color: royalblue;
    border-radius: 40px;
    overflow: hidden;
}
.elem img{
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
}
.elem video{
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
}


#page2{
    height: 100%;
    width: 100%;
    background-color: rgb(255, 255, 255);
    position: relative;
    padding: 70px;
    padding-top: 100px;
}
#page2 h1{
    text-align: center;
    font-weight: 500;
    font-size: 60px;
    margin-bottom: 50px;
}
.box{
    height: 320px;
    width: 400px;
    background-color: red;
    border-radius: 15px;
    display: inline-block;
    position: relative;
    transition: all ease 0.5s;
    overflow: hidden;
    margin: 15px;
}
.box img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
.box video{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
.box-bottom{
    height: 40%;
    width: 100%;
    background:linear-gradient(transparent,rgba(0, 0, 0, 0.63)) ;
    position: absolute;
    bottom: -40%;
    transition: all ease 0.5s;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 20px;
}
.box-bottom i{
    background-color: white;
    padding: 8px 9px;
    color: #000;
    font-size: 19px;
    font-weight: 600;
    border-radius: 50%;
}
.box-bottom h5{
    font-size: 18px;
}
.box:hover .box-bottom{
    bottom: 0;
}

.box:hover{
    box-shadow: 0px 2px 20px rgba(123, 123, 123, 0.498);
}
```


### Fonts

The project uses custom fonts, Gilroy and Source Serif 4. The font files are included in the `fonts` directory.

### Important CSS Styles

- Responsive design with `@media` queries.
- Navigation bar styling.
- Content section styling, including buttons and image/video displays.
- Explore designs section styling with interactive hover effects.

Feel free to explore and modify the code to suit your needs or use it as a learning resource.

---

Feel free to reach out to RamxCodes for any questions or suggestions! Happy coding! 🚀
