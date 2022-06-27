## Kahani Module Troubleshooting

  

Listed below are issues that might arise and how to seamlessly debug them.

  

**Module is not showing up?**

- Check if you have added the Kahani module elements(`<kahani-module>`) on the page and also confirm if the script tag is appropriately added on the page.

- If the above is properly done, check if you have the correct story.json file attached to the `<kahani-module  storyUrl="STORY_URL_SHOULD_BE_HERE">`, you can also copy the link and try to access it directly to be sure you get back a good response.

**Google Analytics Events Are Not Published**
- If GA events are not getting published, you need to check and confirm that you have enabled the `analyticsLogging` flag on the Kahani module element. To do that, check if you have the analyticsLogging flag on the element and confirm that the value is set to true.
Example:

    <kahani-module analyticsLogging="true" storyUrl="STORY_URL_SHOULD_BE_HERE"></kahani-module>

  
