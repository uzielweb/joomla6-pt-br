# CHANGELOG - Pacote de Idioma Português (Brasil) para Joomla! 6

## [6.0.3.2] - 2026-03-27

### Atualizado
- Sincronização de todos os arquivos de metadados e configuração para a versão 6.0.3.2.
- Atualização da versão do pacote no manifesto principal e nos servidores de atualização.

## [6.0.0.1.20] - 2026-03-11

### Adicionado
- Tradução completa dos plugins de botões do editor (Editors-XTD): Artigo, Contato, Campos, Mídia, Menu, Módulo, Quebra de Página, Leia Mais.

### Alterado
- Naturalização de termos de publicação ("Publicar em" / "Encerrar em").
- Naturalização de termos de destaque ("Destacar em" / "Remover destaque em").
- Alteração de "Pseudônimo" para "Apelido do autor" em todos os campos de criação por alias.
- Alteração de "Acessos" para "Visualizações".
- Melhoria na tradução de termos de link ("Vincular um texto" para "Texto do link").
- Refinamento técnico nos plugins CodeMirror, TinyMCE e Debug (ex: "Fechar parênteses automaticamente", "Shift", "Ctrl").
- Atualização da versão do pacote para 6.0.0.1.20.


## Versão 6.0.0.1.19 (11/03/2026)

### Correções de Traduções "Esdrúxulas" (Literais)
- CORRIGIDO: "Mesa" -> "Tabela" em diversos locais (SQL e interface)
- CORRIGIDO: "Claro" -> "Limpar" para botões de formulário
- CORRIGIDO: "Falha na loja" -> "Falha ao salvar" em mensagens de erro de banco de dados
- CORRIGIDO: "Falha no acerto" -> "Falha ao registrar acesso"
- CORRIGIDO: "Matriz" -> "Array" em mensagens de erro técnicas

### Naturalização de Termos (pt-PT para pt-BR)
- CORRIGIDO: "Ligação" -> "Link" ou "Conexão" (conforme o contexto) em plugins e sistema
- CORRIGIDO: Resquícios de termos técnicos não naturais removidos

## Versão 6.0.0.1.18 (12/03/2026)

### Correções de Idioma e Tradução
- CORRIGIDO: Traduções esdrúxulas e literais em diversos componentes (ex: Categoria infantil -> Subcategorias)
- PADRONIZADO: Uso de "Link" em vez de "Ligação" e "Feed" em vez de "Alimentação"
- CORRIGIDO: Termos técnicos como "Recolher" em vez de "Colapso" e "Último" em vez de "Durar"
- AJUSTADO: Concordância gramatical em strings de API e notificações do sistema
- ATUALIZADO: Todas as tags de "Etiqueta" para "Tag" ou "Rótulo" conforme o contexto

## Versão 6.0.0.1.17 (11/03/2026)

### Atualização de Versão
- ATUALIZADO: Versão do pacote para conformidade com nova regra sem emojis
- SINCRONIZADO: Todos os arquivos de metadados e configuração atualizados para 6.0.0.1.17

---

## Versão 6.0.0.1.16 (11/03/2026)

###  Atualização de Versão
- **ATUALIZADO**: Versão do pacote para compatibilidade com melhorias recentes
- **SINCRONIZADO**: Todos os arquivos de metadados e configuração atualizados para 6.0.0.1.16

###  Melhorias de Terminologia e Gramática
- **MELHORADO**: "Hits"  "Acessos" em múltiplos locais (site e admin)
- **CORRIGIDO**: "Biscoito"  "Cookie" nas configurações globais
- **PADRONIZADO**: "Aulas"  "Classes" em plugins (TinyMCE) e componentes (Content)
- **MELHORADO**: Mensagens de resultados de busca mais naturais com "que o texto %2$s"
- **CORRIGIDO**: Diversas correções de concordância de gênero e número

###  Arquivos Atualizados
- **pkg_pt-BR.xml**: Versão principal do pacote
- **Metadados**: langmetadata.xml e install.xml de todos os clientes (site, admin, api)
- **Updates**: Arquivo de atualizações atualizado
- **Documentação**: CHANGELOG.md e inclusão de regras em .agent/rules.md

