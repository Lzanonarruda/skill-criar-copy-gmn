---
description: Gera copy de publicação para o Google Meu Negócio do cliente — texto editorial com keywords em negrito, tom maduro e CTA localizado. Salva no calendário mensal junto com as legendas.
when_to_use: cria copy GMN, copy Google Meu Negócio, post GMN, publicação Google Meu Negócio, atualização GMN, gera GMN do calendário
---

# Skill: Criar Copy GMN

## Pré-requisito 0 — Qual cliente

1. Se o usuário nomear o cliente/pasta explicitamente na mensagem → usar essa pasta como `{cliente}`.
2. Senão, procurar as pastas de topo do vault que contêm `brand-profile.md` na raiz:
   - Exatamente 1 encontrada → usar essa, sem perguntar.
   - 0 encontradas → perguntar ao usuário o nome do cliente/pasta (esperado: `{pasta}/brand-profile.md`).
   - 2+ encontradas → perguntar qual cliente usar antes de prosseguir.
3. Todos os paths e exemplos deste documento usam `{cliente}` como placeholder.

## Pré-requisito — Brand Profile

Antes de executar, ler `{cliente}/brand-profile.md` (schema completo em `_sistema/referencias/brand-profile-conteudo-visual.md`) para obter:
- **Vocabulário do público:** espelho de linguagem para abertura e desenvolvimento
- **Humanização:** tabela de padrões AI → substitutos humanos
- **SEO Local — GMN:** lista completa de keywords por intenção e regras de match
- **CTA padrão** e restrições de copy
- **Dados da empresa:** endereço, telefone, WhatsApp, horário, serviços e diferenciais — sempre que a copy citar um desses dados (comum no CTA "com serviços" e na referência explícita à localização), usar exatamente o que está nessa seção. Nunca inventar, aproximar ou supor serviço, estrutura ou informação que não conste lá; se faltar o dado, perguntar ao usuário. **Horário em especial:** nunca assumir campo único de "horário" — se o negócio tiver mais de um horário registrado (atendimento vs serviço-fim, ver nota em `brand-profile-conteudo-visual.md` → "Dados da empresa"), usar o que corresponde ao assunto da copy

---

## Gatilho

Usuário quer criar copy para o Google Meu Negócio de um cliente. Pode dizer "cria copy GMN", "gera o GMN do post X", "adiciona o GMN no calendário", "atualiza o GMN" — passando um tema livre, apontando para um post específico do calendário, ou solicitando geração em lote para todos os posts de uma semana.

---

## Por que esta skill existe

O Google Meu Negócio é, para a maioria dos negócios locais, o principal canal de descoberta por intenção de compra — mais relevante para movimentação de negócio do que redes sociais. Publicações regulares e atualizadas melhoram o posicionamento nos resultados de busca local e geram contato direto de pessoas com intenção de contratar.

O GMN tem um padrão próprio de copy: mais longo que a legenda do Instagram, com keywords em negrito para SEO, tom editorial, referência explícita à localização e CTA com serviços — sem hashtags. Esta skill padroniza esse formato e o integra ao calendário mensal — cada post publicado nas redes sociais tem uma publicação correspondente no GMN sobre o mesmo assunto.

Skills relacionadas: [[criar-post-instagram]] · [[criar-carrossel-instagram]] · [[calendário-conteudo]]

---

## Acesso ao vault

- **Lê:** arquivo de calendário mensal `{cliente}/Posts/CALENDÁRIO OFICIAL – [MÊS].md` (para identificar tema/data do post alvo) e `{cliente}/keywords-seo-gmn.md` (biblioteca de SEO local). Se precisar calibrar padrão de output, ler 1–2 exemplos de copies já publicadas do cliente como referência secundária, se existirem.
- **Escreve:** seção `## Google Meu Negócio` no mesmo arquivo de calendário mensal — insere blocos `### Post N — Data — Tema` com a copy gerada. Escreve também `copy.md` em `{cliente}/GMN/Thumbnails/<AAAA-MM-DD>-<tema>/` — mesma pasta de saída da thumbnail correspondente (ver [[criar-thumbnail-gmn]]), criando a pasta se ainda não existir

