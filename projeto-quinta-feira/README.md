# IA Evolution - Site de Cursos de Inteligência Artificial

Este projeto é uma implementação completa do site da IA Evolution utilizando exclusivamente **Tailwind CSS** para estilização, seguindo o guia de trabalho especificado.

## ✨ Características Implementadas

### 🎨 Design e Estilização
- **Cor primária**: Verde (#29e361) configurada no tema personalizado do Tailwind
- **Tipografia**: Fonte Poppins importada do Google Fonts
- **Layout responsivo**: Adaptável para desktop, tablet e mobile
- **Efeitos visuais**: Sombras, transições suaves e estados de hover

### 📱 Componentes Principais

#### Header e Navegação
- Layout flexbox com logotipo e menu horizontal
- Menu responsivo (oculto em mobile com botão hamburger)
- Efeitos de hover nos links de navegação
- Header fixo no topo (sticky)

#### Seção Hero
- Design centralizado com título destacado
- Botão CTA (Call-to-Action) com estilo primário
- Fundo diferenciado para destaque

#### Cards dos Níveis de Curso
- **Iniciante**: Layout com imagem à direita
- **Intermediário**: Layout alternado (imagem à esquerda)
- **Avançado**: Layout com imagem à direita
- Cards com sombras, cantos arredondados e padding generoso
- Listas de características com ícones de check

#### Tabela de Comparação
- Cabeçalho com cor primária e texto branco
- Efeito zebra (linhas alternadas) para melhor legibilidade
- Hover effect nas linhas da tabela
- Totalmente responsiva com scroll horizontal em telas pequenas

#### Formulário de Contato
- Campos com estilos consistentes e bordas suaves
- Estados de foco destacados com cor primária
- Botão de envio com estilo matching ao CTA
- Validação HTML5 nos campos obrigatórios

### 🔧 Configuração Técnica

#### Tailwind CSS
- CDN oficial do Tailwind CSS
- Configuração personalizada para cores primárias
- Família de fontes personalizada (Poppins)

#### Responsividade
- Breakpoints utilizados: `sm:`, `md:`, `lg:`
- Grid system responsivo
- Menu mobile com botão hamburger
- Imagens responsivas com `max-w-full` e `h-auto`

## 📁 Estrutura do Projeto

```
projeto-quinta-feira/
├── index.html          # Arquivo principal com toda a estrutura
└── README.md          # Este arquivo de documentação
```

## 🚀 Como Usar

1. **Visualizar o Site**:
   - Abra o arquivo `index.html` em qualquer navegador moderno
   - O site carregará automaticamente o Tailwind CSS via CDN

2. **Desenvolvimento**:
   - Todas as classes Tailwind estão aplicadas diretamente no HTML
   - Nenhum arquivo CSS adicional é necessário
   - Modificações podem ser feitas editando as classes no HTML

## 🎯 Requisitos Atendidos

### ✅ Conformidade Tailwind
- ❌ Arquivo `style.css` removido/não utilizado
- ✅ 100% das estilizações usando classes utilitárias do Tailwind
- ✅ Configuração personalizada para cor primária (#29e361)

### ✅ Responsividade
- ✅ Navegação adaptável (menu mobile)
- ✅ Cards responsivos com grid system
- ✅ Tabela com scroll horizontal em telas pequenas
- ✅ Formulário totalmente responsivo

### ✅ Aparência Profissional
- ✅ Design moderno e limpo
- ✅ Esquema de cores consistente com verde #29e361
- ✅ Tipografia harmoniosa com Poppins
- ✅ Espaçamentos e proporções equilibradas

### ✅ Organização do Código
- ✅ HTML limpo e bem estruturado
- ✅ Classes Tailwind organizadas logicamente
- ✅ Comentários descritivos nas seções
- ✅ Sem duplicação desnecessária de código

## 🎨 Paleta de Cores Utilizada

- **Primary 50**: #f0fdf4 (Background muito claro)
- **Primary 100**: #dcfce7
- **Primary 200**: #bbf7d0
- **Primary 300**: #86efac
- **Primary 400**: #4ade80
- **Primary 500**: #29e361 (Cor principal)
- **Primary 600**: #16a34a (Hover states)
- **Primary 700**: #15803d
- **Primary 800**: #166534
- **Primary 900**: #14532d

## 📖 Seções do Site

1. **Header** - Navegação principal
2. **Hero** - Seção de apresentação com CTA
3. **Iniciante** - Curso nível básico
4. **Intermediário** - Curso nível intermediário  
5. **Avançado** - Curso nível avançado
6. **Comparação** - Tabela comparativa dos cursos
7. **Contato** - Formulário de contato
8. **Footer** - Rodapé com informações adicionais

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Framework CSS utilitário
- **Google Fonts** - Tipografia (Poppins)
- **SVG Icons** - Ícones vetoriais para melhor performance

## 📱 Compatibilidade

- ✅ Chrome, Firefox, Safari, Edge (versões modernas)
- ✅ Dispositivos móveis (iOS/Android)
- ✅ Tablets e desktops
- ✅ Acessibilidade básica implementada

---

**Desenvolvido seguindo as especificações do Guia de Trabalho: Migração para Tailwind CSS**