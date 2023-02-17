# simple-webui-colab
First cell startup time - around 4:50 sec. (Web-UI fully loaded)

Second cell startup time - aprox. 1:33.52 sec. (Web-UI restarted, Google Drive mounted and option files from Google Drive loaded)


Estimated total startup time for most users on free account: ~ 5.8 - 7 minutes



# About this script

This is an edit/modification of someone's else script, I just made some modifications to make it easier to understand various things such as changing the model and vae, adding extensions and also adding in support for loading options.

The script is already setup with Anything-V4.5 model and Anything-V4.0 vae, but can be changed to any by replacing the links and file names.

**IMPORTANT** This only works with Google colab atm. I'm working on a Kaggle version currently, and will include it in this repository.

# Changes from [Nolan Aatama's](https://github.com/nolanaatama) original [sd-1click-colab](https://github.com/nolanaatama/sd-1click-colab):
     
Added [autocomplete booru extension](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)

Added [booru2prompt extension](https://github.com/Malisius/booru2prompt)

Added [booru tag autocompletion extension](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)

Added [Civitai browser extension, forked version by Etherealxx](https://github.com/etherealxx/sd-civitai-browser)

Added easy way to mount drive and replace option files to mitigate sessions destroying all resources after being ended

Added many comments including explantions on changing/adding in more models and VAEs, adding extensions, as well as a super short tutorial on setting up the options replacement with your Google Drive (Only neccesary once!)

# Need to fix/find fix for:

Sampling steps won't change to Google Drive saved options when replacing with ui-options.json from your own PC

# TODO:

Comments for explaining how to add hypernetworks and embeddings with web links (the same way you can add models and vae's)

Create Kaggle version (current Google colab version spits out some errors even after replacing file storage directorys to Kaggle's and removing any Google drive functions to take from another service)
