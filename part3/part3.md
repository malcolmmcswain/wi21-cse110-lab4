# DevTools - Debugging
- The bug was that getting the number from the DOM returned a string so the + operation was treated as concatenation rather than addition.
- To fix it, I added Number() calls around num1 and num2 to convert the strings into numbers.

# DevTools - Network Tab
1. citylots.json
2. part2.js
3. 11.7 MB
4. 6.84s
5. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.96 Safari/537.36 Edg/88.0.705.50
6. Apache
7. Tue, 26 Jan 2021 22:14:13 GMT
8. application/json
9. fetchData()