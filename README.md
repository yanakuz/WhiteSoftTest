# WhiteSoftTest
 Test task

Данное консольное приложение на C# восстанавливает изменённые сообщения. Изменённые сообщения (data.JSON) получаются с указанного API с использованием HTTP GET запроса, а данные о произведенных перестановках извлекаются из файла replacement.JSON (bin/release/netcoreapp3.1/replacement.JSON), находящемся внутри проекта. В результате выполнения программы будет сформирован файл result.JSON (bin/release/netcoreapp3.1/result.JSON) с исправленными сообщениями.

Запуск программы осуществляется с помощью Visual Studio. Для начала необходимо открыть файл решения проекта (WhiteSoftTest.sln) и запустить программу. По завершении работы в консоли появится сообщение "Загрузка в файл прошла успешно!". Результат выполнения программы будет записан в result.JSON

