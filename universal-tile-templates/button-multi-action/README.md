# Multi Action Button

![button-multi-action](Button_multi_Action.jpg)

```json
{
  "title": "Multi Action Button",
  "tooltip": "Click me!",
  "type": "button",
  "style": {
    "color": "#FFF",
    "background-color": "#3E47A0",
    "size": "medium"
  },
  "click": {
    "actions": [
      {
        "type": "publishText",
        "text": "Button Clicked!"
      },
      {
        "type": "link",
        "uri": "https://www.liveperson.com",
        "target": "blank"
      }
    ]
  }
}

```
