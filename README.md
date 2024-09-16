### Directory Descriptions

- **`components/`**: Contains reusable HTML component files.
  - `head.html`: Contains common `<head>` tags.
  - `preloader.html`: Code for the page preloader.
  - `header.html`: Code for the site header.
  - `footer.html`: Code for the footer.
  - `scripts.html`: JavaScript files included in the page.
  - `back.html`: Another reusable HTML component.

- **`sections/`**: Contains various sections of the main page.
  - `about.html`: "About" section.
  - `services.html`: "Services" section.
  - `portfolio.html`: "Portfolio" section.
  - `pricing.html`: "Pricing" section.
  - `testimonial.html`: "Testimonials" section.
  - `contact.html`: "Contact" section.

- **`assets/`**: Contains project assets.
  - `css/`: CSS stylesheets.
  - `js/`: JavaScript files.
  - `images/`: Images used in the project.

- **`index.php`**: Main PHP file that includes various components and sections to generate the webpage.

 ## configuring Contact Form

open ​contact.php​ file from ​assets​ folder of template and configure mailer function and email
address parameters to get it worked.
<!-- Replace You Email Here -->
$recipient = "your@gmail.com"

## Changing Default Color

As its default color is ​#f14836​ find out all ​#f14836​ from ​assets->css>style.css​ file and
replace it with your own color code, to change the color preset


## Changing Font Family

body {
font-family: "Nunito", sans-serif
}
To change the font-family you have to change the current ​font-family​ property with your own
font-family (from style.css file) and required weight​. But, make sure you have already
included the font on header (using CSS link) or on CSS (using import).
You can find all google fonts here: ​http://www.google.com/fonts
