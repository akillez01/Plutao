# Portfólio SB Tech Support

Um portfólio moderno e interativo desenvolvido com React, Three.js e Tailwind CSS.

## 🚀 Deploy para GitHub Pages

Este projeto está configurado para deploy automático no GitHub Pages com domínio personalizado.

### Configuração Inicial

1. **Configurar GitHub Pages:**

   - Vá para Settings > Pages no seu repositório
   - Em "Source", selecione "GitHub Actions"
   - O deploy será feito automaticamente a cada push na branch main

2. **Domínio Personalizado:**
   - O projeto está configurado para usar `sbtechsupport.com.br`
   - Configure seu DNS para apontar para o GitHub Pages
   - O arquivo CNAME será automaticamente incluído no deploy

### Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera a build de produção
- `npm run preview` - Visualiza a build local
- `npm run deploy` - Deploy manual (se necessário)

### Deploy Automático

O projeto usa GitHub Actions para deploy automático. A cada push na branch main:

1. Instala as dependências
2. Gera a build de produção
3. Faz o deploy para GitHub Pages
4. Inclui o arquivo CNAME para o domínio personalizado

### Tecnologias Utilizadas

- **React** - Biblioteca JavaScript para UI
- **Vite** - Ferramenta de build
- **Three.js** - Biblioteca 3D para JavaScript
- **Tailwind CSS** - Framework CSS
- **Framer Motion** - Biblioteca de animações
- **EmailJS** - Serviço de email

### Estrutura do Projeto

```
src/
├── components/     # Componentes React
├── constants/      # Dados e configurações
├── assets/         # Imagens e recursos
├── hoc/           # Higher Order Components
└── utils/         # Utilitários

public/
├── desktop_pc/    # Modelo 3D do computador
├── planet/        # Modelo 3D do planeta
├── icons/         # Ícones das tecnologias
└── CNAME          # Configuração do domínio
```

## 🔧 Desenvolvimento Local

1. Clone o repositório
2. Instale as dependências: `npm install`
3. Inicie o servidor: `npm run dev`
4. Acesse: `http://localhost:3000`

## 📦 Build de Produção

```bash
npm run build
```

Os arquivos serão gerados na pasta `dist/`

---

## 👋 SB Tech & Support

Somos à **SB Tech & Support**, uma empresa de tecnologia dedicada a oferecer soluções inovadoras para empresas e indivíduos que desejam otimizar suas operações, melhorar sua infraestrutura e se manter à frente no mercado competitivo.

### 🎯 Nossa missão

Somos uma empresa focada em atender nossos clientes com excelência, dedicando-nos a compreender e superar seus desafios e objetivos. Com expertise em redes de computador e segurança da informação, oferecemos soluções personalizadas e inovadoras.

### Nossos serviços

- **Suporte técnico de TI**: Diagnóstico e resolução de problemas em hardware, redes e sistemas operacionais
- **Gerenciamento de infraestrutura**: Configuração, monitoramento e manutenção de servidores, redes e dispositivos
- **Gerenciamento de Backup**: Soluções de backup e recuperação de dados
- **Soluções de Segurança**: Proteção avançada para ambientes tecnológicos
- **Desenvolvimento Web e aplicações**: Soluções sob medida utilizando tecnologias modernas
