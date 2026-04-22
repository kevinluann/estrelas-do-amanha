<div align="center">

<hr />

# Estrelas do Amanhã

<img width="1200" alt="estrelas-do-amanha-preview (1)" src="https://github.com/user-attachments/assets/dca16cce-9270-42f5-b3ea-d2b41a33ebb0" />

**Página única** de formulário de matrícula para escola de educação infantil, desenvolvida com HTML5 e CSS3.

<hr />

</div>

## 🎯 **Objetivo**

Projeto de estudo para praticar:
- HTML5 semântico
- CSS3 com variáveis customizadas
- CSS Nesting
- Flexbox e Grid para layouts
- Organização modular de arquivos CSS
- Formulários complexos e validação

## Estrutura da Página

- **Main** com formulário de matrícula completo e navegação
  - `div.main-container` com estrutura principal
  - `form` com múltiplos `fieldset` para organização dos dados
- **Aside** com logotipo e header
  - `header` com Ilustração SVG decorativa e mensagem convidativa

## Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e layout

## Estrutura do Projeto

```
estrelas-do-amanha/
|-- assets/
|   |-- icons/          # Ícones SVG
|   |-- Illustration.svg # Ilustração principal
|-- styles/
|   |-- fields/         # Estilos dos campos do formulário
|   |   |-- button.css
|   |   |-- checkbox.css
|   |   |-- droparea.css
|   |   |-- index.css
|   |   |-- input.css
|   |   |-- radio.css
|   |-- global.css      # Variáveis e estilos globais
|   |-- forms.css       # Estilos gerais do formulário
|   |-- layout.css      # Estrutura e posicionamento da página
|   `-- index.css       # Importação dos estilos
|-- index.html          # Página principal
`-- README.md          # Este arquivo
```

## ⚡ **Funcionalidades**

**Formulário completo de matrícula** com campos para:
  - **Informações da criança** (nome, data de nascimento, sexo, informações médicas)
  - **Upload de certidão de nascimento** com área drag-and-drop
  - **Endereço residencial**
  - **Informações do responsável** (nome, telefone, e-mail)
  - **Opções de matrícula** com turno de estudo e 6 esportes diferentes
  - **Aceitação de termos e condições**

## 📚 **Aprendizados**

Este projeto foi desenvolvido como parte dos estudos de **front-end**, focando em:

- **Boas práticas de organização**: Separação responsável dos arquivos CSS por componente
- **CSS Moderno**: Aplicação de recursos como nesting e variáveis customizadas
- **Semântica HTML5**: Uso correto das tags para melhor acessibilidade
- **Design System**: Consistência visual através de variáveis e padrões definidos
- **Formulários complexos**: Implementação de diversos tipos de campos
- **UX/UI**: Design intuitivo e acessível para pais e responsáveis
- **Estabilidade Visual**: Prevenção de layout shift para melhor experiência do usuário
- **CSS Grid Layout**: Layout com colunas proporcionais
