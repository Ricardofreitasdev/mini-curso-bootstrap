# Mini Curso de Bootstrap

## Introdução HTML Simples

**Apresentação do Treinamento e Objetivos**
   - O que é o Bootstrap e por que utilizá-lo.
   - Principais funcionalidades e vantagens.

## Configuração e Estrutura Básica

**Instalação do Bootstrap**
   - CDN vs. instalação local.
   - Inclusão do Bootstrap em um projeto HTML.

**Estrutura Básica de um Documento HTML com Bootstrap**
   - Estrutura básica do HTML5.
   - Importação correta do CSS e JS do Bootstrap.

## Sistema de Linhas e Colunas

**Introdução ao Sistema de Linhas e Colunas**

Container padrão

   ```html
   <div class="container">
      seu conteúdo aqui
   </div>
   ```

Tipos de container

  ![container](./assets/container.png)

Container responsivo

```html
<div class="container-sm">pequeno</div>
<div class="container-md">médio</div>
<div class="container-lg">grande</div>
<div class="container-xl">extra grande</div>
<div class="container-xxl">extra extra grande</div>
```

container fluido

```html
<div class="container-fluid">
  ...
</div>
```

Linhas e Colunas

exemplo 1

```html
<div class="container text-center">
  <div class="row">
    <div class="col">
      1 of 2
    </div>
    <div class="col">
      2 of 2
    </div>
  </div>
  <div class="row">
    <div class="col">
      1 of 3
    </div>
    <div class="col">
      2 of 3
    </div>
    <div class="col">
      3 of 3
    </div>
  </div>
</div>
```

![alt text](/assets/linhas-e-colunas.png)

exemplo 2

```html
<div class="container text-center">
  <div class="row">
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
    <div class="col">col</div>
  </div>
  <div class="row">
    <div class="col-8">col-8</div>
    <div class="col-4">col-4</div>
  </div>
</div>
```

![linhas-e-colunas-2](/assets/linhas-e-colunas-2.png)

**Layout Responsivo**
   - Utilização de colunas e breakpoints.

**Margin e Padding**
   - Entendendo o uso dos espaçamentos.

**Tipografia**
   - Uso de fontes, títulos, parágrafos. [Documentação](https://getbootstrap.com/docs/5.0/utilities/text/)
   - Uso de cores. [Documentação](https://getbootstrap.com/docs/5.0/utilities/background/)

**Hands-on: Construção de Layout**
   - Exercício prático de construção de um layout utilizando o sistema de linhas e colunas.
     [Exemplo](https://getbootstrap.com/docs/5.3/examples/jumbotron/) (20 minutos)

## Componentes Básicos

**Componentes Comuns**
   - Botões, Navbars, Cards, Formulários, Badge.
  
**Criação de uma Página Completa**
   - Exercício prático: construção de uma página web utilizando os componentes aprendidos.
     [Exemplo](https://getbootstrap.com/docs/5.3/examples/checkout/)

## Avançado

**Componentes Interativos** 
   - Carousels, Modals, Tabs, Tooltip.
   - Introdução ao JavaScript do Bootstrap.

**Customização Avançada**
   - Utilização de Sass para customização.
   - Variáveis e temas.

**Hands-on: Desafio Final** 
   - [Desafio](https://696871.commercesuite.com.br/checkout/cart/gift-wraps?store_id=696871&session_id=0hs9vn9ah97vjps4uut8liksq3&id_items=4182)

## Conclusão

 **Resumo e Perguntas**
   - Recapitulação dos principais pontos abordados.
   - Sessão de perguntas e respostas.
