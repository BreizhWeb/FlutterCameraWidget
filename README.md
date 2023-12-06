# Camera App

A simple Flutter application to capture images using the `Camera` widget.

## Installation

1. Make sure you have Flutter installed on your system. If not, follow the instructions on [flutter.dev](https://flutter.dev/docs/get-started/install).

2. Clone this repository:
```bash
git clone https://github.com/BreizhWeb/FlutterCameraWidget.git
```

3. Accédez au répertoire de l'application :
```bash
cd FlutterCameraWidget
```

4. Ajoutez la dépendance camera avec cette commande, le changement se fera dans le fichier pubspec.yaml :
```bash
flutter pub get add camera
```
```yml
dependencies:
  flutter:
    sdk: flutter
  camera: ^0.10.25
```

5. Exécutez la commande flutter pub get pour installer les dépendances :
```bash
flutter pub get
```

6. Configuration Android :

Ouvrez le fichier android/app/src/main/AndroidManifest.xml.
Ajoutez ces lignes à l'intérieur de la balise <manifest> :
```xml
<uses-permission android:name="android.permission.CAMERA" />
<uses-feature android:name="android.hardware.camera" />
<uses-feature android:name="android.hardware.camera.autofocus" />
```

## Utilisation

1. Assurez-vous que votre périphérique dispose d'une caméra.

2. Lancez l'application en utilisant la commande :

```bash
flutter run
```

3. L'application s'ouvrira et affichera la prévisualisation de la caméra.

4. Appuyez sur l'icône de l'appareil photo pour capturer une image.




