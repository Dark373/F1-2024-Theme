# F1-2024-Theme
RLT theme in the style of the official F1 2024 graphics
## APPLY A CATEGORY TO YOUR SEASON
(see image)

Step 1: Create a category

Step 2: Apply category to the season

Color#1 -> Dictates the main colour of renders.

Color#2 -> Dictates the main color of the white (default) bar for P1.

I strongly recommend that you populate the "Short Name" field, as not all renders have the space to show longer season names.
Users can switch between "Season Name", "Category Name" and "Category Short Name" in theme options.
![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/76cb3b7a-2e75-4971-8b0b-74982164ab37)

## DRIVER AVATARS
Setting Driver Avatars option to "Custom Avatars" means the theme will search for images named after the driver. Example: 

Driver Name: Dark373

Image Name: Dark373.png

Add your images here -> theme/images/avatars

## CUSTOM TEAMS
This theme was desgined to support teams outside of F1. All you need to do is add the team logos.

Add the team logos here -> RacingLeagueTools_v095_preview-7_v2\images\logotypes\teams

## GLOBAL VARIABLES
All variables are stored in global_vars.json within the theme folder. Example of what variables exist:

- Team Name Varients
- Driver/Team Foregrounds
- Team Logo Size
- Font Colours
- Font Sizes

To add support for custom teams, simply observe prexisting examples used for the F1 teams.

## LOCALISATION
Found in the theme folder.

## HOW TO - CUSTOM TEAMS
*using Audi as the example*
### STEP 1
Create your team in the app.
Name: Audi
UniqueId: audi.2024
*only 2 fields with significance*
### STEP 2
Add the logo into the apps image folder.
Path: RacingLeagueTools_v095_preview-7_v2\images\logotypes\teams\F1_2024
Image name: audi.2024.png
**And thats it. The following steps are for team names that need a black/darker font colour.**
### STEP 1
- Open the global_vars.json file in the theme.
- Locate "team foreground colours" header
- Create one for your team: "AudiFG": "000000",
**Some renders have separate variables for foreground, such as the line-up render. (see second image)**

Localisation is used to manipulate text. Or similpy used to translate text. Edit the right-hand side of the variables.

If you wish to add permenant support for your language, please make a copy of the english.json and edit the file. Once completed, send the file to Dark373 on discord.
