# ReplyAction Themes

If you have no idea what this tweak does, oh man you're missing out. Check it out on Havoc!

<a href="https://havoc.app/package/replyactions"><img src="https://docs.havoc.app/img/badges/get_square.png" alt="drawing" style="width:200px;"/></a>

This is a documentation on how to create custom themes yourself for ReplyActions. 

I've designed the tweak to be fully customizable, so everyone can **_tweak_** the way it looks according to their own liking :)

Themes are stored in `/var/jb/Library/ReplyActions/Themes/`as JSON file with its corresponding properties

##### Here's an example of how a theme file looks like (Classic Black.json):
```
{
    "name": "Classic Black",
    "modalBackgroundColor": "#000000",
    "modalBackgroundAlpha": "0.2",
    "modalCornerRadius": "40",
    "titleColor": "#EBE0E0",
    "titleFontSize": "18",
    "messageColor": "#EBE0E0",
    "messageFontSize": "16",
    "lineColor": "#39393A",
    "defaultPhotoAvatarBackgroundColor": "#D3D3D3",
    "defaultPhotoAvatarTintColor": "#A9A9A9",
    "topButtonsTintColor": "#716B6B",
    "topButtonsBackgroundColor": "clear",
    "textBoxBackgroundColor": "#333333",
    "textBoxColor": "#EBE0E0",
    "textBoxPlaceholderColor": "#A9A9A9",
    "textBoxFontSize": "14",
    "textBoxCornerRadius": "10",
    "sendButtonDefaultServiceBackgroundColor": "#333333",
    "sendButtonIMessageServiceBackgroundColor": "#007AFF",
    "sendButtonSMSServiceBackgroundColor": "#34C759",
    "sendButtonTintColorColor": "#EBE0E0",
    "bottomButtonsColor": "#EBE0E0",
    "bottomButtonsBackgroundColor": "#333333",
    "bottomButtonsCornerRadius": "6"
}
```

###
### &nbsp;

### Here's a table showing each properties and what it corresponds to:

| Property                                         | Type                | Description                                                  | Example               |
|--------------------------------------------------|---------------------|--------------------------------------------------------------|-----------------------|
| `name`                                          | String              | The name of the theme **(file name should match this)**                                      | `"Classic Black"`     |
| `modalBackgroundColor`                          | String (Hex Color)  | Background color of the modal.                              | `"#000000"`           |
| `modalBackgroundAlpha`                          | String              | Alpha transparency level of the modal background.           | `"0.2"`               |
| `modalCornerRadius`                            | String              | Corner radius of the modal for rounded corners.             | `"40"`                |
| `titleColor`                                    | String (Hex Color)  | Color of the title text.                                    | `"#EBE0E0"`           |
| `titleFontSize`                                 | String              | Font size of the title text.                                | `"18"`                |
| `messageColor`                                  | String (Hex Color)  | Color of the message text.                                  | `"#EBE0E0"`           |
| `messageFontSize`                               | String              | Font size of the message text.                              | `"16"`                |
| `lineColor`                                     | String (Hex Color)  | Color of the lines or dividers in the UI.                  | `"#39393A"`           |
| `defaultPhotoAvatarBackgroundColor`            | String (Hex Color)  | Background color for default photo avatars.                 | `"#D3D3D3"`           |
| `defaultPhotoAvatarTintColor`                  | String (Hex Color)  | Tint color for default photo avatars.                       | `"#A9A9A9"`           |
| `topButtonsTintColor`                           | String (Hex Color)  | Tint color for the top buttons.                             | `"#716B6B"`           |
| `topButtonsBackgroundColor`                     | String              | Background color for the top buttons. Can be a digit or "clear"                       | `"clear"`             |
| `textBoxBackgroundColor`                        | String (Hex Color)  | Background color of the text input box.                     | `"#333333"`           |
| `textBoxColor`                                  | String (Hex Color)  | Color of the text in the input box.                         | `"#EBE0E0"`           |
| `textBoxPlaceholderColor`                       | String (Hex Color)  | Color of the placeholder text in the input box.             | `"#A9A9A9"`           |
| `textBoxFontSize`                               | String              | Font size of the text in the input box.                     | `"14"`                |
| `textBoxCornerRadius`                           | String              | Corner radius of the text input box for rounded corners.    | `"10"`                |
| `sendButtonDefaultServiceBackgroundColor`      | String (Hex Color)  | Background color of the send button for default service.   | `"#333333"`           |
| `sendButtonIMessageServiceBackgroundColor`     | String (Hex Color)  | Background color of the send button for iMessage.  | `"#007AFF"`           |
| `sendButtonSMSServiceBackgroundColor`          | String (Hex Color)  | Background color of the send button for SMS.       | `"#34C759"`           |
| `sendButtonTintColorColor`                      | String (Hex Color)  | Tint color of the send button.                              | `"#EBE0E0"`           |
| `bottomButtonsColor`                            | String (Hex Color)  | Color of the bottom buttons.                                | `"#EBE0E0"`           |
| `bottomButtonsBackgroundColor`                  | String (Hex Color)  | Background color of the bottom buttons.                     | `"#333333"`           |
| `bottomButtonsCornerRadius`                     | String              | Corner radius of the bottom buttons for rounded corners.    | `"6"`                 |


### Warning
- All properties are needed. You can't leave out any property, or tweak won't work.
- I would suggest creating a new theme instead of overwriting an existing theme so it's cleaner.
- **DON'T DELETE THE DEFAULT THEME (CLASSIC BLACK) OR THE TWEAK WON'T WORK.** Classic black is the default fallback theme **_in case_** tweak preferences resets/if you lose tweak preferences for some reason. I didn't hardcode any themes since I want everyone to have full flexibility on customization. Just don't do silly things, you'll be fine, mmkay?

