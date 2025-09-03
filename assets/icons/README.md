# Локальные иконки AI Clinic (@expo/vector-icons)

## Описание

Этот проект использует готовые иконки из библиотеки @expo/vector-icons, которая включает в себя множество популярных иконных шрифтов: Ionicons, MaterialIcons, FontAwesome, AntDesign, Feather и др. Иконки работают локально без необходимости подключения к интернету.

## Структура

- `components/LocalIcons.js` - основной файл с компонентами иконок
- `assets/icons/` - папка для дополнительных иконок (если потребуется)

## Доступные иконки

### Основные навигационные
- `home` - 🏠 home-outline (Ionicons)
- `search` - 🔍 search-outline (Ionicons)
- `analytics` - 📊 bar-chart-outline (Ionicons)
- `settings` - ⚙️ settings-outline (Ionicons)

### Голосовые функции
- `mic` - 🎤 mic-outline (Ionicons)
- `stop` - ⏹️ stop-circle-outline (Ionicons)

### Коммуникация
- `call` - 📞 call-outline (Ionicons)

### Документы и контент
- `document-text` - 📄 document-text-outline (Ionicons)
- `image` - 🖼️ image-outline (Ionicons)

### Аналитика и статистика
- `trending-up` - 📈 trending-up-outline (Ionicons)
- `stats-chart` - 📊 stats-chart-outline (Ionicons)
- `grid` - ⊞ grid-outline (Ionicons)
- `analytics` - 📊 bar-chart-outline (Ionicons)

### Время и навигация
- `time` - ⏰ time-outline (Ionicons)
- `chevron-forward` - › chevron-forward-outline (Ionicons)
- `apps` - ⊞ apps-outline (Ionicons)

### Компьютерное зрение
- `eye` - 👁️ eye-outline (Ionicons)

### Эмоции и классификация
- `heart` - ❤️ heart-outline (Ionicons)
- `layers` - 📚 layers-outline (Ionicons)

### Уведомления и звук
- `notifications` - 🔔 notifications-outline (Ionicons)
- `volume-high` - 🔊 volume-high-outline (Ionicons)

### Интерфейс
- `moon` - 🌙 moon-outline (Ionicons)
- `flash` - ⚡ flash-outline (Ionicons)

### Действия
- `refresh` - 🔄 refresh-outline (Ionicons)
- `download` - ⬇️ download-outline (Ionicons)
- `information-circle` - ℹ️ information-circle-outline (Ionicons)

### Пользователи
- `person-add` - 👤+ person-add-outline (Ionicons)
- `log-in` - ➡️ log-in-outline (Ionicons)

### Статусы
- `checkmark` - ✓ checkmark-outline (Ionicons)
- `checkmark-circle` - ✅ checkmark-circle-outline (Ionicons)
- `close` - ✕ close-outline (Ionicons)

## Использование

```javascript
import LocalIcons from '../components/LocalIcons';

// Простое использование
{LocalIcons.home({ size: 24, color: "#ffffff" })}

// С проверкой существования
{LocalIcons[iconName] ? 
  LocalIcons[iconName]({ size: 24, color: "#ffffff" }) : 
  <Text style={{ color: "#ffffff", fontSize: 16 }}>?</Text>
}
```

## Преимущества

1. **🎨 Профессиональные иконки** - готовые иконки от ведущих дизайнеров
2. **🎨 Консистентность** - единый стиль в рамках каждого набора иконок
3. **�� Производительность** - оптимизированные векторные иконки
4. **🔄 Работа без интернета** - все иконки загружаются локально
5. **⚡ Быстрая загрузка** - встроенные в Expo SDK
6. **🎨 Множество вариантов** - тысячи готовых иконок на выбор
7. **📐 Масштабируемость** - идеально для разных размеров экранов
8. **�� Надежность** - проверенная библиотека с активной поддержкой
9. **🎯 Простота использования** - готовые компоненты
10. **🌈 Кросс-платформенность** - работают на всех устройствах

## Технические детали

- Библиотека: `@expo/vector-icons`
- Включает наборы: Ionicons, MaterialIcons, FontAwesome, AntDesign, Feather и др.
- Формат: Векторные иконки (SVG-подобные)
- Поддержка кастомизации размера и цвета
- Работают локально (не требуют интернета)
- Встроены в Expo SDK для максимальной производительности
- Оптимизированы для React Native

## Совместимость

- ✅ iOS
- ✅ Android  
- ✅ Web
- ✅ Expo Go
- ✅ React Native CLI

## Производительность

- ⚡ Мгновенная загрузка
- 💾 Минимальное использование памяти
- 🔄 Отсутствие сетевых запросов
- 📱 Оптимизировано для мобильных устройств
- 🎨 Векторное масштабирование

## Добавление новых иконок

1. Откройте `components/LocalIcons.js`
2. Добавьте новый компонент в объект `LocalIcons`
3. Используйте готовые иконки из @expo/vector-icons
4. Следуйте существующему формату с параметрами `size` и `color`

## Пример добавления иконки

```javascript
newIcon: ({ size = 24, color = '#000000' }) => (
  <Ionicons name="star-outline" size={size} color={color} />
),
```

## Доступные наборы иконок

### Ionicons (используется в проекте)
- Более 1,300 иконок
- Два стиля: filled и outline
- Оптимизированы для мобильных приложений
- Единый дизайн-язык

### MaterialIcons
- Более 2,000 иконок
- Официальные иконки Material Design
- Поддержка разных стилей
- Широко используются в Android

### FontAwesome
- Более 1,500 иконок
- Популярный набор иконок
- Поддержка версий 5 и 6
- Универсальный дизайн

### AntDesign
- Более 700 иконок
- Дизайн-система Ant Design
- Оптимизированы для интерфейсов
- Современный стиль

### Feather
- Более 280 иконок
- Минималистичный дизайн
- Единый стиль линий
- Идеальны для простых интерфейсов

## Дизайн-система

- **Размеры**: Рекомендуется использовать кратные 4 (16, 20, 24, 32, 48, 64)
- **Цвета**: Поддерживают любые цвета через параметр `color`
- **Стили**: Outline, filled, sharp в зависимости от набора
- **Масштабирование**: Автоматическое векторное масштабирование
- **Консистентность**: Единый стиль в рамках выбранного набора
