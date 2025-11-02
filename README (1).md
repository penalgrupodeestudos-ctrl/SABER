# 🎓 PROJETO SABER ELITE PRO

**Plataforma de Estudo Interativa para Concursos Públicos - Polícia Penal**

---

## ✨ DESTAQUES

- 🎓 **12 Disciplinas** - Organização completa
- 📚 **500+ Questões** - Banco extenso
- 🎮 **Simulados JSON** - Importar e compartilhar facilmente
- 📖 **Modo Professor** - Explicações detalhadas
- 👁️ **Modo Deus** - Visualizar todas as respostas
- 🔄 **GitHub Auto-Sync** - Simulados carregam automaticamente
- 📱 **100% Responsivo** - Mobile, Tablet, Desktop
- 💾 **LocalStorage** - Dados salvos no navegador
- ⚡ **Instantâneo** - Sem conexão com servidor necessária

---

## 🚀 COMEÇAR RAPIDAMENTE

### 1️⃣ Acessar a Plataforma

```
https://penalgrupodeestudos-ctrl.github.io/SABER
```

### 2️⃣ Usar o Conversor (Admin)

1. Clique em **⚙️ Admin**
2. Cole seu simulado (qualquer formato JSON)
3. Digite o **NOME** do simulado
4. Clique **🔄 CONVERTER**
5. Clique **💾 DOWNLOAD**

### 3️⃣ Upload no GitHub

1. Arquivo: `simulados-padrao.json`
2. GitHub → **Upload files**
3. Selecione o arquivo
4. **Commit changes**
5. ✅ **PRONTO!**

### 4️⃣ Todos Veem (F5 para atualizar)

```
Qualquer aluno que abrir a página → F5
↓
Seus simulados carregam AUTOMATICAMENTE!
```

---

## 📋 AS 12 DISCIPLINAS

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

## 🎯 GUIA DE USO

### Para Estudar

#### 1. Banco de Questões
- Vá em **❓ Questões**
- Use a busca ou filtro por disciplina
- Clique **Ver Explicação** para ver o gabarito

#### 2. Simulados
- Vá em **🎮 Simulados**
- Clique **▶️ Começar** para fazer um simulado
- Veja as questões e gabaritos

#### 3. Modo Professor
- Vá em **🎓 Professor**
- Clique **📚 Carregar**
- Veja todas com explicações

#### 4. Modo Deus
- Vá em **⚡ Deus**
- Clique **👁️ Revelar Tudo**
- Veja todas as respostas de uma vez

### Para Administrador

#### Converter Simulado
1. Vá em **⚙️ Admin**
2. Cole seu simulado (qualquer formato JSON)
3. Digite um NOME
4. Clique **🔄 CONVERTER**
5. Clique **💾 DOWNLOAD**
6. Upload no GitHub

#### Upload no GitHub
1. GitHub → **Upload files**
2. Selecione: `simulados-padrao.json`
3. Clique **Commit changes**
4. ✅ Simulado ativo para TODOS!

---

## 📤 FORMATOS DE JSON ACEITOS

O sistema aceita múltiplos formatos:

### Formato 1: Array Simples
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

### Formato 2: Com "questoes"
```json
{
  "questoes": [
    { ... },
    { ... }
  ]
}
```

### Formato 3: Com "simulados"
```json
{
  "simulados": [
    {
      "questoes": [ ... ]
    }
  ]
}
```

### Formato 4: Com "questions" ou "items"
```json
{
  "questions": [ ... ]
}
```

**✅ Qualquer combinação funciona!**

---

## 📋 ESTRUTURA DE CADA QUESTÃO

```json
{
  "numero": 1,                    // Número sequencial
  "disciplina": "Direito Penal",  // Uma das 12 disciplinas
  "questao": "Texto da pergunta", // Pergunta completa
  "opcoes": {
    "A": "Opção A",
    "B": "Opção B",
    "C": "Opção C",
    "D": "Opção D"
  },
  "resposta_correta": "A",        // Letra da resposta
  "explicacao_professor": "..."   // Explicação detalhada
}
```

### Disciplinas Aceitas

Use **EXATAMENTE** um destes nomes:

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

---

## 💻 INSTALAÇÃO LOCAL

### Opção 1: Usar Localmente (Mais Fácil)

1. Baixe o arquivo `index.html`
2. Clique duplo
3. Pronto! Abre no navegador

### Opção 2: GitHub Pages (Recomendado)

1. Crie repositório no GitHub
2. Upload `index.html`
3. Upload `simulados-padrao.json`
4. Ative GitHub Pages (Settings → Pages)
5. Acesse via: `seu-usuario.github.io/seu-repo`

### Opção 3: Servidor Web

1. Upload via FTP para seu servidor
2. Configure seu domínio
3. Acesse via seu domínio

---

## 🎮 COMO ADICIONAR SIMULADOS

### Passo a Passo Completo

#### 1. Prepare seu simulado em JSON
```json
[
  {
    "numero": 1,
    "disciplina": "Direito Penal",
    "questao": "Pergunta aqui?",
    "opcoes": {
      "A": "Resposta A",
      "B": "Resposta B",
      "C": "Resposta C",
      "D": "Resposta D"
    },
    "resposta_correta": "A",
    "explicacao_professor": "Explicação aqui"
  }
]
```

#### 2. Acesse a Plataforma
```
https://penalgrupodeestudos-ctrl.github.io/SABER
```

#### 3. Use o Conversor
- ⚙️ **Admin**
- Cole o JSON
- Digite o NOME
- Clique **🔄 CONVERTER**

#### 4. Download
- Clique **💾 DOWNLOAD**
- Arquivo: `simulados-padrao.json`

#### 5. Upload no GitHub
- GitHub → **Upload files**
- Selecione o arquivo
- **Commit changes**

