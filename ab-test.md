## AB Test Module Configuration

Some clients might require GO test where we want to hide the module for 50% of the users, because the module CSS and HTML are encapsulated, the right approach would be to add an add a parent DIV around the <kahani-module> element and hide that instead, for example:


```
<div id=”kahani_parent”>
     <kahani-module storyUrl="<Path To Client Stories.json file>" disableLogging="false"></kahani-module>
</div>
```

