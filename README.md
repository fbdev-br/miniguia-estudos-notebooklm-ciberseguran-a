# README: Projeto de Estudo em Cibersegurança 2026

## 1. Contexto e Objetivos
Este repositório é o resultado de uma imersão técnica sobre o cenário da Cibersegurança, com foco especial na transição para sistemas autônomos e as tendências previstas para 2026.
Objetivos de Estudo:
Compreender os pilares fundamentais da segurança (Tríade CIA) e a estratégia de defesa em camadas
.
Analisar o impacto da IA Agêntica (Agentic AI) como um novo vetor de ataque autônomo
.
Estudar a migração para a Criptografia Pós-Quântica (PQC) frente à ameaça Harvest Now, Decrypt Later (HNDL)
.
Mapear as mudanças regulatórias, incluindo o acordo de adequação de dados Brasil-União Europeia
.

## 2. Curadoria de Fontes

Para este estudo, foram selecionadas e processadas as seguintes fontes de alta relevância:
SentinelOne: 10 Cyber Security Trends For 2026 – Foco em automação de SOC e segurança de APIs
.
Acuvity.ai: 2026 Cybersecurity Predictions – Análise sobre o colapso da atribuição entre humanos e agentes
.
Rising Trends: 8 Cybersecurity Trends to Watch In 2026 – Dados estatísticos sobre tempo de invasão (breakout time)
.
Perícia Hacker (Transcrições de Vídeo): Curso prático sobre fundamentos, Phishing, Ransomware e segurança de rede
.
Relatórios Institucionais (IBM/Gartner): Visão executiva sobre governança de IA e resiliência organizacional
.

## 3. Engenharia de Prompts e "Cicatrizes"

Nesta seção, registro a evolução da interação para extrair o máximo de precisão das fontes.
Variações de Prompts e Resultados

**Prompt Inicial (Básico):**
"Ensine-me sobre segurança em camadas para iniciantes, do antivírus ao comportamento."

*Resultado:*
A segurança cibernética não depende de uma única ferramenta mágica, mas sim de uma estratégia de defesa em camadas. Como não existe um sistema 100% seguro, o objetivo é implementar múltiplos obstáculos para dificultar ao máximo a ação de um invasor
.
Aqui está o seu roteiro para construir uma base sólida, do nível técnico ao comportamental:
1. A Primeira Linha: Credenciais e Autenticação
A sua senha é a chave do seu "reino digital", mas ela sozinha não basta mais
.
Senhas Fortes: Esqueça padrões óbvios como datas de nascimento ou nomes de pets. Uma senha segura deve ter no mínimo 16 caracteres, misturando letras maiúsculas, minúsculas, números e símbolos
. Como é impossível memorizar tudo, utilize um gerenciador de senhas (como Bitwarden ou LastPass) para criar cofres criptografados
.
Autenticação de Dois Fatores (2FA): Esta é a sua defesa principal caso sua senha seja vazada
. Priorize aplicativos de autenticação (Google ou Microsoft Authenticator) em vez de SMS, pois o SMS é vulnerável a golpes de "SIM Swap" (clonagem de chip)
.
2. A Proteção do Perímetro: Redes e Roteadores
O roteador é a porta de entrada da sua casa digital e muitas vezes é negligenciado
.
Configuração do Roteador: Troque imediatamente as credenciais padrão (como admin/admin)
. Desative o recurso WPS e utilize criptografia WPA2 ou WPA3
.
Redes Públicas: Ao usar Wi-Fi de cafeterias ou aeroportos, seus dados podem ser interceptados por ataques de "Man-in-the-Middle"
. Nestes casos, o uso de uma VPN é obrigatório para criar um túnel criptografado para suas informações
.
3. As Muralhas do Dispositivo: Antivírus e Firewall
Eles formam a base técnica de proteção do seu computador ou smartphone
.
Antivírus: Atua como um guardião que escaneia arquivos em busca de assinaturas de malwares conhecidos e monitora comportamentos suspeitos em tempo real
.
Firewall: Funciona como um "controlador de portões", monitorando o tráfego de rede e bloqueando conexões não autorizadas
. Juntos, antivírus e firewall podem reduzir em até 80% o risco de infecção
.
4. Higiene de Software e Aplicativos
Malwares muitas vezes entram por falta de manutenção ou fontes duvidosas
.
Atualizações Constantes: Mantenha o sistema operacional, navegadores e aplicativos sempre atualizados. As atualizações corrigem vulnerabilidades que hackers exploram para invadir sistemas
.
Cuidado com Apps: Baixe softwares apenas de fontes oficiais (Play Store, App Store)
. Verifique as permissões: não faz sentido um aplicativo de calculadora pedir acesso à sua câmera ou contatos
.
5. A Camada Humana: Comportamento e Mentalidade
Este é o elo mais crítico: 95% das violações de segurança são causadas por erro humano
.
Engenharia Social: Hackers usam a psicologia para manipular você através do medo, urgência ou curiosidade
. Desconfie de ofertas "boas demais para ser verdade" ou mensagens urgentes pedindo códigos
.
Navegação Segura: Antes de clicar, passe o mouse sobre o link para ver o destino real
. Verifique se o site usa HTTPS (o cadeado na barra), embora sites de golpes também possam usá-lo, a ausência dele é um sinal de alerta imediato
.
Pausar e Pensar: A regra de ouro é: se não solicitou o contato ou o link, não clique e não forneça dados
.
A Rede de Segurança Final: Backup
Se todas as camadas falharem (como em um ataque de Ransomware que sequestra seus dados), o backup é o que salvará você
. Siga a regra 3-2-1:
Tenha 3 cópias dos dados.
Em 2 mídias diferentes (ex: HD externo e Nuvem).
Com 1 cópia fora do local físico (em um servidor remoto ou nuvem)
.
Seguindo essas camadas, você deixa de ser um alvo fácil e passa a ter uma postura proativa na sua proteção digital.

