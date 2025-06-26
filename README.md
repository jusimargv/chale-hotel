# 🏨 Chalé Hotel - Layout Responsivo

## 📋 Descrição

Este projeto apresenta um layout responsivo para um site de hotel chalé, desenvolvido com HTML5 e CSS3. O design combina elementos modernos com uma estética rústica e acolhedora, perfeita para representar um estabelecimento hoteleiro que valoriza o conforto e a natureza.

**🎯 Objetivo**: Criar um site profissional e acolhedor que transmita confiança e convide os visitantes a conhecerem os serviços do hotel.

## 🎨 Características do Design

### Layout Estrutural
- **Header com Logo**: Área superior com logo posicionado estrategicamente
- **Menu de Navegação**: Menu horizontal responsivo com links para diferentes seções
- **Área de Locais**: Seção destacando as localidades atendidas pelo hotel
- **Botão de Reserva**: Call-to-action proeminente para reservas
- **Menu Lateral**: Navegação vertical com links organizados
- **Conteúdo Principal**: Área dedicada ao conteúdo principal do site
- **Área Lateral**: Seção complementar com benefícios e informações adicionais
- **Rodapé**: Informações de contato e links importantes

### Elementos Visuais
- **Paleta de Cores**: Tons terrosos e dourados que remetem à natureza
- **Tipografia**: Fonte Helvetica para melhor legibilidade
- **Imagens de Fundo**: Elementos visuais que complementam o design
- **Efeitos Hover**: Interações suaves para melhor experiência do usuário
- **Sombras e Bordas**: Elementos que conferem profundidade ao layout

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com flexbox e grid
- **Design Responsivo**: Adaptação para diferentes tamanhos de tela
- **Acessibilidade**: Código otimizado para leitores de tela

## 📱 Responsividade

O layout foi desenvolvido pensando na experiência do usuário em diferentes dispositivos:
- **Desktop**: Layout completo com todas as funcionalidades
- **Tablet**: Adaptação para telas médias
- **Mobile**: Versão otimizada para smartphones

## 🎯 Funcionalidades

- Navegação intuitiva e organizada
- Sistema de reservas integrado
- Informações sobre localidades atendidas
- Apresentação de benefícios e diferenciais
- Design profissional e acolhedor

## 📸 Preview do Layout

![Layout do Chalé Hotel](./image/layout.png)

## 🚀 Como Utilizar

### 📥 Download e Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/jusimargv/chale-hotel.git
   cd chale-hotel
   ```

2. **Ou faça o download manual**:
   - Clique no botão "Code" → "Download ZIP"
   - Extraia o arquivo em uma pasta de sua preferência

### 🖥️ Executando o Projeto

1. **Método Simples**:
   - Navegue até a pasta do projeto
   - Dê duplo clique no arquivo `index.html`
   - O site abrirá em seu navegador padrão

2. **Usando um servidor local** (recomendado):
   ```bash
   # Se você tem Python instalado:
   python -m http.server 8000
   
   # Se você tem Node.js instalado:
   npx serve .
   
   # Se você tem PHP instalado:
   php -S localhost:8000
   ```

3. **Acesse no navegador**:
   - Abra: `http://localhost:8000`

## 📁 Estrutura do Projeto

```
chale_hotel/
├── index.html          # Página principal do site
├── css/
│   └── style.css       # Arquivo de estilos CSS
├── image/              # Pasta com todas as imagens
│   ├── apartamento.jpg
│   ├── bg-area-lateral.png
│   ├── bg-area-principal.png
│   ├── bg-container.png
│   ├── bg-linha.gif
│   ├── bg-rodape.png
│   ├── bg.png
│   ├── depoimento.png
│   ├── logo.png
│   ├── ornamento.png
│   ├── piscina.jpg
│   ├── restaurante.jpg
│   ├── topo-imagem-lateral.png
│   ├── topo-imagem-principal.png
│   └── topo-imagem-principal2.png
└── README.md           # Este arquivo
```

## 🔧 Personalização

### 🎨 Alterando Cores

Para personalizar as cores do site, edite o arquivo `css/style.css`:

```css
/* Cores principais do site */
:root {
    --cor-primaria: #dbcd87;      /* Dourado principal */
    --cor-secundaria: #7d7640;    /* Marrom escuro */
    --cor-texto: #615b2d;         /* Marrom para textos */
    --cor-fundo: #ede9cc;         /* Bege claro */
    --cor-hover: #f6f3d6;         /* Bege para hover */
}

/* Exemplo de uso */
#topo {
    background: var(--cor-primaria);
}
```

### 📝 Alterando Conteúdo

1. **Título do site** (`index.html` linha 15):
   ```html
   <title>Seu Nome do Hotel</title>
   ```

2. **Logo e nome** (`index.html` linha 25):
   ```html
   <a href="">Seu Nome do Hotel</a>
   ```

3. **Locais atendidos** (`index.html` linhas 33-37):
   ```html
   <a href="">Sua Cidade 1</a> 
   <a href="">Sua Cidade 2</a> 
   <a href="">Sua Cidade 3</a>
   ```

4. **Links do menu** (`index.html` linhas 47-51):
   ```html
   <li><a href="#">Início</a></li>
   <li><a href="#">Sobre</a></li>
   <li><a href="#">Serviços</a></li>
   <li><a href="#">Galeria</a></li>
   <li><a href="#">Contato</a></li>
   ```

### 🖼️ Alterando Imagens

1. **Logo** (`image/logo.png`):
   - Substitua por sua logo
   - Mantenha proporções similares (aproximadamente 151x66px)
   - Formato PNG com fundo transparente

