# MinimalApp - Application iOS Minimaliste

Une application iOS simple et élégante créée avec SwiftUI, présentant une landing page minimaliste.

## Fonctionnalités

- Interface utilisateur moderne avec SwiftUI
- Landing page avec gradient coloré
- Design minimaliste et épuré
- Compatible iPhone et iPad
- Support iOS 15+

## Comment ouvrir le projet dans Xcode

1. Ouvrez Xcode sur votre Mac
2. Sélectionnez "Open a project or file"
3. Naviguez vers le dossier `MinimalApp` et sélectionnez le fichier `MinimalApp.xcodeproj`
4. Attendez que Xcode charge le projet

## Comment exécuter l'application

1. Sélectionnez un simulateur iOS dans la barre d'outils Xcode (par exemple, iPhone 15)
2. Appuyez sur le bouton "Play" (▶️) ou utilisez le raccourci `Cmd + R`
3. L'application se lancera dans le simulateur

## Structure du projet

```
MinimalApp/
├── MinimalApp/
│   ├── MinimalAppApp.swift      # Point d'entrée de l'application
│   ├── ContentView.swift        # Vue principale (Landing page)
│   ├── Assets.xcassets/         # Ressources (icônes, couleurs)
│   └── Preview Content/         # Ressources pour les previews Xcode
└── MinimalApp.xcodeproj/        # Configuration du projet Xcode
```

## Personnalisation

Vous pouvez facilement personnaliser l'application en modifiant :

- **ContentView.swift** : Modifiez le texte, les couleurs, ou ajoutez de nouveaux éléments UI
- **Gradient** : Changez les couleurs du dégradé dans `LinearGradient`
- **Icône** : Remplacez `systemName: "swift"` par une autre icône SF Symbols
- **Texte** : Personnalisez "Minimal App" et le sous-titre selon vos besoins

## Exigences

- macOS avec Xcode 15.0 ou supérieur
- iOS 15.0 ou supérieur pour le déploiement

## Licence

Ce projet est open source et disponible pour tous.
