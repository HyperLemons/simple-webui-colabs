# fastest-stablediffusion-collab-webui
First cell startup time - aprox. 4:50 sec. (Web-UI fully loaded, no options from Google Drive loaded)
Second cell startup time - aprox. 1:33.52 sec. (Web-UI fully loaded, options from Google Drive loaded)

Estimated total startup time for most users on free account: ~ 5.8 - 7 minutes

# About this script

This is an edit/modification of someone's else script, I just made some modifications to make it easier to understand various things such as changing the model and vae, adding extensions and also adding in support for loading options (I don't believe any other of these colab scripts have this implemented at all atm...?)

As far as I can tell, this is faster than any other .ipynb for Google Colab. The reason for this being it simply installs the webui as if your installing it on your pc with a few Python and Git commands.

IDFK why some of them are so long and complex with so many f*cking lines of python commands. Unless there is something in them that is somehow superior to mine (still haven't found it!), they take up way more time to install and launch as well as being much more complicated to setup.

The script is already setup with anythingV3 model and vae, but can be changed to any by replacing the links.

# Changes from [Nolan Aatama's](https://github.com/nolanaatama) original [sd-1click-colab](https://github.com/nolanaatama/sd-1click-colab):
     
Added [autocomplete booru extensions](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)

Added [booru2prompt](https://github.com/Malisius/booru2prompt)

Added easy way to mount drive and replace option files to mitigate sessions destroying all resources after being ended

Added many comments including explantions on changing/adding in more models and VAEs, adding extensions, as well as a super short tutorial on setting up the options replacement with your Google Drive (Only neccesary once!)

# Need to fix/find fix for:

Sampling steps won't change to Google Drive saved options when replacing with ui-options.json from your own PC

# Need to add:

Ability to add hypernetworks and embeddings with web links (the same way you can add models and vae's)
