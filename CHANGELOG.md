# CHANGELOG - Pacote de Idioma Português (Brasil) para Joomla! 6

## Versão 6.0.0.1 (16/01/2025)

### Novidades

- **Primeira versão oficial** para Joomla! 6.0.0.1
- Tradução completa de todos os componentes core
- Suporte completo à Autenticação Multifator (AMF)
- Tradução dos temas Cassiopeia e Atum
- Tradução completa do Smart Search

### Melhorias

#### Terminologia
- **Padronização de termos técnicos:**
 - "Templates" → "Temas" (interface)
 - "Banners" → "Faixas Publicitárias"
 - "Check-out" → "Bloqueados"
 - "Frontend" → "Site"
 - "Backend" → "Área Administrativa"
 - "Tags" → Mantido em inglês (termo técnico universal)

#### Concordância
- **Tag tratada como feminino no Brasil:**
 - "a tag", "uma tag", "esta tag"
 - Todas as concordâncias verbais corrigidas
 - Particípios concordam com o gênero feminino

#### Arquivos Especiais
- **localise.php criados para:**
 - Site (language/pt-BR/localise.php)
 - Administrador (administrator/language/pt-BR/localise.php)
 - API (api/language/pt-BR/localise.php)
 
- **Regras de pluralização em português**
- **Palavras de busca ignoradas** (artigos, preposições)
- **Limites de caracteres** para buscas

### Cobertura

- **540+ arquivos traduzidos**
- **30+ componentes**
- **40+ módulos**
- **70+ plugins**
- **2 temas** (Cassiopeia + Atum)
- **100% de tradução** dos arquivos core

### Correções

- Correção de inconsistências terminológicas
- Normalização de XMLs de metadados
- Remoção de imagens base64 de flags
- Correção de concordâncias verbais e nominais
- Padronização de plurais

### Arquivos Principais

#### Site (Frontend)
- `joomla.ini` - 533 linhas traduzidas
- Todos os componentes do site
- Todos os módulos do site
- Plugins de conteúdo e sistema

#### Administrador (Backend)
- `joomla.ini` - Versão administrativa
- `com_admin.ini` - 274 linhas (Sistema de informações)
- `com_users.ini` - Gerenciamento de usuários
- `com_tags.ini` - Sistema de tags
- Todos os componentes administrativos
- Módulos administrativos
- Plugins de sistema

#### API
- `joomla.ini` - API traduzida
- Componentes da API
- Webservices

### Temas

#### Cassiopeia (Site)
- `tpl_cassiopeia.ini`
- `tpl_cassiopeia.sys.ini`
- Totalmente traduzido e adaptado

#### Atum (Administrador)
- `tpl_atum.ini`
- `tpl_atum.sys.ini`
- Interface administrativa em PT-BR

### Autenticação Multifator

- Tradução completa do sistema AMF
- Plugins de autenticação:
 - Email (Código por e-mail)
 - TOTP (Google Authenticator, etc.)
 - WebAuthn (Chaves de acesso, biometria)
 - Códigos de backup
- Interface de configuração traduzida
- Mensagens de erro e sucesso em PT-BR

### Metadados de Idioma

```xml
<metadata>
 <name>Portuguese (Brazil)</name>
 <nativeName>Português (Brasil)</nativeName>
 <tag>pt-BR</tag>
 <rtl>0</rtl>
 <locale>pt_BR.utf8, pt_BR.UTF-8, pt_BR, ptb, portuguese, portuguese-brazil, pt</locale>
 <firstDay>0</firstDay>
 <weekEnd>0,6</weekEnd>
 <calendar>gregorian</calendar>
</metadata>
```

### Estrutura do Pacote

```
pkg_pt-BR_6.0.0.1.zip
├── pkg_pt-BR.xml (XML principal do pacote)
├── README.md (Documentação)
├── site_pt-BR/ (Frontend)
│ ├── install.xml
│ ├── langmetadata.xml
│ ├── localise.php
│ └── [540+ arquivos .ini]
├── admin_pt-BR/ (Backend)
│ ├── install.xml
│ ├── langmetadata.xml
│ ├── localise.php
│ └── [460+ arquivos .ini]
└── api_pt-BR/ (API)
 ├── install.xml
 ├── langmetadata.xml
 ├── localise.php
 └── [80+ arquivos .ini]
```

### Créditos

**Tradução:** Use Joomla! - Comunidade Brasileira de Joomla!
**Website:** https://www.usejoomla.com.br
**Email:** traducao@usejoomla.com.br

### Licença

GNU General Public License version 2 or later

---

**Próximas Versões:**
- Atualizações conforme novas versões do Joomla! 6
- Melhorias contínuas na qualidade da tradução
- Feedback da comunidade

