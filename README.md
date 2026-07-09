# Império das Piscinas — Landing Pages

Duas landing pages de conversão para a **Império das Piscinas**, especialista em aquecimento solar e capas térmicas de piscinas em Goiânia e região.

Páginas estáticas em HTML/CSS/JS puro (sem build, sem dependências), publicadas via **cPanel Git Version Control**.

## Estrutura

```
.
├── index.html               # tela seletora (raiz do domínio) — escolhe entre as duas LPs
├── aquecedores.html         # LP de aquecimento solar -> /aquecedores
├── capas-termica.html       # LP de capas térmicas 300 micras -> /capas-termica
├── .htaccess                # URLs limpas, HTTPS, gzip, cache
├── .cpanel.yml               # tarefa de deploy do cPanel Git Version Control
├── robots.txt / sitemap.xml
├── assets/
│   ├── favicon-dark.svg / favicon-light.svg   # trocam conforme o tema do navegador
│   ├── apple-touch-icon.png / favicon-48.png
│   └── img/                 # imagens em WebP otimizado + og-image.jpg
└── README.md
```

## URLs

- `/` — seletor entre as LPs
- `/aquecedores` — aquecimento solar
- `/capas-termica` — capas térmicas (URL antiga `/v2` redireciona automaticamente)

## Como visualizar localmente

Suba um servidor estático simples (ex.: `npx serve .`) e acesse `http://localhost:.../index.html`. As URLs limpas (`/aquecedores`, `/capas-termica`) só funcionam com as regras do `.htaccess`, ativas no servidor de produção (Apache/cPanel).

## Identidade visual

- **Azul-marinho** `#0C1860` (cor da marca, derivada da logo)
- **Azul-água** `#0E7EC4` (CTA e destaques)
- **Branco** como base
- Tipografia: Sora (títulos) + Inter (corpo)

## Seções

Faixa de urgência · Hero · Prova numérica · Problema · Solução (galeria) · Processo · Diferenciais · Depoimento · FAQ · Formulário de orçamento · Rodapé.

## Pendências

- Substituir o depoimento ilustrativo por prova social real de cliente.
- Validar a copy com o cliente / redação.
- Conectar o formulário a um destino real (hoje é apenas visual).
