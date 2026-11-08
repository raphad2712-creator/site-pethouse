# Vídeos opcionais

O arquivo servicos.mp4 ainda não foi fornecido ao repositório. Para evitar players quebrados, a versão de entrega usa o iframe do Google Maps como mídia incorporada. A rubrica aceita vídeo, áudio ou iframe.

Quando o grupo receber o arquivo, deve salvá-lo em videos/servicos.mp4 e incluir o trecho abaixo na página agendamento.html, dentro de uma section com título. Não usar endereços iniciados em 127.0.0.1 no site publicado.

```html
<section>
  <h2>Conheça nossos serviços</h2>
  <video controls preload="metadata" poster="imagens/gatohigiene.png">
    <source src="videos/servicos.mp4" type="video/mp4">
    Seu navegador não suporta vídeo.
  </video>
</section>
```

Conferir reprodução e áudio antes de gerar um novo ZIP de entrega. O CSS compartilhado já prepara o vídeo para se adaptar à largura da página.
