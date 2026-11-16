# Análise de vendas com PostgreSQL

**Status: planejamento — implementação ainda não iniciada.**

Repositório de estudo de [José Carlos](https://github.com/carlos0ff), organizado a partir da [seleção de desafios de Matheus Leandro](https://www.matheusleandro.com.br/desafios).

## Objetivo

Explorar relacionamentos, totais e rankings de vendas com consultas SQL e funções PostgreSQL.

## Dados de entrada

A referência fornece um backup de banco e instruções para popular quatro tabelas: `clientes`, `produtos`, `pedidos` e `pedido_itens`. O backup permanece no repositório de origem; não está incluído aqui.

## Entregas previstas

| Views | Funções |
| --- | --- |
| `vw_pedidos_detalhados` | `fn_calcula_total_pedido` |
| `vw_total_por_cliente` | `fn_clientes_vip` |
| `vw_pedidos_resumo` | `fn_produtos_mais_vendidos` |
| `vw_vendas_por_cidade` | `fn_vendas_por_cidade` |
| `vw_produtos_mais_vendidos` | `fn_pedido_json` |

As entregas exercitam junções, agregações, filtros por parâmetros, resultados tabulares e composição de JSON.

## Critérios de conclusão

- [ ] Verificar a versão e o formato do backup.
- [ ] Documentar a restauração em um banco local de estudo.
- [ ] Implementar as views e funções.
- [ ] Validar totais, rankings, clientes sem compras e pedidos sem itens.
- [ ] Organizar scripts por ordem de execução.
- [ ] Demonstrar consultas e resultados esperados.

## Tecnologia prevista

PostgreSQL e PL/pgSQL. A versão será escolhida após verificar a compatibilidade do backup.

## Como executar

Este repositório contém apenas a documentação inicial. Ainda não há aplicação, scripts de execução ou testes executáveis. Os comandos serão adicionados junto com a implementação.

## Referências e créditos

- [Enunciado na plataforma](https://www.matheusleandro.com.br/desafios/desafio-de-engenharia-de-dados)
- [Referência original indicada pela plataforma](https://github.com/matheuslf/dev-matheuslf-desafio-eng-dados)

Este README resume a proposta e registra um plano de trabalho. Os créditos do enunciado pertencem aos autores das referências; a solução será desenvolvida neste repositório.
