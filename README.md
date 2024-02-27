To request data using this microservice, submit a GET request to https://daugherc.pythonanywhere.com/stock?ticker=YourTickerHere
This can be done with a browser, with software such as Postman, or (most usefully) via a programming language of your choice (e.g., Python's Request library can send a GET request).
Example: https://daugherc.pythonanywhere.com/stock?ticker=AAPL is used to request data related to Apple, Inc.

To receive data: data is sent back via HTTP after submitting the GET request above. Data comes back in JSON format. Example data:
{"currentPrice":181.16,"dayHigh":182.75,"dayLow":180.65,"dividendYield":0.0053,"forwardPE":25.266388,"name":"Apple Inc.","ticker":"AAPL"}

UML Diagram:
![image](https://github.com/CD-oregon-state/CS361/assets/114345379/eb43039a-9c69-4344-a83f-2a28b45d2688)
