В этой лабораторной работе демонстрируется параллельное умножение двух 100x100 матриц на C# с использованием MPI.  

Программа распределяет вычисления между несколькими процессами MPI, повышая производительность, особенно для больших матриц.
Работа программы включает инициализацию матриц (процесс 0), распределение данных между процессами, параллельное вычисление участков результирующей матрицы и, наконец, сбор результатов (процессом 0).

Для запуска программы необходимо установить MS-MPI. Это можно сделать на официальном сайте Microsoft https://learn.microsoft.com/en-us/message-passing-interface/microsoft-mpi#ms-mpi-source-code

![Uploading image.png…]()
