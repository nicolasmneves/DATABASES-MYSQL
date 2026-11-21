# Bancos de Dados MySQL

Scripts SQL dos meus estudos de banco de dados com MySQL/MariaDB.

| Arquivo | Conteúdo |
|---|---|
| `DATABASE-NovaTech.sql` | Modelo da empresa fictícia NovaTech: escritórios, departamentos, funcionários e projetos |
| `PROJETO_CLIENTE.sql` | Dump do phpMyAdmin (MariaDB 10.11 em Docker) com a tabela `PROJETO_CLIENTE` do banco `aula` |

## Como usar

Crie um banco e importe o script:

```
mysql -u root -p nome_do_banco < DATABASE-NovaTech.sql
```

Também dá para importar pela aba **Importar** do phpMyAdmin.