###  Compatibilidade
- **Joomla**: 6.0.0.1.16
- **Cobertura**: Melhorias de naturalidade e correção técnica de termos

---

## Versão 6.0.0.1.13 (27/10/2025)

###  Atualização de Versão
- **ATUALIZADO**: Versão do pacote para compatibilidade com Joomla! 6.0.0.1.13
- **SINCRONIZADO**: Todos os arquivos de metadados e configuração atualizados
- **MANTIDO**: Todas as traduções e correções da versão anterior

###  Arquivos Atualizados
- **pkg_pt-BR.xml**: Versão principal do pacote
- **Metadados**: langmetadata.xml e install.xml de todos os clientes (site, admin, api)
- **Updates**: Arquivo de atualizações para downloads
- **Documentação**: README.md, INSTALL.md e CHANGELOG.md

###  Compatibilidade
- **Joomla**: 6.0.0.1.13
- **Cobertura**: Mantidas todas as traduções e melhorias anteriores

---

## Versão 6.0.0.1.12 (18/10/2025)

###  Padronização de Formatação em Mensagens de Erro
- **CORRIGIDO**: Formatação inconsistente "%s:"  "%s: " em erro de banco de dados
- **PADRONIZADO**: Padrão consistente "%s: " para todos os erros de banco de dados
- **MELHORADO**: Consistência visual e legibilidade em mensagens de erro técnicas

###  Arquivos Atualizados
- **admin_pt-BR**: lib_joomla.ini (correção de formatação em JLIB_DATABASE_ERROR_CHECKOUT_FAILED)
- **Formatação**: Padronização de placeholders em mensagens de erro

###  Compatibilidade
- **Joomla**: 6.0.0.1.12
- **Cobertura**: Correções de formatação em mensagens de erro

---

## Versão 6.0.0.1.11 (18/10/2025)

###  Correções de Expressões com "Lixeira"
- **CORRIGIDO**: "categoria lixeira"  "categoria na lixeira" (2 arquivos)
- **CORRIGIDO**: "estado diferente de lixeira"  "estado diferente da lixeira"
- **MELHORADO**: Naturalidade das expressões relacionadas à lixeira
- **PADRONIZADO**: Terminologia consistente para português brasileiro

###  Arquivos Atualizados
- **admin_pt-BR**: lib_joomla.ini, com_menus.ini
- **site_pt-BR**: lib_joomla.ini
- **Terminologia**: Correções semânticas para expressões com "lixeira"

###  Compatibilidade
- **Joomla**: 6.0.0.1.11
- **Cobertura**: Correções semânticas para expressões com "lixeira"

---

## Versão 6.0.0.1.10 (18/10/2025)

###  Correções Adicionais de Expressões Joomla!
- **CORRIGIDO**: "Atualizar token"  "Token de atualização"
- **CORRIGIDO**: "atualizar o Joomla!"  "atualizar o Joomla" (removido ! desnecessário)
- **MELHORADO**: Consistência terminológica em expressões Joomla!
- **PADRONIZADO**: Uso do ponto de exclamação em referências ao Joomla

###  Arquivos Atualizados
- **admin_pt-BR**: com_joomlaupdate.ini (correções terminológicas adicionais)
- **Terminologia**: Padronização de uso do ponto de exclamação

###  Compatibilidade
- **Joomla**: 6.0.0.1.10
- **Cobertura**: Correções terminológicas adicionais

---

## Versão 6.0.0.1.9 (18/10/2025)

###  Correção de Terminologia para Canais de Atualização
- **CORRIGIDO**: "Atualizar canal"  "Canal de atualização" (4 ocorrências)
- **MELHORADO**: Naturalidade da tradução para português brasileiro
- **PADRONIZADO**: Terminologia consistente para canais de atualização do Joomla

###  Arquivos Atualizados
- **admin_pt-BR**: com_joomlaupdate.ini (correção terminológica)
- **Terminologia**: Padronização de "canal de atualização"

###  Compatibilidade
- **Joomla**: 6.0.0.1.9
- **Cobertura**: Correção terminológica para canais de atualização

---

