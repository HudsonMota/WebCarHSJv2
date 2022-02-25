# WebCar - HSJ

## Baixar Projeto
```
git clone https://github.com/HudsonMota/WebCarHSJv2.git
```
## Executar Projeto

- Configuração da .env
```
cp .env.example .env
```
## Criação do banco de dados deve ser feita e configurada no arquivo .env

- Copie o arquivo /db/db_wecar_hsj.sql e cole no gerenciador de banco de dados (Workbench)


- Instalação dos componentes
```
composer install
```

- Atualização dos componentes
```
composer update
```

- Tokens e chaves
```
php artisan key:generate
```

- Servidor local
```
php artisan serve
```
