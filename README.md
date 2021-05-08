# controls.xml-with-extra-buttons

The controls.xml file combines arcade button descriptions from -
- The well known but now quite out of date controls.xml from here: http://controls.arcadecontrols.com/
- An extra ~1k games from here: https://github.com/Texacate/Visual-RetroPie-Control-Maps/blob/master/primary_map.csv - These only include player 1 buttons

Can be used in CPWizard to generate button images, by replacing the default controls.xml file in the Data dir, you may need to go into options > Mame paths and re-select a mame.exe to force it to regenerate the larger xml files used by CPWizard to generate buttons.

ListInfo.xml is the (much larger and more detailed) file CPWizard generates from various sources, after being fed with my Controls.xml file - might be useful one day to have that without needing to go through CPWizard to generate it ...
