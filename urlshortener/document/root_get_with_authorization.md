## GET

### GET /

### Request Headers

* AUTHORIZATION: eyJhbGciOiJIUzI1NiIsImlhdCI6MTUyOTM5MTA0MiwiZXhwIjoxNTI5NDc3NDQyfQ.eyJlbWFpbCI6Im1vaGFtbWFkc2hlaWtoaWFuNzBAZ21haWwuY29tIiwibmFtZSI6Im1vaGFtbWFkIiwiZmFtaWx5Ijoic2hlaWtoaWFuIiwiaWQiOjEsInNlc3Npb25JZCI6MSwicm9sZXMiOlsiYWRtaW4iXX0.YnodWvTOTOjCMxZPCsAXJCzRtyIaS8rN98nb4VjM9bc

### Response: 200 OK

#### Headers

* X-Identity: 1
* Content-Type: text/html; charset=utf-8
* Content-Length: 506

#### Body

```
<html>
<head><title>Url shortener</title></head>
<body>
        <div style="background-color:DodgerBlue;color:white;padding:20px;">
        <h1>Profile: mohammad sheikhian</h1>
        <form method="POST" action="/">
        <strong>Iuput url:</strong>
            <input type="text" name="url" />
            <input type="submit" value="Submit" />
        </form>
        <form method="POST" action="/auth">
            <input type="submit" value="Login" />
        </form>
        </div>
</body>
</html>

```

