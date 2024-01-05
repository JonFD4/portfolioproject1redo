# Dream Tea House
Scenario: Dream Teahouse is a newly established premium teashop that offers a unique, high-quality tea blend as its flagship product. To portray their commitment to providing an exceptional tea-drinking experience, Dream Teahouse plans to create an informational website that will serve as an online resource for tea enthusiasts and potential customers. 
## Deployment
This is the live website
[Dream Teahouse](https://jonfd4.github.io/portfolioproject1-repeat/product-page.html)
# Overview
Create a functional and aesthetically pleasing website that is responsive, considers accesbility and is user-friendly.

**Remaking portfolio one**

# Design process
## User Perspective:
As a potential customer or a tea enthusiast, visiting Dream Teahouse's website, the user would expect the following:

1. Product Details: Users would want comprehensive information about the tea blend, including its unique flavors, origins, the ingredients used, and the detailed brewing instructions. This will help them understand the quality and uniqueness of the product.

2. Mission and Story: Users are interested in learning about the teashop's mission, values, and the story behind the creation of the signature tea blend. This information gives them a deeper connection and understanding of the brand.

3. Tea Education: Users would want access to educational content about tea, such as brewing tips, information on different types of tea, health benefits, and the proper way to serve and enjoy tea. They desire a platform that not only offers products but also educates and enriches their tea-drinking experience.

4. Product Availability: Users would appreciate a section that informs them about where the product can be purchased, both online and in physical stores. Details about shipping options, retail partners, and any upcoming events or promotions would be useful.

## Familiarity of users
**First time user**
* I want to understand the primary goal of the site.
* I want to the website to be easily navigable through the website and clear directions as well as CTAs.
* I want to find product sections and learn about the purpose of each product.
 * I want exploration and usage of the site to be intuitive
 
 **Returning and/ or Frequent user**
 * I want exploration and usage of the site to be intuitive
 * I want to be able to readily and easily purchase products


## Developer Perspective:
When developing the website for Dream Teahouse, the website developer would focus on the following aspects:

1. Engaging Design: The developer would create an aesthetically pleasing and user-friendly website design that aligns with the teahouse's brand identity. The design should evoke a sense of tranquility and elegance, reflecting the essence of tea.

2. Responsive Design: The developer would prioritize making the website fully responsive, ensuring it functions seamlessly across various devices (desktops, tablets, and mobile phones). This enhances the user experience and accessibility.

3. Integration of Multimedia: To enhance the user experience, the developer may integrate multimedia elements such as high-resolution images and videos demonstrating tea brewing techniques. These elements can make the website more engaging and informative.

4. SEO Optimization: The developer would implement search engine optimization techniques to improve the website's visibility on search engines. This helps potential customers find Dream Teahouse easily when searching for tea-related information or products.

5. The developers aims to make use and achieve understanding of the potential of CSS and its implementation for web development.

## Planning
* Imagery: The images used are vital in conveying peace and traquility witouth overshadowing the writting context of the page. The ones used in the products sections are to attract user and give them an idea of the product they will be receiving.

* Colours: Notably, the primary colour seen consitently is green colour palette. This represents health. Additional colours including black and white used, especially on text, is to create contrast.

* Fonts: `cursive, sans-serif` font used creates elegance and keeps the page from being overly uniformed and boring.
## WireFrames
Balsamiq was used in the design of the website.

The structure of the image was designed with the intention that not all of it will be implemented in the website, due to stylistic changes and determine what fits the aim of the website.

<details>
<summary> Lo-fi prototyping of dream tea house website with balsamiq</summary>

* Desktop wireframe
  - [Landing page 1](docs/ReadmeImg/Dream-Teahouse-planning/landing-page.png)
  - [Landing page 2](docs/ReadmeImg/Dream-Teahouse-planning/dream-teahouse-landing-page.png)
  - [About](docs/ReadmeImg/Dream-Teahouse-planning/About-us.png)
  - [product carousel section](docs/ReadmeImg/Dream-Teahouse-planning/product-carousel.png)
  - [popular product section](docs/ReadmeImg/Dream-Teahouse-planning/popular-product.png)
  - [blog section](docs/ReadmeImg/Dream-Teahouse-planning/Blog-desktop.png)
  - [footer section](docs/ReadmeImg/Dream-Teahouse-planning/footer.png)
  <br>
* Mobile wireframe
    - [landing page mobile 1](docs/ReadmeImg/Dream-Teahouse-planning/mobile-layout/smaller-screen-landing-page.png)
    - [landing page mobile 2](docs/ReadmeImg/Dream-Teahouse-planning/mobile-layout/pt2-landing-page-mobilepng.png)
     - [About ](docs/ReadmeImg/Dream-Teahouse-planning/mobile-layout/smaller-screen-about.png)
     - [product carousel mobile screen](docs/ReadmeImg/Dream-Teahouse-planning/mobile-layout/product-carousel-smaller-screen.png)
     - [Full product page](docs/ReadmeImg/Dream-Teahouse-planning/mobile-layout/product-html-smaller-screen.png)
</details>

## Features

## Tools and technologies
 **Language**
 - CSS
 - JavaScript
 - HTML

**Tools**
- VS Code
- git and github
- Balsamiq

## Test and validation
validations was carried out and used to make necessary improvements to code for final products.
<details>
<summary> Lighthouse validation </summary>
The accessibility aspect of the code was challenging. Some flaws highlighted by lighthouse validator  and fixed by developer included: 

[Find lighthous errors](validation-images/lighthouse)

**Landing page**
* forms id and label mismatch
* image loading issues: not fixed
* contrast issues

**Product page**
* Input label mismatch- labels not necessary
* buttons do no have accessibility names.

**Thank you page**
No meta description

* Background image loading issues on the homepage
 - This caused reduction in accessibility and performance. Nonetheless, the other pages had better performance and accessibility.
</details>

<details>
<summary>Fixing and debugging<summary>

* lighthous errors were fixed and tested again. Some errors such as image loading were not resolved since they will break the website.

* There were a few minor errors with CSS according to jigsaw validator. The errors can be seen in [here](validation-images/cssjigsaw.png). These were fixed.

* A lot of the [w3c erros](validation-images/w3c) found through out the html were similar:
 most consist of bad practices and trail slashing. I took note of this and took teh effective time to make the relevant changes in accordance with w3c validation standards.

* The very low performance of the homepage was because of the hero background images and animation. This feature was taken out.
</details>

<details>
<summary>Errors not fixed<summary>

**Lighthouse home page**

* Background and foreground colors do not have a sufficient contrast ratio.
* <frame> or <iframe> elements do not have a title
* Elements with visible text labels do not have matching accessible names.
* Image elements have [alt] attributes that are redundant text.

**lighthouse product page**
* Buttons do not have an accessible name
* Elements with visible text labels do not have matching accessible names.
* Image elements have [alt] attributes that are redundant text.
* Select elements do not have associated label elements.
</details>

### Form testing
* Forms were tested to and ensured to send user to the right location
* Developer ensured forms indicated required alert when user clicked on submit button

### links testing
* The links were verified to make sure they sent user to the right location
* Social media elements were not presented as links since there is no page to direct user.

### Browser Testing
The Website was tested on Google Chrome, Firefox, and safari browsers with no major issues noted except for the display of favicon.