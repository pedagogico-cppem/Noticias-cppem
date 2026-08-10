# CPPEM Notícias — Portal de Concursos

Portal de notícias e análises estratégicas sobre concursos públicos em Pernambuco, com foco em carreiras policiais.

## Páginas disponíveis

| Página | Descrição |
|--------|-----------|
| **Início** | Cards com as principais notícias |
| **Concursos em PE** | Análise dos fatores que pressionam novos certames |
| **PPRN — Reta Final** | Estratégia de estudos com 74 dias para a prova |
| **GCM Tamandaré** | Edital completo: vagas, matérias, TAF e cronograma |

## Tecnologias

- HTML5 puro
- CSS3 com variáveis customizáveis
- JavaScript vanilla (SPA com navegação por páginas)
- Sem dependências externas — funciona offline

## Como usar

Basta abrir o arquivo `index.html` no navegador. Não requer servidor.

## Identidade visual

As cores estão definidas como variáveis CSS no topo do `index.html`:

```css
--cor-principal:   #0a3d0a;   /* verde escuro */
--cor-secundaria:  #00cc00;   /* verde médio  */
--cor-destaque:    #00FF01;   /* verde CPPEM  */
--cor-fundo:       #f6f5f1;
--cor-texto:       #1c2530;
--cor-card:        #ffffff;
--cor-borda:       #e2e1da;
```

## Publicar via GitHub Pages

1. Faça o push deste repositório para o GitHub
2. Vá em **Settings → Pages**
3. Selecione **Branch: main** e pasta **/ (root)**
4. Acesse em: `https://SEU-USUARIO.github.io/NOME-DO-REPO/`

## Estrutura do projeto

```
cppem-site/
├── index.html      ← arquivo principal (tudo em um só arquivo)
├── README.md       ← este arquivo
└── .gitignore      ← arquivos ignorados pelo Git
```

---

© CPPEM Colégio e Curso — Conteúdo informativo.
