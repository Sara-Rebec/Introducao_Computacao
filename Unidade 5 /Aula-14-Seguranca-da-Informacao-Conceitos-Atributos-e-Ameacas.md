#  Aula 14 – Segurança da Informação: Conceitos, Atributos e Ameaças

##  Integrantes do Grupo
- Sara Rebeca do Rosario Soares

---

#  1. Conceitos Fundamentais

##  Definição de Segurança da Informação

Segundo a norma **ISO/IEC 27000:2018**, Segurança da Informação é a proteção das informações contra diversos tipos de ameaças, garantindo a continuidade do negócio, reduzindo riscos e protegendo dados contra acessos não autorizados.

Seu objetivo principal é preservar os dados e sistemas utilizados por pessoas e organizações.

---

#  Principais Atributos da Segurança da Informação

##  Confidencialidade

Garantia de que as informações sejam acessadas apenas por pessoas autorizadas.

###  Exemplo
Senhas bancárias acessadas somente pelo usuário e pela instituição financeira.

---

##  Integridade

Garantia de que os dados não sejam alterados indevidamente.

###  Exemplo
Um documento acadêmico não pode sofrer alterações sem autorização.

---

## Disponibilidade

Garantia de que sistemas e informações estejam disponíveis quando necessários.

###  Exemplo
Um site de banco online precisa funcionar 24 horas por dia.

---

##  Privacidade

Relaciona-se à proteção dos dados pessoais dos usuários.

###  Exemplo
Empresas devem proteger CPF, endereço e informações pessoais de clientes.

---

#  2. Ameaças e Vulnerabilidades

##  Ameaças Digitais

As ameaças digitais são ações maliciosas que podem comprometer sistemas, dados e usuários.

---

##  Phishing

Golpe que tenta enganar usuários para roubar informações pessoais, senhas ou dados bancários.

###  Exemplo
E-mails falsos imitando bancos ou redes sociais.

---

##  Malware

Programas maliciosos criados para causar danos ou roubar informações.

###  Tipos comuns
- Vírus
- Worms
- Ransomware
- Spyware

###  Exemplo
Um ransomware pode bloquear arquivos e exigir pagamento para liberá-los.

---

##  Engenharia Social

Manipulação psicológica utilizada para convencer pessoas a fornecer informações sigilosas.

###  Exemplo
Um criminoso se passando por funcionário da empresa para obter senhas.

---

#  Vulnerabilidades

##  Vulnerabilidades Técnicas
- Sistemas desatualizados
- Senhas fracas
- Falhas em softwares
- Redes sem proteção

---

##  Vulnerabilidades Humanas
- Compartilhamento de senhas
- Falta de treinamento
- Cliques em links suspeitos
- Uso inadequado de sistemas

---

#  Impactos Potenciais

As ameaças podem causar:
- Vazamento de dados
- Perdas financeiras
- Interrupção de serviços
- Danos à reputação da empresa
- Roubo de informações pessoais

---

#  3. Estudo de Cenário

#  Opção A – Ataque Cibernético Real

##  Caso: WannaCry (2017)

O ataque ransomware **WannaCry** ocorreu em maio de 2017 e afetou milhares de computadores em diversos países.

O malware explorava uma vulnerabilidade no sistema operacional Windows, espalhando-se rapidamente pelas redes.

---

##  Vulnerabilidade Explorada

A falha utilizada estava relacionada ao protocolo SMB do Windows, permitindo acesso não autorizado aos computadores vulneráveis.

Muitos sistemas estavam desatualizados e sem correções de segurança.

---

##  Impactos Causados

O ataque causou:
- Paralisação de hospitais
- Interrupção de empresas
- Perda de acesso a arquivos
- Prejuízos financeiros milionários

O ransomware criptografava os arquivos e exigia pagamento em criptomoedas.

---

##  Medidas de Mitigação

###  Atualização de sistemas
Aplicação de patches de segurança.

###  Backup de dados
Criação de cópias de segurança periódicas.

### Antivírus e firewall
Uso de ferramentas de proteção.

###  Treinamento de usuários
Conscientização sobre ameaças digitais.

---

# Organização dos Arquivos

```txt
Grupo1_AtaqueReal/
│
├── conceitos.md
├── ameacas.md
├── estudo_de_caso.md
└── README.md
```

---

#  Conclusão

A Segurança da Informação é essencial para proteger dados, sistemas e usuários contra ameaças digitais. Os atributos de confidencialidade, integridade, disponibilidade e privacidade são fundamentais para garantir proteção e confiabilidade nas informações.

Além disso, compreender as ameaças e vulnerabilidades permite que empresas e usuários adotem medidas preventivas mais eficientes.

---

#  Reflexão Individual

##  “Por que o fator humano é considerado o elo mais frágil da segurança da informação?”

O fator humano é considerado o elo mais frágil da segurança da informação porque muitas falhas acontecem devido a erros das próprias pessoas. Mesmo com sistemas modernos e ferramentas avançadas de proteção, usuários podem clicar em links maliciosos, utilizar senhas fracas ou compartilhar informações sem perceber os riscos envolvidos.

Os criminosos digitais frequentemente utilizam técnicas de engenharia social para manipular emoções e enganar usuários. Dessa forma, a falta de atenção, treinamento e conscientização pode comprometer toda a segurança de uma organização.

Por isso, além da tecnologia, é fundamental investir na educação e capacitação das pessoas para reduzir riscos e aumentar a proteção das informações.

# Referências 

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR ISO/IEC 27000:2018 – Tecnologia da informação — Técnicas de segurança — Sistemas de gestão da segurança da informação — Visão geral e vocabulário**. Rio de Janeiro: ABNT, 2018. Disponível em: <https://www.abntcatalogo.com.br/>. Acesso em: 22 maio 2026.

MICROSOFT. **MS17-010: atualização de segurança para Windows SMB Server**. Microsoft Security Response Center, 2017. Disponível em: <https://learn.microsoft.com/pt-br/security-updates/securitybulletins/2017/ms17-010>. Acesso em: 22 maio 2026.

KASPERSKY. **WannaCry ransomware: o que é e como se proteger**. Kaspersky, 2024. Disponível em: <https://www.kaspersky.com.br/resource-center/threats/ransomware-wannacry>. Acesso em: 22 maio 2026.

CISCO. **What Is Malware?** Cisco. Disponível em: <https://www.cisco.com/c/en/us/products/security/what-is-malware.html>. Acesso em: 22 maio 2026.

FORTINET. **What is Phishing?** Fortinet. Disponível em: <https://www.fortinet.com/resources/cyberglossary/phishing>. Acesso em: 22 maio 2026.

IBM. **What is Social Engineering?** IBM. Disponível em: <https://www.ibm.com/topics/social-engineering>. Acesso em: 22 maio 2026.

CARTILHA CERT.BR. **Segurança para Internet**. Centro de Estudos, Resposta e Tratamento de Incidentes de Segurança no Brasil. Disponível em: <https://cartilha.cert.br/>. Acesso em: 22 maio 2026.
