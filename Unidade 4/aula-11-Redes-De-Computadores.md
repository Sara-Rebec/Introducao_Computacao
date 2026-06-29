# Aula 11 – Redes de Computadores: Topologias, Dispositivos e Meios

## Nome(s) do(s) estudante(s): Sara Rebeca do Rosario Soares Matrícula(s): 22610249 

## Objetivo

Entender a organização física e lógica das redes, identificar os principais dispositivos e reconhecer os diferentes meios de transmissão.


# 1. Diagramas de Topologias

As topologias de rede representam a forma como os dispositivos estão conectados entre si.

| Topologia | Características | Vantagens | Desvantagens |
|------------|-----------------|-----------|--------------|
| **Estrela (Star)** | Todos os dispositivos são conectados a um equipamento central (switch, hub ou roteador). | Fácil manutenção, identificação rápida de falhas e boa performance. | Se o dispositivo central falhar, toda a rede é interrompida. |
| **Barramento (Bus)** | Todos os dispositivos compartilham um único cabo principal. | Baixo custo e instalação simples. | Uma falha no cabo principal pode interromper toda a comunicação. |
| **Anel (Ring)** | Os dispositivos são conectados em forma de círculo, enviando dados de um para outro. | Comunicação organizada e sem colisões. | A falha de um dispositivo pode afetar toda a rede. |
| **Malha (Mesh)** | Cada dispositivo possui conexão direta com vários outros dispositivos. | Alta confiabilidade e redundância. | Alto custo de instalação e maior complexidade. |

---

# 2. Quadro Comparativo de Dispositivos

| Dispositivo | Função Principal | Vantagens | Limitações | Exemplo de Uso |
|--------------|------------------|-----------|-------------|----------------|
| **Hub** | Envia os dados para todos os dispositivos conectados. | Simples e barato. | Baixa segurança e desempenho. | Redes antigas ou pequenos laboratórios. |
| **Switch** | Envia os dados apenas para o dispositivo de destino. | Maior velocidade, eficiência e segurança. | Custo maior que o hub. | Redes domésticas e empresariais. |
| **Roteador** | Interliga redes diferentes e fornece acesso à Internet. | Compartilha a conexão com vários dispositivos e realiza o roteamento dos dados. | Configuração mais complexa. | Residências, empresas e instituições de ensino. |

---

# 3. Meios de Transmissão

## Meios Guiados (Com Fio)

| Meio | Características | Exemplo de Uso |
|------|-----------------|----------------|
| **Par Trançado** | Cabo de cobre formado por pares de fios entrelaçados. | Redes domésticas e escritórios. |
| **Cabo Coaxial** | Cabo com blindagem contra interferências. | TV a cabo e algumas redes antigas. |
| **Fibra Óptica** | Transmite dados por pulsos de luz, oferecendo alta velocidade. | Provedores de Internet e redes corporativas. |

## Meios Não Guiados (Sem Fio)

| Meio | Características | Exemplo de Uso |
|------|-----------------|----------------|
| **Wi-Fi** | Comunicação por ondas de rádio. | Internet residencial e empresarial. |
| **Bluetooth** | Comunicação sem fio de curto alcance. | Celular e fone de ouvido. |
| **Satélite** | Comunicação de longa distância. | Internet em áreas remotas. |
| **Infravermelho** | Comunicação por luz infravermelha. | Controles remotos. |

---

# Reflexão Individual

## Qual topologia seria mais adequada para a rede da sua residência e por quê?

A topologia em estrela é a mais adequada para uma residência, pois todos os dispositivos são conectados a um roteador central. Esse modelo facilita a instalação, a manutenção e a identificação de falhas, além de permitir que os demais dispositivos continuem funcionando caso apenas um apresente problemas. Por isso, é a topologia mais utilizada em redes domésticas.

-

# Referências

# Referências

- TANENBAUM, A. S.; FEAMSTER, N.; WETHERALL, D. J. **Redes de Computadores**. 6. ed. São Paulo: Bookman, 2021.

- KUROSE, James F.; ROSS, Keith W. **Redes de Computadores e a Internet: Uma Abordagem Top-Down**. 8. ed. São Paulo: Pearson, 2022.

- CISCO NETWORKING ACADEMY. **Introduction to Networks (ITN)**. Cisco Networking Academy. Disponível em: https://www.netacad.com/. 

- Material da disciplina de Introdução à Computação.
