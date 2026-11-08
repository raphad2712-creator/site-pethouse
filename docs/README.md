# PetHouse

Trabalho prático de Desenvolvimento Web do Grupo 7, do curso de Engenharia de Software da Universidade Cidade de São Paulo (UNICID). O projeto apresenta uma loja de produtos e serviços para animais de estimação e foi desenvolvido com HTML e CSS simples.

**Site:** [PetHouse no GitHub Pages](https://raphad2712-creator.github.io/site-pethouse/)

**Documentação:** [PDF](Documentacao_PetHouse_Grupo_7.pdf) · [Word editável](Documentacao_PetHouse_Grupo_7.docx) · [Diário](diario.md) · [Orçamento de esforço](orcamento.md)

## Objetivo e proposta

Aplicar os conteúdos de estruturação de páginas, semântica HTML, formulários, tabelas, imagens, mídias incorporadas e responsividade em um site com navegação entre páginas. A PetHouse reúne catálogo, informações sobre pets, serviços, orçamento, avaliações e telas demonstrativas de acesso.

## Equipe e contribuições

| Integrante | Participação | Tempo informado |
| --- | --- | --- |
| Raphael David Silva Freitas | Desenvolvimento da página de Produtos e organização do catálogo. | Não informado |
| Ruan Silva Costa | Ajustes na página inicial. | Não informado |
| Jioselia Abigail Picco Mollo | Desenvolvimento da página Mundo Pet. | Aproximadamente 2 horas e alguns minutos |
| Joana Manuele Freitas Silva | Revisão do projeto e relatório de alterações, abrangendo CSS, mídias e documentação. | 3 horas |
| Luan de Oliveira Mendes | Criação inicial da página de Login. | Entre 2 e 3 horas |
| Klener Nilmar Quispe Cari | Desenvolvimento da página de Login e inclusão do acesso a novo cadastro. | 2 horas |
| João Victor Fava Yamada | Desenvolvimento da página de Cadastro. | Não informado |

As contribuições e os tempos seguem os relatos dos integrantes e a distribuição informada pelo grupo. O Login recebeu a contribuição de Luan e Klener. O nome completo de João Victor foi identificado na autoria dos commits de cadastro. Os tempos não informados não foram estimados como se fossem horas reais.

## Páginas e navegação

| Arquivo | Conteúdo |
| --- | --- |
| index.html | Apresentação, imagem principal, destaques, serviços, contato e espaço de vídeo |
| produtos.html | Catálogo com imagens, categorias, preços e consulta de produtos |
| mundo-pet.html | Alimentação, higiene, saúde e diversão dos animais |
| fornecedores.html | Apresentação de fornecedores |
| orcamentos.html | Formulário para solicitação de orçamento |
| feedbacks.html | Avaliações ilustrativas, banner e formulário de opinião |
| fidelidade.html | Tabelas de pontos e benefícios, banner e exemplo de progresso |
| agendamento.html | Tabela de serviços, espaço de vídeo e formulário |
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
| videos/ | Pasta destinada a apresentacao.mp4 e servicos.mp4 |
| docs/ | Documentação acadêmica, diário e orçamento |
| README.md | Apresentação e instruções do repositório |

## Tecnologias e decisões de design

O HTML organiza o conteúdo e o CSS define a apresentação. Foram mantidos arquivos simples, sem JavaScript, frameworks, bibliotecas ou comentários no código.

A fonte principal é Arial. O verde `#386b5a` identifica a marca e a navegação; o laranja `#c9572b` destaca botões e preços; o creme `#fffbf5` compõe o fundo. O rodapé usa verde escuro `#263e36`. As cores, os raios de borda e o espaçamento principal ficam em variáveis no bloco `:root` de `css/style.css`.

Regras iguais foram agrupadas para evitar repetições. O CSS do Login permanece separado para concentrar o fundo e o cartão centralizado. As imagens mantêm proporções adequadas com `object-fit`. Os banners e as capas dos vídeos reutilizam imagens já disponíveis no projeto.

## Semântica e acessibilidade

O projeto utiliza `header`, `nav`, `main`, `section`, `article`, `figure`, `address` e `footer` conforme a função de cada conteúdo. As páginas têm título principal, os cartões apresentam subtítulos e as tabelas usam `thead`, `tbody` e cabeçalhos com `scope="col"`.

As imagens têm texto alternativo. Os campos possuem rótulos associados com `label` e `for`; o navegador utiliza `required`, tipos de entrada, tamanho mínimo e `pattern` nos campos aplicáveis. Telefones usam DDD e 10 ou 11 dígitos; os usuários de Login e Cadastro aceitam de 3 a 20 letras sem acento, números ou sublinhado. A navegação por teclado possui destaque de foco. O mapa tem `title` e carregamento adiado.

As grades passam para uma coluna em telas de até 700 px, o menu pode quebrar linha e as tabelas possuem rolagem horizontal quando necessário. O Login inclui ajuste adicional para telas de até 480 px.

## Mídias

| Local | Implementação | Situação |
| --- | --- | --- |
| Página inicial | Imagem principal e elemento video com controles, capa e texto alternativo | Imagem disponível; apresentacao.mp4 pendente |
| Agendamento | Elemento video com controles e capa | servicos.mp4 pendente de envio |
| Contato | iframe do Google Maps | Mapa geral de São Paulo; endereço real pendente |
| Feedbacks | Banner com foto de gato recebendo cuidados | Disponível |
| Fidelidade | Banner com foto de cachorro | Disponível |

O endereço `http://127.0.0.1:5500/videos/servicos.mp4` aponta para um servidor local e não disponibiliza o arquivo no GitHub Pages. O HTML já utiliza o caminho relativo `videos/servicos.mp4`. Para concluir a publicação, é necessário adicionar esse arquivo à pasta `videos`, conferir a reprodução e retirar o aviso “Vídeo em breve.” da página correspondente.

## Requisitos do relatório de avaliação

Esta relação reúne os itens descritos no relatório de alterações fornecido ao grupo. A avaliação e a nota dependem da conferência do professor.

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
| Capas com extensões corretas | Capas de vídeos apontam para imagens existentes .jpg e .png |
| Vídeo de apresentação | Estrutura pronta; arquivo ainda ausente |
| Vídeo de serviços | Estrutura pronta; arquivo ainda ausente |
| Google Maps | Incorporado; localização definitiva ainda não informada |
| README com proposta, execução, estrutura e tecnologias | Este arquivo |
| Identificação e divisão de tarefas | Tabela de equipe acima |
| Diário de bordo | docs/diario.md, com acontecimentos confirmados |
| Orçamento de esforço e comparação de horas | docs/orcamento.md, com estimativas e tempos relatados separados |
| Documentação acadêmica | Versões em PDF e Word em docs |

## Verificação e limites

Na simplificação do código foram comparados os estilos renderizados e o conteúdo das 12 páginas no navegador, sem diferenças nos itens conferidos. Também foram revisados links locais, imagens, rótulos, títulos e cabeçalhos de tabelas. Os vídeos continuam como arquivos pendentes, portanto sua reprodução ainda não foi validada.

Login, Cadastro, Carrinho e Fidelidade são demonstrações estáticas: não há autenticação, gravação de dados, compra ou cálculo de pontos no servidor. Os formulários com `mailto` dependem de um aplicativo de e-mail configurado. O HTML não compara automaticamente os dois campos de senha. O endereço, o telefone e as avaliações apresentados têm finalidade ilustrativa.

## Pendências de entrega

- Adicionar os arquivos de vídeo e conferir reprodução, conteúdo e eventuais legendas.
- Informar o endereço real para configurar a localização definitiva no mapa.
- Complementar as horas de Raphael, Ruan e João Victor, se houver registro.
- Confirmar com o professor se os comentários no código são obrigatórios.

## Fontes do registro

Relatos dos integrantes compartilhados em novembro de 2026; relatório de alterações PetHouse de 7 de novembro de 2026; histórico e arquivos deste repositório. Para apresentação acadêmica, foi consultada a ABNT NBR 14724:2024. A formatação de páginas se aplica ao PDF e ao Word; o README mantém a leitura própria do GitHub.
