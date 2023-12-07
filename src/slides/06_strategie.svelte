<script>
	import { onMount } from 'svelte';
	import Slide from '../lib/Slide.svelte';
	import Code from '../lib/Code.svelte';

</script>

<Slide>
	<section>
		<h3 >Stratégies</h3>	
	</section>	
		<section>
			<img class="imgPageAvecLegende" alt="" src="../../assets/jet_des.jpg" />
			<h5>Probabilités</h5>
	</section>
	<section>
			<h5>Probabilités des jets de dés</h5>
			<ol class="listeCartes">
				<li> La plupart du temps, il faut 5 ou 6 jets de dés pour faire le tour de plateau.</li>
				<li >Connaitre les probabilités de dés.</li>
				<li> Vous avez 17% de chances de faire un double.</li>
			</ol>
		<img class="imgProba" style="margin-left: 20%;" alt="" src="../../assets/deux_des_distribution.webp" />
	</section>
	<section>
			<img class="imgPageAvecLegende" alt="" src="../../assets/ordre_cartes.jpg" />
			<h5>Ordre des cartes Chance et Caisse de Communauté</h5>
	</section>
	<section>
			<h5>Liste des cartes chances</h5>
			<ol class="listeCartes">
				<li class="bleu">Rendez-vous à la Rue de la Paix</li>
				<li class="bleu">Avancer jusqu’à la case départ</li>
				<li class="bleu">Rendez-vous à l’Avenue Henri-Martin.</li>
				<li class="bleu">Avancez au Boulevard de La Villette.</li>
				<li class="bleu">Avancez jusqu’à la Gare de Lyon.</li>
				<li class="bleu">Reculez de trois cases</li>
				<li class="bleu">Aller en prison.</li>
				<li>Votre immeuble et votre prêt rapportent. Vous toucher 150 €</li>
				<li>Vous avez gagné le prix de mots croisés. Recevez 100 €</li>
				<li>La banque vous verse un dividende de 50 €</li>
				<li>Vous êtes libéré de prison. Cette carte peut être conservée jusqu’à ce qu’elle soit utilisée ou vendue.</li>
				<li class="rouge">Vous êtes imposé pour les réparations de voirie à raison de 40 € par maison et 115 € par hôtel.</li>
				<li class="rouge">Faites des réparations dans toutes vos maisons.&nbsp;Versez pour chaque maison 25 €. Versez pour chaque hôtel 100 €</li>
				<li class="rouge">Amende pour excès de vitesse 15 €</li>
				<li class="rouge">Payez pour frais de scolarité 150 €</li>
				<li class="rouge">Amende pour ivresse 20 €</li>
			</ol>
	</section>	
	<section>
			<h5>Liste des cartes Caisse de Communauté</h5>
			<ol class="listeCartes">
				<li class="bleu">Placez-vous sur la case départ</li>
				<li class="bleu">Aller en prison.</li>
				<li class="bleu">Retournez à Belleville</li>
				<li class="bleu">Rendez-vous à la gare la plus proche. Si vous passez par la case départ, recevez 200 €</li>
				<li>Erreur de la banque en votre faveur. Recevez 200 €</li>
				<li>La vente de votre stock vous rapporte 50 €</li>
				<li>Vous êtes libéré de prison. Cette carte peut être conservée jusqu’à ce qu’elle soit utilisée ou vendue.</li>
				<li>Vous avez gagné le deuxième Prix de Beauté.&nbsp;Recevez 10 €</li>
				<li>Vous héritez 100 €</li>
				<li>Recevez votre revenu annuel 100 €</li>
				<li>C’est votre anniversaire.&nbsp;Chaque joueur doit vous donner 10 €</li>
				<li>Les contributions vous remboursent la somme de 20 €</li>
				<li>Recevez votre intérêt sur l’emprunt à 7% 25 €</li>
				<li class="rouge">Payez votre Police d’Assurance 50 €</li>
				<li class="rouge">Payez la note du médecin 50 €</li>
				<li class="rouge">Payez une amende de 100€ ou bien tirez une carte «&nbsp;CHANCE&nbsp;»</li>
			</ol>
	</section>	
	<section>
		<img class="imgPageAvecLegende" alt="" src="../../assets/strategie.jpg" />
			<h5>Bien choisir son monopole</h5>
	</section>	
	<section>
		<img class="imgPage" alt="" src="../../assets/case_propa.png" />
	</section>	
	<section>
			<h5>probabilité par groupe</h5>
			<ol class="listeCartes">
				<li>Les 4 gares : 54%</li>
				<li>Les rues orange : 50%</li>
				<li>Les rues rouges : 49%</li>
				<li>Les rues jaunes : 45%</li>
				<li>Les rues vertes : 44%</li>
				<li>Les rues violettes : 43%</li>
				<li>Les rues bleu clair : 39%</li>
				<li>Les compagnies : 32%</li>
				<li>Les rues bleu foncé : 27%</li>
				<li>Les rues marrons : 24%</li>
			</ol>
	</section>
	<section>
		<img class="imgPageAvecLegende" alt="" src="../../assets/3maisons.jpg" />
			<h5>3 maisons</h5>
	</section>	
	<section>
		<img class="imgPageAvecLegende" alt="" src="../../assets/hypotheques.jpg" />
			<h5>hypothéquez</h5>
	</section>
	
	<section>
		<img class="imgPageAvecLegende" alt="" src="../../assets/penurie.jpg" />
			<h5>Pénurie de maison</h5>
	</section>	
</Slide>