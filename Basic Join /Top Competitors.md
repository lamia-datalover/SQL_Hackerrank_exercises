# Here is the solution of the following exercise :
![sql27](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/ee01761a-fa95-4b4c-828b-a7374386dafc)
![sql27prime](https://github.com/lamia-datalover/SQL_Hackerrank_exercises/assets/145395677/26c580c2-7a38-420a-8e99-38198abac6ac)
# Solution :
```bash
SELECT s.hacker_id, h.name FROM Submissions s
LEFT JOIN Hackers h ON h.hacker_id = s.hacker_id
LEFT JOIN Challenges c ON c.challenge_id = s.challenge_id
LEFT JOIN Difficulty d ON d.difficulty_level = c.difficulty_level
WHERE s.score = d.score
GROUP BY s.hacker_id,h.name
HAVING COUNT(s.hacker_id) > 1
ORDER BY COUNT(s.hacker_id) DESC, s.hacker_id ASC;

```
