# 2i-crud

# Introdução
Este projeto é uma aplicação CRUD que permite criar, eliminar e atualizar produtos de uma base de dados MySQL. 

# Tecnologias Utilizadas
-> PHP   
-> PHPMyAdmin  
-> MySQL  
-> HTML/CSS  

# Funcionalidades

-> Criar novos produtos  
-> Ver os produtos adicionados  
-> Atualizar produtos  
-> Eliminar produtos  

# Requisitos

...........................

# Instalação  

Clone este repositório:

git clone https://github.com/seu-usuario/nome-do-repositorio.git

Acesse o diretório do projeto:

cd nome-do-repositorio

Configure o banco de dados MySQL:

Acesse o painel de controle do seu alojamento

Crie um banco de dados MySQL

Importe o arquivo database.sql (se fornecido) via phpMyAdmin

Atualize as credenciais do banco de dados no arquivo de conexão (config.php ou similar)

Faça o upload dos arquivos para o servidor via FTP ou gerenciador de arquivos do provedor

Acesse o sistema pelo navegador:

http://seu-dominio.com

# Estrutura do Projeto  

/
|-- index.php       # Página inicial  
|-- config.php      # Configuração do banco de dados  
|-- create.php      # Criar novo registro  
|-- read.php        # Ler registros  
|-- update.php      # Atualizar registro  
|-- delete.php      # Deletar registro  
|-- assets/         # CSS, JS, imagens  
|-- database.sql    # Script para criar as tabelas (se disponível)  

