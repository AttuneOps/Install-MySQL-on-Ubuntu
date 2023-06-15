As a best practice, it is recommended to execute the `FLUSH PRIVILEGES` 
command. This command releases any cached memory in the server that may 
have been affected by the previous `CREATE USER` and `GRANT` statements.