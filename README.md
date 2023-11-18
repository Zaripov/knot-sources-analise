# knot book analise // Анализ книг о морских узлах
Frequent use of knots in books // Частота употребления узлов в книгах
## data
column description
- **knot_name** — название узла в книге
- **page** — knot page // страница с узлом в книге
- **sourse** — book // название книги или источника
- **theme** — тематика (ручное заполнение)
- **book_type** — справочник, энциклопедия, учебник..(ручная заполнение, слабо заполнено)
- **year** — год издания (extracted from sourse)
- **lang** — book lang // язык книги
- **translated** — from what lang translated // язык книги с которой был сделан перевод
- **knot_count** — knot count in book by group by rows
- **sponsor** — source finder/giver
- **date_add** — add date to dataset

#book count by langs
ru       321
en        15

## Стек технологий
Pandas