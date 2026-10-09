# pollinating sandboxes
*pollinating sandboxes* is a Minecraft modpack rooted in TerraFirmaCraft (TFC) to combine Create Mods (including Create Aeronautics).

## Current Actions
1. Understand VSCodium and the Github.com repository and projects to have a working path for moving forward. [managed commit loop through VSCodium, getting comfortable with Markdown langauge]
2. Create a list of "Goal" mods that provide the fundamental flavor for *pollinating sandboxes*. These are the mods that provide the basic feel and intent for the package.
    1. Establish the platform and version for the latest TFC [Minecraft 1.21.1, NeoForge modloader]
    2. Match with Create: ☑
    3. Match with some form of nuclear energy with Create Mod: Create: Power Grid appears to be a good candidate: ☑ create: nuclear industry
    4. Match with some form of space exploration: Ad Astra vs. Create: Creating Space
    5. Consider storage and backpacks.
    6. Consider application of magic: theorematurgy may do the trick.
    7. Dragons...
    8. Map/ WorldGen...
3. Form the process for adding individual mods and testing to verify the mods merge correctly. The process should also provide a list of what mod versions as well as which mods are "client only" (and should be deactivated on the server) or "server only" (and can be safely disabled from the client to conserve load time and memory).
    1. https://youtu.be/Ykqol8zOYpw has a quick tutorial on making the modpack using the CurseForge tool. Instructions for uploading the pack are in the text. Note from the "uploading" video: "Any third party mods or anything from third party the modpack will be automatically declined." Alrighty then, something to keep min mind. My next stop is to begin building the modpack in CurseForge and determine how to synchronize issues and work with the Github repository.
    2. I have a basic image for the modpack logo. I should tinker with my user settings and any other required images. BayGames (author of the videos mentioned) notes the logo should be 400x400. https://youtu.be/i3W9ng12Msg has great advice on how to go about this. I used the Curseforge tool to create and save the .zip file, then unpacked it into the `curseforge/pollinating sandboxes` folder. The goal will be to independently "make" the zip file to be uploaded to Curseforge. I need a dadtabase of mods to confirm they are on both Modrinth and Curseforge until I'm forced to decide exclusivity.
    3. Examine Gravitas² on CurseForge to determine how they do it.
    
    4. I r recall a github project to assist with modpacks. Is that useful here?
        1. https://github.com/hhy2534/mc-modpack-generator doesn't have anything.
        2. https://github.com/onlive1337/ModForge-AI last release was two years ago.
        3. https://github.com/BLAZExFURY/Mod-smith commit last year. It would help a great deal if I changed the sort order of my query on github.com.
        4. https://github.com/elajko/AI-Minecraft-Modpack-Generator doesn't strike me as what I'm looking for.
        5. https://github.com/yalcinunique/UniqueForge-Builder looks like it will do the whole thing *using the power of AI.* That's nice. Doesn't strike me as useful for my intended goal.
        6. https://github.com/PowerMeep/Minecraft-Modpack-Generator "Only supports Modrinth/ Curseforge yada-yada." Yeah, I'd like to be mod platform agnostic. If I *can* be. I'm going to stop working this line of thought.
    5. Set up a table of added mods, version, filesize, category, and so on to maintain an overview of dependencies. I don't find anything useful, as such, on github.