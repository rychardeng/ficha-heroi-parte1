# Ficha de Herói: Jaguaretê, a Onça Verdadeira

Projeto Prático (Parte 1) da disciplina de Tecnologia Web: uma página em HTML e CSS que funciona como a tela de status de um RPG, apresentando um personagem original.

## O personagem

### Origem
**Marcos Hedmar** nasceu em uma família muito simples, mas boa de coração. Desde menino entendeu que o estudo seria o seu caminho, e foi com dedicação e disciplina que conquistou uma **bolsa de estudos** em uma escola que oferecia aulas de **karatê**, a sua grande paixão. Ali aprendeu muito mais do que golpes, Marcos aprendeu respeito, paciência, autocontrole e a nunca desistir. Treinando todos os dias, se destacou entre os alunos e levou esses valores para a vida inteira.

Depois de muito esforço, realizou outro sonho, de entrar para o **Exército Brasileiro**. Como soldado, ficou conhecido pela técnica de luta e, principalmente, pelo caráter. Marcos sempre acreditou que um soldado existe para proteger as pessoas. Sempre que via alguém em perigo, ia ajudar, mesmo arriscando a própria vida, e buscava salvar o máximo de pessoas possível, sem olhar a quem. Essa coragem rendeu muitas broncas de sargentos e coronéis, que diziam que um dia ela lhe custaria caro. Ele ouvia, respeitava, mas não mudava, pois para ele, fazer o que é certo sempre vem em primeiro lugar.

### A missão
O Exército recebe uma denúncia grave: **cientistas e soldados estadunidenses** esconderam um laboratório no meio da Floresta Amazônica. Em busca de poder militar, eles faziam experimentos com **onças-pintadas**, o maior felino das Américas, para criar **supersoldados-animais** e tornar o seu país o mais forte do mundo. A primeira patrulha brasileira enviada para investigar nunca voltou. Marcos é escolhido para a segunda.

O ataque ao laboratório vira uma batalha. Infiltrado para desligar as torres de tiro automáticas, Marcos encontra dezenas de onças presas em cápsulas de líquido verde, ligadas a cabos, cercadas de amostras de garras, dentes e sangue. Helicópteros estrangeiros resgatam os cientistas e bombardeiam o próprio laboratório para apagar as provas. No desabamento, Marcos cai em um **tanque de mutação** e sai de lá transformado em um **homem-onça**. Marcos ganhou a agilidade, a velocidade, o nado e os instintos da onça, mas manteve a mente, as memórias e o coração de soldado.

### O guardião
O Exército guarda o caso em segredo absoluto e o batiza de **Jaguaretê**, do tupi *jaguara* (onça) e *etê* (verdadeiro): **"a onça verdadeira"**, o nome indígena da onça-pintada. Nas comunidades ribeirinhas, quem vê seus olhos brilhando entre as árvores jura ter encontrado o **Yaguareté-Abá**, o homem que vira onça das lendas da sua cultura.

Promovido a **sargento**, ele hoje comanda o **Esquadrão Sombra da Mata**, uma unidade secreta que age "invisível" na floresta. A missão É encontrar e destruir os outros laboratórios escondidos na Amazônia, libertar os animais e as pessoas capturados e impedir que o plano dos estrangeiros se espalhe pelo mundo.

### Valores
- **Coragem:** Nunca recua quando alguém precisa ser salvo;
- **Justiça:** Faz o que é certo, mesmo quando isso vai contra as ordens;
- **Disciplina:** Herdada do karatê, guia cada passo e cada golpe;
- **Lealdade:** Ao Brasil, aos companheiros do esquadrão e ao povo da floresta;
- **Proteção da natureza:** Depois de ver as onças presas no laboratório, jurou defender a Amazônia e os seus animais;
- **Humildade:** Nunca esqueceu de onde veio. A força que ganhou é usada para servir, nunca para dominar.

## Seções da página

- **Sobre o Herói:** A história em 4 capítulos, a origem do nome, a lenda e a personalidade;
- **Atributos & Habilidades:** Barras de progresso (Agilidade, Velocidade, Coragem, Técnica de luta, Força), habilidades e ponto fraco;
- **Inventário:** 6 itens com raridade (lendário, épico, raro e comum);
- **Conquistas & Objetivos:** Missões concluídas e em andamento;
- **Contato com o Esquadrão:** Links e botão de mensagem.

## Tecnologias

- HTML5 semântico;
- CSS3 em arquivo externo (`style.css`);
- Flexbox no menu e CSS Grid no inventário;
- Media queries: 1 coluna no celular, 2 no tablet e 3 no desktop;
- Variáveis CSS no `:root` com paleta;
- Google Fonts (Black Ops One, Barlow e Barlow Condensed) e ícones do Font Awesome;

## Estrutura de pastas

```
ficha-heroi-parte1/
├── index.html
├── style.css
├── README.md
└── imagens/
```

## Como abrir

Abra a pasta no VS Code e clique em **Go Live** (extensão Live Server), ou dê dois cliques no `index.html`.

## Decisões de UI/UX

- **Hierarquia visual:** O nome "Jaguaretê" é o maior texto da página e aparece logo na capa, ao lado da imagem do personagem. Depois vêm o subtítulo e os botões, guiando o olhar do herói para as ações;
- **Contraste e legibilidade:** Fundo escuro (carvão e verde-escuro) com texto claro (areia e prata), seguindo a referência WCAG AA. O dourado é usado só em destaques;
- **Consistência:** Todos os cards de item, missões e barras de atributo seguem o mesmo padrão de borda, cor, espaçamento e cantos, definidos nas variáveis do `:root`;
- **Affordance e feedback:** Botões, links e cards mudam de cor e crescem levemente ao passar o mouse (`transition`), mostrando que são clicáveis;
- **Área de toque (Lei de Fitts):** Botões e links do menu têm no mínimo 44px de altura, para facilitar o toque no celular;
- **Proximidade (Gestalt):** Em cada atributo, o ícone, o nome, o valor e a barra ficam agrupados, e a explicação vem logo abaixo;
- **Fluxo de leitura:** A página segue uma ordem natural de cima para baixo: apresentação do herói, história, atributos, inventário, conquistas e, por último, o contato com o esquadrão.

## Autor

Nome: Rychard Mendes Rombaldo

Curso: Engenharia da Computação

RA: 268958