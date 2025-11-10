# 🚀 Empreenda Fácil

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-2.0.0-green.svg)](https://github.com/seu-usuario/empreenda-facil)
[![HTML](https://img.shields.io/badge/HTML-5-orange.svg)](https://www.w3.org/html/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://www.javascript.com/)
[![Responsive](https://img.shields.io/badge/Responsive-100%25-brightgreen.svg)](https://github.com/seu-usuario/empreenda-facil)

> Sistema completo e gratuito para planejamento e abertura de empresas no Brasil 🇧🇷

## 📱 [Acessar Demo Online](https://seu-usuario.github.io/empreenda-facil/)

![Empreenda Fácil Screenshot](https://via.placeholder.com/800x400/667eea/ffffff?text=Empreenda+F%C3%A1cil)

## ✨ Características

- ✅ **100% Gratuito e Open Source**
- 📱 **Totalmente Responsivo** - Funciona em qualquer dispositivo
- 🚀 **Sem Necessidade de Servidor** - Roda direto no navegador
- 📊 **Gráficos Interativos** - Visualize seus custos em tempo real
- 📧 **Envio de Relatório por Email** - Receba o planejamento completo
- 💾 **Funciona Offline** - Após o primeiro carregamento
- 🔒 **Seguro** - Seus dados não são enviados para nenhum servidor

## 🎯 Funcionalidades

### 📝 Dados da Empresa
- Cadastro completo de informações
- Seleção de cidade com custos regionais
- Capital inicial e número de sócios

### 📋 Sistema de CNAEs
- **1.332 CNAEs** cadastrados
- Busca inteligente por palavras-chave
- CNAE principal + até 4 secundários
- Sugestões automáticas por ramo

### 👥 Gestão de Funcionários
- Cálculo automático de encargos trabalhistas
- CLT, PJ ou Autônomo
- INSS, FGTS, 13º salário, férias
- Folha de pagamento completa

### 💰 Cálculos de Custos
- **Custos de Abertura:**
  - Junta Comercial
  - Alvará de Funcionamento
  - Certificado Digital
  - Honorários Contábeis
  
- **Custos Operacionais:**
  - Aluguel
  - Energia/Água/Internet
  - Folha de Pagamento
  - Contador mensal

### 📊 Análises e Gráficos
- Gráfico de pizza com distribuição de custos
- Projeção de 6 meses
- Análise de viabilidade
- Ponto de equilíbrio

### 📄 Relatório Completo
- Resumo de todos os dados
- Envio por email
- Impressão otimizada
- Export para PDF (pelo navegador)

## 🚀 Como Usar

### Opção 1: Usar Online
Acesse: [https://seu-usuario.github.io/empreenda-facil/](https://seu-usuario.github.io/empreenda-facil/)

### Opção 2: Baixar e Usar Localmente
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/empreenda-facil.git

# Entre na pasta
cd empreenda-facil

# Abra o index.html no navegador
# No Windows:
start index.html

# No Mac:
open index.html

# No Linux:
xdg-open index.html
```

### Opção 3: Hospedar no Seu Servidor
1. Faça upload do `index.html` para seu servidor
2. Acesse pelo navegador
3. Pronto! Não precisa de PHP, MySQL ou configuração

## 📧 Configurar Envio de Email (Opcional)

O sistema usa [EmailJS](https://www.emailjs.com) para enviar relatórios por email.

### Passo a Passo:
1. Crie uma conta gratuita em [emailjs.com](https://www.emailjs.com)
2. Configure seu serviço de email (Gmail, Outlook, etc)
3. Crie um template
4. Adicione suas chaves no código:

```javascript
// Linha 2823 do index.html
emailjs.init("SUA_PUBLIC_KEY_AQUI");

// Linha 3715
emailjs.send('SEU_SERVICE_ID', 'SEU_TEMPLATE_ID', templateParams)
```

## 🎨 Personalização

### Mudar Cores Principais
```css
/* Linha 28 - Cor de fundo */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Suas cores personalizadas */
background: linear-gradient(135deg, #SUA_COR1 0%, #SUA_COR2 100%);
```

### Adicionar Nova Cidade
```javascript
// Linha 3245 - Adicione sua cidade
'sua_cidade': {
    junta: 500,
    alvara: 800, 
    certificado: 400,
    contador: 1200,
    aluguel: 1500,
    utilidades: 500
},
```

### Adicionar Novos CNAEs
```javascript
// Linha 2850 - Adicione novos CNAEs
{
    codigo: "00.00-0/00",
    descricao: "Descrição da atividade",
    palavras: "palavras chave para busca"
},
```

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilos e animações
- **JavaScript ES6** - Lógica e interatividade
- **Chart.js** - Gráficos interativos
- **EmailJS** - Envio de emails
- **GitHub Pages** - Hospedagem gratuita

## 📱 Compatibilidade

| Navegador | Versão | Status |
|-----------|--------|--------|
| Chrome | 90+ | ✅ Totalmente compatível |
| Firefox | 88+ | ✅ Totalmente compatível |
| Safari | 14+ | ✅ Totalmente compatível |
| Edge | 90+ | ✅ Totalmente compatível |
| Opera | 76+ | ✅ Totalmente compatível |
| Chrome Mobile | 90+ | ✅ Totalmente compatível |
| Safari iOS | 14+ | ✅ Totalmente compatível |

## 📊 Estatísticas do Projeto

- 📝 **1 arquivo HTML** (tudo em um!)
- 📏 **~4000 linhas** de código
- 🎯 **400+ CNAEs** cadastrados
- 🏙️ **12 cidades** com custos regionais
- 📊 **2 tipos** de gráficos
- ⚡ **< 200kb** tamanho total
- 🚀 **< 2s** tempo de carregamento

## 🤝 Como Contribuir

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Sugestões de Contribuição:
- 📋 Adicionar mais CNAEs
- 🏙️ Adicionar mais cidades
- 💰 Atualizar valores de custos
- 🌍 Traduzir para outros idiomas
- 📊 Adicionar novos tipos de gráficos
- 🎨 Criar temas de cores

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Seu Nome**
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [seu-perfil](https://linkedin.com/in/seu-perfil)

## 🙏 Agradecimentos

- [Chart.js](https://www.chartjs.org/) - Biblioteca de gráficos
- [EmailJS](https://www.emailjs.com/) - Serviço de email
- [GitHub Pages](https://pages.github.com/) - Hospedagem gratuita
- Comunidade open source brasileira 🇧🇷

## 📈 Roadmap

- [x] Sistema básico de cálculo
- [x] Interface responsiva
- [x] Gráficos interativos
- [x] Envio por email
- [ ] PWA - Instalar como app
- [ ] Modo offline completo
- [ ] Exportar para Excel
- [ ] API de CNAEs
- [ ] Integração com contadores
- [ ] Simulador de impostos

## 🐛 Problemas Conhecidos

- Em iOS Safari, o zoom pode ocorrer em alguns inputs (corrigido na v2.0)
- EmailJS tem limite de 200 emails/mês no plano gratuito

## 📞 Suporte

Encontrou um bug? Tem uma sugestão? 

- 🐛 [Abra uma issue](https://github.com/seu-usuario/empreenda-facil/issues)
- 💡 [Discussões](https://github.com/seu-usuario/empreenda-facil/discussions)
- 📧 Email: seu-email@exemplo.com

---

<div align="center">

**⭐ Se este projeto te ajudou, considere dar uma estrela!**

Feito com ❤️ para empreendedores brasileiros

[🔝 Voltar ao topo](#-empreenda-fácil)

</div>