# virus_identifier
Предсказывание является ли файл вирусом или нет.
Разработать систему машинного обучения, которая по списку статически импортируемых библиотек exe файла предсказывает, является ли этот файл зловредным.
Для выполнения задания предоставляются три выборки: обучающая, валидационная и проверочная. Выборки представлены в виде tsv файлов с тремя колонками – is_virus – является ли файл зловредным: 1=да, 0=нет; filename – имя файла для ознакомления; libs – через запятую перечисление библиотек, статически импортируемых этим файлом (мы использовали библиотеку LIEF для получения списка).
На обучающей выборке – train.tsv – следует тренировать модель машинного обучения.
На валидационной выборке – val.tsv – требуется подсчитать, насколько хорошо модель справляется с файлами, которые она не видела при тренировке.
