## Générer du code NodeJS avec CodeGen à partir d'une spécification OAS au format JSON ou YAML.
---

### Avec votre fichier
* au format JSON (remplacez le contenu du fichier **your-spec.json**)

`java -jar swagger-codegen-cli.jar generate -i your-spec.json -l spring -o server/spring`{{execute}}

* au format YAML (remplacez le contenu du fichier **your-spec.yaml**)

`java -jar swagger-codegen-cli.jar generate -i your-spec.yaml -l spring -o server/spring`{{execute}}

### A partir de la correction du Lab #1

`java -jar swagger-codegen-cli.jar generate -i lab-1-correction.yaml -l spring -o server/spring`{{execute}}

### Options disponibles pour la génération

* [Documentation Github](https://github.com/swagger-api/swagger-codegen#generators)
