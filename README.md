# Controle de Frota

**Projeto histórico — sem manutenção ativa.** Este repositório é preservado como registro de uma etapa anterior de desenvolvimento. Não há previsão de novas funcionalidades ou correções.

## Sobre o projeto

Aplicação desktop para administrar veículos, motoristas e movimentações de uma frota. Surgiu de uma necessidade de organização na Trilha Tecnologia, onde informações de viagens, gastos e manutenção estavam dispersas em um grupo de mensagens.

## Escopo preservado

O projeto reúne cadastros de veículos e motoristas, registro de saídas e retornos, viagens, abastecimentos, gastos e manutenções, incluindo manutenções programadas. Também contém filtros e relatórios para consulta e exportação em PDF.

## Tecnologias e organização

C#, WPF, .NET 5 e Entity Framework Core 5, com MySQL por meio do provider Pomelo. Os relatórios utilizam FastReport Open Source; `ControleFrotaApp/` concentra modelos, serviços, ViewModels, telas e migrações.

## Estado e contexto de execução

A execução requer Windows, banco MySQL compatível e os modelos de relatório utilizados pela aplicação. A documentação anterior registrava uso na Trilha Tecnologia; este registro histórico não afirma que o sistema ainda esteja em uso atualmente.

Esta documentação foi revisada a partir dos arquivos versionados. Não foram executados build, testes funcionais ou integrações durante a revisão; as versões citadas descrevem o projeto preservado, não uma recomendação de stack para novos sistemas.
