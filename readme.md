# Déjà-vu website

## Architecture

Styling files all located in **assets > saas directory** :
* blocks
  * _about-us.sass
  * _homepage.sass
  * _services.sass
  * _support.sass
* _configuration.sass
* _design-ststem.sass
* _font.sass
* main.saas

**2 partials in layouts directory** : one for the footer, one for the people block

**Assets directory** (located in static directory) includes :
* font for heading
* images and logos:
  * hero background images for homepage and about-us page
  * Déjà-vu's logos in white (full), blue (full, main logo) and black (outlined)
  * screenshot of Déjà-vu's HQ location

## Design system

### Footer

* **Partial** to display Déjà-vu's postal adress at the same level as the logo. Partial is located in layouts > partials > footer : site.html
* **Credits lines** added in i18n : fr.yml

### Homepage

Special styling in **_design-system.sass** : 
* **Header** : navbar text content + logo in white
* **Hero** : background image added + title in white

### About-us page

Special styling in **_design-system.sass** : 
* **Header** : navbar text content + logo in white
* **Hero** : background image added + title in white
* **Breadcrumb** : text in white

## Blocks

### Homepage

Special styling in **_homepage.sass**.

Custom html selectors added through Osuny's backoffice include :
* `two-columns-chapter` : chapter in 2 columns
* `pages-cards` : for pages block : 4 pages cards displayed in 2 rows and aligned with the block's summary
* `with-cover` : for CTA block : font styling + bigger image
* `three-columns-chapter-one`, `three-columns-chapter-two`, `three-columns-chapter-three` : chapter in 3 columns

### About-us page

Custom html selectors added through Osuny's backoffice include :
* `centered-chapter` : chapter centered in the grid
* `definitions-about-us-page` : definitions block centered, title bold + divider thicker & blue on hover
* `right-aligned-button` : for CTA block : button right aligned + styling

**Partial** to add a line break in people's role description. Partial is located in layouts > partials > persons : person.html

### Services page

Custom html selectors added through Osuny's backoffice include :
* `chapter-title` : for chapter block : font styling on all services pages
* `right-aligned-cta` : for cta block : no title and text content and button styling on all services pages
* `right-aligned-definitions-consulting` :  for definition block : title bold + divider thicker & green on hover on consulting page
* `right-aligned-definitions-training` : for definition block title bold + divider thicker & pink on hover on training page
* `right-aligned-image` : for image block : margin top added btw title and image on advocacy page
* `custom-grid` : for gallery block : custom grid, square images and 3 images per row on material library page
* `right-aligned-definitions-material-library` : for definition block : title bold + divider thicker & brown on hover on training page

### Support-us page

Custom html selectors added through Osuny's backoffice include :
* `right-aligned-chapter` : chapter right aligned

## About Osuny

[Documentation officielle sur developers.osuny.org](https://developers.osuny.org/docs/website/)

This project is tested with BrowserStack.
