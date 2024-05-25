![Preview](./assets/saimon-in-work.jpg)

# Simon-Bot

Simon-Bot це застосунок, який надає функціонал для керування адресною книгою та ведення нотаток. Застосунок дозволяє створювати, редагувати та видаляти записи контактів, додавати і видаляти номери телефонів та електронні адреси, керувати днями народження та адресами, а також здійснювати пошук записів за різними критеріями. Крім того, ви можете створювати та керувати нотатками, шукати нотатки за тегами та переглядати всі нотатки, відсортовані за датою.

## Керування Адресною Книгою

Створення та керування записами контактів з наступною інформацією:

- [x] Ім'я
- [x] Номери телефонів
- [x] Електронні адреси
- [x] Дні народження
- [x] Адреса
- [x] Редагування та видалення записів контактів
- [x] Додавання, редагування і видалення телефонних номерів та електронної пошти контакту
- [x] Встановлення і видалення днів народження контакту
- [x] Встановлення і видалення адреси контакту
- [x] Пошук записів контактів за пошуковим рядком.
- [x] Список майбутніх днів народження в межах заданої кількості днів.
- [x] Перегляд всіх записи контактів.

## Керування Нотатками

- [x] Створення та керування нотатками з вмістом та тегами.
- [x] Пошук нотатків за тегами.
- [x] Перегляд всіх нотатків, відсортованих за датою.
- [x] Редагування і видалення нотатків.

## Використання

1. Встановіть пакет:

   ```
   pip install simon-bot==0.3
   ```

2. Запустіть застосунок

   ```
     simon-bot
   ```

3. Використовуйте застосунок, дотримуючись вказівок на екрані

## Commands

Застосунок підтримує наступні команди:

- `add [Name]`: Створення нового запису контакту з указаним іменем.
- `edit [Contact_id] [new_Name]`: Редагування назви запису контакту.
- `del [Contact_id]`: Видалення запису контакту
- `add-phone [Contact_id] [Phone]`: Додання телефонного номеру контакту
- `edit-phone [Contact_id] [Phone] [new_Phone]`: Заміна телефонного номеру в контакту
- `del-phone [Contact_id] [Phone]`: Видалення номера телефону з контакту
- `add-email [Contact_id] [Email]`: Додання електронної пошти до контакту.
- `edit-email [Contact_id] [Email] [new_Email]`: Заміна електронної пошти в контакті.
- `del-email [Contact_id] [Email]`: Заміна електронної пошти в контакті.
- `birthday [Contact_id] [Birthday]`: Додавання дня народження до контакту.
- `del-birthday [Contact_id]`: Видалення дня народження від контакту.
- `address [Contact_id] [Address]`: Додання адреси до контакту.
- `del-address [Contact_id]`: Видалення адреси від контакту.
- `find [searchstring]`: Пошук записів контактів на основі пошукового рядка
- `help`: Відображення списку доступних команд.
- `note`: Додання нотатки до блокнота
- `all-notes`: Список усіх приміток
- `edit-note [Note_id] [Note]`: Редагування тексту примітки
- `del-note [Note_id]`: Видалення нотатки із блокноту
- `add-tag [Note_id] [Tag]`: Додання тегу до нотатки
- `del-tag [Note_id] [Tag]`: Видалення тегу від нотатки
- `find-notes [searchstring]`: Список всіх нотаток із даними рядка пошуку в нотатках і тегах. Пошуковий рядок має містити мінімум 2 символи
- `find-tags [searchstring]`: Перелік всіх нотатків з даними рядка пошуку в тегах. Пошуковий рядок має містити мінімум 2 символи
- `sort-tag`: Список усіх нотаток, упорядкованих за кількістю тегів
- `next-birthdays [int]`: Відображення майбутніх днів народження протягом вказаної кількості днів.
- `all`: Перелік всіх записів контактів.
- `close or exit`: Виход з програми.

## Development team

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AM1007)
  Андрій Мотько **Team Lead** - розробка додатку, код-рев'ю

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SvitlanaSavchenko)
  Світлана Савченко **Scrum Master** - розробка додатку

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vademandr)
  Вадім Андрющенко **Front End Developer** - розробка додатку

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TiZorii)
  Тетяна Зорій **Front End Developer** - розробка додатку

- [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/andrei-81)
  Андрій Гордійчук **Front End Developer** - розробка додатку
