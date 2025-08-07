# BCFuture
### BlockCard Future Bot

Интерактивное веб‑приложение (Telegram Mini App + Web) для симуляции трейдинга, участия в турнирах и отслеживания PnL. Фронтенд на React + Vite + TypeScript, бэкенд‑логика. Интеграция кошелька через TON Connect.


### Возможности
- **Трейдинг (симуляция)**: ордера, баланс, лидерборды, учебный режим
- **Турниры**: создание, участие, призовые, участники
- **Профиль и рефералы**: VIP система, комиссии
- **TON Connect**: подключение кошелька TON
- **Интеграции**: Dexscreener и др.


### Технологии
- **Frontend**: Vite, React, TypeScript, TailwindCSS
- **Backend**; - закрытая информация.
- **Wallet**: TON Connect (manifest в `public/tonconnect-manifest.json`)
- **Прочее**: Telegram WebApp (см. `src/hooks/useTelegram.ts`)


### Структура проекта (упрощенно)
- `src/` — приложение (React)
  - `components/` — экраны, виджеты, модули трейдинга/турниров
  - `services/` — интеграции (wallet, trading, tournament, referral, vip)
  - `contexts/`, `hooks/`, `translations/`, `types/`, `utils/`
- `public/` — статика, `tonconnect-manifest.json`
- `dist/` — сборка фронтенда


### Документация внутри репозитория
- `TOURNAMENTS_README.md` — особенности турнирного модуля
- `VIP_COMMISSION_SYSTEM.md` — VIP и комиссия
- `VIP_SYSTEM_DEPLOYMENT.md` — деплой VIP системы


### Разработка
- Используйте Node.js LTS (рекомендация: 18+ или 20+)
- Следуйте стилю проекта и линтингу (см. `eslint.config.js`)
- Не коммитьте ключи и секреты


### Вопросы и обратная связь
Создавайте issue в репозитории или обращайтесь к мейнтейнерам проекта.


### Лицензия
Уточните условия лицензирования в файле `LICENSE` (если имеется) или согласуйте с владельцем проекта.
