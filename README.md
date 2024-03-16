![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/f8706c3e-cb4c-4daf-8c8b-3bca611a5a38)# Weapon FOV & Clipping Fix
[![Version](https://img.shields.io/badge/Version-1.0.2-3FB911?style=flat&logo&logoColor=white&labelColor=4d4d4d)](https://github.com/gerlogu/WeaponFOVAndClippingFix/releases/tag/v1.0.2)
![Asset Type](https://img.shields.io/badge/Blueprints-0086d9?style=flat)
![Asset Type 2](https://img.shields.io/badge/Materials-00d998?style=flat)
![Asset Stars](https://img.shields.io/github/stars/gerlogu/WeaponFOVAndClippingFix?style=social)</br>
An Unreal Engine asset to fix the most common FPS problems in an easy way 🔫

https://user-images.githubusercontent.com/55363746/225155677-d2e5db50-5fc6-4e0e-9e7a-af6921dbe558.mp4

##### <div align="center">If you find this asset useful, please support it by giving a "★ Star" to the repository, thank you!</div>

## Description
***Latest Update:*** _July 24th, 2022_

***Note:*** _A good understanding of Blueprint Components, Materials & Material Functions will be useful if you want to modify content._

***[Video Preview](https://www.youtube.com/watch?v=B9kg524mwxU) / [Documentation](https://gerlogu.com/wp-content/uploads/2022/05/Weapon-FOV-and-Clipping-FIX-Users-Manual.pdf) / [Official Website](https://gerlogu.com) / [GitHub Profile](https://github.com/gerlogu)***


### 📚 Overview

This asset allows you to fix the most common problem in FPS projects: **Clipping and FOV**. It includes **customized Material Functions** that allows you to **fix every mesh material** in a First Person Shooter.

### 📣 Content

This is what you can modify:

- Material Functions
- Weapon FOV value
- Weapon Clipping
- Weapon Camera Sway
- Weapon Movement Sway

### 🛠 How to Use

Read the manual here: [HERE](https://gerlogu.com/wp-content/uploads/2022/05/Weapon-FOV-and-Clipping-FIX-Users-Manual.pdf)

### ✔ Additional Content

This asset also includes the following content, useful for any First Person Game:
- **Weapon Sway Components:** Add it to your character and make your game feeling more professional

### 🗣 Contact

If you have any questions, contact me and I will answer you and include your question into the User's Manual.

- **OFFICIAL WEBSITE:** www.gerlogu.com
- **CONTACT EMAIL:** contact@gerlogu.com

### ⚠ Disclaimer

No fire effects nor animations are included.

## Technical Information

**Features:**

- Fix First Person Weapon Clipping **by using included Material Functions**
- Fix First Person Weapon FOV **by using included Material Functions**
- Customize World FOV and Weapon FOV **separately**
- Includes fully customizable Material Functions
- **Camera Sway Component** that allow your weapon to move with the camera
- **Movement Sway Component** that allow your weapon to move with the player lateral movement

**Number of Blueprints:** 10

**Number of Macro Libraries:** 1

**Number of Data Tables:** 1

**Number of Structures:** 1

**Number of Material Functions:** 3

**Number of Materials:** 6

**Texture Resolutions:** Anyone is valid

**Input:**

*Action Mappings*
- Jump: Gamepad Face Button Down | Spacebar

*Axis Mappings*
- HorizontalMovement: D (1.0) | A (-1.0) | Gamepad Left Thumbstick X-Axis (1.0)]
- VerticalMovement: W (1.0) | S (-1.0) | Gamepad Left Thumbstick Y-Axis (1.0)]

**Network Replicated:** No

**Supported Development Platforms:** All

**Documentation:** [HERE](https://gerlogu.com/wp-content/uploads/2022/05/Weapon-FOV-and-Clipping-FIX-Users-Manual.pdf)

**Important/Additional Notes:** Contact me and I will answer you and include your question into the User Manual.

## Documentation

### Basic setup

To carry out the inclusion of this fix, you need to follow these steps:
- Open your arms & weapon parent material.
- Add the following material function: MF_FOV_Clipping_FIX
![Image-6](https://user-images.githubusercontent.com/55363746/180665874-135b2475-737e-4a26-abc1-d1fef1944ba2.jpg)

Now everything is set up! Remember that you need an scalar parameter (usually named
FOV or Field Of View) that will determine the custom weapon FOV. You can update this
parameter during the game execution.

### Weapon Sway
This project also includes a weapon sway system that includes the following sway types:
- Camera movement sway
- Character movement Sway
Both systems are located in two independent components located in the following path:
`Game/WeaponFOVandClippingFix/FOVandClippingFix/Character/Components`
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/0a6c649c-baf5-4f24-aa52-b8611e9f69a7)

Ensure you have your arms and weapon mesh located inside two different scene components.
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/3d574316-6942-4194-a21b-d769aeff9c33)

### Camera Sway
This component need to be initialized in the actor `Begin Play`.

![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/fc4e92c0-e267-446f-914c-e5760a9bac18)

Then the effect must be updated in the Tick Event (or in a Timer).
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/1a97382d-000b-4e64-9fb9-a3ae2203edda)

Now you can configure the different component variables.
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/f8951e02-1d25-4cc6-9ca7-c4df2d103e08)

### Movement Sway

This component needs to be initialized in the actor `Begin Play`
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/940f55ce-53bd-478f-a609-b488a892ee04)

Then the effect must be updated in the Tick Event (or in a Timer)
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/f8c87a98-c588-4273-be2d-d2b00cde3544)

Now you can configure the different component variables.
![image](https://github.com/gerlogu/WeaponFOVAndClippingFix/assets/1442796/b4d1d29b-f8cf-4ab1-9036-4c765edb9032)

With this, your weapon movement sway is configured.

## Images

![Image-1](https://user-images.githubusercontent.com/55363746/180665862-2afb39e0-d410-4cd5-b599-820b8aaf24fd.jpg)
![Image-2](https://user-images.githubusercontent.com/55363746/180665868-570311df-5fa5-44de-828b-b6638bdd2422.jpg)
![Image-3](https://user-images.githubusercontent.com/55363746/180665869-c0acc161-2840-465b-b422-a3d087425110.jpg)
![Image-4](https://user-images.githubusercontent.com/55363746/180665870-1d20ce41-29b4-44b0-9a1e-30b3fb442639.jpg)
![Image-5](https://user-images.githubusercontent.com/55363746/180665873-86e5ee74-17f0-4e01-bea4-5ff167b6e32a.jpg)
![Image-6](https://user-images.githubusercontent.com/55363746/180665874-135b2475-737e-4a26-abc1-d1fef1944ba2.jpg)





