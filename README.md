# UHM_OS
## theme 2
### lab 1
**first.c:**  
Выводит PID себя и родительского процесса   
**second.c :**  
В цикле программа копирует саму себя ` fork(); ` и выводит PID себя и родителя  
**third_*.c :**  
Сначала выводит PID себя и родителя, после через ` execl() `  заменяет себя на эту программу и выводит её PID, который, собственно, совпадает с оригинальным   
