# simulação-ransomware-keylogger

Este repositório contém **documentação completa, reflexões e simulações seguras** sobre o funcionamento de:

- Ransomware (criptografia + mensagem de “resgate”)
- Keylogger (captura de atividade – simulado, sem registrar teclas reais)
- Medidas de defesa e prevenção

⚠ **IMPORTANTE:**  
Este projeto **não contém malware real**.  
Todos os códigos aqui são **simbólicos, seguros e executam apenas simulações em ambientes controlados**, seguindo práticas éticas de cibersegurança.

---

## 🎯 Objetivo do Projeto
Demonstrar entendimento técnico sobre:

- Funcionamento de ataques reais (de forma teórica)
- Simulação ética e segura de comportamentos de malware
- Boas práticas de defesa, detecção e resposta a incidentes

---

# 🧩 1. Ransomware Simulado
📁 Pasta: `simulacao_ransomware/`

### O que foi documentado:
- Como ransomwares funcionam (fluxo real vs seguro)
- Criação de arquivos de teste
- Um **script simulado de criptografia** (que opera SOMENTE em uma pasta de teste)
- Processo reversível de descriptografia
- Mensagem de “resgate” simulada
- Medidas de prevenção

### 🧪 Objetivo da simulação
Aprender:
- Conceitos de criptografia (AES, chave, nonce)
- Como ransomwares afetam arquivos
- Fluxos de operação
- Boas práticas para criação de backups

---

# 🎹 2. Keylogger Simulado
📁 Pasta: `simulacao_keylogger/`

### O que foi documentado:
- Funcionamento teórico de keyloggers reais
- Script **seguro** que monitora atividade:
  - Conta pressionamentos
  - Monitora frequência
  - Categoriza eventos (letra, número, controle)
  - **Não grava nenhuma tecla real**
- Explicação de como keyloggers reais se escondem
- Fluxo de envio simulado por e-mail

---

# 🛡 3. Reflexão sobre Defesa
📁 Pasta: `defesa/`

Nesta seção, eu documento:

### ✔ Medidas de prevenção contra ransomware
- Backup 3-2-1
- Antivírus e EDR
- Bloqueios de macros
- Controle de privilégios
- Updates e patches

### ✔ Medidas contra keyloggers
- Detecção de hooks
- Monitoramento de integridade
- Hardening de SO
- Segurança no navegador

### ✔ Boas práticas gerais
- Firewalls
- Sandboxing
- Zero Trust
- Conscientização do usuário
- Ferramentas de análise (Sysmon, YARA, Procmon)

---

# 📸 Prints e Diagramas
Alguns arquivos (opcionais):

- Fluxo de um ransomware
- Fluxo de um keylogger
- Demonstrações da simulação
- Estrutura de criptografia segura

---

# 📌 Como Executar as Simulações (Opcional)
### Ransomware Simulado
- Crie a pasta `lab_ransom_test`
- Teste o script seguro (exemplo dentro da pasta)
- Criptografe e descriptografe os arquivos de teste

### Keylogger Simulado
- Execute o script seguro
- Observe apenas os *eventos*, não as teclas

---

# 📚 Tecnologias Utilizadas
- Python (somente scripts seguros)
- Criptografia com `cryptography`
- Simulações com `pynput`
- Markdown para documentação

---

# 🤝 Contribuição
Este projeto é educativo.  
Colaborações são bem-vindas desde que sigam diretrizes éticas.

---

# 🏁 Conclusão
Este repositório demonstra:

- Entendimento profundo sobre ransomware e keyloggers
- Compreensão técnica e ética
- Capacidade de análise e documentação
- Maturidade no uso seguro de simulações

Esse projeto atende aos requisitos da DIO para “Entregar Projeto”.

---