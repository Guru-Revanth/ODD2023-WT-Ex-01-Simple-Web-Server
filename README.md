# Ex-01-Simple-Web-Server
## NAME: GURU REVANTH KUMARAVEL RADHIKA
## REFERENCE NUMBER: 23004484
## DEPARTMENT: AI & DS

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
```
from http.server import HTTPServer, BaseHTTPRequestHandler

content="""
<html>
<h**ead>
</head>
<body>
<h1>Welcome</h1>
</body>
</html>
"""
class HelloHandler (BaseHTTPRequestHandler):
    def do_GET(self):


        self.send  (200)
        self.send_header('content-type', 'text/html; charset=utf-8')
        self.end_headers()
        self.wfile.write(content.encode())
```

## OUTPUT:
![WhatsApp Image 2023-11-22 at 10 29 22_c72e098c](https://github.com/Guru-Revanth/ODD2023-WT-Ex-01-Simple-Web-Server/assets/139841931/638a9795-90b7-4edb-8c48-df12531581c2)



## RESULT:
The program for implementing simple webserver is executed successfully.
