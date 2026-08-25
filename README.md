# 🌸 App Flutter 

Aplicación móvil desarrollada con **Flutter** utilizando una interfaz moderna, sencilla y basada en una paleta de colores pastel.

## 📱 Descripción

**App Flutter Pastel** es una aplicación desarrollada como proyecto de aprendizaje y práctica con Flutter. El proyecto implementa diferentes pantallas y funcionalidades, utilizando una estructura organizada por características.

Actualmente cuenta con:

* 🌸 Pantalla Splash
* 🔐 Inicio de sesión
* 📝 Registro de usuario
* 🔑 Recuperación de contraseña
* 📊 Dashboard principal
* 🎨 Tema y colores personalizados
* 📱 Diseño adaptable

## 🛠️ Tecnologías utilizadas

* **Flutter**
* **Dart**
* **Material 3**
* **Android Studio / Visual Studio Code**
* **Git**
* **GitHub**

## 📂 Estructura del proyecto

```text
lib/
│
├── main.dart
│
├── core/
│   └── theme/
│       └── app_colors.dart
│
└── features/
    │
    ├── splash/
    │   └── presentation/
    │       └── pages/
    │           └── splash.dart
    │
    ├── auth/
    │   └── presentation/
    │       └── pages/
    │           ├── login_screen.dart
    │           ├── signup_screen.dart
    │           └── recover_password_screen.dart
    │
    └── dashboard/
        └── presentation/
            └── pages/
                └── dashboard_page.dart
```

## 🚀 Instalación

### 1. Clonar el repositorio

```bash
git clone URL_DEL_REPOSITORIO
```

### 2. Entrar al proyecto

```bash
cd flutter_application_1
```

### 3. Instalar las dependencias

```bash
flutter pub get
```

### 4. Ejecutar la aplicación

```bash
flutter run
```

## 🌐 Ejecutar versión web

Para ejecutar el proyecto en Chrome:

```bash
flutter run -d chrome
```

Para generar la versión web:

```bash
flutter build web
```

Los archivos generados estarán en:

```text
build/web/
```

## 🎨 Arquitectura

El proyecto utiliza una organización basada en **Features**, separando las funcionalidades principales de la aplicación.

```text
features/
├── splash/
├── auth/
└── dashboard/
```

Esto permite mantener el código organizado y facilita agregar nuevas funcionalidades posteriormente.

## 🔀 Rutas de la aplicación

La aplicación utiliza las siguientes rutas:

| Ruta         | Pantalla             |
| ------------ | -------------------- |
| `/`          | Splash               |
| `/login`     | Inicio de sesión     |
| `/signup`    | Registro             |
| `/recover`   | Recuperar contraseña |
| `/dashboard` | Dashboard            |


**Mariana López Palencia**