2. **Imagens de fundo**:
   - `bg.png`: Fundo geral do site
   - `bg-container.png`: Fundo do container principal
   - `bg-area-principal.png`: Fundo da área principal
   - `bg-area-lateral.png`: Fundo da área lateral
   - `bg-rodape.png`: Fundo do rodapé

3. **Imagens de conteúdo**:
   - `apartamento.jpg`: Foto dos apartamentos
   - `restaurante.jpg`: Foto do restaurante
   - `piscina.jpg`: Foto da piscina
   - `depoimento.png`: Imagem decorativa de depoimento

### 📱 Ajustando Responsividade

Para melhorar a responsividade, adicione media queries no `css/style.css`:

```css
/* Para tablets */
@media (max-width: 768px) {
    #area-principal,
    #area-lateral {
        width: 100%;
        float: none;
    }
    
    #topo {
        height: auto;
        min-height: 200px;
    }
}

/* Para smartphones */
@media (max-width: 480px) {
    #container {
        min-width: auto;
        margin: 0;
    }
    
    #area-menu {
        width: 100%;
        position: relative;
    }
}
```

## 🎨 Paleta de Cores Utilizada

| Cor | Código Hex | Uso |
|-----|------------|-----|
| Dourado Principal | `#dbcd87` | Header, botões |
| Marrom Escuro | `#7d7640` | Textos principais |
| Marrom Claro | `#615b2d` | Títulos |
| Bege Claro | `#ede9cc` | Fundo do container |
| Bege Hover | `#f6f3d6` | Efeitos hover |
| Dourado Reserva | `#a29750` | Botão de reserva |
| Dourado Hover | `#c2aa0e` | Hover do botão |

## 📋 Checklist de Personalização

- [ ] Alterar título da página
- [ ] Substituir logo
- [ ] Atualizar nome do hotel
- [ ] Modificar locais atendidos
- [ ] Personalizar links do menu
- [ ] Substituir imagens de conteúdo
- [ ] Ajustar cores conforme sua marca
- [ ] Atualizar informações de contato
- [ ] Testar responsividade
- [ ] Verificar links funcionando

## 🔍 Dicas de SEO

1. **Meta tags importantes** (já incluídas):
   ```html
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Chalé Hotel - Seu Refúgio na Natureza</title>
   ```

2. **Adicione meta description**:
   ```html
   <meta name="description" content="Descubra o conforto e a beleza do nosso chalé hotel. Reserve sua estadia e aproveite momentos inesquecíveis.">
   ```

3. **Otimize imagens**:
   - Use nomes descritivos para arquivos
   - Adicione atributo `alt` em todas as imagens
   - Comprima imagens para melhor performance

## 🚀 Deploy

### GitHub Pages (Gratuito)
1. Faça upload do projeto para um repositório GitHub
2. Vá em Settings → Pages
3. Selecione a branch main
4. Seu site estará disponível em: `https://seu-usuario.github.io/nome-do-repo`

### Netlify (Gratuito)
1. Acesse netlify.com
2. Arraste a pasta do projeto
3. Seu site será publicado automaticamente

### Vercel (Gratuito)
1. Acesse vercel.com
2. Conecte seu repositório GitHub
3. Deploy automático a cada commit

## 🐛 Solução de Problemas

### Imagens não aparecem
- Verifique se os caminhos estão corretos
- Confirme se as imagens estão na pasta `image/`
- Use caminhos relativos: `./image/nome-da-imagem.jpg`

### Layout quebrado
- Verifique se o arquivo CSS está sendo carregado
- Confirme se não há erros de sintaxe no CSS
- Teste em diferentes navegadores

### Menu não responsivo
- Adicione as media queries sugeridas
- Teste em diferentes tamanhos de tela
- Use as ferramentas de desenvolvedor do navegador

## 📞 Suporte e Contato

### Antes de perguntar, verifique:
1. Se seguiu todos os passos de instalação
2. Se os arquivos estão na estrutura correta
3. Se não há erros de digitação no código

### Como obter ajuda:
- **Issues do GitHub**: Abra uma issue no repositório
- **Email**: [seu-email@exemplo.com]
- **WhatsApp**: [seu-número]

## 📚 Recursos Adicionais

### Documentação Útil:
- [MDN Web Docs - HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
- [W3Schools - CSS Tutorial](https://www.w3schools.com/css/)

### Ferramentas Recomendadas:
- **Editor de código**: VS Code, Sublime Text, Atom
- **Navegadores para teste**: Chrome, Firefox, Safari, Edge
- **Ferramentas de desenvolvedor**: F12 em qualquer navegador
- **Compressor de imagens**: TinyPNG, ImageOptim

## 📄 Licença

Este projeto está sob a licença MIT. Você pode:
- ✅ Usar comercialmente
- ✅ Modificar
- ✅ Distribuir
- ✅ Usar privadamente
- ✅ Sublicenciar

**Apenas mantenha o aviso de copyright e a licença.**

## 🙏 Agradecimentos

- Comunidade de desenvolvedores web
- Tutoriais e documentações que inspiraram este projeto
- Todos que contribuíram com feedback e sugestões

---

## 🎉 Próximos Passos

Depois de personalizar o site, considere:

1. **Adicionar funcionalidades**:
   - Formulário de contato
   - Sistema de reservas real
   - Galeria de fotos
   - Blog de notícias

2. **Melhorar performance**:
   - Otimizar imagens
   - Minificar CSS
   - Usar CDN para recursos

3. **Implementar analytics**:
   - Google Analytics
   - Facebook Pixel
   - Hotjar para análise de comportamento

4. **Adicionar acessibilidade**:
   - Navegação por teclado
   - Contraste adequado
   - Textos alternativos

---

*Desenvolvido com ❤️ para proporcionar a melhor experiência digital para hóspedes e visitantes.*

**⭐ Se este projeto te ajudou, considere dar uma estrela no repositório!** 