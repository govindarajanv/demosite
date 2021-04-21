Front Matter  starts with --- and ends with ---

pre-defined and custom variables

site - global variable about site  site.pages, site.posts  and site.data
page - about page
content - 

Liquid templating language
Built by Shopify

output markup uses two curly braces and used for rendering {{ site.title }}

Tag Markup for performing logic uses {% %}

{% if page.title %}
{% endif %}

Steps:

1. Reads config file
2. reads other files and checks for Yaml front matter
3. uses Liquid templating language to process the content and templates
4. reads the assets
5. generates final output into folder _site

## Posts

posts should be under _post
naming convention Y-M-D-title.markup

