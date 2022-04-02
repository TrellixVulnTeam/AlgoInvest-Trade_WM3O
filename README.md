<!DOCTYPE html>
<html>
<head>
</head>
<body>
	<h1>AlgoInvest&Trade</h1>
	<p>
		Le programme d�finie la meilleure strat�gie d'investissement � partir d'une liste d'actions qui lui est fournit.<br>
		<h2>Deux approches de calcul pour arriver � la solution la plus optimis�e.</h2><br>
		<h3>La m�thode bruteforce</h3><br>
		(limit�e � des donn�es de petite taille)<br>
		Est une technique de resolution de probl�me dans laquelle la solution possible 
		� un probleme est decouverte en v�rifiant chaque r�ponse une par une, en
		d�terminant si le resultat satisfait ou non l'�nonce d'un probleme.<br><br>
		<h3>L'approche dynamique</h3><br>
		(solution plus optimis�e, couteux en taille m�moire)<br>
		La programmation dynamique est une technique algorithmique pour r�soudre
		un probl�me d'optimisation en le d�composant en sous-problemes plus 
		simples et en utilisant le fait que la solution optimale au probl�me
		global d�pend de la solution optimale � ses sous probl�mes.
	</p>
	<h2>Installtion</h2>
	<p>
		<ul>
			<li>Clonez le repository <code>git clone</code></li>
			<li>Se d�placer dans le r�pertoire racine epic-events <code>cd algoinvest</code></li>
			<li>Cr�er un environnement virtuel <code>python -m venv env</code></li>
			<li>Activez l'environnement virtuel <code>env\Scripts\activate.bat</code></li>
			<li>Installez les d�pendances du project <code>pip install -r requirements.txt</code></li>
		</ul>
	</p>
	<h2>Ex�cution</h2>
	<ul>
		<li>Se d�placer dans le r�pertoire racine AlgoInvest <code>cd AlgoInvest</code></li>
		<li>Pour lancer l'algorithme bruteforce<code>python bruteforce.py</code></li>
		<li>Pour lancer l'algorithme optimis�<code>python optimized_v1.py</code></li>
		<li>Pour changer la liste d'actions/datasets : <br>
			1.Ouvrir le fichier optimized_v1.py<br>
			2.Modifier la variable filename ligne 84 avec le bon filename<br>
		</li>
	</ul>
</body>
</html>