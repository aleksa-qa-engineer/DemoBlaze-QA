# TC-005 — Registration with password only
**ID:** TC-005  
**Название:** Registration with password only  
**Предусловие:** Открыта форма регистрации.
## Тестовые данные

- **Username:** пусто
- **Password:** `Test12345!`
## Шаги

1. Нажать **Sign up**.
2. Оставить поле Username пустым.
3. Ввести Password `Test12345!`.
4. Нажать **Sign up**.
## Ожидаемый результат

Система не выполняет регистрацию и предлагает заполнить обязательное поле Username.
## Фактический результат

Отображается сообщение **"Please fill out Username and Password."**  
Регистрация не выполняется.
## Статус

**Passed**
