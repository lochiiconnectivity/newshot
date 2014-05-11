newshot
=======

Take partial screenshots and put them in the clipboard 
or upload them to the web. 

Tolerates Apple's "Retina" displays.

Instructions:

1. Place the script 'newshot' in /usr/local/bin

2. Open and install the services in the services diretory (using Automator.app)

2.1 "NewShot" service should replace the standard selection of the screen to the clipboard

2.2 "NewShotUpload" service should upload the selection from the screen to your SCP location, returning a URL to your clipboard buffer

3. Remap the keyboard shortcuts to these new services

3.1  Map the NewShot service to Option+Shift+4

3.2  Map the NewShotUpload service to Option+Shift+5


