# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 20 de Maio de 2026
**Empresa:** Abstergo Industries
**Responsável:** António Mendes

---

# Introdução

Este relatório apresenta o processo de implementação de serviços da [Amazon Web Services (AWS)](https://aws.amazon.com) na empresa Abstergo Industries, com o objetivo principal de reduzir custos operacionais em infraestrutura tecnológica, melhorar a eficiência dos sistemas e otimizar o armazenamento e processamento de dados corporativos.

A indústria farmacêutica trabalha com grandes volumes de informações, incluindo dados laboratoriais, documentos regulatórios, sistemas ERP, backups, pesquisas clínicas e aplicações internas. Dessa forma, a utilização correta de serviços cloud permite reduzir desperdícios, automatizar processos e melhorar a escalabilidade da infraestrutura.

O projeto foi dividido em três etapas estratégicas, focadas em armazenamento, monitorização e otimização computacional.

---

# Descrição do Projeto

## Etapa 1

### Serviço AWS:

Amazon S3

### Foco da ferramenta:

Redução de custos com armazenamento de dados e backups.

### Descrição do caso de uso:

A empresa possuía servidores locais para armazenamento de documentos farmacêuticos, relatórios laboratoriais, backups de sistemas e arquivos regulatórios, gerando elevados custos com manutenção física, energia elétrica e expansão de hardware.

Com a implementação do Amazon S3, os arquivos passaram a ser armazenados na nuvem com alta durabilidade e escalabilidade automática. Além disso, foram aplicadas políticas de ciclo de vida (“Lifecycle Policies”) para mover automaticamente arquivos antigos para classes de armazenamento mais baratas, como o S3 Glacier.

### Benefícios obtidos:

* Redução de custos com servidores físicos;
* Menor necessidade de manutenção de infraestrutura local;
* Armazenamento escalável sob demanda;
* Backup automatizado e seguro;
* Redução do consumo energético da empresa.

---

## Etapa 2

### Serviço AWS:

Amazon EC2

### Foco da ferramenta:

Otimização de recursos computacionais.

### Descrição do caso de uso:

A empresa utilizava servidores locais superdimensionados, funcionando continuamente mesmo em períodos de baixa utilização. Isso gerava desperdício de processamento e custos elevados de energia e manutenção.

Com a migração para Amazon EC2, foi possível utilizar instâncias sob demanda e implementar Auto Scaling, permitindo que os servidores aumentassem ou diminuíssem automaticamente conforme a necessidade do sistema.

Além disso, instâncias reservadas foram aplicadas em workloads previsíveis, reduzindo significativamente os custos operacionais.

### Benefícios obtidos:

* Pagamento apenas pelos recursos utilizados;
* Redução de desperdício computacional;
* Escalabilidade automática;
* Melhor desempenho das aplicações;
* Redução de custos operacionais de TI.

---

## Etapa 3

### Serviço AWS:

AWS CloudWatch

### Foco da ferramenta:

Monitorização e controlo de custos da infraestrutura.

### Descrição do caso de uso:

A empresa não possuía visibilidade adequada sobre consumo de recursos, picos de utilização e desperdícios na infraestrutura tecnológica.

Com o AWS CloudWatch, foram implementados dashboards, métricas automáticas e alertas inteligentes para monitorizar utilização de CPU, armazenamento, tráfego de rede e consumo de recursos.

A monitorização permitiu identificar instâncias subutilizadas e serviços desnecessários, possibilitando desligamentos automáticos em horários de baixa utilização.

### Benefícios obtidos:

* Identificação rápida de desperdícios;
* Melhor gestão de recursos;
* Redução de custos com serviços ociosos;
* Maior controlo operacional;
* Monitorização centralizada da infraestrutura.

---

# Conclusão

A implementação dos serviços da [AWS](https://aws.amazon.com) na Abstergo Industries proporcionou uma redução significativa nos custos de infraestrutura tecnológica, além de melhorar a eficiência operacional e a escalabilidade dos sistemas corporativos.

A utilização do Amazon S3 permitiu otimizar o armazenamento de dados e backups. O Amazon EC2 trouxe flexibilidade e redução de custos computacionais através do uso sob demanda e escalabilidade automática. Já o AWS CloudWatch forneceu monitorização contínua da infraestrutura, permitindo identificar desperdícios e melhorar a gestão dos recursos.

Com estas soluções, a empresa passa a possuir uma infraestrutura moderna, escalável, segura e financeiramente mais eficiente.

Recomenda-se a continuidade da utilização dos serviços implementados, bem como futuras análises de otimização cloud, visando melhorias contínuas nos processos tecnológicos da organização.

---

# Anexos

---

# Assinatura do Responsável pelo Projeto

**António Mendes**
Responsável pelo Projeto de Implementação Cloud AWS
