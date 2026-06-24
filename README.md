# desafio-step-functions-aws
Workflows automatizados com AWS Step Functions.

# Explorando Workflows Automatizados com AWS Step Functions

## Objetivo

Este laboratório teve como objetivo compreender o funcionamento do AWS Step Functions para criação e execução de workflows automatizados utilizando serviços da AWS.

## O que é AWS Step Functions

AWS Step Functions é um serviço que permite coordenar múltiplos serviços AWS através de fluxos de trabalho visuais chamados State Machines.

## Arquitetura Utilizada

O workflow utilizado no laboratório foi composto por:

* Start
* AWS Lambda
* AWS Batch
* End

Fluxo:

Start → Lambda → AWS Batch → End

## Etapas Realizadas

### 1. Análise do Workflow

Foi utilizado o modelo BatchJobWithLambda, responsável por iniciar um processamento em lote através da integração entre AWS Lambda e AWS Batch.

### 2. Implantação da Solução

A implantação foi realizada através do AWS CloudFormation, responsável pela criação automática dos recursos necessários.

### 3. Execução da Máquina de Estados

Após a implantação, a State Machine foi executada com sucesso, iniciando o processamento definido no workflow.

## Benefícios Observados

* Automação de processos
* Integração entre serviços AWS
* Orquestração visual de fluxos
* Facilidade de monitoramento
* Escalabilidade

## Evidências


## Conclusão

Durante o laboratório foi possível compreender como o AWS Step Functions coordena diferentes serviços AWS através de máquinas de estado. Também foi possível observar a utilização do AWS Lambda para geração de dados de entrada e do AWS Batch para execução de tarefas em lote, demonstrando o potencial da automação de workflows na nuvem.
