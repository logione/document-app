# LogiONE Document Desktop App
[Français](https://github.com/logione/document-app/blob/main/README.md#%C3%A0-propos)

Welcome to the LogiONE Document Desktop App repository. This repository is dedicated to publishing the latest releases of the desktop version of LogiONE Document.

## About

LogiONE Document is a powerful document management tool that streamlines the process of organizing, storing, and retrieving documents. The desktop version brings all the functionality of the web app to your local machine, allowing for opening documents on your desktop.

## Installation Instructions

### Debian-based systems (.deb)

1. Download the `.deb` package from the [Releases](https://github.com/logione/document-app/releases) page.
2. Open a terminal window.
3. Navigate to the directory where the downloaded file is located.
4. Run the following command to install the package:
   ```bash
   sudo dpkg -i logione-document_x.x.x_amd64.deb
   ```
5. If there are any dependency issues, resolve them by running:
   ```bash
   sudo apt-get install -f
   ```

### Red Hat-based systems (.rpm)

1. Download the `.rpm` package from the [Releases](https://github.com/logione/document-app/releases) page.
2. Open a terminal window.
3. Navigate to the directory where the downloaded file is located.
4. Run the following command to install the package:
   ```bash
   sudo rpm -i logione-document-x.x.x.x86_64.rpm
   ```
5. If there are any dependency issues, resolve them by running:
   ```bash
   sudo yum install -f
   ```
   or for systems using `dnf`:
   ```bash
   sudo dnf install -f
   ```

### Windows (.exe)

1. Download the `.exe` file from the [Releases](https://github.com/logione/document-app/releases) page.
2. Double-click on the downloaded file to start the installation process.

## Troubleshooting

### Ubuntu: Launching the App with `--no-sandbox` switch

If you're experiencing issues launching the LogiONE Document Desktop App on Ubuntu, it may be necessary to start the application with the `--no-sandbox` switch. This is particularly relevant if you encounter permissions or sandbox-related errors. To do this:

1. Open a terminal window.
2. Run the application with the `--no-sandbox` switch by executing:
   ```bash
   logione-document --no-sandbox
   ```

Please note that running the app with `--no-sandbox` might expose your system to additional security risks. Use this workaround only if you understand the implications.


## Support

If you need any assistance or require a version for a different architecture, please contact our support team. We're here to help!

- **Email:** info@logi.one
- **Phone:** +41 21 552 15 15

---

Thank you for using LogiONE Document!

---

----
<br>
<br>

## À propos

LogiONE Document est un outil puissant de gestion de documents qui simplifie le processus d'organisation, de stockage et de récupération des documents. La version de bureau vous permet d'ouvrir les documents avec vos applications préférées.

## Instructions d'installation

### Systèmes basés sur Debian (.deb)

1. Téléchargez le paquet `.deb` depuis la page des [Releases](https://github.com/logione/document-app/releases).
2. Ouvrez un terminal.
3. Naviguez jusqu'au répertoire où le fichier téléchargé est situé.
4. Exécutez la commande suivante pour installer le paquet :
   ```bash
   sudo dpkg -i logione-document_x.x.x_amd64.deb
   ```
5. Si vous rencontrez des problèmes de dépendances, résolvez-les en exécutant :
   ```bash
   sudo apt-get install -f
   ```

### Systèmes basés sur Red Hat (.rpm)

1. Téléchargez le paquet `.rpm` depuis la page des [Releases](https://github.com/logione/document-app/releases).
2. Ouvrez un terminal.
3. Naviguez jusqu'au répertoire où le fichier téléchargé est situé.
4. Exécutez la commande suivante pour installer le paquet :
   ```bash
   sudo rpm -i logione-document-x.x.x.x86_64.rpm
   ```
5. Si vous rencontrez des problèmes de dépendances, résolvez-les en exécutant :
   ```bash
   sudo yum install -f
   ```
   ou pour les systèmes utilisant `dnf` :
   ```bash
   sudo dnf install -f
   ```

### Windows (.exe)

1. Téléchargez le fichier `.exe` depuis la page des [Releases](https://github.com/logione/document-app/releases).
2. Double-cliquez sur le fichier téléchargé pour commencer le processus d'installation.

## Dépannage

### Ubuntu : Lancer l'application avec l'option `--no-sandbox`

Si vous rencontrez des problèmes pour lancer l'application LogiONE Document Desktop sur Ubuntu, il peut être nécessaire de démarrer l'application avec l'option `--no-sandbox`. Ceci est particulièrement pertinent si vous rencontrez des erreurs liées aux permissions ou au sandbox. Pour ce faire :

1. Ouvrez un terminal.
2. Lancez l'application avec l'option `--no-sandbox` en exécutant :
   ```bash
   logione-document --no-sandbox
   ```

Veuillez noter que lancer l'application avec `--no-sandbox` peut exposer votre système à des risques de sécurité supplémentaires. Utilisez cette solution de contournement uniquement si vous comprenez les implications.

## Support

Si vous avez besoin d'assistance ou si vous nécessitez une version pour une architecture différente, veuillez contacter notre équipe de support. Nous sommes là pour aider !

---

Merci d'utiliser LogiONE Document!

---
