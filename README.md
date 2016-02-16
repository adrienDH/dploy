Installation de Dploy
==
- Avoir npm d'installé 
 
<pre><code>npm install dploy -g</code></pre>

- Vérifié l'installation avec <pre><code>dploy --version</code></pre>

- Aller dans le répertoire du projet

<pre><code>dploy install</code></pre>

- Ouvrir à la racine le fichier "dploy.yaml"

- Garder qu'un seul bloc que l'on renommera à souhait

- Mettre les bonnes valeurs dans les différents champs
<pre><code>
mon-environnement: 
    scheme: ftp 
    host: ftp.my-live-server.com 
    port: 21 
    user: monnom 
    pass: monMotDePass
    check: true 
    path: 
        remote: /www/
</code></pre>

Sécurité
==
-  Mettre le "dploy.yaml" dans le .gitignore

Utilisation
==
lancer la commande dans le répertoire du projet : 
<pre><code>dploy</code></pre>
ou
<pre><code>dploy mon-environnement</code></pre>
