# Тесты для BooksCollector

## Реализованные тесты

1. **test_add_new_book_add_two_books** — проверка добавления двух книг
2. **test_add_new_book_valid_name** — добавление книги с валидным названием
3. **test_add_new_book_invalid_name** — проверка невалидных названий (параметризация: строка >40 символов, пустая строка)
4. **test_add_new_book_duplicate** — дубликат книги не добавляется
5. **test_set_book_genre** — установка жанра книге
6. **test_set_book_genre_invalid_genre** — нельзя установить несуществующий жанр
7. **test_get_book_genre** — получение жанра по названию книги
8. **test_get_books_with_specific_genre** — получение списка книг определённого жанра
9. **test_get_books_for_children** — получение книг для детей (без возрастного рейтинга)
10. **test_add_book_in_favorites** — добавление книги в избранное
11. **test_delete_book_from_favorites** — удаление книги из избранного