**Prompt Refinado (Com Contexto):**
"Atue como um especialista em cibersegurança com experiência prática em proteção de sistemas, análise de vulnerabilidades e resposta a incidentes. Seu objetivo é me ensinar de forma progressiva e aplicada.


Estruture o conteúdo como um plano de aprendizado dividido em níveis (iniciante, intermediário e avançado), cobrindo os seguintes tópicos:


Fundamentos de cibersegurança (conceitos básicos, ameaças comuns, princípios como confidencialidade, integridade e disponibilidade)
Redes e protocolos (TCP/IP, DNS, HTTP/HTTPS)
Criptografia (conceitos, criptografia simétrica e assimétrica, hash)
Segurança em sistemas (Linux/Windows, hardening)
Testes de invasão (pentest) e ethical hacking
Engenharia social
Segurança em aplicações web (OWASP Top 10)
Resposta a incidentes e forense digital


Para cada tópico:


Explique o conceito de forma clara e didática
Dê exemplos reais ou práticos
Sugira exercícios práticos ou desafios
Indique ferramentas relevantes (ex: Wireshark, Nmap, Metasploit)
Aponte erros comuns e boas práticas


Inclua também:


Simulações de cenários reais (ex: ataque de phishing, invasão a servidor, vazamento de dados)
Perguntas para testar meu conhecimento ao final de cada módulo
Um projeto final prático integrando os conhecimentos adquiridos


Adapte o nível de dificuldade conforme meu progresso e faça perguntas para avaliar meu entendimento antes de avançar."

*Resultado:*
Como seu mentor em cibersegurança, preparei um plano de aprendizado progressivo projetado para levar você do zero ao domínio das tecnologias de ponta que definem o cenário de 2026
.
Este roteiro está dividido em três níveis, integrando teoria, ferramentas e simulações práticas. Vamos começar com o alicerce fundamental.

--------------------------------------------------------------------------------
Nível 1: Iniciante – O Alicerce da Proteção
Neste estágio, focaremos na compreensão do que estamos protegendo e de quem estamos nos defendendo.
1. Fundamentos e a Tríade CIA
A cibersegurança baseia-se em três pilares essenciais:
Confidencialidade: Garantir que apenas pessoas autorizadas acessem os dados (ex: controle de acesso e biometria)
.
Integridade: Garantir que a informação não seja alterada de forma indevida (ex: hashes de arquivos)
.
Disponibilidade: Garantir que os sistemas e dados estejam prontos para uso sempre que necessário (ex: proteção contra ataques DDoS)
.
Exemplo Real: Se um invasor deletar o banco de dados de um hospital, ele quebrou a Disponibilidade. Se ele alterar o tipo sanguíneo de um paciente no sistema, ele violou a Integridade
.
2. Ameaças Comuns (Malware)
Você deve conhecer as "famílias" de códigos maliciosos
:
Vírus e Worms: Programas que se replicam para infectar arquivos ou redes inteiras
.
Trojans (Cavalos de Troia): Disfarçam-se de programas úteis para abrir "portas dos fundos" (backdoors) no sistema
.
Ransomware: O "sequestro digital" que criptografa seus dados e exige resgate em criptomoedas
.
Spyware: Monitora silenciosamente suas teclas (keylogging) e atividades
.
Simulação de Cenário: Você recebe um e-mail com o assunto "Fatura Pendente" contendo um anexo .exe ou um link. Ao clicar, um Trojan é instalado, permitindo que o hacker veja sua webcam e roube suas senhas bancárias
.
3. Engenharia Social: A Psicologia do Hacking
É a manipulação psicológica para obter dados
. Os hackers exploram gatilhos como Urgência ("Sua conta será bloqueada em 10 minutos!"), Autoridade ("Aqui é do suporte técnico do banco") ou Simpatia
.
Vishing: Phishing por voz (ligações falsas)
.
Smishing: Phishing por SMS ou WhatsApp
.
Deepfakes: Uso de IA para clonar vozes ou rostos em tempo real para fraudes complexas
.

