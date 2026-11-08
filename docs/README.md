# PetHouse

Trabalho prático de Desenvolvimento Web do Grupo 7, do curso de Engenharia de Software da Universidade Cidade de São Paulo (UNICID). O projeto apresenta uma loja de produtos e serviços para animais de estimação e foi desenvolvido com HTML e CSS simples.

**Site:** [PetHouse no GitHub Pages](https://raphad2712-creator.github.io/site-pethouse/)

**Documentação:** [Diário](diario.md) · [Orçamento de esforço](orcamento.md) · [Checklist da entrega](checklist_entrega.md) · [Roteiro](apresentacao.md) · [Evidências](evidencias.md)

## Objetivo e proposta

Aplicar os conteúdos de estruturação de páginas, semântica HTML, formulários, tabelas, imagens, mídias incorporadas e responsividade em um site com navegação entre páginas. A PetHouse reúne catálogo, informações sobre pets, serviços, orçamento, avaliações e telas demonstrativas de acesso.

## Equipe e contribuições

As participações informadas seguem os relatos do grupo. As atribuições sugeridas completam a divisão das 12 páginas e precisam ser confirmadas pelos integrantes; não representam autoria passada comprovada. As horas acrescentadas são estimativas de planejamento, não registros reais. Estefany foi incluída com o nome informado, sem sobrenome.

| Integrante | Participação | Tempo e natureza |
| --- | --- | --- |
| Raphael David Silva Freitas | Produtos (informada); Fornecedores (sugerida). | 4 h estimadas para as duas páginas |
| Ruan Silva Costa | Ajustes na página inicial (informada). | 2 h estimadas |
| Jioselia Abigail Picco Mollo | Mundo Pet (informada). | Aproximadamente 2 h e alguns minutos relatados |
| Joana Manuele Freitas Silva | Revisão de CSS e documentação (informada); Fidelidade e Orçamentos (sugeridas). | 3 h relatadas na revisão; mais 2 h estimadas para as páginas sugeridas |
| Luan de Oliveira Mendes | Criação inicial do Login (informada). | Entre 2 e 3 h relatadas |
| Klener Nilmar Quispe Cari | Login e acesso ao Cadastro (informada); Agendamento e Carrinho (sugeridas). | 2 h relatadas no Login; mais 3 h estimadas para as páginas sugeridas |
| João Victor Fava Yamada | Cadastro (informada). | 3 h estimadas |
| Estefany | Contato e Feedbacks (sugeridas). | 3 h estimadas |

## Divisão das 12 páginas

| Página | Integrante responsável | Origem da atribuição |
| --- | --- | --- |
| index.html | Ruan Silva Costa | Informada |
| produtos.html | Raphael David Silva Freitas | Informada |
| mundo-pet.html | Jioselia Abigail Picco Mollo | Informada |
| fornecedores.html | Raphael David Silva Freitas | Sugerida |
| orcamentos.html | Joana Manuele Freitas Silva | Sugerida |
| feedbacks.html | Estefany | Sugerida |
| fidelidade.html | Joana Manuele Freitas Silva | Sugerida |
| agendamento.html | Klener Nilmar Quispe Cari | Sugerida |
| carrinho.html | Klener Nilmar Quispe Cari | Sugerida |
| contato.html | Estefany | Sugerida |
| login.html | Luan de Oliveira Mendes e Klener Nilmar Quispe Cari | Informada |
| cadastro.html | João Victor Fava Yamada | Informada |

## Páginas e navegação

| Arquivo | Conteúdo |
| --- | --- |
| index.html | Apresentação, imagem principal, destaques, serviços, perguntas frequentes e contato |
| produtos.html | Catálogo com imagens, categorias, preços e consulta de produtos |
| mundo-pet.html | Alimentação, higiene, saúde e diversão dos animais |
| fornecedores.html | Apresentação de fornecedores |
| orcamentos.html | Formulário para solicitação de orçamento |
| feedbacks.html | Avaliações ilustrativas, banner e formulário de opinião |
| fidelidade.html | Tabelas de pontos e benefícios, banner e exemplo de progresso |
| agendamento.html | Tabela de serviços e formulário com orientações |
| carrinho.html | Exemplo de carrinho de compras |
| contato.html | Informações de contato e mapa incorporado |
| login.html | Tela demonstrativa de Login e link para Cadastro |
| cadastro.html | Tela demonstrativa de Cadastro |

O cabeçalho apresenta os links de navegação. A página ativa é identificada com `aria-current="page"`. Login e Cadastro oferecem acesso de volta ao início.

## Como abrir o projeto

1. Baixe ou clone este repositório.
2. Abra a pasta no Visual Studio Code.
3. Com a extensão Live Server instalada, clique com o botão direito em `index.html` e escolha **Open with Live Server**.
4. Navegue pelos links do menu. Também é possível abrir `index.html` diretamente no navegador.

O site estático não exige instalação de pacotes, compilação ou banco de dados. O mapa precisa de conexão com a internet.

## Organização dos arquivos

| Pasta ou arquivo | Função |
| --- | --- |
| Arquivos .html na raiz | Conteúdo das 12 páginas |
| css/style.css | Estilos compartilhados, variáveis e regra de adaptação para celular |
| css/login.css | Fundo, cartão e campos de Login e Cadastro |
| css/mundo-pet.css | Estilos exclusivos de Mundo Pet |
| imagens/ | Fotos de produtos, animais, banners e fundo do Login |
| videos/ | Instruções para adicionar um vídeo quando o arquivo for recebido |
| docs/ | README, diário, orçamento, checklist e roteiro |
| README.md | Apresentação e instruções do repositório |

## Tecnologias e decisões de design

O HTML organiza o conteúdo e o CSS define a apresentação. Foram mantidos arquivos simples, sem JavaScript, frameworks, bibliotecas ou comentários no código.

A fonte principal é Arial. O verde `#386b5a` identifica a marca e a navegação; o laranja `#c9572b` destaca botões e preços; o creme `#fffbf5` compõe o fundo. O rodapé usa verde escuro `#263e36`. As cores, os raios de borda e o espaçamento principal ficam em variáveis no bloco `:root` de `css/style.css`.

Regras iguais foram agrupadas para evitar repetições. O CSS do Login permanece separado para concentrar o fundo e o cartão centralizado. As imagens mantêm proporções adequadas com `object-fit`. Os banners reutilizam imagens disponíveis no projeto. A instrução de vídeo opcional também utiliza uma imagem existente como capa.

## Semântica e acessibilidade

O projeto utiliza `header`, `nav`, `main`, `section`, `article`, `figure`, `address` e `footer` conforme a função de cada conteúdo. As páginas têm título principal, os cartões apresentam subtítulos e as tabelas usam `thead`, `tbody` e cabeçalhos com `scope="col"`.

As imagens têm texto alternativo. Os campos possuem rótulos associados com `label` e `for`; o navegador utiliza `required`, tipos de entrada, tamanho mínimo e `pattern` nos campos aplicáveis. Telefones usam DDD e 10 ou 11 dígitos; os usuários de Login e Cadastro aceitam de 3 a 20 letras sem acento, números ou sublinhado. A navegação por teclado possui destaque de foco e link para pular ao conteúdo. As perguntas frequentes usam details/summary, sem JavaScript. Os campos obrigatórios são marcados e possuem orientações de preenchimento. O mapa tem `title` e carregamento adiado.

As grades passam para uma coluna em telas de até 700 px, o menu pode quebrar linha e as tabelas possuem rolagem horizontal quando necessário. O Login inclui ajuste adicional para telas de até 480 px.

## Mídias

A versão de entrega utiliza um **iframe do Google Maps** na página Contato. A rubrica aceita vídeo, áudio ou iframe. O mapa é responsivo, tem título, carregamento adiado e link para acesso externo. O carregamento foi conferido no navegador. Ele apresenta São Paulo; o endereço da loja continua ilustrativo.

Os dois players que apontavam para vídeos ausentes foram removidos para evitar erros na apresentação. O arquivo `servicos.mp4` pode ser incluído posteriormente seguindo [videos/README.md](../videos/README.md), caso o grupo o forneça. O link `127.0.0.1` não publica esse arquivo. A imagem principal e os banners de Feedbacks e Fidelidade continuam disponíveis.

## Segunda entrega e rubrica

O líder ou uma pessoa delegada por ele deve enviar no Blackboard o **link do repositório público e o arquivo ZIP**. O prazo é o primeiro dia de apresentação da turma; a data exata precisa ser conferida no calendário da sala. O professor considera apenas a última versão enviada. Guarde o ZIP entregue e apresente essa versão se o GitHub receber mudanças posteriores.

A rubrica soma 5 pontos: codificação (3), documentação e criatividade (1) e apresentação (1). A distribuição dos 12 critérios e as ações de conferência estão em [docs/checklist_entrega.md](checklist_entrega.md). A [rubrica recebida](rubrica_avaliacao.jpeg), o [roteiro de 7 minutos](apresentacao.md) e as [evidências de revisão](evidencias.md) acompanham o projeto. A nota e a validação final cabem ao professor.

## Requisitos do projeto

Esta relação resume os itens de implementação e documentação. A entrega solicitada pelo professor é o link do repositório e o ZIP; não há relatório em PDF ou Word neste pacote.

| Item | Evidência ou situação |
| --- | --- |
| CSS com variáveis | Cores e medidas compartilhadas no bloco :root |
| Organização e simplificação do CSS | Regras repetidas agrupadas e classes sem uso removidas |
| Comentários explicativos no CSS | Omitidos conforme a orientação de manter o código sem comentários; verificar a exigência do professor |
| Login com CSS próprio | login.css concentra estilos específicos e utiliza o CSS global |
| Semântica HTML | Estrutura com elementos adequados e títulos organizados |
| Formulários e validação | label/for, required, type, minlength e pattern nos campos aplicáveis |
| Responsividade | Media queries, menu flexível, imagens adaptáveis e tabelas com rolagem |
| Imagem principal e banners | Arquivos existentes referenciados nas páginas |
| Caminhos e extensões das imagens | Imagens e banners referenciados existem; o exemplo de vídeo usa uma capa .png disponível |
| Mídia de apresentação | O iframe do mapa atende ao tipo de mídia previsto; vídeo é opcional |
| Vídeo de serviços | Arquivo ainda não recebido; nenhum player quebrado na página |
| Google Maps | Incorporado; localização definitiva ainda não informada |
| README com proposta, execução, estrutura e tecnologias | Este arquivo |
| Identificação e divisão de tarefas | Tabela de equipe acima |
| Diário de bordo | docs/diario.md, com acontecimentos confirmados |
| Orçamento de esforço e comparação de horas | docs/orcamento.md, com estimativas e tempos relatados separados |
| Documentação do projeto | README e arquivos Markdown em docs |

## Verificação e limites

Na simplificação do código foram comparados os estilos renderizados e o conteúdo das 12 páginas no navegador, sem diferenças nos itens conferidos. Também foram revisados links locais, imagens, rótulos, títulos e cabeçalhos de tabelas. O mapa carregou, as perguntas frequentes abriram e os campos foram verificados com entradas válidas e inválidas. As 12 páginas não apresentaram rolagem horizontal geral em quadros móveis de 390 px. Os detalhes e limites dessas verificações estão em docs/evidencias.md.

Login, Cadastro, Carrinho e Fidelidade são demonstrações estáticas: não há autenticação, gravação de dados, compra ou cálculo de pontos no servidor. Os formulários com `mailto` dependem de um aplicativo de e-mail configurado. O HTML não compara automaticamente os dois campos de senha. O endereço, o telefone e as avaliações apresentados têm finalidade ilustrativa.

## Pendências de entrega

- Enviar o vídeo somente se o grupo quiser incluí-lo além do iframe que já funciona.
- Informar o endereço real para configurar a localização definitiva no mapa.
- Confirmar a divisão sugerida e substituir estimativas por horas reais quando houver registro.
- Confirmar com o professor se os comentários no código são obrigatórios.

## Fontes do registro

Rubrica de avaliação e comunicado da segunda entrega fornecidos pelo professor; relatos dos integrantes compartilhados em novembro de 2026; relatório de alterações PetHouse de 7 de novembro de 2026; histórico e arquivos deste repositório. O README e os arquivos Markdown mantêm a leitura própria do GitHub; relatórios em PDF e Word foram retirados desta versão.
