# Configuração do VSCode para o Repositório

Este diretório contém as configurações do VSCode para facilitar a edição deste repositório GitHub.

## Arquivos de Configuração

### `.vscode/settings.json`
Configurações do editor incluindo:
- Formatação automática ao salvar
- Quebra de linha automática
- Salvamento automático
- Configurações específicas para Markdown
- Integração com Git

### `.vscode/extensions.json`
Lista de extensões recomendadas do VSCode:
- **Markdown All in One**: Suporte completo para Markdown
- **Markdown Lint**: Linter para arquivos Markdown
- **GitLens**: Visualização avançada do Git
- **GitHub Pull Requests**: Integração com GitHub
- **GitHub Copilot**: Assistente de código AI
- **PDF Viewer**: Visualizador de PDFs integrado

### `.vscode/tasks.json`
Tarefas rápidas do VSCode:
- Abrir README
- Git Status
- Git Pull
- Git Push

### `amgauna.code-workspace`
Arquivo de workspace do VSCode que organiza o projeto em pastas lógicas.

## Como Usar

### Opção 1: Abrir Pasta
1. Abra o VSCode
2. Vá em `File > Open Folder...`
3. Selecione a pasta do repositório
4. O VSCode automaticamente usará as configurações em `.vscode/`

### Opção 2: Usar Workspace (Recomendado)
1. Abra o VSCode
2. Vá em `File > Open Workspace from File...`
3. Selecione o arquivo `amgauna.code-workspace`
4. Isso organizará o projeto com pastas separadas para cada seção

## Instalando Extensões Recomendadas

Quando abrir o projeto, o VSCode sugerirá automaticamente as extensões recomendadas. Você também pode:
1. Pressionar `Ctrl+Shift+P` (ou `Cmd+Shift+P` no Mac)
2. Digite "Extensions: Show Recommended Extensions"
3. Instale as extensões sugeridas

## Tarefas do VSCode

Para executar tarefas:
1. Pressione `Ctrl+Shift+P` (ou `Cmd+Shift+P` no Mac)
2. Digite "Tasks: Run Task"
3. Selecione a tarefa desejada

## Atalhos Úteis

- `Ctrl+K V` - Abrir preview do Markdown lado a lado
- `Ctrl+Shift+V` - Abrir preview do Markdown
- `Ctrl+Shift+P` - Paleta de comandos
- `Ctrl+P` - Busca rápida de arquivos
- `Ctrl+Shift+G` - Abrir controle de versão Git
