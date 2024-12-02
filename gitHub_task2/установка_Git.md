# Установка Git
Чтобы начать использовать Git, его необходимо установить на вашу операционную систему. Ниже описаны шаги для разных платформ.


## Windows
 1. Перейдите на официальный сайт Git и скачайте последнюю версию.
 2. Запустите установочный файл:
 - В процессе установки выберите:
   - "Use Git from the command line and also from 3rd-party software" – для интеграции с терминалом.
   - "Use the OpenSSL library" – для безопасности.
   - "Checkout Windows-style, commit Unix-style line endings" – для совместимости строковых окончаний.
   -  Завершите установку, оставив остальные параметры по умолчанию.
   -  Проверьте установку, открыв командную строку и введя:
      `git --version`
       Должна появиться версия Git.

## macOS
 1. Убедитесь, что у вас установлен Homebrew (если нет, установите его командой):
    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
 2. Установите Git через Homebrew:
    `brew install git`
 3.  Проверьте установку:
    `git --version`

---
---
<br>

[к содержанию](gitGuide.md "к содержанию")