# Horiseon Code-Refactoring!

## Correcting pre-written code and adding semantic HTML and CSS for accessibility and SEO purposes

### There were many things semantically incorrect with the way Horiseon's website was launched, sure it looked pretty and to the average user there may be no visual issues. However, when semantic HTML is **not** used when building a website and syntax primarily only consists of **div** classes, there is an inate problem with this process that involves **limiting users** and not allowing users who may have a disibility to view the website. Screen readers are commonly used by people who have visual disabilities and when HTML is writtin insemanticly, then screen readers cannot process this information.


## One example of some code block changes!
`code` 
``` 
<!-- You can see the code was written with some "Div" elements>
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
```
`code`
   ## Code written with "div" and "span" elements had to be changed!
`code`
```

<!--Here's our changes!-->
    <header class="header">
        <h1>Hori<mark class="seo">seo</mark>n</h1>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
    </header>
```
`code`

### In this project our goal was to **re-write** the existing code to solve this problem and in doing so we also improved the site's ability to be found on google with what is called Search Engine Optimization **"SEO"**

### Managing these changes while not changing the current look and layout of the website meant that certain changes had to be made within the **CSS** file of the website but we are confident that even the changes made in CSS are more efficent, **flow better**, and add clarity to the code.

![alt text](/assets/images/homescreen.png)
![alt text](/assets/images/homescreen2.png)

## Dynamic navigation bar!

### Additionally we changed the way the navigation bar works when scrolling through the webpage so that is follows the user down the page, so that at any time they can access the buttons within it.


