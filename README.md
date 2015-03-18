Instruções
----------
----------

Primeiramente configure a conexão do banco no arquivo:

```
app/configdb.php
```

Depois execute o seguinte comando para popular a base:

```
php app/fixture.php

```

Depois execute o comando para rodar o site:

```
php -S localhost:8000 -t public_html
```