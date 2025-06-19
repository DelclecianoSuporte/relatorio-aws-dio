# RELATORIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 18/06/2025<br>
Empresa: Abstergo Industries<br>
Responsável: Delcleciano Júnior

## Introdução
Este relatório apresenta o processo de análise e proposta de implementação de 
ferramentas AWS na empresa Abstergo Industries, realizada por Delcleciano Júnior. 
A empresa atua no ramo de distribuição de cosméticos e medicamentos, 
e atualmente não possui qualquer infraestrutura em nuvem. O objetivo do projeto é reduzir custos operacionais, 
aumentar a escalabilidade e segurança, proponho então algumas soluções utilizando Cloud Computing AWS.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. 
A seguir, serão descritas as etapas do projeto:

### Etapa 1: Amazon EC2

**Foco da ferramenta:**  
Hospedagem de sistemas internos, como ERPs ou sistemas para controle de estoque, com alta disponibilidade e escalabilidade.

**Descrição de caso de uso:**  
A empresa poderá migrar seus sistemas legados para a nuvem, eliminando a necessidade de servidores físicos locais.  
Isso reduz custos com manutenção, energia e infraestrutura, além de permitir que os sistemas operem com maior estabilidade e segurança.

### Principais ganhos:
- Eliminação de servidores físicos locais
- Flexibilidade para escalar recursos computacionais

### Etapa 2: Amazon S3

**Foco da ferramenta:**  
Armazenamento seguro, durável e escalável de documentos, planilhas, backups e arquivos da empresa.

**Descrição de caso de uso:**  
Os arquivos administrativos e operacionais da empresa, incluindo relatórios regulatórios, laudos laboratoriais, notas fiscais e planilhas de controle, podem ser armazenados em buckets S3.

### Principais ganhos:
- Redução de custos com armazenamento físico ou em servidores locais
- Acesso seguro de qualquer lugar
- Segurança e conformidade com as normas LGPD

### Etapa 3: AWS CloudWatch

**Foco da ferramenta:**  
Monitoramento e observabilidade dos sistemas, aplicações e recursos AWS.

**Descrição de caso de uso:**  
Através do CloudWatch, a empresa poderá acompanhar o desempenho de seus sistemas hospedados na nuvem, identificar gargalos e agir proativamente.  
Alarmes automáticos podem ser configurados para evitar falhas em processos críticos, como o abastecimento de produtos ou o controle de estoques.

### Principais ganhos:
- Redução de falhas operacionais
- Monitoramento em tempo real
- Aumento da confiabilidade dos serviços internos


## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado benefícios:

- Redução imediata de custos com infraestrutura física
- Melhoria na segurança e conformidade dos dados
- Aumento da escalabilidade dos sistemas internos
- Maior controle e monitoramento dos serviços utilizados

O que aumentará significativamente a eficiência e a produtividade da empresa. 
Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por 
novas tecnologias que possam melhorar ainda mais os processos da empresa, 
como o uso de inteligência artificial, automação com Lambda, 
e soluções de analytics para decisões estratégicas baseadas em dados.

## Anexos

### Amazon EC2

- [Documentação oficial](https://docs.aws.amazon.com/ec2/)
- [Visão e benefícios](https://aws.amazon.com/pt/ec2/)

### Amazon S3

- [Documentação oficial](https://docs.aws.amazon.com/s3/)
- [Visão e benefícios](https://aws.amazon.com/pt/s3/)

### AWS CloudWatch

- [Documentação oficial](https://docs.aws.amazon.com/cloudwatch/)
- [Guia de como monitorar suas aplicações](https://aws.amazon.com/pt/cloudwatch/getting-started/)

### Material complementar

- [AWS Overview (Whitepaper PDF)](https://d1.awsstatic.com/whitepapers/aws-overview.pdf)

Assinatura do Responsável pelo Projeto:

Delcleciano Júnior