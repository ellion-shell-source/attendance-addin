Надбудова «Відвідування» для Excel (особисте користування)

1. На github.com створіть публічний репозиторій з назвою attendance-addin
   (акаунт ellion-shell-source). Додайте в нього всі файли з цього архіву:
   Add file -> Upload files: manifest.xml, taskpane.html, icon-16/32/64/80.png.
2. Settings -> Pages -> Source: Deploy from a branch -> main, папка /(root) -> Save.
   Через 1-2 хвилини відкрийте
   https://ellion-shell-source.github.io/attendance-addin/taskpane.html
   Має з'явитися сторінка з повідомленням, що відкривати треба з Excel.
3. У таблиці в Excel для вебу: Основне -> Надбудови -> Передати мою надбудову ->
   виберіть manifest.xml -> Передати. Панель відкриється праворуч,
   а на вкладці «Основне» з'явиться кнопка «Відвідування».

Якщо назва репозиторію або акаунт інші, замініть адресу
https://ellion-shell-source.github.io/attendance-addin у manifest.xml.
Назва аркуша за замовчуванням: «Вч · Євгеній» (змінюється в ⚙ на панелі).
