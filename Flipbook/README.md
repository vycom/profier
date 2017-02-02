


Flipbook Template
--------------------
This is a highly customizable and very easy to use Flipbook template. Follow the guidelines below in order to change available parameters.

**Required assets **

- One PNG/JPEG image per each FlipBook panel. 

- MP4/WEBM format video files and a poster for video player.

- PNG/JPEG image per each slider panel for slider component.

### How to change default images ###

Select `File Browser` panel located on the left side of the screen. Once in the `File Browser` panel, select settings icon next to the title `Additional assets`.

You can assign assets to each panel in Flipbook settings through `Adform.getAsset()` function.

**Backup image **

If the browser is outdated and doesn't support HTML5, the backup panel image is displayed and clickTAGBackup is used for landing page.

Backup image should be assigned as a `Backup Image` via `Banner Settings` panel.

### How to change template dimensions ###

Open banner settings panel by clicking on the settings icon in the top left corner of the screen. Change dimensions property and click `Save button` or hit `Ctrl + S`.

The expanded size of Flipbook depends on collapsed stage sizes and on the numbers of columns/rows.

### Changing  Flipbook settings ###

If you want to change the clickTAG, the number or type of panels, or other available  parameters, you can edit component settings inside `index.html` document.

Open `File Browser` panel and select `index.html `file. See the code editor panel at the bottom of the screen. Then navigate to component parameters block which starts under `<--User Code-->`.

All available parameters and values are listed [here.](http://support.adform.com/documentation/build-html5-banners/adform-html5-api-components/flip-component/)

### Supported Browsers ###
| Desktop browser version | | 
| ------------- |:-------------:|
| Internet Explorer 10 & 11 | fully supported |  
| Edge | fully supported | 
| Firefox (newest version) | fully supported |  
| Chrome (newest version) | fully supported | 
| Safari (newest version) | fully supported |
___
| Tablet Operating System | OS (fully supported) | 
| ------------- |:-------------| 
| iOS 8.1 (and above) | Safari & Chrome | 
| Android 4.0 (and above) | Native, Chrome & Firefox |