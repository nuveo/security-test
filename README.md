# Teste para Security Engineer

## Case

A startup XPTO Tech recentemente lançou o MVP da sua API de leitura de arquivos, e realizou o deploy da API da maneira mais simplória possível para realizar a entrega do MVP para possíveis investidores.

O lançamento foi um sucesso e a XPTO Tech irá um investimento inicial, mas isto está condicionado a melhorias nos aspectos de segurança da aplicação, e para isso está solicitando os seus préstimos como Security Engineer para avaliar a aplicação e entregar um relatório de melhorias no quesito de segurança.

A aplicação está na seguinte URL: https://sectest.nuveo.io/.

## Endpoints da API

|Method|Endpoint|Body|Result|
| --- | --- | --- | --- |
|POST|/pdf|Arquivo pdf em form-data com chave 'pdf'|Um pdf é armazenado. |
|GET|/search?filename=xxx|| Busca um arquivo com nome `xxx`. Este endpoint é protegido com basic auth. |
|GET|/file/id|| Retorna informações do pdf com o `id`. |
|GET|/status|| Readiness/liveness |

## Relatório

Seu relatório deverá conter os seguintes pontos:

- Embasar seu relatório com alguma metodologia de mercado como OWASP, NIST ou ISO27001;
- Identificar as possíveis vulnarabilidades e propor soluções para mitigar as mesmas;
- Propor novas soluções de hospedagem da aplicação que sejam mais robustas no aspecto de segurança;
- Sugerir possíveis soluções para monitoramento de redes, servidores e containers;
- Sugerir também possíveis soluções de melhoria de acordo com a LGPD.

Qualquer dúvida estamos a disposição para lhe ajudar.
