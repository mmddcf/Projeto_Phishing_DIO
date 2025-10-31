# Projeto_Phishing_DIO
Simulação educativa de phishing usando SEToolkit para criar página falsa da DIO.me em ambiente isolado. 
Objetivo: entender vetores de engenharia social, documentar ataques e mitigações. 
Uso estritamente educativo — não utilizar para fins ilícitos.

Ferramentas utilizadas para o desafio

    • Virtual Box
    • Kali Linux
    • Setoolkit

Como configurar o phishing

    1. Como entrar no root: digite “sudo su” no emulador de terminal
    2. Acessar o Setoolkit: digite “setoolkit”
    3. Tipo de ataque: Social-Engineering Attacks, digitando “1”
    4. Vetor de ataque: Web Site Attack Vectors, digitando “2”
    5. Método de ataque: Credential Harvester Attack Method, digitando “3”
    6. Método de Ataque: Site Cloner, digitando “2”
    7. Neste caso o próprio Setoolkit irá buscar e mostrar o ip da máquina: aparte “enter”
    8. Digite ou cole a URL a ser clonada: https://auth.dio.me/realms/master/protocol/openid-connect/auth?client_id=spa-core-client&redirect_uri=https%3A%2F%2Fweb.dio.me%2F&state=94eb078b-84b1-4874-8559-c6e9cb1ee5e2&response_mode=fragment&response_type=code&scope=openid&nonce=183726fc-9525-44a8-b612-75fe2c9ec98b

Resultado esperado

<img width="1175" height="171" alt="image" src="https://github.com/user-attachments/assets/60f07040-0e23-4c34-9b54-03aadfdf07d4" />
