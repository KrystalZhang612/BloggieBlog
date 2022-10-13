# BloggieBlog
A newsfeed blog developed with HTML, CSS and JavaScript with frontend development skills, including various features of header, search bar, featured articles, posts, popular tags, newsletter subscription option and abundant media queries, and so on.<br/><hr>
# Functionalities/Demo
[BloggieBlog Overview-1.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-1.png)<br/>
[BloggieBlog Overview-2.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-2.png)<br/> 
[BloggieBlog Overview-3.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-3.png)<br/>
[BloggieBlog Overview-4.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-4.png)<br/> 
[BloggieBlog Overview-5.PNG](https://github.com/KrystalZhang612/BloggieBlog/blob/main/BloggieBlog%20Overview-5.png)<br/> 
- A responsive blog website from scratch.
- A header section that holds the navigation and all of its items.
- A theme toggle button that transitions the color scheme into the light scheme.
- It uses JavaScript Store, so the theme selection remains active when closing the webpage. - A search button with a popping up activated search bar when clicking the button.
- Signin and Signup buttons with neon effect.
- A main section with a nested grid that is split into two sides with creative layouts.
- A right-hand-side sidebar contains a quick read section utilizing JavaScript library `Swiper`, which creates a responsive carousel, to achieve arrows in pagination work.
- Older Posts section and Popular Tags section that are composed of six cards.
- A Newsletter section prompting users to subscribe to the newsletter if they want to.
# Developing Tools
[JavaScript Swiper](https://swiperjs.com/)<br/>
[Vscode 1.72](https://code.visualstudio.com/updates/v1_72)<br/>
[Live Server Vscode Extension v5.7.9](https://www.vsixhub.com/vsix/1950/)<br/>
# Build 
[Prerequisites & Setup](https://github.com/KrystalZhang612/BloggieBlog/blob/main/README.md#prerequisites--setup)<br/>
[Method Running The Project(Locally)]()<br/> 
[Debugging&Troubleshooting]()<br/> 
[Synchronous Developing Notes]()<br/> 
[Testing Results]()<br/> 
# Prerequisites & Setup
## ***Set up Header***
In [index.html](https://github.com/KrystalZhang612/BloggieBlog/blob/main/Starter/index.html) under [Starter](https://github.com/KrystalZhang612/BloggieBlog/tree/main/Starter):<br/>
Make Header contains a navigation bar contains a menu of lists and their list-items:<br/>
```JavaScript 
<!-- Header -->
    <header class = "header" id = "header">
        <nav class = "navbar container">
            <a href = "./index.html">
                <h2 class = "logo">BloggieBlog</h2>
            </a>
            <div class = "menu" id = "menu">
                <ul class = "list">
    current">Home</a>
<li class="list-item">
    <a href = "#"  class = "list-link
</li>
<li class="list-item">
                        <a href = "#"  class =
"list-link">Categories</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Reviews</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">News</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class =
"list-link">Membership</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Contact</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Sign in</a>
                    </li>
                    <li class="list-item">
                        <a href = "#"  class = "list-link">Sign up</a>
                    </li>
</ul> </div>
        </nav>
    </header>
```
Click `Go Live`, and the 8 list-items shows on localhost as:<br/>















 