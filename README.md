# Portfolio de Projetos do Santander Bootcamp Cibersegurança #2

Este repositório contém os projetos realizados durante o bootcamp.

## Projetos

### Projeto 1 - [Explorando Fundamentos de Cibersegurança com Desafios de Código em Python - Módulo Fundamentos de Cibersegurança]
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

DESAFIO 1

Descrição
Você foi encarregado de criar um sistema simples que verifica a integridade de arquivos, comparando o hash fornecido pelo usuário com o hash real do arquivo. Na função verificar_hashes que irá receber uma lista de hashes e compará-los com os valores esperados para cada arquivo. Seu objetivo é verificar se o hash calculado é igual ao hash esperado.
Entrada
Uma lista de pares de hashes (hash calculado e hash esperado), separados por vírgulas, e cada par separado por ponto e vírgula.
Saída
Para cada par de hashes fornecido, o código imprime o resultado "Correto" ou "Inválido".

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

DESAFIO 2:
Descrição
Desenvolva um sistema que simule a enumeração de serviços em um servidor, dado um conjunto de portas e serviços associados. Você deve receber uma lista de números de portas e, para cada porta, retornar o serviço associado. Se a porta não estiver no dicionário, retorna "Desconhecido".
Entrada
Uma lista de números de portas separados por vírgula.
Saída
Uma lista de serviços correspondentes a essas portas.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Projeto 2 - [Busca por Vulnerabilidades com Desafios de Código em Python - Módulo Fundamentos de Busca por Vulnerabilidades e Testes de Invasão]
DESAFIO 1

Descrição
Crie uma solução para analisar uma lista de e-mails recebidos, verificando padrões comuns de phishing nas mensagens. Se um e-mail contiver palavras suspeitas como "ganhe", "prêmio", "urgente", "desconto", "click" e "promoção" ele deve ser classificado como "Phishing" e "Seguro".
Entrada
Uma String contendo um conteúdo único representando o corpo do e-mail.
Saída
"Phishing" ou "Seguro" para cada e-mail.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

DESAFIO 2:
Descrição
Você é responsável por implementar um sistema de monitoramento de segurança para um sistema de acesso. Seu objetivo é analisar registros de log de tentativas de acesso para detectar possíveis invasões. Cada registro contém um identificador de usuário e um status que indica se a tentativa de acesso foi bem-sucedida ou falhou.

A detecção de tentativas de invasão é essencial para a segurança do sistema, e a análise de logs é uma prática comum para identificar comportamentos suspeitos. O sistema deve emitir um alerta se detectar mais de 3 tentativas consecutivas de falha para o mesmo usuário.

Entrada
Uma lista de registros de log no formato id_usuario:status, onde:

id_usuario é uma string que representa o identificador do usuário (exemplo: "user1").

status pode ser uma das seguintes strings:
- "sucesso" – indica que a tentativa de acesso foi bem-sucedida.
- "falha" – indica que a tentativa de acesso falhou.

A lista pode conter qualquer número de registros.

Saída
O sistema deve retornar:

O id_usuario que teve mais de 3 tentativas consecutivas de falha.

Se nenhum usuário tiver mais de 3 tentativas de falha consecutivas, o sistema deve retornar a mensagem "Nenhum invasor detectado".
