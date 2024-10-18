# 5 Scripts para Automação na AWS

Este repositório contém cinco scripts úteis para automação de tarefas comuns na Amazon Web Services (AWS). Cada script aborda uma funcionalidade específica, facilitando a gestão e otimização de recursos. Abaixo, você encontrará uma breve descrição de cada um deles.

## Scripts

### 1. Criando Instâncias EC2 com Python
Um script que utiliza a biblioteca Boto3 para provisionar instâncias EC2 de forma programática. Permite definir parâmetros como tipo de instância, imagem (AMI), segurança e muito mais.

**Dependências:**
- Python 3.x
- Boto3

### 2. Reduzindo o Tamanho de Imagens dentro do S3
Este script otimiza as imagens armazenadas no Amazon S3, reduzindo seu tamanho sem perda significativa de qualidade. Utiliza a biblioteca Pillow para processamento de imagens.

**Dependências:**
- Python 3.x
- Boto3
- Pillow

### 3. Backup Programado de Instâncias EC2
Um script que configura backups automáticos de instâncias EC2 utilizando snapshots. Permite agendar a frequência dos backups e escolher quais instâncias incluir.

**Dependências:**
- Python 3.x
- Boto3
- Cron (para agendamento)

### 4. Ligar/Desligar Máquinas EC2
Este script permite ligar ou desligar instâncias EC2 de acordo com a necessidade. É ideal para economizar custos em ambientes de desenvolvimento e teste.

**Dependências:**
- Python 3.x
- Boto3

### 5. Backup das Tabelas do Banco de Dados DynamoDB
Um script que realiza backups programados das tabelas do DynamoDB, garantindo a integridade e a segurança dos dados.

**Dependências:**
- Python 3.x
- Boto3

## Como Usar

1. **Clone o Repositório:**
   git clone git@github.com:ellydamicaella/AWS-Automator.git
   

2. **Instale as Dependências:**
   Certifique-se de ter o Python e o pip instalados, e instale as bibliotecas necessárias:
   pip install boto3 pillow
   

3. **Configurações da AWS:**
   Configure suas credenciais da AWS usando o AWS CLI.

4. **Execute o Script Desejado:**
   Navegue até o diretório do script e execute-o conforme necessário.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Contato

Para dúvidas ou sugestões, entre em contato através do seu e-mail, linkedin ou GitHub.

 Email: ellydamicaella810@gmail.com
 Linkedin: https://www.linkedin.com/in/ellyda-santana-62a580223/



