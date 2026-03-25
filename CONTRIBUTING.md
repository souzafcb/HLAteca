# Contribuindo para a HLAteca

Obrigado por contribuir com a preservação histórica de catálogos, templates, manuais e documentos técnicos relacionados a testes de HLA.

## Objetivo
A HLAteca busca preservar a memória técnica de kits, softwares e documentos históricos de histocompatibilidade, especialmente materiais que deixam de estar disponíveis nos sites dos fornecedores.

## Como contribuir

As contribuições devem ser feitas preferencialmente por **Pull Request (PR)**.

Fluxo sugerido:
1. Faça um fork do repositório
2. Crie uma branch para sua contribuição
3. Adicione os arquivos e metadados
4. Abra um Pull Request com descrição clara da origem do material

## O que pode ser incluído
- Catálogos
- Datasheets
- IFUs / Instruções de uso
- Templates de software
- Release notes
- Manuais
- Tabelas técnicas históricas
- Material técnico público ou historicamente relevante

## O que não deve ser incluído
- Arquivos obtidos por quebra de acesso, invasão ou mecanismo não autorizado
- Conteúdo sensível de clientes, pacientes ou laboratórios
- Dados pessoais
- Arquivos sem qualquer informação mínima de proveniência
- Material cujo compartilhamento viole claramente restrições legais ou contratuais

## Informações mínimas obrigatórias
Toda contribuição deve informar, no PR ou em arquivo de metadados:

- Fabricante
- Produto / kit / software
- Tipo de documento
- Versão, se conhecida
- Ano ou data estimada
- Origem do arquivo
- Situação de acesso:
  - público
  - arquivado
  - histórico
  - institucional
  - restrito/metadado apenas

## Padrão de organização
Exemplo de estrutura:

`SSO/onelambda/labtype/drb345/`
`NGS/gendx/ngsengine/`
`ANTICORPOS/immucor/lifecodes/`

## Padrão sugerido para nomes de arquivos
`fabricante_produto_tipo_versao_ano_idioma.ext`

Exemplos:
- `onelambda_labtype_drb345_datasheet_v2-1_2019_en.pdf`
- `immucor_lifecodes_single_antigen_catalog_2018_en.pdf`

## Metadados
Quando possível, incluir um arquivo `.json` ou descrição no PR contendo:

- manufacturer
- product_name
- product_family
- assay_type
- document_type
- version
- language
- publication_date
- capture_date
- source_url
- source_status
- notes
- verification_status

## Critérios de revisão
As contribuições poderão ser revisadas quanto a:
- relevância histórica/técnica
- duplicidade
- organização
- nomenclatura
- proveniência
- risco jurídico/ético

## Pull Requests
No PR, descreva:
1. O que foi adicionado

## Observação importante
A aceitação de um arquivo no repositório não significa garantia de licença aberta do documento original. O repositório pode manter materiais históricos, metadados ou referências com finalidade técnica, educacional e de preservação documental.

## Dúvidas
Abra uma Issue para discutir estrutura, nomenclatura, duplicidade ou políticas de curadoria.
