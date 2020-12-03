# Marketing-Agency-Website

## Website Links
[Site](https://ericchen96.github.io/Marketing-Agency-Website/ "Site") <br>
[Github](https://github.com/EricChen96/Marketing-Agency-Website "Github")

![Screenshot](./screenshot.JPG)

## Description

This site is for a Marketing Agency Company and it shows what the company has to offer to potential clients.
This activity was to make the site more accessible for users and to clean up code within the HTML and css files. 

## Changes Made
1. Added and cleaned up semantic HTML elements.
    - Took out 'Header' and 'Footer' class and made it container classes
        - Also changed it in the 'style.css' so it wouldn't be classes anymore
    - Changed all the '< div >' tags into other semantic HTML elements such as figure, main, section, aside
        - Figure refers to the figures such as the large classroom image
        - Main refers to the main body paragraphs detailing what the marketing agency would do such as optimize search engines, online reputation, and social media marketing

```html
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <!-- Navigation links to sections-->
        <nav>
            <!-- Unordered list of navigation links-->
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
        </nav>
    </header>
```
2. In the footer, changed the 'h2' tag into 'h4' and applied the same changes in 'style.css' so they refer to the correct area
3. Consolidated elements with the same attibutes such as .benefit-lead, .benefit-brand, .benefit-cost
4. Added alt tag to images so it would provide the alternate text if the image cannot be displayed
5. Added in ID for 'search-engine-optimization' in the 'search-engine-optimization' section so the Nav Link works 

