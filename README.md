<div align="center">

<img src="assets/logo.png" alt="Логотип ChaMi VPN" width="160" />

# ChaMi VPN

Официальные приложения [ChaMi VPN](https://chama.cc) для Windows и Android.

[![Скачать для Windows](https://img.shields.io/badge/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20%D0%B4%D0%BB%D1%8F%20Windows-0078D4?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgMy40NSA5Ljc1IDIuMXY5LjQySDB6TTEwLjk1IDEuOTMgMjQgMHYxMS41MkgxMC45NXpNMCAxMi42aDkuNzV2OS40NUwwIDIwLjd6TTEwLjk1IDEyLjZIMjRWMjRsLTEzLjA1LTEuODV6Ii8%2BPC9zdmc%2B)](https://github.com/chama-development/Chama-VPN/releases/latest/download/Chama-Windows.exe)
[![Скачать для Android](https://img.shields.io/badge/%D0%A1%D0%BA%D0%B0%D1%87%D0%B0%D1%82%D1%8C%20%D0%B4%D0%BB%D1%8F%20Android-2E9E5B?style=for-the-badge&logo=android&logoColor=white)](https://github.com/chama-development/Chama-VPN/releases/latest/download/Chama-Android.apk)

[![Версия](https://img.shields.io/github/v/release/chama-development/Chama-VPN?label=%D0%B2%D0%B5%D1%80%D1%81%D0%B8%D1%8F&color=6D4AFF)](https://github.com/chama-development/Chama-VPN/releases/latest)

Нет подписки? Попробуйте бесплатно на **[chama.cc](https://chama.cc)**.

</div>

---

## 📥 Скачать

| Платформа | Требования | Скачать |
|:--|:--|:--|
| 🪟 **Windows** | Windows 10 или 11, 64-бит | [**Установщик EXE**](https://github.com/chama-development/Chama-VPN/releases/latest/download/Chama-Windows.exe) |
| 🤖 **Android** | Android 8.0 и новее | [**Приложение APK**](https://github.com/chama-development/Chama-VPN/releases/latest/download/Chama-Android.apk) |

Все версии доступны в разделе [Releases](https://github.com/chama-development/Chama-VPN/releases).

## 🚀 Установка

### Windows

1. Скачайте и запустите `Chama-Windows.exe`. Установщик попросит права администратора. Отдельно устанавливать .NET не нужно.
2. Если SmartScreen показывает «Windows защитил ваш компьютер», убедитесь, что файл скачан из этого репозитория. Чтобы продолжить установку, нажмите **«Подробнее»** → **«Выполнить в любом случае»**.
3. Скопируйте ссылку на подписку из личного кабинета на [chama.cc](https://chama.cc) и нажмите **«Вставить из буфера»** в приложении. Можно также выбрать **«Ввести вручную»**.
4. Выберите локацию и нажмите кнопку подключения.

### Android

1. Скачайте `Chama-Android.apk` на телефон и откройте файл.
2. Если Android попросит, разрешите установку приложений из выбранного браузера или файлового менеджера, затем нажмите **«Установить»**.
3. Скопируйте ссылку на подписку из личного кабинета на [chama.cc](https://chama.cc) и нажмите **«Вставить из буфера»**. Можно ввести ссылку вручную или выбрать **«Сканировать QR-код»** и отсканировать код с другого устройства.
4. Выберите локацию, нажмите кнопку подключения и подтвердите системный запрос на создание VPN-подключения.

Чтобы перенести подписку с компьютера на телефон, откройте **«Поделиться подпиской»** в Windows-приложении и отсканируйте QR-код Android-приложением.

## ✨ Возможности

- ⚡ Подключение в одно нажатие и выбор локации.
- 📊 Информация о подписке: использованный трафик и срок действия.
- 🎯 Маршрутизация по приложениям: выбранные приложения через VPN или в обход него. На Windows доступна в режиме TUN.
- 📷 Сканирование QR-кода подписки на Android и обмен подпиской между устройствами.
- 🔘 Плитка VPN в быстрых настройках Android.
- 🪟 Системный прокси, режим TUN, значок в трее и автозапуск на Windows.
- 🔄 Проверка обновлений и предложение установить новую версию.

### 🛡️ Защита при обрыве подключения

**Windows:** kill switch доступен в режиме TUN через установленную службу и блокирует обычный интернет-трафик при потере VPN до восстановления подключения или отключения пользователем. Он недоступен в режиме «VPN только для выбранных приложений». При аварийном завершении самой службы непрерывная блокировка не гарантируется.

**Android:** для блокировки трафика без VPN используйте системные настройки **«Постоянная VPN»** и **«Блокировать подключения без VPN»**, если они доступны на вашем устройстве. Названия пунктов зависят от производителя. При такой блокировке приложения, исключённые из VPN, могут потерять доступ к интернету.

## 🔄 Обновления

Приложения проверяют наличие новых версий и предлагают обновление. Подпись данных обновления и контрольная сумма скачанного файла проверяются перед установкой.

Обновление также можно установить вручную: скачайте новый EXE или APK из [последнего релиза](https://github.com/chama-development/Chama-VPN/releases/latest) и установите поверх текущей версии. Удалять приложение перед обновлением не нужно.

## 📄 Документы

[Условия использования](https://telegra.ph/Usloviya-ispolzovaniya-Chama-VPN-10-02) · [Политика конфиденциальности](https://telegra.ph/Politika-konfidencialnosti-Chama-VPN-10-02) · [Лицензии](https://telegra.ph/Licenzii-Chama-VPN-10-02)

## 💬 Поддержка

Telegram: [@Chama_VPN_support_bot](https://t.me/Chama_VPN_support_bot)

---

<div align="center">

<sub>Работает на <a href="https://github.com/XTLS/Xray-core">Xray-core</a>. В Windows для режима TUN используется <a href="https://github.com/SagerNet/sing-box">sing-box</a>.</sub>

</div>
