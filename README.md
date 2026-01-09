# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data de início do projeto:** 09/01/2026  
**Empresa:** Farmácia Saúde+  
**Responsável:** Lêda Trindade

---

## 1. Introdução

Este relatório descreve a **implementação de serviços da AWS** na farmácia **Saúde+**, com foco em **redução de custos e otimização de processos operacionais**.  

A farmácia possui desafios como **controle de estoque, gestão de vendas e manutenção de servidores locais**, que geram custos altos e demandam automação de processos. A implementação de soluções na nuvem trouxe **benefícios de escalabilidade, segurança e monitoramento eficiente**.

O projeto aborda conceitos de **Cloud Computing**, modelos de serviço, implantação e os principais serviços AWS aplicados à farmácia.

---

## 2. Conceitos de Cloud Utilizados

### 2.1 Cloud Computing
- **Definição:** Computação em nuvem que permite acessar recursos de TI sob demanda, como armazenamento, processamento e bancos de dados, sem depender de infraestrutura física local.  
- **Benefícios aplicados:** Redução de gastos com hardware e manutenção, maior flexibilidade e escalabilidade.

### 2.2 Modelos de Serviço
- **IaaS (Infrastructure as a Service):** Amazon EC2, Elastic Block Store (EBS)  
- **PaaS (Platform as a Service):** Amazon RDS  
- **SaaS (Software as a Service):** Automatizações via AWS Lambda e notificações via Amazon SNS  

### 2.3 Modelos de Implantação
- **Nuvem pública:** Serviços AWS utilizados para armazenar e processar dados da farmácia, reduzindo custos de servidores locais.  
- **Regiões e Zonas de Disponibilidade:** Garantem alta disponibilidade e redundância de dados.  

---

## 3. Descrição do Projeto

O projeto foi dividido em **3 etapas principais**, cada uma focada na implementação de um serviço AWS para **reduzir custos e aumentar eficiência**.

### Etapa 1 – Armazenamento Seguro e Escalável
- **Serviço AWS:** Amazon S3  
- **Foco da ferramenta:** Armazenamento de arquivos em nuvem  
- **Caso de uso:** Migrar relatórios de vendas, histórico de estoque e documentos fiscais para S3, reduzindo necessidade de servidores locais e custos de energia.  

### Etapa 2 – Computação Automatizada e Escalável
- **Serviço AWS:** Amazon EC2 + AutoScaling + AWS Lambda  
- **Foco da ferramenta:** Computação sob demanda e execução de funções serverless  
- **Caso de uso:**  
  - EC2 para hospedagem de sistemas de vendas em nuvem, com **AutoScaling** para ajustar recursos conforme demanda, evitando pagamento por capacidade ociosa.  
  - Lambda para automatizar alertas de estoque, produtos vencidos e envio de relatórios diários, reduzindo horas de trabalho manual.

### Etapa 3 – Monitoramento e Otimização de Recursos
- **Serviço AWS:** Amazon CloudWatch + Elastic Load Balancing (ELB)  
- **Foco da ferramenta:** Monitoramento de métricas, logs e balanceamento de carga  
- **Caso de uso:**  
  - CloudWatch para monitorar consumo de recursos e identificar desperdícios.  
  - ELB para distribuir a carga entre servidores EC2, evitando sobrecarga e garantindo que o sistema de vendas permaneça estável durante horários de pico.

### Etapa 4 – Banco de Dados Escalável e Seguro
- **Serviço AWS:** Amazon RDS (MySQL) + DynamoDB  
- **Foco da ferramenta:** Banco de dados relacional e NoSQL  
- **Caso de uso:**  
  - RDS para gerenciar dados de clientes, estoque e vendas com alta disponibilidade e backups automáticos.  
  - DynamoDB para registros rápidos, como histórico de acesso a promoções e consultas frequentes, garantindo performance e baixo custo.

---

## 4. Conclusão

A implementação dos serviços AWS na farmácia **Saúde+** trouxe os seguintes benefícios:

- **Redução de custos operacionais** com servidores locais e manutenção de hardware;  
- **Automação de processos** críticos, como controle de estoque e alertas de vencimento;  
- **Alta disponibilidade** e escalabilidade, garantindo que os sistemas de vendas funcionem mesmo em horários de pico;  
- **Monitoramento contínuo** do uso de recursos, permitindo ajustes rápidos e prevenção de desperdícios.

Recomenda-se a continuidade do uso das ferramentas implementadas e a exploração de serviços adicionais da AWS, como **Amazon Redshift para análise de dados e Amazon SNS para notificações automáticas**, para otimizar ainda mais os processos da farmácia.

---

## 5. Anexos

� Planilhas de análise de estoque antes e depois da implementação  
� Documentação de configuração dos serviços AWS  
� Prints do console AWS mostrando Lambda, S3 e CloudWatch  
� Manuais internos adaptados para processos na nuvem  

---

**Assinatura do Responsável pelo Projeto:**  
Lêda Trindade
