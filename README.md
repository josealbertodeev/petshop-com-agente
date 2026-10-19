# Patinhas Pet Shop & Vet: landing page com agente de IA

Landing page para um pet shop e clínica veterinária fictícios, com um agente de IA que responde dúvidas dos visitantes em um chat flutuante. Feita com HTML, CSS e JavaScript puro, com o agente integrado via [GPTMaker](https://gptmaker.ai/).

**[Ver o projeto online](https://petshop-com-agente.vercel.app)**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![GPTMaker](https://img.shields.io/badge/GPTMaker-Agente_de_IA-blueviolet?style=for-the-badge)

<img src="https://github.com/user-attachments/assets/6f8804bd-39f7-4637-b928-679447e2ed8b" alt="Página inicial do pet shop" width="800">

## Agente de IA

O site tem um chat flutuante com um agente criado no GPTMaker, que responde perguntas sobre serviços, horários e atendimento do pet shop. O agente é configurado na plataforma e incorporado ao site com um script:

```html
<script async src="https://app.gptmaker.ai/widget/<ID-DO-AGENTE>/float.js"></script>
```

O carregamento é `async`, então o widget não atrasa a renderização da página.

## Seções

- **Hero** com chamada principal
- **Sobre nós** com galeria de fotos
- **Serviços** em cards
- **Diferenciais** e **vantagens**
- **Depoimentos**
- **FAQ** em acordeão
- **Contato** com endereço, telefones, e-mail e horários

## Interações em JavaScript

- **Menu mobile** que fecha ao clicar em um link, ao clicar fora ou com a tecla `Esc`. Enquanto o menu está aberto, a rolagem da página fica travada.
- **Rolagem suave** que desconta a altura do header fixo, para o título da seção não ficar escondido atrás dele.
- **Link ativo no menu** de acordo com a seção visível.
- **Header que encolhe** ao rolar a página.
- **FAQ em acordeão:** abrir uma pergunta fecha as outras.
- **Animação de entrada** dos cards com `IntersectionObserver`.

## Tecnologias

- HTML5
- CSS3 (Grid, Flexbox, custom properties, media queries)
- JavaScript puro (`IntersectionObserver`, eventos de scroll e teclado)
- GPTMaker (agente de IA)
- Google Fonts (Poppins e Fredoka)

## Como rodar localmente

```bash
git clone https://github.com/josealbertodeev/petshop-com-agente.git
cd petshop-com-agente
```

Abra o `index.html` no navegador ou use a extensão Live Server do VS Code.

## Estrutura

```
petshop-com-agente/
├── index.html
├── style.css
└── script.js
```

## Próximos passos

- Botão flutuante do WhatsApp com mensagem pré-preenchida
- Formulário de agendamento
- Imagens servidas localmente em WebP

## Aviso

O Patinhas Pet Shop & Vet, os depoimentos, o endereço e os contatos são fictícios. As fotos são do [Unsplash](https://unsplash.com).

## Autor

**José Alberto**: [LinkedIn](https://www.linkedin.com/in/josealbertofarias/) · [Portfólio](https://josealbertodeev.github.io/portfolio/)
