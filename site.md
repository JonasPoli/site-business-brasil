Fico feliz que o conceito visual tenha agradado. Para que outra I.A. (ou equipe de front-end) consiga reproduzir essa interface com exatidão, preparei um descritivo técnico exaustivo.

Este prompt está estruturado de forma lógica (top-down), detalhando a hierarquia visual, tipografia, paleta de cores e efeitos. Você pode copiar o bloco abaixo e colar diretamente na outra ferramenta.

---

### Descritivo Técnico do Layout "Business Brasil"

**Visão Geral e Direção de Arte**
O layout é uma landing page premium de alta conversão, apresentada em um monitor desktop. A estética é sofisticada, corporativa e tecnológica ("sem oba-oba"). A paleta de cores primária é baseada em Dark Charcoal (quase preto), Branco Puro, tons de Cinza Claro para fundos secundários e um Dourado Metálico vibrante (similar a `#F2A900`) como cor de destaque e conversão (CTAs). A tipografia principal é uma fonte sem serifa moderna, geométrica e altamente legível (como Montserrat, Inter ou Roboto), utilizando variações de peso (Bold para títulos, Regular/Light para textos de apoio).

**1. Header (Barra de Navegação Global)**

* **Fundo:** Dark Charcoal sólido, ocupando 100% da largura.
* **Alinhamento:** Flexbox horizontal, itens centralizados verticalmente, distribuídos com espaço entre si (`justify-between`).
* **Esquerda (Logo):** O logotipo da "Business Brasil" (o 'B' estilizado em cinza e dourado com o texto empilhado ao lado) alinhado à esquerda.
* **Centro (Menu):** Links de navegação em caixa alta (uppercase), fonte leve, cor cinza claro/branco com espaçamento generoso entre as letras (tracking). Textos: "O MÉTODO", "CONTEÚDO PREMIUM", "A CONSULTORIA", "CURSOS RESTRITOS", "BLOG".
* **Direita (CTA):** Um botão retangular com fundo dourado e texto em preto: "ÁREA DO ALUNO". Cantos levemente arredondados (border-radius pequeno).

**2. Hero Section (Dobra Principal)**

* **Background:** Cor Dark Charcoal, coberto por um padrão geométrico sutil (efeito *Deep Space Network*). Este padrão consiste em linhas finas e pontos de conexão (nós) formando uma rede tecnológica assimétrica, com leve transparência (opacity baixa) para não brigar com o texto.
* **Conteúdo Centralizado:** Todo o texto e botões estão alinhados rigorosamente ao centro.
* **Headline:** Fonte robusta (Bold/Black), caixa alta, cor branca, tamanho grande (aprox. 48px+). Texto: "CONHECIMENTO SEM APLICAÇÃO É APENAS ENTRETENIMENTO." A palavra "ENTRETENIMENTO" tem forte destaque.
* **Sub-headline:** Abaixo da headline, fonte regular, cor cinza claro, tamanho médio. Texto: "Uma plataforma nichada e restrita para empresários que buscam clareza, decisões aceleradas e crescimento operacional sustentável."
* **Botão Principal (CTA):** Centralizado abaixo do texto. Retangular, fundo dourado, texto em preto, caixa alta, peso bold. Texto: "SOLICITAR ACESSO RESTRITO".
* **Micro-cópia:** Abaixo do botão, em fonte menor e cor cinza: "Para concorrentes nichados, sem oba-oba."

**3. Seção "O Método" (Faixa de Transição)**

* **Background:** Transição abrupta do fundo escuro para um fundo Branco/Cinza super claro (Off-white).
* **Título da Seção:** Alinhado à esquerda, em preto, peso bold, caixa alta: "O MÉTODO".
* **Cards de Metodologia:** Um grid horizontal com três caixas (cards) retangulares de fundo branco, bordas sutis e sombra projetada leve (drop shadow) para criar profundidade.
* Cada card contém um ícone dourado estilizado (engrenagens, gráfico de crescimento em seta, nós de conexão/mente) alinhado à esquerda.
* Ao lado do ícone, o texto: Título em bold (ex: "FOCO NA PRÁTICA:") seguido de texto regular descrevendo o tópico.



**4. Seção Dupla: Cursos Restritos e Ferramentas (Grid 50/50)**

* **Background:** Continua no tom Branco/Off-white.
* **Coluna Esquerda ("CURSOS RESTRITOS"):**
* Cabeçalho da coluna com título em bold à esquerda e um link "Ver Todos" menor à direita.
* Apresenta um carrossel visual com dois cards de curso visíveis.
* **Design dos Cards de Curso:** Imagem de capa (profissionais/executivos de terno em fundo escuro). Título sobreposto à imagem em caixa alta, branco e negrito (ex: "TURNAROUND EMPRESARIAL").
* *Detalhe Específico (Card 2):* Uma pequena tag visual (badge) em formato de pílula sobreposta à imagem, com a inscrição "CPF FLUTUANTE ATIVO", indicando segurança.
* Abaixo da imagem de cada card: Título do curso (Bold), meta-dados ("3 Módulos, 30min/aula" em fonte leve), preço em destaque ("R$ 100") alinhado à esquerda, e um pequeno botão dourado "Ver Detalhes" alinhado à direita.
* Indicadores de carrossel (três pontinhos) centralizados abaixo dos cards.


* **Coluna Direita ("FERRAMENTAS E SEGURANÇA"):**
* Cabeçalho similar: Título em bold à esquerda, "Ver Todos" à direita.
* Dois cards retangulares orientados verticalmente. Fundo Dark Charcoal, texto branco.
* **Card 1 (Podcast):** Ícone grande de microfone dourado no topo. Título em bold, caixa alta ("EXTRAÇÃO DE PODCAST COM I.A.:"). Texto descritivo menor abaixo ("Legendas e áudios extraídos automaticamente.").
* **Card 2 (Segurança):** Ícone grande de cadeado/usuário dourado no topo. Título em bold, caixa alta ("SEGURANÇA AVANÇADA:"). Texto descritivo menor ("CPF flutuante do usuário no vídeo para evitar compartilhamento.").



**5. Seção Inferior (Consultoria e Conteúdo)**

* **Background Geral:** Uma barra mais escura, num tom de cinza médio-escuro (`#333` ou similar) para separar visualmente o conteúdo de cima do rodapé da página.
* **Bloco Esquerdo ("A CONSULTORIA"):** Uma grande caixa retangular com uma imagem de fundo escurecida (uma silhueta de cidade/arranha-céus desfocada). Título em branco e negrito ("A CONSULTORIA"). Um bloco de texto descritivo menor em branco. Centralizado na parte inferior desta caixa, um botão dourado em caixa alta: "APLICAR PARA CONSULTORIA".
* **Bloco Direito ("CONTEÚDO PREMIUM"):**
* Cabeçalho acima do bloco alinhado com o da esquerda.
* Três cards menores em formato quadrado/retangular com imagens fotográficas de fundo escurecidas por um overlay (filtro escuro).
* **Card 1:** Logo do "Panda Video" em branco com a legenda "VÍDEOS CONCEITUAIS" na base.
* **Card 2:** Imagem de cadernos/livros escuros, legenda "E-BOOKS" na base.
* **Card 3:** Imagem de alguém segurando um café/lendo, legenda "INSIGHTS" na base.



---

Se precisar que eu ajuste a descrição focando em alguma tecnologia específica (como prompts direcionados ao Midjourney, v0.dev ou similares), basta avisar.