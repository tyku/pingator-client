#Pingator

## Before start
`npm install`

## Client

### Run
`npm run start:client`

### Description
После прекращения работы сервис выводит всю статистику в сообщении вида:<br>

----------------------
Total requests: 33<br>
Success requests: 13<br>
Failed requests: 3<br>
Timed requests: 17<br>
----------------------
<b>Важно</b>: При завершении работы, сервис заканчивает начатые запросы. Это может длиться 10-20 секунд.
Сделано намеренно, что бы не было потерянных метрик.

## Server

## Start server

### Run

`npm run start:server`

### Description
После прекращения работы сервис выводит всю статистику в сообщении вида:<br>

----------------------
Average time: 500.38 ms<br>
Median time: 383 ms<br>

----------------------
<b>Важно</b>: При завершении работы, сервис  ожидает таймаута всех текущих запросов. Это может длиться 10-20 секунд.
После чего завершает работу.