## Versão 6.0.0.1.8 (18/10/2025)

###  Correções Adicionais de Expressões Joomla!
- **CORRIGIDO**: "Joomla! Servidor de idiomas"  "servidor de idiomas do Joomla!"
- **CORRIGIDO**: "Joomla! Site de documentação"  "site de documentação do Joomla!"
- **CORRIGIDO**: "Joomla! instalação"  "instalação do Joomla!"
- **CORRIGIDO**: "Joomla! por exemplo"  "Joomla" (removido erro de tradução)
- **MELHORADO**: Semântica e naturalidade de expressões Joomla! adicionais
- **PADRONIZADO**: Terminologia mais fluida para português brasileiro

###  Arquivos Atualizados
- **admin_pt-BR**: com_installer.ini (correções semânticas adicionais)
- **Terminologia**: Correções semânticas adicionais em expressões Joomla!

###  Compatibilidade
- **Joomla**: 6.0.0.1.8
- **Cobertura**: Correções semânticas adicionais em expressões Joomla!

---

## Versão 6.0.0.1.7 (18/10/2025)

###  Correções Semânticas em Expressões Joomla!
- **CORRIGIDO**: "Joomla! Atualizar"  "Atualização do Joomla!" (3 arquivos)
- **CORRIGIDO**: "Veja Joomla! Atualizações"  "Ver Atualizações do Joomla!"
- **CORRIGIDO**: "Verifique o Joomla! atualizações"  "Verifique as atualizações do Joomla!"
- **CORRIGIDO**: "Joomla! Componente Update"  "Componente de Atualização do Joomla!"
- **MELHORADO**: Semântica e naturalidade das expressões relacionadas ao Joomla!
- **PADRONIZADO**: Terminologia mais fluida para português brasileiro

###  Arquivos Atualizados
- **admin_pt-BR**: com_joomlaupdate.sys.ini, plg_extension_joomlaupdate.sys.ini, plg_extension_joomlaupdate.ini, com_installer.ini
- **Terminologia**: Correções semânticas para expressões Joomla! mais naturais

###  Compatibilidade
- **Joomla**: 6.0.0.1.7
- **Cobertura**: Correções semânticas em expressões Joomla! específicas

---

## Versão 6.0.0.1.6 (18/10/2025)

###  Padronização Completa de Terminologia Checkin/Checkout
- **PADRONIZADO**: "check-out"/"Check-out"  "bloqueado" em todas as ocorrências (12+ arquivos)
- **PADRONIZADO**: Terminologia consistente para sistema de bloqueio/liberação
- **CORRIGIDO**: "itens retirados"  "itens bloqueados"
- **CORRIGIDO**: "itens com bloqueados"  "itens bloqueados"
- **CORRIGIDO**: "fazer liberar"  "liberar"
- **MELHORADO**: Consistência terminológica em admin_pt-BR, site_pt-BR e api_pt-BR
- **APLICADO**: Padrão consistente: "bloqueado" para estado, "liberação" para ação

###  Arquivos Atualizados
- **admin_pt-BR**: lib_joomla.ini, com_menus.ini, com_finder.ini, com_content.ini, com_checkin.ini, com_categories.ini, com_associations.ini
- **site_pt-BR**: lib_joomla.ini (já consistente)
- **api_pt-BR**: joomla.ini (já consistente)
- **Terminologia**: Padronização completa do sistema checkin/checkout

###  Compatibilidade
- **Joomla**: 6.0.0.1.6
- **Cobertura**: 100% das traduções checkin/checkout padronizadas

---

## Versão 6.0.0.1.5 (18/10/2025)

###  Correções de Traduções Literais e Melhorias de Linguagem
- **CORRIGIDO**: JACTION_MANAGE de "Acesse a interface de administração"  "Gerenciar" (3 arquivos)
- **CORRIGIDO**: "Acesse a administração area"  "Acesse a área de administração"
- **CORRIGIDO**: Removidas redundâncias como "área administrativa do administrador"  "área administrativa"
- **MELHORADO**: Naturalidade das traduções em contextos administrativos
- **PADRONIZADO**: Terminologia para português brasileiro mais fluido

