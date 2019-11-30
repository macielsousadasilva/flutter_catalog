
# Flutter Catalog

<a href='https://play.google.com/store/apps/details?id=io.github.x_wei.flutter_catalog'>
  <img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width='200'/>
</a>

<a href="https://itunes.apple.com/us/app/flutter-catalog/id1458332586?mt=8">
  <img alt='Get it on AppStore' src='https://linkmaker.itunes.apple.com/en-us/badge-lrg.svg?releaseDate=2019-04-02&kind=iossoftware&bubble=ios_apps' width='200'>
</a>

<a href="https://github.com/Solido/awesome-flutter#components">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>

Um aplicativo que mostra os componentes do Flutter, com exibição de código-fonte lado a lado.

## Screenshots

<img src="screenshots/Screenshot_1546722517.png" width="240px" />
<img src="screenshots/Screenshot_1541613187.png" width="240px" />
<img src="screenshots/Screenshot_1541613193.png" width="240px" />
<img src="screenshots/Screenshot_1541613197.png" width="240px" />
<img src="screenshots/Screenshot_1546722832.png" width="240px" />
<img src="screenshots/Screenshot_1546722852.png" width="240px" />


## Como contribuir adicionando uma nova página de exemplo

1. Create a dart filCrie um arquivo herdado de `lib/route/` (ou apenas duplicar um arquivo, `cp widgets_icon_ex.dart new_example.dart`);
2. No novo arquivo, crie uma classe que estenda MyRoute;;
3. Adicionar construtor const, a convenção é usar o caminho do arquivo como parâmetro padrão do construtor;
4. (Opcional) substituir getters: `title`, `description`, `links`;
5. Sobrepor `buildMyRouteContent()`, tente simplificar o código, como será mostrado nas telas do telefone;
6. Abrir `lib/my_app_meta.dart`, importe o novo arquivo no início do arquivo;
7. Em `kMyAppRoutesStructure`, adicione uma instanciação da nova classe no grupo de itens apropriado.

## Credits

Este aplicativo foi escrito com referência a muitos recursos, incluindo:

* Offical gallery app: https://github.com/flutter/flutter/tree/master/examples/flutter_gallery
* Andrea Bizzotto's YouTube channel: https://www.youtube.com/channel/UCrTnsT4OYZ53l0QGKqLeD5Q
* Tensor Programming's YouTube channel: https://www.youtube.com/watch?v=WwhyaqNtNQY&list=PLJbE2Yu2zumDqr_-hqpAN0nIr6m14TAsd
* Eajy's flutter demo: https://github.com/Eajy/flutter_demo


#----------------------------------------




# Flutter Catalog

<a href='https://play.google.com/store/apps/details?id=io.github.x_wei.flutter_catalog'>
  <img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' width='200'/>
</a>

<a href="https://itunes.apple.com/us/app/flutter-catalog/id1458332586?mt=8">
  <img alt='Get it on AppStore' src='https://linkmaker.itunes.apple.com/en-us/badge-lrg.svg?releaseDate=2019-04-02&kind=iossoftware&bubble=ios_apps' width='200'>
</a>

<a href="https://github.com/Solido/awesome-flutter#components">
   <img alt="Awesome Flutter" src="https://img.shields.io/badge/Awesome-Flutter-blue.svg?longCache=true&style=flat-square" />
</a>

An app showcasing Flutter components, with side-by-side source code view.

## Screenshots

<img src="screenshots/Screenshot_1546722517.png" width="240px" />
<img src="screenshots/Screenshot_1541613187.png" width="240px" />
<img src="screenshots/Screenshot_1541613193.png" width="240px" />
<img src="screenshots/Screenshot_1541613197.png" width="240px" />
<img src="screenshots/Screenshot_1546722832.png" width="240px" />
<img src="screenshots/Screenshot_1546722852.png" width="240px" />


## How to contribute by adding a new example page

1. Create a dart file under `lib/route/` (or just duplicate a file, e.g. `cp widgets_icon_ex.dart new_example.dart`);
2. In the new file, create a class that extends MyRoute;
3. Add const constructor, the convention is to use the file path as constructor's default parameter;
4. (Optional) override getters: `title`, `description`, `links`;
5. Override `buildMyRouteContent()`, try to make the code simple, as it'll be shown on phone screens;
6. Open `lib/my_app_meta.dart`, import the new file at the beginning of file;
7. In `kMyAppRoutesStructure`, add an instantiation of the new class under the appropriate item group.

## Credits

This app is written with reference to many resources, including:

* Offical gallery app: https://github.com/flutter/flutter/tree/master/examples/flutter_gallery
* Andrea Bizzotto's YouTube channel: https://www.youtube.com/channel/UCrTnsT4OYZ53l0QGKqLeD5Q
* Tensor Programming's YouTube channel: https://www.youtube.com/watch?v=WwhyaqNtNQY&list=PLJbE2Yu2zumDqr_-hqpAN0nIr6m14TAsd
* Eajy's flutter demo: https://github.com/Eajy/flutter_demo
