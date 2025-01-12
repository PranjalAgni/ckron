# Notifier Reference

- [Email Notifier](#email-notifier)

## Email Notifier

Sends an emails

| Property | Description | Required |
|-|-|-|
| [`smtp_host`](#smtp_host) | Hostname or IP address of the SMTP server | Yes |
| [`smtp_port`](#smtp_port) | Port to connect to | No |
| [`smtp_auth`](#smtp_auth) | SMTP server authentication | No |
| [`from`](#from) | The email address of the sender | Yes |
| [`to`](#to) | Recipients email addresses | Yes |


### **smtp_host**
Hostname or IP address of the SMTP server

```yml
smtp_host: smtp.example.com
```

### **smtp_port**
Port to connect to. Default value is `25`

```yml
smtp_port: 2525
```

### **smtp_auth**
SMTP server authentication

```yml
smtp_auth:
  user: user
  pass: password
```

### **from**
The email address of the sender

```yml
from: '"Ckron Scheduler" <ckron@example.com>'
```

### **to**
Recipients email addresses

```yml
to: dev@example.com
```
