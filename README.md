# 🌍 Hora Global

Uma aplicação web moderna e elegante que combina busca universal e relógios mundiais em tempo real, com design responsivo e tema dark mode.

## ✨ Funcionalidades

### 🔍 Busca Universal
- **Múltiplas plataformas**: Google, YouTube, X (Twitter), Instagram, TikTok, Pinterest, LinkedIn
- **Interface intuitiva**: Campo de busca único com dropdown de seleção de serviço
- **Busca inteligente**: Suporte a hashtags, usernames e consultas gerais
- **Atalhos de teclado**: `Ctrl + /` para foco rápido no campo de busca

### 🕐 Relógios Mundiais
- **9 cidades globais** com horários em tempo real:
  - Shanghai (GMT+8)
  - Nova Delhi (GMT+5:30)
  - Dubai (GMT+4)
  - Madrid (GMT+1)
  - Londres (GMT+0)
  - São Paulo (GMT-3)
  - Nova York (GMT-5)
  - Bogotá (GMT-5)
  - Cidade do México (GMT-6)

- **Atualização automática**: Horários e datas atualizados a cada segundo
- **Organização temporal**: Ordenados do fuso horário mais tarde ao mais cedo

### 🎨 Design e UX
- **Dark Mode**: Tema escuro elegante e moderno
- **Responsivo**: Adaptável a diferentes tamanhos de tela
- **Gradientes**: Backgrounds e elementos com gradientes suaves
- **Animações**: Hover effects e transições fluidas
- **Acessibilidade**: Alto contraste e legibilidade otimizada

## 🚀 Tecnologias

- **HTML5**: Estrutura semântica moderna
- **CSS3**: Estilos avançados com gradientes e animações
- **JavaScript ES6+**: Funcionalidades interativas e manipulação de tempo
- **Tailwind CSS**: Framework CSS utilitário (arquivos locais)
- **Responsive Design**: Grid e Flexbox para layouts adaptativos

## 📁 Estrutura do Projeto

```
hora-global/
├── assets/
│   ├── css/
│   │   └── tailwind.min.css    # Tailwind CSS local
│   └── js/
│       └── tailwind.min.js     # Tailwind JS local
├── dist/
│   └── tailwind.css            # CSS adicional
├── search.html                 # Página principal
└── README.md                   # Documentação
```

## 🛠️ Instalação e Uso

### Pré-requisitos
- Navegador web moderno
- Servidor web local (opcional, mas recomendado)

### Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu-usuario/hora-global.git
   cd hora-global
   ```

2. **Inicie um servidor local** (recomendado):
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   
   # PHP
   php -S localhost:8000
   ```

3. **Acesse a aplicação**:
   - Servidor: `http://localhost:8000/search.html`
   - Arquivo local: Abra `search.html` diretamente no navegador

## 🌐 Funcionalidades Detalhadas

### Busca Universal
A aplicação suporta diferentes tipos de busca dependendo da plataforma:

- **Google**: Busca geral
- **YouTube**: Busca por vídeos
- **X (Twitter)**: Busca por tweets e hashtags
- **Instagram**: Suporte a hashtags (#) e usernames (@)
- **TikTok**: Suporte a hashtags (#) e usernames (@)
- **Pinterest**: Busca por pins
- **LinkedIn**: Busca profissional

### Relógios Mundiais
- **Precisão**: Utiliza a API nativa `Intl.DateTimeFormat` do JavaScript
- **Fusos horários**: Configuração precisa com identificadores IANA
- **Formato**: Horário 24h e data no formato brasileiro (DD/MM/AAAA)
- **Performance**: Atualização otimizada sem impacto na performance

## 🎯 Casos de Uso

- **Profissionais globais**: Acompanhar horários de diferentes fusos
- **Pesquisadores**: Busca rápida em múltiplas plataformas
- **Social media**: Acesso direto a redes sociais
- **Estudantes**: Ferramenta de pesquisa e organização temporal
- **Viajantes**: Consulta de horários mundiais

## 🔧 Personalização

### Adicionar Nova Cidade
1. Adicione o elemento HTML no `clock-grid`
2. Configure o fuso horário no objeto `timeZones`
3. Mantenha a ordenação por GMT

### Modificar Serviços de Busca
1. Adicione nova opção no `<select>`
2. Implemente a lógica no `switch` da função `performSearch`

## 📱 Compatibilidade

- **Navegadores**: Chrome 60+, Firefox 55+, Safari 12+, Edge 79+
- **Dispositivos**: Desktop, tablet, mobile
- **Sistemas**: Windows, macOS, Linux, iOS, Android

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ para facilitar buscas e acompanhamento de horários globais.

## 🔄 Versões

- **v1.0.0**: Versão inicial com busca universal e relógios mundiais
- **v1.1.0**: Implementação do dark mode
- **v1.2.0**: Adição de novas capitais (Madrid, Nova Delhi, Cidade do México)
- **v1.3.0**: Reorganização temporal dos relógios

## 🚀 Roadmap

- [ ] Modo claro/escuro toggle
- [ ] Mais cidades e fusos horários
- [ ] Notificações de horários
- [ ] Exportação de horários
- [ ] PWA (Progressive Web App)
- [ ] API para integração externa

---

**Hora Global** - Conectando você ao mundo, um clique de cada vez! 🌍⏰