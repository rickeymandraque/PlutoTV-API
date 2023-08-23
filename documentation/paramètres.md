# Paramètres de Requête pour Pluto TV

## Paramètres Obligatoires

### `terminate`
- **Type:** Booléen
- **Valeur possible:** true, false
- **Utilité:** Contrôle si la lecture doit être terminée prématurément.

### `sid`
- **Type:** Chaîne de caractères
- **Utilité:** Identifiant de session unique généré pour chaque flux vidéo.

### `deviceDNT`
- **Type:** Entier (0 ou 1)
- **Utilité:** Signale si le suivi ("Do Not Track") est activé.

### `deviceLat`
- **Type:** Nombre
- **Utilité:** Latitude du périphérique.

### `deviceLon`
- **Type:** Nombre
- **Utilité:** Longitude du périphérique.

### `deviceModel`
- **Type:** Chaîne de caractères
- **Utilité:** Modèle du périphérique.

### `deviceVersion`
- **Type:** Chaîne de caractères
- **Utilité:** Version du périphérique.

### `appName`
- **Type:** Chaîne de caractères
- **Utilité:** Nom de l'application.

### `deviceId`
- **Type:** Chaîne de caractères
- **Utilité:** Identifiant unique du périphérique.

### `appVersion`
- **Type:** Chaîne de caractères
- **Utilité:** Version de l'application.

### `deviceType`
- **Type:** Chaîne de caractères
- **Utilité:** Type de périphérique (web, samsung-tvplus, etc.).

### `deviceMake`
- **Type:** Chaîne de caractères
- **Utilité:** Marque du périphérique.

## Paramètres Optionnels

### `advertisingId`
- **Type:** Chaîne de caractères
- **Utilité:** Identifiant unique utilisé pour le suivi publicitaire.

### `embedPartner`
- **Type:** Chaîne de caractères
- **Utilité:** Partenaire d'intégration pour l'incorporation du flux vidéo.

### `samsung_app_domain`
- **Type:** Chaîne de caractères
- **Utilité:** Domaine de l'application Samsung associée.

### `samsung_app_name`
- **Type:** Chaîne de caractères
- **Utilité:** Nom de l'application Samsung.

### `serverSideAds`
- **Type:** Booléen
- **Valeur possible:** true, false
- **Utilité:** Indique si les annonces doivent être gérées côté serveur.

### `us_privacy`
- **Type:** Chaîne de caractères
- **Utilité:** Informations de confidentialité ou réglementations (1YNY ou similaire).

### `includeDeviceUA`
- **Type:** Booléen
- **Valeur possible:** true, false
- **Utilité:** Inclure ou non l'en-tête "User-Agent" du périphérique.

## Notes
- Les valeurs possibles indiquées sont basées sur les informations fournies. Veuillez consulter la documentation de Pluto TV pour les valeurs exactes et les mises à jour éventuelles.
- Certains paramètres sont spécifiques à certaines plateformes (par exemple, les paramètres Samsung).
- Les paramètres non listés dans cette documentation peuvent ne pas être nécessaires ou pertinents pour votre utilisation spécifique.




# Documentation des Paramètres

Voici la liste des paramètres utilisés dans l'URL ainsi que leur utilité :

## Paramètres Obligatoires

- `sid`: Identifiant de session unique généré pour chaque flux vidéo.
- `deviceDNT`: Signale si le suivi ("Do Not Track") est activé (0 ou 1).
- `deviceId`: Identifiant unique du périphérique.
- `deviceModel`: Modèle du périphérique.
- `deviceVersion`: Version du périphérique.
- `appVersion`: Version de l'application.
- `deviceType`: Type de périphérique (web, samsung-tvplus, etc.).
- `deviceMake`: Marque du périphérique.

## Paramètres Optionnels

- `terminate`: Contrôle si la lecture doit être terminée prématurément (true ou false).
- `advertisingId`: Identifiant unique utilisé pour le suivi publicitaire.
- `deviceLat`: Latitude du périphérique.
- `deviceLon`: Longitude du périphérique.
- `embedPartner`: Partenaire d'intégration pour l'incorporation du flux vidéo.
- `samsung_app_domain`: Domaine de l'application Samsung associée.
- `samsung_app_name`: Nom de l'application Samsung.
- `serverSideAds`: Indique si les annonces doivent être gérées côté serveur (true ou false).
- `us_privacy`: Informations de confidentialité ou réglementations (1YNY ou similaire).
- `appName`: Nom de l'application.
- `includeDeviceUA`: Inclure ou non l'en-tête "User-Agent" du périphérique.

## Paramètres de l'API Pluto TV

- **offset:** Permet de spécifier le nombre d'entrées de données à récupérer. Par exemple, `offset=10` récupérera les 10 premières données de la page.

- **page:** Utilisé pour naviguer entre les pages de résultats lorsque la liste est paginée. Par exemple, `page=2` affichera la deuxième page de résultats si le paramètre `offset` a été utilisé.

- **includeItems:** Un booléen qui indique si les détails des éléments tels que les sous-catégories, séries, etc., doivent être inclus dans la réponse. Par exemple, `includeItems=true` ou `includeItems=false`.

- **deviceType:** Utilisé pour indiquer le type d'appareil à partir duquel vous accédez à l'API. Par exemple, `deviceType=web`, `deviceType=android`, `deviceType=ios`, etc.
- **itemoffset** Utilisé pour spécifier le nombre d'entrées de données à récupérer dans les items.
- **itempage** Utilisé pour naviguer entre les pages de résultat des items lorsque la liste est paginée.

Ces paramètres vous permettent de personnaliser les résultats renvoyés par l'API de Pluto TV en fonction de vos besoins et de votre plateforme d'accès.
