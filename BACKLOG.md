# BACKLOG.md — Landing Page Pão & Cia

> Projeto de portfólio: landing page responsiva para uma padaria artesanal de bairro.

---

## 1. Visão Geral

**Projeto:** Landing Page Pão & Cia  
**Tipo:** Landing page institucional/comercial  
**Stack:** HTML5 + CSS3  
**Objetivo principal:** criar uma página simples, aconchegante, responsiva e orientada à conversão, apresentando a padaria e levando o visitante ao WhatsApp.

### Objetivos

- Apresentar a Pão & Cia de forma profissional.
- Destacar produtos e preços.
- Facilitar o contato pelo WhatsApp.
- Informar endereço e horário de funcionamento.
- Criar uma experiência mobile-first.
- Praticar HTML semântico, CSS responsivo, acessibilidade e Git/GitHub.

---

# 2. Escopo da V1

## Incluído

- Header/navegação.
- Hero/banner principal.
- Seção "Sobre nós".
- Produtos em destaque.
- Horário de funcionamento.
- Endereço.
- CTA para WhatsApp.
- Links para Instagram e Facebook.
- Footer.
- Layout responsivo para celular, tablet e desktop.
- Estados básicos de hover/focus.
- Acessibilidade básica.
- SEO básico.
- Estrutura profissional de projeto.

## Fora do escopo da V1

- Sistema de pedidos.
- Carrinho.
- Checkout/pagamento.
- Login/cadastro.
- Banco de dados.
- Painel administrativo.
- Blog.
- Sistema de avaliações.
- Integração dinâmica com Instagram.
- Backend/Django.

Esses itens podem entrar em versões futuras.

---

# 3. Estrutura Sugerida

```text
pao-e-cia/
├── index.html
├── README.md
├── BACKLOG.md
├── assets/
│   ├── images/
│   └── icons/
├── css/
│   └── style.css
└── .gitignore
```

---

# 4. Convenção de Prioridades

- **P0 — Crítica:** necessária para a V1 funcionar.
- **P1 — Alta:** importante para qualidade e conversão.
- **P2 — Média:** melhoria relevante.
- **P3 — Baixa:** melhoria futura.

---

# 5. Etapas do Desenvolvimento

## ETAPA 01 — Planejamento

### P0 — Definir conteúdo

- [x] Definir nome oficial: **Pão & Cia**.
- [x] Definir slogan: **"Pão fresquinho todos os dias"**.
- [x] Definir texto final da seção Sobre nós.
- [x] Definir endereço.
- [x] Definir horário de funcionamento.
- [x] Insere ícone do WhatsApp.
- [ ] Confirmar URLs do Instagram e Facebook.
- [ ] Confirmar preços dos produtos.

**Estimativa:** 30–60 min  
**Dependências:** nenhuma.

### P1 — Definir identidade visual

- [ ] Definir paleta de cores terrosas/quentes.
- [ ] Definir tipografia.
- [ ] Definir estilo dos botões.
- [ ] Definir bordas, sombras e espaçamentos.
- [ ] Definir tratamento das imagens.

**Estimativa:** 1h  
**Dependências:** conteúdo inicial.

---

# 6. ETAPA 02 — Preparação do Projeto

### P0 — Criar estrutura

- [ ] Criar repositório Git.
- [ ] Criar `index.html`.
- [ ] Criar `css/style.css`.
- [ ] Criar pastas de assets.
- [ ] Criar `.gitignore`.
- [ ] Criar `README.md`.
- [ ] Criar este `BACKLOG.md`.

**Estimativa:** 30 min.

### P0 — Configurar HTML

- [ ] Usar `<!DOCTYPE html>`.
- [ ] Definir `lang="pt-BR"`.
- [ ] Configurar charset UTF-8.
- [ ] Configurar viewport.
- [ ] Criar `<title>` descritivo.
- [ ] Criar meta description.
- [ ] Organizar estrutura semântica.

**Estimativa:** 30 min.

---

# 7. ETAPA 03 — Header

### P0 — Criar cabeçalho

