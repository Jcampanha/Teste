# Website de Portfólio de Bailarina

Um website de portfólio moderno e responsivo projetado especificamente para bailarinas e coreógrafas profissionais. Este website apresenta apresentações de dança, habilidades e fornece uma presença online profissional.

## Features

### 🎨 Design
- **Moderno & Elegante**: Design limpo e profissional com gradientes e animações bonitas
- **Responsivo**: Design totalmente responsivo que funciona em todos os dispositivos (desktop, tablet, mobile)
- **Animações Suaves**: Animações CSS e interações JavaScript para uma experiência envolvente
- **Tipografia**: Tipografia bonita usando Google Fonts (Playfair Display & Poppins)

### 📱 Seções
1. **Seção Hero**: Introdução chamativa com elementos animados
2. **Sobre**: Histórico profissional, habilidades e estatísticas
3. **Apresentações**: Mostra de apresentações de dança em destaque
4. **Galeria**: Portfólio visual de fotos/vídeos de dança
5. **Contato**: Formulário de contato e informações profissionais

### ⚡ Recursos Interativos
- **Navegação Mobile**: Menu hambúrguer para dispositivos móveis
- **Rolagem Suave**: Navegação suave entre seções
- **Validação de Formulário**: Formulário de contato com validação de email
- **Animações de Rolagem**: Elementos animam conforme entram na tela
- **Efeitos Hover**: Efeitos interativos de hover em cards e botões
- **Botão Voltar ao Topo**: Botão conveniente para retornar ao topo
- **Notificações**: Notificações de sucesso/erro para envios de formulário

### 🎭 Mostra de Apresentações
- Cards de apresentação com descrições
- Tags de estilos de dança
- Datas e locais das apresentações
- Efeitos hover e animações

## Estrutura de Arquivos

```
dancer-portfolio/
├── index.html          # Arquivo HTML principal
├── styles.css          # Estilos CSS e animações
├── script.js           # Funcionalidade JavaScript
└── README.md          # Esta documentação
```

## Personalização

### Informações Pessoais
Atualize o seguinte em `index.html`:
- Nome: "Elena Rodriguez" → Seu nome
- Email: "elena.rodriguez@email.com" → Seu email
- Telefone: "+1 (555) 123-4567" → Seu número de telefone
- Localização: "São Paulo, SP" → Sua localização
- Links de redes sociais na seção de contato

### Conteúdo
- **Seção Sobre**: Atualize a história pessoal e experiência
- **Estatísticas**: Modifique os números na seção de estatísticas
- **Apresentações**: Adicione seus próprios detalhes de apresentação
- **Habilidades**: Atualize as tags de estilos de dança
- **Galeria**: Substitua o texto placeholder por imagens reais

### Estilização
O website usa um esquema de cores moderno:
- Primária: `#e74c3c` (Vermelho)
- Secundária: `#f39c12` (Laranja)
- Destaque: `#667eea` para `#764ba2` (Gradiente roxo)
- Texto: `#2c3e50` (Azul-cinza escuro)

## Suporte de Navegadores

- ✅ Chrome (mais recente)
- ✅ Firefox (mais recente)
- ✅ Safari (mais recente)
- ✅ Edge (mais recente)
- ✅ Navegadores móveis

## Recursos de Performance

- **Carregamento Rápido**: CSS e JavaScript otimizados
- **SEO Amigável**: Estrutura HTML semântica
- **Acessibilidade**: Labels ARIA adequados e navegação por teclado
- **Cross-browser**: Compatível com todos os navegadores modernos

## Como Começar

1. **Baixe/Clone** os arquivos para sua máquina local
2. **Personalize** o conteúdo em `index.html` com suas informações
3. **Substitua** o conteúdo placeholder pelo seu conteúdo real
4. **Adicione Imagens**: Substitua os placeholders da galeria por fotos reais de dança
5. **Implante**: Faça upload para seu serviço de hospedagem web

## Adicionando Imagens Reais

Para adicionar imagens reais à galeria:

1. Substitua os placeholders da galeria em `index.html`:
```html
<div class="gallery-item">
    <img src="caminho/para/sua/imagem.jpg" alt="Apresentação de Dança">
</div>
```

2. Atualize o CSS para itens da galeria:
```css
.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 15px;
}
```

## Formulário de Contato

O formulário de contato inclui:
- Campo de nome
- Campo de email (com validação)
- Campo de assunto
- Campo de mensagem
- Validação de formulário e notificações de sucesso

**Nota**: O formulário atualmente mostra uma mensagem de sucesso mas não envia emails realmente. Para torná-lo funcional, você precisará:
1. Configurar um serviço backend (PHP, Node.js, etc.)
2. Configurar funcionalidade de envio de email
3. Atualizar o JavaScript para fazer requisições HTTP reais

## Licença

Este projeto é open source e disponível sob a Licença MIT.

## Suporte

Para dúvidas ou ajuda com personalização, sinta-se à vontade para entrar em contato!

---

**Criado com ❤️ para bailarinas e artistas do mundo todo**