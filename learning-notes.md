# Learning notes while building my personal website

#### Full content page, without "load more" button

Open the "theme editor", go to the page and select desired number of posts per page.

#### Preload web fonts

Insert the following line inside the `<head>` of the header.php file:
`<link rel="preload" href="https://fonts.googleapis.com/css?family=Work+Sans&display=swap" as="style">`
Refer to this [link](https://ashton.codes/preload-google-fonts-using-resource-hints/).

#### Use web fonts

Insert the following line inside the `<head>` of the header.php file, after the font are preloaded:
`<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Work+Sans&display=swap">`