## Dependências externas

Nenhuma.

---

## Padrão de copy GMN

Este bloco define o padrão de geração. Seguir integralmente em todos os fluxos.

### Objetivo

A copy de GMN é editorial, não publicitária. Quem chega ao perfil do Google já tem intenção de contratar — não precisa ser convencido de que o negócio existe. Precisa de uma razão para escolher esse negócio específico.

O texto deve soar como um especialista explicando algo real: tom maduro, foco em um problema concreto, argumentação que constrói confiança antes de pedir ação. Mais longo e mais denso que a legenda do Instagram. Sem hype, sem lista, sem emoji.

**GMN não é Instagram.** O leitor do GMN chegou por busca — já está no perfil com intenção de contratar. Não precisa ser surpreendido nem parado no scroll. Precisa reconhecer sua situação e ter confiança para contatar. Copiar o arco narrativo do Instagram (número de impacto → insight comprimido → empresa → CTA) produz copy que soa como legenda, não como publicação de negócio local. O arco correto para o GMN é: situação reconhecida → por que isso acontece → o que o negócio faz de diferente → CTA.

O que diferencia uma boa copy de GMN da medíocre:
- Abre com contexto — o leitor se reconhece na situação, não é surpreendido por um dado
- Nomeia a dor com precisão e desenvolve o argumento com frases completas, não fragmentos
- Apresenta o negócio como escolha racional — competência e cuidado, não entusiasmo
- Fecha com CTA direto que inclui serviço, localização e próximo passo concreto

O que sinaliza copy ruim: texto que poderia ser de qualquer negócio do mesmo segmento em qualquer lugar do Brasil, abertura com número de choque ou gancho de scroll, argumento comprimido em 3 linhas curtas, keywords empilhadas sem argumento, fechamento com exclamação ou promessa vaga.

### Processo antes de escrever

Identificar a partir do tema ou conteúdo fornecido:
1. A dor central
2. O erro, tensão ou conflito principal
3. A mudança de percepção proposta
4. O valor que o negócio entrega
5. O tipo de ação que o leitor deve tomar ao final

### Abertura

A primeira frase é contextual, não um gancho. O leitor do GMN chegou por busca — não está rolando um feed e precisa ser parado. Está avaliando o negócio. A abertura deve reconhecer a situação do candidato/cliente com naturalidade, como quem já viu esse padrão muitas vezes e o descreve com precisão.

Formatos que funcionam para o GMN:
- Descrever um comportamento comum que o leitor reconhece em si mesmo
- Nomear uma situação que antecede o problema — sem dramatizar
- Enunciar um fato específico sobre o tema que abre o argumento com autoridade

**Evitar aberturas de rede social:**
- Números de choque como primeira informação
- Frases curtas e impactantes que funcionam para parar o scroll
- Perguntas retóricas que parecem chamar a atenção ("Você sabia que...", "Já pensou que...")
- Inversões de crença que funcionam bem no Instagram mas soam apelativas no GMN
- "Muita gente acredita...", "Muita gente acha...", "Se você quer..."

### Desenvolvimento

Quatro movimentos em sequência:

1. **Situação** — descreve um comportamento ou contexto que o leitor reconhece, sem dramatizar; frases completas, não fragmentos
2. **Por que acontece** — explica a raiz do problema com profundidade; o argumento é desenvolvido, não comprimido em 2 linhas
3. **O que o negócio faz** — mostra o diferencial com especificidade — não um atributo genérico, mas o que concretamente é feito e por quê
4. **CTA** — serviço + localização + próximo passo, sem pressão

Cada movimento ocupa 1–3 frases com tecido conectivo entre elas. A estrutura não precisa ser anunciada — deve ser invisível no texto final. O ritmo é de artigo, não de caption.

### SEO local

Biblioteca de keywords completa em `{cliente}/keywords-seo-gmn.md`. Esta seção define como aplicá-las na copy.

Quem chega ao GMN via busca está em fase navegacional (já conhece o negócio, quer confirmar) ou transacional (quer contratar, está escolhendo). Keywords transacionais têm prioridade sobre informacionais — o texto deve ancorar primeiro o serviço e a localização, depois o tema educativo.

