# CHANGELOG - Pacote de Idioma Português (Brasil) para Joomla! 6

## Versão 6.0.0.1.3 (18/10/2025)

### 🔧 Correções de Tradução - Sistema de Permissões
- **CORRIGIDO**: Tradução completa de todas as strings de permissão em inglês
- **CORRIGIDO**: 17+ arquivos com strings "Denied" → "Negado" 
- **CORRIGIDO**: Strings "Inherited" → "Herdado" em todo o sistema
- **CORRIGIDO**: Strings "Allowed" → "Permitido" em componentes e bibliotecas
- **CORRIGIDO**: Traduções de regras de permissão (JLIB_RULES_SETTING_NOTES) em 12 componentes
- **CORRIGIDO**: Strings específicas como "Not Set" → "Não Definido" e "Deny" → "Negar"

### 📁 Arquivos Atualizados
- **admin_pt-BR**: 16 arquivos de componentes corrigidos (com_cache, com_contact, com_content, etc.)
- **site_pt-BR**: lib_joomla.ini com correções nas regras de permissão
- **Componentes**: Todas as strings de sistema de permissões traduzidas

### ✅ Compatibilidade
- **Joomla**: 6.0.0.1.3
- **Cobertura**: 100% das strings de permissão traduzidas

---

## Versão 6.0.0.1.2 (18/10/2025)

### 🚀 Melhorias Gerais
- **NOVO**: Sistema de atualizações automáticas via GitHub
- **NOVO**: Arquivo de atualizações configurado (`updates/pt-br-language-pack.xml`)
- **MELHORADO**: Concordância gramatical em todo o pacote de idioma
- **MELHORADO**: Consistência terminológica em traduções técnicas

### ⚡ Correções de Concordância e Consistência

#### Substituição "Linguagem" → "Idioma"
- **CORRIGIDO**: Substituídas todas as 35+ ocorrências de "linguagem" por "idioma"
- **CORRIGIDO**: Concordância de gênero: "A linguagem" → "O idioma"
- **CORRIGIDO**: "Constantes de linguagem" → "Constantes de idioma"
- **CORRIGIDO**: "Linguagem de depuração" → "Idioma de depuração"
- **CORRIGIDO**: "Linguagem ativa" → "Idioma ativo"

#### Grupos de Campos - Consistência
- **CORRIGIDO**: "Grupos de Campo" → "Grupos de campos"
- **CORRIGIDO**: "Grupo de Campo" → "Grupo de campos"
- **CORRIGIDO**: Padronização entre singular/plural em 8+ arquivos

#### Concordância de Gênero Geral
- **CORRIGIDO**: "Não é permitido senha vazia" → "Não é permitida senha vazia"
- **CORRIGIDO**: "uma dos links" → "um dos links"
- **CORRIGIDO**: "uma de suas pais" → "um de seus pais" (pais é masculino)
- **CORRIGIDO**: "O idioma PHP mbstring não está definido como neutro"

#### Terminologia Técnica "Verificado"
- **MELHORADO**: Diferenciação contextual de "verificado":
  - Check-out de sistema: "bloqueado/liberado"
  - Verificação: "verificado"
  - Marcação de template: "marcado/revisado"
- **CORRIGIDO**: 15+ arquivos com contextos de check-in/check-out

### 🔧 Configuração e Infraestrutura
- **NOVO**: Servidor de atualizações GitHub configurado
- **NOVO**: URL de download baseada em tags Git
- **MELHORADO**: Metadados do pacote atualizados

### Correções

#### Problemas de Concordância de Gênero
- **CORRIGIDO**: "A instalação da linguagem" → "A instalação do idioma"
- **CORRIGIDO**: "A código do idioma" → "O código do idioma"
- **CORRIGIDO**: "arquivo de manifesto XML da linguagem" → "arquivo de manifesto XML do idioma"
- **CORRIGIDO**: "arquivo meta XML da linguagem" → "arquivo meta XML do idioma"
- **CORRIGIDO**: "Tanto a linguagem de conteúdo" → "Tanto o idioma de conteúdo"
- **CORRIGIDO**: "A linguagem de conteúdo foi descartada" → "O idioma de conteúdo foi descartado"

#### Traduções de Interface
- **CORRIGIDO**: "Collapsible Dropdown" → "Menu Suspenso Recolhível"
- **CORRIGIDO**: "Dropdown" → "Menu Suspenso"
- **CORRIGIDO**: "Sidebar-left/right" → "Barra Lateral Esquerda/Direita"
- **CORRIGIDO**: "Button - Menu" → "Botão - Menu"
- **CORRIGIDO**: "Collapsible Default Menu" → "Menu Padrão Recolhível"

#### Padronização Terminológica
- Padronização do uso de "idioma" em vez de "linguagem" para idiomas humanos
- Melhoria na consistência de concordância de gênero e número
- Correção de termos técnicos em inglês que não haviam sido traduzidos

### Arquivos Modificados
- `admin_pt-BR/com_installer.ini`
- `admin_pt-BR/com_languages.ini`
- `admin_pt-BR/plg_editors-xtd_menu.ini`
- `admin_pt-BR/plg_editors-xtd_menu.sys.ini`
- `site_pt-BR/tpl_cassiopeia.sys.ini`
- `site_pt-BR/mod_menu.sys.ini`

## Versão 6.0.0.1.1 (16/10/2025)

### Novidades

- **Primeira versão oficial** para Joomla! 6.0.0.1.1
- Tradução completa de todos os componentes core
- Suporte completo à Autenticação Multifator (AMF)
- Tradução dos temas Cassiopeia e Atum
- Tradução completa do Smart Search

### Melhorias

#### Terminologia
- **Padronização de termos técnicos:**
 - "Templates" → "Temas" (interface)
 - "Banners" → Mantido como "Banners" (termo técnico universal)
 - "Check-out" → "Bloqueados"
 - "Frontend" → "Site"
 - "Backend" → "Área Administrativa"
 - "Tags" → Mantido em inglês (termo técnico universal)
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

#### Traduções de Banners
- **Correção de inconsistências terminológicas:**
  - Padronizado uso de "banner" vs "faixa publicitária"
  - Definido "banner" como termo padrão por ser mais reconhecido no contexto web
  
- **Correção de concordâncias:**
  - `"Cliente liberou para edição"` → `"Cliente liberado para edição"`
  - `"clientes liberaram para edição"` → `"clientes liberados para edição"`
  
- **Correção de traduções incorretas:**
  - `"Digite ascendente/decrescente"` → `"Tipo ascendente/decrescente"`
  
- **Padronização de maiúsculas e minúsculas:**
  - "Banner" (maiúscula) em títulos, labels e ações
  - "banner" (minúscula) em textos descritivos e no meio de frases
  
- **Arquivos corrigidos:**
  - `admin_pt-BR/com_banners.ini`
  - `admin_pt-BR/com_banners.sys.ini`
  - `admin_pt-BR/plg_webservices_banners.ini`
  - `admin_pt-BR/guidedtours.joomla_banners.ini`
  - `admin_pt-BR/guidedtours.joomla_banners_steps.ini`
  - `site_pt-BR/mod_banners.ini`
  - `site_pt-BR/mod_banners.sys.ini`

#### Correções Gerais
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
pkg_pt-BR_6.0.0.1.2.zip
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

