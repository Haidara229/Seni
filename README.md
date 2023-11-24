```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulaire d'Inscription</title>
</head>
<body>

    <h2>Inscription</h2>

    <form action="/traiter_inscription" method="post">
        <label for="nom">Nom :</label>
        <input type="text" id="nom" name="nom" required><br>

        <label for="prenom">Prénom :</label>
        <input type="text" id="prenom" name="prenom" required><br>

        <label for="pays">Pays :</label>
        <input type="text" id="pays" name="pays" required><br>

        <label for="ville">Ville :</label>
        <input type="text" id="ville" name="ville" required><br>

        <label for="whatsapp">Numéro WhatsApp :</label>
        <input type="text" id="whatsapp" name="whatsapp" required><br>

        <input type="submit" value="S'inscrire">
    </form>

</body>
</html>
```