#### 6. Atualizar Navegador
- Alunos fazem **F5** (ou Ctrl+F5)
- ✅ Simulado aparece!

---

## 📊 FLUXO VISUAL

```
Você cria simulado
        ↓
Converte via Admin
        ↓
Download: simulados-padrao.json
        ↓
GitHub Upload
        ↓
Alunos fazem F5
        ↓
✅ TODOS VEEM!
```

---

## 🔄 GITHUB AUTO-SYNC

### Como Funciona

1. **Plataforma lê automaticamente** do GitHub
2. **Arquivo**: `simulados-padrao.json`
3. **URL padrão**: 
   ```
   https://raw.githubusercontent.com/penalgrupodeestudos-ctrl/SABER/main/simulados-padrao.json
   ```

### Atualizações em Tempo Real

- Quando você faz upload de um novo `simulados-padrao.json`
- Os alunos fazem **F5** (atualizar página)
- ✅ Novos simulados aparecem automaticamente!

---

## 🎯 FUNCIONALIDADES

### Para Alunos (Sem Autenticação)

✅ **Banco de Questões**
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

---

## 🐛 TROUBLESHOOTING

### ❌ "JSON inválido"

**Solução:**
- Verifique se o JSON está bem formatado
- Use um validador: [JSONLint](https://jsonlint.com)
- Confirme se as disciplinas estão exatas

### ❌ "Simulados não aparecem"

**Solução:**
- Faça **F5** para atualizar
- Verifique se arquivo está no GitHub
- Confirme nome: `simulados-padrao.json`

### ❌ "Página sem estilo"

**Solução:**
- Limpe cache: **Ctrl+Shift+Delete**
- Tente **Ctrl+F5**
- Tente outro navegador

### ❌ "Dados desapareceram"

**Solução:**
- Dados salvos em **LocalStorage**
- Limpe cache com cuidado
- Reimporte os dados

---

## 📝 EXEMPLO COMPLETO

### Simulado Pronto para Upload

```json
[
  {
    "numero": 1,
    "disciplina": "Direito Penal",
    "questao": "Qual é o conceito de crime segundo o Código Penal?",
    "opcoes": {
      "A": "Ação ou omissão típica, ilícita e culpável",
      "B": "Qualquer ação proibida por lei",
      "C": "Comportamento contrário à moral",
      "D": "Qualquer ato ilegal"
    },
    "resposta_correta": "A",
    "explicacao_professor": "Crime é a ação ou omissão típica, ilícita e culpável que viola norma do Direito Penal. A tipicidade é essencial."
  },
  {
    "numero": 2,
    "disciplina": "Processo Penal",
    "questao": "Quem tem o poder de iniciar uma ação penal pública?",
    "opcoes": {
      "A": "Qualquer cidadão",
      "B": "O Ministério Público",
      "C": "A polícia",
      "D": "A vítima"
    },
    "resposta_correta": "B",
    "explicacao_professor": "Nas ações penais públicas, o Ministério Público é o titular exclusivo da ação penal pública."
  }
]
```

---

## 💡 DICAS PROFISSIONAIS

✅ Faça backup regularmente  
✅ Use nomes claros nas disciplinas  
✅ Mantenha explicações detalhadas  
✅ Organize bem as questões  
✅ Teste os simulados antes de compartilhar  
✅ Atualize regularmente com novas questões  

---

## 📱 COMPATIBILIDADE

- ✅ **Chrome** (Recomendado)
- ✅ **Firefox**
- ✅ **Safari**
- ✅ **Edge**
- ✅ **Mobile Browsers**

**Versão:** Todos os navegadores modernos (2020+)

---

## 🔐 SEGURANÇA

- ✅ Dados armazenados localmente no navegador
- ✅ Sem conexão com servidor externo
- ✅ Sem cookies de rastreamento
- ✅ Privacidade garantida
- ✅ Sem registro de informações pessoais

---

## 📞 SUPORTE

Para dúvidas:

1. Verifique este **README** completo
2. Teste o **JSON** em [JSONLint](https://jsonlint.com)
3. Confirme as **disciplinas** exatas
4. Tente **F5** (atualizar página)
5. Limpe **cache** do navegador

---

## 🎉 PRONTO PARA USAR!

Você tem um **sistema completo de questões** com:

✨ Interface moderna  
✨ 500+ questões  
✨ 12 disciplinas  
✨ GitHub Auto-Sync  
✨ Funcionalidades avançadas  
✨ 100% gratuito  

**Bom sucesso nos estudos! 🎓📚✨**

---

## 📊 STATUS

| Recurso | Status |
|---------|--------|
| **12 Disciplinas** | ✅ |
| **500+ Questões** | ✅ |
| **Modo Aluno** | ✅ |
| **Modo Professor** | ✅ |
| **Modo Deus** | ✅ |
| **GitHub Auto-Sync** | ✅ |
| **Responsivo** | ✅ |
| **LocalStorage** | ✅ |
| **Sem Dependências** | ✅ |
| **Production Ready** | ✅ |

---

## 📄 Informações Técnicas

- **Versão:** 2.1 GitHub Auto-Sync
- **Status:** Production Ready ✅
- **Licença:** MIT
- **Compatibilidade:** 99% dos navegadores
- **Performance:** Instantânea
- **Segurança:** Armazenamento local

---

## 🌟 VERSÃO ATUAL

**Projeto Saber Elite PRO v2.1**
- ✨ GitHub Auto-Sync
- ✨ Múltiplos formatos JSON
- ✨ Layout responsivo
- ✨ Sem erros de importação
- ✨ Pronto para produção

---

*Desenvolvido com ❤️ para estudantes de concursos públicos*

**Atualizado:** 02 de Novembro de 2025