#  Команда grep
'''
Создайте файл fruits.txt с названиями фруктов (например, Apple, Banana, Orange, Apricot) и выведите строки, содержащие букву a.
Найдите в файле fruits.txt строки, которые начинаются с A.
Подсчитайте, сколько строк в файле содержат слово Apple.
Выведите строки из файла fruits.txt, которые не содержат букву e.
Найдите в текущей директории все файлы с расширением .txt и выведите строки, содержащие слово test.
'''
#  Команда tail
'''
Создайте файл log.txt с 15 строками текста и выведите последние 5 строк.
Выведите все строки файла log.txt, начиная с 10-й.
Сохраните последние 3 строки файла log.txt в новый файл end_log.txt.
Выведите последние 7 строк файла /var/log/syslog (если доступно).
Используя команду tail, следите за изменениями в файле log.txt в реальном времени.
'''
#  Команда head
'''
Создайте файл list.txt с 20 строками чисел и выведите первые 4 строки.
Выведите первые 10 строк файла /etc/passwd (если доступно).
Сохраните первые 6 строк файла list.txt в новый файл top_list.txt.
Выведите первые 3 строки из вывода команды ls -l.
Создайте файл с текстом и выведите только первую строку.
'''
#  Команда cut '''
Создайте файл users.txt с данными (Имя Возраст Страна) и выведите только имена.
Из файла users.txt извлеките только возраст (второе поле).
Выведите первые два поля из файла /etc/passwd, разделённых :.
Сохраните страны (третье поле) из users.txt в файл countries.txt.
Из вывода команды date извлеките только время (например, часы и минуты).
'''
#  Команда ps
Выведите список всех запущенных процессов для текущего пользователя.
Найдите PID процесса с именем bash.
Выведите только команды запущенных процессов без заголовков.
Подсчитайте, сколько процессов запущено в системе.
Выведите информацию о процессе с самым высоким использованием CPU.

#  Команда cp
Скопируйте файл test.txt в файл test_copy.txt.
Скопируйте директорию folder1 в folder2 со всем содержимым.
Скопируйте все файлы с расширением .txt в директорию backup.
Скопируйте файл data.txt в /tmp с сохранением исходных прав доступа.
Создайте копию файла log.txt с именем log_$(date +%Y%m%d).txt.

#  Команда less
Откройте файл /var/log/syslog и найдите строку с error.
Просмотрите файл readme.txt и перейдите к концу файла.
Откройте файл long_list.txt и выведите номер 50-й строки.
Используйте less для просмотра вывода команды ls -l.
Откройте файл text.txt и найдите все вхождения слова hello.

# Команда nl
Создайте файл items.txt с 5 строками и пронумеруйте их.
Пронумеруйте строки файла items.txt, пропуская пустые строки.
Выведите пронумерованные строки из файла /etc/passwd.
Сохраните пронумерованный текст из items.txt в numbered_items.txt.
Пронумеруйте строки вывода команды ps aux.

#  Команда find
Найдите все файлы с расширением .txt в текущей директории.
Найдите все файлы, изменённые за последние 7 дней.
Найдите все пустые файлы в директории /tmp.
Найдите файлы размером больше 1 МБ в текущей директории.
Найдите все директории с именем backup в /home.

#  Команда du
Выведите размер текущей директории в читаемом формате.
Подсчитайте размер всех файлов с расширением .txt.
Выведите размер директории /var в килобайтах.
Найдите 5 самых больших поддиректорий в /home.
Сохраните размер текущей директории в файл size.txt.

#  Команда df
Выведите информацию о свободном месте на всех дисках.
Выведите только процент использования диска /.
Сохраните данные о дисках в файл disk_usage.txt.
Выведите информацию о дисках в мегабайтах.
Найдите диск с наименьшим количеством свободного места.

#  Команда tar
Создайте архив backup.tar из директории data.
Распакуйте архив backup.tar в директорию extracted.
Создайте сжатый архив backup.tar.gz из файлов .txt.
Выведите список содержимого архива backup.tar без распаковки.
Добавьте файл new.txt в существующий архив backup.tar.

#  Команда zip
Создайте архив files.zip из всех .txt файлов.
Распакуйте архив files.zip в директорию unzipped.
Добавьте файл extra.txt в существующий архив files.zip.
Выведите список файлов в files.zip без распаковки.
Создайте защищённый паролем архив secure.zip из директории secret.

#  Команда ps -aux
Выведите все процессы в системе с полной информацией.
Найдите процессы, запущенные пользователем root.
Подсчитайте количество процессов с именем python.
Выведите PID и команду для всех процессов bash.
Сохраните вывод ps -aux в файл processes.txt.

#  Команда kill
Найдите PID процесса sleep и завершите его.
Запустите sleep 100 в фоновом режиме и завершите его по PID.
Завершите все процессы с именем bash (осторожно!).
Убейте процесс с самым высоким использованием памяти.
Завершите процесс по его PID с сигналом SIGKILL.

#  Команда last
Выведите последние 5 записей о входах в систему.
Найдите все входы пользователя user1.
Подсчитайте, сколько раз входил текущий пользователь.
Выведите только IP-адреса из вывода last.
Сохраните историю входов в файл login_history.txt.

#  Команда jobs
Запустите sleep 60 в фоновом режиме и выведите список заданий.
Запустите два фоновых процесса и проверьте их статус.
Остановите процесс sleep 100 и выведите список заданий.
Перезапустите остановленное задание в фоне.
Завершите все фоновые задания.

#  Команда bg
Запустите sleep 50 и остановите его, затем переведите в фон.
Остановите два процесса и переведите их в фоновый режим.
Проверьте, какие процессы работают в фоне после bg.
Запустите cat и переведите его в фон.
Переведите в фон последний остановленный процесс.

#  Команда fg
Запустите sleep 30 в фоне и выведите его на передний план.
Остановите процесс nano и верните его на передний план.
Запустите два фоновых процесса и выведите первый на передний план.
Переведите последний фоновый процесс на передний план.
Проверьте, что происходит с fg, если нет фоновых задач.

#  Команда chmod
Создайте файл script.sh и дайте ему права на выполнение.
Установите права чтения и записи для владельца на data.txt.
Дайте всем пользователям права чтения на public.txt.
Уберите права выполнения у файла script.sh.
Установите права 755 на директорию tools.

#  Команда ping
Проверьте доступность сайта google.com с 5 запросами.
Отправьте 10 пингов на локальный адрес 127.0.0.1.
Сохраните результат пинга 8.8.8.8 в файл ping_log.txt.
Выведите только время ответа из пинга github.com.
Проверьте доступность хоста example.com без вывода лишней информации.

#  Команда traceroute
Проследите маршрут до google.com.
Сохраните маршрут до 8.8.8.8 в файл route.txt.
Выведите маршрут до github.com с числовыми IP без имён хостов.
Ограничьте трассировку до facebook.com 10 хопами.
Проверьте маршрут до локального адреса 127.0.0.1.

#  Команда nmap
Просканируйте открытые порты на localhost.
Выполните быстрое сканирование хоста 192.168.1.1.
Найдите все активные хосты в сети 192.168.1.0/24.
Сохраните результаты сканирования scanme.nmap.org в файл nmap_result.txt.
Проверьте, какие сервисы работают на портах 80 и 443 на example.com.

#  Команда netstat
Выведите все активные сетевые соединения.
Покажите только TCP-соединения на вашем компьютере.
Подсчитайте количество открытых портов.
Выведите список прослушиваемых портов.
Сохраните статистику сетевых соединений в файл netstat_log.txt.

#  Команда nslookup
Узнайте IP-адрес домена google.com.
Найдите почтовые серверы для example.com.
Выполните обратный DNS-запрос для 8.8.8.8.
Сохраните результат запроса для github.com в файл dns.txt.
Проверьте NS-записи для домена facebook.com.

#  Команда curl
Скачайте главную страницу example.com и выведите её в терминал.
Сохраните содержимое http://httpbin.org/get в файл response.txt.
Выполните GET-запрос к https://api.github.com и выведите заголовки.
Отправьте POST-запрос с данными name=test на http://httpbin.org/post.
Скачайте файл https://example.com/file.txt в downloaded.txt.



-------------
#  Команда grep
Создайте файл animals.txt с названиями животных и найдите строки, содержащие cat.
Выведите строки из animals.txt, начинающиеся с d.
Подсчитайте, сколько строк в файле содержат букву e.
Найдите строки в animals.txt, которые не содержат dog.
Выведите строки из /etc/passwd, содержащие root (если доступно).
Найдите все файлы .txt в текущей директории и выведите строки с числом 42.
Выведите строки из файла log.txt, заканчивающиеся на точку.
Найдите строки в data.txt, содержащие хотя бы одну цифру.
Подсчитайте вхождения слова error в /var/log/syslog (если доступно).
Выведите строки из notes.txt, содержащие слово TODO без учёта регистра.

#  Команда tail
Создайте файл records.txt с 20 строками текста и выведите последние 8 строк.
Выведите последние 3 строки файла /var/log/syslog (если доступно).
Сохраните последние 5 строк records.txt в файл end_records.txt.
Выведите все строки файла records.txt, начиная с 15-й.
Следите за изменениями в файле access.log в реальном времени.
Выведите последние 10 строк вывода команды ps aux.
Сохраните последние 2 строки файла data.txt в last_data.txt.
Выведите последние 4 строки из /etc/passwd (если доступно).
Создайте файл numbers.txt с числами 1-30 и выведите последние 7 строк.
Выведите последние 6 строк файла history.txt и подсчитайте их количество.

#  Команда head
Создайте файл items.txt с 25 строками и выведите первые 6 строк.
Выведите первые 5 строк файла /etc/passwd (если доступно).
Сохраните первые 10 строк items.txt в файл top_items.txt.
Выведите первые 3 строки вывода команды ls -l.
Создайте файл log.txt и выведите только первую строку.
Выведите первые 8 строк файла /var/log/syslog (если доступно).
Сохраните первые 4 строки data.txt в start_data.txt.
Выведите первые 7 строк из файла numbers.txt с числами 1-20.
Выведите первые 2 строки вывода команды who.
Создайте файл text.txt и выведите первые 5 строк в файл head_text.txt.

#  Команда cut
Создайте файл people.txt (Имя Возраст Город) и выведите только имена.
Извлеките возраст (второе поле) из файла people.txt.
Выведите первые два поля из /etc/passwd, разделённых :.
Сохраните города (третье поле) из people.txt в cities.txt.
Из вывода date извлеките только день недели.
Выведите первые 10 символов каждой строки из log.txt.
Из файла data.txt (с полями через табуляцию) извлеките второе поле.
Выведите третье поле из вывода ls -l (права доступа).
Сохраните первые 5 символов каждой строки notes.txt в short_notes.txt.
Извлеките имя пользователя (первое поле) из вывода who.

#  Команда ps
Выведите все процессы текущего пользователя.
Найдите PID процесса с именем firefox.
Выведите только команды запущенных процессов.
Подсчитайте общее количество процессов в системе.
Выведите процессы, использующие более 10% CPU.
Найдите все процессы с именем python.
Выведите информацию о процессе с PID 1.
Сохраните список процессов в файл ps_output.txt.
Выведите только PID и время запуска для процессов bash.
Найдите процесс с самым долгим временем работы.

#  Команда cp
Скопируйте файл source.txt в source_copy.txt.
Скопируйте директорию docs в docs_backup.
Скопируйте все .log файлы в директорию logs.
Скопируйте файл config.txt в /tmp с сохранением прав.
Создайте копию data.txt с именем data_$(date +%H%M).txt.
Скопируйте файл readme.txt в backup/readme.txt, создав директорию.
Скопируйте все файлы из src в dest, сохраняя структуру.
Скопируйте файл test.txt в test.bak только если он новее.
Скопируйте /etc/hosts в текущую директорию (если доступно).
Скопируйте все .txt файлы в archive с подтверждением перезаписи.

#  Команда less
Откройте файл /var/log/syslog и найдите слово fail.
Просмотрите файл manual.txt и перейдите к 100-й строке.
Откройте data.txt и найдите последнее вхождение error.
Используйте less для просмотра вывода ps aux.
Откройте файл long.txt и прокрутите до конца.
Найдите все вхождения слова test в notes.txt.
Откройте файл log.txt и перейдите на 50% файла.
Просмотрите файл config.txt и выйдите без изменений.
Откройте /etc/passwd и найдите строку с root.
Используйте less для просмотра history.txt с номерами строк.

#  Команда nl
Пронумеруйте строки файла list.txt с 5 строками.
Пронумеруйте строки list.txt, пропуская пустые строки.
Выведите пронумерованные строки из /etc/passwd.
Сохраните пронумерованный текст data.txt в numbered_data.txt.
Пронумеруйте строки вывода команды ls -l.
Создайте файл text.txt с пустыми строками и пронумеруйте только заполненные.
Выведите пронумерованные строки файла log.txt с шагом 2.
Пронумеруйте строки numbers.txt с ведущими нулями.
Сохраните пронумерованный вывод who в файл who_numbered.txt.
Пронумеруйте строки файла readme.txt с пользовательским разделителем.

#  Команда find
Найдите все .txt файлы в текущей директории.
Найдите файлы, изменённые за последние 3 дня.
Найдите все пустые файлы в /tmp.
Найдите файлы размером более 5 МБ в /home.
Найдите все директории с именем test в текущей директории.
Найдите все .log файлы, созданные более 30 дней назад.
Найдите файлы с правами 777 в /var.
Найдите все скрытые файлы (начинающиеся с .) в текущей директории.
Найдите все исполняемые файлы в /bin.
Найдите файлы с именем backup (регистр не важен) в /etc.

#  Команда du
Выведите размер текущей директории в читаемом формате.
Подсчитайте размер всех .txt файлов в текущей директории.
Выведите размер /var в килобайтах.
Найдите 10 самых больших поддиректорий в /home.
Сохраните размер директории logs в файл logs_size.txt.
Выведите общий размер всех файлов в /tmp.
Подсчитайте размер директории data с учётом скрытых файлов.
Выведите размер каждой поддиректории в текущей директории.
Найдите размер всех .log файлов в /var/log.
Выведите максимальную глубину вложенности в /usr.

#  Команда df
Выведите информацию о всех дисках в читаемом формате.
Выведите процент использования диска /.
Сохраните данные о дисках в файл disk_info.txt.
Выведите информацию о дисках в гигабайтах.
Найдите диск с наибольшим количеством свободного места.
Выведите только точки монтирования всех дисков.
Подсчитайте общее количество доступных блоков.
Выведите информацию только для диска /home.
Сохраните процент использования всех дисков в usage.txt.
Выведите диски с менее 20% свободного места.

#  Команда tar
Создайте архив data.tar из директории files.
Распакуйте архив data.tar в директорию extracted.
Создайте сжатый архив data.tar.gz из .txt файлов.
Выведите содержимое data.tar без распаковки.
Добавьте файл new.txt в архив data.tar.
Создайте архив backup.tar из /etc с исключением .conf.
Распакуйте только один файл из data.tar.gz.
Создайте сжатый архив logs.tar.bz2 из директории logs.
Проверьте целостность архива data.tar.gz.
Создайте архив all.tar из текущей директории с максимальным сжатием.

#  Команда zip
Создайте архив docs.zip из всех .txt файлов.
Распакуйте docs.zip в директорию unzipped.
Добавьте файл extra.txt в архив docs.zip.
Выведите содержимое docs.zip без распаковки.
Создайте защищённый паролем архив secure.zip из secret.
Создайте архив backup.zip из директории data с сжатием.
Распакуйте только один файл из docs.zip.
Обновите docs.zip, заменив старый readme.txt.
Создайте архив all.zip из текущей директории рекурсивно.
Проверьте архив docs.zip на ошибки.

#  Команда ps -aux
Выведите все процессы системы с полной информацией.
Найдите процессы пользователя root.
Подсчитайте количество процессов bash.
Выведите PID и команду для процессов python.
Сохраните вывод в файл all_processes.txt.
Найдите процессы с использованием памяти более 5%.
Выведите только процессы, запущенные более часа назад.
Найдите самый ресурсоёмкий процесс по CPU.
Выведите процессы с сортировкой по PID.
Подсчитайте общее количество процессов пользователя.

#  Команда kill
Запустите sleep 100 и завершите его по PID.
Найдите PID процесса firefox и завершите его.
Завершите все процессы python (осторожно!).
Убейте процесс с PID 1000 с сигналом SIGTERM.
Завершите процесс sleep с сигналом SIGKILL.
Остановите фоновый процесс cat и завершите его.
Найдите процесс с высоким CPU и завершите его.
Завершите последний запущенный процесс bash.
Убейте процесс по имени с подтверждением.
Завершите все процессы, связанные с test.sh.

#  Команда last
Выведите последние 10 входов в систему.
Найдите все входы пользователя admin.
Подсчитайте входы текущего пользователя.
Выведите только IP-адреса из last.
Сохраните историю входов в last_log.txt.
Найдите входы с определённого терминала (например, tty1).
Выведите только даты и время входов.
Найдите последний вход пользователя root.
Подсчитайте входы с конкретного IP.
Выведите входы за последний месяц.

#  Команда jobs
Запустите sleep 60 в фоне и выведите список заданий.
Остановите sleep 100 и проверьте статус заданий.
Запустите три фоновых процесса и выведите их список.
Перезапустите последнее остановленное задание.
Завершите все активные задания.
Запустите nano в фоне и проверьте .ConcurrentModificationExceptionjobs.
Остановите два процесса и выведите их номера.
Проверьте статус заданий после завершения одного.
Запустите cat в фоне и выведите его номер.
Остановите и перезапустите задание с sleep.

#  Команда bg
Запустите sleep 50 и переведите его в фон после остановки.
Остановите nano и переведите в фоновый режим.
Запустите два процесса и переведите их в фон.
Переведите последний остановленный процесс в фон.
Проверьте статус фоновых процессов после bg.
Остановите cat и запустите его в фоне.
Переведите sleep 200 в фон после Ctrl+Z.
Запустите python и переведите в фон.
Переведите все остановленные процессы в фон.
Проверьте, что происходит с bg без остановленных задач.

# Команда fg
Запустите sleep 30 в фоне и верните на передний план.
Остановите nano и верните его на передний план.
Запустите два фоновых процесса и верните первый.
Переведите последний фоновый процесс на передний план.
Проверьте поведение fg без фоновых задач.
Запустите cat в фоне и верните его.
Остановите sleep 100 и верните на передний план.
Запустите python в фоне и верните его.
Верните фоновый процесс с номером 2.
Проверьте, что происходит с fg после завершения задачи.

# Команда chmod
Дайте файлу script.sh права на выполнение.
Установите права чтения и записи для владельца data.txt.
Дайте всем права чтения на public.txt.
Уберите права выполнения у script.sh.
Установите права 644 на файл config.txt.
Дайте директории tools права 755.
Установите права только для группы на group_file.txt.
Сделайте файл secret.txt доступным только владельцу.
Дайте права записи всем на shared.txt.
Установите права 700 на директорию private.

# Команда ping
Проверьте доступность google.com с 10 запросами.
Отправьте 5 пингов на 127.0.0.1.
Сохраните результат пинга 8.8.8.8 в ping_result.txt.
Выведите только время ответа от github.com.
Проверьте example.com с 20 запросами.
Пинганите 192.168.1.1 с выводом в реальном времени.
Ограничьте пинг facebook.com до 3 секунд.
Проверьте доступность localhost с минимальным выводом.
Сохраните пинг 1.1.1.1 с датой в ping_log.txt.
Выведите статистику пинга cloudflare.com.

# Команда traceroute
Проследите маршрут до google.com.
Сохраните маршрут до 8.8.8.8 в traceroute.txt.
Выведите маршрут до github.com без имён хостов.
Ограничьте трассировку facebook.com до 15 хопов.
Проверьте маршрут до 127.0.0.1.
Выведите маршрут до 1.1.1.1 с числовыми IP.
Сохраните маршрут до example.com с временем ответа.
Проверьте маршрут до локальной сети 192.168.1.1.
Ограничьте трассировку amazon.com до 5 секунд.
Выведите маршрут до cloudflare.com с максимальной детализацией.

# Команда nmap
Просканируйте порты на localhost.
Выполните быстрое сканирование 192.168.1.1.
Найдите активные хосты в 192.168.1.0/24.
Сохраните сканирование scanme.nmap.org в nmap_scan.txt.
Проверьте порты 80 и 443 на example.com.
Выполните полное сканирование 127.0.0.1.
Найдите открытые порты на github.com.
Сканируйте 192.168.0.0/24 с выводом версий служб.
Проверьте только TCP-порты на facebook.com.
Сохраните агрессивное сканирование localhost в detailed_scan.txt.

# Команда netstat
Выведите все активные соединения.
Покажите только TCP-соединения.
Подсчитайте открытые порты.
Выведите прослушиваемые порты.
Сохраните статистику в netstat_log.txt.
Найдите соединения на порту 80.
Выведите только UDP-соединения.
Покажите маршруты сети.
Выведите статистику по протоколам.
Найдите процессы, использующие порт 22.

# Команда nslookup
Узнайте IP-адрес google.com.
Найдите MX-записи для example.com.
Выполните обратный запрос для 8.8.8.8.
Сохраните результат для github.com в dns_result.txt.
Проверьте NS-записи для facebook.com.
Узнайте SOA-запись для cloudflare.com.
Найдите IP для localhost.
Проверьте CNAME для www.google.com.
Выполните запрос к серверу 1.1.1.1 для amazon.com.
Сохраните все записи для example.org в dns_full.txt.

# Команда curl
Скачайте страницу example.com и выведите её.
Сохраните http://httpbin.org/get в get_response.txt.
Выведите заголовки https://api.github.com.
Отправьте POST-запрос с name=John на http://httpbin.org/post.
Скачайте https://example.com/file.txt в file.txt.
Выведите только код ответа от google.com.
Скачайте изображение с https://example.com/image.jpg.
Отправьте запрос с пользовательским заголовком на httpbin.org.
Сохраните JSON с https://api.ipify.org?format=json в ip.json.
Выполните запрос к facebook.com с тайм-аутом 5 секунд.


# Command grep
Create a file animals.txt with animal names and find lines containing cat.
Display lines from animals.txt that start with d.
Count how many lines in the file contain the letter e.
Find lines in animals.txt that do not contain dog.
Display lines from /etc/passwd containing root (if available).
Find all .txt files in the current directory and display lines with the number 42.
Display lines from log.txt that end with a period.
Find lines in data.txt that contain at least one digit.
Count occurrences of the word error in /var/log/syslog (if available).
Display lines from notes.txt containing the word TODO, case-insensitive.
# Command tail
Create a file records.txt with 20 lines of text and display the last 8 lines.
Display the last 3 lines of the file /var/log/syslog (if available).
Save the last 5 lines of records.txt to a file end_records.txt.
Display all lines from records.txt starting from the 15th line.
Monitor changes in the file access.log in real time.
Display the last 10 lines of the output of the ps aux command.
Save the last 2 lines of data.txt to last_data.txt.
Display the last 4 lines from /etc/passwd (if available).
Create a file numbers.txt with numbers 1-30 and display the last 7 lines.
Display the last 6 lines of history.txt and count them.
# Command head
Create a file items.txt with 25 lines and display the first 6 lines.
Display the first 5 lines of /etc/passwd (if available).
Save the first 10 lines of items.txt to top_items.txt.
Display the first 3 lines of the output of ls -l.
Create a file log.txt and display only the first line.
Display the first 8 lines of /var/log/syslog (if available).
Save the first 4 lines of data.txt to start_data.txt.
Display the first 7 lines of numbers.txt with numbers 1-20.
Display the first 2 lines of the output of who.
Create a file text.txt and save the first 5 lines to head_text.txt.
# Command cut
Create a file people.txt (Name Age City) and display only the names.
Extract the age (second field) from people.txt.
Display the first two fields from /etc/passwd, separated by :.
Save the cities (third field) from people.txt to cities.txt.
Extract only the day of the week from the output of date.
Display the first 10 characters of each line from log.txt.
Extract the second field from data.txt (fields separated by tabs).
Display the third field from the output of ls -l (permissions).
Save the first 5 characters of each line from notes.txt to short_notes.txt.
Extract the username (first field) from the output of who.
# Command ps
Display all processes for the current user.
Find the PID of a process named firefox.
Display only the commands of running processes.
Count the total number of processes in the system.
Display processes using more than 10% CPU.
Find all processes named python.
Display information about the process with PID 1.
Save the list of processes to ps_output.txt.
Display only PID and start time for bash processes.
Find the process with the longest runtime.
# Command cp
Copy the file source.txt to source_copy.txt.
Copy the directory docs to docs_backup.
Copy all .log files to the logs directory.
Copy config.txt to /tmp while preserving permissions.
Create a copy of data.txt named data_$(date +%H%M).txt.
Copy readme.txt to backup/readme.txt, creating the directory if needed.
Copy all files from src to dest, preserving structure.
Copy test.txt to test.bak only if it’s newer.
Copy /etc/hosts to the current directory (if available).
Copy all .txt files to archive with overwrite confirmation.
# Command less
Open /var/log/syslog and search for the word fail.
View manual.txt and go to the 100th line.
Open data.txt and find the last occurrence of error.
Use less to view the output of ps aux.
Open long.txt and scroll to the end.
Find all occurrences of test in notes.txt.
Open log.txt and go to 50% of the file.
View config.txt and exit without changes.
Open /etc/passwd and find the line with root.
Use less to view history.txt with line numbers.
# Command nl
Number the lines of a file list.txt with 5 lines.
Number the lines of list.txt, skipping empty lines.
Display numbered lines from /etc/passwd.
Save the numbered text from data.txt to numbered_data.txt.
Number the lines of the output of ls -l.
Create a file text.txt with empty lines and number only the filled ones.
Display numbered lines from log.txt with a step of 2.
Number the lines of numbers.txt with leading zeros.
Save the numbered output of who to who_numbered.txt.
Number the lines of readme.txt with a custom separator.
# Command find
Find all .txt files in the current directory.
Find files modified in the last 3 days.
Find all empty files in /tmp.
Find files larger than 5 MB in /home.
Find all directories named test in the current directory.
Find all .log files created more than 30 days ago.
Find files with 777 permissions in /var.
Find all hidden files (starting with .) in the current directory.
Find all executable files in /bin.
Find files named backup (case-insensitive) in /etc.
# Command du
Display the size of the current directory in a human-readable format.
Calculate the size of all .txt files in the current directory.
Display the size of /var in kilobytes.
Find the 10 largest subdirectories in /home.
Save the size of the logs directory to logs_size.txt.
Display the total size of all files in /tmp.
Calculate the size of the data directory, including hidden files.
Display the size of each subdirectory in the current directory.
Find the size of all .log files in /var/log.
Display the maximum depth of nesting in /usr.
# Command df
Display information about all disks in a human-readable format.
Display the percentage of usage for the / disk.
Save disk data to disk_info.txt.
Display disk information in gigabytes.
Find the disk with the most free space.
Display only the mount points of all disks.
Count the total number of available blocks.
Display information only for the /home disk.
Save the usage percentage of all disks to usage.txt.
Display disks with less than 20% free space.
# Command tar
Create an archive data.tar from the files directory.
Extract data.tar to the extracted directory.
Create a compressed archive data.tar.gz from .txt files.
Display the contents of data.tar without extracting.
Add the file new.txt to the data.tar archive.
Create an archive backup.tar from /etc, excluding .conf files.
Extract only one file from data.tar.gz.
Create a compressed archive logs.tar.bz2 from the logs directory.
Verify the integrity of the data.tar.gz archive.
Create an archive all.tar from the current directory with maximum compression.
# Command zip
Create an archive docs.zip from all .txt files.
Extract docs.zip to the unzipped directory.
Add the file extra.txt to the docs.zip archive.
Display the contents of docs.zip without extracting.
Create a password-protected archive secure.zip from the secret directory.
Create an archive backup.zip from the data directory with compression.
Extract only one file from docs.zip.
Update docs.zip by replacing the old readme.txt.
Create an archive all.zip from the current directory recursively.
Check docs.zip for errors.
# Command ps -aux
Display all system processes with full details.
Find processes run by the root user.
Count the number of bash processes.
Display PID and command for python processes.
Save the output to all_processes.txt.
Find processes using more than 5% memory.
Display only processes running for over an hour.
Find the most CPU-intensive process.
Display processes sorted by PID.
Count the total number of processes for the current user.
# Command kill
Start sleep 100 and terminate it by PID.
Find the PID of firefox and terminate it.
Terminate all python processes (use caution!).
Kill the process with PID 1000 using SIGTERM.
Terminate a sleep process with SIGKILL.
Stop a background cat process and terminate it.
Find a high-CPU process and kill it.
Terminate the most recently started bash process.
Kill a process by name with confirmation.
Terminate all processes related to test.sh.
# Command last
Display the last 10 system logins.
Find all logins by the admin user.
Count the logins of the current user.
Display only IP addresses from last.
Save login history to last_log.txt.
Find logins from a specific terminal (e.g., tty1).
Display only dates and times of logins.
Find the last login of the root user.
Count logins from a specific IP.
Display logins from the last month.
# Command jobs
Start sleep 60 in the background and list jobs.
Stop sleep 100 and check job status.
Start three background processes and list them.
Restart the last stopped job.
Terminate all active jobs.
Start nano in the background and check jobs.
Stop two processes and display their job numbers.
Check job status after terminating one.
Start cat in the background and display its job number.
Stop and restart a sleep job.
# Command bg
Start sleep 50, stop it, and move it to the background.
Stop nano and move it to the background.
Start two processes and move them to the background.
Move the last stopped process to the background.
Check the status of background processes after bg.
Stop cat and run it in the background.
Move sleep 200 to the background after Ctrl+Z.
Start python and move it to the background.
Move all stopped processes to the background.
Check what happens with bg when there are no stopped tasks.
# Command fg
Start sleep 30 in the background and bring it to the foreground.
Stop nano and bring it to the foreground.
Start two background processes and bring the first one to the foreground.
Bring the last background process to the foreground.
Check the behavior of fg with no background tasks.
Start cat in the background and bring it to the foreground.
Stop sleep 100 and bring it to the foreground.
Start python in the background and bring it to the foreground.
Bring the background job with number 2 to the foreground.
Check what happens with fg after a task completes.
# Command chmod
Make the file script.sh executable.
Set read and write permissions for the owner of data.txt.
Grant read permissions to everyone for public.txt.
Remove execute permissions from script.sh.
Set permissions to 644 on config.txt.
Grant 755 permissions to the tools directory.
Set permissions only for the group on group_file.txt.
Make secret.txt accessible only to the owner.
Grant write permissions to everyone for shared.txt.
Set permissions to 700 on the private directory.
# Command ping
Check the availability of google.com with 10 requests.
Send 5 pings to 127.0.0.1.
Save the result of pinging 8.8.8.8 to ping_result.txt.
Display only the response time from github.com.
Check example.com with 20 requests.
Ping 192.168.1.1 with real-time output.
Limit the ping to facebook.com to 3 seconds.
Check the availability of localhost with minimal output.
Save the ping of 1.1.1.1 with the date to ping_log.txt.
Display ping statistics for cloudflare.com.
# Command traceroute
Trace the route to google.com.
Save the route to 8.8.8.8 to traceroute.txt.
Display the route to github.com without hostnames.
Limit the trace to facebook.com to 15 hops.
Check the route to 127.0.0.1.
Display the route to 1.1.1.1 with numeric IPs.
Save the route to example.com with response times.
Check the route to the local network 192.168.1.1.
Limit the trace to amazon.com to 5 seconds.
Display the route to cloudflare.com with maximum detail.
# Command nmap
Scan ports on localhost.
Perform a quick scan of 192.168.1.1.
Find active hosts in 192.168.1.0/24.
Save the scan of scanme.nmap.org to nmap_scan.txt.
Check ports 80 and 443 on example.com.
Perform a full scan of 127.0.0.1.
Find open ports on github.com.
Scan 192.168.0.0/24 with service version output.
Check only TCP ports on facebook.com.
Save an aggressive scan of localhost to detailed_scan.txt.
# Command netstat
Display all active connections.
Show only TCP connections.
Count the number of open ports.
Display listening ports.
Save statistics to netstat_log.txt.
Find connections on port 80.
Display only UDP connections.
Show network routes.
Display protocol statistics.
Find processes using port 22.
# Command nslookup
Find the IP address of google.com.
Find MX records for example.com.
Perform a reverse lookup for 8.8.8.8.
Save the result for github.com to dns_result.txt.
Check NS records for facebook.com.
Find the SOA record for cloudflare.com.
Find the IP for localhost.
Check the CNAME for www.google.com.
Query 1.1.1.1 for amazon.com.
Save all records for example.org to dns_full.txt.
# Command curl
Download the page from example.com and display it.
Save http://httpbin.org/get to get_response.txt.
Display headers from https://api.github.com.
Send a POST request with name=John to http://httpbin.org/post.
Download https://example.com/file.txt to file.txt.
Display only the response code from google.com.
Download an image from https://example.com/image.jpg.
Send a request with a custom header to httpbin.org.
Save JSON from https://api.ipify.org?format=json to ip.json.
Perform a request to facebook.com with a 5-second timeout.
# Command
Create two files, names.txt (with names) and ages.txt (with ages), and merge them side by side into a single output.
Merge the contents of file1.txt and file2.txt into a new file combined.txt.
Combine three files (a.txt, b.txt, c.txt) with a tab delimiter and display the result.
Merge the lines of list.txt with itself, doubling each line side by side.
Create a file data.txt with numbers and merge it with labels.txt using a comma as the delimiter.
Merge the output of ls -l and who side by side and save it to output.txt.
Combine two files, fruits.txt and colors.txt, with a custom delimiter |.
Merge all .txt files in the current directory into a single output with spaces between columns.
Create a file scores.txt with numbers and merge it with names.txt, replacing missing values with -.
Merge the contents of log1.txt and log2.txt serially (one after the other) instead of side by side.
# Command tr
Create a file text.txt with mixed-case text and convert all characters to uppercase.
Convert all lowercase letters in data.txt to lowercase and save the result to lower_data.txt.
Replace all spaces in notes.txt with underscores.
Delete all digits from the file log.txt and display the result.
Replace all occurrences of a with A in words.txt.
Remove all vowels (a, e, i, o, u) from sentence.txt.
Translate tabs to spaces in table.txt and save the output to spaced_table.txt.
Convert the output of echo "Hello, World!" by replacing commas with semicolons.
Remove all punctuation marks from story.txt and display the cleaned text.
Squeeze multiple consecutive spaces in messy.txt into a single space and save to clean.txt.

# Command sort
Create a file names.txt with a list of names and sort them alphabetically.
Sort the lines of numbers.txt (containing integers) in numerical order.
Sort the contents of data.txt in reverse order and display the result.
Create a file scores.txt with names and scores (e.g., "Alice 85") and sort by the second field numerically.
Sort all .txt files in the current directory alphabetically and save the combined output to all_sorted.txt.
Sort the lines of log.txt by ignoring case sensitivity.
Sort the output of ls -l by file size (5th field) in descending order.
Remove duplicate lines from list.txt while sorting it alphabetically.
Sort dates.txt (containing dates in YYYY-MM-DD format) chronologically.
Sort mixed.txt (containing numbers and text) by the first character, treating numbers as strings.

# Command wc
Create a file text.txt with several lines and display the total number of lines.
Count the number of words in notes.txt.
Display the total number of characters in data.txt.
Use wc to count the number of files in the current directory.
Count the lines, words, and characters in log.txt and save the output to stats.txt.
Find the number of lines in all .txt files in the current directory combined.
Count the number of words in the output of echo "This is a test sentence".
Display only the byte count for binary.dat (a binary file, if available).
Count the number of lines in /etc/passwd (if accessible).
Use wc to determine the total word count across multiple files (file1.txt, file2.txt, file3.txt).

# Command tee
Create a file output.txt and use tee to write the output of echo "Hello, World!" to it while displaying it on the screen.
Pipe the output of ls -l to tee and save it to dir_list.txt.
Use tee to append the current date and time to an existing file log.txt without overwriting it.
Write the output of who to two files, users1.txt and users2.txt, at the same time.
Redirect the output of cat data.txt through tee to save it to backup.txt while displaying it.
Use tee to save the output of ps aux to processes.txt and count the lines with wc -l.
Pipe grep "error" log.txt to tee and save matching lines to errors.txt.
Create a file combined.txt by using tee to merge the contents of file1.txt and file2.txt while showing the result.
Use tee with sudo to write the output of echo "test" > /etc/testfile to a restricted file (if permitted).
Pipe the output of sort names.txt to tee and save it to sorted_names.txt while displaying the sorted list.

# Command uniq
Create a file list.txt with repeated lines (e.g., "apple", "banana", "apple") and remove duplicate consecutive lines.
Sort data.txt with duplicates and use uniq to display only unique lines.
Count the number of occurrences of each line in words.txt after sorting.
Use uniq to display only the lines that appear more than once in a sorted log.txt.
Remove duplicate lines from names.txt and save the result to unique_names.txt.
Sort numbers.txt and use uniq to show only the lines that appear exactly once.
Pipe the output of cat items.txt through sort and uniq to eliminate duplicates while displaying the result.
Use uniq with a case-insensitive option to remove duplicate lines from mixed_case.txt after sorting.
Display the duplicate lines in records.txt with their counts after sorting.
Combine sort and uniq to process entries.txt and save only unique lines to clean_entries.txt.