- [ ] Criar logo/nome "Pão & Cia".
- [ ] Criar navegação para as principais seções.
- [ ] Garantir navegação utilizável em telas pequenas.
- [ ] Criar link/âncora para CTA.
- [ ] Definir comportamento visual no hover.
- [ ] Garantir foco visível pelo teclado.

**Critérios de aceitação**

- O nome da padaria é claramente identificável.
- Os links levam às seções corretas.
- O header não quebra em telas pequenas.
- A navegação é acessível por teclado.

**Estimativa:** 1h.

---

# 8. ETAPA 04 — Hero

### P0 — Criar banner principal

Conteúdo:

- Nome: **Pão & Cia**
- Slogan: **"Pão fresquinho todos os dias"**
- Imagem de pão saindo do forno.
- CTA "Peça pelo WhatsApp".

### Tarefas

- [ ] Criar seção hero.
- [ ] Adicionar título principal `<h1>`.
- [ ] Adicionar slogan.
- [ ] Adicionar imagem.
- [ ] Criar CTA.
- [ ] Garantir contraste adequado.
- [ ] Definir altura/layout responsivo.
- [ ] Otimizar imagem para web.

**Critérios de aceitação**

- O visitante entende imediatamente o que é a Pão & Cia.
- O CTA é facilmente encontrado.
- O hero funciona em celular e desktop.
- A imagem não distorce.
- O texto continua legível sobre o fundo.

**Estimativa:** 1h30.

---

# 9. ETAPA 05 — Sobre Nós

### P1 — Criar seção institucional

Conteúdo-base:

> A Pão & Cia é uma padaria de bairro artesanal, dedicada a produzir pães e outros produtos com cuidado, ingredientes selecionados e fermentação natural.

### Tarefas

- [ ] Criar seção "Sobre nós".
- [ ] Criar título `<h2>`.
- [ ] Escrever texto curto.
- [ ] Adicionar imagem complementar, se necessário.
- [ ] Aplicar identidade visual.

**Critérios de aceitação**

- A seção comunica que a padaria é artesanal.
- A fermentação natural é mencionada.
- O texto é curto e fácil de ler no celular.

**Estimativa:** 45 min.

---

# 10. ETAPA 06 — Produtos em Destaque

### P0 — Criar cards de produtos

Produtos:

1. Pão de fermentação natural.
2. Croissant.
3. Bolo de cenoura.
4. Café especial.

Cada card deve conter:

- Imagem.
- Nome.
- Breve descrição opcional.
- Preço.

### Tarefas

- [ ] Criar seção "Produtos em destaque".
- [ ] Criar estrutura semântica para lista de produtos.
- [ ] Criar card reutilizável visualmente.
- [ ] Adicionar os quatro produtos.
- [ ] Adicionar preços.
- [ ] Garantir proporção consistente das imagens.
- [ ] Criar layout responsivo.
- [ ] Adicionar hover sem prejudicar acessibilidade.

**Critérios de aceitação**

- Todos os quatro produtos aparecem corretamente.
- Nome, imagem e preço são legíveis.
- Os cards se reorganizam em telas menores.
- Nenhum conteúdo fica cortado.

**Estimativa:** 1h30.

---

# 11. ETAPA 07 — Informações

### P0 — Horário e endereço

- [ ] Criar seção de informações.
- [ ] Exibir dias e horários.
- [ ] Exibir endereço.
- [ ] Destacar informações importantes.
- [ ] Garantir boa leitura no celular.

**Critérios de aceitação**

- O cliente consegue descobrir quando a padaria está aberta.
- O endereço é claramente identificável.
- As informações não dependem de JavaScript.

**Estimativa:** 45 min.

---

# 12. ETAPA 08 — CTA / WhatsApp

### P0 — Criar chamada para ação

Texto:

**"Peça pelo WhatsApp"**

### Tarefas

- [ ] Criar botão CTA.
- [ ] Configurar link para WhatsApp.
- [ ] Usar formato correto do número.
- [ ] Considerar mensagem inicial pré-preenchida.
- [ ] Criar estado hover.
- [ ] Criar estado focus.
- [ ] Garantir área de toque confortável no celular.

**Critérios de aceitação**

- O botão é facilmente identificável.
- O clique abre o WhatsApp corretamente.
- O CTA funciona em dispositivos móveis.
- O botão possui contraste adequado.

