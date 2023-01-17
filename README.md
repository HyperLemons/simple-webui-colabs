# fastest-stablediffusion-collab-webui
Est. 10-12 minutes on 2nd launch after replacing with new options using a free Google Colab Account
Still need to time this, will update after    

This is an edit/modification of someone's else script, I just made some modifications to make it easier to understand various things such as changing the model and vae, also adding in support for saving options (I don't believe any other of these colab scripts have this implemented at all atm...?)
As far as I can tell, this is faster than any other .ipynb for Google Colab, as it simply installs the webui as if your installing it on your pc with a few Python and Git commands. IDFK why some of them are so long and complex with so many f*cking lines of python commands. Takes up way more time to install and launch.

Set with anythingV3 model and vae, but can be changed to any by replacing the links.

# Changes from [Nolan Aatama's](https://github.com/nolanaatama) original [sd-1click-colab](https://github.com/nolanaatama/sd-1click-colab):
     
Added [autocomplete extensions](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete) 

Added easy way to mount drive and replace option files to mitigate sessions destroying all resources after being ended


# Need to fix/find fix for:

Sampling steps won't change to dropped in options
