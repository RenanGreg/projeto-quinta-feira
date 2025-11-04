# 📋 Instruções para Upload no GitHub

Como o Git não está instalado no sistema, siga estas instruções para fazer o upload do projeto para o seu GitHub:

## 🌐 Método 1: Upload via Interface Web do GitHub (Mais Fácil)

### 1️⃣ Criar Novo Repositório
1. Acesse: https://github.com/RenanGreg
2. Clique no botão verde **"New"** ou **"+"** → **"New repository"**
3. Nome do repositório: `ia-evolution-tailwind` ou `projeto-quinta-feira`
4. Descrição: `Site IA Evolution - Migração para Tailwind CSS`
5. Deixe como **Public** ou **Private** (sua escolha)
6. ✅ Marque **"Add a README file"**
7. Clique em **"Create repository"**

### 2️⃣ Fazer Upload dos Arquivos
1. No repositório criado, clique em **"uploading an existing file"** ou **"Add file" → "Upload files"**
2. Arraste ou selecione os arquivos:
   - `index.html`
   - `README.md`
3. Na parte inferior:
   - **Commit message**: `Adicionar site IA Evolution com Tailwind CSS`
   - **Description**: `Migração completa para Tailwind CSS conforme guia de trabalho`
4. Clique em **"Commit changes"**

## 💻 Método 2: Instalar Git e Usar Linha de Comando

### 1️⃣ Instalar Git
1. Baixe o Git: https://git-scm.com/download/win
2. Execute o instalador e siga as instruções padrão
3. Reinicie o terminal/VS Code

### 2️⃣ Configurar Git (apenas primeira vez)
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

### 3️⃣ Criar e Configurar Repositório
```bash
# Navegar para o diretório do projeto
cd "c:\Users\Aluno.LAB08-15545.000\projeto-quinta-feira"

# Inicializar repositório Git
git init

# Adicionar arquivos
git add .

# Fazer primeiro commit
git commit -m "Adicionar site IA Evolution com Tailwind CSS"

# Conectar com repositório remoto (substitua pelo URL correto)
git remote add origin https://github.com/RenanGreg/ia-evolution-tailwind.git

# Fazer push para o GitHub
git branch -M main
git push -u origin main
```

## 📁 Arquivos do Projeto

O projeto contém os seguintes arquivos que devem ser enviados:

- **index.html** - Site principal com Tailwind CSS
- **README.md** - Documentação do projeto
- **INSTRUCOES_GITHUB.md** - Este arquivo de instruções

## 🎯 Resultado Final

Após o upload, seu repositório terá:
- ✅ Site funcional da IA Evolution
- ✅ Estilização 100% Tailwind CSS
- ✅ Design responsivo e moderno
- ✅ Documentação completa

## 🔗 URLs Importantes

- **Seu GitHub**: https://github.com/RenanGreg
- **Git Download**: https://git-scm.com/download/win
- **Tailwind CSS Docs**: https://tailwindcss.com/docs

## 📞 Suporte

Se precisar de ajuda:
1. Verifique se o Git está instalado: `git --version`
2. Confirme se está no diretório correto
3. Verifique as permissões do repositório no GitHub

---
**Boa sorte com o upload! 🚀**