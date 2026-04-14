## Складна обробка текстових даних засобами оболонки Unix-подібних ОС інтерпретатора команд ОС

### 1 Пошук у системних файлах Git-репозиторію

![photo_5400343483035358629_x](https://github.com/user-attachments/assets/fea0fb60-832a-4b0c-81ec-fbe93cc10e1c)
2.1.1. Рис.1 - Виведення рядка commit-коментаря зі словом Changed з перенаправленням у /dev/null

![photo_5400343483035358629_x](https://github.com/user-attachments/assets/d78db9f3-7f4f-4c7a-817b-be4e58431487)
2.1.2 Рис.2 -Виведення email адреси Git-користувача за допомогою регулярного виразу
### 2 Складний пошук та заміна текстових даних

![photo_5400343483035358789_w](https://github.com/user-attachments/assets/6feacdc2-3601-47cc-9c1a-55a34c0ecc06)
2.2.1. Рис.3 - За допомогою утиліти grep виконано пошук у файлах каталогу рядків, які містять текст із номером варіанту завдання

![photo_5400343483035358900_y](https://github.com/user-attachments/assets/694aff39-5e5d-441d-9ef9-55c5e378802f)
2.2.2. Рис.4- За допомогою grep та sed виведено тільки імена файлів, у яких знайдено потрібний рядок

![photo_5400343483035358910_y](https://github.com/user-attachments/assets/9b2318c1-0476-42f3-b06a-129a8055da45)
2.2.3. Рис.5- Скопійовано файл у каталог Laboratory-work-4 та виконано перехід до нього.

![photo_5400343483035359007_w](https://github.com/user-attachments/assets/ce390534-3af4-46ea-9ad9-799b6cc13271)
2.2.4. Рис.6- Видалено порожні рядки з виводу файлу за допомогою sed

![photo_5400343483035359040_x](https://github.com/user-attachments/assets/601e0580-61c1-47dc-99e9-93efd22dd0f9)
2.2.5. Рис.6- Виведено рядки з <td> та змінено цілі числа на формат з .00 за допомогою sed.

![photo_5400343483035359095_y](https://github.com/user-attachments/assets/491ae38d-0fc7-455e-be7a-f494bc7adc78)
2.2.6. Рис.7- Замінено символи-роздільники на пробіли у рядках <td> за допомогою sed.
### 3 Автоматизована модифікація файлів з текстовими даними

![photo_5400343483035359585_m](https://github.com/user-attachments/assets/7110ecfe-1cd0-47ed-82f6-d45b3fc0682b)
3.2.1. Рис.8- Видалення цифр з кінця тегу <title> у HTML-файлі за допомогою sed.

![photo_5400343483035359586_y](https://github.com/user-attachments/assets/7742fafd-c814-4e9b-85f4-bfa82b4e967c)
3.2.2. Рис.9- Додано новий рядок <h1> після тегу <title> у HTML-файлі за допомогою sed.

![photo_5400343483035359589_m](https://github.com/user-attachments/assets/ad08e70e-8cad-471f-855b-bc47575994db)
3.2.3. Рис.10- Видалення з файлу всі порожні рядки.

![photo_5400343483035359582_x](https://github.com/user-attachments/assets/4578bbee-26e1-4e21-9b92-93fed2b4a1cf)
3.2.4. Рис.11- Об’єднання всіх команд sed у окремий файл та виконання обробки HTML-файлу з читанням команд із цього файлу.
