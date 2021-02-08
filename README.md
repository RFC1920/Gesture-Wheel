Gesture Wheel allows players to have a convenient wheel that provide them the ability to use gestures.

## Usage
The plugin is preset to use Shift-RightClick to bring up the menu.  This cannot currently be customized, but should be relatively inconspicuous and conflict-free.  Let me know...

Once the player has clicked on the X to close or one of the gestures, the menu will close.

## Permissions
This plugin uses Oxide's permission system. To assign a permission, use oxide.grant <user or group> <name or steam id> <permission>. To remove a permission, use oxide.revoke <user or group> <name or steam id> <permission>.

    gesturewheel.use -- Required to use Gestures (if enabled)

## Configuration
The settings and options for this plugin can be configured in the GestureWheel.json file under the oxide/config directory. The use of a JSON editor or validation site such as jsonlint.com is recommended to avoid formatting issues and syntax errors.

```json
{
  "Command": "gestures",
  "Use Permission": false,
  "Button Radius": 100,
  "ActivationCode": 2176,
  "Close Button Color": "#FFB6B3DE",
  "Gesture Button Color": "#FF6666DE",
  "Gesture Button Size": 50,
  "Gestures": [
    {
      "Gesture Name": "wave",
      "Image": "https://i.imgur.com/pB3iZer.png"
    },
    {
      "Gesture Name": "victory",
      "Image": "https://i.imgur.com/PLbSgED.png"
    },
    {
      "Gesture Name": "shrug",
      "Image": "https://i.imgur.com/A3hHcgV.png"
    },
    {
      "Gesture Name": "thumbsup",
      "Image": "https://i.imgur.com/yWuhCMu.png"
    },
    {
      "Gesture Name": "chicken",
      "Image": "https://i.imgur.com/Qxhjf6N.png"
    },
    {
      "Gesture Name": "hurry",
      "Image": "https://i.imgur.com/vVKVeha.png"
    },
    {
      "Gesture Name": "whoa",
      "Image": "https://i.imgur.com/AFeGOrK.png"
    }
  ]
}
```

ActivationCode defaults to 2176, which is Shift-RightClick.  This can be customized in the configuration now.  For the brave, there are notes in the code about how to find a new one, or ask...

## Preview
![](https://i.imgur.com/PGvdmqZ.png)

## Credits
    Tricky - Maintenance up to 0.1.3
    Mevent - Initial development.
