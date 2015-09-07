# D2HeroKeys - TheCore-Config-Engine Compatible Edition (Super compact keybinds)
An implementation for per-hero keybindings in Dota 2. This has been modified to be compatible with /u/loopuleasa's super-compact-keybinds layout, by copying over the top of it, and is also compatible with the triple layout switches of TheCore-Config-Engine, by copying across the last several lines of each of the provided files.

## How to Use
- Copy the hk_aliases, hk_binds, hk_logic and dota2_gameplay_mode folders to: `steam/steamapps/common/dota 2 beta/game/dota/cfg/` (For Reborn), or `steam/steamapps/common/dota 2 beta/dota/cfg/` (For Legacy Client).
  - The dota2_gameplay_mode folder should be merged with the existing folder, as it changes the parts of the script that modify custom hero bind interactions
    - **IF YOU HAVE ANY CUSTOM BINDS IN THAT FOLDER, ONLY COPY THE LAST SECTION FROM EACH OF THE PROVIDED FILES THAT DEALS WITH THE CURRENT HERO.** This will replace the last line or so in each of the respective files.
    - The modification to the dota2_functions_active.cfg file is not necessary, though removes unnecessary aliases from being set.
- Add any custom hero keybinds in the respective hero's .cfg files in the hk_binds folder
- Replace the existing autoexec.cfg file with the one provided
  - Look at the README.md file in the hk_binds folder for more information on keybinding
- Remove any in-game binds (probably should have done this already, if you're using this config)
- Enter a practice lobby to test your binds to make sure that they work.

## Issues
- There are issues with DotA 2 not showing some messages in quick succession from config files due to "flood detection", however this can mean that you won't see the confirmation of your hero selection if you typed it in quickly.
- If you find any issues, go to the GitHub page and see if anybody else is having the same issue.
  - If other people have reported the issue, comment letting me know that it is affecting you as well
  - If nobody else has reported the issue, create a new issue, and I will respond as soon as possible
  - Check closed issues as well, in case it has already been fixed, in which case, you will have to re-download the files, and replace your old ones (the hk_binds folder will NOT change, so your binds will never be overwritten).

## Want to help?
If you want to help out, you can fork this project and create pull requests for new features / fixes. I will look over them and hopefully merge them in.

## Other autoexec.cfg creators
I am happy to let this be used in your own keybinding setups, just give me a heads up, and I will be happy to help implement this around your existing config files.
