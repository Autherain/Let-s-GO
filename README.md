# Let-s-GO

Repo to archive what i learned from Alex Edward's book

## Remarks

### Mysql container

I won't use any software giving me a GUI for managing the MySql database. I will be only using the CLI tool.

To do so, you can pass the following command :

```bash
mysql -D snippetbox -u web -p
```

The password can be found inside the init.sql script used by docker to create the whole db. 
