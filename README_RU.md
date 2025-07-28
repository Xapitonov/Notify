[English](README.md) | [Русский](README_RU.md)

<div align="center">
</br>
<img src="art/logo_notify.svg" width="200" />

</div>

<h1 align="center">Notify</h1>

</br>
<p align="center">
  <img alt="API" src="https://img.shields.io/badge/Api%2021+-50f270?logo=android&logoColor=black&style=for-the-badge"/></a>
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-a503fc?logo=kotlin&logoColor=white&style=for-the-badge"/></a>
  <img alt="Jetpack Compose" src="https://img.shields.io/static/v1?style=for-the-badge&message=Jetpack+Compose&color=4285F4&logo=Jetpack+Compose&logoColor=FFFFFF&label="/></a> 
  <img alt="material" src="https://custom-icon-badges.demolab.com/badge/material%20you-lightblue?style=for-the-badge&logoColor=333&logo=material-you"/></a>
  </br>
  </br>
  <a href="https://github.com/aritra-tech/Notify/actions">
  <a href="https://github.com/aritra-tech/Notify/actions">
    <img alt="Build" src="https://img.shields.io/github/actions/workflow/status/aritra-tech/notify/ci_build.yml?label=Build&style=for-the-badge"/></a>
  <img alt="GitHub commits since tagged version (branch)" src="https://img.shields.io/github/commits-since/aritra-tech/Notify/v1.0?color=palegreen&label=Commits&style=for-the-badge">
  <a href="https://github.com/aritra-tech/Notify/stargazers"><img src="https://img.shields.io/github/stars/aritra-tech/Notify?color=ffff00&style=for-the-badge"/></a>
  <a href="https://hits.sh/github.com/aritra-tech/Notify/"><img alt="Hits" src="https://hits.sh/github.com/aritra-tech/Notify.svg?style=for-the-badge&label=Views&extraCount=10&color=54856b"/></a>
    </br>
  <a href="https://github.com/aritra-tech/Notify/releases"><img src="https://img.shields.io/github/downloads/aritra-tech/notify/total?color=orange&style=for-the-badge"/></a>
  <img alt="Размер кода в байтах" src="https://img.shields.io/github/languages/code-size/aritra-tech/Notify?style=for-the-badge">
  <a href=""><img src="https://img.shields.io/github/v/release/aritra-tech/notify?color=purple&include_prereleases&logo=github&style=for-the-badge"/></a>
  <a href="https://play.google.com/store/apps/details?id=com.aritra.notify"><img src="https://img.shields.io/endpoint?color=purple&logo=google-play&style=for-the-badge&label=Play%20store&url=https%3A%2F%2Fplay.cuzi.workers.dev%2Fplay%3Fi%3Dcom.aritra.notify%26l%3DAndroid%26m%3D%24version"/></a>
  </br>
</p>

<h4 align="center">📝Notify — простое приложение для заметок, созданное с использованием современных инструментов разработки Android.    
Этот проект демонстрирует качественную реализацию Android с правильным архитектурным дизайном.              
Сделано с ♥ для всех Android-разработчиков.
<br>
<br>
Я развиваю проект публично. Идея в том, чтобы каждый мог внести вклад, оставить комментарии, предложить идеи и т.д. через вкладку <a href="https://github.com/aritra-tech/Notify/discussions">Обсуждения</a>.
<br>
<br>
Пожалуйста, ознакомьтесь с файлом <a href="https://github.com/aritra-tech/Notify/blob/master/CONTRIBUTING_RU.md">CONTRIBUTING_RU.md</a> перед тем, как начать вносить изменения.
</h4>

<div align="center">
</br>
<img src="art/notify_banner.svg"/>

</div>

<div align="center">
  
# ⬇️ Скачать
<a href="https://play.google.com/store/apps/details?id=com.aritra.notify"><img alt="Загрузить в Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" height=80px />
<a href="https://github.com/aritra-tech/notify/releases/latest"><img alt="Загрузить с GitHub" src="https://user-images.githubusercontent.com/69304392/148696068-0cfea65d-b18f-4685-82b5-329a330b1c0d.png" height=80px />
<a href="https://apt.izzysoft.de/fdroid/index/apk/com.aritra.notify/"><img alt="Загрузить через IzzyOnDroid" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" height=80px />
</div>

# Особенности ✨

_Notify_ сосредоточен на следующих ключевых функциях:

- Дизайн с одной Activity.
- Работа в офлайн — заметки ✈️.
- Чистый и простой Material UI 🎨.
- Тёмная тема 🌗.
- Функция резервного копирования и восстановления 👀.
- UI на Jetpack Compose 🖌.
- Переключение между разметками 🌟.
- Возможность поделиться заметками в виде текста, изображения и PDF 📤.

# Построено с помощью 🛠

- [Kotlin](https://kotlinlang.org/) — официальный язык программирования для Android.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) — для асинхронных вызовов и задач с использованием потоков.
- [Jetpack Compose UI Toolkit](https://developer.android.com/jetpack/compose) — современный инструмент для разработки UI.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) — набор библиотек для создания надежных, тестируемых и поддерживаемых приложений.
  - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) — объекты данных, которые уведомляют view при изменении базы.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) — хранит UI-данные, не уничтожающиеся при изменениях UI.
  - [Room](https://developer.android.com/topic/libraries/architecture/room) — ORM для работы с SQLite базой.
  - [StateFlow и SharedFlow](https://developer.android.com/kotlin/flow/stateflow-and-sharedflow#:~:text=StateFlow%20is%20a%20state%2Dholder,property%20of%20the%20MutableStateFlow%20class.) — API Flow для оптимальной передачи обновлений состояния нескольким потребителям.
- [Dependency Injection](https://developer.android.com/training/dependency-injection) —
    - [Hilt-Dagger](https://dagger.dev/hilt/) — стандартный способ внедрения зависимостей Dagger в Android.
    - [Hilt-ViewModel](https://developer.android.com/training/dependency-injection/hilt-jetpack) — DI для ViewModel.
- [Material Components for Android](https://github.com/material-components/material-components-android) — модульные и настраиваемые UI-компоненты Material Design.
- [Accompanist](https://google.github.io/accompanist/) — набор расширений для Jetpack Compose.
- [Biometric](https://developer.android.com/jetpack/androidx/releases/biometric) — аутентификация через биометрические данные или учетные записи устройства.
- [gson](https://github.com/google/gson) — библиотека сериализации/десериализации Java объектов в JSON и обратно.
- [Coil](https://github.com/coil-kt/coil) — загрузка изображений для Android с поддержкой Kotlin Coroutines.
- [Telephoto](https://github.com/saket/telephoto) — инструменты для создания медиаконтента в Compose UI.
- [Camera X](https://developer.android.com/jetpack/androidx/releases/camera) — облегчает добавление возможностей камеры в приложение.

# Архитектура 👷‍♂️
Это приложение использует архитектуру [MVVM (Model View View-Model)](https://developer.android.com/topic/architecture#recommended-app-arch).

![MVVM](art/mvvm.png)

<div align="center">
  
# Участники проекта 📢

<a href="https://github.com/aritra-tech/Notify/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=aritra-tech/Notify" />
</a>

# История звезд ⭐

[![График звёзд](https://api.star-history.com/svg?repos=aritra-tech/Notify&type=Date)](https://star-history.com/#aritra-tech/Notify&Date)

# Считаете этот репозиторий полезным? ❤️

Поддержите проект, присоединившись к __[наблюдателям](https://github.com/aritra-tech/Notify/stargazers)__ :star: <br>
И __[следите](https://github.com/aritra-tech)__ за моими следующими проектами! 🤩

</div>
