# bt-controller-esp32

Code pour controller un robot esp32 à l'aide d'une manette ps4 ou xbox one.

## Installation

Pour installer le arduino IDE: winget install ArduinoSA.IDE.stable

## Configuration

Ajouter les liens suivants dans les préférences de l'IDE arduino:

- <https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json>
- <https://raw.githubusercontent.com/ricardoquesada/esp32-arduino-lib-builder/master/bluepad32_files/package_esp32_bluepad32_index.json>

Il faut ensuite installer les board manager pour esp32 et bluepad32. Pour ce faire, aller dans Outils -> Type de carte -> Gestionnaire de carte. Rechercher "esp32" et "bluepad32" et installer les deux.
