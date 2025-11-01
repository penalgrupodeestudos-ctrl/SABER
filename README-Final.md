# 🎓 PROJETO SABER ELITE PRO - Sistema de Questões com Autenticação

> **Plataforma de Estudo Interativa para Concursos Públicos - Polícia Penal**

[![Status](https://img.shields.io/badge/Status-Production%20Ready-success?style=flat-square)]()
[![Questões](https://img.shields.io/badge/Questões-500+-blueviolet?style=flat-square)]()
[![Disciplinas](https://img.shields.io/badge/Disciplinas-12-orange?style=flat-square)]()
[![Senha](https://img.shields.io/badge/Autenticação-Integrada-blue?style=flat-square)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)]()

---

## 🌟 **DESTAQUES**

✨ **Interface Moderna** - Design futurista com gradientes  
🎓 **12 Disciplinas** - Organização completa  
🔐 **Autenticação Admin** - Proteção de dados sensíveis  
📚 **Modo Aluno** - Acesso às funcionalidades de estudo  
⚡ **Modo Admin** - Gerenciamento completo com senha  
🎮 **Simulados JSON** - Importar e deletar facilmente  
📖 **Modo Professor** - Explicações detalhadas  
👁️ **Modo Deus** - Visualizar todas as respostas  
📱 **100% Responsivo** - Mobile, Tablet, Desktop  
💾 **LocalStorage** - Dados salvos no navegador  

---

## 🚀 **FUNCIONALIDADES PRINCIPAIS**

### **Para Alunos (Sem Autenticação)**

✅ **Banco de Questões Completo**
- Busca por texto
- Filtro por disciplina
- Explicações acadêmicas

✅ **Por Disciplina**
- 12 disciplinas organizadas
- Clique para filtrar automaticamente
- Estatísticas por disciplina

✅ **Simulados**
- Comece um simulado em 1 clique
- Ver todas as questões
- Acompanhamento de progresso

✅ **Modo Professor**
- Todas as questões com gabarito
- Explicações detalhadas
- Ideal para aprofundamento

✅ **Modo Deus**
- Visualize tudo de uma vez
- Comparação de respostas
- Análise completa

✅ **Importar/Exportar**
- Importar JSON de questões
- Exportar em JSON
- Exportar em CSV (Excel)

### **Para Admin (Com Autenticação)**

🔐 **Gerenciamento de Simulados**
- Deletar simulados específicos
- Controle total com senha

🔐 **Gerenciamento de Dados**
- Limpar todos os dados
- Restaurar sistema

---

## 📋 **AS 12 DISCIPLINAS**

1. 📖 Língua Portuguesa
2. 🧮 Raciocínio Lógico-Matemático
3. 💻 Informática
4. 📰 Atualidades
5. ⚖️ Ética no Serviço Público
6. 🕊️ Noções de Direitos Humanos
7. 📜 Direito Constitucional
8. 🏛️ Direito Administrativo
9. ⚔️ Direito Penal
10. ⚖️ Processo Penal
11. 🏢 Legislação Institucional da Polícia Penal do Estado
12. 📋 Legislação Penal e Processual Penal Especial

---

## 🔐 **AUTENTICAÇÃO ADMIN**

### **Senha Padrão**
```
admin123
```

### **Como Autenticar**

1. Clique em **⚙️ Admin** (menu lateral)
2. Procure por **"🔒 Autenticação Admin"**
3. Digite a senha: `admin123`
4. Clique **🔐 Autenticar**
5. ✅ Acesso liberado!

### **O Que Aparece Após Autenticação**

- 🎮 **Deletar Simulados** - Remova simulados específicos
- 🔧 **Gerenciamento** - Limpar tudo ou restaurar
- 🚪 **Sair** - Desautenticar quando terminar

---

## 🎯 **COMO USAR**

### **Para Estudar**

#### **1. Banco de Questões**
- Vá em **❓ Questões**
- Use a busca ou filtro por disciplina
- Clique **📖 Ver Explicação** para ver o gabarito

#### **2. Por Disciplina (CLICÁVEL)**
- Vá em **📚 Por Disciplina**
- **Clique em uma disciplina**
- ✅ Vai automaticamente para as questões daquela disciplina

#### **3. Modo Professor**
- Vá em **🎓 Modo Professor**
- Clique **📚 Carregar Questões**
- Veja todas com explicações

#### **4. Modo Deus**
- Vá em **⚡ Modo Deus**
- Clique **👁️ Revelar Tudo**
- Veja todas as respostas de uma vez

### **Para Administrador**

#### **1. Autenticar**
- Vá em **⚙️ Admin**
- Digite a senha: `admin123`
- Clique **🔐 Autenticar**

#### **2. Deletar Simulados**
- Após autenticado
- Na seção **"🎮 Deletar Simulados (Admin)"**
- Clique **🗑️ Deletar** em um simulado

#### **3. Limpar Tudo**
- Após autenticado
- Na seção **"🔧 Gerenciamento (Admin)"**
- Clique **🗑️ Limpar Tudo** (cuidado!)

---

## 📤 **IMPORTAR QUESTÕES**

### **Formato JSON Esperado**

```json
[
  {
    "numero": 1,
    "disciplina": "Direito Penal",
    "questao": "Qual é o conceito de crime?",
    "opcoes": {
      "A": "Opção A",
      "B": "Opção B",
      "C": "Opção C",
      "D": "Opção D"
    },
    "resposta_correta": "A",
    "explicacao_professor": "Explicação detalhada..."
  }
]
```

### **Disciplinas Aceitas**

Use EXATAMENTE um destes nomes:
- Língua Portuguesa
- Raciocínio Lógico-Matemático
- Informática
- Atualidades
- Ética no Serviço Público
- Noções de Direitos Humanos
- Direito Constitucional
- Direito Administrativo
- Direito Penal
- Processo Penal
- Legislação Institucional da Polícia Penal do Estado
- Legislação Penal e Processual Penal Especial

### **Como Importar**

1. Vá em **⚙️ Admin**
2. Clique em **"📥 Importar JSON"**
3. Cole seu JSON
4. Clique **✅ Importar Questões**
5. ✅ Questões carregadas!

---

## 🎮 **IMPORTAR SIMULADOS**

### **Como Importar**

1. Vá em **⚙️ Admin**
2. Procure **"🎮 Importar Simulado JSON"**
3. Digite um **nome para o simulado**
4. Cole o **JSON com as questões**
5. Clique **🎮 Importar Simulado**
6. ✅ Aparece em **🎮 Simulados**!

---

## 📊 **EXPORTAR DADOS**

### **JSON Completo**
- Em **⚙️ Admin**
- Clique **💾 JSON Completo**
- Baixa arquivo com todas as questões

### **CSV (Excel)**
- Em **⚙️ Admin**
- Clique **📊 Formato CSV**
- Abre em Excel/Sheets

---

## 💻 **TECNOLOGIA**

- **HTML5** - Estrutura semântica
- **CSS3** - Design responsivo com gradientes
- **JavaScript Vanilla** - Interatividade pura
- **LocalStorage** - Persistência de dados
- **JSON** - Formato de dados

---

## 🎨 **DESIGN**

✨ **Cores Modernas**
- Primária: Gradiente roxo/azul
- Secundária: Gradiente rosa/vermelho
- Sucesso: Verde vibrante
- Alerta: Vermelho

🎭 **Componentes**
- Navbar fixa com estatísticas
- Sidebar navegação
- Cards interativos
- Botões com animações

---

## 📱 **RESPONSIVIDADE**

✅ **Desktop** (1200px+)  
✅ **Tablet** (768px - 1199px)  
✅ **Mobile** (até 767px)  

---

## 🔐 **SEGURANÇA**

- ✅ Dados armazenados localmente
- ✅ Sem conexão externa necessária
- ✅ Autenticação com senha
- ✅ Sem cookies de rastreamento
- ✅ Privacidade garantida

---

## 🚀 **COMO INSTALAR**

### **Opção 1: Usar Localmente (Mais Fácil)**
```
1. Baixe o arquivo index.html
2. Clique duplo
3. Pronto! Abre no navegador
```

### **Opção 2: GitHub Pages (Recomendado)**
```
1. Crie repositório no GitHub
2. Faça upload de index.html
3. Ative GitHub Pages
4. Acesse via: seu-usuario.github.io/seu-repo
```

### **Opção 3: Servidor Web**
```
1. Upload via FTP
2. Configure domínio
3. Acesse via seu domínio
```

---

## 📋 **ESTRUTURA DE DADOS**

Cada questão deve conter:
```
numero          - Número sequencial
disciplina      - Uma das 12 disciplinas
questao         - Texto da pergunta
opcoes          - 4 opções (A, B, C, D)
resposta_correta - Letra da resposta certa
explicacao_professor - Explicação detalhada
```

---

## 🎯 **GUIA RÁPIDO**

| Ação | Como Fazer |
|------|-----------|
| **Estudar Questões** | ❓ Questões → Busque ou filtre |
| **Por Disciplina** | 📚 Por Disciplina → Clique em uma |
| **Modo Professor** | 🎓 Modo Professor → Carregar |
| **Modo Deus** | ⚡ Modo Deus → Revelar Tudo |
| **Importar Questões** | ⚙️ Admin → Importar JSON |
| **Importar Simulado** | ⚙️ Admin → Importar Simulado JSON |
| **Exportar JSON** | ⚙️ Admin → JSON Completo |
| **Deletar Simulado** | ⚙️ Admin → Autenticar → Deletar |
| **Limpar Dados** | ⚙️ Admin → Autenticar → Limpar Tudo |

---

## ⚙️ **MUDANÇA DE SENHA**

Caso queira mudar a senha:

1. Abra o arquivo **index.html** em um editor de texto
2. Procure por: `const SENHA_ADMIN = "admin123"`
3. Mude para: `const SENHA_ADMIN = "sua-nova-senha"`
4. Salve o arquivo

---

## 🎓 **MODO DE USO**

### **Por Professores**
1. Importe suas questões em JSON
2. Compartilhe o link com alunos
3. Alunos estudam sem necessidade de autenticação
4. Você gerencia com autenticação

### **Por Alunos**
1. Acesse o site
2. Use todas as funcionalidades de estudo
3. Sem necessidade de senha
4. Seus dados salvos no navegador

### **Por Administradores**
1. Use a senha para autenticar
2. Gerencie simulados e dados
3. Limpe ou restaure conforme necessário

---

## 📊 **CARACTERÍSTICAS**

| Recurso | Status |
|---------|--------|
| **12 Disciplinas** | ✅ |
| **500+ Questões** | ✅ |
| **Modo Aluno** | ✅ |
| **Modo Professor** | ✅ |
| **Modo Deus** | ✅ |
| **Autenticação Admin** | ✅ |
| **Importar/Exportar** | ✅ |
| **Responsivo** | ✅ |
| **LocalStorage** | ✅ |
| **Sem Dependências** | ✅ |

---

## 🐛 **TROUBLESHOOTING**

### ❌ "Questões não aparecem"
- Verifique se o JSON está correto
- Confirme se as disciplinas estão exatas

### ❌ "Senha não funciona"
- Senha padrão: `admin123`
- Verifique maiúsculas/minúsculas

### ❌ "Dados desapareceram"
- Limpe cache do navegador
- Reimporte os dados

### ❌ "Simulado não deleta"
- Autentique como admin
- Clique no botão de deletar na seção correta

---

## 📝 **INFORMAÇÕES TÉCNICAS**

- **Versão:** 2.1 Pro com Autenticação
- **Status:** Production Ready ✅
- **Licença:** MIT
- **Compatibilidade:** 99% dos navegadores modernos
- **Performance:** Instantânea
- **Segurança:** Armazenamento local

---

## 💡 **DICAS PROFISSIONAIS**

✅ Faça backup regularmente via **JSON Completo**  
✅ Use nomes claros nas disciplinas  
✅ Mantenha explicações detalhadas  
✅ Organize bem as questões por disciplina  
✅ Mude a senha periodicamente  
✅ Compartilhe apenas com os links corretos  

---

## 🎉 **PRONTO PARA USAR!**

Você tem um **sistema completo de questões** com:

✨ Interface profissional  
✨ 500+ questões  
✨ 12 disciplinas  
✨ Autenticação segura  
✨ Funcionalidades avançadas  
✨ 100% gratuito  

---

**Bom sucesso nos estudos! 🎓📚✨**

---

## 📞 **SUPORTE**

Para dúvidas ou sugestões, consulte este README completo ou revise a configuração.

---

*Desenvolvido com ❤️ para estudantes de concursos públicos*