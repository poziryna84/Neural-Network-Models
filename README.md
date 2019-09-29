# Neural-Network-Models
Neural Network Models with FastAI and other models.


#The necessary data for the Head_rotation__Mobile__net tutorial can be downloaded from  the following link:
# http://www-prima.inrialpes.fr/perso/Gourier/Faces/HeadPoseImageDatabase.tar.gz


#For Google images recognition project the data was downloaded from Google images in the following order:
Go to Google Images and search for the images you are interested in.

Press CtrlShiftJ in Windows/Linux and CmdOptJ in Mac, and a small window the javascript 'Console' will appear. That is where you will paste:
urls = Array.from(document.querySelectorAll('.rg_di .rg_meta')).map(el=>JSON.parse(el.textContent).ou);
window.open('data:text/csv;charset=utf-8,' + escape(urls.join('\n')));
