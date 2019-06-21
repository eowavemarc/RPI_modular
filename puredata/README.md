# Utiliser Pure data
Pour faire tourner un patch Pd avec notre système, stocker-le dans un dossier dans la racine de votre clef usb.<br/> Nommez-le <b>main.pd</b> et joignez-y un fichier de configuration nommé <b>conf.txt</b>.<br/>
Vous trouverez dans ce dossier des objets utiles pour adapter un patch Pd à la plate-forme, pensez à les copier dans votre dossier. Toutes les informations necessaires sont à l'intérieur des objets en question.<br/>
# norme du fichier conf.txt
le système ne tient pas compte des espaces, tabulations et sauts de lignes, vous pouvez donc mettre en page ce fichier comme bon vous semble.<br/>
les caractères <b>=</b> séparent les déclarations et leur type. le fichier doit donc suivre la forme suivante :<br/>
<code>type d'input = liste d'input = autre type d'input = autre liste</code> et ainsi de suite<br/>
les caractères <b>;</b> séparent les différents inputs d'une déclaration.<br/>
<code>type d'input = premier input de ce type ; second input</code> etc.<br/>. 
  Les caratères <b>,</b> séparent les différentes informations concernant un input. Dans le cas des encodeur :<br/><code> nom de la valeur , valeur minimum , valeur maximum , unité de mesure</code><br/>
  dans le cas des switchs :<br/>
  <code>nom du switch , nom du premier état , nom de second état , etc.</code><br/>
les différents éléments sont automatiquement répartient sur les différentes pages de l'affichage en respectant l'ordre décrit dans <b>conf.txt</b>. Pour plus de détail, voir les exemples.
