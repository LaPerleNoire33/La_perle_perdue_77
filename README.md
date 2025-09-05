
<html lang="fr">

<head>

<meta charset="UTF-8">

<title>Indice Secret – Bunker</title>

<style>

body {

    font-family: 'Georgia', serif; /* Police type “lettre” */

    background-color: #f3e4d0; /* Fond beige clair / marron clair */

    color: #3e2f1c; /* Couleur texte foncée */

    padding: 40px;

}

#secret {

    display: none;

    font-style: italic; /* Texte en italique pour effet lettre */

    line-height: 1.8;

    max-width: 600px;

    margin: auto;

    border: 1px solid #cbb79b;

    padding: 20px;

    background-color: #fff3e0; /* Fond légèrement plus clair pour la lettre */

}

#login {

    text-align: center;

    max-width: 400px;

    margin: auto;

}

input {

    padding: 10px;

    font-size: 16px;

    margin-top: 10px;

}

button {

    padding: 10px 15px;

    font-size: 16px;

    margin-top: 10px;

    cursor: pointer;

}

</style>

<script>

function checkPassword() {

    var pass = document.getElementById("password").value;

    if(pass === "LAPERLENOIRE") { // Remplace MONCODE par ton mot de passe

        document.getElementById("secret").style.display = "block";

        document.getElementById("login").style.display = "none";

    } else {

        alert("Mot de passe incorrect !");

    }

}

</script>

</head>

<body>



<div id="login">

<h2>Entrez le code pour accéder à l'indice</h2>

<input type="password" id="password" placeholder="Votre code">

<br>

<button onclick="checkPassword()">Valider</button>

</div>



<div id="secret">

<h2>Des années ont été perdues, et pourtant…</h2>

<p>Soyez certains d’une chose : malgré le temps qui s’est écoulé, vous avez contribué à faire renaître un amour. Et cet amour sera plus fort que jamais, il sera aussi éblouissant qu’un phare dans la nuit et ceci jusqu’à leur dernier souffle.
C’est une histoire que mon grand-père m’a racontée, et cela me comble de bonheur de l’avoir partagée avec vous.
Si l’on devait retenir une seule leçon de cette histoire, c’est que l’amour et le temps sont précieux. Il ne faut jamais les gaspiller. N’hésitez pas à vous jeter à l’eau, à dire je t’aime. Je t’aime plus que tout. Tu es ma meilleure amie, la personne avec qui je me sens complet. Tu es celle qui m’apporte douceur et calme dans la tempête de la vie, celle qui me fait rire, celle avec qui chaque jour est une nouvelle aventure. Je ne peux imaginer une autre vie qu’à tes côtés. Je t’aime.
</p>