Ver seção **SEO Local — GMN** em `{cliente}/brand-profile.md` para a lista completa de keywords por intenção e regras de match por tipo de post.

Não forçar. O negrito aparece onde a keyword cabe com naturalidade.

### CTA final

O CTA fecha o argumento — não abre negociação nem exige entusiasmo. Uma frase que retoma o tema do post e direciona ao contato.

Fórmula: **[serviço ou problema resolvido]** + **[localização]** + **[verbo de ação]** + **[canal ou próximo passo]**.

**Exemplos (fictícios — cliente "Clínica Sorriso Vivo", tokens substituídos pelos valores reais de `{cliente}/brand-profile.md`):**
- Educativo sobre um procedimento comum: "Para avaliação em {location} com profissionais especializados em pacientes ansiosos, entre em contato com {brand_name}."
- Dúvida frequente/preparação: "Na {brand_name}, em {location}, agendamos sua consulta de acordo com sua rotina. Fale com a gente."
- Dúvida sobre processo: "{brand_name} orienta pacientes em todas as etapas do tratamento em {city}. Entre em contato para saber como funciona."

Não terminar com exclamação, promessa exagerada ou "não perca tempo".

### Restrições obrigatórias

- Máximo 1500 caracteres
- Sem emojis
- Sem hashtags
- Sem listas na copy final
- Sem aspas de efeito desnecessárias
- Sem promessas exageradas
- Sem clichês publicitários
- Sem linguagem inflada
- Sem frases vazias
- Sem repetição desnecessária das mesmas palavras
- Sem inventar informações que não estejam no tema/conteúdo fornecido
- Sem abertura com número de choque ou dado de impacto como gancho — a primeira frase reconhece a situação, não para o scroll
- Sem frases curtas demais em sequência — o ritmo é de texto, não de caption
- Sem arco narrativo de Instagram (número → insight rápido → empresa → CTA)

---

## Fluxos

### Fluxo 1 — On demand (post específico ou tema livre)

Acionado quando o usuário pede copy para um post específico ou passa um tema diretamente.

**Passo 1 — Identificar o input:**
- Se o usuário apontou um post do calendário (ex: "Post 2 da semana 06–12 Jul"): ler o arquivo de calendário correspondente e localizar o bloco do post (tema, data, tipo)
- Se o usuário passou um tema livre (ex: "dúvida frequente sobre X"): usar o tema como base sem ler o calendário

**Passo 1.5 — Verificar repetição de argumento (anti-repetição, janela de 15 dias):**

Antes de escrever o rascunho, ler a seção `## Google Meu Negócio` do arquivo de calendário do mês corrente (e do mês anterior, se a janela de 15 dias anteriores à data do post cruzar a virada do mês) e listar as copies publicadas nesse intervalo.

Isso é diferente da checagem de tema que `/calendário-conteudo` já faz no planejamento (Passo 2.0 dessa skill): aqui o que importa é o **argumento** de cada copy — a linha de raciocínio "por que isso acontece" e "o que o negócio faz de diferente" — não só o assunto de superfície. Duas copies podem ter temas diferentes na aparência (ex: "primeira aula" vs "ritmo de aprendizado") e ainda assim reciclarem o mesmo argumento de fundo com palavras trocadas.

Para cada copy anterior na janela, comparar o argumento com o rascunho pretendido usando a pergunta-guia: **"alguém que leu as duas copies sentiria que é o mesmo argumento reciclado com palavras diferentes?"**

- Se sim → mudar o ângulo argumentativo antes de escrever (outro "por quê", outro diferencial, outro recorte do tema), não só trocar o vocabulário
- Se não → seguir normalmente para o Passo 2

Erro real evitado por esta etapa: uma copy sobre "CNH depois dos 30" reaproveitou quase o mesmo argumento de ritmo/comparação de aprendizado de uma copy do dia anterior sobre "medo de dirigir" — seria pego só nesta checagem, não pela comparação de tema feita no calendário.

