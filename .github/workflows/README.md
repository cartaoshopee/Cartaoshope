# Site Cartão Shopee

Este é um site idêntico e funcional baseado nas imagens fornecidas do processo de solicitação do Cartão Shopee.

## Características

- **Design fiel**: Reproduz exatamente o visual das imagens originais
- **Totalmente funcional**: Navegação completa entre todas as páginas
- **Responsivo**: Compatível com desktop e mobile
- **Tecnologias modernas**: React, Tailwind CSS, Lucide Icons

## Páginas Implementadas

1. **Página Inicial** - Banner principal com informações do cartão e seção "Como funciona?"
2. **Preferências do Cartão** - Seleção de características importantes do cartão
3. **Formulário CPF** - Preenchimento e validação do CPF com máscara
4. **Processamento** - Página de loading com animação dos passos de análise
5. **Aprovação** - Confirmação da aprovação do cartão
6. **Método de Envio** - Seleção das opções de entrega do cartão

## Funcionalidades

- ✅ Navegação fluida entre páginas
- ✅ Validação de formulários
- ✅ Máscaras de entrada (CPF)
- ✅ Estados interativos (seleção de opções)
- ✅ Animações de loading
- ✅ Navegação automática temporizada
- ✅ Design responsivo
- ✅ Feedback visual para interações

## Como executar

1. Navegue até o diretório do projeto:
   ```bash
   cd shopee-card-site
   ```

2. Instale as dependências (se necessário):
   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```

4. Acesse no navegador:
   ```
   http://localhost:5173
   ```

## Estrutura do Projeto

```
shopee-card-site/
├── src/
│   ├── pages/           # Páginas da aplicação
│   │   ├── Home.jsx
│   │   ├── CardPreferences.jsx
│   │   ├── CpfForm.jsx
│   │   ├── ProcessingPage.jsx
│   │   ├── CardApproval.jsx
│   │   └── ShippingMethod.jsx
│   ├── components/      # Componentes reutilizáveis
│   ├── App.jsx         # Componente principal com roteamento
│   └── App.css         # Estilos globais
├── public/             # Arquivos estáticos
└── package.json        # Dependências e scripts
```

## Tecnologias Utilizadas

- **React** - Biblioteca para interface de usuário
- **React Router** - Roteamento entre páginas
- **Tailwind CSS** - Framework de estilos
- **Lucide React** - Ícones
- **Vite** - Bundler e servidor de desenvolvimento

## Observações

- O site é uma reprodução fiel das imagens fornecidas
- Todas as funcionalidades de navegação estão implementadas
- O formulário de CPF inclui validação e máscara automática
- A página de processamento inclui animação temporal realística
- O fluxo completo funciona do início ao fim

