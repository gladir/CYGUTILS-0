# CYGUTILS-0
Clone de CygUtils écrit en Pascal (Turbo Pascal ou Free Pascal)

<h2>Liste des fichiers</h2>

Voici la liste des différents fichiers proposés dans CYGUTILS-0 :

<table>
		<tr>
			<th>Nom</th>
			<th>Description</th>	
		</tr>
	  <tr>
			<td><b>ASCII.PAS</b></td>
			<td>Cette commande permet d'afficher la table ASCII de la console.</td>
		</tr>  
		<tr>
			<td><b>BANNER.PAS</b></td>
			<td>Cette commande permet d'afficher une bannière. Cette commande est un équivalent de la commande UNIX.</td>
		</tr>  
		<tr>
			<td><b>D2U.PAS</b>
			<td>Cette commande permet de convertir les sauts de ligne DOS en saut de ligne UNIX.</td>
		</tr>	
		<tr>
			<td><b>DOS2UNIX.PAS</b></td>
			<td>Cette commande permet d'effectuer la conversion des caractères de saut de ligne du système d'exploitation DOS en leur équivalent UNIX.</td>
		</tr>
		<tr>
			<td><b>DUMP.PAS</b></td>
			<td>Cette commande permet d'afficher le contenu d'un fichier en format hexadécimal.</td>
		</tr>	
		<tr>
			<td><b>REALPATH.PAS</b></td>
			<td>Cette commande permet de convertir le paramètre du nom en chemin absolue, avec toutes les références à «.», «..» et les liens symboliques résolus.</td>
		</tr>	
</table>

<h2>Compilation</h2>
	
Les fichiers Pascal n'ont aucune dépendances, il suffit de télécharger le fichier désiré et de le compiler avec Free Pascal avec la syntaxe de commande  :

<pre><b>fpc</b> <i>LEFICHIER.PAS</i></pre>
	
Sinon, vous pouvez également le compiler avec le Turbo Pascal à l'aide de la syntaxe de commande suivante :	

<pre><b>tpc</b> <i>LEFICHIER.PAS</i></pre>
	
Par exemple, si vous voulez compiler ASCII.PAS, vous devrez tapez la commande suivante :

<pre><b>fpc</b> ASCII.PAS</pre>
	
<h2>Licence</h2>
<ul>
 <li>Le code source est publié sous la licence <a href="https://github.com/gladir/CYGUTILS-0/blob/master/LICENSE">MIT</a>.</li>
 <li>Le paquet original est publié sous la licence <a href="https://github.com/gladir/CYGUTILS-0/blob/master/LICENSE">MIT</a>.</li>
</ul>
