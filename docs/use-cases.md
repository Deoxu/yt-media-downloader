## Casos de Uso

---

### UC01 – Inserir link do YouTube

**Ator:** Usuário  

**Descrição:** Permite ao usuário inserir um link de vídeo do YouTube para iniciar o processo de download.

**Fluxo principal:**
1. Usuário insere o link na aplicação
2. Sistema valida o link
3. Sistema armazena o link para processamento

**Fluxo alternativo:**
- 2a. Link inválido  
  → Sistema exibe mensagem de erro

---

### UC02 – Visualizar informações do vídeo

**Ator:** Usuário  

**Descrição:** Permite visualizar dados do vídeo antes do download.

**Fluxo principal:**
1. Sistema processa o link inserido
2. Sistema busca informações do vídeo
3. Sistema exibe título, duração e outras informações

---

### UC03 – Selecionar formato de download

**Ator:** Usuário  

**Descrição:** Permite escolher o formato do arquivo.

**Fluxo principal:**
1. Usuário escolhe entre MP3 ou MP4
2. Sistema registra a escolha

---

### UC04 – Selecionar pasta de destino

**Ator:** Usuário  

**Descrição:** Permite definir onde o arquivo será salvo.

**Fluxo principal:**
1. Usuário abre o seletor de diretório
2. Usuário escolhe a pasta
3. Sistema salva o caminho selecionado

---

### UC05 – Formatar nome dos arquivos

**Ator:** Usuário  

**Descrição:** Permite padronizar automaticamente os nomes dos arquivos baixados.

**Fluxo principal:**
1. Usuário ativa opção de formatação automática
2. Sistema aplica regras:
   - enumeração dos arquivos
   - remoção de caracteres especiais
3. Sistema gera nome final do arquivo

---

### UC06 – Executar aplicação desktop

**Ator:** Usuário  

**Descrição:** Permite utilizar a aplicação localmente sem depender de serviços externos.

**Fluxo principal:**
1. Usuário abre a aplicação no computador
2. Sistema inicializa interface
3. Usuário interage normalmente com as funcionalidades

---

### UC07 – Baixar vídeos de playlist

**Ator:** Usuário  

**Descrição:** Permite baixar múltiplos vídeos a partir de uma playlist.

**Fluxo principal:**
1. Usuário insere link de playlist
2. Sistema identifica os vídeos da playlist
3. Sistema inicia downloads automaticamente

**Fluxo alternativo:**
- 2a. Playlist inválida  
  → Sistema exibe erro

---

### UC08 – Exibir progresso do download

**Ator:** Usuário  

**Descrição:** Permite acompanhar o andamento do download.

**Fluxo principal:**
1. Sistema inicia download
2. Sistema exibe progresso em percentual
3. Sistema atualiza progresso em tempo real
4. Sistema notifica quando o download é concluído
