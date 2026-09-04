# Приложение "Для Ксюши" 💕

## Как собрать .ipa файл

### Способ 1: PhoneGap Build (онлайн, без Mac)

1. Зайдите на https://build.phonegap.com
2. Зарегистрируйтесь
3. Нажмите **+ New app** → **Upload a .zip**
4. Загрузите папку `KsyushaApp` как .zip файл
5. Выберите платформу **iOS**
6. Нажмите **Build**
7. Скачайте готовый .ipa файл

### Способ 2: Xcode (нужен Mac)

1. Установите Node.js и Cordova:
```bash
npm install -g cordova
```

2. Перейдите в папку проекта:
```bash
cd KsyushaApp
```

3. Добавьте iOS платформу:
```bash
cordova platform add ios
```

4. Откройте проект в Xcode:
```bash
cordova build ios
open platforms/ios/Ксюши.xcworkspace
```

5. В Xcode: Product → Archive → Distribute App → Export IPA

### Способ 3: Capacitor (рекомендуется)

1. Установите Capacitor:
```bash
npm install @capacitor/core @capacitor/cli
npx cap init "Для Ксюши" com.ksyusha.loveapp
npx cap add ios
npx cap copy
npx cap open ios
```

2. В Xcode: Product → Archive → Export IPA

## Что умеет приложение

- 🏠 Главная страница с пульсирующим сердцем
- 📸 Галерея для загрузки ваших совместных фото
- 💌 Раздел с любовным письмом
- 💕 Плавающие сердечки
- 📱 Навигация в стиле iOS
- 🔢 Счётчик дней вместе

## Как добавить фото

1. Перейдите во вкладку "Фото"
2. Нажмите "Выбрать фото"
3. Загрузите совместные фотографии
