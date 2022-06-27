## Quick Installation Steps

To install the widget on any site, there are two steps to follow

1. Add the `kahani-module` custom element and a `storyUrl` on any section of your page where you want the module to appear.
2. Add the script tag with the src pointing to the hosted bundle. (`<script src="https://cdn.prd.kahaniapp.com/kahani/kahani.js" />`)

!> NOTE: The custom element and script tags will most likely be generated from the Portal/CMS and all you need to do is paste on the page where you want to show the module so you can just skip the rest of the step or move to the [Customization](customization.md) section.


DEV CDN Url: 

Production CDN: 

### Example:
```
<kahani-module storyUrl="https://cdn.beta.kahaniapp.com/adam_cf.json"></kahani-module>
<script src="https://cdn.prd.kahaniapp.com/kahani/kahani.js">
```

Make sure to add the `<script>` tag before the closing of your `<body>` tag to ensure the scripts loads after the page assets has been loaded.





