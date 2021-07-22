# Polls Application

## Useful Commands

Takes migration names and returns their SQL:

```bash
#!/bin/bash
echo python3 manage.py sqlmigrate polls 0001
```

Check for any problems within your project without making migrations or touching your database:

```bash
#!/bin/bash
python3 manage.py check
```