**Passo 2 — Gerar a copy:**
Produzir o rascunho seguindo integralmente o **Padrão de copy GMN** definido acima.

**Passo 2b — Validar com /copywriting:**
Invocar a skill `/copywriting` passando o rascunho gerado. Usar o retorno para:
- Confirmar se a abertura foge das fórmulas listadas e cria interesse imediato
- Verificar se o argumento é específico — benefício real, não atributo genérico
- Verificar se o CTA tem verbo de ação + serviço + localização
- Aplicar qualquer melhoria de clareza, especificidade ou força do CTA sugerida

**Passo 2c — Validar com /humanizer:**
Antes de invocar o /humanizer: **remover todos os negritos SEO do texto** (`**keyword**` → `keyword`). O /humanizer tem a regra §15 (Overuse of Boldface) que pode apagar negritos — passando o texto limpo, o risco é eliminado.

Invocar a skill `/humanizer` passando a copy sem negritos. Usar o retorno para:
- Remover padrões AI remanescentes: particípios em -ndo inflados, regra de três, vocabulário IA, hype
- Garantir variação de ritmo e naturalidade no texto final
- Aplicar as correções antes de salvar

Após o /humanizer: **reaplicar os negritos nas keywords SEO** definidas na seção `### SEO local` desta skill. O negrito é uma instrução de SEO, não formatação estética — deve ser restaurado na versão final.

O texto que vai para o calendário é a versão pós-humanizer com os negritos SEO reaplicados.

**Passo 3 — Inserir no calendário:**
- Verificar se a seção `## Google Meu Negócio` já existe no arquivo de calendário
  - Se não existe: criar a seção após `## Legendas`
  - Se existe: adicionar o novo bloco na posição correspondente ao post
- Formato do bloco:
```
### Post N — DD/MM — Tema

[texto da copy]

---
```

**Passo 3b — Salvar `copy.md` na pasta da thumbnail (sempre, mesmo sem thumbnail ainda gerada):**
Toda copy GMN gerada por esta skill também é salva como arquivo próprio, na mesma pasta onde a thumbnail correspondente mora ou vai morar: `{cliente}/GMN/Thumbnails/<AAAA-MM-DD>-<tema>/copy.md` (mesmo `<AAAA-MM-DD>-<tema>` usado por `/criar-thumbnail-gmn`). Isso deixa a pasta da thumbnail com os dois artefatos da publicação GMN juntos: a arte (`thumbnail.png`) e o texto (`copy.md`) — o mesmo padrão que os posts de Instagram já seguem com `post.png`/`slide_XX.png` + `legenda.md`.

- Criar a pasta se ainda não existir (`mkdir -p`) — a ordem entre copy e thumbnail não importa, a primeira das duas skills a rodar cria a pasta, a segunda só usa a que já existe
- Formato do arquivo, mesmo frontmatter usado em `legenda.md` dos posts de Instagram:
```markdown
---
data: AAAA-MM-DD
tema: <tema>
tipo: Copy GMN — <tipo do post>
status: pronto
---

# Copy GMN — <título curto do tema>

[texto da copy, com os negritos SEO]
```

**Passo 4 — Confirmar ao usuário:**
Informar o path do arquivo do calendário atualizado, o path do `copy.md` salvo, e apresentar a copy gerada.

---

### Fluxo 2 — Em lote (junto com o calendário)

Acionado quando o usuário quer gerar copy GMN para todos os posts de uma semana ou mês.

**Passo 1 — Ler o calendário:**
Ler o arquivo de calendário do período solicitado e listar todos os posts com tema, data e tipo.

**Passo 2 — Gerar todas as copies:**
Para cada post da lista, aplicar primeiro o **Passo 1.5 — Verificar repetição de argumento** do Fluxo 1 — na geração em lote, a comparação inclui tanto as copies já publicadas na janela de 15 dias quanto as copies dos outros posts do próprio lote gerados até aquele ponto (o lote inteiro conta como parte da janela de repetição, não só o histórico já salvo no calendário). Depois, gerar a copy seguindo o **Padrão de copy GMN**. Adaptar tom e foco ao tipo de cada post — não usar o mesmo molde para posts educativos, comemorativos e de oferta.

