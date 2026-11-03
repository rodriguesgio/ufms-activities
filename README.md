# Alimenta — Sistema de Gerenciamento de Doações de Alimentos

Aplicação web acadêmica para demonstrar o registro de doações, acompanhamento de estoque e visualização de instituições beneficiárias.

## Tecnologias
- React
- Vite
- JavaScript (ES Modules)
- HTML5 semântico
- CSS3 responsivo
- Lucide React (ícones)
- LocalStorage (persistência local demonstrativa)

## Requisitos
- Node.js 20.19+ ou 22.12+
- npm

## Como executar
```bash
npm install
npm run dev
```
Acesse o endereço informado pelo Vite (normalmente `http://localhost:5173`).

## Como gerar a versão de produção
```bash
npm run build
npm run preview
```
Os arquivos compilados serão gerados na pasta `dist/`.

## Funcionalidades implementadas
- Painel com indicadores de doações, alimentos recebidos, distribuições e alertas.
- Registro de novas doações por formulário.
- Atualização automática do estoque quando uma doação é registrada.
- Pesquisa de doações por doador, alimento ou status.
- Alteração de status: Recebida, Em triagem e Distribuída.
- Exclusão de registros de doação.
- Exportação da listagem de doações em CSV.
- Visualização de estoque e alerta de itens abaixo do mínimo.
- Consulta de instituições beneficiárias fictícias.
- Persistência local dos registros por meio de LocalStorage.
- Layout responsivo para desktop, tablet e celular.

## Estrutura
```text
sistema-doacoes-alimentos/
├── index.html
├── package.json
├── README.md
└── src/
    ├── main.jsx
    └── styles.css
```

## Decisões e limitações
O React foi escolhido para organizar a interface em componentes e controlar atualizações de estado. O Vite foi adotado como ferramenta de desenvolvimento e build. O LocalStorage permite demonstrar persistência sem configurar um servidor ou banco de dados. Os dados iniciais são fictícios; o protótipo não deve ser usado para operação real nem para armazenar dados pessoais. Uma evolução futura pode incluir autenticação, API, banco de dados, controle de validade/lotes e trilha de auditoria.

## Publicação no GitHub
Crie um repositório público com o nome `sistema-doacoes-alimentos` e envie os arquivos desta pasta. Depois, substitua no relatório o endereço de exemplo pelo link real do repositório.
