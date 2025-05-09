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
📦 **Package:** io.th.curtainmenu
💾 **Size:** 22.41 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 7
📅 **Updated On:** [date=2025-05-09 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>
Library Used By 7heaven [original CurtainSlidingMenu library](https://github.com/7heaven/CurtainSlidingMenu). thanks you. 

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

