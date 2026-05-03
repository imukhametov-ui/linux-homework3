# linux-homework3
# Homework 3

## Завдання 1

```bash
ps aux
top
echo $$
ps -p $$
```

## Завдання 2

```bash
sleep 1000 &
jobs
fg
# Ctrl + Z
jobs
kill %1
nohup sleep 1000 &
ps aux | grep sleep
```

## Завдання 3

```bash
nice -n 10 sleep 1000 &
ps aux | grep sleep
renice 15 -p PID
ulimit -a
```

## Завдання 4

```bash
df -h
free -h
```
