# <span style="color:lightblue; text-shadow: 0 0 20px blue;">IntelliBeams</span> - <span style="color:green; font-weight:bold;">V1.3.0</span> / <span style="color:grey; font-weight:bold; font-size: 15px;">Singleplayer Only</span>

# 🙎🏼‍♀️ Overview

The <span style="color:lightblue; text-shadow: 0 0 20px blue; font-size: 15px;">**IntelliBeams**</span>  script is a GTA V mod that enhances vehicle lighting systems to improve realism and functionality, especially under low-light conditions. It automatically adjusts high beams based on conditions like vehicle speed, road type, and the presence of other vehicles.

# 🚀 Features

- **(1.) Automatic High Beams:**
  - <b>Automatically toggles high beams based on conditions:</b>
    - Speed above a threshold 30MPH default.
    - Driving on designated "dark roads" with low ambient lighting.
    - No other vehicles are detected in front within a specified detection distance.
    - Speed, Roads, Times, and Distance are specified in the INI file.

- **(2.) Vehicle Detection:**
  - Scans nearby vehicles and activates high beams or adjusts other lighting as needed based on a set proximity (Player or AI). Aircraft, Boats will not use IntelliBeams

- **(3.) Time-Based Headlights:**
  - Headlights automatically turn on/off at a set hour & minute specified in the INI file.
  - The lights will turn off during the daytime.
  - Times can be configured in the INI file.

- **(4.) Realistic Lights:**
  - <b>Authentic Number Plate Illumination:</b>
    - Accurately replicates the operation of number plate lights, ensuring a more realistic lighting effect. Other realistic lighting effects will be added in future updates.

- **(5.) Realistic Braking:**
  - <b>Emergency Braking:</b>
    - Activates automatically when the vehicle speed exceeds 60 MPH, simulating a high-speed emergency stop.
  - <b>Dynamic Brake Lights:</b>
    - Brake lights are now automatically triggered when the vehicle comes to a complete stop, enhancing realism by reflecting the vehicle's deceleration state.
  - Emergency Braking Speed, Dynamic Brake Lights, are specified in the INI file.
___
# ⚡️ Performance Advisory

IntelliBeams is optimized for performance, but if any issues arise, please report them for support and troubleshooting.

