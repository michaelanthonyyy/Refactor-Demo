# Refactor Demo



## Summary
Horiseon is a marketing agency that wants their site that is optimized for search engines as well as a codebase following accessibility standards by anybody who reads the code. 
<br>
<br>

## Site Picture
![Site](assets/images/01-html-css-git-homework-demo.png)
<br>
<br>

## What Was Changed
Tasked by marketing agency to optimize the websites while stylizing accessibility of the code. Links on the page were fixed to properly bring visitors of the webpage to be brought to the appropriate content. The style.css page was reworked to reflect any changes made in the index.html as well as reordering prompts into the correct sequential order. Different elements in index.html were renamed for ease in any future changes that may be made by another party.
<br>
<br>

## Code Snippet
```html
    <!-- changed div class to nav to specify navigation links at top of website -->
    <main class="content">
        <section id="search-engine-optimization" class="search-engine-optimization">
            <!-- fixed search engine optimization leading to ease of access-->
            <img src="./assets/images/search-engine-optimization.jpg" alt="Search Engine Optimization" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" alt="Online Reputation Management" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>d
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" alt="Social Media Marketing" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
            <!-- added alt text to images in each nav section for more search engine optimization-->
        </section>
        <!-- renamed div to section to section off content sections of the webpage -->
    </main>
```

```css
.social-media-marketing, 
.online-reputation-management, 
.search-engine-optimization {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
    /* snippet of a section of code that was consolidated for cleaner looking style.css page */
}
```
<br>
<br>


## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

<br>
<br>

## Deployed Link

[Live Link "Horiseon Social Media Marketing"](https://michaelanthonyyy.github.io/refactor-demo/)

<br>
<br>

## Authors

**Michael Medina** 
- [Link to Github](https://github.com/michaelanthonyyy)
- [Link to LinkedIn](https://www.linkedin.com/in/michael-medina-22aa70200?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B311BosSLTMS4JkhAfkX61A%3D%3D)

<br>
<br>

## Acknowledgement

- This project is was made possible by the UC Berkeley Extension Program for the original code and assets
