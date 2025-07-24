# Relatório do Projeto: Plataforma Virtual para Farmácia Fictícia na AWS

## 1. Introdução  
Este projeto consiste na criação de uma plataforma virtual para uma farmácia fictícia utilizando a infraestrutura da Amazon Web Services (AWS). O objetivo é aplicar conhecimentos práticos sobre serviços de nuvem para resolver desafios comuns enfrentados em sistemas reais.

## 2. Arquitetura da Solução  
A solução utiliza os seguintes serviços da AWS:  
- **EC2:** servidores virtuais para hospedar a aplicação web.  
- **S3:** armazenamento dos arquivos estáticos, como imagens e documentos.  
- **RDS:** banco de dados gerenciado para armazenar informações da farmácia, clientes e pedidos.  
- **CloudWatch:** monitoramento básico da infraestrutura.  

## 3. Desafios Enfrentados e Soluções  
- **Escalabilidade:** Foi utilizado o Auto Scaling para ajustar automaticamente a quantidade de servidores conforme a demanda.  
- **Segurança:** Configuração de grupos de segurança para controlar o acesso às instâncias EC2.  
- **Alta Disponibilidade:** Implantação do banco de dados RDS em modo Multi-AZ para garantir maior disponibilidade.  

## 4. Conclusão  
O projeto permitiu aplicar conceitos fundamentais da AWS e entender como diferentes serviços podem ser integrados para construir uma solução prática e escalável. Além disso, os desafios encontrados ajudaram a aprimorar o conhecimento sobre segurança, disponibilidade e escalabilidade em nuvem.
