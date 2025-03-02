# FreePulse-Grief [![Discord](https://img.shields.io/discord/1297490292349468715?logo=discord&logoColor=white&label=Discord&color=7289DA)](https://discord.gg/openpulse)

<p align="center">
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/badge/Platform-Linux-brightgreen?logo=linux&logoColor=white" alt="Linux"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/badge/Platform-Windows-brightgreen?logo=windows&logoColor=white" alt="Windows"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/badge/Platform-macOS-brightgreen?logo=apple&logoColor=white" alt="macOS"></a>
</p>

<p align="center">
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2FFreePulse%2FFreePulse-Grief&label=Repository%20Visits&countColor=%230c7ebe&style=flat&labelStyle=none" alt="Visitors"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/license/FreePulse/FreePulse-Grief?color=blue" alt="License"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/contributors/FreePulse/FreePulse-Grief?color=blue" alt="Contributors"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/repo-size/FreePulse/FreePulse-Grief" alt="Repository Size"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/commit-activity/m/FreePulse/FreePulse-Grief" alt="Commit Activity"></a>
</p>

<p align="center">
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/issues/FreePulse/FreePulse-Grief" alt="Issues"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/issues-closed/FreePulse/FreePulse-Grief" alt="Issues Closed"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/issues-pr/FreePulse/FreePulse-Grief" alt="Pull Requests"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/github/last-commit/FreePulse/FreePulse-Grief" alt="Last Commit"></a>
<a href="https://github.com/FreePulse/FreePulse-Grief"><img src="https://img.shields.io/badge/Maintained-yes-brightgreen" alt="Maintenance"></a>
</p>

FreePulse-Grief - это свободная и бесплатная сборка сервера построенная на базе ядра [Paper](https://papermc.io/).

**Официальный** сервер, использующий и активно разрабатывающий эту сборку: mc.openpulse.ru

## Особенности

1. **Установщик**: После запуска установщик автоматически скачает сборку, ядро, необходимые плагины и расширения PlaceholderAPI.
2. **Полностью свободна**: Мы используем лицензию [GNU AGPL v3.0](https://www.gnu.org/licenses/agpl-3.0.en.html), каждый может модифицировать, распространять, и использовать эту сборку.
3. **Только свободные плагины**: Мы используем только свободные плагины, с лицензиями которые были одобрены [Free Software Foundation (FSF)](https://www.fsf.org/).
   - Мы не используем несвободные плагины, даже если они имеют открытый исходный код.


## Лицензия

Проект лицензирован по [GNU AGPL v3.0](https://www.gnu.org/licenses/agpl-3.0.html).  
**Основные условия AGPL:**
- Свобода использования, изучения и модификации.
- Требование открывать исходный код любых изменений.

## Вклад

Мы приветствуем любую помощь проекту. Если у вас есть предложения, исправления или улучшения, пожалуйста, создайте issue или отправьте pull request. Ваша помощь очень важна. Подробнее вы можете узнать в [CONTRIBUTING.md](CONTRIBUTING.md)

## Установка

В репозитории нашей сборки не содержатся никакие бинарные файлы, установщик сам скачивает их с официальных ресурсов.

Но мы также предоставляем возможность скачать двоичные файлы ядра, плагинов, и расширений PlaceholderAPI, например если у вас нет возможности запустить установщик.

> **ВАЖНО!**<br>
> Хотя мы гарантируем отсутствие вредоносного кода в нашей сборке и установщике, мы не можем дать абсолютную гарантию для сторонних бинарных файлов, даже учитывая то что они загружаются с официальных источников. Вы всегда можете проверить исходный код всех плагинов самостоятельно.

```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/FreePulse/FreePulse-Grief/main/install.sh)"
```

