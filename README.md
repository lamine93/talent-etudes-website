## project structure

project_root/
├── components/
│   ├── head.html
│   ├── preloader.html
│   ├── header.html
│   ├── footer.html
│   └── scripts.html
|   └── back.html
├── sections/
│   ├── about.html
│   ├── services.html
│   ├── portfolio.html
│   ├── pricing.html
│   ├── testimonial.html
│   └── contact.html
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
└── index.php


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
