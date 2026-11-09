# Evidências da revisão

Revisão realizada em 8 de novembro de 2026, a partir da rubrica compartilhada pelo grupo. Os resultados abaixo descrevem os casos efetivamente conferidos, sem atribuir nota.

## Casos verificados

| Verificação | Resultado observado |
| --- | --- |
| Estrutura das 12 páginas | Um main e um h1 por página; IDs únicos; rótulos e descrições associados a elementos existentes. |
| Arquivos locais | Links, imagens e folhas de estilo referenciados existem. Os players que apontavam para MP4 ausentes foram removidos. |
| Largura móvel | As 12 páginas foram renderizadas em quadros de 390 px, com área útil de 375 px após a barra de rolagem. Nenhuma apresentou rolagem horizontal geral. |
| Orçamentos com e-mail inválido | typeMismatch foi verdadeiro e o campo foi considerado inválido. |
| Orçamentos com telefone 123 | patternMismatch foi verdadeiro e o campo foi considerado inválido. |
| Orçamentos com quantidade 0 | rangeUnderflow foi verdadeiro para o mínimo 1. |
| Orçamentos com dados corrigidos | Campos verificados ficaram válidos; o envio por e-mail não foi executado. |
| Login com usuário fora do padrão | patternMismatch foi verdadeiro. |
| Login com senha curta digitada pelo teclado | tooShort foi verdadeiro para o mínimo de 6 caracteres. |
| Login demonstrativo com dados válidos | O botão Entrar navegou para Produtos, sem autenticação ou gravação de dados. |
| FAQ | A pergunta sobre solicitação de serviços abriu o conteúdo correspondente. |
| Google Maps | O iframe carregou o mapa de São Paulo e exibiu seus controles e o acesso externo. |

## Trechos de evidência

O trecho abaixo registra o padrão usado no telefone. As descrições visíveis ajudam o usuário a corrigir a entrada.

```html
<label for="telefone">Telefone</label>
<input type="tel" pattern="[0-9]{10,11}" inputmode="numeric"
  id="telefone" name="telefone" aria-describedby="ajuda-telefone">
<small class="ajuda" id="ajuda-telefone">
  Digite o DDD e o telefone, com 10 ou 11 números, sem espaços.
</small>
```

A organização principal está no [CSS compartilhado](../css/style.css). As regras específicas estão em [login.css](../css/login.css) e [mundo-pet.css](../css/mundo-pet.css). A navegação, os formulários e a mídia podem ser conferidos em [Início](../index.html), [Orçamentos](../orcamentos.html), [Login](../login.html) e [Contato](../contato.html).

## Decisões e limitações

Foram preservados HTML e CSS simples e a ausência de comentários no código, conforme orientação do grupo. A rubrica cita comentários claros como parte da faixa Excelente de qualidade do CSS; a documentação externa não garante a mesma avaliação desse item.

O mapa depende da internet. Login, Cadastro, Carrinho e Fidelidade são interfaces estáticas. Os formulários com mailto dependem de um aplicativo de e-mail. As senhas de Cadastro não são comparadas automaticamente. O vídeo da Petz TV é incorporado pelo YouTube, sem depender de MP4 local. A disponibilidade do player depende da conexão e das permissões do YouTube.

Esta conferência não incluiu todos os navegadores ou aparelhos físicos. As regras responsivas foram verificadas no navegador disponível em uma largura de referência móvel.
