# practica-github-01
# Pràctica 01 — GitHub: Fork i Pull Request

## Objectiu

Aprendre a treballar de manera col·laborativa amb Git i GitHub, utilitzant repositoris remots, forks, commits i pull requests.

## 1. Crear un compte de GitHub

Crea un compte a https://github.com amb el teu correu corporatiu `@alu.edu.gva.es`.

## 2. Fer un fork

Accedeix al repositori del professor:

https://github.com/ahernandezdom/practica-github-01

Prem el botó **Fork** i crea una còpia del repositori al teu compte de GitHub.

## 3. Clonar el repositori

Obri un terminal d'Ubuntu i executa:

```bash
cd ~
mkdir -p repos
cd repos
git clone https://github.com/EL_TEU_USUARI/practica-github-01.git
cd practica-github-01
code .
```

Substitueix `EL_TEU_USUARI` pel teu nom d'usuari de GitHub.

## 4. Modificar els arxius

- Obri `classe.txt` i afegeix una nova línia amb les teues dades, seguint el format indicat.
- Afig un pòster d'una pel·lícula a la carpeta `images`.
- El nom de la imatge ha de contindre el número de PC i el teu nom. Exemple: `15_jordi.jpg`.

## 5. Guardar els canvis

Des del terminal, executa:

```bash
git add --all
git commit -m "Modificació NomAlumne"
git push -u origin main
```

## 6. Crear un Pull Request

Accedeix al teu repositori de GitHub, entra a **Pull requests** i crea una sol·licitud per incorporar els teus canvis al repositori original del professor.

## 7. Sincronitzar el repositori

Quan el professor haja acceptat els canvis dels companys, sincronitza el teu fork amb el repositori original mitjançant **Sync fork** a GitHub.

Després, al terminal, executa:

```bash
git pull origin main
```

Comprova amb Visual Studio Code els canvis al fitxer `classe.txt` i a la carpeta `images`.

## Lliurament

Entrega l'enllaç del teu Pull Request al professor.
