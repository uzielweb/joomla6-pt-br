# 📋 TODO - Ideias de Melhorias para o Pacote de Idioma PT-BR

Este arquivo reúne sugestões de melhorias técnicas, de automação e de qualidade para o pacote de idioma Português (Brasil) do Joomla 6.

---

## 🚀 1. Automação e Qualidade de Código (CI/CD)

- [ ] **Validador de Sintaxe Automático**: Expandir o script de comparação para validar a sintaxe dos arquivos `.ini` (ex: verificar aspas não fechadas, caracteres de escape inválidos como `\"`, ou chaves duplicadas no mesmo arquivo).
- [ ] **GitHub Actions (CI)**: Criar um fluxo de integração contínua que execute o script de validação de traduções e sintaxe a cada Pull Request ou Push na branch principal.
- [ ] **Verificador de UTF-8 sem BOM**: Adicionar no script de CI um check para garantir que nenhum arquivo seja acidentalmente salvo com codificação diferente de **UTF-8 sem BOM** (o que quebra a renderização do Joomla).
- [ ] **Auto-empacotador**: Configurar uma Action no GitHub que gere automaticamente o arquivo `.zip` final do pacote (`pkg_pt-BR-v*.zip`) e o anexe como asset de release sempre que uma nova tag for criada.

---

## ✍️ 2. Melhorias de Tradução e Consistência (UX/L10n)

- [ ] **Mapeamento de URLs de Ajuda (Help URLs)**: Revisar as chaves de links de ajuda (`HELPURL` ou `COM_XXXX_HELP_URL`) nos arquivos de configuração do administrador para direcionar à documentação em português (ex: Use Joomla! ou Wiki traduzido) em vez do docs.joomla.org em inglês.
- [ ] **Padronização Estrita de Termos**: Realizar um pente fino periódico nos novos plugins do Joomla 6.x para garantir que termos técnicos sigam as decisões de tradução já tomadas:
  - *Workflow* ➔ "Fluxo de Trabalho"
  - *Task* ➔ "Tarefa"
  - *Feature/Unfeature* ➔ "Destaque/Remover Destaque"
- [ ] **Revisão de Textos Longos e E-mails**: Fazer uma revisão editorial nas mensagens longas de e-mail (como as de notificação de atualização e consentimento de privacidade) para garantir uma leitura natural e formal.

---

## 📦 3. Recursos Adicionais

- [ ] **Plugin de Dados de Exemplo (Sample Data)**: Desenvolver ou traduzir dados de exemplo nativos em PT-BR para facilitar testes de novos sites criados no Brasil.
- [ ] **Melhorias no localise.php**: Atualizar a lista de palavras ignoradas (*search ignore list*) e regras locais para refletir termos de pesquisa modernos usados na web brasileira.
