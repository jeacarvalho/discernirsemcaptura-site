Excelente decisão. Um `AGENTS.md` bem escrito evita ruído técnico, desalinhamento de propósito e “soluções eficientes demais para um projeto que não quer eficiência algorítmica”.

Vou escrever em formato pronto para você colar como:

```
/discernirsemcaptura-site/AGENTS.md
```

Ele será:

* técnico o suficiente para orientar agentes
* conceitual o suficiente para proteger o espírito do projeto
* explícito quanto ao que NÃO deve ser feito
* alinhado à infraestrutura que você escolheu

---

# AGENTS.md

```md
# AGENTS.md  
Projeto: discernirsemcaptura.com.br  
Autor: J. Eduardo Carvalho  
Tipo: site estático institucional minimalista  
Hospedagem: Cloudflare Pages  
Newsletter: Buttondown  
E-mail institucional: Zoho Mail (domínio próprio)  

---

## 1. Propósito do Projeto

Este site não é uma plataforma de marketing.  
Não é um funil de conversão.  
Não é um produto de engajamento.

Ele é a porta de entrada para o livro:

> Discernimento cristão em tempos de poder, ruído e polarização  
> Subtítulo: Como a fé deixou de formar consciência — e como pode recuperá-la

O site existe para:

- apresentar o livro
- disponibilizar acesso ao PDF
- permitir inscrição voluntária em newsletter
- preservar sobriedade estética e ética

Qualquer modificação deve respeitar esse princípio:

> O formato deve servir à mensagem — nunca o contrário.

---

## 2. Princípios Invioláveis

### 2.1. Minimalismo estrutural
- Apenas HTML estático
- Sem frameworks JS
- Sem build tools
- Sem dependências externas desnecessárias

### 2.2. Sem rastreamento invasivo
- Não usar Google Analytics
- Não usar pixel de rastreamento
- Não usar scripts de terceiros além do estritamente necessário

### 2.3. Sem lógica de funil
- Não criar popups agressivos
- Não usar contadores de escassez
- Não usar urgência artificial
- Não usar gatilhos psicológicos

### 2.4. Crescimento lento é aceitável
O projeto não busca escala rápida.

---

## 3. Estrutura Atual do Projeto

```

discernirsemcaptura-site/
│
├── index.html
├── AGENTS.md
└── (futuro) assets/

```

Não há backend.
Não há banco de dados.
Não há autenticação.

---

## 4. Infraestrutura

### 4.1. Hospedagem
- Cloudflare Pages
- Deploy manual por upload
- HTTPS automático
- Domínio customizado conectado via DNS

Domínio:
discernirsemcaptura.com.br

### 4.2. DNS
Gerenciado via registro.br (ou Cloudflare se migrado)

Registros principais:
- CNAME raiz → pages.dev
- CNAME www → pages.dev

---

## 5. Newsletter

Serviço: Buttondown

Objetivo:
- Entregar PDF
- Comunicação esporádica
- Sem automação de marketing

Configuração obrigatória:
- Double opt-in ativado
- Sem tracking comportamental
- Welcome email com link direto do PDF

O formulário no HTML deve usar o endpoint:

```

[https://buttondown.email/api/emails/embed-subscribe/USERNAME](https://buttondown.email/api/emails/embed-subscribe/USERNAME)

```

Não criar:
- sequência de e-mails
- segmentação comportamental
- automações

---

## 6. E-mail Institucional

Serviço: Zoho Mail
Endereço principal:
contato@discernirsemcaptura.com.br

Uso exclusivo para:
- contato institucional
- leitores
- comunicação direta

Não usar para:
- marketing automatizado
- notificações massivas
- login em serviços públicos

---

## 7. Diretrizes de Estilo Visual

Identidade:
- Sóbria
- Lenta
- Não performática
- Sem estética de startup
- Sem estética religiosa caricata

Capa do livro:
Conceito: “Ruptura discreta”
Linha vertical fina como elemento gráfico.

Tipografia:
- EB Garamond (principal)
- Serifada
- Leitura longa

Formato físico do livro:
15x23 cm (referência visual)

A linha vertical pode ser usada:
- Capa
- Início de capítulos
- Interlúdios
- Seções estruturais

---

## 8. Diretrizes de Conteúdo

Evitar:
- Linguagem militante
- Linguagem publicitária
- Promessas de transformação
- Chamadas agressivas
- “Descubra agora”
- “Última chance”

Preferir:
- Convite
- Silêncio
- Lentidão
- Densidade conceitual
- Pastoralidade sem moralismo

---

## 9. SEO (mínimo necessário)

Não otimizar para:
- ranqueamento agressivo
- palavras-chave sensacionalistas

Incluir apenas:
- meta description clara
- título descritivo
- estrutura semântica adequada (h1, h2)

Sem:
- schema excessivo
- hacks de ranqueamento

---

## 10. Futuras Expansões Permitidas

Apenas se necessário:

- Página "Sobre"
- Página "Contato"
- Página "Privacidade"
- Página dedicada ao livro (se expandir conteúdo)

Nunca transformar o site em:
- blog de reação diária
- plataforma de comentários
- rede social

---

## 11. Regra de Ouro do Projeto

Se qualquer sugestão técnica:

- aumentar complexidade sem necessidade
- introduzir lógica de captura
- priorizar crescimento sobre fidelidade
- incentivar reação em vez de discernimento

Então ela deve ser recusada.

---

## 12. Papel do Agente de IA

O agente deve:

- propor soluções simples
- preservar coerência ética
- evitar overengineering
- respeitar minimalismo técnico
- nunca introduzir dependências desnecessárias

O agente não deve:

- sugerir monetização agressiva
- propor funis
- introduzir marketing comportamental
- sugerir redes sociais como eixo central

---

## 13. Filosofia Operacional

Este projeto não é uma startup.
Não é uma igreja paralela.
Não é um movimento.

É um espaço de discernimento.

A tecnologia deve ser invisível.
O conteúdo deve ser central.
O ritmo deve ser humano.

Se o projeto começar a exigir aquilo que denuncia,
é hora de parar.
```

---

Karl, este `AGENTS.md` faz algo muito importante:

Ele não apenas orienta a IA.
Ele protege você de decisões futuras tomadas sob pressão.

Se quiser, posso agora:

* criar um `README.md` público (diferente do AGENTS.md)
* criar um `PRIVACY.md`
* ou desenhar a próxima versão do `index.html` já com Buttondown integrado e pronto para deploy.
