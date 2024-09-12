# Projeto: Implementação de Servidor DNS

## Descrição Geral

Este projeto tem como objetivo a implementação e configuração de um servidor DNS (Domain Name System) utilizando o software BIND (Berkeley Internet Name Domain) em um ambiente Linux, mais especificamente no Github Codespace. O BIND é um dos softwares DNS mais utilizados e serve como referência para a configuração de servidores DNS em ambientes de produção.

## O que é DNS?

O DNS (Domain Name System) é um sistema que traduz nomes de domínios legíveis por humanos (como `www.exemplo.com`) para endereços IP legíveis por máquinas (como `192.0.2.1`). Esse serviço é essencial para o funcionamento da internet, permitindo que os usuários acessem recursos e sites na web de maneira intuitiva, sem a necessidade de memorizar endereços IP.

### Componentes Básicos de um Servidor DNS

- **Zone File (Arquivo de Zona)**: Contém os registros DNS que apontam os domínios para seus respectivos endereços IP.
- **Registros DNS**: Tipos comuns de registros incluem:
  - `A`: Aponta um domínio para um endereço IPv4.
  - `AAAA`: Aponta um domínio para um endereço IPv6.
  - `CNAME`: Cria um alias de um domínio para outro.
  - `MX`: Define o servidor de e-mail responsável pelo recebimento de mensagens.
  - `NS`: Especifica os servidores DNS autoritativos para o domínio.
- **named.conf**: Arquivo de configuração principal do BIND, onde as zonas DNS e outras opções são definidas.

## Ferramentas Utilizadas

- **BIND (Berkeley Internet Name Domain)**: Software que implementa o protocolo DNS e permite a configuração de servidores DNS.
- **Linux (Github Codespace)**: O ambiente utilizado para a configuração e testes do servidor DNS.

## Considerações Finais
A configuração de um servidor DNS é uma habilidade crucial para administradores de redes e engenheiros de sistemas, permitindo o controle eficiente sobre a resolução de nomes de domínio em uma rede. Este projeto serve como uma introdução ao BIND e à administração de serviços DNS em um ambiente Linux, com foco na configuração, diagnóstico e solução de problemas.

## Desenvolvedores
Repositório público desenvolvido pelos estudantes Anderson Henrique Silva Santos	(matrícula SUAP 20232014040014), Lucas Pinheiro da Costa (matrícula SUAP 20231014040023) e Rogério Young Evaristo de Souza	(matrícula SUAP 20232014040017), alunos de Tecnologia em Análise e Desenvolvimento de Sistemas do IFRN - Instituto Federal do Rio Grande do Norte.
