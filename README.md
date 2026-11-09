# PetHouse

Projeto do Grupo 7 de Engenharia de Software da UNICID: site de produtos e serviços para animais de estimação, desenvolvido com HTML e CSS.

[Site publicado](https://raphad2712-creator.github.io/site-pethouse/) · [Repositório](https://github.com/raphad2712-creator/site-pethouse)

## Como executar

Abra `index.html` no navegador ou use a extensão Live Server no Visual Studio Code. Não é necessário instalar pacotes. O vídeo e o mapa precisam de internet.

## Equipe e divisão de tarefas

A tabela organiza as responsabilidades pelas páginas. As estimativas de tempo e os registros de esforço estão em [docs/orcamento.md](docs/orcamento.md).

| Integrante | Responsabilidades |
| --- | --- |
| Raphael David Silva Freitas | Produtos e Fornecedores |
| Ruan Silva Costa | Página inicial |
| Jioselia Abigail Picco Mollo | Mundo Pet |
| Joana Manuele Freitas Silva | Fidelidade, Orçamentos, revisão de CSS e documentação |
| Luan de Oliveira Mendes | Criação inicial do Login |
| Klener Nilmar Quispe Cari | Login, acesso ao Cadastro, Agendamento e Carrinho |
| João Victor Fava Yamada | Cadastro |
| Estefany Isidro Pachacuti | Logo no cabeçalho, ícone da aba e linha laranja de separação no menu |
| Giovanni Ferreira dos Santos — RGM 48091341 | Contribuição a confirmar |

## Estrutura e tecnologias

- Arquivos HTML na raiz: as 12 páginas do site.
- `css/`: estilos compartilhados e estilos de Login e Mundo Pet.
- `imagens/`: imagens de produtos, banners e fundo do Login.
- `docs/`: diário, orçamento de esforço, evidências e roteiro de apresentação.

O HTML usa elementos semânticos, títulos, rótulos e validação nativa nos formulários. O CSS utiliza variáveis, Flexbox, Grid e media queries para adaptar o site ao celular. Não há JavaScript ou banco de dados.

## Decisões de design e mídias

A identidade visual utiliza verde, laranja e fundo creme, com fonte Arial e componentes compartilhados. O CSS de Login fica separado para o fundo e o cartão dessa página. As cores e medidas principais estão em `:root`, no arquivo `css/style.css`.

Agendamento incorpora o vídeo [Como dar banho em cachorro em casa?](https://www.youtube.com/watch?v=IUNmfBJkSUs), produzido pela Petz TV. Contato incorpora o Google Maps. As duas mídias se adaptam à largura da página. O endereço da loja é ilustrativo.

## Documentação

- [Diário de bordo](docs/diario.md)
- [Orçamento de esforço e tempos](docs/orcamento.md)

As telas de Login, Cadastro, Carrinho e Fidelidade são demonstrativas. Os formulários com `mailto` abrem o aplicativo de e-mail; os dados não são salvos no servidor.
