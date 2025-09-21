# Instruções para GitHub Pages

## Configuração Completa

O repositório já está configurado para GitHub Pages com:

- ✅ **_config.yml** - Configuração Jekyll com tema Cayman
- ✅ **index.md** - Página inicial estilizada
- ✅ **artigo/index.md** - Página do artigo acadêmico
- ✅ **manifesto/index.md** - Página do manual prático
- ✅ **Gemfile** - Dependências do Jekyll

## Como Ativar GitHub Pages

1. **Faça commit dos arquivos**:
```bash
git add .
git commit -m "Configuração inicial GitHub Pages"
git push origin main
```

2. **No GitHub, vá em Settings > Pages**:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Clique em "Save"

3. **Aguarde alguns minutos** para o site ficar disponível em:
   `https://[seu-usuario].github.io/vida-poder-desigualdade-social/`

## Estrutura do Site

```
📁 Site Principal (index.md)
├── 📖 Artigo Acadêmico (artigo/)
├── 🛠️ Manual Prático (manifesto/)  
└── 🔬 Análise Teórica (avancos_teoricos/)
```

## Personalização

- **Título**: Edite `title` em `_config.yml`
- **Descrição**: Edite `description` em `_config.yml`
- **Navegação**: Modifique `header_pages` em `_config.yml`
- **Estilo**: Adicione CSS customizado em `index.md` (já incluído)

## Teste Local (Opcional)

```bash
bundle install
bundle exec jekyll serve
```

Acesse: `http://localhost:4000`

## URLs Finais

- **Site Principal**: `[seu-site]/`
- **Artigo**: `[seu-site]/artigo/`
- **Manual**: `[seu-site]/manifesto/`
- **Análise Teórica**: `[seu-site]/avancos_teoricos/`