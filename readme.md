# Зольников В.В., ФИТ-2024-НМ. Методы и инструменты DevOps. ЛР 4
## Подготовка
* Создаем две виртуальных машины.
* Создаем сеть и настраиваем проброс портов

![Pasted image 20251214202830.png](attachments/Pasted%20image%2020251214202830.png)

На обеих машинах настраиваем статический адрес:

![Pasted image 20251214203231.png](attachments/Pasted%20image%2020251214203231.png)

![Pasted image 20251214203239.png](attachments/Pasted%20image%2020251214203239.png)

На второй машине создаем пользователя `runner` и добавляем его в sudoers:

![Pasted image 20251214203336.png](attachments/Pasted%20image%2020251214203336.png)

Создаем ssh ключ:

![Pasted image 20251214203453.png](attachments/Pasted%20image%2020251214203453.png)

## Подготовка плейбука
Создаем и заполняем плейбук и инвентарь:

![Pasted image 20251214203654.png](attachments/Pasted%20image%2020251214203654.png)

![Pasted image 20251214203703.png](attachments/Pasted%20image%2020251214203703.png)

Тестовый прогон:

![Pasted image 20251214203720.png](attachments/Pasted%20image%2020251214203720.png)

Добавляем страницу index:

![Pasted image 20251214203823.png](attachments/Pasted%20image%2020251214203823.png)

## Проверка
Применяем плейбук:

![Pasted image 20251214203842.png](attachments/Pasted%20image%2020251214203842.png)

Проверяем:

![Pasted image 20251214203858.png](attachments/Pasted%20image%2020251214203858.png)
