# Firebase Anket Uygulaması

Google Flutter İle Mobil Uygulama Kursu (BTK - Engin Demiroğ)

## Prerequstiques
Node.js
Google firebase projesi oluşturun ve web konsol ile seçerek aktif edin.

https://firebase.google.com/docs/cli#windows/
https://firebase.flutter.dev/docs/overview/

### Getting Started
firebase araçları için nodejs konsoldan aşağıdaki komutu girin.

$npm install -g firebase-tools

### firebase de oturum açın
$firebase login

### projelerinizi listeleyin
$firebase projects:list

### bağımlılıklar için proje klasöründe aşağıdaki komutları çalıştırın.
$flutter pub add firebase_core

### Install the CLI if not already done so
$dart pub global activate flutterfire_cli

### Run the `configure` command, select a Firebase project and platforms
$flutterfire configure
