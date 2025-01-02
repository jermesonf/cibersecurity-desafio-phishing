# Phishing para captura de senhas do Instagram

Utilizando o Kali Linux e o Social-Engineer Toolkit (SET), realizei um ataque de phishing bem-sucedido. Clonando um site legítimo, capturei credenciais de e-mail e senha dos usuários que acessaram a página falsa. Este processo envolveu a criação de uma réplica exata do site alvo, enganando os usuários para que inserissem suas informações confidenciais, que foram então armazenadas para análise posterior.

| Ferramenta          | Descrição                                                                 |
|---------------------|--------------------------------------------------------------------------|
| Kali Linux          | Sistema operacional especializado em testes de penetração e segurança.   |
| Social-Engineer Toolkit (SET) | Ferramenta para realizar ataques de engenharia social.          |

## Configurando o Phishing no Kali Linux
Obtendo o IP da máquina: ``ifconfig``
Acesso root: ``sudo su``
Iniciando o setoolkit: ``setoolkit``
Tipo de ataque: ``Social-Engineering Attacks``
Vetor de ataque: ``Web Site Attack Vectors``
Método de ataque: ``Credential Harvester Attack Method``
Método de ataque: ``Site Cloner``
URL para clone: ``http://www.instagram.com``

### RESULTADO

![Screenshot 2025-01-01 204808](https://github.com/user-attachments/assets/960d1001-681c-4d5d-8f46-0f31a2cd0d4a)