--------------------------------------------------------------------------------
Exercícios Práticos (Nível 1)
Higiene de Senhas: Instale um gerenciador de senhas (ex: Bitwarden) e gere uma senha mestra de 20 caracteres combinando símbolos, números e letras
.
Autenticação: Ative o 2FA (Autenticação de Dois Fatores) em seu e-mail principal, priorizando aplicativos como o Google Authenticator em vez de SMS (para evitar golpes de clonagem de chip/SIM Swap)
.
Análise de Links: Utilize o VirusTotal ou URLScan para verificar se um link que você recebeu é malicioso antes de clicar
.
Erros Comuns: Usar a mesma senha para tudo ou confiar que um site é seguro apenas por ter o cadeado (HTTPS), já que sites de phishing também podem usá-lo
.

--------------------------------------------------------------------------------
Nível 2: Intermediário – Infraestrutura e Defesa Ativa
Aqui, avançaremos para o funcionamento técnico da internet e dos sistemas.
Redes e Protocolos: Entender como os dados viajam via TCP/IP e as portas padrão (80 para HTTP, 443 para HTTPS, 53 para DNS, 22 para SSH)
.
Criptografia: Diferença entre simétrica (mesma chave para cifrar/decifrar) e assimétrica (par de chaves pública/privada), além da importância da Criptografia Pós-Quântica (PQC) para o futuro
.
Hardening de Sistemas: Configurar roteadores para desativar o WPS, atualizar firmwares e isolar redes de convidados ou dispositivos IoT
.
Ferramentas Relevantes:
Wireshark: Para capturar e analisar pacotes de rede (sniffing)
.
Nmap: Para descobrir quais portas e serviços estão abertos em um servidor
.

--------------------------------------------------------------------------------
Nível 3: Avançado – Operações Ofensivas e IA
No topo da pirâmide, entraremos no cenário atual de 2026.
IA Agêntica (Agentic AI): Aprender a lidar com agentes de IA que atacam de forma autônoma em "velocidade de máquina", reduzindo o tempo de invasão para menos de uma hora
.
Testes de Invasão (Pentest): Usar o Metasploit para testar vulnerabilidades conhecidas em ambientes controlados
.
OWASP Top 10: Dominar as falhas mais comuns em aplicações web, como SQL Injection e Broken Access Control
.
Resposta a Incidentes: Seguir playbooks para Isolar sistemas infectados, Erradicar a ameaça e Recuperar dados via backups (seguindo a regra 3-2-1)
.

--------------------------------------------------------------------------------
Pergunta de Avaliação para Prosseguirmos:
Para garantir que a base está sólida: Imagine que você recebeu um código de autenticação por SMS que você não solicitou e, logo em seguida, recebe uma ligação de alguém se passando pelo suporte do seu banco pedindo esse código para "cancelar uma transação suspeita". Quais pilares da Tríade CIA estão em risco e qual técnica de ataque está sendo usada contra você?

**Prompt Estratégico (Análise de Tendências):**
"Converse sobre o que as fontes dizem sobre Ataques Autônomos no contexto de Agentic AI."
Referência: Extraiu o dado crítico de que o tempo de invasão caiu para 48 minutos, com casos de 51 segundos
.
Troubleshooting (Solução de Problemas)
Dificuldade: A IA tendia a misturar conceitos de IA generativa simples com IA agêntica.
Ajuste: Foi necessário forçar a distinção no prompt, pedindo explicitamente a definição de "autonomia de decisão" citada nas fontes de 2026
. Isso evitou respostas superficiais sobre apenas "geração de texto".

**4. Miniguia de Estudo (Entrega Final)**

Resumo Estruturado: O Novo Cenário de 2026
IA Agêntica como Atacante: A IA não apenas auxilia humanos; ela agora planeja e executa ataques em múltiplas etapas autonomamente, aprendendo com falhas em tempo real
.
Identidade é o Novo Perímetro: O perímetro de rede tradicional desapareceu. A segurança agora foca em Identidades de Máquina (que superam as humanas em 82 para 1) e arquiteturas Zero Trust
.
Resiliência Quântica (HNDL): Adversários estão roubando dados criptografados hoje para descriptografá-los em 3 a 5 anos. A migração para algoritmos como o ML-KEM (FIPS 203) é urgente
.
Cadeia de Suprimentos de IA: O envenenamento de um único agente pode contaminar 87% de uma rede corporativa em menos de 4 horas
.
*Glossário de Conceitos Chave*

Tríade CIA: Confidencialidade, Integridade e Disponibilidade
.
Breakout Time: Tempo entre o acesso inicial e a movimentação lateral
.
HNDL (Harvest Now, Decrypt Later): Estratégia de interceptação de dados para futura quebra quântica
.
Shadow AI: Uso de ferramentas de IA não aprovadas pela organização
.
IA Agêntica: Sistemas que definem objetivos e agem sem intervenção humana constante
.
*Prompts Reutilizáveis para Revisão*
"Resuma os riscos de segurança física em ambientes industriais (OT) causados por agentes de IA maliciosos em 2026."
"Explique o impacto do acordo Brasil-UE na circulação de dados pessoais entre jurisdições conforme a Resolução CD/ANPD nº 32/2026."
"Quais são as 5 camadas principais de defesa para um usuário doméstico segundo as transcrições do Perícia Hacker?"
