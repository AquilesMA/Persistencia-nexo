# Persistência Nexo

Modelagem da camada de **persistência de dados** da plataforma **Nexo** — plataforma integrada para gestão de serviços psicológicos, dividida em Aplicação Web (Administrador, Atendente, Psicólogo) e Aplicativo Mobile (Paciente, Responsável).

Este repositório reúne o **Dossiê de Modelagem de Persistência**: DER lógico, modelo relacional, normalização, dicionário de dados, mapeamento objeto-relacional e a verificação de coerência entre classes, DER e tabelas.

> Trabalho da **AV3** da disciplina de **Modelagem Orientada a Objetos** — Centro Universitário Jorge Amado (UNIJORGE), prof. Celso Barreto.


## Papel neste repositório

Camada de persistência, com base no diagrama de classes de domínio e nos 9 módulos do sistema: Acesso e Permissões, Pessoas e Vínculos, Agenda, Atendimento, Recorrência, Financeiro, Lista de Espera, Documentos e Comunicação.

## Documentos

| # | Documento | Conteúdo |
|---|-----------|----------|
| 01 | [Modelo Relacional](docs/01-Modelo%20Relacional%20-%20Nexo.pdf) | As 25 tabelas, colunas, tipos, restrições, cardinalidades, tratamento de N:N, estratégia de herança e integridade referencial |
| 02 | [Normalização e Justificativas](docs/02-Normalizacao%20e%20Justificativas-nexo.pdf) | Dependências funcionais e verificação de 1FN, 2FN e 3FN para as 25 tabelas |
| 03 | [Dicionário de Dados](docs/03-Dicionario%20de%20Dados%20-nexo.pdf) | Descrição detalhada de cada atributo, tipo e restrição |
| 04 | [Mapeamento Objeto-Relacional](docs/04-Mapeamento%20Objeto-Relacional-nexo.pdf) | Correspondência entre as classes do diagrama de domínio e as tabelas do banco |
| 05 | [Coerência Classes ↔ DER ↔ Modelo Relacional](docs/05-Coerencia%20Classes-DER-Relacional-nexo.pdf) | Verificação cruzada garantindo consistência entre os três artefatos |

Cada documento está disponível em `.docx` (editável) e `.pdf` (leitura).

## Diagramas

| Diagrama | Imagem |
|----------|--------|
| DER lógico | [ver](diagramas/DER-logico.png) |


## Estrutura

```
Persistencia-nexo/
├── docs/            # documentos de modelagem (docx e pdf)
└── diagramas/       # diagramas exportados como imagem
```
