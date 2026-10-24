# EX01 Developing a Simple Webserver
## Date:
15/10/2026
## REG NO:
26018110
## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Computer Network Protocols</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 2rem;
      background: #f4f7fb;
      color: #1f2937;
    }

    h1 {
      text-align: center;
      color: #163a63;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: white;
      box-shadow: 0 2px 10px #00000015;
    }

    th, td {
      padding: 12px 14px;
      border: 1px solid #d5deea;
      text-align: left;
    }

    th {
      background: #163a63;
      color: white;
    }

    tr:nth-child(even) {
      background: #f0f5fa;
    }

    caption {
      padding: 10px;
      font-weight: bold;
      color: #40546b;
    }

    @media (max-width: 700px) {
      body {
        margin: 1rem;
      }

      table {
        font-size: 0.9rem;
      }

      th, td {
        padding: 8px;
      }
    }
  </style>
</head>
<body>
  <h1>Computer Network Protocols</h1>

  <table>
    <caption>Common protocols and their purposes</caption>
    <thead>
      <tr>
        <th>Protocol</th>
        <th>Layer</th>
        <th>Default Port</th>
        <th>Purpose</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>HTTP</td>
        <td>Application</td>
        <td>80</td>
        <td>Transfers web pages and other data.</td>
      </tr>
      <tr>
        <td>HTTPS</td>
        <td>Application</td>
        <td>443</td>
        <td>Secure web communication using encryption.</td>
      </tr>
      <tr>
        <td>DNS</td>
        <td>Application</td>
        <td>53 (UDP/TCP)</td>
        <td>Translates domain names into IP addresses.</td>
      </tr>
      <tr>
        <td>DHCP</td>
        <td>Application</td>
        <td>67/68 (UDP)</td>
        <td>Automatically assigns network settings to devices.</td>
      </tr>
      <tr>
        <td>FTP</td>
        <td>Application</td>
        <td>21 (control)</td>
        <td>Transfers files between computers.</td>
      </tr>
      <tr>
        <td>SSH</td>
        <td>Application</td>
        <td>22</td>
        <td>Provides secure remote login and command access.</td>
      </tr>
      <tr>
        <td>SMTP</td>
        <td>Application</td>
        <td>25, 465, or 587</td>
        <td>Sends email between mail clients and servers.</td>
      </tr>
      <tr>
        <td>POP3</td>
        <td>Application</td>
        <td>110 / 995 (secure)</td>
        <td>Downloads email from a mail server.</td>
      </tr>
      <tr>
        <td>IMAP</td>
        <td>Application</td>
        <td>143 / 993 (secure)</td>
        <td>Accesses and synchronizes email stored on a server.</td>
      </tr>
      <tr>
        <td>TCP</td>
        <td>Transport</td>
        <td>—</td>
        <td>Provides reliable, ordered data delivery.</td>
      </tr>
      <tr>
        <td>UDP</td>
        <td>Transport</td>
        <td>—</td>
        <td>Provides lightweight, connectionless data delivery.</td>
      </tr>
      <tr>
        <td>IP</td>
        <td>Internet / Network</td>
        <td>—</td>
        <td>Addresses and routes packets across networks.</td>
      </tr>
      <tr>
        <td>ICMP</td>
        <td>Internet / Network</td>
        <td>—</td>
        <td>Reports network errors and supports diagnostic tools.</td>
      </tr>
      <tr>
        <td>ARP</td>
        <td>Link</td>
        <td>—</td>
        <td>Maps IPv4 addresses to local network hardware addresses.</td>
      </tr>
    </tbody>
  </table>
</body>
</html>
~~~

## OUTPUT:
![alt text](<Screenshot 2026-10-15 143035.png>)

## RESULT:
The program for implementing simple webserver is executed successfully.

