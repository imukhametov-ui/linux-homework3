# Homework 3

## Завдання 1

```bash
ubuntu@ubuntu-VirtualBox:~$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.2 167944 13416 ?        Ss   00:43   0:12 /sbin/init sp
root           2  0.0  0.0      0     0 ?        S    00:43   0:00 [kthreadd]
root           3  0.0  0.0      0     0 ?        S    00:43   0:00 [pool_workque
root           4  0.0  0.0      0     0 ?        I<   00:43   0:00 [kworker/R-rc
root           5  0.0  0.0      0     0 ?        I<   00:43   0:00 [kworker/R-rc
root           6  0.0  0.0      0     0 ?        I<   00:43   0:00 [kworker/R-sl
root           7  0.0  0.0      0     0 ?        I<   00:43   0:00 [kworker/R-ne
root          12  0.0  0.0      0     0 ?        I<   00:43   0:00 [kworker/R-mm
root          13  0.0  0.0      0     0 ?        I    00:43   0:00 [rcu_tasks_kt
root          14  0.0  0.0      0     0 ?        I    00:43   0:00 [rcu_tasks_ru
root          15  0.0  0.0      0     0 ?        I    00:43   0:00 [rcu_tasks_tr
root          16  0.0  0.0      0     0 ?        S    00:43   0:27 [ksoftirqd/0]

```ubuntu@ubuntu-VirtualBox:~$ top

top - 18:26:10 up 17:42,  1 user,  load average: 1,55, 1,55, 1,01
Завдання: 202 загалом,   1 працює, 201 приспано,   0 зупинено,   0 зомбі
%CПроц.: 45,0 us, 11,1 sy,  0,0 ni, 42,4 id,  0,0 wa,  0,0 hi,  1,5 si,  0,0 st
МіБ Пам :   5926,4 загал,    299,3 вільн,   1739,6 вик,   3887,4 буф/кеш
МіБ Своп:   2048,0 загал,   2047,0 вільн,      1,0 вик.   3845,2 дост Пам 

    PID КОР.      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND  
    993 ubuntu    20   0 4336384 432600 149124 S  68,1   7,1 145:00.35 gnome-s+ 
   2505 ubuntu    20   0   11,5g 521956 204560 S  27,2   8,6  61:37.08 firefox  
   3521 ubuntu    20   0 2900840 335224 100276 S   6,6   5,5   9:25.11 Isolate+ 




### Пояснення:
ps aux — показує всі процеси системи  
top — інтерактивний монітор процесів  
echo $$ — показує PID поточної оболонки  
ps -p $$ — показує інформацію про процес оболонки


## ЗАВДАННЯ 2

```bash
sleep 1000 &
jobs
fg
# Ctrl+Z
jobs
kill %1
nohup sleep 1000 &
ps aux | grep sleep
```

### Результат:
Процес sleep запущено у фоновому режимі  
Переведено у передній план  
Зупинено через Ctrl+Z  
Завершено через kill  
nohup дозволяє процесу працювати після закриття терміналу  

### Пояснення:
sleep 1000 & — запуск у фоновому режимі  
jobs — показує фонові процеси  
fg — повертає процес у передній план  
Ctrl+Z — зупиняє процес  
kill — завершує процес  
nohup — дозволяє процесу працювати після закриття терміналу  

## Завдання 3

```bash


### Пояснення:


## Завдання 4

```bash

```

### Пояснення:
