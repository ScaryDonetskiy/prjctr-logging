![ELK](./elk.png)
![Graylog](./graylog.png)

-
| Select/Long query time | 0    | 1    | 10   |
|------------------------|------|------|------|
| First Select           | 50ms | 25ms | 39ms |
| Second Select          | 19ms | 11ms | 19ms |
| Third Select           | 9ms  | 24ms | 12ms |

SELECT event, COUNT(*) FROM events GROUP BY event;
SELECT DISTINCT event FROM events;
SELECT * FROM events ORDER BY event ASC LIMIT 10;
