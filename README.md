
# Lecteur vidéo YouTube Flutter

Ce widget représente un lecteur vidéo YouTube dans une application mobile Flutter. Il permet à l'utilisateur de regarder des vidéos à partir de liens YouTube directement dans l'application.

## Fonctionnalités

- Lecture de vidéos YouTube dans l'application.
- Contrôles de lecture intégrés (lecture, pause, avance rapide, etc.).
- Prise en charge du mode plein écran pour une expérience immersive.
- Lecture automatique, boucle et fonction de sourdine.

## Captures d'écran

![Capture d'écran du lecteur vidéo YouTube](https://images.everyeye.it/img-notizie/ia-never-gonna-give-you-up-rick-astley-trionfale-remaster-4k-v6-500421.jpg)

## Utilisation

Pour utiliser ce widget, vous pouvez l'incorporer dans votre application Flutter en important le fichier `home_page_widget.dart` et en l'appelant dans votre arborescence de widgets.

```dart
import 'home_page_widget.dart';

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Mon Lecteur Vidéo YouTube',
      home: Scaffold(
        body: HomePageWidget(),
      ),
    );
  }
}
```

## Dépendances

Ce widget utilise les dépendances suivantes :
- flutter
- provider

Pour installer ces dépendances, ajoutez les lignes suivantes à votre fichier `pubspec.yaml` :

```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^5.0.0
```

## Auteur

Ce widget a été développé par Paul-Franck Dencausse.
