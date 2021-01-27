#Debugger#
The bug is that the `num1` and `num2` are both strings from `getElementById()`, and so the `calculateSum` function simply appends them and returns that. To fix this, I used `Number()` to convert `num1` and `num2` into numbers.  
#Network tab#
1. The new json file is called citylots.json.
2. The download was initiated by part2.js.
3. The file size is 11.7 MB.
4. It took 10.97 seconds to download.
5. The User-Agent that made the request was Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/88.0.4324.104 Safari/537.36.
6. The server was Apache type.
7. The file was last modified on Tue, 26 Jan 2021 22:14:13 GMT.
8. The Content-Type of the file was application/json.
9. The `fetchData()` method made the request.