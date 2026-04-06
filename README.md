# 🚀 VLESS Configs Collection

<div align="center">

![VLESS](https://img.shields.io/badge/Protocol-VLESS-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Auto-Update](https://img.shields.io/badge/Auto--Update-Daily-orange?style=for-the-badge)

**Автоматически обновляемая коллекция VLESS конфигураций**

[🔗 Использование](#-использование) • [📋 Список конфигов](#-список-конфигов) • [⚙️ Настройка](#️-настройка) • [❓ FAQ](#-faq)

</div>

---

## 📖 О проекте

Данный репозиторий содержит автоматически собранные VLESS конфигурации от различных провайдеров. Конфиги обновляются регулярно и проверяются на работоспособность.

### ✨ Особенности

- 🔄 **Автоматическое обновление** - конфиги обновляются каждые 6 часов
- ✅ **Проверка работоспособности** - только рабочие конфиги
- 🌍 **Различные локации** - серверы по всему миру
- 📱 **Совместимость** - работает с v2rayN, v2rayNG, Nekoray и другими клиентами

---

## 🚀 Использование

### Быстрый старт

1. **Скачайте конфиги**
   ```bash
   git clone https://github.com/username/vless-configs.git
   cd vless-configs
   ```

2. **Выберите конфиг** из папки `configs/`

3. **Импортируйте в клиент**
   - Скопируйте ссылку vless://
   - Вставьте в ваш V2Ray клиент

### 📱 Рекомендуемые клиенты

| Платформа | Клиент | Ссылка |
|-----------|--------|--------|
| 🪟 Windows | v2rayN | [Скачать](https://github.com/2dust/v2rayN/releases) |
| 🐧 Linux | Nekoray | [Скачать](https://github.com/MatsuriDayo/nekoray/releases) |
| 🍎 macOS | V2RayXS | [Скачать](https://github.com/tzmax/V2RayXS/releases) |
| 📱 Android | v2rayNG | [Скачать](https://github.com/2dust/v2rayNG/releases) |
| 📱 iOS | Shadowrocket | [App Store](https://apps.apple.com/app/shadowrocket/id932747118) |

---

## 📋 Список конфигов

Конфиги расположены в папке `configs/`:

```
configs/
├── us-servers.txt      # Серверы США
├── eu-servers.txt      # Серверы Европы
├── asia-servers.txt    # Серверы Азии
└── all-servers.txt     # Все серверы
```

### 📊 Статистика

- **Всего конфигов**: ~150+
- **Активных серверов**: ~120+
- **Последнее обновление**: Автоматически каждые 6 часов
- **Средняя скорость**: 50+ Mbps

---

## ⚙️ Настройка

### Импорт в v2rayN (Windows)

1. Откройте v2rayN
2. Нажмите `Ctrl + V` или `Servers → Import from clipboard`
3. Конфиг автоматически добавится в список

### Импорт в v2rayNG (Android)

1. Скопируйте vless:// ссылку
2. Откройте v2rayNG
3. Нажмите ➕ → Import config from clipboard

### Пакетный импорт

Для импорта всех конфигов сразу:

```bash
# Скопировать все конфиги в буфер обмена
cat configs/all-servers.txt | xclip -selection clipboard
```

---

## 🔒 Безопасность

- ⚠️ **Не используйте для незаконной деятельности**
- 🔐 Рекомендуется использовать дополнительное шифрование
- 🛡️ Проверяйте конфиги перед использованием
- 🚫 Не доверяйте неизвестным источникам

---

## ❓ FAQ

<details>
<summary><b>Как часто обновляются конфиги?</b></summary>
<br>
Конфиги обновляются автоматически каждые 6 часов. Проверяйте время последнего коммита.
</details>

<details>
<summary><b>Почему некоторые конфиги не работают?</b></summary>
<br>
Серверы могут быть перегружены или временно недоступны. Попробуйте другой конфиг из списка.
</details>

<details>
<summary><b>Можно ли использовать для торрентов?</b></summary>
<br>
Не рекомендуется. Используйте выделенные VPN-сервисы для торрентов.
</details>

<details>
<summary><b>Как проверить скорость сервера?</b></summary>
<br>
Используйте встроенные инструменты тестирования в вашем клиенте (Real Ping, Speed Test).
</details>

---

## 📝 Структура конфига

Типичный VLESS конфиг выглядит так:

```
vless://[uuid]@[server]:[port]?encryption=none&security=tls&sni=[domain]&type=ws&path=[path]#[name]
```

### Параметры:
- `uuid` - Уникальный идентификатор
- `server` - IP или домен сервера
- `port` - Порт подключения
- `encryption` - Тип шифрования
- `security` - Протокол безопасности (tls/reality)
- `type` - Тип транспорта (ws/grpc/tcp)

---

## 🤝 Вклад в проект

Contributions are welcome! 

1. Fork репозиторий
2. Создайте feature branch (`git checkout -b feature/new-configs`)
3. Commit изменения (`git commit -am 'Add new configs'`)
4. Push в branch (`git push origin feature/new-configs`)
5. Создайте Pull Request

---

## ⚠️ Disclaimer

Этот репозиторий создан исключительно в образовательных целях. Автор не несёт ответственности за использование конфигов в незаконных целях. Используйте на свой риск.

**Соблюдайте законы вашей страны!**

---

## 📜 Лицензия

MIT License - см. [LICENSE](LICENSE)

---

## 📞 Контакты

- 💬 **Issues**: [GitHub Issues](https://github.com/username/vless-configs/issues)
- 📧 **Email**: your-email@example.com
- 💬 **Telegram**: @your_channel

---

<div align="center">

### ⭐ Поставьте звезду, если проект был полезен!

**Made with ❤️ for free internet**

![Visitors](https://visitor-badge.laobi.icu/badge?page_id=username.vless-configs)
![GitHub stars](https://img.shields.io/github/stars/username/vless-configs?style=social)
![GitHub forks](https://img.shields.io/github/forks/username/vless-configs?style=social)

</div>
