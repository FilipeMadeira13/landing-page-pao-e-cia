# Pão & Cia

Landing page da Pão & Cia, uma padaria artesanal criada para apresentar a marca, sua proposta e alguns dos principais produtos. A página também exibe endereço, horário de funcionamento e links para redes sociais.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

## Instalação

Este é um projeto estático e não possui dependências externas ou etapa de compilação.

1. Clone o repositório:

```bash
git clone https://github.com/FilipeMadeira13/landing-page-pao-e-cia.git
cd landing-page-pao-e-cia
```

2. Abra o arquivo `index.html` no navegador.

Para uma experiência de desenvolvimento mais próxima de um ambiente real, sirva a pasta com qualquer servidor HTTP local. Por exemplo, usando o Python instalado na máquina:

```bash
python -m http.server 8000
```

Depois, acesse <http://localhost:8000> no navegador.

## Uso

A página pode ser usada como apresentação institucional da padaria, com:

- Identidade visual e mensagem principal da Pão & Cia;
- Seção institucional sobre a padaria;
- Catálogo visual com pão de fermentação natural, croissant artesanal e bolo de banana com canela;
- Endereço e horários de funcionamento;
- Ícones de WhatsApp, Instagram e Facebook.

Para editar o conteúdo, altere o HTML em `index.html`. Para personalizar cores, tipografia, espaçamentos e layout, edite `css/style.css`.

## Estrutura do projeto

```text
landing-page-padaria-artesanal/
├── index.html                 # Página principal
├── css/
│   └── style.css              # Estilos e layout da landing page
├── assets/
│   ├── icons/                 # Ícones das redes sociais
│   │   ├── facebook.png
│   │   ├── instagram.png
│   │   └── whatsapp.png
│   └── images/                # Logo e imagens dos produtos
│       ├── bolo-banana-canela.jpg
│       ├── croissant-artesanal.jpg
│       ├── logo.svg
│       └── pao-artesanal.jpg
└── fonts/                     # Fontes locais usadas no projeto
    ├── Caveat-Bold.ttf
    ├── Lora-Bold.ttf
    └── Lora-Regular.ttf
```

## Como contribuir

1. Faça um fork do projeto.
2. Crie uma branch para sua alteração:

```bash
git checkout -b feature/minha-alteracao
```

3. Faça as mudanças e valide a página em um navegador desktop e em uma viewport mobile.
4. Confira se os caminhos para imagens, ícones e fontes continuam funcionando.
5. Faça o commit e abra um pull request descrevendo o que foi alterado.

Mantenha o projeto simples, preserve a identidade visual existente e evite adicionar dependências sem necessidade.
