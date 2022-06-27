
## How To Customize The Module

In addition to setting the styles properties(primary_color, accent_color etc) from the CMS tool, you can extend the CSS by customizaing the module yourself, you can either add the custom CSS inside the custom css field from the module or add this using the KahaniModule custom style implementation below:



## Classes and definitions

### Kahani CSS Class
!> Note: CTA button means call to action button, this button usually appears between the unmute and the Kahani share button when the module is open.

|   CSS Class             |Definitions                          
|----------------|-------------------------------|
|kahani-cta-button-container button| Kahani CTA wrapper class |   
|.kahani-cta-button-container button          |CTA Button      |
|. kahani-story-title-image          |round image that appears at the top right corner of a chapter when the module is open|
|.kahani-photo-animated-overlay1          |Css class for the animate overlay 1 text, you can use this to customize the overlay as you like|
|.kahani-photo-animated-overlay2          |Css class for the animate overlay 2 text, you can use this to customize the overlay as you like|



Because the module is Sandboxed and won't be affected by outer CSS on host sites, you need to inject the custom CSS into the module by using the `window.KahaniModule.customCSS` parameter.

### Example CSS Injection:

```
window.KahaniModule.customCSS = `
.kahani-thumbnail, .kahani-cta-button-container button, .kahani-cta-button-container button:hover, button.kahani-cta-email-modal-submit,
button.kahani-cta-email-modal-loading-close {
    background-color: #5BBA9A;
}
.kahani-story-title-image {
    border-color: #5BBA9A;
}
.kahani-photo-animated-overlay1 {
    background-color: #FFA97D;
}
.kahani-photo-animated-overlay2 {
    background-color: #FFCB7D;
}
`
```



# CTA Types

|   CTA Name           |Definitions                          
|----------------|-------------------------------|
|Link CTA | a call to action button that links that opens a URL when clicked |   
|Klaviyo Email Modal         |Email modal to submit leads to Klaviyo     |