###  Arquivos Atualizados
- **admin_pt-BR**: Correções em joomla.ini, com_login.ini, com_modules.ini, com_messages.ini, plg_sampledata_blog.ini
- **site_pt-BR**: Correções em joomla.ini
- **api_pt-BR**: Correções em joomla.ini
- **Terminologia**: Traduções mais naturais e menos literais

###  Compatibilidade
- **Joomla**: 6.0.0.1.5
- **Cobertura**: Traduções mais naturais e fluídas

---

## Versão 6.0.0.1.4 (18/10/2025)

###  Correções de Terminologia Técnica - Sistema de Atualização
- **CORRIGIDO**: "Atualizar sites"  "Sites de atualização" (8 ocorrências)
- **CORRIGIDO**: "Atualizar site"  "Site de atualização" (3 ocorrências)
- **CORRIGIDO**: "Atualizar Gerenciador dos Sites"  "Gerenciador de Sites de Atualização"
- **CORRIGIDO**: "servidor de atualização"  "sites de atualização" em contextos apropriados
- **CORRIGIDO**: Concordância: "Site de atualização liberados"  "Site de atualização liberado"
- **MELHORADO**: Consistência terminológica em módulos e componentes relacionados a atualizações

###  Arquivos Atualizados
- **admin_pt-BR**: Correções em com_joomlaupdate.ini e outros componentes
- **site_pt-BR**: Ajustes em módulos relacionados a atualizações
- **Terminologia**: Padronização completa do vocabulário técnico de atualizações

###  Compatibilidade
- **Joomla**: 6.0.0.1.4
- **Cobertura**: Terminologia técnica de atualizações padronizada

---

## Versão 6.0.0.1.3 (18/10/2025)

###  Correções de Tradução - Sistema de Permissões
- **CORRIGIDO**: Tradução completa de todas as strings de permissão em inglês
- **CORRIGIDO**: 17+ arquivos com strings "Denied"  "Negado" 
- **CORRIGIDO**: Strings "Inherited"  "Herdado" em todo o sistema
- **CORRIGIDO**: Strings "Allowed"  "Permitido" em componentes e bibliotecas
- **CORRIGIDO**: Traduções de regras de permissão (JLIB_RULES_SETTING_NOTES) em 12 componentes
- **CORRIGIDO**: Strings específicas como "Not Set"  "Não Definido" e "Deny"  "Negar"

###  Arquivos Atualizados
- **admin_pt-BR**: 16 arquivos de componentes corrigidos (com_cache, com_contact, com_content, etc.)
- **site_pt-BR**: lib_joomla.ini com correções nas regras de permissão
- **Componentes**: Todas as strings de sistema de permissões traduzidas

###  Compatibilidade
- **Joomla**: 6.0.0.1.3
- **Cobertura**: 100% das strings de permissão traduzidas

---

## Versão 6.0.0.1.2 (18/10/2025)

###  Melhorias Gerais
- **NOVO**: Sistema de atualizações automáticas via GitHub
- **NOVO**: Arquivo de atualizações configurado (`updates/pt-br-language-pack.xml`)
- **MELHORADO**: Concordância gramatical em todo o pacote de idioma
- **MELHORADO**: Consistência terminológica em traduções técnicas

###  Correções de Concordância e Consistência

#### Substituição "Linguagem"  "Idioma"
- **CORRIGIDO**: Substituídas todas as 35+ ocorrências de "linguagem" por "idioma"
- **CORRIGIDO**: Concordância de gênero: "A linguagem"  "O idioma"
- **CORRIGIDO**: "Constantes de linguagem"  "Constantes de idioma"
- **CORRIGIDO**: "Linguagem de depuração"  "Idioma de depuração"
- **CORRIGIDO**: "Linguagem ativa"  "Idioma ativo"

#### Grupos de Campos - Consistência
- **CORRIGIDO**: "Grupos de Campo"  "Grupos de campos"
- **CORRIGIDO**: "Grupo de Campo"  "Grupo de campos"
- **CORRIGIDO**: Padronização entre singular/plural em 8+ arquivos

