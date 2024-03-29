
# {{project-name}}-shopify-theme

A Shopify theme for _{{client-name}}_

By {{company-name}} (Location)

* Staging store: [https://{{project-code}}.myshopify.com](https://{{project-code}}.myshopify.com)

* Live store: [{{store-name}}.myshopify.com]({{store-name}}.myshopify.com)

Preview password: `....`


## Setup

`{{project-code}}` is a good enough prefix/key for any naming conventions

Standard Shopify theme style / (no alternate build systems - slate etc)

Starting with this `{{theme-name}}` theme _(IF starting from a 3rd party theme)_

An 'app' is setup for themekit authentication already (called _ThemeKit_)

`theme get --list -p={{password}} -s={{store-name}}.myshopify.com` to get the list of themes

Clone this repo in a folder called _sites/shopify/`{{project-code}}`_ or whatever you do

Move into that folder before pulling down the theme files from the live instance

`theme get -p={{password}} -s={{store-name}}.myshopify.com -t={{theme-id}}`

This will show any updates that may have happend on the live site / and you can commit them.


## Steps to not *blow it*

* ...

* 


## Requirements

Edge + (modern browsers)

Keep in mind that this .scss system Shopify has - might not autoprefix?

Probably shouldn't use grid yet...



## "Apps" (plugins/addons)

*

*



## Custom *components*

The little reusable things

* [x] "**Component name**" */snippets/component.name.liquid* `.class`
  
  - What it needs to do
  - How to build it



* [x] "**Component name**" */snippets/component.name.liquid* `.class`
  
  - What it needs to do
  - How to build it



## Custom *modules*

The bigger page 'section' - (often made up of the components ^)


* [x] "**Module name**" */sections/module-name.liquid* `.class`
  
  - What it needs to do
  - How to build it



* [x] "**Module name**" */sections/module-name.liquid* `.class`
  
  - What it needs to do
  - How to build it



## Pages

Not every Shopify site has all of these pages... 

Here's a list of pages (in order of imporatance). Mark the ones we're using with an **x**.


* [x] "**Home**" `/` *index.liquid* `.class`
  
  - Shows products and other informational modules
  - You could just add to cart here - and skip product index or detail pages
    - Which can lead you to ‘cart’
    - You might even be able to skip straight to checkout



* [x] "**Checkout**" `/unique-id/checkouts/unique-id` *...*
  
  - Fully handled by Shopify. We don't have access to this except on 'plus' accounts
  - One less thing to deal with. : )



* [x] "**Cart**" `/cart` *cart.liquid* `.uknown`

  - Shows products and other informational modules
  - You could just add to cart here - and skip product index or detail pages
    - Which can lead you to ‘cart’



* [x] "**Product Detail**" `/products/handle` *product.liquid* > *product.?.liquid* `.template-product`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.unknown`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.template-page.handle`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.unknown`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.unknown`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.unknown`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.unknown`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know



* [ ] "**Page**" `/pages/handle` *page.liquid* > *page.handle.liquid* `.unknown`

  - Description of use
  - How it's connected to the whole
    - any more specifics to know
