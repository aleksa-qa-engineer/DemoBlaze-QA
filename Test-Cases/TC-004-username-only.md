# TC-004 — Registration with username only
**ID:** TC-004  
**Название:** Registration with username only  
**Предусловие:** Открыта форма регистрации.
## Тестовые данные

- **Username:** `QA_Test_OnlyUser`
- **Password:** пусто
- ## Шаги

1. Нажать **Sign up**.
2. Ввести Username `QA_Test_OnlyUser`.
3. Оставить поле Password пустым.
4. Нажать **Sign up**.
## Ожидаемый результат

Система не выполняет регистрацию и предлагает заполнить обязательное поле Password.
## Фактический результат

Отображается сообщение **"Please fill out Username and Password."**  
Регистрация не выполняется.
## Статус

**Passed**
