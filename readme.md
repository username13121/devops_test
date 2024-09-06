# Тестовое задание. DevOps

## 1. Основы Linux
### Задание: Напишите команды для выполнения следующих задач:

- Создание директории devops_test в домашнем каталоге.
- Создание пустого файла readme.txt в созданной директории.
- Показать текущий путь в терминале.

```bash
mkdir devops_test
cd devops_test
touch readme.txt
pwd
```



## 2. Основы Git
### Задание: Выполните следующие действия с использованием Git:

- Создайте новый локальный репозиторий.
- Создайте файл test.txt, добавьте в него текст “Hello DevOps”.
- Закоммитьте изменения с сообщением “Initial commit”.
- Покажите историю коммитов.

### Решение:
```bash
git init
touch test.txt
echo "Hello DevOps" > test.txt
git add *
git commit -m "Initial commit"
git log
```



## 3. Основы сетевых технологий
### Задание: Ответьте на вопросы:
- Что такое IP-адрес и для чего он используется?
- Назовите основные отличия между протоколами TCP и UDP.

### Решение;
- Уникальный числовой идентификатор, используется для идентификации устройств в сети.
- TCP — надёжный, ориентированный на соединение, с контролем потока, но медленнее из-за проверок и гарантий доставки.
- UDP — быстрый, без установления соединения, без гарантии доставки и контроля потока, подходит для приложений, где потеря данных не критична.



## 4. Программирование (Bash или Python)
### Задание:
- Напишите скрипт на Bash или Python, который выводит числа от 1 до 10.

### Решение:
Bash
```bash
seq 1 10
```

Python
```python
for i in range(1, 11):
    print(i)
```



## 5. Логическое мышление
### Задание: Решите следующую задачу:
- В одном здании находится три лампочки, управляемые тремя выключателями в
другой комнате. Как определить, какой выключатель к какой лампочке относится,
если вы можете зайти в комнату с лампочками только один раз?

### Решение:
- 3 выключателя слева направо: В1, В2, В3
- Включить В1, подождать несколько минут, пока лампочка нагревается. 
- Выключить В1, включить В2.
- Зайти в комнату с лампочками.
- В1: выключенная нагретая лампочка, В2: включенная лампочка, В3: оставшаяся