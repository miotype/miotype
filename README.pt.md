<p align="center">
  <img src="assets/icon.png" width="96" height="96" alt="Ícone do MioType">
</p>

<h1 align="center">MioType</h1>

<p align="center">
  <b>Fale, não digite.</b> Ditado por voz e tradução instantânea para Mac.<br>
  Pressione <kbd>Fn</kbd>, fale, pressione <kbd>Fn</kbd> de novo e o texto aparece no cursor, em qualquer app.
</p>

<p align="center">
  <a href="https://miotype.com/download"><b>Baixar para macOS</b></a> ·
  <a href="https://miotype.com">Site</a> ·
  <a href="https://miotype.com/pricing">Preços</a>
</p>

<p align="center"><sub><a href="README.md">English</a> · <a href="README.zh-CN.md">简体中文</a> · <a href="README.de.md">Deutsch</a> · <a href="README.es.md">Español</a> · <a href="README.fr.md">Français</a> · <a href="README.it.md">Italiano</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.pt.md">Português</a> · <a href="README.ru.md">Русский</a></sub></p>

---

Seu cursor pode estar num terminal, no VS Code, no Cursor, no prompt do Claude Code ou do Codex, numa conversa do Slack ou numa mensagem de commit. Para o MioType tanto faz: ele digita onde estiver o foco.

## Atalhos

| Teclas | O que acontece |
|---|---|
| <kbd>Fn</kbd> | Pressione para começar a falar e de novo para digitar. <kbd>Esc</kbd> cancela |
| <kbd>Fn</kbd> + <kbd>Space</kbd> | Pergunte qualquer coisa. Selecione um texto antes para perguntar sobre ele, ou diga "deixe mais curto" para reescrevê-lo no lugar |
| <kbd>Fn</kbd> + <kbd>Left Shift</kbd> | Fale em chinês e receba inglês, e vice-versa |
| <kbd>Fn</kbd> + <kbd>Control</kbd> | Traduz a seleção. Uma única palavra em inglês abre um cartão de dicionário |
| <kbd>Fn</kbd> + <kbd>R</kbd> | Refina a seleção no lugar |
| <kbd>Fn</kbd> + <kbd>S</kbd> | Procura uma palavra ou expressão |

Todos os atalhos podem ser alterados em Configurações.

## Por que desenvolvedores gostam

- **Digita onde está o cursor.** Sem janela separada e sem copiar e colar. Dite um prompt longo para seu agente de código, a descrição de um PR ou a resposta a uma issue direto no lugar.
- **Chinês misturado com inglês continua misturado.** Diga "把这个 function 改成 async" e é exatamente isso que sai. Termos em inglês não são traduzidos para o chinês.
- **Aprende seu vocabulário.** Corrija uma palavra mal reconhecida logo após o ditado (`kubectl`, `useEffect`, o nome de um colega) e o MioType a adiciona ao dicionário para acertar da próxima vez. Também dá para importar um dicionário.
- **Offline a um botão de distância.** Escolha o modelo Whisper local em Configurações e sua voz nunca sai do Mac. Funciona sem rede e sem conta.
- **Use sua própria chave.** Reconhecimento e refinamento podem ir para o seu provedor de API em vez do MioType Cloud.

## Grátis e pago

| | |
|---|---|
| **Local** | Grátis para sempre. Ditado offline com Whisper, tradução e refinamento com sua própria chave de API. Histórico, dicionário e configurações ficam no seu Mac |
| **Nuvem grátis** | Entre na conta e ganhe 3.000 palavras na nuvem por semana |
| **MioType Cloud** | 100.000 palavras na nuvem por mês para reconhecimento na nuvem, refinamento e tradução com IA, sem chave de API. US$ 9,99/mês, US$ 59,99/ano ou US$ 149 em pagamento único |

Detalhes na [página de preços](https://miotype.com/pricing). Qualquer compra pode ser reembolsada em até 14 dias, sem perguntas.

## Privacidade

- O Whisper local roda inteiramente no seu Mac.
- No modo nuvem, o áudio ou texto de cada solicitação passa pelo nosso servidor até o Alibaba Cloud Model Studio, e o resultado volta direto para você. Nosso servidor não guarda áudio nem texto; registra apenas a contagem de palavras, o tipo e o horário da solicitação para calcular sua cota.
- Com sua própria chave, as solicitações vão direto do seu Mac para o provedor escolhido.
- Não treinamos modelos com o seu conteúdo e não usamos anúncios nem rastreadores.
- Política completa (em inglês): [miotype.com/privacy](https://miotype.com/privacy)

## Requisitos

- Um Mac com Apple silicon (M1 ou posterior)
- Permissões de Microfone e Acessibilidade. O MioType pede durante a configuração

## Feedback

Encontrou um bug ou quer um recurso? [Abra uma issue](https://github.com/miotype/miotype/issues/new/choose). Para assuntos privados, escreva para [hi@miotype.com](mailto:hi@miotype.com).

As notas de cada versão são publicadas em [Releases](https://github.com/miotype/miotype/releases). Clique em **Watch → Custom → Releases** para ser avisado.

---

O MioType não é de código aberto. Este repositório hospeda o rastreador público de issues e as notas de versão.
