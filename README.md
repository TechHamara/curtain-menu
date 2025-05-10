<div align="center">
<h1><kbd>🧩 CurtainMenu</kbd></h1>
An extension for MIT App Inventor 2.<br>
Developed by TechHamara using Fast.<br>
- Sliding menu with curtain effect animation
- Support for left or right menu directions
- Customizable menu width
- Smooth animation transitions
- Touch gestures (swipe, fling) for intuitive interaction
- Direction-aware gesture handling (works properly for both left and right menu directions)
- Event-driven programming support with menu state change events
- Robust error handling with informative error messages
- Proper background color handling (automatically hides when menu is closed).<br>
  <a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://techhamara.blogspot.com/' target='_blank'>Blogger</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.curtainmenu<br>
💾 **Size:** 22.41 KB<br>
⚙️ **Version:** 1.0<br>
📱 **Minimum API Level:** 7<br>
📅 **Updated On:** [date=2025-05-09 timezone="Asia/Calcutta"]<br>
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small><br>
📚 **Library** Used By 7heaven [original CurtainSlidingMenu library](https://github.com/7heaven/CurtainSlidingMenu). thanks you. <br>
💲 **BUY** On UPI 180rs USD 2$

## Demo

![MIT-App-Inventor-05-09-2025_10_38_AM](https://github.com/user-attachments/assets/27937825-4a4b-49e0-9f90-27b177b604b3)
![blocks](https://github.com/user-attachments/assets/4c8181cd-a1cb-49f1-b0de-98801c3fe376)

-----

![Gif2.gif](https://github.com/user-attachments/assets/58bc5aa6-5b6a-47d3-9e4c-725dc1bd3437)

![Gif1.gif](https://github.com/user-attachments/assets/941e477f-6067-438f-8da6-b53172e09be5)

-----

![Screenshot2.jpg](https://github.com/user-attachments/assets/f437f770-c818-4670-b34e-c1d1998ce7eb)

![Screenshot1.jpg](https://github.com/user-attachments/assets/33bf2c5b-3c1f-4ae5-95e5-90ebeccafdcd)

## Blocks

![AnimationStart_Event](https://github.com/user-attachments/assets/b1fca2d7-5659-4a4e-86a4-2f40fb80f37a)
![AnimationEnd_Event](https://github.com/user-attachments/assets/79b2f570-63b2-454c-9b5e-bb4b8e1d465f)
![MenuOpened_Event](https://github.com/user-attachments/assets/d83b6c2c-f713-4efc-a92b-f9c23222235c)
![MenuClosed_Event](https://github.com/user-attachments/assets/cce11951-141e-4f8e-a142-6a08f0496553)
![Initialized_Event](https://github.com/user-attachments/assets/bf8caf8f-f5c0-4b26-acd6-2db3c8fb7edf)
![InitializationError_Event](https://github.com/user-attachments/assets/b0dd743f-fbe1-4183-85cb-e4059a841ffc)

-----

![Cleanup_Method](https://github.com/user-attachments/assets/af01bc28-f554-4e4a-909e-ebcfb78b2f1f)
![BackgroundColor_Method](https://github.com/user-attachments/assets/5cbad097-505a-44c6-9941-e4e2c6a68d7b)
![AddMenu_Method](https://github.com/user-attachments/assets/c3c6892a-7367-48cf-8e58-7172dd48e318)
![AddContent_Method](https://github.com/user-attachments/assets/ad0e8f4b-9d4a-4ff4-a174-a23540597792)
![Toggle_Method](https://github.com/user-attachments/assets/7988def9-3a41-4e8d-b573-c8ca34114750)
![OpenMenu_Method](https://github.com/user-attachments/assets/bc7d5835-6461-4b3e-a578-245bd9760635)
![Initialize_Method](https://github.com/user-attachments/assets/cb280095-3c2e-4cbd-8ca1-c73f16110cf9)
![Direction_Method](https://github.com/user-attachments/assets/d220fa90-806a-47bf-8271-b74526e304c5)
![CloseMenu_Method](https://github.com/user-attachments/assets/58b9b20f-f85f-4184-a6d1-0275b739d9dc)

-----

![IsMenuOpen_Get_Property](https://github.com/user-attachments/assets/2e47fdab-cb60-4bbe-aa99-c5358972bfd3)
![IsInitialized_Get_Property](https://github.com/user-attachments/assets/dfdc3f39-8b39-49cd-8859-4de0fd5af06b)
![IsAnimating_Get_Property](https://github.com/user-attachments/assets/0d5f846d-f972-4e34-a3ff-f9360dfcbac4)
![MenuWidth_Set_Property](https://github.com/user-attachments/assets/bd6b5328-19f6-4a3c-8805-3863afc7d44e)


## <kbd>Events:</kbd>
**CurtainMenu** has total 6 events.

### Initialized
Event indicating that initialization is complete

### InitializationError
Event indicating that initialization failed with an error

| Parameter | Type
| - | - |
| errorMessage | text

### MenuOpened
Event indicating that menu has opened

### MenuClosed
Event indicating that menu has closed

### AnimationStart
Event triggered when curtain animation starts

| Parameter | Type
| - | - |
| isOpening | boolean

### AnimationEnd
Event triggered when curtain animation ends

| Parameter | Type
| - | - |
| isOpen | boolean

## <kbd>Methods:</kbd>
**CurtainMenu** has total 9 methods.

### Initialize
Initialize inside an arrangement.

| Parameter | Type
| - | - |
| arrangement | component

### AddContent
Add content component to the curtain menu.

| Parameter | Type
| - | - |
| content | component

### AddMenu
Add menu component to the curtain menu.

| Parameter | Type
| - | - |
| menu | component

### Toggle
Toggle the curtain menu open/closed with animation.

### OpenMenu
Open the menu with animation.

### CloseMenu
Close the menu with animation.

### Direction
Set the direction of the curtain menu (0 for left, 1 for right).

| Parameter | Type
| - | - |
| direction | number

### BackgroundColor
Set the background color of the menu layout.

| Parameter | Type
| - | - |
| color | number

### Cleanup
Cleanup resources when the extension is no longer needed

## <kbd>Setter:</kbd>
**CurtainMenu** has total 1 setter property.

### MenuWidth
Set the width of the menu in dp

* Input type: `number`

## <kbd>Getters:</kbd>
**CurtainMenu** has total 3 getter properties.

### IsMenuOpen
Returns whether the menu is currently open.

* Return type: `boolean`

### IsAnimating
Returns whether an animation is currently in progress.

* Return type: `boolean`

### IsInitialized
Returns whether the menu has been initialized.

* Return type: `boolean`

## Thanks
TechHamara

## Buy on Paypal

![paypal](https://github.com/user-attachments/assets/1fca8193-8814-44c8-9aec-813436fda7ef)

