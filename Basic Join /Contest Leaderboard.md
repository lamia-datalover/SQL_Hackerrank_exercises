# Here is the solution of this exercise:
![29](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/1e86f80b-05e6-4c1a-a356-d31770ebf8ac)

# Solution :
```bash
SELECT h.hacker_id, 
       h.name, 
       SUM(max_score) as total_score
FROM Hackers h
JOIN (
    SELECT hacker_id, 
           challenge_id, 
           MAX(score) as max_score
    FROM Submissions
    GROUP BY hacker_id, challenge_id
) as s ON h.hacker_id = s.hacker_id
GROUP BY h.hacker_id, h.name
HAVING SUM(max_score) > 0
ORDER BY total_score DESC, h.hacker_id ASC;
```
# Link of the exercise:
https://www.hackerrank.com/challenges/contest-leaderboard/problem
