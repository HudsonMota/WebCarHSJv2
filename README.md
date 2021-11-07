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
Criação do banco de dados deve ser feita e configurada através do arquivo .env

- Configuração das tabelas no banco
```
php artisan migrate
```

- Tokens e chaves
```
php artisan jwt:secret
php artisan key:generate 
```

- Instalação dos componentes
```
composer install
```

- Atualização dos componentes
```
composer update
```

- Servidor local
```
php artisan serve
```