**Estimativa:** 30 min.

> **Importante:** o número real do WhatsApp deve ser fornecido pelo cliente antes da publicação.

---

# 13. ETAPA 09 — Footer

### P1 — Criar rodapé

- [ ] Exibir nome da Pão & Cia.
- [ ] Adicionar Instagram.
- [ ] Adicionar Facebook.
- [ ] Adicionar links funcionais.
- [ ] Adicionar informação de copyright, se desejado.
- [ ] Garantir que os links sejam acessíveis.

**Estimativa:** 30 min.

---

# 14. ETAPA 10 — Responsividade

### P0 — Mobile-first

Breakpoints devem ser definidos conforme o conteúdo, e não apenas por dispositivos específicos.

- [ ] Testar celular pequeno.
- [ ] Testar celular grande.
- [ ] Testar tablet.
- [ ] Testar desktop.
- [ ] Verificar overflow horizontal.
- [ ] Verificar imagens.
- [ ] Verificar tamanho dos textos.
- [ ] Verificar espaçamento.
- [ ] Verificar botões.
- [ ] Verificar navegação.

**Critérios de aceitação**

- Nenhuma seção apresenta scroll horizontal acidental.
- Texto permanece legível.
- Cards se adaptam ao espaço disponível.
- CTA continua fácil de tocar.
- Imagens não quebram o layout.

**Estimativa:** 1h30.

---

# 15. ETAPA 11 — Acessibilidade

### P1

- [ ] Usar HTML semântico.
- [ ] Manter hierarquia correta de headings.
- [ ] Adicionar `alt` adequado às imagens informativas.
- [ ] Usar `alt=""` em imagens puramente decorativas.
- [ ] Garantir contraste suficiente.
- [ ] Garantir foco visível.
- [ ] Não depender apenas de cor para transmitir informação.
- [ ] Verificar navegação por teclado.
- [ ] Garantir áreas de toque adequadas.

**Estimativa:** 1h.

---

# 16. ETAPA 12 — SEO Básico

### P1

- [ ] Definir `<title>`.
- [ ] Criar meta description.
- [ ] Usar `<h1>` único.
- [ ] Utilizar headings em ordem lógica.
- [ ] Usar HTML semântico.
- [ ] Adicionar `alt` nas imagens relevantes.
- [ ] Definir idioma `pt-BR`.
- [ ] Criar conteúdo que mencione padaria artesanal e localização quando o cliente fornecer a cidade/bairro.

**Estimativa:** 30 min.

---

# 17. ETAPA 13 — Performance

### P1

- [ ] Comprimir imagens.
- [ ] Utilizar formatos modernos quando apropriado.
- [ ] Definir dimensões das imagens para evitar layout shift.
- [ ] Evitar CSS desnecessário.
- [ ] Evitar bibliotecas sem necessidade.
- [ ] Verificar carregamento da página.
- [ ] Testar Lighthouse.

**Meta inicial:** buscar bons resultados em Performance, Accessibility, Best Practices e SEO sem sacrificar a experiência visual.

**Estimativa:** 1h.

---

# 18. ETAPA 14 — Testes

### P0 — Testes funcionais

- [ ] Todos os links funcionam.
- [ ] CTA do WhatsApp funciona.
- [ ] Instagram funciona.
- [ ] Facebook funciona.
- [ ] Âncoras funcionam.
- [ ] Não existem links quebrados.
- [ ] Imagens carregam.
- [ ] Não existem erros no console.

### P1 — Testes visuais

- [ ] Chrome desktop.
- [ ] Navegador mobile.
- [ ] Diferentes larguras de viewport.
- [ ] Zoom de 200%.
- [ ] Teste de orientação, quando aplicável.

**Estimativa:** 1h.

---

# 19. ETAPA 15 — Git e GitHub

## Estratégia de branches

```text
main
 └── feature/landing-page
```

Para funcionalidades maiores:

```text
main
 ├── feature/header
 ├── feature/hero
 ├── feature/products
 ├── feature/contact
 └── fix/responsive-layout
```

### Commits

Usar mensagens claras, por exemplo:

