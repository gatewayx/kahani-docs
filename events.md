## Kahani Module Events

There might be a need to perform some operation when the module is opened or closed, to do that, we have callback functions that are triggered when the module open or closes and you can attach to this function and it will be executed.

# KahaniModule properties
A reference to the KahaniModule object is available as `window.KahaniModule`

- `KahaniModule.isOpen`: A bool that is true when the widget is open.

## You can set some callbacks:
- `KahaniModule.onOpen`: A callback that fires when the widget is opened.

Example:

```
  <script>
    window.KahaniModule.onOpen = function(){
        // You can add your custom codes here.
        console.log("Module is open")
    }
  </script>
```
- `KahaniModule.onClose`: A callback that fires when the widget is closed.

Example:
```
  <script>
    window.KahaniModule.onClose = function(){
        // You can add your custom codes here.
        console.log("Module is open")
    }
  </script>
```