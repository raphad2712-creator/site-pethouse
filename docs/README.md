# PetHouse

Projeto acadêmico de uma loja de produtos e serviços para animais de estimação. Desenvolvido com HTML e CSS, sem JavaScript e sem comentários no código.

## Como abrir

Abra a pasta no VS Code, instale a extensão Live Server e escolha Open with Live Server no arquivo index.html. Também é possível abrir index.html diretamente no navegador.

## Organização

| Caminho | Conteúdo |
| --- | --- |
| index.html | Apresentação, produtos em destaque, serviços e espaço para vídeo |
| produtos.html | Catálogo |
| mundo-pet.html | Informações sobre cuidados com animais |
| fornecedores.html | Fornecedores |
| orcamentos.html | Formulário de orçamento |
| feedbacks.html | Avaliações, banner e formulário |
| fidelidade.html | Banner, pontos, selos e exemplo de progresso |
| agendamento.html | Serviços, valores, espaço para vídeo e formulário |
| carrinho.html | Exemplo de carrinho |
| contato.html | Contatos e mapa de São Paulo |
| login.html e cadastro.html | Telas demonstrativas de acesso |
| css/style.css | Estilos compartilhados e variáveis de cores e espaçamentos |
| css/login.css | Estilos específicos de login e cadastro |
| css/mundo-pet.css | Estilos da página Mundo Pet |
| imagens/ | Fotos de produtos, pets e fundo do login |
| videos/ | Pasta preparada para receber os vídeos |
| docs/ | Instruções, diário e estimativa de trabalho |

## Design

O verde aparece na marca e na navegação. O laranja destaca preços e botões. O fundo creme mantém o contraste com os cartões brancos. A fonte principal é Arial. O login usa um CSS separado para o fundo e o cartão centralizado. As cores e os espaçamentos principais ficam no início de style.css, em :root.

As telas se adaptam ao celular com media queries. As imagens têm texto alternativo, os campos têm rótulos e o mapa possui título. Os formulários usam validação nativa do HTML.

## Equipe e tarefas

Integrante identificado: Raphael David Silva Freitas. Nomes dos demais integrantes e divisão efetiva das tarefas: a informar pelo grupo.

| Área | Responsável |
| --- | --- |
| Página inicial e navegação | A confirmar pelo grupo |
| Produtos e fornecedores | A confirmar pelo grupo |
| Login, cadastro e formulários | A confirmar pelo grupo |
| Mundo Pet e imagens | A confirmar pelo grupo |
| Revisão e documentação | A confirmar pelo grupo |

## Pendências

Adicionar videos/apresentacao.mp4 e videos/servicos.mp4. As imagens de capa já existem e seus caminhos correspondem às extensões reais. Os banners reutilizam fotos disponíveis no projeto.

Informar o endereço verdadeiro para substituir o mapa geral de São Paulo. O endereço e os contatos atuais são exemplos acadêmicos.

Preencher os nomes e responsabilidades do grupo e os tempos realmente gastos no orçamento.

## Limites do projeto

Login, cadastro, carrinho e fidelidade são demonstrações estáticas. Não existe banco de dados ou autenticação. Os formulários com mailto dependem de um aplicativo de e-mail configurado; não salvam dados no servidor. A confirmação de senha não é comparada automaticamente, pois o projeto utiliza somente HTML e CSS.
