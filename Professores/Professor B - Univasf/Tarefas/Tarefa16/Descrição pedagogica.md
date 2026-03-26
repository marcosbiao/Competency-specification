## Título da Atividade

Sistema de Cadastro de Alunos com Persistência em Arquivo Binário

## Contexto Instrucional

Atividade prática de programação introdutória, adequada a disciplina de Introdução à Programação, realizada em ambiente de desenvolvimento com compilação e execução de programas em linguagem C. A produção esperada é individual, centrada na implementação de um programa funcional com interação por menu, manipulação de arquivo binário e registro breve das decisões adotadas na solução.

## Objetivo da Atividade

Desenvolver um sistema simples de cadastro de alunos que utilize armazenamento persistente em arquivo binário, organizando dados estruturados e operações de consulta por meio de funções. A atividade busca verificar a capacidade do estudante de integrar leitura e escrita estruturada, acesso sequencial a registros e navegação básica em diretórios em uma aplicação única e coerente.

## Descrição da Tarefa

O estudante deve implementar um programa em C, com interface baseada em menu, capaz de executar as operações centrais de um sistema de cadastro de alunos. O sistema deve permitir o registro de dados de alunos em arquivo binário, a listagem dos registros armazenados, a busca de aluno por ID e a exibição dos arquivos presentes no diretório de trabalho.

A solução deve utilizar estrutura de dados para representar cada aluno e organizar o programa em funções com responsabilidades bem definidas. O produto esperado é um programa executável que demonstre persistência dos dados entre execuções, permita consultar os registros já armazenados e apresente funcionamento consistente das opções do menu. Além do código, espera-se uma justificativa breve sobre a organização geral da solução e sobre as decisões adotadas para armazenamento e busca dos registros.

## Condições de Execução

1. A implementação deve utilizar arquivo binário para gravação e leitura de registros, com operações compatíveis com acesso sequencial.
2. Os dados de cada aluno devem ser representados por uma estrutura, preservando a associação entre os campos cadastrados e o ID utilizado nas consultas.
3. O programa deve ser modularizado em funções, evitando concentrar toda a lógica em um único bloco principal.
4. A interação com o usuário deve ocorrer por menu textual, com opções claramente associadas às funcionalidades solicitadas.
5. A funcionalidade de busca deve operar sobre os registros armazenados no arquivo, sem pressupor carregamento integral em memória como requisito obrigatório.
6. Como o enunciado não especifica política para IDs repetidos nem detalha os campos do cadastro, a solução deve ao menos manter consistência entre gravação, listagem e busca, deixando explícito o comportamento adotado nesses casos.
7. A listagem de arquivos do diretório deve refletir o conteúdo acessível ao programa no ambiente de execução, podendo utilizar biblioteca específica de manipulação de diretórios quando adotada na implementação.

## Evidências Esperadas

1. Código fonte em C, compilável e organizado em funções.
2. Definição da estrutura de dados usada para representar os alunos.
3. Arquivo binário gerado e utilizado pelo sistema durante a execução.
4. Demonstração das operações de cadastro, listagem e busca por ID.
5. Demonstração da funcionalidade de exibição dos arquivos do diretório.

## Critérios de Avaliação

1. Correção funcional das operações solicitadas, com cadastro, listagem, busca por ID e exibição de arquivos do diretório funcionando de modo coerente.
2. Uso adequado de arquivo binário e estrutura de dados, preservando a integridade dos registros armazenados e recuperados.
3. Organização modular da solução, com funções claras e compatíveis com as responsabilidades do sistema.
4. Consistência entre entrada, armazenamento e saída dos dados, incluindo tratamento verificável das consultas realizadas pelo menu.
5. Clareza e verificabilidade do artefato entregue, considerando legibilidade do código e possibilidade de execução.
