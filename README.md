# simple-webui-colabs


**Update (3/11/23):** Testing Nolan Aatama's newest sd-1click-colab for [anything4.5](https://colab.research.google.com/github/nolanaatama/sd-1click-colab/blob/main/anythingv4.5.ipynb) launched in just about 5 minutes (nice!) However they have added/changed most of the code. If if ever have the strength I may adjust to it, if there's anything crazy improved then I will add/change to it if I find out about it.

**Update (4/18/23):** Testing Nolan's latest script took around 9 minutes to install and launch a public URL for the webui (I acceidenlty stopped the time midway so I don't have an exact time) Might try update to Nolan's latest changes, it looks a lot more feasable now.

**Update (4/18/23):** Finally got around to getting a Kaggle script. Kaggle gives you a bit more freedom than Google for free, especially with it's 30 free GPU hours per week (that's around 4.28 hours of usage per day!). **AND YOU GET PERSISTANT STORAGE (15 GB)!!!!!** It's really just camenduru's script with a fix for the image browser to work with old gradio versions. Camenduru hasn't updated the script in a bit and I haven't figured out how to update Gradio without breaking other stuff, so, yeah. Also included a cell to easily launch the web-ui after installing. Will add more later if i'm up for it.

(Using Google colab) First cell startup time - around 4:50 sec. (Web-UI fully loaded) *(using current Google script that is outdated from upstream)*

(Using Google colab) Second cell startup time - aprox. 1:33.52 sec. (Web-UI restarted, Google Drive mounted and option files from Google Drive loaded) *(using current Google script that is outdated from upstream)*


Estimated total startup time for most users on free Google Colab account: ~ 5.8 - 7 minutes *(using current Google script that is outdated from upstream)*



# About this script

These are just edits/modifications of people's script, I just made some modifications to make it easier to understand various things such as changing the model and vae, adding extensions and also adding in support for loading options (option loading limited to Google Drive currently).

The script is already setup with Anything-V4.5 model and Anything-V4.0 vae, but can be changed to any by replacing the links and file names.

**IMPORTANT** Only Google Colab and Kaggle scripts currently. Will update with Paperspace script if i'm ever able to claim a free GPU or decide to subscribe for some reason (highly unlikely).



# Google Colab Script: Changes from [Nolan Aatama's](https://github.com/nolanaatama) original [sd-1click-colab](https://github.com/nolanaatama/sd-1click-colab) (currently edited from a outdated version, still need to update to latest version/upstream and add more extensions)
     
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

~~Create Kaggle version (current Google colab version spits out some errors even after replacing file storage directorys to Kaggle's and removing any Google drive functions to take from another service)~~ Ensure Kaggle script stability and full functionality (whatever functionality available in the A1111 WebUI that is to the extent of my knowledge, as well as whatever extensions I know and use)

Create Paperspace version

Retest current Google version to ensure stability after updating everything

Create [mobile version](https://github.com/nolanaatama/sd-1click-colab-mobile)? 

# Disclaimer

As iterated from the *About this script* section of this README.md, I do not own any of the original code made for these scripts/colabs nor did I contribute to the original scripts.

I am not a python developer, I am not a C++ developer, I just try to configure things to the extent of my knowledge and best ability for myself and anyone else who would like a better pre-configured expirence with little to no hassle. Any changes I make to the original scripts/colabs by thier original creators are only changes that ANYONE can do, with absolutely 0 coding knowledge.

**All respective credits go to _(will update as needed)_:**
[Nolan Aatama](https://github.com/nolanaatama) for their immense sd-1click-colab scripts/colabs and amazing resource of tutorials on their (Youtube)[https://www.youtube.com/@nolanaatama].
[camenduru](https://linktr.ee/camenduru) for their work on (will add later)
and all developers of the extensions I added, the people who created the models I added, the people behind Civitai, and anyone else I may have forgot to mention.

**They are all the real people to spread your thanks for these scripts, as it would not be possible without their work.**