#### Concordância de Gênero Geral
- **CORRIGIDO**: "Não é permitido senha vazia"  "Não é permitida senha vazia"
- **CORRIGIDO**: "uma dos links"  "um dos links"
- **CORRIGIDO**: "uma de suas pais"  "um de seus pais" (pais é masculino)
- **CORRIGIDO**: "O idioma PHP mbstring não está definido como neutro"

#### Terminologia Técnica "Verificado"
- **MELHORADO**: Diferenciação contextual de "verificado":
  - Check-out de sistema: "bloqueado/liberado"
  - Verificação: "verificado"
  - Marcação de template: "marcado/revisado"
- **CORRIGIDO**: 15+ arquivos com contextos de check-in/check-out

###  Configuração e Infraestrutura
- **NOVO**: Servidor de atualizações GitHub configurado
- **NOVO**: URL de download baseada em tags Git
- **MELHORADO**: Metadados do pacote atualizados

### Correções

#### Problemas de Concordância de Gênero
- **CORRIGIDO**: "A instalação da linguagem"  "A instalação do idioma"
- **CORRIGIDO**: "A código do idioma"  "O código do idioma"
- **CORRIGIDO**: "arquivo de manifesto XML da linguagem"  "arquivo de manifesto XML do idioma"
- **CORRIGIDO**: "arquivo meta XML da linguagem"  "arquivo meta XML do idioma"
- **CORRIGIDO**: "Tanto a linguagem de conteúdo"  "Tanto o idioma de conteúdo"
- **CORRIGIDO**: "A linguagem de conteúdo foi descartada"  "O idioma de conteúdo foi descartado"

#### Traduções de Interface
- **CORRIGIDO**: "Collapsible Dropdown"  "Menu Suspenso Recolhível"
- **CORRIGIDO**: "Dropdown"  "Menu Suspenso"
- **CORRIGIDO**: "Sidebar-left/right"  "Barra Lateral Esquerda/Direita"
- **CORRIGIDO**: "Button - Menu"  "Botão - Menu"
- **CORRIGIDO**: "Collapsible Default Menu"  "Menu Padrão Recolhível"

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

- **Primeira versão oficial**para Joomla! 6.0.0.1.1
- Tradução completa de todos os componentes core
- Suporte completo à Autenticação Multifator (AMF)
- Tradução dos temas Cassiopeia e Atum
- Tradução completa do Smart Search

### Melhorias

#### Terminologia
- **Padronização de termos técnicos:**
 - "Templates"  "Temas" (interface)
 - "Banners"  Mantido como "Banners" (termo técnico universal)
 - "Check-out"  "Bloqueados"
 - "Frontend"  "Site"
 - "Backend"  "Área Administrativa"
 - "Tags"  Mantido em inglês (termo técnico universal)
 - "Tags"  Mantido em inglês (termo técnico universal)

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
- **Palavras de busca ignoradas**(artigos, preposições)
- **Limites de caracteres**para buscas

### Cobertura

- **540+ arquivos traduzidos**
- **30+ componentes**
- **40+ módulos**
- **70+ plugins**
- **2 temas**(Cassiopeia + Atum)
- **100% de tradução**dos arquivos core

### Correções

#### Traduções de Banners
- **Correção de inconsistências terminológicas:**
  - Padronizado uso de "banner" vs "faixa publicitária"
  - Definido "banner" como termo padrão por ser mais reconhecido no contexto web
  
- **Correção de concordâncias:**
  - `"Cliente liberou para edição"`  `"Cliente liberado para edição"`
  - `"clientes liberaram para edição"`  `"clientes liberados para edição"`
  
- **Correção de traduções incorretas:**
  - `"Digite ascendente/decrescente"`  `"Tipo ascendente/decrescente"`
  
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
pkg_pt-BR_6.0.0.1.3.zip
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

**Tradução:**Use Joomla! - Comunidade Brasileira de Joomla!
**Website:**https://www.usejoomla.com.br
**Email:**traducao@usejoomla.com.br

### Licença

GNU General Public License version 2 or later

---

**Próximas Versões:**
- Atualizações conforme novas versões do Joomla! 6
- Melhorias contínuas na qualidade da tradução
- Feedback da comunidade

