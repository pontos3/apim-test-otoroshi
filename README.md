# apim-test-otoroshi

## Objectif

Mettre en place un moyen de tester otoroshi un API Manager développé par la MAIF

[otoroshi](https://www.otoroshi.io/)


## 1-démarrage-simple

Afin de démarrer l'instance Otoroshi, lancer la commande ci-dessous :

```bash
docker compose up -d
```
* APIM : Ototroshi
  * l'instance est accessible via l'adresse  : "http://otoroshi.oto.tools:8080/"
  * Login admin : "admin@otoroshi.io"
  * Mot de passe admin : "P@ssw0rd"
  * La configuration d'othoroshi est ici : ./conf/oto.conf
  * Les données de l'outil sont stokées dans le fichier ./filedb/state.ndjson
* API de test : httpbin
  * La doc : [httpbin](https://httpbin.org/)
  * l'accès local : [httpbin-local](http://127.0.0.1)



### Elements installés

* Une instance otoroshi : l'outil à tester
* une intance httbin : une api de test