# Guia de Memorização Rápida — OS 191045 (Desenvolvimento SAEP)

Tutorial interativo em HTML e CSS com o **Método B-B-P-C-D** para execução completa da Ordem de Serviço 191045 (Banco de Dados, Backup Automático, Aplicação Python/Flask e Dashboard Gerencial).

## Como acessar
- Abra o arquivo `index.html` diretamente no navegador ou acesse via GitHub Pages:
  **https://instrutorrafaelreis.github.io/tutorialrota/**

## O Método B-B-P-C-D (5 Passos = 23 Pontos)
1. **B — Banco (`dbfilialnorte`)**: Criação do banco UTF-8 e importação do script SQL.
2. **B — Backup (`backup.bat`)**: Script `mysqldump` gerando `BKP-DDMMAAAAHHMM.sql` em `C:\BKP_BANCO` + agendamento às `06:00` e `18:00`.
3. **P — Python (`app.py`)**: Rotas `/` (Cadastro) e `/dashboard` (3 consultas SQL) rodando em `host="0.0.0.0"`.
4. **C — Cadastro (`templates/cadastro.html`)**: Formulário com 5 campos, calendário nativo (`type="date"`), CSS Grid e botões Cadastrar/Limpar/Voltar.
5. **D — Dashboard (`templates/dashboard.html`)**: Painel com 3 indicadores + liberação de porta 5000 e atalho na Estação `PC_02`.