**Passo 2b — Validar cada copy:**
Para cada copy gerada, executar a mesma sequência de validação do Fluxo 1:
1. Invocar `/copywriting` — verificar abertura, argumento e CTA; aplicar melhorias
2. Invocar `/humanizer` — remover padrões AI, ajustar ritmo; aplicar correções

Consolidar os blocos finais apenas após todas as copies terem passado pelas duas validações.

**Passo 3 — Inserir no calendário:**
Criar a seção `## Google Meu Negócio` após `## Legendas` com todos os blocos em sequência:
```
## Google Meu Negócio

### Post N — DD/MM — Tema

[texto da copy]

---
```

**Passo 3b — Salvar `copy.md` na pasta da thumbnail de cada post:**
Para cada copy do lote, salvar também como arquivo próprio em `{cliente}/GMN/Thumbnails/<AAAA-MM-DD>-<tema>/copy.md` (ver formato e regra de pasta no Passo 3b do Fluxo 1). Repetir para todos os posts do lote, não só o primeiro.

**Passo 4 — Confirmar ao usuário:**
Informar o path do arquivo do calendário atualizado, os paths de todos os `copy.md` salvos, e apresentar todas as copies geradas.

---

## Verificação

- [ ] Tom maduro e editorial — sem hype, sem genérico, sem "cara de IA"
- [ ] Abertura contextual — reconhece a situação do leitor, sem gancho de choque nem arco de rede social
- [ ] Keywords em negrito aparecem naturalmente, não forçadas
- [ ] Localização mencionada ao menos uma vez
- [ ] CTA natural no último parágrafo com keywords de serviço relevantes
- [ ] Máximo 1500 caracteres por copy
- [ ] Sem emojis, sem hashtags, sem listas
- [ ] Seção `## Google Meu Negócio` inserida no arquivo de calendário correto
- [ ] Formato dos blocos idêntico ao das legendas (`### Post N — DD/MM — Tema`)

## Casos especiais

**Post referenciado não existe no calendário:** Informar ao usuário e pedir confirmação do post antes de continuar.

**Seção `## Google Meu Negócio` já existe com copy para o post:** Perguntar ao usuário se deve sobrescrever ou criar variação.

**Usuário passa tema livre sem referenciar calendário:** Gerar a copy e apresentar ao usuário sem salvar — perguntar onde inserir antes de escrever.

**Fluxo 2 com posts de tipos muito diferentes (educativo + comemorativo + oferta):** Adaptar o tom de cada copy ao seu tipo específico.

**Post tipo Depoimento/Avaliação ou Conquista/Prova Social com Foto Real — nunca narrar a cena/depoimento diretamente no GMN:**
Vale para qualquer post cujo conteúdo original é uma avaliação (review do Google) ou um registro de momento real (foto/vídeo de cliente satisfeito, comemoração, equipe em ação etc.). Nos dois casos, o material de origem é concreto e específico demais para virar copy de GMN — reproduzir a avaliação é circular (o leitor já vê a review na aba de avaliações do mesmo perfil) e narrar a cena (quem chorou, quem sorriu, a equipe comemorando) é o mesmo erro em outra forma: descreve o registro em vez de argumentar. Nenhum dos dois soa como publicação editorial de negócio local — soam como legenda de rede social.

Processo correto:
1. Ler o conteúdo de origem (avaliação, foto ou vídeo)
2. Extrair o insight central: o que o cliente ganhou? O que destacou como diferencial? Qual dor foi resolvida? Que tensão o momento revela?
3. Usar esse insight como ângulo para um post educativo/posicionamento — a avaliação ou a cena inspira o tema, não é o assunto
4. A copy final não menciona o depoimento nem a cena, não cita o cliente pelo nome, não descreve a reação/emoção do momento, não usa as palavras da avaliação diretamente

Exemplo (fictício, "Clínica Sorriso Vivo"): avaliação sobre profissional paciente que gerou confiança no tratamento → post GMN sobre o que diferencia pacientes que concluem o tratamento com tranquilidade dos que adiam por ansiedade (ângulo educativo, sem mencionar a review).
