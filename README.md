Aqui está o arquivo **README.md** completo e sem cortes. Pode copiar e colar inteiramente no seu arquivo.

```markdown
# 📺 Catálogo de TVs (App)

> Projeto desenvolvido em 2022 como estudo de interfaces mobile e navegação.

Este é um aplicativo de comércio eletrônico desenvolvido em **React Native** com **Expo**, focado na exibição de um catálogo de televisores. O projeto demonstra a criação de interfaces ricas, uso de fontes personalizadas e navegação entre telas de listagem e detalhes de produtos.

## 📱 Funcionalidades

- **Home Page Interativa:**
  - Banner promocional em destaque.
  - Listagem horizontal de lançamentos e produtos mais relevantes.
  - Filtros visuais (interface).
- **Detalhes do Produto:**
  - Telas dedicadas para cada modelo de TV (LG, AOC, Philco, Samsung, Sony).
  - Exibição de preço, descrição técnica detalhada e botão de compra.
- **Navegação:**
  - Sistema de rotas utilizando **React Navigation** (Stack).
  - Cabeçalho personalizado com ícone de carrinho de compras.

## 🚀 Como rodar o projeto

Como este projeto utiliza uma versão do Expo de 2022 (SDK 44), siga estes passos estritos para evitar erros de compatibilidade:

### Pré-requisitos
- **Node.js** (Versão recomendada: 16 ou 18).
- **Git**.
- Celular com o app **Expo Go** instalado (Android ou iOS).

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/victorrgoms/catalogo-tvs.git](https://github.com/victorrgoms/catalogo-tvs.git)
   cd catalogo-tvs

```

2. **Instale as dependências:**
⚠️ **Importante:** Use a flag `--legacy-peer-deps` para resolver conflitos de versões antigas.
```bash
npm install --legacy-peer-deps

```


3. **Inicie o projeto:**
```bash
npx expo start

```


4. **Para visualizar:**
* O terminal exibirá um **QR Code**.
* Abra o app **Expo Go** no seu celular.
* Escaneie o QR Code para carregar o aplicativo.



## 🛠 Tecnologias Utilizadas

* **React Native** (0.64.3)
* **Expo SDK** (~44.0.0)
* **React Navigation** (v6)
* **Google Fonts** (Raleway)
* **Expo Vector Icons** (Feather e MaterialIcons).

## 📂 Estrutura do Projeto

```bash
src/
├── assets/          # Imagens dos produtos e banners
├── component/       # Componentes reutilizáveis
│   ├── Button/      # Botão de ação (Compra)
│   ├── ButtonWhat/  # Botão de chamada para ação
│   ├── Footer/      # Rodapé das telas
│   └── Tvs/         # Card de exibição do produto na Home
├── pages/           # Telas da aplicação
│   ├── Home/        # Tela principal
│   ├── Detail/      # Telas de detalhes (Detail, Detail2, etc.)
│   └── Description/ # Tela de descrição adicional
└── router.js        # Configuração das rotas e navegação

```

---

Feito por [Victor Gomes](https://www.google.com/search?q=https://github.com/victorrgoms)

```