# 🚀 Landing Page - Bootstrap Componentes Interativos

![Status](https://img.shields.io/badge/Status-Finalizado-green)
![Bootstrap](https://img.shields.io/badge/Framework-Bootstrap_5-purple?logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/Code-HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/Style-CSS3-blue?logo=css3&logoColor=white)

> Uma aplicação prática focada na construção de interfaces dinâmicas e ricas, utilizando o ecossistema de componentes JavaScript do Bootstrap 5 para enriquecer a navegação.

## 🎯 Motivação e Propósito

Este projeto foi desenvolvido para consolidar o conhecimento sobre **Componentes de UI Interativos**. Enquanto projetos anteriores focavam na estrutura (Grid), o propósito aqui é resolver a necessidade de dinamismo na página sem a complexidade de escrever JavaScript puro.

O repositório demonstra a capacidade de implementar galerias rotativas, janelas de diálogo (pop-ups) e navegação responsiva complexa, utilizando as melhores práticas do framework mais utilizado no mercado.

## 🖼️ Demonstração Visual

## 🛠️ Tecnologias Utilizadas

A arquitetura do projeto baseia-se na eficiência de frameworks CSS:

* **[Bootstrap 5](https://getbootstrap.com/):** Core do projeto. Utilizado via CDN para:
    * **JS Components:** Lógica de Carrossel e Modais via *data-attributes*.
    * **Grid System:** Layout responsivo de colunas.
    * **Utilities:** Espaçamento, cores e tipografia.
* **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estrutura semântica.
* **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Customização (`main.css`) para identidade visual específica.

## ✨ Funcionalidades

O projeto conta com os seguintes recursos implementados:

* **Carrossel de Destaques:** Slider automático na seção principal (Hero) para rotação de banners promocionais.
* **Vitrine de Produtos:** Uso de **Cards** organizados em Grid, adaptando-se de 1 coluna (Mobile) para múltiplas colunas (Desktop).
* **Interatividade via Modal:** Botões de ação ("Comprar" ou "Saiba Mais") que acionam janelas modais sobrepostas para detalhes, sem recarregar a página.
* **Navegação Responsiva:** Barra de navegação (Navbar) que se converte automaticamente em menu "hambúrguer" (colapsável) em dispositivos móveis.
* **Formulários Estilizados:** Campos de input padronizados com validação visual do framework.

## 📦 Instalação e Configuração

Este é um projeto **Client-Side** estático. Não requer instalação de dependências via NPM se utilizado via CDN (configuração padrão).

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/DouglassenG/bootstrap_exercicio_13.git](https://github.com/DouglassenG/bootstrap_exercicio_13.git)
    ```

2.  **Acesse o diretório:**
    ```bash
    cd bootstrap_exercicio_13
    ```

3.  **Execução:**
    * Localize o arquivo `index.html`.
    * Dê um duplo clique para abrir no seu navegador padrão.
    * *Dica:* Para simular a experiência mobile, utilize o "Inspecionar Elemento" (F12) do navegador e ative a "Device Toolbar".

## 💻 Uso e Exemplos

O código destaca o uso de **Data Attributes** (`data-bs-*`), essenciais no Bootstrap 5 para ativar comportamentos JS diretamente no HTML.

**Exemplo de Gatilho de Modal:**
```html
<button class="btn btn-primary" data-bs-toggle="modal" data-
