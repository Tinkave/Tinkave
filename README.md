# Site Tinkave — Tinturaria e Acabamentos Têxteis

Site institucional multilingue (PT · ES · EN · FR), estático, pronto a publicar
em qualquer alojamento web. Domínio previsto: **www.tinkave.pt**

## Conteúdo desta pasta
- `index.html` — site principal
- `calculadora.html` — calculadora têxtil (página própria, instalável/PWA)
- `sw.js` — service worker (cache da calculadora offline)
- `img/` — logótipo, poster, fotografias da unidade e logótipos de certificação
- `videos/tinkave.mp4` — vídeo institucional (720p, com áudio)
- `404.html` — página de erro

## Como publicar (servidor próprio)
1. Copia **todo o conteúdo desta pasta** (incluindo o ficheiro oculto `.htaccess`)
   para a raiz pública do servidor — o `DocumentRoot` do site
   (ex.: `/var/www/tinkave/` ou `/var/www/html/`).
2. Garante que `index.html` fica diretamente nessa raiz.
3. **DNS:** cria um registo **A** `www` → IP do teu servidor; e o apex
   `tinkave.pt` a redirecionar/apontar igualmente para o servidor.

### Apache
- O `.htaccess` incluído já força **HTTPS**, redireciona para **www.tinkave.pt**,
  define o `404.html` e ativa cache/compressão.
- Requer os módulos `mod_rewrite`, `mod_expires` e `mod_deflate` ativos
  (e `AllowOverride All` no virtual host para o `.htaccess` ser lido).

### Nginx
- O `.htaccess` é ignorado. No `server` block, equivalente:
  ```
  server {
    listen 443 ssl;
    server_name www.tinkave.pt;
    root /var/www/tinkave;
    index index.html;
    error_page 404 /404.html;
    location / { try_files $uri $uri/ =404; }
  }
  # redirecionar http e apex para https://www.tinkave.pt
  server {
    listen 80;
    server_name tinkave.pt www.tinkave.pt;
    return 301 https://www.tinkave.pt$request_uri;
  }
  ```

### HTTPS (certificado SSL)
- Recomenda-se **Let's Encrypt** com `certbot`:
  `sudo certbot --apache -d tinkave.pt -d www.tinkave.pt`
  (ou `--nginx`). Renova automaticamente.

## Formulário "Pedir proposta" (envio de emails)
Atualmente envia para **geral@tinkave.pt** via FormSubmit (serviço externo, sem servidor).
Funciona, mas precisa de **ativação única** (clicar no link que chega a geral@tinkave.pt
na 1.ª submissão).
> **Tens servidor próprio:** o ideal é trocar para um pequeno **script PHP** que envia
> o email diretamente do servidor (sem terceiros nem passo de ativação). Pede essa
> adaptação — fornece-se o `contacto.php` e liga-se o formulário a ele.

## Notas
- Os logótipos de certificação (OEKO-TEX, GOTS, GRS, OCS, TÜV) foram extraídos dos
  certificados; antes de divulgação ampla, confirmar com os kits oficiais de cada entidade.
- O vídeo de fundo é mudo (em loop); o botão "Ver vídeo" abre a versão completa com som.
- O site é gerado a partir de um script — para alterações de conteúdo, contacta quem mantém o projeto.