# 🛠️ Requirements
- **ScriptHookV:** [Download ScriptHookV](http://www.dev-c.com/gtav/scripthookv/)
- **ScriptHookVDotNet-nightly:** [Download ScriptHookVDotNet](https://github.com/scripthookvdotnet/scripthookvdotnet-nightly/releases/latest) - Any version from and above **|> ᴠ3.6.0 / 139 <|**

# 🔧 Installation
1. Simply drag and drop the `scripts` folder into the root directory of your Grand Theft Auto V installation.

# ⚙️ How to Use
The script will activate automatically in-game. However, you also have the option to customize the settings via the INI file in GTAV/scripts/Code-Master-Configs, which appears once you run the mod for the first time.

# 📋 Versions & Changelog

> ## ⭐ V1.3.0 | New Features & Enhancements <span style="color:green; display: block; text-align: right; font-size: 12px; font-weight: bold;">Current Version<span style="color:white; font-size: 14px; text-shadow: 0 0 10px white; text-align: right;"> /</span><span style="color:green; font-size: 14px; text-shadow: 0 0 10px green; text-align: right;"> 🟢</span></span>
>
>- <span style="color:green"> 📝 <span style="font-weight: bold; color: white;">Ini File Updates:</span> A system was introduced to prevent overwriting existing INI settings. With each update, the system now only adds new settings or deletes old settings, preserving user customizations</span>
>
>- <span style="color:green"> 💡 <span style="font-weight: bold; color: white;">Realistic Lights:</span> Implemented real lights (Number Plate Supported at the moment).</span>
>
>- <span style="color:green"> 🔑 <span style="font-weight: bold; color: white;">Engine Key Function:</span> Introduced a new Engine Key functionality, allowing players to toggle the engine on and off using a specific keybinding editable in the INI file (e.g., <code>E</code> to start/stop). Adding an extra layer of realism and immersion for vehicle control. When you get into a vehicle you have to toggle the engine using the EngineKeif set and if AllowEngineControl is true in the INI.</span>
>
>- <span style="color:green"> 🔑 <span style="font-weight: bold; color: white;">Headlight Key Functionality:</span> A new feature has been implemented, enabling players to control vehicle headlights with the default game key, <code>H</code>. This allows for seamless toggling of headlights on or off during gameplay. The engine has to be on for this to work.</span>
>
>- <span style="color:green"> 🛑 <span style="font-weight: bold; color: white;">Emergency Brake (Beta):</span> Added a beta version of Emergency Brake functionality, which triggers brake light flashing when the emergency brake is activated or the player is speeding in certain conditions. This adds a more realistic emergency brake system, allowing players to use <code>S</code> for braking with enhanced visual feedback. <b style="color: white;">Please give us feedback so we can improve this in future updates.</b></span>
>
>- <span style="color:green"> ⚡ <span style="font-weight: bold; color: white;">Enhanced High Beam Flash for Players & AI:</span> Improved flash patterns and delay settings to deliver a more realistic lighting effect.</span>
>
>## <code>Important Notice for V1.3.0:</code><span style="color:darkorange; display: block; font-size: 12px; font-weight: bold;">Prior to launching the game with IntelliBeams V1.3.0, we highly recommend removing the <code>IntelliBeams.ini</code> file located in the <code>scripts > Code-Master-Configs</code> directory. If you have made any customizations, please ensure you create a backup of this file. Once the game is launched, a new configuration file will be generated, allowing you to reapply your settings. Note that this backup process is only necessary for this version - future updates will automatically preserve your settings.</span>
>---

> ## ⭐ V1.2.0 | Enhanced Improvements <span style="color:darkorange; display: block; text-align: right; font-size: 12px; font-weight: bold;">Previous Version<span style="color:white; font-size: 14px; text-shadow: 0 0 10px white; text-align: right;"> /</span><span style="color:darkorange; font-size: 14px; text-shadow: 0 0 10px darkorange; text-align: right;"> 🟠</span></span>
>
>- <span style="color:green"> 🚘 <span style="font-weight: bold; color: white;">Anti-Dimming Control (New Boolean Option):</span> Added a configurable boolean option that allows players to deactivate the auto-dimming of headlights when exiting the vehicle with the engine running, giving players more control over vehicle lighting behavior.</span>
>- <span style="color:green"> ✨ <span style="font-weight: bold; color: white;">AI High Beam Behavior Refined:</span> Tweaked the Player & AI high beam flashing timings to more closely align with real-world driving dynamics, enhancing the authenticity of traffic interactions.</span>
>- <span style="color:green"> 🚨 <span style="font-weight: bold; color: white;">Enhanced Brake Light Behavior:</span> Brake lights now activate when the player's speed drops below 1.0 or while holding the brake key <code>(S)</code>. This ensures more realistic lighting behavior for vehicles.</span>
>- <span style="color:green"> 💡 <span style="font-weight: bold; col[or: white;">Allow Auto High Beam (New Boolean Option):</span> This option enables automatic high beam control for both player and AI vehicles, with the ability to allow or restrict the use of auto high beams for each.</span>
>---

> ## ⭐ V1.1.0 | Enhanced IntelliBeam Functionality <span style="color:darkorange; display: block; text-align: right; font-size: 12px; font-weight: bold;">Previous Version<span style="color:white; font-size: 14px; text-shadow: 0 0 10px white; text-align: right;"> /</span><span style="color:darkorange; font-size: 14px; text-shadow: 0 0 10px darkorange; text-align: right;"> 🟠</span></span>
>
>- <span style="color:green"> 🚘 <span style="font-weight: bold; color: white;">Anti-Dimming Function:</span> Headlights will no longer dim when the player is out of the vehicle with the engine running.
>- <span style="color:green"> 🚨 <span style="font-weight: bold; color: white;">AI Flashing High Beams:</span> When the player flashes their high beams, nearby AI vehicles will now flash their high beams and beep their horn in response, mimicking real-life traffic behavior.</span>
>- <span style="color:green"> 📝 <span style="font-weight: bold; color: white;">Enhanced Configuration File:</span> The headlight activation and deactivation times have been refined, with significant improvements made to the configuration settings for better flexibility and control.</span>
>- <span style="color:green"> 🚦 <span style="font-weight: bold; color: white;">Player Vehicle Brake Lights:</span> The player's vehicle brake lights will automatically activate when the vehicle comes to a stop.</span>
>---


> ## ⭐ V1.0.0 | Initial Release <span style="color:grey; display: block; text-align: right; font-size: 12px; font-weight: bold;">Outdated Version</span>
>
>- <span style="color:grey"> 🆕 <span style="font-weight: bold; color: white;">Initial Release:</span> The script is now available for download.
</span>
>---

# 🔮 Future Updates
### We are continuously working on improving IntelliBeams. Future updates may include:

- **Realistic Lights Enhancement:** Expand the scope of visible lights beyond just number plates for a more immersive and realistic experience.

- **Further Customization Options:** Add more configurable settings, such as the ability to define more complex lighting profiles for different environments.

# 🛡️ Security & Code Protection
To safeguard against unauthorized duplication, IntelliBeams now includes encrypted DLL files.


# 📈 Feedback & Support
Your feedback is appreciated! For suggestions, support, or bug reports, reach out via:

<a href="https://discord.gg/3MKyscCXkk" target="_blank">
  <img src="https://avatarfiles.alphacoders.com/367/thumb-1920-367017.png" style="width: 50px; height: auto;" alt="Description of the photo">
</a>

#### [© Code Master 2024](https://codemaster.ltd/)
