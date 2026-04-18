# React MarcaTempo

Uma aplicação web minimalista para adicionar e registrar nomes com timestamps automáticos.

## 📋 Sobre

**React MarcaTempo** é uma aplicação React construída para fins de estudo e demonstra conceitos importantes de desenvolvimento frontend como:
- Gerenciamento de estado com hooks (`useState`)
- Efeitos colaterais com `useEffect`
- Componentes reutilizáveis com TypeScript
- Requisições a APIs externas (exemplo: GitHub)

## ✨ Funcionalidades

- ✅ Adicionar nomes a uma lista
- ⏰ Timestamps automáticos (hora, minuto, segundo)
- 🎯 Interface simples e intuitiva
- 📝 Componentes reutilizáveis
- 🔷 Desenvolvida com TypeScript

## 🛠️ Tecnologias

- **React** 18.2.0
- **TypeScript** 4.9.3
- **Vite** 3.2.3
- **CSS3**

## 🚀 Como Usar

### Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/react-marcatempo.git

# Acesse o diretório
cd react-marcatempo

# Instale as dependências
npm install
```

### Desenvolvimento

```bash
# Inicie o servidor de desenvolvimento
npm run dev
```

O aplicativo estará disponível em `http://localhost:5173`

### Build

```bash
# Crie uma versão otimizada para produção
npm run build

# Visualize a build
npm run preview
```

## 📁 Estrutura do Projeto

```
src/
├── components/
│   └── Card/              # Componente que exibe cada registro de nome
│       ├── index.tsx
│       └── style.css
├── pages/
│   └── Home/              # Página principal com lógica da aplicação
│       ├── index.tsx
│       └── style.css
├── styles/
│   └── global.css         # Estilos globais
└── main.jsx               # Ponto de entrada da aplicação
```

## 💡 Conceitos Aprendidos

- **useState**: Gerenciar estado local do componente
- **useEffect**: Executar efeitos colaterais (como requisições API)
- **Props e TypeScript**: Passar dados tipados entre componentes
- **Componentes Funcionais**: Desenvolvimento moderno com React
- **Vite**: Build tool moderno e rápido

## 📝 Como Usar a Aplicação

1. Digite o nome no campo de entrada
2. Clique no botão para adicionar à lista
3. Cada nome será registrado com a hora exata da adição
4. Os nomes aparecem em cards com a informação do timestamp

## 📄 Licença

Este projeto é de código aberto e disponível sob a licença MIT.

---

**Desenvolvido para fins educacionais** 🚀
