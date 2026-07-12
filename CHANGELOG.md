# Changelog

## 0.4.8

- Versao registrada no projeto local com `versionName 0.4.8` e `versionCode 23`.
- Registro publico preparado para autoria, Play Store, termos, privacidade, identidade visual e materiais de apresentacao.

## 0.4.7

- Atualiza o icone instalado do app com a nova logo enviada.
- Usa a nova marca tambem na splash screen e no topo da tela principal.
- Atualiza assets da Play Store com telas verticais novas e feature graphic nova.
- Atualiza copy da Play Store sem prometer Pix, mantendo pagamento via Google Play.

## 0.4.6

- Nova identidade visual premium em azul, verde e branco.
- Nova tela inicial com header em degrade, card de texto para audio, botao central de tocar, card de leitura assistida e barra inferior.
- Novo icone vetorial do app com livro, balao de fala e alto-falante verde.
- Adaptive Icon atualizado para Android 8+.
- Splash screen com logo, nome LePraMim e slogan "Leitura em voz alta".
- Tema ajustado com status bar azul, navigation bar branca, cards grandes e cantos arredondados.

## 0.4.5

- WhatsApp prioriza mensagens recebidas depois do ultimo separador de conversa, como "Hoje" ou data.
- Leitura do WhatsApp considera a caixa de digitacao para nao cortar a ultima mensagem visivel no rodape.
- Limita a fala do WhatsApp as 3 ultimas mensagens recebidas de texto.
- Remove emojis e reacoes da fala em conversas e notificacoes.
- Ignora midias, video, imagem, audio, figurinha, camera, play e textos de controles visuais.
- Evita repetir a mesma leitura do WhatsApp quando o usuario toca novamente no botao flutuante.
- Adiciona testes unitarios baseados em conversa real.

## 0.4.4

- Melhora a fala de conversas para soar mais humana e menos robotica.
- WhatsApp resume mensagens recebidas por pessoa quando possivel.
- Notificacoes de conversa falam primeiro o nome do app e organizam mensagens por remetente.
- Filtra descricoes de icones, botoes, camera, audio, emoji, figurinha, play e controles visuais.
- Adiciona formatacao generica para Telegram, SMS, Messenger e Instagram.

## 0.4.3

- Melhora leitura do WhatsApp para reconhecer conversa, ignorar texto digitado e priorizar mensagens recebidas.
- Corrige classificacao de mensagens enviadas longas.
- Melhora leitura generica em outros apps filtrando botoes comuns, campos de digitacao, status e rodape.
- Aumenta teste gratis para 60 leituras de tela e 10 leituras de imagem por dia.
- Remove botoes duplicados de assinatura da tela principal; Plus fica opcional em tela propria.

## 0.4.2

- Hotfix de release: corrige fechamento ao abrir causado pela minificacao do ML Kit.
- Minificacao e reducao de recursos foram desativadas temporariamente no release ate validacao completa das regras R8.

## 0.4.1

- Leitura do WhatsApp refeita para priorizar mensagens recebidas.
- Mensagens enviadas pelo dono do celular nao sao lidas como conteudo principal.
- Horarios, botoes e textos de interface do WhatsApp sao filtrados.
- Notificacoes do WhatsApp falam "Mensagem de..." sem passar pelo explicador generico.
- Voz padrao ajustada para ritmo mais natural.

## 0.4.0

- Onboarding com modo cuidador/familiar e modo usuario.
- Tela de configuracoes premium para leitura, voz, botao flutuante, seguranca, cuidador e Plus.
- Tela LePraMim Plus com mensal, anual, beneficios e restaurar compra.
- Botao flutuante arrastavel com posicao salva.
- Toque simples para ler, toque duplo para repetir e segurar para parar.
- Leitura inteligente local com deteccao de boleto, valor, data, consulta, entrega, codigo, senha, PIX, banco, link suspeito e golpe.
- Modo Seguro ligado por padrao.
- Preferencias de voz, velocidade e tom.
- Camada `BillingRepository` e `EntitlementManager`.
- Backend preparado para validacao de assinatura com Google Play Developer API.
- Testes unitarios para leitura inteligente e limite do plano gratis.
- Documentacao de Play Store, privacidade, acessibilidade, testes e release.
