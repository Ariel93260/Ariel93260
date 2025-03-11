<header>Rénovation d'Ampleur</header>
<div class="container">
    <h2>Obtenez votre diagnostic gratuit</h2>
    <form id="prospectForm">
        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom" required>

        <label for="prenom">Prénom :</label>
        <input type="text" id="prenom" name="prenom" required>

        <label for="codePostal">Code Postal :</label>
        <input type="text" id="codePostal" name="codePostal" required>

        <label for="telephone">Numéro de téléphone :</label>
        <input type="tel" id="telephone" name="telephone" required pattern="^\+?\d{10,15}$" title="Numéro de téléphone valide, sans espaces (ex. : 0123456789 ou +33612345678)">

        <label for="chauffage">Mode de chauffage :</label>
        <select id="chauffage" name="chauffage" required>
            <option value="electrique">Électrique</option>
            <option value="gaz">Gaz</option>
            <option value="fioul">Fioul</option>
            <option value="bois">Bois</option>
            <option value="pompeChaleur">Pompe à chaleur</option>
        </select>

        <button type="submit">Soumettre</button>
    </form>
</div>

<footer>
    <p>&copy; 2025 Rénovation d'Ampleur | Tous droits réservés</p>
</footer>
