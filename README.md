# Awesome Flutter

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![](https://img.shields.io/badge/dependencies-zero-green)
[![Last Commits](https://img.shields.io/github/last-commit/nepaul/awesome-flutter?logo=git&logoColor=white)](https://github.com/nepaul/awesome-flutter/commits/master)
[![Pull Requests](https://img.shields.io/github/issues-pr/nepaul/awesome-flutter?logo=github&logoColor=white)](https://github.com/nepaul/awesome-flutter/pulls)
[![Code size](https://img.shields.io/github/languages/code-size/nepaul/awesome-flutter?logo=github&logoColor=white)](https://github.com/nepaul/awesome-flutter)

All you should know about Flutter development!

A curated list of awesome Flutter libraries, tools, tutorials, articles and more..

**Show some ❤️ and star the repo to support the project**

# Table of Contents

- [Awesome Flutter](#awesome-flutter)
- [Table of Contents](#table-of-contents)
  - [Document](#document)
  - [Style Guide](#style-guide)
  - [Community](#community)
  - [Starter Samples](#starter-samples)
  - [Add Flutter to existing app](#add-flutter-to-existing-app)
  - [Navigation \& Routing](#navigation--routing)
  - [Data \& Backend](#data--backend)
    - [Storage](#storage)
    - [State management](#state-management)
    - [Network](#network)
  - [Components](#components)
    - [UI Kits](#ui-kits)
    - [Theme](#theme)
    - [Color](#color)
    - [Text](#text)
    - [Button](#button)
    - [Icon](#icon)
    - [Toast \& Loading \& Refresh \& Notifications](#toast--loading--refresh--notifications)
    - [Dialog \& Alert](#dialog--alert)
    - [Popup \& Sheet](#popup--sheet)
    - [Picker](#picker)
    - [Bar](#bar)
    - [Chart](#chart)
    - [Switch](#switch)
    - [Swipe \& Slide \& Indicator](#swipe--slide--indicator)
    - [Badges \& Labels \& Tags](#badges--labels--tags)
    - [Datetime](#datetime)
    - [Calendars](#calendars)
    - [Clippers](#clippers)
    - [Images](#images)
    - [List \& Grid](#list--grid)
    - [Input \& Form](#input--form)
    - [Select](#select)
    - [Steps \& Timelines](#steps--timelines)
    - [Progress](#progress)
    - [Menu](#menu)
    - [Editor](#editor)
    - [Effect](#effect)
  - [Plugins](#plugins)
  - [Utils](#utils)
  - [Games](#games)
  - [CI/CD](#cicd)
  - [Monitor](#monitor)
  - [Tools](#tools)
  - [Service](#service)
  - [Apps](#apps)
  - [Desktop Only](#desktop-only)
  - [No-Code / Low-Code](#no-code--low-code)
  - [Contribution](#contribution)
  - [License](#license)

## Document

- ![](https://img.shields.io/github/stars/kamranahmedse/developer-roadmap?style=social) [Flutter Developer Roadmap](https://github.com/kamranahmedse/developer-roadmap)

- ![](https://img.shields.io/github/stars/londonappbrewery/Flutter-Course-Resources?style=social)[Flutter-Course-Resources](https://github.com/londonappbrewery/Flutter-Course-Resources)

- ![](https://img.shields.io/github/stars/olexale/flutter_roadmap?style=social) [Flutter Roadmap](https://github.com/olexale/flutter_roadmap)

- ![](https://img.shields.io/github/stars/FilledStacks/flutter-tutorials?style=social) [flutter-tutorials](https://github.com/FilledStacks/flutter-tutorials) - The repo contains the source code for all the written tutorials by Filledstacks.

  All Tutorials plus additional snippets and shorter posts can be found on the Official FilledStacks website.

- ![](https://img.shields.io/github/stars/mkobuolys/flutter-design-patterns?style=social) [flutter-design-patterns](https://github.com/mkobuolys/flutter-design-patterns) - An open-source design patterns application built with Dart and Flutter.
- ![](https://img.shields.io/github/stars/VB10/flutter-architecture-template?style=social) [flutter-architecture-template](https://github.com/VB10/flutter-architecture-template) - This project craeeted for proffesionel application arhitecture.

**Best Practices**:

- ![](https://img.shields.io/github/stars/erluxman/awesomefluttertips?style=social) [awesomefluttertips](https://github.com/erluxman/awesomefluttertips)

## Style Guide

**Lint**

- ![](https://img.shields.io/github/stars/fluttercommunity/import_sorter?style=social) [import_sorter](https://github.com/fluttercommunity/import_sorter) -  🎯 Dart package to automatically organize your dart imports. Any dart project supported! Will sorts imports alphabetically and then group them in the following order:

  1. Dart imports
  2. Flutter imports
  3. Package imports
  4. Project imports

- ![](https://img.shields.io/github/stars/fluttercommunity/import_sorter?style=social) [flutter-surf-lint-rules](https://github.com/surfstudio/flutter-surf-lint-rules)

- ![](https://img.shields.io/github/stars/dart-lang/lints?style=social) [Official Dart lint rules](https://github.com/dart-lang/lints) - The Dart linter is a static analyzer for identifying possible problems in your Dart source code. More than a hundred linter rules are available, checking anything from potential typing issues, coding style, and formatting. This package, lints, contains the lint settings recommended by the Dart team.

- ![](https://img.shields.io/github/stars/camus-design/camus_lints?style=social) [Camus Lints](https://github.com/camus-design/camus_lints)

## Community

- [fluttercommunity](https://github.com/fluttercommunity) - A central place for all community made Flutter packages. To get started, see the README of the 'community' repository.

- [fluttercandies](https://github.com/fluttercandies) - Custom Flutter Candies (packages) for you to build your Flutter app easily. Enjoy it!

## Starter Samples

- **OFFICIAL!** ![](https://img.shields.io/github/stars/flutter/packages?style=social) [flutter/packages](https://github.com/flutter/packages) - This repo is a companion repo to the main flutter repo. It contains the source code for Flutter's first-party packages (i.e., packages developed by the core Flutter team). Check the packages directory to see all packages.

  These are the available packages in this repository.

  | Plugin | Pub |
  |--------|-----|
  | [animations](https://github.com/flutter/packages/animations/) | [![pub package](https://img.shields.io/pub/v/animations.svg)](https://pub.dev/packages/animations) |
  | [css\_colors](https://github.com/flutter/packages/css_colors/) | [![pub package](https://img.shields.io/pub/v/css_colors.svg)](https://pub.dev/packages/css_colors) |
  | [extension\_google\_sign\_in\_as\_googleapis\_auth](https://github.com/flutter/packages/extension_google_sign_in_as_googleapis_auth/) | [![pub package](https://img.shields.io/pub/v/extension_google_sign_in_as_googleapis_auth.svg)](https://pub.dev/packages/extension_google_sign_in_as_googleapis_auth) |
  | [fuchsia\_ctl](https://github.com/flutter/packages/fuchsia_ctl/) | [![pub package](https://img.shields.io/pub/v/fuchsia_ctl.svg)](https://pub.dev/packages/fuchsia_ctl) |
  | [flutter\_image](https://github.com/flutter/packages/flutter_image/) | [![pub package](https://img.shields.io/pub/v/flutter_image.svg)](https://pub.dev/packages/flutter_image) |
  | [flutter\_lints](https://github.com/flutter/packages/flutter_lints/) | [![pub package](https://img.shields.io/pub/v/flutter_lints.svg)](https://pub.dev/packages/flutter_lints) |
  | [flutter\_markdown](https://github.com/flutter/packages/flutter_markdown/) | [![pub package](https://img.shields.io/pub/v/flutter_markdown.svg)](https://pub.dev/packages/flutter_markdown) |
  | [go\_router](https://github.com/flutter/packages/go_router/) | [![pub package](https://img.shields.io/pub/v/go_router.svg)](https://pub.dev/packages/go_router) |
  | [multicast\_dns](https://github.com/flutter/packages/multicast_dns/) | [![pub package](https://img.shields.io/pub/v/multicast_dns.svg)](https://pub.dev/packages/multicast_dns) |
  | [palette\_generator](https://github.com/flutter/packages/palette_generator/) | [![pub package](https://img.shields.io/pub/v/palette_generator.svg)](https://pub.dartlang.org/packages/palette_generator) |
  | [pigeon](https://github.com/flutter/packages/pigeon/) | [![pub package](https://img.shields.io/pub/v/pigeon.svg)](https://pub.dev/packages/pigeon) |
  | [pointer\_interceptor](https://github.com/flutter/packages/pointer_interceptor/) | [![pub package](https://img.shields.io/pub/v/pointer_interceptor.svg)](https://pub.dev/packages/pointer_interceptor) |
  | [xdg\_directories](https://github.com/flutter/packages/xdg_directories/) | [![pub package](https://img.shields.io/pub/v/xdg_directories.svg)](https://pub.dev/packages/xdg_directories) |

- ![](https://img.shields.io/github/stars/alibaba/flutter-go?style=social) [FlutterGo](https://github.com/alibaba/flutter-go)
- ![](https://img.shields.io/github/stars/iampawan/FlutterExampleApps?style=social) [FlutterExampleApps](https://github.com/iampawan/FlutterExampleApps) - Example APPS Basic Flutter apps, for flutter devs.
- ![](https://img.shields.io/github/stars/flutter/samples?style=social) 🥰 [Flutter Official Samples](https://github.com/flutter/samples) -  A collection of open source samples that illustrate best practices for Flutter.

- ![](https://img.shields.io/github/stars/brianegan/flutter_architecture_samples?style=social)[flutter_architecture_samples](https://github.com/brianegan/flutter_architecture_samples) -  TodoMVC for Flutter <http://fluttersamples.com/>

- ![](https://img.shields.io/github/stars/kaina404/FlutterDouBan?style=social)[FlutterDouBan](https://github.com/kaina404/FlutterDouBan) -  A Douban client that uses Flutter to restore

- ![](https://img.shields.io/github/stars/flutter/gallery?style=social) [Flutter Gallery](https://github.com/flutter/gallery) s a resource to help developers evaluate and use Flutter. It is a collection of Material Design & Cupertino widgets, behaviors, and vignettes implemented with Flutter. We often get asked how one can see Flutter in action, and this gallery demonstrates what Flutter provides and how it behaves in the wild.

- ![](https://img.shields.io/github/stars/Sky24n/flutter_wanandroid?style=social) [flutter_wanandroid](https://github.com/Sky24n/flutter_wanandroid)

- ![](https://img.shields.io/github/stars/FilledStacks/flutter-tutorials?style=social)[flutter-tutorials](https://github.com/FilledStacks/flutter-tutorials) -  The repo contains the source code for all the tutorials on the FilledStacks Youtube channel.

- ![](https://img.shields.io/github/stars/gskinnerTeam/flutter_vignettes?style=social) [The Flutter Vignettes](https://github.com/gskinnerTeam/flutter_vignettes) - A collection of explorations into the exciting user experience possibilities enabled by the Flutter platform. Built by [gskinner](https://gskinner.com/) in partnership with Google, these vignettes range from the practical to the novel. They aim to inspire both developers and designers to build delightful and beautiful experiences with Flutter.

  In addition to forking and reviewing the MIT licensed code available here, you can also check out more information on the [Vignette Showcase Website](https://flutter.gskinner.com/vignettes.html).

- ![](https://img.shields.io/github/stars/diegoveloper/flutter-samples?style=social) [flutter-samples](https://github.com/diegoveloper/flutter-samples)

- ![](https://img.shields.io/github/stars/bdlukaa/fluent_ui?style=social) [fluent_ui](https://github.com/bdlukaa/fluent_ui) - Unofficial implementation of Fluent UI for Flutter. It's written based on the official documentation

- ![](https://img.shields.io/github/stars/yukilzw/dy_flutter?style=social) [dy_flutter](https://github.com/yukilzw/dy_flutter) - The Douyu Live APP refactored by flutter. The home page and entertainment are Material components; the live room and fish bar are purely custom-written. In addition, various high-quality third-party open source libraries are integrated to create a silky user experience for native APPs.

- ![](https://img.shields.io/github/stars/syncfusion/flutter-examples?style=social) [syncfusion/flutter-examples](https://github.com/syncfusion/flutter-examples) - This repository contains awesome demos of Syncfusion Flutter UI widgets. This is the best place to check our widgets to get more insight into the usage of APIs. You can also check our widgets by installing the complete Flutter sample browser from Google Play Store or App Store, in which you can browse the demo for all the widgets and view the source code of each sample within the app itself.

- ![](https://img.shields.io/github/stars/JideGuru/FlutterFoodybite?style=social) [FlutterFoodybite](https://github.com/JideGuru/FlutterFoodybite) - Flutter representation of a Restaurant app UI i found in Uplabs. It only consists of 2 screens.

- ![](https://img.shields.io/github/stars/google/flutter.widgets?style=social) 💗[google/flutter.widgets](https://github.com/google/flutter.widgets) - This repository contains the source code for various Flutter widgets that are developed by Google but not by the core Flutter team.
  - [visibility_detector](https://github.com/google/flutter.widgets/blob/master/packages/visibility_detector/README.md)
  - [self_storing_input](https://github.com/google/flutter.widgets/blob/master/packages/self_storing_input/README.md) - A set of input widgets that automatically save and load the entered value to a data store.
  - [scrollable_positioned_list](https://github.com/google/flutter.widgets/blob/master/packages/scrollable_positioned_list/README.md) - A flutter list that allows scrolling to a specific item in the list. Also allows determining what items are currently visible.
  - [linked_scroll_controller](https://github.com/google/flutter.widgets/blob/master/packages/linked_scroll_controller/README.md) - This package provides a way to set up a set of scrollable widgets whose scrolling is synchronized. The set can be stable across the lifetime of the containing screen, or can change dynamically (for example, a vertically scrolling ListView.builder() whose items are Scrollables that scroll horizontally in unison).
  - [flutter_simple_treeview](https://github.com/google/flutter.widgets/blob/master/packages/flutter_simple_treeview/README.md) - This widget visualises a tree structure, where a node can be any widget.

- ![](https://img.shields.io/github/stars/flutter/codelabs?style=social) [Flutter Official CodeLabs](https://github.com/flutter/codelabs) - This repository contains the code for a variety of Flutter Codelabs. Here is a list of the codelabs represented here:
  - [Adaptive Apps in Flutter](https://codelabs.developers.google.com/codelabs/flutter-adaptive-app) is in `adaptive_app`
  - [Adding Google Maps to a Flutter app](https://codelabs.developers.google.com/codelabs/google-maps-in-flutter) is in `google-maps-in-flutter`
  - [Adding in-app purchases to your Flutter app](https://codelabs.developers.google.com/codelabs/flutter-in-app-purchases) is in `in_app_purchases`
  - [Adding WebView to your Flutter app](https://codelabs.developers.google.com/codelabs/flutter-webview) is in `webview_flutter`
  - [Build a Photo Sharing app with Google Photos and Flutter
](https://codelabs.developers.google.com/codelabs/google-photos-sharing) is in `photos-sharing`
  - [Building a Cupertino app with Flutter](https://codelabs.developers.google.com/codelabs/flutter-cupertino) is in `cupertino_store`
  - [Get to know Firebase for Flutter](https://firebase.google.com/codelabs/firebase-get-to-know-flutter) is in `firebase-get-to-know-flutter`
  - [How to test a Flutter app](https://codelabs.developers.google.com/codelabs/flutter-app-testing) is in `testing_codelab`
  - [How to write a Flutter plugin](https://codelabs.developers.google.com/codelabs/write-flutter-plugin) is in `plugin_codelab`
  - [Using a plugin with a Flutter web app](https://codelabs.developers.google.com/codelabs/web-url-launcher) is in `star_counter`
  - [Write a Flutter desktop application](https://codelabs.developers.google.com/codelabs/flutter-github-client) is in `github-client`
  - [Write your first Flutter app, part 1](https://codelabs.developers.google.com/codelabs/first-flutter-app-pt1) and [Write your first Flutter app, part 2](https://codelabs.developers.google.com/codelabs/first-flutter-app-pt2) are in `startup_namer`
  - [Get started with text classification in Flutter apps](https://developers.google.com/learn/pathways/text-classification-flutter) pathway is in `tfserving-flutter`
  - [Building a fullstack movie recommendation system](https://codelabs.developers.google.com/tfrecommenders-flutter) is in `tfrs-flutter`
  - [Building a board game with TensorFlow Agents and Flutter](https://codelabs.developers.google.com/tfagents-flutter#0) is in `tfagents-flutter`  

  To learn more about setting up Flutter and running apps, see
  [flutter.dev/get-started][].

  [flutter.dev/get-started]: https://flutter.dev/docs/get-started

- ![](https://img.shields.io/github/stars/aagarwal1012/IntroViews-Flutter?style=social) [IntroViews-Flutter](https://github.com/aagarwal1012/IntroViews-Flutter) - IntroViews is inspired by [Paper Onboarding](https://github.com/Ramotion/paper-onboarding-android) and developed with love from scratch. Checkout our fully responsive [live example app](https://introviews-flutter.web.app/)

- ![](https://img.shields.io/github/stars/AliAnilKocak/Flutter-Shopping-UI-Kit?style=social) [Flutter-Shopping-UI-Kit](https://github.com/AliAnilKocak/Flutter-Shopping-UI-Kit) - Shopping UI design in Flutter

- ![](https://img.shields.io/github/stars/abuanwar072/Furniture-App-UI-2-Flutter?style=social)  ![Furniture-App-UI-2-Flutter](https://github.com/abuanwar072/Furniture-App-UI-2-Flutter) -  A responsive furniture app UI using flutter, all of the data come from API so that you can learn how to use API on flutter. There are two pages Home page which contains a horizontal category list then the list of recommended products.

- ![](https://img.shields.io/github/stars/MarcusNg/flutter_covid_dashboard_ui?style=social) [flutter_covid_dashboard_ui](https://github.com/MarcusNg/flutter_covid_dashboard_ui)[[YouTube Video](https://www.youtube.com/watch?v=krU-ASLb8lM&feature=youtu.be&ab_channel=MarcusNg))

- ![](https://img.shields.io/github/stars/VB10/ecommerce_flutter_side?style=social)  [ecommerce_flutter_side](https://github.com/VB10/ecommerce_flutter_side)

**Architecture:**

- ![](https://img.shields.io/github/stars/marcojakob/dart-event-bus?style=social) [Event Bus](https://github.com/marcojakob/dart-event-bus) - A simple Event Bus using Dart Streams for decoupling applications. <details><summary>*More Details*</summary>
   ![](https://raw.githubusercontent.com/marcojakob/dart-event-bus/master/doc/event-bus.png)

</details>

- ![](https://img.shields.io/github/stars/AndriousSolutions/mvc_pattern?style=social) [mvc_pattern](https://github.com/AndriousSolutions/mvc_pattern) - Flutter Plugin to implement one of many variations of the MVC design pattern.

## Add Flutter to existing app

- 💗💗👍👍![](https://img.shields.io/github/stars/alibaba/flutter_boost?style=social) [flutter_boost@alibabba](https://github.com/alibaba/flutter_boost) -  A next-generation Flutter-Native hybrid solution. FlutterBoost is a Flutter plugin which enables hybrid integration of Flutter for your existing native apps with minimum efforts.The philosophy of FlutterBoost is to use Flutter as easy as using a WebView. Managing Native pages and Flutter pages at the same time is non-trivial in an existing App. FlutterBoost takes care of page resolution for you. The only thing you need to care about is the name of the page(usually could be an URL).
- ![](https://img.shields.io/github/stars/hellobike/flutter_thrio?style=social) [flutter_thrio @hellobike](https://github.com/hellobike/flutter_thrio)
- ![](https://img.shields.io/github/stars/gfaraday/g_faraday?style=social)  [Faraday](https://github.com/gfaraday/g_faraday/blob/develop/README_EN.md) - Flutter plugin for integrate flutter to existing app

## Navigation & Routing

- 💗🤔👀 ![](https://img.shields.io/github/stars/theyakka/fluro?style=social) [fluro](https://github.com/theyakka/fluro) -  The brightest, hippest, coolest router for Flutter.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">  ![](https://img.shields.io/github/stars/lejard-h/chopper?style=social)  [chopper](https://github.com/lejard-h/chopper) -  Chopper is an http client generator for Dart and Flutter using source_gen and inspired by Retrofit.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">![](https://img.shields.io/github/stars/slovnicki/beamer?style=social) [](https://github.com/slovnicki/beamer) - A Flutter package to help you handle your application routing and synchronize it with browser URL. Beamer uses the power of Router and implements all the underlying logic for you.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">![](https://img.shields.io/github/stars/csells/go_router?style=social) [go_router](https://github.com/csells/go_router) - The purpose of the go_router package is to use declarative routes to reduce complexity, regardless of the platform you're targeting (mobile, web, desktop), handle deep and dynamic linking from Android, iOS and the web, along with a number of other navigation-related scenarios, while still (hopefully) providing an easy-to-use developer experience.
- ![](https://img.shields.io/github/stars/felangel/flow_builder?style=social) [flow_builder](https://github.com/felangel/flow_builder) - Flutter Flows made easy!

## Data & Backend

- ![](https://img.shields.io/github/stars/ReactiveX/rxdart?style=social) [RxDart](https://github.com/ReactiveX/rxdart) - RxDart extends the capabilities of Dart Streams and StreamControllers.

  Dart comes with a very decent Streams API out-of-the-box; rather than attempting to provide an alternative to this API, RxDart adds functionality from the reactive extensions specification on top of it.

  RxDart does not provide its Observable class as a replacement for Dart Streams. Instead, it offers several additional Stream classes, operators (extension methods on the Stream class), and Subjects.

  If you are familiar with Observables from other languages, please see the [Rx Observables vs. Dart Streams comparison chart](https://github.com/ReactiveX/rxdart#rx-observables-vs-dart-streams) for notable distinctions between the two.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> Google! [json_serializable](https://github.com/google/json_serializable.dart/tree/master/json_serializable) - Provides Dart Build System builders for handling JSON.
  The builders generate code when they find members annotated with classes defined in package:json_annotation.

  To generate to/from JSON code for a class, annotate it with JsonSerializable. You can provide arguments to JsonSerializable to configure the generated code. You can also customize individual fields by annotating them with JsonKey and providing custom arguments. See the table below for details on the annotation values.

  To generate a Dart field with the contents of a file containing JSON, use the JsonLiteral annotation.

- ![](https://img.shields.io/github/stars/k-paxian/dart-json-mapper?style=social) [dart_json_mapper](https://github.com/k-paxian/dart-json-mapper) - This package allows programmers to annotate Dart objects in order to Serialize / Deserialize them to / from JSON.

### Storage

- ![](https://img.shields.io/github/stars/hivedb/hive?style=social) [hive](https://github.com/hivedb/hive) - Hive is a lightweight and blazing fast key-value database written in pure Dart. Inspired by Bitcask.

  If you need queries, multi-isolate support or links between objects check out Isar Database.
  Features
  - 🚀 Cross platform: mobile, desktop, browser
  - ⚡ Great performance (see benchmark)
  - ❤️ Simple, powerful, & intuitive API
  - 🔒 Strong encryption built in
  - 🎈 NO native dependencies
  - 🔋 Batteries included

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/tekartik/sqflite?style=social) [sqflite](https://github.com/tekartik/sqflite) - SQLite plugin for Flutter. Supports iOS, Android and MacOS.

- ![](https://img.shields.io/github/stars/simolus3/drift?style=social) [drift(Moor)](https://github.com/simolus3/drift) - Drift is a reactive persistence library for Flutter and Dart, built on top of sqlite. Drift is

  Flexible: Drift let's you write queries in both SQL and Dart, providing fluent apis for both languages. You can filter and order results or use joins to run queries on multiple tables. You can even use complex sql features like WITH and WINDOW clauses.

- 🔥 Feature rich: Drift has builtin support for transactions, schema migrations, complex filters and expressions, batched updates and joins. We even have a builtin IDE for SQL!
- 📦 Modular: Thanks to builtin support for daos and imports in sql files, drift helps you keep your database code simple.
- 🛡️ Safe: Drift generates typesafe code based on your tables and queries. If you make a mistake in your queries, drift will find it at compile time and provide helpful and descriptive lints.
- ⚡ Fast: Even though drift lets you write powerful queries, it can keep up with the performance of key-value stores like shared preferences and Hive. Drift is the only major persistence library with builtin threading support, allowing you to run database code across isolates with zero additional effort.
Reactive: Turn any sql query into an auto-updating stream! This includes complex queries across many tables
- ⚙️ Cross-Platform support: Drift works on Android, iOS, macOS, Windows, Linux and the web. This template is a Flutter todo app that works on all platforms.
- 🗡️ Battle tested and production ready: Drift is stable and well tested with a wide range of unit and integration tests. It powers production Flutter apps.
With drift, persistence on Flutter is fun!

  To start using drift, read our detailed [docs](https://drift.simonbinder.eu/docs/getting-started/).

- ![](https://img.shields.io/github/stars/isar/isar?style=social) [Isar Database](https://github.com/isar/isar)
  - 💙 Made for Flutter. Easy to use, no config, no boilerplate
  - 🚀 Highly scalable from hundreds to hundreds of thousands of records
  - 🍭 Feature rich. Composite & multi indexes, query modifiers, JSON support and more
  - 🔎 Full-text search. Make searching fast and fun
  - 📱 Multiplatform. iOS, Android, Desktop and the web (soon™)
  - 🧪 ACID semantics. Rely on consistency
  - ⏱ Asynchronous. Parallel query operations & multi-isolate support
  - 💃 Static typing. Compile-time checked and autocompleted queries

- ![](https://img.shields.io/github/stars/mogol/flutter_secure_storage?style=social) [flutter_secure_storage](https://github.com/mogol/flutter_secure_storage) - A Flutter plugin to store data in secure storage:

  - Keychain is used for iOS
  - AES encryption is used for Android. AES secret key is encrypted with RSA and RSA key is stored in KeyStore
  - With V5.0.0 we can use EncryptedSharedPreferences on Android

- ![](https://img.shields.io/github/stars/vitusortner/floor?style=social) [floor](https://github.com/vitusortner/floor) - Floor provides a neat SQLite abstraction for your Flutter applications inspired by the Room persistence library. It comes with automatic mapping between in-memory objects and database rows while still offering full control of the database with the use of SQL. As a consequence, it's necessary to have an understanding of SQL and SQLite in order to harvest Floor's full potential.

- ![](https://img.shields.io/github/stars/realm/realm-dart?style=social) [Realm](https://github.com/realm/realm-dart) -  a mobile database that runs directly inside phones, tablets or wearables. This repository holds the source code for the Realm SDK for Flutter™ and Dart™.
- ![](https://img.shields.io/github/stars/lesnitsky/flutter_localstorage?style=social) [flutter_localstorage](https://github.com/lesnitsky/flutter_localstorage) - Simple json file-based storage for flutter

- ![](https://img.shields.io/github/stars/flutterdata/flutter_data?style=social) [flutter_data](https://github.com/flutterdata/flutter_data/) - Persistent reactive models in Flutter with zero boilerplate. Flutter Data is an offline-first persistence framework that gives you a configurable REST client and powerful model relationships. Heavily inspired by [Ember Data](https://github.com/emberjs/data) and [ActiveRecord](https://guides.rubyonrails.org/active_record_basics.html)

- ![](https://img.shields.io/github/stars/camus-design/simple_shared_preferences?style=social) [simple_shared_preferences](https://github.com/camus-design/simple_shared_preferences) - A simple wrapper for SharedPreferences

### State management

- ![](https://img.shields.io/github/stars/felangel/bloc?style=social) [felangel/bloc](https://github.com/felangel/bloc) - A predictable state management library that helps implement the [BLoC design pattern](https://www.didierboelens.com/2018/08/reactive-programming-streams-bloc/).
- ![](https://img.shields.io/github/stars/alibaba/fish-redux?style=social) [alibaba/fish-redux](https://github.com/alibaba/fish-redux) - is an assembled flutter application framework based on Redux state management. It is suitable for building medium and large applications.

  It has four characteristics:

  - Functional Programming
  - Predictable state container
  - Pluggable componentization
  - Non-destructive performance
- ![](https://img.shields.io/github/stars/jonataslaw/getx?style=social) [getx](https://github.com/jonataslaw/getx) - GetX is an extra-light and powerful solution for Flutter. It combines high-performance state management, intelligent dependency injection, and route management quickly and practically. GetX has 3 basic principles. This means that these are the priority for all resources in the library: PRODUCTIVITY, PERFORMANCE AND ORGANIZATION.

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/rrousselGit/provider?style=social) [provider](https://github.com/rrousselGit/provider) - A wrapper around InheritedWidget to make them easier to use and more reusable.

  By using provider instead of manually writing InheritedWidget, you get:
  - simplified allocation/disposal of resources
  - lazy-loading
  - a vastly reduced boilerplate over making a new class every time
  - devtool friendly – using Provider, the state of your application will be visible in the Flutter devtool
  - a common way to consume these InheritedWidgets (See Provider.of/Consumer/Selector)
  - increased scalability for classes with a listening mechanism that grows exponentially in complexity (such as ChangeNotifier, which is O(N) for dispatching notifications).
- ![](https://img.shields.io/github/stars/rrousselGit/riverpod?style=social) [river_pod](https://github.com/rrousselGit/riverpod) - A state-management library that:
  - catches programming errors at compile time rather than at runtime
  - removes nesting for listening/combining objects
  - ensures that the code is testable

  This project can be considered as a rewrite of provider to make improvements that would be otherwise impossible.

  For learning how to use Riverpod, see its documentation: <https://riverpod.dev>

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/mobxjs/mobx.dart?style=social)  [mobx](https://github.com/mobxjs/mobx.dart) - MobX is a state-management library that makes it simple to connect the reactive data of your application with the UI. This wiring is completely automatic and feels very natural. As the application-developer, you focus purely on what reactive-data needs to be consumed in the UI (and elsewhere) without worrying about keeping the two in sync.

  It's not really magic but it does have some smarts around what is being consumed (observables) and where (reactions), and automatically tracks it for you. When the observables change, all reactions are re-run. What's interesting is that these reactions can be anything from a simple console log, a network call to re-rendering the UI.

  > MobX has been a very effective library for the JavaScript apps and this port to the Dart language aims to bring the same levels of productivity.

- ![](https://img.shields.io/github/stars/fluttercommunity/get_it?style=social) [get_it](https://github.com/fluttercommunity/get_it) - This is a simple Service Locator for Dart and Flutter projects with some additional goodies highly inspired by Splat. It can be used instead of InheritedWidget or Provider to access objects e.g. from your UI.

  Typical usage:

  - Accessing service objects like REST API clients or databases so that they easily can be mocked.
  - Accessing View/AppModels/Managers/BLoCs from Flutter Views

- ![](https://img.shields.io/github/stars/brianegan/scoped_model?style=social) [scoped_model](https://github.com/brianegan/scoped_model) - A set of utilities that allow you to easily pass a data Model from a parent Widget down to its descendants. In addition, it also rebuilds all of the children that use the model when the model is updated. This library was originally extracted from the Fuchsia codebase.

### Network

- ![](https://img.shields.io/github/stars/flutterchina/dio?style=social) [dio](https://github.com/flutterchina/dio) - A powerful Http client for Dart, which supports Interceptors, Global configuration, FormData, Request Cancellation, File downloading, Timeout etc.
- **DART OFFICIAL** ![](https://img.shields.io/github/stars/dart-lang/http?style=social)  [dart-lang/http](https://github.com/dart-lang/http) - A composable, Future-based library for making HTTP requests. This package contains a set of high-level functions and classes that make it easy to consume HTTP resources. It's multi-platform, and supports mobile, desktop, and the browser.

  **Utils**:
  - ![](https://img.shields.io/github/stars/jogboms/flutter_offline?style=social) [flutter_offline](https://github.com/jogboms/flutter_offline) - A tidy utility to handle offline/online connectivity like a Boss. It provides support for both iOS and Android platforms (offcourse).

  - ![](https://img.shields.io/github/stars/komapeb/data_connection_checker?style=social) [data_connection_checker](https://github.com/komapeb/data_connection_checker/) - A pure Dart utility library that checks for an internet connection by opening a socket to a list of specified addresses, each with individual port and timeout. Defaults are provided for convenience.

## Components

### UI Kits

- ![](https://img.shields.io/github/stars/mitesh77/Best-Flutter-UI-Templates?style=social) [💗Best-Flutter-UI-Templates](https://github.com/mitesh77/Best-Flutter-UI-Templates)

- ![](https://img.shields.io/github/stars/iampawan/Flutter-UI-Kit?style=social) [Flutter-UI-Kit: Flutter app for collection of UI in a UIKit](https://github.com/iampawan/Flutter-UI-Kit)

- ![](https://img.shields.io/github/stars/samarthagarwal/FlutterScreens?style=social) [Flutter Screens: A collection of Login Screens, Buttons, Loaders and Widgets with attractive UIs, built with Flutter, ready to be used in your applications.](https://github.com/samarthagarwal/FlutterScreens)

- ![](https://img.shields.io/github/stars/nb312/flutter-ui-nice?style=social) [flutter-ui-nice](https://github.com/nb312/flutter-ui-nice)

- ![](https://img.shields.io/github/stars/ionicfirebaseapp/getwidget?style=social) [getwidget](https://github.com/ionicfirebaseapp/getwidget) - Most popular and easy to use open source UI library with 1000+ Widgets to build flutter app.

- ![](https://img.shields.io/github/stars/Idean/Flutter-Neumorphic?style=social) [Flutter-Neumorphic](https://github.com/Idean/Flutter-Neumorphic) - A complete, ready to use, Neumorphic ui kit for Flutter

- ![](https://img.shields.io/github/stars/Rannie/flui?style=social) [flui](https://github.com/Rannie/flui) -  A powerful UI framework for Google Flutter. <https://www.flui.xin/en/>

- ![](https://img.shields.io/github/stars/olayemii/flutter-ui-kits?style=social) [flutter-ui-kits](https://github.com/olayemii/flutter-ui-kits) - Free Flutter UI Kits based on designs on UpLabs 💓. Includes Wrist Watch Store UI Kit, Language Learning FLutter UI Kit, News UI Flutter UI Kit, Real Estate Flutter UI Kit, Repair Service Flutter UI Kit, AirBnB Redesign Flutter UI Kit, Laundry App Flutter UI Kit.

### Theme

- ![](https://img.shields.io/github/stars/rxlabz/panache?style=social) [panache](https://github.com/rxlabz/panache) - A Flutter Material Theme editor.

  Panache helps you to create beautiful Material themes for your Flutter applications.

  Customize widgets colors and shapes, and download your theme.dart file.

### Color

- ![](https://img.shields.io/github/stars/bregydoc/pigment?style=social) [pigment](https://github.com/bregydoc/pigment) - A simple but useful plugin for use colors with Flutter.
  - You can use string colors (like #01E19F) direct in flutter
  - Pigment extends to Color dar:ui class, then you can use all methods of Color class
  - Pigment 1.0.1 can parse 'rgb()' (e.g. 'rgb(29, 123, 10)').
  - Added CSS colors with default name, you can access from this with CSSColor.* (e.g. Pigment.fromCSSColor(CSSColor.lightsalmon)) or directly with Pigment.fromString('lightsalmon').

### Text

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/leisim/auto_size_text?style=social)[AutoSizeText](https://github.com/leisim/auto_size_text) - Flutter widget that automatically resizes text to fit perfectly within its bounds.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/aagarwal1012/Animated-Text-Kit?style=social) [Animated-Text-Kit](https://github.com/aagarwal1012/Animated-Text-Kit) - A flutter package which contains a collection of some cool and awesome text animations. Recommended package for text animations in Codemagic's Ebook, "Flutter libraries we love". Try out our live [example app](https://animated-text-kit.web.app/#/).
    ![](https://github.com/aagarwal1012/Animated-Text-Kit/raw/master/display/cover.gif?raw=true)
- ![](https://img.shields.io/github/stars/bytedance/RealRichText?style=social) [RealRichText](https://github.com/bytedance/RealRichText) - A Tricky Solution for Implementing Inline-Image-In-Text Feature in Flutter.

- ![](https://img.shields.io/github/stars/marcelgarus/marquee?style=social) [marquee](https://github.com/marcelgarus/marquee) - A Flutter widget that scrolls text infinitely. Provides many customizations including custom scroll directions, durations, curves as well as pauses after every round.

- ![](https://img.shields.io/github/stars/faob-dev/flutter_circular_text?style=social) [flutter_circular_text](https://github.com/faob-dev/flutter_circular_text)

  <img src="https://raw.githubusercontent.com/faob-dev/flutter_circular_text/master/screenshots/multi_circular_text.jpeg" width="200" height="320"/>

### Button

- ![](https://img.shields.io/github/stars/Frezyx/group_button?style=social) [group_button](https://github.com/Frezyx/group_button) - Flutter widget to create a group of buttons fast 🚀. Included Radio and CheckBox buttons models with custom groping types 🤤
- ![](https://img.shields.io/github/stars/juliansteenbakker/sign_in_button?style=social) [sign_in_button](https://pub.dev/packages/sign_in_button) - A Flutter package that provides a set of buttons for signing in with Google, Facebook, Twitter, Apple, Microsoft, GitHub, and more.

### Icon

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png">  ![](https://img.shields.io/github/stars/fluttercommunity/font_awesome_flutter?style=social) [font_awesome_flutter](https://github.com/fluttercommunity/font_awesome_flutter) - The [Font Awesome](https://fontawesome.com/icons) Icon pack available as set of Flutter Icons.
- ![](https://img.shields.io/github/stars/flutter-studio/flutter-icons?style=social) [flutter_icons](https://github.com/flutter-studio/flutter-icons) -  Customizable Icons for Flutter,Inspired by react-native-vector-icons.  
  Bundled Icon Sets:
  - AntDesign by AntFinance (297 icons)
  - Entypo by Daniel Bruce (411 icons)
  - EvilIcons by Alexander Madyankin & Roman Shamin (v1.10.1, 70 icons)
  - Feather by Cole Bemis & Contributors (v4.7.0, 266 icons)
  - FontAwesome by Dave Gandy (v4.7.0, 675 icons)
  - FontAwesome 5 by Fonticons, Inc. (v5.7.0, 1500 (free))
  - Foundation by ZURB, Inc. (v3.0, 283 icons)
  - Ionicons by Ben Sperry (v4.2.4, 696 icons)
  - MaterialIcons by Google, Inc. (v3.0.1, 932 icons)
  - MaterialCommunityIcons by MaterialDesignIcons.com (v4.0.96, 4416 icons)
  - Octicons by Github, Inc. (v8.0.0, 177 icons)
  - Zocial by Sam Collins (v1.0, 100 icons)
  - SimpleLineIcons by Sabbir & Contributors (v2.4.1, 189 icons)
  - Weather Icons by erikflowers (v2.0.10, 596 icons)
- ![](https://img.shields.io/github/stars/iconfont-cli/flutter-iconfont-cli?style=social) [flutter-iconfont-cli](https://github.com/iconfont-cli/flutter-iconfont-cli) - 用纯 JS 把 [iconfont](https://www.iconfont.cn/) 的图标转换成Flutter Widget，不依赖字体，支持多色彩

### Toast & Loading & Refresh & Notifications

- ![](https://img.shields.io/github/stars/CoderMJLee/MJRefresh?style=social) [MJRefresh](https://github.com/CoderMJLee/MJRefresh) - An easy way to use pull-to-refresh
- ![](https://img.shields.io/github/stars/xuelongqy/flutter_easyrefresh?style=social) [flutter_easyrefresh](https://github.com/xuelongqy/flutter_easyrefresh)
- ![](https://img.shields.io/github/stars/jogboms/flutter_spinkit?style=social) [Flutter Spinkit](https://github.com/jogboms/flutter_spinkit) - A collection of loading indicators animated with flutter. Heavily inspired by @tobiasahlin's SpinKit.
- ![](https://img.shields.io/github/stars/peng8350/flutter_pulltorefresh?style=social) [flutter_pulltorefresh](https://github.com/peng8350/flutter_pulltorefresh) - a widget provided to the flutter scroll component drop-down refresh and pull up load.support android and ios.

- ![](https://img.shields.io/github/stars/ponnamkarthik/FlutterToast?style=social) [FlutterToast](https://github.com/ponnamkarthik/FlutterToast) - this toast library supports two kinds of toast messages one which requires BuildContext other with No BuildContext(Powered by platform channel!). Supported Platforms: Android, iOS, Web (Uses Toastify-JS)

- ![](https://img.shields.io/github/stars/aagarwal1012/Liquid-Pull-To-Refresh?style=social) [Liquid-Pull-To-Refresh](https://github.com/aagarwal1012/Liquid-Pull-To-Refresh) - A beautiful and custom refresh indicator for flutter highly inspired from [Ramotion Pull Down](https://dribbble.com/shots/1797373-Pull-Down-To-Refresh) to Refresh. Try out our live [example app](https://liquid-pull-to-refresh.web.app/#/).

- ![](https://img.shields.io/github/stars/MMMzq/bot_toast?style=social) [💗 bot_toast](https://github.com/MMMzq/bot_toast) - A really easy to use flutter toast library!
  - In the true sense of Toast, you can call it whenever you need it, without any restrictions!
  - Feature-rich, support for displaying notifications, text, loading, attachments, etc. Toast
  - Support for popping up various custom Toasts, or you can pop up any Widget as long as it meets the requirements of the flutter code.
  - API is simple and easy to use
  - Pure flutter implementation
- ![](https://img.shields.io/github/stars/OpenFlutter/flutter_oktoast?style=social) [flutter_oktoast](https://github.com/OpenFlutter/flutter_oktoast) - A pure dart toast Library. You can completely customize the style of toast.
- ![](https://img.shields.io/github/stars/appdev/FlutterToast?style=social) [FlutterToast](https://github.com/appdev/FlutterToast)
- ![](https://img.shields.io/github/stars/bytedance/pull_to_refresh?style=social) [bytedance pull_to_refresh](https://github.com/bytedance/pull_to_refresh) - A widget that provided to pull-up load and pull-down refresh with Flutter.

- ![](https://img.shields.io/github/stars/surfstudio/flutter-push-notification?style=social) [flutter-push-notification](https://github.com/surfstudio/flutter-push-notification)

- ![](https://img.shields.io/github/stars/surfstudio/flutter-swipe-refresh?style=social) [surfstudio/flutter-swipe-refresh](https://github.com/surfstudio/flutter-swipe-refresh) - Widget for refresh by swipe.

### Dialog & Alert

- ![](https://img.shields.io/github/stars/xsahil03x/giffy_dialog?style=social) [giffy_dialog](https://github.com/xsahil03x/giffy_dialog) - A beautiful and custom alert dialog for flutter highly inspired from [FancyAlertDialog-Android](https://github.com/Shashank02051997/FancyGifDialog-Android). The source code is 100% Dart, and everything resides in the /lib folder.

- ![](https://img.shields.io/github/stars/YYFlutter/flutter-custom-dialog?style=social)  [flutter-custom-dialog](https://github.com/YYFlutter/flutter-custom-dialog) - Global dialog function encapsulation, with a semantic way to fill the content inside the dialog, the current function provided
  1. Support for a few semantic component methods to populate the component content inside dialog
  2. Support for customizing semantic components for developers to freely populate component content inside dialog
  3. Support setting dialog background color, foreground color, position, animation, click the external disappear and other functions, see the details below
  4. Support no Context call dialog, see below

- ![](https://img.shields.io/github/stars/fluttercandies/flutter_smart_dialog?style=social) [flutter_smart_dialog](https://github.com/fluttercandies/flutter_smart_dialog) - An elegant Flutter Dialog solution.

- ![](https://img.shields.io/github/stars/RatelHub/rflutter_alert?style=social) [rflutter_alert](https://github.com/RatelHub/rflutter_alert) - RFlutter Alert is super customizable and easy-to-use alert/popup dialogs for Flutter. You may create reusable alert styles or add buttons as much as you want with ease.

### Popup & Sheet

- ![](https://img.shields.io/github/stars/minikin/popover?style=social) [minikin/popover/](https://github.com/minikin/popover/) - A popover is a transient view that appears above other content onscreen when you tap a control or in an area. Typically, a popover includes an arrow pointing to the location from which it emerged. Popovers can be nonmodal or modal. A nonmodal popover is dismissed by tapping another part of the screen or a button on the popover. A modal popover is dismissed by tapping a Cancel or other button on the popover.

- ![](https://img.shields.io/github/stars/surfstudio/flutter-bottom-sheet?style=social) [surfstudio/flutter-bottom-sheet](https://github.com/surfstudio/flutter-bottom-sheet) - Custom bottom sheet widget that can be resized in response to drag gestures and then scrolled.

### Picker

- ![](https://img.shields.io/github/stars/fluttercandies/flutter_wechat_assets_picker?style=social) [wechat_assets_picker](https://github.com/fluttercandies/flutter_wechat_assets_picker) - An assets picker which based on the WeChat's UI, using photo_manager for asset implementation, extended_image for image preview, and provider to help control the state of the picker.

  To take a photo or a video for assets, please check the detailed usage in the example, and head over to [wechat_camera_picker](https://pub.dev/packages/wechat_camera_picker).

  All UI designs are based on WeChat 8.x, and it will be updated following the WeChat update in anytime.
- ![](https://img.shields.io/github/stars/yangyxd/flutter_picker?style=social) [flutter_picker](https://github.com/yangyxd/flutter_picker) - Flutter plugin picker. Include NumberPicker, DateTimePicker, ArrayPicker, and default linkage Picker. Provide flexible parameters to meet various needs. At the same time, you can extend more functions through custom adapters.

- ![](https://img.shields.io/github/stars/mchome/flutter_colorpicker?style=social) [flutter_colorpicker](https://github.com/mchome/flutter_colorpicker) - HSV(HSB)/HSL/RGB/Material color picker inspired by all the good design for your amazing flutter apps.
Adorable color pickers out of the box with highly customized widgets to all developers' needs. [Web Example](https://mchome.github.io/flutter_colorpicker)

### Bar

- ![](https://img.shields.io/github/stars/hacktons/convex_bottom_bar?style=social) [convex_bottom_bar](https://github.com/hacktons/convex_bottom_bar) - The official BottomAppBar can only display a notch FAB with app bar, sometimes we need a convex FAB. This ConvexAppBar is inspired by BottomAppBar and NotchShape's implementation. Online example can be found at <https://appbar.codemagic.app>. convex_bottom_bar is now a **Flutter Favorite package**!

### Chart

- ![](https://img.shields.io/github/stars/imaNNeoFighT/fl_chart?style=social) [fl_chart](https://github.com/imaNNeoFighT/fl_chart) - A powerful Flutter chart library, currently supporting Line Chart, Bar Chart, Pie Chart and Scatter Chart.

- ![](https://img.shields.io/github/stars/google/charts?style=social) [](https://github.com/google/charts) - Charts is a general charting library, currently enabled for the Flutter mobile UI framework.

  See [the online gallery](https://google.github.io/charts/flutter/gallery.html) for supported chart types and examples of how to custom components of the chart.

  Note: This is not an official Google product.

### Switch

- ![](https://img.shields.io/github/stars/boringdeveloper/FlutterSwitch?style=social) [FlutterSwitch](https://github.com/boringdeveloper/FlutterSwitch) - An easy to implement custom switch created for Flutter. Give it a custom height and width, border for the switch and toggle, border radius, colors, toggle size, a choice to display an 'On' and 'Off' text and able to add an icon inside the toggle.

### Swipe & Slide & Indicator

- ![](https://img.shields.io/github/stars/best-flutter/flutter_swiper?style=social) [flutter_swiper](https://github.com/best-flutter/flutter_swiper) - The best swiper for flutter , with multiple layouts, infinite loop. Compatible with Android & iOS.
- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/letsar/flutter_slidable?style=social)  [flutter_slidable](https://github.com/letsar/flutter_slidable) - A Flutter implementation of slidable list item with directional slide actions that can be dismissed.
- ![](https://img.shields.io/github/stars/akshathjain/sliding_up_panel?style=social) [sliding_up_panel](https://github.com/akshathjain/sliding_up_panel) - A draggable Flutter widget that makes implementing a SlidingUpPanel much easier! Based on the Material Design bottom sheet component, this widget works on both Android & iOS. (like DouBan)
- ![](https://img.shields.io/github/stars/Milad-Akarie/smooth_page_indicator?style=social) [smooth_page_indicator](https://github.com/Milad-Akarie/smooth_page_indicator) - Customizable animated page indicator with a set of built-in effects.

### Badges & Labels & Tags

- ![](https://img.shields.io/github/stars/yako-dev/flutter_badges?style=social) [flutter_badges](https://github.com/yako-dev/flutter_badges)
   <details><summary>Showcase</summary>
    <img src="https://github.com/yako-dev/flutter_badges/blob/docs/readme/images/showcase.gif?raw=true" width="900" alt="" />
  </details>
- ![](https://img.shields.io/github/stars/Dn-a/flutter_tags?style=social) [flutter_tags](https://github.com/Dn-a/flutter_tags) - Create beautiful tags quickly and easily.

### Datetime

- ![](https://img.shields.io/github/stars/Realank/flutter_datetime_picker?style=social) [Flutter Datetime Picker](https://github.com/Realank/flutter_datetime_picker) - A flutter date time picker inspired by flutter-cupertino-date-picker

### Calendars

- ![](https://img.shields.io/github/stars/aleksanderwozniak/table_calendar?style=social) [table_calendar](https://github.com/aleksanderwozniak/table_calendar) - Highly customizable, feature-packed Flutter Calendar with gestures, animations and multiple formats

### Clippers

- ![](https://img.shields.io/github/stars/lohanidamodar/flutter_custom_clippers?style=social) [flutter_custom_clippers](https://github.com/lohanidamodar/flutter_custom_clippers) - Flutter package that provides you custom clippers to help you achieve various custom shapes.

### Images

- ![](https://img.shields.io/github/stars/Baseflow/flutter_cached_network_image?style=social)  [flutter_cached_network_image](https://github.com/Baseflow/flutter_cached_network_image) - A flutter library to show images from the internet and keep them in the cache directory.

- ![](https://img.shields.io/github/stars/fluttercandies/extended_image?style=social) [extended_image](https://github.com/fluttercandies/extended_image) - A powerful official extension library of image, which support placeholder(loading)/ failed state, cache network, zoom pan image, photo view, slide out page, editor(crop,rotate,flip), paint custom etc.

- ![](https://img.shields.io/github/stars/dnfield/flutter_svg?style=social) [flutter_svg](https://github.com/dnfield/flutter_svg) - Draw SVG (and some Android VectorDrawable (XML)) files on a Flutter Widget.

- ![](https://img.shields.io/github/stars/hnvn/flutter_image_cropper?style=social) [Image Cropper](https://github.com/hnvn/flutter_image_cropper) - A Flutter plugin for Android and iOS supports cropping images. This plugin is based on two different native libraries so it comes with different UI between these platforms.

- ![](https://img.shields.io/github/stars/xsahil03x/before_after?style=social) [before_after](https://github.com/xsahil03x/before_after) - A flutter package which makes it easier to display the differences between two images.

- ![](https://img.shields.io/github/stars/fluttercandies/flutter_image_compress?style=social) [](https://github.com/fluttercandies/flutter_image_compress) - Compresses image as native plugin (Obj-C/Kotlin). This library works on Android and iOS.

- ![](https://img.shields.io/github/stars/alibaba/power_image?style=social) [alibaba/power_image](https://github.com/alibaba/power_image) - A powerful plugin that fully uses the native image library's ability to display images on the flutter side.

### List & Grid

- ![](https://img.shields.io/github/stars/letsar/flutter_staggered_grid_view?style=social) [flutter_staggered_grid_view](https://github.com/letsar/flutter_staggered_grid_view) - Provides a collection of Flutter grids layouts. This package contains various grid layouts. In the following section, you'll discover each one of them. The explanation of the layout will always considered a top-to-bottom and left-to-right directions to simplify the description. However it is possible to change these directions in the code.

- ![](https://img.shields.io/github/stars/The-ring-io/flutter_staggered_animations?style=social) [flutter_staggered_animation](https://github.com/The-ring-io/flutter_staggered_animations) - Easily add staggered animations to your ListView, GridView, Column and Row children as shown in Material Design guidelines
  ![](https://github.com/mobiten/flutter_staggered_animations/raw/master/assets/card_grid.gif?raw=true)

- [flutterchina/azlistview](https://github.com/flutterchina/azlistview) - A Flutter sticky headers & index ListView. Based on scrollable_positioned_list.
AzListView, SuspensionView, IndexBar.
Easy creation of city list or contact list interfaces.
  - List items can be grouped A-Z.
  - Sticky headers with floating option.
  - Support custom header.
  - Support index linkage.
  - IndexBar supports custom styles.
  - IndexBar supports local images.
  - Allows scrolling to a specific item in the list.

- ![](https://img.shields.io/github/stars/mobiten/flutter_staggered_animations?style=social) [flutter_staggered_animations](https://github.com/mobiten/flutter_staggered_animations) - Easily add staggered animations to your ListView, GridView, Column and Row children as shown in [Material Design guidelines](https://material.io/design/motion/customization.html#sequencing)

- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_sticky_headers?style=social) [flutter_sticky_headers](https://github.com/fluttercommunity/flutter_sticky_headers) - Lets you place headers on scrollable content that will stick to the top of the container whilst the content is scrolled.

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/EdsonBueno/infinite_scroll_pagination?style=social) [infinite_scroll_pagination](https://github.com/EdsonBueno/infinite_scroll_pagination) - Unopinionated, extensible and highly customizable package to help you lazily load and display small chunks of items as the user scrolls down the screen – known as infinite scrolling pagination, endless scrolling pagination, auto-pagination, lazy loading pagination, progressive loading pagination, etc.

  Designed to feel like part of the Flutter framework.

- ![](https://img.shields.io/github/stars/Kavantix/sliver_tools?style=social) [sliver_tools](https://github.com/Kavantix/sliver_tools) - A set of useful sliver tools that are missing from the flutter framework. Here is a taste what you can make using this packages.

  ![](https://raw.githubusercontent.com/Kavantix/sliver_tools/master/gifs/demo2.gif)

- ![](https://img.shields.io/github/stars/fluttercandies/waterfall_flow?style=social) [fluttercandies/waterfall_flow](https://github.com/fluttercandies/waterfall_flow) - A Flutter grid view easy to build waterfall flow layout quickly.

- ![](https://img.shields.io/github/stars/fluttercandies/loading_more_list?style=social) [loading_more_list](https://github.com/fluttercandies/loading_more_list) - A loading more list which supports ListView,GridView,WaterfallFlow and Slivers.
  
- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_infinite_listview?style=social) [flutter_infinite_listview](https://github.com/fluttercommunity/flutter_infinite_listview) - ListView with items that can be scrolled infinitely in both directions.

- ![](https://img.shields.io/github/stars/marcglasberg/indexed_list_view?style=social) [indexed_list_view](https://github.com/marcglasberg/indexed_list_view) - Similar to a ListView, but lets you programmatically jump to any item, by index. The index jump happens instantly, no matter if you have millions of items.

  Limitation: The list is always infinite both to positive and negative indexes. In other words, it can be scrolled indefinitely both to the top and to the bottom.

- ![](https://img.shields.io/github/stars/MayLau-CbL/flutter_horizontal_data_table?style=social)  [flutter_horizontal_data_table](https://github.com/MayLau-CbL/flutter_horizontal_data_table) - A Flutter Widget that create a horizontal table with fixed column on left hand side.

- ![](https://img.shields.io/github/stars/LinXunFeng/flutter_scrollview_observer?style=social) [LinXunFeng/flutter_scrollview_observer](https://github.com/LinXunFeng/flutter_scrollview_observer) - A widget for observing data related to the child widgets being displayed in a ScrollView.
  - Observing child widgets those are being displayed in ScrollView.
  - Support for scrolling to a specific item in ScrollView.
  - Quickly implement the chat session page effect.
  - Support for keeping IM message position when inserting or updating messages, avoiding jitter.

### Input & Form

- ![](https://img.shields.io/github/stars/danvick/flutter_form_builder?style=social) [Flutter Form Builder](https://github.com/danvick/flutter_form_builder) - Flutter Form Builder provides an easy way of working with forms in Flutter by removing the boilerplate needed to build a form, validate fields, react to changes, and collect final user input.

- ![](https://img.shields.io/github/stars/AbdulRahmanAlHamali/flutter_typeahead?style=social)  [flutter_typeahead](https://github.com/AbdulRahmanAlHamali/flutter_typeahead) - A TypeAhead (autocomplete) widget for Flutter, where you can show suggestions to users as they type.

- ![](https://img.shields.io/github/stars/Tkko/Flutter_Pinput?style=social)  [Pinput](https://github.com/Tkko/Flutter_Pinput) is a package that provides an easy-to-use and customizable Pin code input field. It offers several features such as animated decoration switching, form validation, SMS autofill, custom cursor, copying from clipboard, and more. It also provides beautiful examples that you can choose from.

- ![](https://img.shields.io/github/stars/TinoGuo/pin_input_text_field?style=social)  [pin_input_text_field](https://github.com/TinoGuo/pin_input_text_field) - PinInputTextField is a TextField widget to help display different style pin. It supports all the platforms flutter supports.

### Select

- ![](https://img.shields.io/github/stars/LanarsInc/direct-select-flutter?style=social) [https://github.com/LanarsInc/direct-select-flutter](https://github.com/LanarsInc/direct-select-flutter) - DirectSelect is a selection widget with an ethereal, full-screen modal popup displaying the available choices when the widget is interact with. Inspired by dribble shot.

### Steps & Timelines

- ![](https://img.shields.io/github/stars/chulwoo-park/timelines?style=social) [timelines](https://github.com/chulwoo-park/timelines/) - A powerful & easy to use timeline package for Flutter! (This package is an early stage. Not enough testing has been done to guarantee stability. Some APIs may change. 2021-12-29)

### Progress

- ![](https://img.shields.io/github/stars/diegoveloper/flutter_percent_indicator?style=social) [flutter_percent_indicator](https://github.com/diegoveloper/flutter_percent_indicator) - Circular and Linear percent indicators:
  - Circle percent indicator
  - Linear percent indicator
  - Toggle animation
  - Custom duration of the animation
  - Progress based on a percentage value
  - Progress and background color
  - Custom size
  - Left , right or center child for Linear percent indicator
  - Top, bottom or center child for Circular percent indicator
  - Progress Color using gradients

### Menu

- ![](https://img.shields.io/github/stars/medyas/flutter_zoom_drawer?style=social) [flutter_zoom_drawer](https://github.com/medyas/flutter_zoom_drawer) - A Flutter package with custom implementation of the Side Menu (Drawer)

### Editor

- ![](https://img.shields.io/github/stars/singerdmx/flutter-quill?style=social) [flutter-quill](https://github.com/singerdmx/flutter-quill) - FlutterQuill is a rich text editor and a Quill component for Flutter.

  This library is a WYSIWYG editor built for the modern mobile platform, with web compatibility under development. Check out our Youtube Playlist to take a detailed walkthrough of the code base. You can join our Slack Group for discussion.

  Demo App: <https://bulletjournal.us/home/index.html>

- ![](https://img.shields.io/github/stars/AppFlowy-IO/appflowy-editor?style=social)  [appflowy-editor](https://github.com/AppFlowy-IO/appflowy-editor) - A highly customizable rich-text editor for Flutter

### Effect

- ![](https://img.shields.io/github/stars/2d-inc/Flare-Flutter?style=social) [Flare-Flutter](https://github.com/2d-inc/Flare-Flutter) - Rive 1 (previously Flare) offers powerful realtime vector design and animation for app and game designers alike. The primary goal of Flare is to allow designers to work directly with assets that run in their final product, eliminating the need to redo that work in code.

- ![](https://img.shields.io/github/stars/glorylab/wave?style=social)  [Wave](https://github.com/glorylab/wave) - A Flutter package for displaying waves.

- ![](https://img.shields.io/github/stars/felixblaschke/simple_animations?style=social) 💗[simple_animations](https://github.com/felixblaschke/simple_animations) - Simple Animations is a powerful package to create beautiful custom animations in no time.
  - 💪 fully tested
  - 📝 well documented
  - 💼 enterprise-ready

  Highlights

  - Easily create custom animations in stateless widgets
  - Animate multiple properties at once
  - Create staggered animations within seconds
  - Simplified working with AnimationController instances
  - Debug animations

- ![](https://img.shields.io/github/stars/xvrh/lottie-flutter?style=social)  [Lottie for Flutter](https://github.com/xvrh/lottie-flutter) - Lottie is a mobile library for Android and iOS that parses Adobe After Effects animations exported as json with Bodymovin and renders them natively on mobile!

  This repository is an unofficial conversion of the Lottie-android library in pure Dart.

  It works on Android, iOS, macOS, linux, windows and web.

- ![](https://img.shields.io/github/stars/i-protoss/wave?style=social) [wave](https://github.com/i-protoss/wave) - Widget for displaying waves with custom color, duration, floating and blur effects.

- ![](https://img.shields.io/github/stars/YYFlutter/flutter-animation-set?style=social) [flutter-animation-set](https://github.com/YYFlutter/flutter-animation-set) - Simplified Flutter stagger animation.To drive the Flutter stagger animation through a timeline in the form of an animation configuration.You can

  1. Uses the existing Animation Widget of Flutter Animation Set
  2. Use Flutter Animation Set to create a new Animation Widget
  3. Contribute your Flutter Animation Set Widget
  4. Watch All of the Curves of Flutter in example

- ![](https://img.shields.io/github/stars/letsar/local_hero?style=social) [local_hero](https://github.com/letsar/local_hero) - A widget which implicitly launches a hero animation when its position changed within the same route.

- ![](https://img.shields.io/github/stars/canopas/animated-visibility?style=social) [animated-visibility](https://github.com/canopas/animated-visibility) - Animate appearance and disappearance using pre-built effects with the AnimatedVisibility.

## Plugins

- ![](https://img.shields.io/github/stars/flutter/plugins?style=social)  OFFICIAL! [Flutter plugins](https://github.com/flutter/plugins) - This repo is a companion repo to the main [flutter
repo](https://github.com/flutter/flutter). It contains the source code for
Flutter first-party plugins (i.e., plugins developed by the core Flutter team).
Check the `packages` directory for all plugins.

  These are the available plugins in this repository.

| Plugin | Pub | Points | Popularity | Likes |
|--------|-----|--------|------------|-------|
| [camera](./packages/camera/) | [![pub package](https://img.shields.io/pub/v/camera.svg)](https://pub.dev/packages/camera) | [![pub points](https://badges.bar/camera/pub%20points)](https://pub.dev/packages/camera/score) | [![popularity](https://badges.bar/camera/popularity)](https://pub.dev/packages/camera/score) | [![likes](https://badges.bar/camera/likes)](https://pub.dev/packages/camera/score) |
| [espresso](./packages/espresso/) | [![pub package](https://img.shields.io/pub/v/espresso.svg)](https://pub.dev/packages/espresso) | [![pub points](https://badges.bar/espresso/pub%20points)](https://pub.dev/packages/espresso/score) | [![popularity](https://badges.bar/espresso/popularity)](https://pub.dev/packages/espresso/score) | [![likes](https://badges.bar/espresso/likes)](https://pub.dev/packages/espresso/score) |
| [file_selector](./packages/file_selector/) | [![pub package](https://img.shields.io/pub/v/file_selector.svg)](https://pub.dev/packages/file_selector) | [![pub points](https://badges.bar/file_selector/pub%20points)](https://pub.dev/packages/file_selector/score) | [![popularity](https://badges.bar/file_selector/popularity)](https://pub.dev/packages/file_selector/score) | [![likes](https://badges.bar/file_selector/likes)](https://pub.dev/packages/file_selector/score) |
| [flutter_plugin_android_lifecycle](./packages/flutter_plugin_android_lifecycle/) | [![pub package](https://img.shields.io/pub/v/flutter_plugin_android_lifecycle.svg)](https://pub.dev/packages/flutter_plugin_android_lifecycle) | [![pub points](https://badges.bar/flutter_plugin_android_lifecycle/pub%20points)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) | [![popularity](https://badges.bar/flutter_plugin_android_lifecycle/popularity)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) | [![likes](https://badges.bar/flutter_plugin_android_lifecycle/likes)](https://pub.dev/packages/flutter_plugin_android_lifecycle/score) |
| [google_maps_flutter](./packages/google_maps_flutter) | [![pub package](https://img.shields.io/pub/v/google_maps_flutter.svg)](https://pub.dev/packages/google_maps_flutter) | [![pub points](https://badges.bar/google_maps_flutter/pub%20points)](https://pub.dev/packages/google_maps_flutter/score) | [![popularity](https://badges.bar/google_maps_flutter/popularity)](https://pub.dev/packages/google_maps_flutter/score) | [![likes](https://badges.bar/google_maps_flutter/likes)](https://pub.dev/packages/google_maps_flutter/score) |
| [google_sign_in](./packages/google_sign_in/) | [![pub package](https://img.shields.io/pub/v/google_sign_in.svg)](https://pub.dev/packages/google_sign_in) | [![pub points](https://badges.bar/google_sign_in/pub%20points)](https://pub.dev/packages/google_sign_in/score) | [![popularity](https://badges.bar/google_sign_in/popularity)](https://pub.dev/packages/google_sign_in/score) | [![likes](https://badges.bar/google_sign_in/likes)](https://pub.dev/packages/google_sign_in/score) |
| [image_picker](./packages/image_picker/) | [![pub package](https://img.shields.io/pub/v/image_picker.svg)](https://pub.dev/packages/image_picker) | [![pub points](https://badges.bar/image_picker/pub%20points)](https://pub.dev/packages/image_picker/score) | [![popularity](https://badges.bar/image_picker/popularity)](https://pub.dev/packages/image_picker/score) | [![likes](https://badges.bar/image_picker/likes)](https://pub.dev/packages/image_picker/score) |
| [in_app_purchase](./packages/in_app_purchase/) | [![pub package](https://img.shields.io/pub/v/in_app_purchase.svg)](https://pub.dev/packages/in_app_purchase) | [![pub points](https://badges.bar/in_app_purchase/pub%20points)](https://pub.dev/packages/in_app_purchase/score) | [![popularity](https://badges.bar/in_app_purchase/popularity)](https://pub.dev/packages/in_app_purchase/score) | [![likes](https://badges.bar/in_app_purchase/likes)](https://pub.dev/packages/in_app_purchase/score) |
| [ios_platform_images](./packages/ios_platform_images/) | [![pub package](https://img.shields.io/pub/v/ios_platform_images.svg)](https://pub.dev/packages/ios_platform_images) | [![pub points](https://badges.bar/ios_platform_images/pub%20points)](https://pub.dev/packages/ios_platform_images/score) | [![popularity](https://badges.bar/ios_platform_images/popularity)](https://pub.dev/packages/ios_platform_images/score) | [![likes](https://badges.bar/ios_platform_images/likes)](https://pub.dev/packages/ios_platform_images/score) |
| [local_auth](./packages/local_auth/) | [![pub package](https://img.shields.io/pub/v/local_auth.svg)](https://pub.dev/packages/local_auth) | [![pub points](https://badges.bar/local_auth/pub%20points)](https://pub.dev/packages/local_auth/score) | [![popularity](https://badges.bar/local_auth/popularity)](https://pub.dev/packages/local_auth/score) | [![likes](https://badges.bar/local_auth/likes)](https://pub.dev/packages/local_auth/score) |
| [path_provider](./packages/path_provider/) | [![pub package](https://img.shields.io/pub/v/path_provider.svg)](https://pub.dev/packages/path_provider) | [![pub points](https://badges.bar/path_provider/pub%20points)](https://pub.dev/packages/path_provider/score) | [![popularity](https://badges.bar/path_provider/popularity)](https://pub.dev/packages/path_provider/score) | [![likes](https://badges.bar/path_provider/likes)](https://pub.dev/packages/path_provider/score) |
| [plugin_platform_interface](./packages/plugin_platform_interface/) | [![pub package](https://img.shields.io/pub/v/plugin_platform_interface.svg)](https://pub.dev/packages/plugin_platform_interface) | [![pub points](https://badges.bar/plugin_platform_interface/pub%20points)](https://pub.dev/packages/plugin_platform_interface/score) | [![popularity](https://badges.bar/plugin_platform_interface/popularity)](https://pub.dev/packages/plugin_platform_interface/score) | [![likes](https://badges.bar/plugin_platform_interface/likes)](https://pub.dev/packages/plugin_platform_interface/score) |
| [quick_actions](./packages/quick_actions/) | [![pub package](https://img.shields.io/pub/v/quick_actions.svg)](https://pub.dev/packages/quick_actions) | [![pub points](https://badges.bar/quick_actions/pub%20points)](https://pub.dev/packages/quick_actions/score) | [![popularity](https://badges.bar/quick_actions/popularity)](https://pub.dev/packages/quick_actions/score) | [![likes](https://badges.bar/quick_actions/likes)](https://pub.dev/packages/quick_actions/score) |
| [shared_preferences](./packages/shared_preferences/) | [![pub package](https://img.shields.io/pub/v/shared_preferences.svg)](https://pub.dev/packages/shared_preferences) | [![pub points](https://badges.bar/shared_preferences/pub%20points)](https://pub.dev/packages/shared_preferences/score) | [![popularity](https://badges.bar/shared_preferences/popularity)](https://pub.dev/packages/shared_preferences/score) | [![likes](https://badges.bar/shared_preferences/likes)](https://pub.dev/packages/shared_preferences/score) |
| [url_launcher](./packages/url_launcher/) | [![pub package](https://img.shields.io/pub/v/url_launcher.svg)](https://pub.dev/packages/url_launcher) | [![pub points](https://badges.bar/url_launcher/pub%20points)](https://pub.dev/packages/url_launcher/score) | [![popularity](https://badges.bar/url_launcher/popularity)](https://pub.dev/packages/url_launcher/score) | [![likes](https://badges.bar/url_launcher/likes)](https://pub.dev/packages/url_launcher/score) |
| [video_player](./packages/video_player/) | [![pub package](https://img.shields.io/pub/v/video_player.svg)](https://pub.dev/packages/video_player) | [![pub points](https://badges.bar/video_player/pub%20points)](https://pub.dev/packages/video_player/score) | [![popularity](https://badges.bar/video_player/popularity)](https://pub.dev/packages/video_player/score) | [![likes](https://badges.bar/video_player/likes)](https://pub.dev/packages/video_player/score) |
| [webview_flutter](./packages/webview_flutter/) | [![pub package](https://img.shields.io/pub/v/webview_flutter.svg)](https://pub.dev/packages/webview_flutter) | [![pub points](https://badges.bar/webview_flutter/pub%20points)](https://pub.dev/packages/webview_flutter/score) | [![popularity](https://badges.bar/webview_flutter/popularity)](https://pub.dev/packages/webview_flutter/score) | [![likes](https://badges.bar/webview_flutter/likes)](https://pub.dev/packages/webview_flutter/score) |

- ![](https://img.shields.io/github/stars/FirebaseExtended/flutterfire?style=social) [FlutterFire](https://github.com/FirebaseExtended/flutterfire) - FlutterFire is a set of Flutter plugins that enable Flutter apps to use Firebase services. You can follow an example that shows how to use these plugins in the Firebase for Flutter codelab.

  Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase. Flutter is used by developers and organizations around the world, and is free and open source.
- ![](https://img.shields.io/github/stars/OpenFlutter/flutter_screenutil?style=social) [flutter_screenutil](https://github.com/OpenFlutter/flutter_screenutil) - A flutter plugin for adapting screen and font size.Let your UI display a reasonable layout on different screen sizes!

- ![](https://img.shields.io/github/stars/jonbhanson/flutter_native_splash?style=social) [flutter_native_splash](https://github.com/jonbhanson/flutter_native_splash) - When your app is opened, there is a brief time while the native app loads Flutter. By default, during this time, the native app displays a white splash screen. This package automatically generates iOS, Android, and Web-native code for customizing this native splash screen background color and splash image. Supports dark mode, full screen, and platform-specific options.

- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_downloader?style=social) [flutter_downloader](https://github.com/fluttercommunity/flutter_downloader) - A plugin for creating and managing download tasks. Supports iOS and Android.

  This plugin is based on WorkManager in Android and NSURLSessionDownloadTask in iOS to run download task in background mode.

- ![](https://img.shields.io/github/stars/diegoveloper/flutter_keyboard_actions?style=social) [flutter_keyboard_actions](https://github.com/diegoveloper/flutter_keyboard_actions/) - Add features to the Android / iOS keyboard in a simple way.

  Because the keyboard that Android / iOS offers us specifically when we are in numeric mode, does not bring the button to hide the keyboard. This causes a lot of inconvenience for users, so this package allows adding functionality to the existing keyboard.

- ![](https://img.shields.io/github/stars/creativecreatorormaybenot/wakelock?style=social) [Wakelock](https://github.com/creativecreatorormaybenot/wakelock) - Wakelock is Flutter plugin that allows you to keep the device screen awake, i.e. prevent the screen from sleeping.
- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_uploader?style=social) [flutter_uploader](https://github.com/fluttercommunity/flutter_uploader) - A plugin for creating and managing upload tasks. Supports iOS and Android.

  This plugin is based on WorkManager in Android and NSURLSessionUploadTask in iOS to run upload task in background mode.

  This plugin is inspired by flutter_downloader. Thanks to Hung Duy Ha & Flutter Community for great plugins and inspiration.

- [flutter-otp-autofill](https://github.com/surfstudio/flutter-otp-autofill) - This plugin uses [SMS User Consent](https://developers.google.com/identity/sms-retriever/user-consent/overview) API and [SMS Retriever API](https://developers.google.com/identity/sms-retriever/overview) on Android.

  You could use autofill from another input by using OTPStrategy. (e.g. from push-notification).

  For testing you could create TestStrategy.

- ![](https://img.shields.io/github/stars/BestBurning/platform_device_id?style=social) [platform_device_id](https://github.com/BestBurning/platform_device_id) -  Get device id from android、ios、windows、linux、mac、web

**Plugins FFI:**

- ![](https://img.shields.io/github/stars/fzyzcjy/flutter_rust_bridge?style=social) [flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) - High-level memory-safe binding generator for Flutter/Dart <-> Rust.

**Plugins productivity:**

- ![](https://img.shields.io/github/stars/dart-native/dart_native?style=social)  [Dart_Native](https://github.com/dart-native/dart_native) - Dart_Native operates as both a code generator tool and a bridge to communicate between Dart and native APIs.

  Replaces the low-performing Flutter channel with faster and more concise code

## Utils

- ![](https://img.shields.io/github/stars/Sub6Resources/flutter_html?style=social) [flutter_html](https://github.com/Sub6Resources/flutter_html) - A Flutter widget for rendering HTML and CSS as Flutter widgets.

- ![](https://img.shields.io/github/stars/google/quiver-dart?style=social) [google/quiver-dart](https://github.com/google/quiver-dart) - Quiver is a set of utility libraries for Dart that makes using many Dart libraries easier and more convenient, or adds additional functionality. [👉 API Doc](https://pub.dev/documentation/quiver/latest/)

- ![](https://img.shields.io/github/stars/dart-lang/intl?style=social)  [dart-lang/intl](https://github.com/dart-lang/intl) - Provides internationalization and localization facilities, including message translation, plurals and genders, date/number formatting and parsing, and bidirectional text.

- ![](https://img.shields.io/github/stars/ReinBentdal/styled_widget?style=social) 💗👍 [styled_widget](https://github.com/ReinBentdal/styled_widget) - Simplifying your widget tree structure by defining widgets using methods.

- ![](https://img.shields.io/github/stars/flutterchina/lpinyin?style=social) [lpinyin](https://github.com/flutterchina/lpinyin) - 汉字转拼音
- ❗️GOOGLE❗️ ![](https://img.shields.io/github/stars/google/reflectable.dart?style=social) [reflectable.dart](https://github.com/google/reflectable.dart) - This repository provides the Dart package reflectable along with a set of test cases, test_reflectable.

- ![](https://img.shields.io/github/stars/mmcc007/screenshots?style=social) [Screenshots](https://github.com/mmcc007/screenshots) - A screenshot image with overlaid status bar placed in a device frame. Screenshots is a standalone command line utility and package for capturing screenshot images for Flutter.

  Screenshots will start the required android emulators and iOS simulators (or find attached devices), run tests, process the captured screenshots, and drop them off to Fastlane for delivery to both stores.

  Screenshots is inspired by three tools from Fastlane:

  1. [Snapshots](https://docs.fastlane.tools/getting-started/ios/screenshots/)
  This is used to capture screenshots on iOS using iOS UI Tests.
  1. [Screengrab](https://docs.fastlane.tools/actions/screengrab/)
  This captures screenshots on android using Android Espresso tests.
  1. [FrameIt](https://docs.fastlane.tools/actions/frameit/)
  This is used to place captured iOS screenshots in a device frame.

  Since all three of these Fastlane tools do not work with Flutter, Screenshots combines key features of these Fastlane tools into one tool.
- ![](https://img.shields.io/github/stars/ganeshrvel/pub-rules?style=social)[Rules](https://github.com/ganeshrvel/pub-rules) - Powerful and feature-rich validation library for both Dart and Flutter.
  - Highly flexible
  - Easy to understand
  - Less boilerplate code
  - Custom error handling
  - Override individual errors
  - Flutter friendly
  - State management libraries friendly (Mobx example included)

- ![](https://img.shields.io/github/stars/surfstudio/flutter-surf-util?style=social) [flutter-surf-util](https://github.com/surfstudio/flutter-surf-util) - A library with set of common classes and utilities used in different modules:

  - Bitmask - A generic implementation of the Bitmask type.
  - Enum - Java-like enum.
  - DisableOverscroll - Prevent glowing when scrolling over the edge

**Dynamic**:

- ![](https://img.shields.io/github/stars/dengyin2000/dynamic_widget?style=social) [Flutter Dynamic Widget](https://github.com/dengyin2000/dynamic_widget) - A Backend-Driven UI toolkit, build your dynamic UI with json, and the json format is very similar with flutter widget code.
- ![](https://img.shields.io/github/stars/wuba/fair?style=social) [fair](https://github.com/wuba/fair) - Fair is a lightweight package for Flutter, which can be used to update widget tree and state dynamically. This package is still at an early stage.

  We create Fair so we can dispatch any pages changes to users as bundle(s), the way similar to React Native. With Flutter Fair integrated, you can publish your pages without waiting for the next release date of your App. Fair provides standard widget and some logic plugins, it can be used as a new dynamic page or as part of existing Flutter page.

  ![](https://github.com/wuba/fair/raw/main/fair/what-is-fair-en.png)

**Dart Extend**:

- ![](https://img.shields.io/github/stars/jogboms/time.dart?style=social) [time.dart](https://github.com/jogboms/time.dart)

  ```dart
  final Duration tenMinutes = 10.minutes;
  final Duration oneHourThirtyMinutes = 1.5.hours;
  final DateTime afterTenMinutes = DateTime.now() + 10.minutes;
  final Duration tenMinutesAndSome = 10.minutes + 15.seconds;
  final int tenMinutesInSeconds = 10.minutes.inSeconds;
  final DateTime tenMinutesFromNow = 10.minutes.fromNow;
  ```

- ![](https://img.shields.io/github/stars/Ephenodrom/Dart-Basic-Utils?style=social) [Dart-Basic-Utils](https://github.com/Ephenodrom/Dart-Basic-Utils) - A dart package for many helper methods fitting different situations. String, Domain, Email, Math, HTTP, DNS, Sort, Color, Date, Iterable, Crypto, ASN1, FunctionDefs, X509....

- ![](https://img.shields.io/github/stars/dart-lang/collection?style=social) [dart-lang/collection](https://github.com/dart-lang/collection)(**Dart Official**) - Contains utility functions and classes in the style of dart:collection to make working with collections easier. Includes Algorithms, Equality, Iterable Zip, Priority Queue, Wrappers...

- **DART OFFICIAL**![](https://img.shields.io/github/stars/dart-lang/stream_transform?style=social) [dart-lang/stream_transform](https://github.com/dart-lang/stream_transform) - Extension methods on Stream adding common transform operators.

**Lifecycle**

- ![](https://img.shields.io/github/stars/rrousselGit/flutter_hooks?style=social) [flutter_hooks](https://github.com/rrousselGit/flutter_hooks) - A Flutter implementation of React hooks: <https://medium.com/@dan_abramov/making-sense-of-react-hooks-fdbde8803889>.
Hooks are a new kind of object that manage the life-cycle of a Widget. They exist for one reason: increase the code-sharing between widgets by removing duplicates.

- ![](https://img.shields.io/github/stars/fluttercommunity/flutter_after_layout?style=social) [flutter_after_layout](https://github.com/fluttercommunity/flutter_after_layout) - Brings functionality to execute code after the first layout of a widget has been performed, i.e. after the first frame has been displayed.

**Screen**

- ![](https://img.shields.io/github/stars/xamantra/relative_scale?style=social)[relative_scale](https://github.com/xamantra/relative_scale) - RelativeScale is a simple custom sizing system for flutter widgets to achieve the same physical sizes across different devices.

**Code generator**

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> [pigeon](https://github.com/flutter/packages/tree/master/packages/pigeon) - Pigeon is a code generator tool to make communication between Flutter and the host platform type-safe, easier and faster.

- ![](https://img.shields.io/github/stars/flutter/packages?style=social) [Flutter Official packages pigeon](https://github.com/flutter/packages/tree/master/packages/pigeon) - Pigeon is a code generator tool to make communication between Flutter and the host platform type-safe, easier and faster.

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/rrousselGit/freezed?style=social) [freezed](https://github.com/rrousselGit/freezed) - another code generator for unions/pattern-matching/copy. Using Freezed, we will get:

  - a simple and concise syntax for defining models, where we don't need to define both a constructor and a property.
Instead, we only need to define the constructor, removing unnecessary duplication.

  - a copyWith method, for cloning objects with different values.
Note: As opposed to many alternatives, when using Freezed, that copyWith method correctly supports assigning null to a value.

  - union-types/pattern matching, for making impossible states impossible. See also unions/sealed-classes.

  - an automatic serialization/deserialization of your objects (including union types).

  - a default ==/toString implementation which respectively compares/shows all properties of the object.

  See [the example](https://github.com/rrousselGit/freezed/blob/master/packages/freezed/example/lib/main.dart) for a preview on what's available

- ![](https://img.shields.io/github/stars/netglade/auto_mappr?style=social) [auto_mappr](https://github.com/netglade/auto_mappr) - AutoMappr is a code-generation package that helps with writing object-to-object mappings, so you don't have to write code by hand.

  - Mapping objects to other objects can be for sure done by hand. While it works, it's incredibly boring. Most of the time, object mapping can occur in places like mapping network DTOs from/to domain layer's models, domain layer's models from/to UI models, etc. In other words: if you care about code segregation and single responsibility, you do a lot of mappings. Tools like AutoMappr can help you with reducing boilerplate code and reduce the time you would spend on mapping objects or updating the mappings.
  
- ![](https://img.shields.io/github/stars/FlutterGen/flutter_gen?style=social) [json_to_dart](https://github.com/javiercbk/json_to_dart) - Given a JSON string, this library will generate all the necessary Dart classes to parse and generate JSON.

  This library is designed to generate Flutter friendly model classes following the [flutter's doc recommendation](https://flutter.io/json/#serializing-json-manually-using-dartconvert).

- ![](https://img.shields.io/github/stars/FlutterGen/flutter_gen?style=social) [flutter_gen](https://github.com/FlutterGen/flutter_gen) - The Flutter code generator for your assets, fonts, colors, … — Get rid of all String-based APIs.

  Inspired by [SwiftGen](https://github.com/SwiftGen/SwiftGen).

- <img width="24" alt="flutter_favorite_badge" src="https://user-images.githubusercontent.com/1112181/109502339-d11da080-7ad3-11eb-8324-e2aaba817f16.png"> ![](https://img.shields.io/github/stars/google/built_value.dart?style=social) [google/built_value](https://github.com/google/built_value.dart) - Built Value provides:

  - Immutable value types;
  - EnumClass, classes that behave like enums;
  - JSON serialization.
  - Immutable collections are from built_collection.

  See the API docs.

- ![](https://img.shields.io/github/stars/dart-lang/build?style=social) [Dart Official Build](https://github.com/dart-lang/build) - These packages provide libraries for generating, compiling and serving Dart code.
  - build: Defines the interfaces for creating a Builder which is a way of doing codegen that is compatible across build systems (pub, bazel, standalone runner).

    For packages doing code generation this should generally be the only package against which there is a public dependency. Packages may have a dev_dependency on one or more of the other packages.

  - build_config: Support for parsing build.yaml files. Used by build_runner.
  - build_modules: Support for discovering the sub-modules within packages and creating summaries of those modules. Used by build_web_compilers but should not be used directly by most users.
  - build_resolvers: An implementation of the Resolver interface to use the analyzer during build steps.
  - build_runner: Provides utilities to enact builds and a way to automatically run builds based on configuration.

    This package should generally be a dev_dependency as it is used to run standalone builds. The only exception would be wrapping the build and watch methods with some other package.
  - build_test: Stub implementations for classes in Build and some utilities for running instances of builds and checking their outputs.

    This package generally only be a dev_dependency as it introduces a dependency on package:test. The exception to that would be if you were creating another testing-only package that wraps this one.
  - build_web_compilers: Provides the dart2js and dartdevc support for your package. To use this package you should add it as a dev_dependency.

    If you are using the automated build scripts, your project will automatically start being compiled with dartdevc, and you can start developing with chrome without any configuration.

- ![](https://img.shields.io/github/stars/dart-lang/source_gen?style=social) [dart-lang/source_gen](https://github.com/dart-lang/source_gen) - source_gen provides utilities for automated source code generation for Dart:
  - A framework for writing Builders that consume and produce Dart code.
  - A convention for human and tool generated Dart code to coexist with clean separation, and for multiple code generators to integrate in the same project.

  Its main purpose is to expose a developer-friendly API on top of lower-level packages like the analyzer or build. You don't have to use source_gen in order to generate source code; we also expose a set of library APIs that might be useful in your generators.

**Internationalization**

- ![](https://img.shields.io/github/stars/aissat/easy_localization?style=social)  [easy_localization](https://github.com/aissat/easy_localization) - Easy and Fast internationalization for your Flutter Apps

  - 🚀 Easy translations for many languages
  - 🔌 Load translations as JSON, CSV, Yaml, Xml using Easy Localization Loader
  - 💾 React and persist to locale changes
  - ⚡ Supports plural, gender, nesting, RTL locales and more
  - ↩️ Fallback locale keys redirection
  - ⁉️ Error widget for missing translations
  - ❤️ Extension methods on Text and BuildContext
  - 💻 Code generation for localization files and keys.
  - 🛡️ Null safety
  - 🖨️ Customizable logger.
  
**Performance**

- ![](https://img.shields.io/github/stars/rmawatson/flutter_isolate?style=social) [flutter_isolate](https://github.com/rmawatson/flutter_isolate) - FlutterIsolate allows creation of an Isolate in flutter that is able to use flutter plugins. It creates the necessary platform specific bits (FlutterBackgroundView on android & FlutterEngine on iOS) to enable the platform channels to work inside an isolate.

## Games

- ![](https://img.shields.io/github/stars/flame-engine/flame?style=social) [flame](https://github.com/flame-engine/flame) - A minimalist Flutter game engine

## CI/CD

- ![](https://img.shields.io/github/stars/f3ath/cider?style=social) [Cider(CI for Dart. Efficient Release)](https://github.com/f3ath/cider) - A command-line utility to automate package maintenance. Manipulates the changelog and pubspec.yaml.

  This tool assumes that the changelog:
  - is called CHANGELOG.md
  - is sitting in the project root folder
  - strictly follows the Keep a Changelog v1.0.0 format
  - uses basic markdown (no HTML and complex formatting supported)

## Monitor

- ![](https://img.shields.io/github/stars/dart-lang/stack_trace?style=social)  [dart-lang/stack_trace](https://github.com/dart-lang/stack_trace) - This library provides the ability to parse, inspect, and manipulate stack traces produced by the underlying Dart implementation. It also provides functions to produce string representations of stack traces in a more readable format than the native StackTrace implementation.

  Traces can be parsed from native StackTraces using Trace.from, or captured using Trace.current. Native StackTraces can also be directly converted to human-readable strings using Trace.format.

## Tools

- ![](https://img.shields.io/github/stars/aloisdeniel/flutter_device_preview?style=social) [Device Preview](https://github.com/aloisdeniel/flutter_device_preview) - Approximate how your app looks and performs on another device.
- ![](https://img.shields.io/github/stars/rxlabz/panache?style=social) [panache](https://github.com/rxlabz/panache) - A Flutter Material Theme editor. Panache helps you to create beautiful Material themes for your Flutter applications. Customize widgets colors and shapes, and download your theme.dart file.
- [fvm](https://github.com/befovy/fvm/) - Flutter Version Management: A simple cli to manage Flutter SDK versions.
  - Configure Flutter SDK version per project or globally
  - Ability to install and cache multiple Flutter SDK Versions
  - Easily switch between Flutter channels & versions
- ![](https://img.shields.io/github/stars/filiph/linkcheck?style=social) [linkcheck](https://github.com/filiph/linkcheck) - Very fast link-checking.

**Lint & Format:**

- ![](https://img.shields.io/github/stars/passsy/dart-lint?style=social)  [dart-lint](https://github.com/passsy/dart-lint) - lint is a hand-picked, open-source, community-driven collection of lint rules for Dart and Flutter projects. The set of rules follows the Effective Dart: Style Guide.

  This package can be used as a replacement for package:lints or the discontinued package:pedantic for those who prefer stricter rules.

  lint tries to be strict but not annoying.
- ![](https://img.shields.io/github/stars/fluttercommunity/import_sorter?style=social) [import_sorter](https://github.com/fluttercommunity/import_sorter) - 🎯 Dart package to automatically organize your dart imports. Any dart project supported! Will sorts imports alphabetically and then group them in the following order:
  1. Dart imports
  2. Flutter imports
  3. Package imports
  4. Project imports

**Testing:**

- ![](https://img.shields.io/github/stars/Betterment/alchemist?style=social) [alchemist](https://github.com/Betterment/alchemist) - **A Flutter tool that makes golden testing easy.**
  Alchemist is a Flutter package that provides functions, extensions and documentation to support golden tests.

  Heavily inspired by Ebay Motor's golden_toolkit package, Alchemist attempts to make writing and running golden tests in Flutter easier.

- ![](https://img.shields.io/github/stars/dart-lang/coverage?style=social) DART OFFICIAL [coverage](https://github.com/dart-lang/coverage)- Coverage provides coverage data collection, manipulation, and formatting for Dart.

**Mock:**

- ![](https://img.shields.io/github/stars/felangel/mocktail?style=social)  [mocktail](https://github.com/felangel/mocktail) - This repository contains mocking libraries for Dart inspired by [mockito](https://pub.dev/packages/mockito).

**Pub server:**

- [unpub](https://github.com/bytedance/unpub) - Unpub is a self-hosted private Dart Pub server for Enterprise, with a simple web interface to search and view packages information.

  ![](https://raw.githubusercontent.com/bytedance/unpub/master/assets/screenshot.png)

- ![](https://img.shields.io/github/stars/dart-archive/pub_server?style=social) [pub_server](https://github.com/dart-archive/pub_server)

- ![](https://img.shields.io/github/stars/aloisdeniel/micropub?style=social)[micropub](https://github.com/aloisdeniel/micropub) - A minimalist private pub server for small teams.

**Debug**:

- ![](https://img.shields.io/github/stars/bytedance/flutter_ume?style=social) [flutter_ume](https://github.com/bytedance/flutter_ume) - UME is an in-app debug kits platform for Flutter apps(Widget Info, Widget Detail, Align Ruler, Color Picker, Color Sucker, Touch Indicator, Memory Info, Perf Overlay, CPU Info, Device Info, Show Code, Console, Dio Inspector).
- ![](https://img.shields.io/github/stars/leoafarias/fvm?style=social)  [fvm](https://github.com/leoafarias/fvm) - Flutter Version Management: A simple cli to manage Flutter SDK versions.
- ![](https://img.shields.io/github/stars/leisim/logger?style=social)[logger](https://github.com/leisim/logger) - Small, easy to use and extensible logger which prints beautiful logs. Inspired by logger for Android.

- ![](https://img.shields.io/github/stars/leanflutter/flutter_flipperkit?style=social) [flutter_flipperkit](https://github.com/leanflutter/flutter_flipperkit) - [Flipper](https://fbflipper.com/) (Extensible mobile app debugger) for flutter. [View document](https://flutter-widget.live/flutter_flipperkit)

**Git(Code Management)**:

- ![](https://img.shields.io/github/stars/pre-commit/pre-commit?style=social) [pre-commit](https://github.com/pre-commit/pre-commit/) - A framework for managing and maintaining multi-language pre-commit hooks.

**Doc**

- ![](https://img.shields.io/github/stars/glesica/dcdg.dart?style=social) [Dart Class Diagram Generator](https://github.com/glesica/dcdg.dart) - A small command line utility to generate a class (UML or similar) diagram from a Dart package.

**No|Low Code**

- ![](https://img.shields.io/github/stars/aloisdeniel/figma-to-flutter?style=social) [figma-to-flutter](https://github.com/aloisdeniel/figma-to-flutter)

## Service

- ![](https://img.shields.io/github/stars/OpenFlutter/fluwx?style=social) [fluwx](https://github.com/OpenFlutter/fluwx) - Fluwx is flutter plugin for WeChatSDK which allows developers to call
WeChatSDK native APIs.

- ![](https://img.shields.io/github/stars/dart-lang/usage?style=social) [usage](https://github.com/dart-lang/usage) - A wrapper around Google Analytics for command-line, web, and Flutter apps.

- [Instabug: Superior Mobile App Performance. Improved User Experience.](https://instabug.com/) - Our comprehensive platform empowers users to monitor, prioritize, and debug performance and stability issues throughout the entire mobile app development lifecycle.

- [RevenueCat: In-App Subscriptions Made Easy](https://www.revenuecat.com/) - RevenueCat makes it easy to implement and manage in-app subscriptions, analyze customer data, and grow recurring revenue on iOS, Android, and the web.

- [airship](https://www.airship.com/) - provides marketing and branding services. Airship allows companies to generate custom messages to consumers via push notifications, SMS messaging, and similar, and provides customer analytics services.

- [amplitude](https://www.amplitude.com/) - Give your teams self-service product data to understand your users, drive conversions, and increase engagement, growth and revenue.

- [Countly: Product analytics and innovation](https://count.ly/) - Countly is the best analytics platform to understand and enhance customer journeys in web, desktop and mobile applications. We securely process billions of data points every day in the cloud and on-premises in order to help companies across the globe grow their business.

- [appsflyer: Make good choices](https://www.appsflyer.com/) - The world’s top marketing and product teams turn to AppsFlyer cloud to power predictable app growth, protect customer privacy and deliver exceptional mobile experiences

**Messaging**:

- [OneSignal: Customer Messaging Delivered](https://onesignal.com/) - The market leading self-serve customer engagement solution for Push Notifications, Email, SMS & In-App.

- [WonderPush](https://www.wonderpush.com/) - Unlimited push notifications
for iOS, Android and Web.

## Apps

> Complete Projects(Open Source)

- ![](https://img.shields.io/github/stars/rustdesk/rustdesk?style=social)  [rustdesk](https://github.com/rustdesk/rustdesk) - Another remote desktop software

- ![](https://img.shields.io/github/stars/KRTirtho/spotube?style=social)   [spotube](https://github.com/KRTirtho/spotube) - An open source, cross-platform Spotify client compatible across multiple platforms
utilizing Spotify's data API and YouTube (or Piped.video or JioSaavn) as an audio source,
eliminating the need for Spotify Premium
  
- ![](https://img.shields.io/github/stars/roughike/inKino?style=social) [inKino](https://github.com/roughike/inKino) - inKino is a multiplatform Dart app for browsing movies and showtimes for Finnkino cinemas.

  InKino showcases **Redux**, has an extensive set of automated tests and 40% code sharing between Flutter and web. The Android & iOS apps are made with a single Flutter codebase. The progressive web app is made with AngularDart. This project is generally something that I believe is a good example of a multiplatform Dart project.

- ![](https://img.shields.io/github/stars/TheAlphamerc/flutter_ecommerce_app?style=social) [flutter_ecommerce_app: E-Commerce App built in flutter](https://github.com/TheAlphamerc/flutter_ecommerce_app)

- ![](https://img.shields.io/github/stars/mdanics/fluttergram?style=social) [fluttergram](https://github.com/mdanics/fluttergram) - A working Instagram clone written in Flutter using Firebase / Firestore

- ![](https://img.shields.io/github/stars/trentpiercy/trace?style=social) [trace](https://github.com/trentpiercy/trace) - Modern Crypto Portfolio & Market Explorer. Built with Flutter.
Open Source. Lightweight. Clean. Straightforward. Fast. Powerful.

- ![](https://img.shields.io/github/stars/aaronoe/FlutterCinematic?style=social) [❤️ FlutterCinematic](https://github.com/aaronoe/FlutterCinematic) - This app is a Flutter port of the native Android App [Cinematic](https://github.com/aaronoe/Cinematic). My intention in creating this app was understanding the intricacies of building apps in Flutter. Just like the native Android App this app does **not make any efforts in being a nicely architectured application**. That being said the whole point is to showcase Flutter's capabilities for building simple apps and to understand key difference and advantages to native development.

- ![](https://img.shields.io/github/stars/MarcinusX/flutter_ui_challenge_flight_search?style=social) [Flight search](https://github.com/MarcinusX/flutter_ui_challenge_flight_search) - This is my second UI Challenge. I picked a [Jhony Vino's Flight search design](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/e36a3e53917017.594779c56ecbf.gif) from [100 Mobile App UI Interactions](https://github.com/MarcinusX/flutter_ui_challenge_flight_search#:~:text=100%20Mobile%20App%20UI%20Interactions) and implemented it in Flutter.

  Whole process of development is documented on my [blog](https://marcinszalek.pl/flutter/ui-challenge-flight-search/).

- ![](https://img.shields.io/github/stars/jesusrp98/spacex-go?style=social) [spacex-go](https://github.com/jesusrp98/spacex-go) - The purpose of this project is to develop the ultimate SpaceX experience in a variety of platforms. A single experience, from a single codebase.

  From the start, SpaceX GO! has been developed to be light-weight, fast and easy to use. It takes all the data from the open-source r/SpaceX REST API, which can be found [here](https://github.com/r-spacex/SpaceX-API).

- ![](https://img.shields.io/github/stars/pawlik92/flutter_whirlpool?style=social) [flutter_whirlpool](https://github.com/pawlik92/flutter_whirlpool) - Flutter UI Challenge- SMART Washing Machine

  *App in action:*

![Washing machine GIF 1](https://github.com/pawlik92/flutter_whirlpool/raw/master/doc/img/1.gif)
![Washing machine GIF 2](https://github.com/pawlik92/flutter_whirlpool/raw/master/doc/img/2.gif)
![Washing machine GIF 3](https://github.com/pawlik92/flutter_whirlpool/raw/master/doc/img/3.gif)
![Washing machine GIF 4](https://github.com/pawlik92/flutter_whirlpool/raw/master/doc/img/4.gif)

- ![](https://img.shields.io/github/stars/matthewtory/trinity-orientation-2018?style=social) [Trinity Orientation 2018](https://github.com/matthewtory/trinity-orientation-2018) - An app created for Trinity College at University of Toronto. The app is acts as a companion for all first year students during orientation week. Available on [Google Play](https://play.google.com/store/apps/details?id=com.tory.trinityOrientation) and the [App Store](https://itunes.apple.com/us/app/trinity-orientation-2t2000s/id1431022073)

- ![](https://img.shields.io/github/stars/o1298098/Flutter-Movie?style=social) [Flutter-Movie](https://github.com/o1298098/Flutter-Movie) - 😎 🎬 A Flutter movie app build with **Fish-Redux** and The Movie DB api.

- ![](https://img.shields.io/github/stars/avirias/Grey?style=social) [Grey](https://github.com/avirias/Grey) -  A Material designed music player developed in Flutter

- ![](https://img.shields.io/github/stars/benoitletondor/Beer-Me-Up?style=social) [Beer-Me-Up](https://github.com/benoitletondor/Beer-Me-Up) - Beer Me Up is an iOS and Android app build with Flutter.

  The app is a personal beer logging that allows you to enter every beer you have to be sure to remember them forever.Beer Me Up is an iOS and Android app build with Flutter.

  The app is a personal beer logging that allows you to enter every beer you have to be sure to remember them forever.

- ![](https://img.shields.io/github/stars/MSzalek-Mobile/weight_tracker?style=social) [WeightTracker](https://github.com/MSzalek-Mobile/weight_tracker) - Simple application for tracking weight. See Google Play for more details about this app!

- ![](https://img.shields.io/github/stars/iampawan/AI-Radio?style=social)  [AI-Radio](https://github.com/iampawan/AI-Radio) - AI-Powered Voice Assistant Flutter Radio App

- ![](https://img.shields.io/github/stars/MDSADABWASIM/Toughest?style=social) [toughest](https://github.com/MDSADABWASIM/Toughest) - Interview questions and answers for preparation, built in pure flutter also have CI implementation for learning.

- ![](https://img.shields.io/github/stars/Roaa94/movies_app?style=social)[movies_app](https://github.com/Roaa94/movies_app) - A Flutter app that uses the "The Movie DB" api to fetch popular people and their info (their movies, images, ..etc).

- ![](https://img.shields.io/github/stars/MDSADABWASIM/You?style=social) [You](https://github.com/MDSADABWASIM/You) - The app checks what internet knows about you.

- ![](https://img.shields.io/github/stars/Blakexx/CryptoTracker?style=social) [Platypus Crypto](https://github.com/Blakexx/CryptoTracker) - Platypus Crypto is an ad-free cross-platform robust solution for tracking cryptocurrency assets. Our intuitive interface includes real-time 7-day graphs, current prices and market caps, and percent change over time. Featuring rapid sort, search and refresh features, and support for 32 fiat currencies, Platypus Crypto enables casual and power users alike to monitor cryptocurrency assets on-the-go! Our customization options allow for the removal of 7-day graphs for a more compact feel and a dark theme.

- ![](https://img.shields.io/github/stars/AminBhst/brisk?style=social)  [Brisk](https://github.com/AminBhst/brisk) -  A fast, multithreaded, cross-platform download manager for desktop

- ![](https://img.shields.io/github/stars/PierreBresson/flutter-wordpress-podcast?style=social)  [Flutter Wordpress Podcast](https://github.com/PierreBresson/flutter-wordpress-podcast) -  🎤 Podcast white label app based on Wordpress API

- ![](https://img.shields.io/github/stars/cybercying/coffee_coupon_full_system_demo?style=social) [Full Flutter System Demo for Coffee Coupons](https://github.com/cybercying/coffee_coupon_full_system_demo) - This project provides a full Flutter/Dart system template from front-end APPs to the backend database to demonstrate a coupon management system, which is suitable for a coffeehouse chain (or any restaurant chain) to build customer loyalty.

- ![](https://img.shields.io/github/stars/mateusz-bak/openreads-android?style=social) [A mobile books tracker that respects your privacy](https://github.com/mateusz-bak/openreads-android) - A simple privacy oriented mobile books tracker using Open Library API.

## Desktop Only

- ![](https://img.shields.io/github/stars/AppFlowy-IO/appflowy?style=social) [appflowy](https://github.com/AppFlowy-IO/appflowy) - Desktop App! The Open Source Notion Alternative(53+% Rust, 41+%Dart, C++...).
- ![](https://img.shields.io/github/stars/google/flutter-desktop-embedding?style=social) [flutter-desktop-embedding](https://github.com/google/flutter-desktop-embedding/) - This project was originally created to develop Windows, macOS, and Linux embeddings of Flutter. That work has since become part of Flutter, and all that remains here are experimental, early-stage desktop plugins.

  If you want to get started with Flutter on desktop, the place to start is now the Flutter documentation, rather than this project. You will already need to have followed the instructions there to get an application running on desktop before using any of the plugins here.

  - [menubar](https://github.com/google/flutter-desktop-embedding/tree/main/plugins/menubar) - This plugin provides access to a native menubar.

    This is a prototype, and in the long term will either be replaced by functionality within the Flutter framework itself, or a published plugin (likely part of flutter/plugins). Either way, the API will change significantly.
  - [window_size](https://github.com/google/flutter-desktop-embedding/tree/main/plugins/window_size) - This plugin allows resizing and repositioning the window containing the Flutter content, as well as querying screen information.

    This is a prototype, and in the long term is expected to be replaced by [functionality within the Flutter framework](https://docs.google.com/document/d/11_4wntz_9IJTQOo_Qhp7QF4RfpIMTfVygtOTxQ4OGHY/edit).

- ![](https://img.shields.io/github/stars/leanflutter/window_manager?style=social) ![](https://img.shields.io/badge/platform-mac%20%7C%20linux%20%7C%20windows-lightgrey) [window_manager](https://github.com/leanflutter/window_manager) - This plugin allows Flutter desktop apps to resizing and repositioning the window.

- ![](https://img.shields.io/github/stars/leanflutter/launch_at_startup?style=social) ![](https://img.shields.io/badge/platform-mac%20%7C%20linux%20%7C%20windows-lightgrey) [launch_at_startup](https://github.com/leanflutter/launch_at_startup) - This plugin allows Flutter desktop apps to Auto launch on startup / login.

## No-Code / Low-Code

- [FlutterFlow](https://flutterflow.io/) - Build applications faster than ever: Create beautiful UI, generate clean code, and deploy to the app stores or web in one click. Fully extensible with custom code.

## Contribution

Your contributions and suggestions are heartily welcome.

Thanks to all the people who already contributed!

<a href="https://github.com/nepaul/awesome-flutter/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=nepaul/awesome-flutter" />
</a>

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