```text
feat: create landing page structure
feat: add hero section
feat: add featured products
feat: add WhatsApp CTA
style: improve responsive layout
fix: correct mobile card overflow
docs: update README
```

### Pull Request

- [ ] Criar branch de trabalho.
- [ ] Desenvolver funcionalidade.
- [ ] Fazer commits pequenos e relacionados.
- [ ] Revisar alterações.
- [ ] Fazer push.
- [ ] Abrir Pull Request para `main`.
- [ ] Descrever o que foi alterado.
- [ ] Registrar testes realizados.
- [ ] Revisar o próprio diff.
- [ ] Corrigir problemas encontrados.
- [ ] Fazer merge somente após a revisão.

---

# 20. Regras de Negócio

Mesmo sendo uma landing page estática, o projeto deve respeitar estas regras:

### RN01 — Identidade

A marca deve aparecer como **Pão & Cia**.

### RN02 — Slogan

O hero deve apresentar o conceito:

**"Pão fresquinho todos os dias"**

### RN03 — Produtos

A seção de destaque deve apresentar os quatro produtos definidos pelo cliente:

- Pão de fermentação natural.
- Croissant.
- Bolo de cenoura.
- Café especial.

### RN04 — Preços

Os preços exibidos devem ser fornecidos e aprovados pelo cliente. Não inventar preços na versão final.

### RN05 — Contato

O CTA deve direcionar para o WhatsApp oficial da padaria.

### RN06 — Redes sociais

Instagram e Facebook devem apontar para os perfis oficiais.

### RN07 — Informações

Endereço e horário devem refletir informações reais fornecidas pelo cliente.

### RN08 — Mobile

A página deve ser totalmente utilizável em dispositivos móveis.

### RN09 — Conteúdo

Informações comerciais importantes devem estar visíveis sem exigir interação complexa.

---

# 21. Critérios de Aceitação da V1

A V1 será considerada pronta quando:

- [ ] A página abre corretamente.
- [ ] O nome e slogan estão visíveis.
- [ ] O hero apresenta uma imagem adequada.
- [ ] Existe seção Sobre nós.
- [ ] Existem quatro produtos em destaque.
- [ ] Cada produto possui imagem, nome e preço.
- [ ] Horário está disponível.
- [ ] Endereço está disponível.
- [ ] CTA do WhatsApp funciona.
- [ ] Instagram funciona.
- [ ] Facebook funciona.
- [ ] Layout é responsivo.
- [ ] Não existe overflow horizontal.
- [ ] Imagens possuem tratamento adequado de acessibilidade.
- [ ] Navegação por teclado funciona.
- [ ] Não existem erros no console.
- [ ] SEO básico foi implementado.
- [ ] Página foi testada em mobile e desktop.
- [ ] Código foi revisado antes do merge.

---

# 22. Definition of Done

Uma tarefa só será considerada **Done** quando:

- [ ] A implementação foi concluída.
- [ ] O código está organizado.
- [ ] O comportamento esperado foi testado.
- [ ] Não há erros conhecidos relacionados à tarefa.
- [ ] O layout foi verificado em diferentes tamanhos.
- [ ] Acessibilidade foi considerada.
- [ ] O commit foi realizado com mensagem clara.
- [ ] O Pull Request foi revisado.
- [ ] Critérios de aceitação foram atendidos.

---

# 23. Riscos

| Risco | Impacto | Mitigação |
|---|---|---|
| Imagens muito pesadas | Alto | Otimizar/comprimir imagens |
| Layout ruim no celular | Alto | Desenvolver mobile-first |
| Contraste insuficiente | Médio | Testar acessibilidade |
| Informações comerciais incorretas | Alto | Validar conteúdo com cliente |
| WhatsApp configurado incorretamente | Alto | Testar link em dispositivo real |
| Excesso de elementos visuais | Médio | Priorizar simplicidade |
| Escopo crescer durante o projeto | Médio | Manter funcionalidades fora da V1 |

---

# 24. Decisões do Projeto

Registrar decisões importantes neste espaço.

