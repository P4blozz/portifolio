# Portfólio Minimalista de Pablo

Um portfólio extremamente profissional, limpo, moderno e direto ao ponto. Estrutura pronta para preencher apenas o essencial.

## Estrutura
```
index.html          // Página principal
assets/
  css/style.css     // Estilos globais minimalistas (dark/light)
  js/main.js        // Interações leves (tema, ano, menu mobile)
  img/              // Imagens (coloque profile.jpg e favicon.svg)
  docs/             // (opcional) CV.pdf
```

## Principais Seções
- Hero: nome, título, call-to-actions
- Sobre: 3 blocos curtos (Foco / Valor / Atual)
- Skills: lista de competências essenciais
- Projetos Selecionados: cards com impacto e stack
- Contato: links diretos (email, LinkedIn, GitHub, CV)

## Customização Rápida
1. Edite o título e meta description em `index.html`.
2. Substitua "Seu Título Profissional" por sua função real.
3. Ajuste o parágrafo `.tagline` para refletir sua proposta de valor.
4. Atualize os 3 blocos da seção Sobre.
5. Ajuste as skills reais (mantenha concisas).
6. Em Projetos: inclua só 3–6 projetos relevantes (impacto mensurável).
7. Atualize links de contato e coloque seu `CV.pdf` em `assets/docs/`.
8. Adicione sua foto em `assets/img/profile.jpg` (aprox 600x600, corte quadrado).

## Estilo / Design
- Tipografia: Inter
- Cores: modo escuro por padrão (respeita `prefers-color-scheme`)
- Layout responsivo com grid adaptável
- Componentes reutilizáveis (cards, tags, botões)

## Acessibilidade
- Navegação com teclado (focus states visíveis)
- Botão de alternância de tema com `aria-label`
- Menu mobile com `aria-expanded`

## Performance / Boas Práticas
- CSS único minificado manualmente se desejar (pode reduzir espaços)
- Sem dependências externas JS (apenas fonte Google)
- Imagens: use formatos otimizados (WebP/AVIF se quiser)

## Futuras Extensões (Opcional)
- Analytics leve (Plausible/Umami)
- Sitemap simples
- Manifest + Service Worker para PWA
- Micro animações com `@keyframes` suaves

## Deploy Rápido
- GitHub Pages: coloque os arquivos na branch `main` e ative Pages
- Vercel / Netlify: arraste a pasta ou conecte o repositório

## Licença
Uso pessoal livre. Para compartilhar como template, mantenha referência.

---
Qualquer ajuste extra que quiser (ex: versão em inglês, animação de entrada, modo ultra-claro), é só pedir.
