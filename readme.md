# Déjà-vu website

## Architecture

Styling files all located in assets > saas directory :
* blocks
  * _about-us.sass
  * _homepage.sass
  * _services.sass
  * _support.sass
* _configuration.sass
* _design-ststem.sass
* _font.sass
* main.saas

2 partials in layouts directory : one for the footer, one for the people block

Assets directory (located in static directory) includes :
* font for heading
* images and logos :
  * hero background images for homepage and about-us page
  * Déjà-vu's logos in white (full), blue (full, main logo) and black (outlined)
  * screenshot of Déjà-vu's HQ location

### Desing system

#### Footer

* Partial to display Déjà-vu's postal adress at the same level as the logo. Partial is located in layouts > partials > footer : site.html
* Credits lines added in i18n : fr.yml

#### Homepage

Special styling in _design-system.sass : 
* Header : navbar text content + logo in white
* Hero : background image added + title in white

#### About-us page

Special styling in _design-system.sass : 
* Header : navbar text content + logo in white
* Hero : background image added + title in white
* Breadcrumb : text in white

### Blocks

#### Homepage
#### About-us page
#### Services page
#### Support-us page

## About Osuny

[Documentation officielle sur developers.osuny.org](https://developers.osuny.org/docs/website/)

This project is tested with BrowserStack.
