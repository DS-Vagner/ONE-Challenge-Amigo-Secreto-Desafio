# Amigo Secreto

![Static Badge](https://img.shields.io/badge/Amigo_Secreto_Em_Desenvolvimento-brightgreen)
![License Badge](https://img.shields.io/badge/License-MIT-blue)



## Lista de AMIGO SECRETO

### Amigo Secreto

Esta aplicação permite que os usuários adicionem os nomes de seus amigos em uma lista, e ao final, faça o sorteio de um amigo secreto de forma aleatória.

![Imagem de capa](assets/amigo-secreto.png)

---


<h2>📖 Descrição do projeto</h2>

O projeto **Amigo Secreto** foi desenvolvido para proporcionar aos usuários, uma experiência simples e divertida ao realizar o sorteios de amigo secreto de forma rápida e eficiente. Com esta aplicação, os usuários podem inserir seus nomes, visualizar a lista total de participantes e ao final realizar sortear um nome de forma totalmente aleatória.

Garantindo de quem informou o nome, não tire seu próprio nome

---

## 📊 Estado do Projeto

![Progresso](https://img.shields.io/badge/Progresso-100%25-green?style=for-the-badge&labelColor=000000&color=008000&logo=github)

Este projeto foi **concluido** mas poderá ser aprimorado constantemente. Funcionalidades adicionais podem ser implementadas nas próximas versões.

---

##  Autor
<h2>Vagner Marques</h2>

<p>Cientista de Dados</p>

<p>
  <a href="https://github.com/DS-Vagner" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
<a href="https://www.linkedin.com/in/vagner-marques/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

</p>


## Funcionalidades e Demonstração da Aplicação

## 📱 Funcionalidades

- **Adicionar Amigos**: O usuário pode adicionar nomes de amigos em um campo de texto.
- **Visualizar a Lista**: Os nomes dos amigos adicionados são exibidos em uma lista visível na tela.
- **Sortear Amigo Secreto**: O sistema sorteia aleatoriamente um amigo da lista e exibe o nome do "amigo secreto".

### Demonstração

1. **Adicionar amigos**: Digite o nome do amigo e clique no botão **Adicionar**.
2. **Sortear amigo secreto**: Após adicionar os amigos, clique no botão **Sortear amigo** para escolher aleatoriamente um nome da lista.

---


## 🚀 Tecnologias

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) **HTML5**: Linguagem de marcação para estruturar a página web.
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) **CSS3**: Para estilizar e criar o layout responsivo e atraente da aplicação.
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) **JavaScript**: Responsável por adicionar a funcionalidade interativa, como adicionar amigos à lista e realizar o sorteio aleatório.
- ![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google-fonts&logoColor=white) **Google Fonts**: Utilizado para as fontes personalizadas **Inter** e **Merriweather**, melhorando a estética e legibilidade do site.

## 🕹 Uso/Exemplos

#### Função de embaralhamento de array

```javascript
function embaralhaArray(arr) {
  for (let i = arr.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [arr[i], arr[j]] = [arr[j], arr[i]];
  }
}
```

#### Função de sorteio

```javascript
function sortear() {
  elemListaSorteio.innerHTML = "";

  embaralhaArray(amigos);
  for (i = 0; i < amigos.length; i++) {
    if (i == amigos.length - 1) {
      elemListaSorteio.innerHTML += `${amigos[i]} --> ${amigos[0]}<br>`;
    } else {
      elemListaSorteio.innerHTML += `${amigos[i]} --> ${amigos[i + 1]}<br>`;
    }
  }
}
```

## Acesso ao Projeto

Para acessar o projeto localmente, siga os passos abaixo:

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/amigo-secreto.git




MIT License

Copyright (c) [2025] [Vagner Marques]

Permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados, para usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software, e para permitir que as pessoas a quem o Software é fornecido o façam, sujeito às seguintes condições:

A notificação de copyright e esta permissão devem ser incluídas em todas as cópias ou partes substanciais do Software.

O Software é fornecido "como está", sem garantia de qualquer tipo, expressa ou implícita, incluindo, mas não se limitando a, garantias de comercialização, adequação a um propósito específico e não infração. Em nenhum caso os autores ou detentores dos direitos autorais serão responsáveis por qualquer reclamação, dano ou outra responsabilidade, seja em uma ação de contrato, ato ilícito ou outro, decorrente de ou em conexão com o Software ou o uso ou outros negócios no Software.


   

