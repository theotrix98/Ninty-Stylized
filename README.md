# Ninty-Stylized
A pack of themes for ninstar's Ninty Launcher that are intentionally simple but colorful.

# How do I use Ninty themes?
Great question, because the launcher is sure as hell vague about it! In general to use a Ninty theme, mine or otherwise, here are the steps I've figured out:
- you'll want to first download the **.ini**, **.png**, and (if the theme has one) the **.ogg** files.
- Once you have them, move them to your Ninty profile folder. I'm not certain if it's *required* that these files be in the Ninty folder, but I keep them there, and regardless I think putting them there is easier to keep track of. Feel free to try keeping them elsewhere, though.
- Protip: If you want to have multiple themes you can change between, I recommend sorting them into folders. Every theme's 2 or 3 files will be named the same, so it should be relatively simple to group them together. Again, I would advise keeping these folders in the Ninty profile folder, but since I haven't tested otherwise, they might work fine outside of it as well.
- Finally, once you have all files for a theme, open Ninty and select the Change Wallpaper button.
- Choose the **.png** of the theme; this is the wallpaper. The **.ini** and (if included) **.ogg** should both be named the same as the wallpaper, or else the theme won't be able to find them. You *can* select a wallpaper without corresponding **.ini** or **.ogg** files, and it will show the image, however you'll just be defaulting to Ninty's default .ini configuration and won't have any bgm.

I'm not the best at explaining things, so forgive me if this reads awkwardly. I'll probably try to revise this to be easier to understand later. Essentially, you want your file structure to look like this, with "themename" being the same for each file:

📂 Folder Holding Your Theme
- themename.ini (<-- basically the configuration of the theme. see the Ninty-Launcher repo's wiki for more detailed info on this)
- themename.png (<-- wallpaper)
- themename.ogg (<-- if you want to include bgm; if not, just don't include this file)

# Hang on, where is everything?
Currently, the complete pack is a work in progress; all background graphics have been created, I just need to create proper .ini files for them and sort them appropriately. Should hopefully be finished within 24 hours. This is also my first attempt at making Ninty themes, so while they *should* work properly as I will do my best to test these myself before adding the files to the repo, please forgive me if I somehow manage to fuck up something. Feel free to tell me what I did stupidly and I will attempt to fix it!
