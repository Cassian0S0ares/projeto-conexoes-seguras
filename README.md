# Projeto Conexões Seguras

**Visão geral**  
Projeto educacional de cybersecurity que demonstra, de forma prática, três áreas fundamentais de redes e segurança da informação. O objetivo é oferecer exemplos claros, documentação e artefatos (PDFs, scripts e configurações) que ajudem estudantes e profissionais a entender como essas tecnologias funcionam na prática.

---

## Módulos

### 1. Sniffing — Captura e Análise de Tráfego
Captura e análise de tráfego de rede usando ferramentas como `tcpdump` e `Wireshark`. Exemplos práticos de interceptação de pacotes em camadas 2 e 3.

**Documentação:** [`modulo1-sniffing/modulo1.pdf`](modulo1-sniffing/modulo1.pdf)

### 2. TLS — Conexões Seguras
Demonstração de handshakes TLS, configuração de certificados e testes de vulnerabilidades básicas. Implementação e verificação de conexões seguras via SSL/TLS.

**Documentação:** [`modulo2-tls/modulo2.pdf`](modulo2-tls/modulo2.pdf)

### 3. Sessões — Gerenciamento e Monitoramento
Estratégias de manutenção de sessões, controle de estado e monitoramento de atividade. Gerenciamento e monitoramento de sessões de comunicação em redes.

**Documentação:** [`modulo3-sessao/modulo3.pdf`](modulo3-sessao/modulo3.pdf)

---

## Estrutura de diretórios

```
.
├─ README.md
├─ Relatorio.pdf                 # Relatório completo do projeto
├─ evidencias/
│   ├─ Captura 1 - Modulo 1.png
│   ├─ Captura 1 - Modulo 2.png
│   ├─ Captura 1 - Modulo 3.png
│   ├─ Captura 2 - Modulo 1.png
│   └─ Captura 2 - Modulo 2.png
├─ modulo1-sniffing/
│   └─ modulo1.pdf
├─ modulo2-tls/
│   └─ modulo2.pdf
└─ modulo3-sessao/
    └─ modulo3.pdf
```

---

## Portal Web

O projeto inclui um portal interativo (`index.html`) para navegação entre os módulos, visualização dos PDFs e acesso às evidências visuais.

Para usar localmente:

```bash
python3 -m http.server 8080
```

Acesse `http://localhost:8080` no navegador.

---

## Relatório

O arquivo [`Relatorio.pdf`](Relatorio.pdf) consolida os três módulos com documentação completa, metodologias e resultados do projeto.

---

## Contribuições

- Cassiano Luiz Brandes Soares  
- Davi Ferreira da Cunha  
- Guilherme Emanuel Gonçalves  
- João Vitor Charleaux