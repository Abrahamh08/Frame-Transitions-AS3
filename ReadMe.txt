Using this file is very easy.  All you have to do is put the file in the location where your fla file is.  Make adjustments on the first like where it says 'package'.  After 'package', put a space and put the folder name that your file is in.  For example, your file is in Documents in a folder that says Blarg.  In the Blarg folder is another folder called Hlarg.  The Hlarg folder has your files.  Then the file would say 'package Blarg.Hlarg'.

If you were to use a transition such as 'Fade.as', you would write this in your fla or main class file: 

import Fade;
//import goes on the top of the code

Fade.fadeIntoFrame(root, stage, 2, 'Scene 2');

Make sure you put Fade.fadeIntoFrame after you add 3rd party components.

Root and Stage are parameters required to be passed on to the Class.