inspired by Ken Cochrane's Blog installed on dotCloud
=========================================

If you want to install this software on dotcloud then this is repo you should use. it should be pretty strait forward, requiring only a few steps to deploy.


Code sample
-----------
Generate code sample HTML with:
pygmentize -O style=native -f html -l <LANGUAGE, i.e. python, or blank> -o <OUTPUT.html> <INPUT, i.e.:models.py>


Website color scheme:
---------------------
http://kuler.adobe.com/#themeID/748381
scheme name: shy

dark blue: 121C26
grey: 30403B
light grey: 8B9976
beige: BFBF8A
orange: 8C4119


Special thanks to:
------------------

Social Network Icon Pack by Rogie King is licensed under a Creative Commons Attribution-Share Alike 3.0 Unported License (http://creativecommons.org/licenses/by-nc-sa/3.0/)




Components used:
----------------
All required components are listed in the requirements file.  To install these dependencies, use the following command (ideally run inside of a virtualenv):

    pip install -r requirements.txt

