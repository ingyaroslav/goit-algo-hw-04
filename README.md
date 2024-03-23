## Висновки
Аналізуючи результати емпіричних даних, можна зробити висновок, що алгоритм Timsort, який використовується вбудованим методом sorted() у Python, є надзвичайно ефективним у порівнянні з алгоритмами сортування злиттям та вставками. Це стосується особливо великих наборів даних, де час виконання є критичним показником. Хоча алгоритм сортування злиттям використовує ефективний метод розділення та об'єднання для сортування, а алгоритм вставок працює швидше на відсортованих або майже відсортованих масивах, Timsort поєднує переваги обох, використовуючи оптимізований підхід до сортування. Це зумовлено тим, що Timsort спочатку ділить вхідний масив на менші частини, які сортує вставками, а потім об'єднує ці частини, використовуючи сортування злиттям, що призводить до значного зниження часу виконання. Таким чином, використання Timsort є оптимальним рішенням у більшості випадків для сортування даних в Python.