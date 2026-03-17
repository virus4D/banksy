# banksy 🎨

> arte crítica gerada por agentes on-chain.

Inspirado em Banksy — anônimo, sem permissão, diz algo real.

Cola uma notícia. O agente lê, interpreta e gera uma obra de arte de rua com crítica social. Se adicionar sua wallet, a figura muda baseada no seu comportamento on-chain.

---

## o que faz

```
① você cola uma notícia ou frase
② agente IA interpreta a crítica social por trás dela
③ gera uma obra estilo stencil de rua — preto, branco, vermelho
④ (opcional) sua wallet define a figura central da obra
```

---

## demo

🔗 **[virus4d.github.io/banksy](https://virus4d.github.io/banksy)**

---

## como usar

1. Cola qualquer notícia, titular ou frase que te impacta
2. (opcional) adiciona o endereço da sua wallet
3. Clica **GERAR OBRA**
4. Baixa a imagem

exemplos de frases para testar:
```
"banco central aumenta juros pela quinta vez consecutiva"
"bilionários aumentaram fortuna em 40% durante a crise"
"bitcoin é mais seguro que o sistema bancário tradicional"
"inteligência artificial vai substituir 40% dos empregos"
```

---

## como a wallet define a arte

a mesma wallet sempre gera a mesma figura — é sua identidade on-chain:

```
🐋 WHALE     → saldo > 10 ETH — homem de terno com baleia
📈 TRADER    → muitas interações com contratos — figura com máscara de gás
🔒 HOLDER    → poucos txs, saldo positivo — figura abraçando cofre
🤖 BOT       → txs em alta frequência — robô com código binário
🎨 ANONYMOUS → sem wallet ou perfil indefinido — figura com capuz e spray
```

mas cada geração é única — detalhes, ratos, ruído e elementos mudam a cada obra.

---

## stack

```
Groq LLM         → llama-3.3-70b interpreta a notícia e gera a mensagem
Base RPC         → lê saldo da wallet sem CORS
Etherscan API V2 → histórico de txs para definir o perfil
Canvas API       → gera a obra visual no browser
Vanilla JS       → sem frameworks, sem dependências
```

---

## a filosofia

Banksy nunca pediu permissão.

A blockchain também não pede.

Dados on-chain são públicos — qualquer um pode lê-los.
Notícias são públicas — qualquer um pode interpretá-las.

Este agente faz as duas coisas ao mesmo tempo
e transforma isso em arte.

---

## projetos relacionados

| tool | descrição | link |
|------|-----------|------|
| 🎨 banksy | arte crítica gerada por agentes | você está aqui |
| 🔍 tx-decoder | decodifica transações on-chain | [ver repo](https://github.com/virus4D/virus4D-tx-decoder) |
| 🛡 sentinel-agent | monitora wallets em tempo real | [ver repo](https://github.com/virus4D/sentinel-agent) |
| 🔍 token-scanner | analisa tokens ERC-20 | [ver repo](https://github.com/virus4D/token-scanner) |
| 🤖 defi-agent-v0 | agente IA para wallets na Base | [ver repo](https://github.com/virus4D/defi-agent-v0) |
| 📊 wallet-lens | scan de transações ETH | [ver repo](https://github.com/virus4D/wallet-lens) |

---

<div align="center">

```
construindo em público · errando em público · chegando lá
```

[![X](https://img.shields.io/badge/@Virus__4D-000000?style=flat-square&logo=x&logoColor=cc0000)](https://x.com/Virus_4D)
[![GitHub](https://img.shields.io/badge/virus4D-000000?style=flat-square&logo=github&logoColor=cc0000)](https://github.com/virus4D)

</div>
