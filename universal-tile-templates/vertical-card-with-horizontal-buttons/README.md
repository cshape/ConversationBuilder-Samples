# Vertical Card With Horizontal Buttons

![vertical-card-with-horizontal-buttons](Vertical_Card_With_Horizontal_Buttons.png)

```json
{
  "type": "vertical",
  "elements": [
    {
      "type": "image",
      "url": "https://i.imgur.com/7nSKrd0.png",
      "click": {
        "actions": [
          {
            "type": "link",
            "uri": "https://www.liveperson.com",
            "target": "blank"
          }
        ]
      }
    },
    {
      "type": "text",
      "text": "Thank you for using LivePerson's Conversational Cloud!",
      "tooltip": "Thanks!",
      "style": {
        "bold": true,
        "size": "small",
        "color": "#0F0943",
        "background-color": "#FFF"
      }
    },
    {
      "type": "horizontal",
      "elements": [
        {
          "title": "Continue",
          "type": "button",
          "click": {
            "actions": [
              {
                "type": "publishText",
                "text": "Continue"
              }
            ]
          },
          "tooltip": "Continue to next interaction."
        },
        {
          "title": "More info",
          "type": "button",
          "click": {
            "actions": [
              {
                "type": "link",
                "uri": "https://www.liveperson.com",
                "target": "blank"
              },
              {
                "type": "publishText",
                "text": "More info"
              }
            ]
          },
          "tooltip": "liveperson.com"
        }
      ]
    }
  ]
}

```
