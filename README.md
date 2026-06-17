# Landing Page — Mapas Mentais de TI para Concursos

## Deploy na Vercel

### Opção 1 — Via GitHub (recomendado)
1. Crie um repositório no GitHub e suba essa pasta
2. Acesse vercel.com → "New Project" → importe o repositório
3. Clique em Deploy — pronto

### Opção 2 — Via Vercel CLI
```bash
npm i -g vercel
cd mapas-ti-landing
vercel
```

## Personalizar antes do deploy

### 1. Botão de compra
Substitua o `href="#"` do botão `.btn-buy` pelo link da sua plataforma de pagamento:
```html
<a href="https://pay.hotmart.com/SEU-LINK" class="btn-buy">
```

### 2. E-mail de contato
Troque `contato@mapasdeti.com.br` pelo seu e-mail real no footer.

### 3. Vídeo
Substitua o placeholder de vídeo pelo embed do seu vídeo do Google Flow/YouTube:
```html
<iframe width="100%" height="100%" src="https://www.youtube.com/embed/SEU-ID" ...></iframe>
```

### 4. Google Analytics / Meta Pixel
Adicione no `<head>` antes do `</head>`.
