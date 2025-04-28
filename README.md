# Platform-Agnostic Development

An independent research of frameworks for platform-agnostic development.


| Backlog  | In Progress | Up Steam |
|----------|-------------|----------|
| JavaScript (Lynx+Cordova) | [Kotlin (KMP)](https://github.com/lyskouski/app-entertainment) |  [Dart (Flutter)](https://github.com/lyskouski/app-finance)  |
| Erlang (LiveView Native) | [Python (Kivy)](https://github.com/lyskouski/app-language) |
| C# (.NET MAUI) | |
| C (GLFW) | |
| Rust (Tauri) | |
| C++ (Qt) | |
| Go (Wails.io) | |
| Java (libGDX [or] Codename One) | |
| Delphi (FMX) | |
| Swift (SKIP.tools) | |
| [(?) _propose_](https://github.com/lyskouski/plan/issues/1) | |


# Summary
Rate is based on an interface support that is distributed as a part of SDK (10 .. -5; (+1) and (+2) for extensions), missing any extensions to solve it (-5 ... -10).

| Update Date |       Interfaces:| SRS | NLP | VUI | TTS | VA  | VB  | VR  | AR  | MR  | GUI | UX  | UI  | HF  |  GR | ET  | TG  | TUI | VK  | TST+PR |
|-------------|------------------|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|-----|--------|
| 2023-11-25  | Flutter (Dart)   | -10 | -10 | -10 | -10 | -8  | -8  | -10 | -10 | -10 | 0   | 0   | 0   | -10 | -10 | -10 | 0   | 0   | -10 | -10    |


|  Update Date | Platforms:                   | Android | iOS | macOS | tvOS | visionOS | watchOS | Windows | Linux | Mainframe | Web |
|--------------|------------------------------|---------|-----|-------|------|----------|---------|---------|-------|-----------|-----|
|  2023-11-25  | Flutter (Dart)               | 8       | 6   |  7    |  -10 | -10      | -5      | 8       | 5     | -10       | 5   |

_Notation: -10 {totally missing} ... 10 {strongly exists}_
 
Voice Interfaces:
- Speech Recognition Systems (SRS): Convert spoken language into text, allowing computers to understand and process voice commands.
- Natural Language Processing (NLP): Analyzes and interprets human language, enabling voice interfaces to understand context, intent, and meaning behind spoken words.
- Voice User Interfaces (VUI): The overall design and interaction between a user and a system using voice commands, often seen in virtual assistants like Amazon Alexa or Google Assistant.
- Text-to-Speech (TTS): Converts written text into spoken words, enabling devices to respond vocally to users.
- Voice Assistants (VA): Intelligent software programs that respond to voice commands and perform tasks, such as setting reminders, answering questions, or controlling smart home devices.
- Voice Biometrics (VB): Uses unique vocal characteristics for user identification and authentication.

Virtual Reality:
- Virtual Reality (VR): A computer-generated environment that simulates a physical presence, often experienced through a head-mounted display.
- Augmented Reality (AR): Integrates digital information or virtual elements into the user's real-world environment, enhancing the overall experience.
- Mixed Reality (MR): Combines elements of both physical and virtual realities, allowing interaction with both real and virtual objects.

Graphical Interfaces:
- Graphical User Interface (GUI): A type of user interface that allows users to interact with electronic devices through graphical elements such as icons, buttons, and menus.
- User Experience (UX): The overall experience a user has while interacting with a system, including aspects like usability, accessibility, and aesthetics.
- User Interface Design (UI Design): The process of designing the visual layout and interactive elements of a user interface.

Touchscreen Interfaces:
- Touch Gestures (TG): (tap) touching the screen briefly with a finger, (swipe) moving a finger across the screen in a specific direction, (pinch) using two fingers to zoom in or out by bringing them closer together or moving them apart, (rotate) turning two fingers in a circular motion to rotate an object; (multi-touch) the ability of a touchscreen to recognize and respond to multiple simultaneous touch points, enabling more complex gestures.
- Touch User Interface (TUI): The overall design and layout of user interfaces optimized for touch interaction.
- Virtual Keyboard (VK): An on-screen keyboard that appears when needed, allowing users to input text by tapping on the screen.
- Touch-sensitive Stylus (TST) + Palm Rejection (PR): A digital pen or stylus that can be used on touchscreens, providing more precision than fingers. PR - technology that prevents unintended touch inputs from the palm of the hand when using a stylus.

Others:
- Haptic Feedback (HF): Technology that provides tactile sensations to users, enhancing the sense of touch in interfaces.
- Gesture Recognition (GR): Allows users to interact with devices using gestures, often detected by cameras or sensors.
- Eye Tracking (ET): Monitors the movement of a user's eyes to determine where they are looking, often used in VR and AR applications.




## Support (Sponsorship)

If you'd like to contribute financially towards the efforts, please consider these options:

* [Github Sponsorship](https://github.com/users/lyskouski/sponsorship)
* [Paypal](https://www.paypal.me/terCAD)
* [Patreon](https://www.patreon.com/terCAD)
* [Donorbox](https://donorbox.org/tercad)

Or, [treat me to :coffee:](https://www.buymeacoffee.com/lyskouski).

**Disclamer:** your financial support won't anyhow affect the planned activities but might speedup them.

## License & Copyright

The content herein are all &copy; 2023 Viachaslau Lyskouski

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivs 4.0 Unported License</a>:
- **Attribution**: provide a link to the license, and indicate if changes were made
- **NonCommercial**: cannot be used for commercial purposes
- **NoDerivatives**: any modification (remix, transform, or build upon the material) cannot be done and distributed by your own. 
