# Teste para Security Engineer

## Descrição

O desafio consiste em elaborar um relatório com base em um pentest (black-box) a ser feito numa aplicação vulnerável.

A `URL` da aplicação está em https://sectest.nuveo.io/.

Para realizar o teste você terá 3 dias.

OBS: Testes de carga ou DDoS serão descartados.

## Endpoints

|Method|Endpoint|Body|Result|
| --- | --- | --- | --- |
|POST|/pdf|Arquivo pdf em form-data com chave 'pdf'|Um pdf é armazenado. |
|GET|/search?filename=xxx|| Busca um arquivo com nome `xxx`. Este endpoint é protegido com basic auth. |
|GET|/file/id|| Retorna informações do pdf com o `id`. |
|GET|/status|| Readiness/liveness |

## Pontos de avaliação

- Quantidade de vulnerabilidades descobertas na aplicação;
- Nível de detalhes sobre os serviços utilizados(Ex: versões e configurações);
- Quanto você consegue explorar as brechas encontradas na aplicação;
- Conhecimento em análise de vulnerabilidades de aplicações web;
- Nível de atenção aos detalhes;
- Propostas para efetuar as correções e sanar os problemas listados, apresentando os possíveis trade-offs.
