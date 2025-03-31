# Команда grep
```
cat > fruits.txt << OEF

 Apple
 Banana
 Orange
 Apricot

 OEF

cat > example.txt << OEF

This is a test
Hello world
Another test line

 OEF

 # Строки с буквой "a"
grep "a" fruits.txt

# Строки, начинающиеся с "A"
grep "^A" fruits.txt

# Подсчет строк с "Apple"
grep -c "Apple" fruits.txt

# Строки без буквы "e"
grep -v "e" fruits.txt

# Поиск "test" во всех .txt файлах
grep "test" *.txt
```

===========


# Команда tail
```
cat > log.txt << EOF
Line 1: System started
Line 2: User logged in
Line 3: Data processing began
Line 4: Warning issued
Line 5: Connection established
Line 6: File saved
Line 7: Update completed
Line 8: Error detected
Line 9: Retry attempted
Line 10: Backup initiated
Line 11: Process paused
Line 12: Memory low
Line 13: Task resumed
Line 14: Operation successful
Line 15: System shutdown
EOF
tail -n 5 log.txt

# 2. Вывод строк, начиная с 10-й
tail -n +10 log.txt

# 3. Сохранение последних 3 строк в end_log.txt
tail -n 3 log.txt > end_log.txt

# 4. Последние 7 строк /var/log/syslog (моделировано)
tail -n 7 /var/log/syslog

# 5. Слежение за изменениями в log.txt
tail -f log.txt
```

===========

# Команда head
```
cat > list.txt << EOF
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
EOF
head -n 4 list.txt

# 2. Первые 10 строк /etc/passwd (моделировано)
head -n 10 /etc/passwd

# 3. Сохранение первых 6 строк в top_list.txt
head -n 6 list.txt > top_list.txt

# 4. Первые 3 строки из ls -l (моделировано)
ls -l | head -n 3

# 5. Создание text.txt и вывод первой строки
cat > text.txt << EOF
First line of text
Second line here
Third line follows
Fourth and final
EOF
head -n 1 text.txt
```
