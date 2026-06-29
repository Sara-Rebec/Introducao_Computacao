


# Aula 12 – Internet: História, Conceitos, Protocolos e Navegadores

## Nome(s) do(s) estudante(s): Sara Rebeca do Rosario Soares Matrícula(s): 22610249

## Objetivo

Compreender a origem e evolução da Internet, seus conceitos fundamentais, principais protocolos de comunicação e o papel dos navegadores.

---

# 1. História da Internet

A Internet surgiu a partir da **ARPANET**, uma rede criada no final da década de 1960 pelo Departamento de Defesa dos Estados Unidos com o objetivo de conectar computadores e garantir a troca de informações entre instituições de pesquisa.

Durante as décadas de 1970 e 1980, a rede foi expandida para universidades e centros de pesquisa, contribuindo para o desenvolvimento de novas tecnologias de comunicação.

Na década de 1990, a Internet tornou-se comercial e passou a ser utilizada pelo público em geral. Nesse período, **Tim Berners-Lee** criou a **World Wide Web (WWW)**, permitindo o acesso às páginas por meio de navegadores e tornando a navegação muito mais simples e acessível.

---

# 2. Conceitos Fundamentais

## Internet x Web

- **Internet:** infraestrutura mundial formada por milhões de computadores e redes interligadas.
- **Web (WWW):** serviço que utiliza a Internet para disponibilizar páginas e conteúdos acessados por navegadores.

## Arquitetura Cliente-Servidor

Na arquitetura cliente-servidor, o **cliente** (computador ou smartphone) faz uma solicitação a um **servidor**, que processa o pedido e envia a resposta.

**Exemplo:**

- Cliente: navegador Google Chrome.
- Servidor: servidor do site da UFRN.
- Resposta: página da UFRN exibida no navegador.

## Endereço IP

O endereço IP identifica um dispositivo conectado à rede.

**Exemplos:**

- IPv4: `192.168.1.10`
- IPv6: `2001:0db8:85a3::8a2e:0370:7334`

---

# 3. Protocolos

| Protocolo | Função | Exemplo |
|-----------|--------|----------|
| **TCP/IP** | Conjunto de protocolos responsável pela comunicação entre dispositivos na Internet. | Acesso a sites e envio de dados pela rede. |
| **HTTP/HTTPS** | Responsável pela transferência de páginas da Web. O HTTPS utiliza criptografia para maior segurança. | Acesso ao Google, UFRN e outros sites. |
| **DNS** | Traduz nomes de domínio em endereços IP. | Converter `www.google.com` para seu endereço IP. |
| **FTP** | Utilizado para envio e recebimento de arquivos entre computadores. | Upload de arquivos para um servidor. |

---

# 4. Navegadores

Os navegadores são programas responsáveis por interpretar os códigos **HTML**, **CSS** e **JavaScript**, permitindo que as páginas da Web sejam exibidas corretamente ao usuário.

## Principais motores de renderização

| Motor | Navegadores |
|--------|-------------|
| **Blink** | Google Chrome e Microsoft Edge |
| **Gecko** | Mozilla Firefox |
| **WebKit** | Safari |

---

# 5. Exercício Prático – Análise de Protocolos

Foi realizada uma análise utilizando o **Inspetor do Navegador (F12)**, na aba **Network**, durante o acesso a um site.

### Exemplo de Request

```http
GET / HTTP/1.1
Host: www.ufrn.br
```

### Exemplo de Response

```http
HTTP/1.1 200 OK
Content-Type: text/html
```

### Status Code Analisado

- **200 OK** – Indica que a requisição foi processada com sucesso e o servidor retornou o conteúdo solicitado.

---

# Reflexão Individual

## Qual protocolo você considera mais essencial para o funcionamento da Internet e por quê?

O protocolo **TCP/IP** pode ser considerado o mais essencial para o funcionamento da Internet, pois ele estabelece as regras para que os dispositivos possam se comunicar de forma organizada e confiável. Sem esse conjunto de protocolos, a troca de informações entre computadores não seria possível, comprometendo o funcionamento dos demais serviços, como navegação na Web, envio de e-mails e transferência de arquivos.

---

# Referências

- TANENBAUM, A. S.; FEAMSTER, N.; WETHERALL, D. J. **Redes de Computadores**. 6. ed. São Paulo: Bookman, 2021.

- KUROSE, James F.; ROSS, Keith W. **Redes de Computadores e a Internet: Uma Abordagem Top-Down**. 8. ed. São Paulo: Pearson, 2022.

- CERN. **A Brief History of the Web**. Disponível em: https://home.cern/science/computing/birth-web

- Cisco Networking Academy. **Introduction to Networks**. Disponível em: https://www.netacad.com/

````

Esse formato fica limpo, organizado e no mesmo padrão das Aulas 10 e 11 que você fez.

