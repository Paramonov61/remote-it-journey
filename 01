from pathlib import Path


# Пути к файлам
input_file = Path("notes/today.md")
output_file = Path("output/progress.md")


# Читаем сегодняшнюю заметку
text = input_file.read_text(encoding="utf-8")


# Создаём папку output, если её ещё нет
output_file.parent.mkdir(exist_ok=True)


# Сохраняем прочитанную заметку как отчёт
output_file.write_text(
    "# Progress\n\n" + text,
    encoding="utf-8"
)


print("Готово! Отчёт создан:", output_file)
