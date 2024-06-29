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

![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/e7132488-2ce9-43fc-9c82-6abd1a815119) ![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/29d3609f-c30d-4b75-912c-2594a5a362fd)

## ACCURATE TEAM COLOURS
*set of instructions to mirror the real life colour schemes*
### STEP 1
- Open the global_vars.json file in the theme folders.
- Locate the "dotd / main colours" header (see image)
### STEP 2
Add colours into your database (second image)
- Color #1: Main
- Color #2: Secondary
Copy and paste the hex codes into your database. 

This is completely at your discretion.

![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/eb7fa983-ebb8-43f1-b69d-618348d25776) ![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/d7b21296-ef67-457d-a2e1-f0ed8a346339)

## HOW TO - ADD LOGO VARIANTS
In some cases, the logo is the same colour as the team logo. So how do we change that?
Haas will be used as the example.
### STEP 1
Prepare your logo.
Use the internet to find a suitable logo, or using software, recolour the logo.
All logos must have a 1:1 ratio with height and width. standard is 256x256 but they could be any size.
### STEP 2
Name the logo. Logos should be named after the team uniqueId (can be found in the teams page).
Haas: haas.2024
New image: haas.2024__light
### STEP 3
Save the image.
Path: F1-2024-Theme/images/logotypes/teams 
### STEP 4
Restart your app.

You cam do this for dark, light, alternative logotypes within the theme.
Alternative is used in official lineups render

![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/addfa5a2-80d5-4bf3-8fa6-3d5c5c254831) ![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/3b91586d-8018-4589-a47e-e4809b000e0a) ![image](https://github.com/Dark373/F1-2024-Theme/assets/141680047/35abd69a-f2df-4ca8-9f8c-173ae0c8f4cd)


