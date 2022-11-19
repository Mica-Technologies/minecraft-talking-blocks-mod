# Minecraft Talking Blocks Mod

## OwO!? What's this!? TTS in LEGIT Minecraft!? 
Don't call us crazy! The Minecraft Talking Blocks Mod is a showcase of our mere attempt into making functional text to speech (TTS) a reality in Minecraft with a rather simple yet pretty old and somewhat arcane Java TTS library. Although very combersome at first and probably by far something that no other Minecraft modder has even dared in trying to do, we might as well be the first in doing so anyways! Sometimes those lines of text going by in your chats with a command block, chat box or whatever other chat things you might as well use just get a little too boring for most of your needs amiright!?

As a start, This mod is based loosley on CSM and will run perfectly on Minecraft 1.12.2 and possibly later versions after that for a cross version mod built entireley from scratch in Minecraft Forge. It brings a number of blocks and items to help make things talk, from NOAA weather radios to the Dectalk, Gravis Ultrasound, Disney Sound Source and many more! If it talks, it will FOR SURE be in this mod!

## Information and Documentation
Coming soon! For now just imagine how cool this will really be!

## Issues
Having an issue with the mod? Error in the documentation or it just isn't clear enough? Let us know by using the [GitHub issue tracker](https://github.com/Mica-Technologies/minecraft-talking-blocks-mod/issues).

## Team
Contributions and modifications are not limited to the development team, and it you are always encouraged to file issues and create pull requests. We want to help see this project grow and for being the first Minecraft TTS mod in reality

<img src="https://minotar.net/armor/bust/HawkA97/100.png" width="50"/>

**Name:** Alex<br/>
**GitHub Username:** mica-alex<br/>
**Minecraft Username:** HawkA97


<img src="https://minotar.net/armor/bust/AngelWingsPanda/100.png" width="50"/>

**Name:** Brandon<br />
**GitHub Username:** AngelWingsPanda<br />
**Minecraft Username:** AngelWingsPanda

## Development
### IDE/Making Changes
The preferred development environment/IDE for the Minecraft Talking Blocks Mod is [IntelliJ IDEA](https://www.jetbrains.com/idea/download). 
After opening IntelliJ, choose the option "Get from Version Control", which allows you to download and open an IntelliJ project from a Git server.

<img src="DOCS/readme/getfromvctl.png" width="200" alt="Get from Version Control Button Image"/>

#### Adding a Block
To add a block, you'll need to do the following:
 
- Create a new block class in `src/main/java/com/micatechnologies/minecraft/mtb/block`. 
- Create a block model file in `src/main/resources/assets/mtb/models/block`.
- Create a block item model file in `src/main/resources/assets/mtb/models/item`.
- Create a block state file in `src/main/resources/assets/mtb/blockstates`.
- Add block name mapping to `src/main/resources/assets/mtb/lang/en_us.lang`

If your block model does not use a built-in Minecraft block model base, add the custom block model to `src/main/resources/assets/mtb/models/custom`.

##### Adding a Model
To maintain proper segregation of model components, there are three models folders, `blocks`, `custom` and `items
`. To add a new model, simply place the complete model in to the `custom` folder. In the `blocks` and `items` folders
, add a model with the proper name and populate it with the following content:

```json
{
  "parent": "mtb:custom/[name of model in custom]"
}
``` 

### Contributing Code/Changes
To contribute code, you will need to push your modifications to GitHub on a new branch. 
To protect the working code, modification of the `master` branch is not permitted except through pull request. 
After you submit a pull request, the development team will need to review and approve your modifications/contributions before they can be merged.

To learn more about using Git integration with the IntelliJ IDEA IDE, please see [https://www.jetbrains.com/help/idea/using-git-integration.html](https://www.jetbrains.com/help/idea/using-git-integration.html).

To learn more about the version control system Git, please see [https://git-scm.com/doc](https://git-scm.com/doc).

## Credits
This mod is entireley buitl from scratch by Mica technologies using the JetBrains IntelliJ IDEA IDE and LOTS of love... and yes random TTS crackups from time to time!


