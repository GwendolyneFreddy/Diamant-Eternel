# Menace sur le Royaume de Diamant Éternel

Mod Menace sur le Royaume de Diamant Éternel pour BG2-ToB, BGT et BG2:EE

<p><strong>Author:</strong> <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Freddy_Gwendo (aka Gwendolyne)</a><br />
<strong>Version:</strong> 1.0.0 alpha<br />
<strong>Language:</strong> French<br />
<a href="README.md">French readme</a><br />
<strong>Platform:</strong> Windows</p>

<strong>Mod forum:</strong> <a href="https://www.baldursgateworld.fr/lacouronne/menace-sur-le-royaume-de-diamant-eternel/">Menace sur le Royaume de Diamant Éternel</a>
</br></br>


## <a name="intro" id="intro"></a>Overview



## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: Baldur's Gate II: Enhanced Edition (BG2EE), the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET).

#### Mods pré-requis

<p>Classical games players are also strongly recommended are strongly recommended to also download and install the <a href="http://www.gibberlings3.net/bg2fixpack/">BG2 Fixpack</a> before proceeding with the installation of this mod.</p><br>



## <a name="installation" id="installation"></a>Installation

#### Notes

<em>If you've previously installed the mod, remove it before extracting the new version. To do this, run <strong>setup-diamant_eternel.exe</strong>, uninstall all previously installed components and delete the <strong>diamant_eternel</strong> folder.</em>

<em>When installing or uninstalling, <strong>do not close the <acronym title="Disk Operating System">DOS</acronym> window</strong> by clicking on the <strong>X</strong> button! Instead, press the <strong>Enter</strong> key whenever instructed to do so.</em>

<em><strong>Disable any antivirus</strong> or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.</em></br>


#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.


#### &#9888;&#65039; Warning: installation process

###### Variables needed for installation are read from <em><a href="https://github.com/GwendolyneFreddy/Diamant-Eternel/master/diamant_eternel/diamant_eternel-config-default.ini">diamant_eternel-config-default.ini</a></em>file, or <em><a href="https://github.com/GwendolyneFreddy/Diamant-Eternel/master/diamant_eternel/diamant_eternel-config.ini">diamant_eternel-config.ini</a></em> if it exists.

As interrupting installation with plain text prompts allowing players to customise components to their liking, those variables have been moved into <a href="https://raw.githubusercontent.com/GwendolyneFreddy/Diamant-Eternel/master/diamant_eternel/diamant_eternel-config-default.ini">diamant_eternel-config-default.ini</a> file in <strong>diamant_eternel</strong> folder. This file provides a '<em>standard</em>' installation.

If you want to define your own customized installation, you have to modify the variables involved in <strong><em>diamant_eternel-config-default.ini</em></strong>, then save this file as <strong><em>diamant_eternel-config.ini</em></strong>.

The installation process will read both ini files and prioritize user values. If a value is not set or mismatched in diamant_eternel-config.ini, any installation failure will be prevented by reverting it back to its default value.</br>

Please read the <a href="https://raw.githubusercontent.com/GwendolyneFreddy/Diamant-Eternel/master/diamant_eternel/diamant_eternel-config-english.txt">diamant_eternel-config-language.txt</a> file (with 'language' being the installation language you chose) to check the variables names and their meanings. Here is a chart listing the variables related to the installation process:<br>


Avec les versions prédécentes, pendant la procédure d'installation, de nombreux messages vous permettaient de personnaliser les composants à votre convenance (en fonction de votre jeu IE et des composants que vous aviez installés). Tous ces choix de variables déterminés pendant l'installation du mod ont été externalisés dans le fichier **_diamant-config-default.ini_** situé dans le répertoire diamant_eternel. Ce fichier établit une installation « _standard_ ».

Si vous souhaitez choisir d'autres options d'installation, il vous suffit de modifier les variables souhaitées dans le fichier diamant-config-default.ini, puis de sauvegarder ce dernier sous le nom **_1pp-config.ini_**.

Le programme d'installation lira les valeurs des variables dans les deux fichiers ini et donnera la priorité aux vôtres. Si le fichier diamant-config.ini contient une variable non conforme, ou si une variable est manquante, il la remplacera par sa valeur par défaut (celle correspondant à l'installation « _standard_ »).

<table style="margin-left: 80px" summary="Installation variables listing">
	<tr>
		<th>Variables</th>
		<th>Signification</th>
		<th>Type</th>
		<th>Valeurs possibles</th>
		<th>Défaut</th>
	</tr>
	<tr>
		<td>mymod_variable1</td>
		<td>définit blabla</td>
		<td>numérique</td>
		<td>1 ou 2</td>
		<td><strong><span style="color: #FFCC33;">1</span><strong></td>
	</tr>
	<tr>
		<td>mymod_variable2</td>
		<td>définit blabla</td>
		<td>numérique</td>
		<td>1, 2, 3 ou 4</td>
		<td><strong><span style="color: #FFCC33;">2</span><strong></td>
	</tr>
	<tr>
		<td>mymod_variable3</td>
		<td>définit blabla</td>
		<td>alphanumérique</td>
		<td>une lettre : A, B ou C</td>
		<td><strong><span style="color: #FFCC33;">A</span><strong></td>
	</tr>
	<tr>
		<td>gw_unicorn_name</td>
		<td>he name of your unicorn</td>
		<td>alphanumérique</td>
		<td>a name!</td>
		<td><strong><span style="color: #FFCC33;">Silver Star</span><strong></td>
	</tr>
	<tr>
		<td>gw_horse_name</td>
		<td>The name of your paladin destrier</td>
		<td>string</td>
		<td>a name!</td>
		<td><strong><span style="color: #FFCC33;">???????</span><strong></td>
	</tr>
