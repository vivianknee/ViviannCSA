---
layout: none
title: Student Blog
---

<html>
<body>
<header>

  <div id="container">
    <nav>
      <ul>
        <li class="fork"><a href="{{site.baseurl}}/">Home</a></li>
        <li class="fork"><a href="{{site.baseurl}}/csa">CSA</a></li>
        <li class="fork"><a href="{{site.baseurl}}/blogs">Blogs</a></li>
        <li class="title"><a href="{{ site.github.repository_url }}#readme">View On GitHub</a></li>
      </ul>
    </nav>
  </div>
</header>
</body>
</html>

<style>
    body{
        margin: 0;
        background: white;
        font-family: 'Work Sans', sans-serif;
        font-weight: 300;
    }

    .container{
        width: 80%;
        margin: 0 auto;
    }

    header{
        background: #55a6da;
        padding: 20px;
    }

    header ::after{
        content: '';
        display: table;
        clear: both;
    }

    nav{
        float: center;
    }

    nav ul{
        margin: 0;
        padding: 0;
        list-style: none;
    }

    nav li{
        display: inline-block;
        margin-left: 70px;
        padding-top: 23px;
        position: relative;
    }

    nav a{
        color: #444;
        text-decoration: none;
        text-transform: uppercase;
        font-size: 14px;
    }

    nav a:hover{
        color: #000;
    }

    nav a::before{
        content: '';
        display: block;
        height: 5px;
        width: 100px;
        background-color: #444;

        position: absolute;
        top: 0;
        width: 0%;

        transition: all ease-in-out: 250ms;
    }

    nav a:hover::before{
        width: 100%;
    }

</style>

## Vivian's CSA Blog 
Hi, my name is Vivian! I'm a rising senior for the class of 2024! Excited to do another year of code code code. Here's a little bit about me:

<div style="text-align: center;">
    <img src="images/aboutme.png" 
        alt="about me" 
        width="500" 
        height="500"/>
</div>

# Here's my Tri 1 Schedule

[Click this](https://delnorte.powayusd.com/apps/bell_schedules/) for Del Norte's Schedule

| Class | Period | Homework |
|---|---|---|
| AP Stats | 1 | Check your understanding |
| AP Gov | 2 | Liberal and Conservative Notes |
| AP CSA | 3 | Setup local GitHub Pages and customize blogs |
| Honors MI | 4 | Share personal Locker |
| Off Roll | 5 | go home |
