# harch-wa-ff
Hide ARCHived WhatsApp (messages count) for FireFox is a utility extension.  
It simply hides the annoying indicator for how many archived messages there are.  
Just something I needed/wanted.

## Note about implementation  
It's pretty simple and barebones, you could probably do something better.  
All it does is look at the classname for the unread chat counter which I know is unique.  
It then just gets it by classname, and makes `display: none`  pretty standard stuff actually.