</table>


#### Windows

Menace sur le Royaume de Diamant Éternel for Windows is distributed as an extractable compressed archive and includes a <acronym title="Weimer Dialogue Utility">WeiDU</acronym> installer.

Extract the contents of the mod archive into the folder of the game you wish to modify, using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. When properly extracted, your game directory will contain <strong>setup-diamant_eternel.exe</strong> and the folder <strong>diamant_eternel</strong>. To install, double-click <strong>setup-diamant_eternel.exe</strong> and follow the instructions on screen.

You can run <strong>setup-diamant_eternel.exe</strong> in your game folder to reinstall, uninstall or otherwise change components.


#### Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using <strong>setup-diamant_eternel --uninstall</strong> at the command line to remove all components without wading through prompts.</br></br>



## <a name="components" id="components"></a>Components

The installer includes the following components. The number of each is the component <em>DESIGNATED</em> number which gives it a fixed install position, lets other components detect it and allows automated installers like the BiG World Setup specify component choices.


#### 10. Core component
</br></br>



## <a name="images" id="images"></a>Screenshots
</br></br>



## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Gwendolyne</a>


#### Special Acknowledgements to:

- <a href="https://www.baldursgateworld.fr"><acronym title="Copper Coronet">La Couronne de Cuivre</acronym></a> team for hosting the mod.
- The creators of the Baldur's Gate series: <a href="http://www.bioware.com/">Bioware</a> and <a href="http://www.obsidian.net/">Black Isle Studios</a>.
- machin for permission to use blabla.
- Isaya for coding help.
- trucmuche for coding help and suggestions.
- bidule for dialogue help.
- xxx for the French translation.
- Graoumf et LuluBaleyette for proofreading.
- Thanks to artists from <a href="https://www.pinterest.fr/">Pinterest</a> for their portraits.
- Everyone else from the <a href="https://www.baldursgateworld.fr">La Couronne de Cuivre</a>, <a href="http://gibberlings3.net/forums/">The Gibberlings Three</a>, <a href="http://www.shsforums.net/">Spellhold Studios</a> forums, and the other Infinity Engine gaming and modding communities who offered their help and support.
- etc.


#### Programs/tools used in creation:

- <a href="http://www.weidu.org/%7Ethebigg/"><acronym title="Weimer Dialogue Utility">WeiDU</acronym></a>, by Wes Weimer, the bigg and Wisp.
- <a href="http://forums.pocketplane.net/index.php/topic,25153.msg314249.html#msg314249">Near Infinity</a>, by Jon Olav Hauglid, FredSRichardson, and Argent77.
- <a href="http://www.gibberlings3.net/tools/dltcep.php"><acronym title="Dragonlance Total Conversion Editor Pro">DLTCEP</acronym></a>, by Avenger.
- <a href="https://gibberlings3.github.io/iesdp/"><acronym title="Infinity Engine Structures Description Project">IESDP</acronym></a>, maintained by igi and lynx.
- <a href="http://www.gibberlings3.net/debug/">G3 Debugging Suite</a>, by CamDawg.
- <a href="http://www.teambg.eu/?page=tools&amp;cat=32">BAM Workshop</a>, by Glenn Flansburg.
- <a href="http://www.shsforums.net/topic/57564-bamworkshop/">BAMWorkshop 2</a>, by Andrew Bridges.
- <a href="http://www.shsforums.net/index.php?showtopic=42359">BAM Batcher</a>, by Miloch.
- <a href="https://www.adobe.com/products/photoshop.html">Adobe Photoshop</a>
- <a href="http://www.gimp.org/"><acronym title="GNU Image Manipulation Program">GIMP</acronym></a>, by the GIMP team.
- <a href="https://www.blender.org/">Blender</a>, by the Blender Foundation.
- <a href="http://notepad-plus-plus.org/">Notepad++</a>, by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a>, by Argent77.
- <a href="http://www.bulkrenameutility.co.uk/">Bulk Rename Utility</a>, by TGRMN Software.


#### Copyrights Information

###### Menace sur le Royaume de Diamant Éternel is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by AUTEUR, based on material from the game Baldur's Gate II and its expansion.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.

###### If there are any copyright issues or this statement needs revision, then please contact me and advise me what to do about it. Most notably, if you see any artwork in this mod that might conflict with Copyright rules, please let me know as soon as possible, and I will remove the conflicting content immediately.

###### The modding community for the Infinity Engine has been going strong for more than 10 years now, and is the culmination of thousands of unpaid modding hours by fellow fans of the game. Modders produce their best work and players get the best, well-supported mods when we all work together.
###### There are two big ways to upset this harmony. One is to claim someone else's work as your own. The second is to host and redistribute a mod without permission from the author(s).
###### Be kind to your fellow players and modders. Don't do either.</br></br>



## <a name="versions" id="versions"></a>Versions History

#### Version beta 1.0.0 - Mois jour, 201x
- Initial release.
