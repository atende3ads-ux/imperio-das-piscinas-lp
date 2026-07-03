# Império das Piscinas — Landing Page

Landing page de conversão para a **Império das Piscinas**, especialista em aquecimento solar de piscinas em Goiânia e região.

Página estática em HTML/CSS/JS puro (sem build, sem dependências), publicada via **GitHub Pages**.

## Estrutura

```
.
├── index.html              # página completa (HTML + CSS + JS inline)
├── assets/
│   └── img/
│       ├── logo-navy.png            # logo azul-marinho (fundos claros)
│       ├── logo-white.png           # logo branca (fundos escuros)
│       ├── hero.png                 # imagem de fundo do hero
│       ├── piscina-cascata.png      # galeria de projetos
│       ├── piscina-lazer.png        # galeria + fundo dos diferenciais
│       ├── piscina-entardecer.png   # galeria de projetos
│       └── piscina-entardecer-2.png # foto alternativa (reserva)
├── .nojekyll               # desativa o processamento Jekyll no Pages
└── README.md
```

## Como visualizar localmente

Abra o `index.html` direto no navegador, ou suba um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

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
