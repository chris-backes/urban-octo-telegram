# Code Refactor Starter Code

Refactored the HTML and CSS for Horiseon website for GWU Bootcamp, Module 1 weekly challenge.

The file contains an HTML document and CSS document, as well as additional images used in the webpage.

## Structure

```shell
|-- Develop
    |-- assets
    |-- index.html
        |-- css
            |--stlye.css
        |-- images
            |-- four .jpg files and three .png files
```

## Cloning the repo

1. Navigate to the URL of the repository: https://github.com/coding-boot-camp/urban-octo-telegram

2. Above the list of files in a 'Code' button. click it and select either HTTPS or SSH, copying the text.
   ![image of the code button](https://docs.github.com/assets/images/help/repository/code-button.png)
3. Open Git Bash and enter the following steps

```
git cd [location of where you would like directory places]
git clone https://github.com/chris-backes/urban-octo-telegram-v2.git
```

## Remote Site

The remote site can be found here: https://chris-backes.github.io/urban-octo-telegram/

## Website Description

The website is for a fictional marketing org. and promotes their offerings:

- Search Engine Optomization
- Online Reputation Managmenet
- Social Media Marketing
  Each of these is organized into its own semantic HTML element, "section", ordered one on top of the other, with a fourth section on the benefits of the section devoted to the upsides to en.gaging in their services on the right side of each of these, arranged vertically

The CSS is divided into Element Selectors and Class Selectors (and Element Slectors within Class Selectors), and the CSS was refactored such that classes which could be eliminated, were eliminated, such that:
`<footer class="footer">`
became:
`<footer>`
And the CSS changed from:
`.footer { ... }`
To:
`footer { ... }`

## Screenshot

![Horiseon Screenshot]
