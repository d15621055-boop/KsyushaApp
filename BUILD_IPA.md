# Сборка .ipa через GitHub Actions

## Пошаговая инструкция

### 1. Установи Git
Скачай с https://git-scm.com/download/win

### 2. Создай репозиторий на GitHub
- Зайди на https://github.com/new
- Название: `KsyushaApp`
- PUBLIC (иначе Actions не будут работать бесплатно)
- Нажми "Create repository"

### 3. Загрузи код
Открой PowerShell и выполни:

```powershell
cd C:\Users\ADMIN\Desktop\Payload\KsyushaApp
git init
git add .
git commit -m "love app for ksyusha"
git branch -M main
git remote add origin https://github.com/TVOY_USERNAME/KsyushaApp.git
git push -u origin main
```

(Замени TVOY_USERNAME на свой ник на GitHub)

### 4. Дождись сборки
- Зайди в репозиторий → вкладка "Actions"
- Дождись зелёной галочки (обычно 3-5 минут)
- Нажми на сборку → внизу "KsyushaApp" — скачается .ipa

### 5. Установи на iPhone
1. Скачай **AltStore** на компьютер: https://altstore.io
2. Установи AltStore на iPhone через iTunes
3. Открой AltStore на iPhone
4. Нажми "+" → выбери скачанный .ipa
5. Готово!

**Важно:** AltStore нужно обновлять раз в 7 дней (подключай iPhone к компьютеру).