| Data | Decisão | Motivo |
|---|---|---|
| — | Mobile-first | Público vindo principalmente do Instagram |
| — | HTML + CSS | Escopo inicial simples e objetivo |
| — | Paleta terrosa/quente | Alinhamento com identidade desejada |
| — | CTA para WhatsApp | Principal objetivo comercial da página |

---

# 25. Melhorias Futuras — V2+

Possíveis evoluções:

- [ ] Mapa/localização integrada.
- [ ] Galeria de fotos.
- [ ] Depoimentos de clientes.
- [ ] Cardápio completo.
- [ ] Formulário de contato.
- [ ] Botão fixo de WhatsApp no mobile.
- [ ] Página própria para cada produto.
- [ ] Blog.
- [ ] Integração com backend.
- [ ] Django para gerenciamento de produtos.
- [ ] Sistema de pedidos.
- [ ] Painel administrativo.
- [ ] Analytics.
- [ ] SEO local mais avançado.

---

# 26. Checklist Final

## Conteúdo

- [ ] Nome correto.
- [ ] Slogan correto.
- [ ] Texto Sobre nós aprovado.
- [ ] Produtos corretos.
- [ ] Preços corretos.
- [ ] Endereço correto.
- [ ] Horários corretos.
- [ ] WhatsApp correto.
- [ ] Redes sociais corretas.

## Design

- [ ] Identidade aconchegante.
- [ ] Cores terrosas/quentes.
- [ ] Tipografia consistente.
- [ ] Espaçamentos consistentes.
- [ ] Imagens de boa qualidade.
- [ ] CTA visualmente destacado.

## Responsividade

- [ ] Mobile.
- [ ] Tablet.
- [ ] Desktop.
- [ ] Sem overflow horizontal.
- [ ] Botões fáceis de tocar.

## Acessibilidade

- [ ] HTML semântico.
- [ ] Alt texts.
- [ ] Contraste.
- [ ] Foco visível.
- [ ] Navegação por teclado.

## Qualidade

- [ ] Console sem erros.
- [ ] Links testados.
- [ ] Lighthouse executado.
- [ ] Código revisado.
- [ ] Git organizado.
- [ ] Pull Request revisado.
- [ ] README atualizado.

---

# 27. Backlog Resumido

| ID | Tarefa | Prioridade | Estimativa | Dependência |
|---|---|---|---:|---|
| P01 | Planejamento de conteúdo | P0 | 1h | — |
| P02 | Identidade visual | P1 | 1h | P01 |
| P03 | Estrutura do projeto | P0 | 30min | — |
| P04 | Configuração HTML | P0 | 30min | P03 |
| P05 | Header | P0 | 1h | P04 |
| P06 | Hero | P0 | 1h30 | P02/P04 |
| P07 | Sobre nós | P1 | 45min | P04 |
| P08 | Produtos | P0 | 1h30 | P02/P04 |
| P09 | Informações | P0 | 45min | P04 |
| P10 | CTA WhatsApp | P0 | 30min | P01 |
| P11 | Footer | P1 | 30min | P10 |
| P12 | Responsividade | P0 | 1h30 | P05–P11 |
| P13 | Acessibilidade | P1 | 1h | P05–P11 |
| P14 | SEO | P1 | 30min | P04 |
| P15 | Performance | P1 | 1h | P12 |
| P16 | Testes | P0 | 1h | P12–P15 |
| P17 | Git/PR | P0 | contínuo | — |

**Estimativa aproximada de execução:** 12–14 horas, dependendo do nível de refinamento visual e da disponibilidade dos conteúdos reais.

---

# 28. Próximo Passo

Começar por **P01 — Planejamento de conteúdo**.

Depois seguir a ordem:

```text
Planejamento
    ↓
Estrutura HTML
    ↓
Header + Hero
    ↓
Sobre + Produtos
    ↓
Informações + CTA + Footer
    ↓
Responsividade
    ↓
Acessibilidade + SEO
    ↓
Performance
    ↓
Testes
    ↓
Pull Request
    ↓
Merge em main
```

O objetivo não é apenas "fazer a página funcionar", mas terminar com um pequeno projeto que demonstre organização, HTML semântico, CSS responsivo, atenção à acessibilidade, qualidade de código e um fluxo profissional de Git/GitHub.
