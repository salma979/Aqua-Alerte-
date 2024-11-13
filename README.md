<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Notification Button</title>
    <style>
        /* Style du bouton */
        #notificationButton {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        #notificationButton:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <!-- Bouton de notification -->
    <button id="notificationButton" onclick="showNotification()">VOIR NOTIFICATION</button>

    <script>
        // Fonction pour afficher la notification
        function showNotification() {
            alert("Vous avez une nouvelle notification !");
        }
    </script>
</body>
</html>
