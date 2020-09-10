# futaba-optional-cogs

Repository to hold optional cogs made for futaba. These are cogs have been made for futaba however are not moderation / server related so less suitable for the main repository.

## Links
- [futaba](https://github.com/strinking/futaba)
- [Discord Server](https://discord.gg/010z0Kw1A9ql5c1Qe)

## Installing
There are 2 ways to install these cogs into futaba
- ### Copying the cogs
This way is the easiest way to add the cogs to futaba. All you need to do is clone this repo then copy the cogs you want to add to your loacl copy of the futaba repo under `futaba/cogs` and that's it.
The down side to this is if there is an update to the cog you will have to pull the lastest version and copy the updated verion in to futaba replacing the current version being used
- ### Creating a symlink
This is the better way to add the cogs you want to futaba as to update the cog all you have to do is pull the lastest verion of this repo and reload the cog.
Steps:
1. Clone this repo and make a not of the absolute path to the cog you want to add e.g `/home/futaba/futaba-optional-cogs/misc`
2. Next create a new folder in your loacl copy of the futaba repo under `futaba/cogs` with the same name as the cog
3. Create a symlink of the cog to the folder you created (Make sure you are in `futaba/cogs`) with the following command: `ln -s <absolute path to cog> <folder you just created>`
e.g. `ln -s /home/futaba/futaba-optional-cogs/misc misc`

## List of cogs
Here are the current cogs you can find in this repo
