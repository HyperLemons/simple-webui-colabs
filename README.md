# simple-webui-colabs


**Update (3/11/23):** Testing Nolan Aatama's newest sd-1click-colab for [anything4.5](https://colab.research.google.com/github/nolanaatama/sd-1click-colab/blob/main/anythingv4.5.ipynb) launched in just about 5 minutes (nice!) However they have added/changed most of the code. If if ever have the strength I may adjust to it, if there's anything crazy improved then I will add/change to it if I find out about it.

**Update (4/18/23):** Testing Nolan's latest script took around 9 minutes to install and launch a public URL for the webui (I acceidenlty stopped the time midway so I don't have an exact time) Might try update to Nolan's latest changes, it looks a lot more feasable now.

**Update (4/18/23):** Finally got around to getting a Kaggle script. Kaggle gives you a bit more freedom than Google for free, especially with it's 30 free GPU hours per week (that's around 4.28 hours of usage per day!). **AND YOU GET PERSISTANT STORAGE (15 GB)!!!!!** It's really just camenduru's script with a fix for the image browser to work with old gradio versions. Camenduru hasn't updated the script in a bit and I haven't figured out how to update Gradio without breaking other stuff, so, yeah. Also included a cell to easily launch the web-ui after installing. Will add more later if i'm up for it.

(Using Google colab) First cell startup time - around 4:50 sec. (Web-UI fully loaded) (using current Google script that is outdated from upstream)

(Using Google colab) Second cell startup time - aprox. 1:33.52 sec. (Web-UI restarted, Google Drive mounted and option files from Google Drive loaded) (using current Google script that is outdated from upstream)


Estimated total startup time for most users on free Google Colab account: ~ 5.8 - 7 minutes (using current Google script that is outdated from upstream)



# About this script

This is an edit/modification of someone's else script, I just made some modifications to make it easier to understand various things such as changing the model and vae, adding extensions and also adding in support for loading options.

The script is already setup with Anything-V4.5 model and Anything-V4.0 vae, but can be changed to any by replacing the links and file names.

**IMPORTANT** Only Google Colab and Kaggle scripts currently. Will update with Paperspace script if i'm ever able to claim a free GPU or decide to subscribe for some reason (highly unlikely).



# Google Colab Script: Changes from [Nolan Aatama's](https://github.com/nolanaatama) original [sd-1click-colab](https://github.com/nolanaatama/sd-1click-colab) (currently edited from a outdated version, still need to update to latest version/upstream)
     
Added [autocomplete booru extension](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)

Added [booru2prompt extension](https://github.com/Malisius/booru2prompt)

Added [booru tag autocompletion extension](https://github.com/DominikDoom/a1111-sd-webui-tagcomplete)

Added [Civitai browser extension, forked version by Etherealxx](https://github.com/etherealxx/sd-civitai-browser)

Added easy way to mount drive and replace option files to mitigate sessions destroying all resources after being ended

Added many comments including explantions on changing/adding in more models and VAEs, adding extensions, as well as a super short tutorial on setting up the options replacement with your Google Drive (Only neccesary once!)

# Need to fix/find fix for

Sampling steps won't change to Google Drive saved options when replacing with ui-options.json from your own PC

# TODO

Comments for explaining how to add hypernetworks and embeddings with web links (the same way you can add models and vae's)

Create Kaggle version (current Google colab version spits out some errors even after replacing file storage directorys to Kaggle's and removing any Google drive functions to take from another service)

Create Paperspace version

Retest current Google version to ensure stability after updating everything

Create [mobile version](https://github.com/nolanaatama/sd-1click-colab-mobile)? 
