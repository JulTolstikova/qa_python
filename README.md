### Перечень тестов:

1. test_add_new_book_boundary_values - проверка граничных значений метода add_new_book
2. test_add_new_book_same_book_not_added - проверка, что при добавлении двух книг в словарь запись не дублируется
3. test_set_book_genre_for_added_book - проверка того, что метод set_book_genre устанавливает книге жанр
4. test_get_book_genre_not_added_book_none_result - проверка, что нельзя установить жанр, если книга не добавлена
5. test_get_books_with_specific_genre_with_horror_genre - проверка, что метод get_books_with_specific_genre выдает книгу с обозначенным жанром
6. test_get_books_genre_add_to_dictionary - проверк, что метод get_books_genre выводит словарь с добавленным именем и жанром
7. test_get_books_for_children_none_children_books - проверка, что если добавлены только книги с недетским жанром, то возвращается пустой список
8. test_add_book_in_favorites_same_book_not_added - проверка, что нельзя дважды добавить в избранное одну и ту же книгу
9. test_delete_book_from_favorites - проверка удаления добавленной в избранное книги
10. test_get_list_of_favorites_books_add_not_favorite_book - проверка, что если книга не добавлена в избранное, в список избранных не выводится