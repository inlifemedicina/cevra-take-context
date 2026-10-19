# Retomada e próximos passos

## Antes de trabalhar

1. Obter acesso ao checkout local recente do projeto de desenvolvimento.
   Conferir origem, branch, HEAD e alterações existentes. Não sobrescrever
   trabalho nem presumir que o `main` remoto reproduz a build instalada.
2. Ler primeiro `LEIA_PRIMEIRO.md` no projeto local. Buscar detalhes somente
   quando necessários; antes de alterar arquivos, ler `AGENTS.md`. Os registros
   locais de contexto são `docs/RETOMADA_ATUAL.md` e `docs/MASTER_CONTEXT.md`.
   Os detalhes estão em
   `docs/VIDEO_SDR_TREATMENT_ROUND1.md`, `docs/VIDEO_PHOTO_ROUND1.md` e
   `docs/RAW_PRORAW_PREFLIGHT.md`. Os nomes são referências locais, não
   promessa de disponibilidade desses arquivos no remoto antigo.
3. Preservar aceites já concluídos. Uma conversa nova não é motivo para
   reinstalar, regravar ou repetir testes sem alteração ou defeito concreto.

## Próximo teste humano: tratamento SDR

Usar uma tomada SDR existente; não é necessária nova gravação.

1. **Biblioteca → tomada → Tratar imagem SDR**. Mudar os quatro controles,
   tocar **Gerar prévia SDR → Reproduzir** e conferir imagem, voz, sincronismo
   e orientação.
2. Mudar um controle: a exportação anterior deve ficar indisponível até
   **Atualizar prévia SDR**. Usar **Salvar/compartilhar cópia SDR → Salvar em
   Arquivos**, abrir a cópia fora do Take e conferir início, fim e áudio.
3. Ao voltar, escolher **Continuar editando** e depois **Voltar e encerrar
   ajustes**. Reabrir o original e conferir que permanece igual; a cópia
   salva em Arquivos deve continuar disponível.

Os ajustes duram a sessão: salvar antes de sair. Se houver recusa de formato
ou cor, registrar a mensagem e não forçar conversão. Registrar o resultado
somente para os itens e a tomada efetivamente exercitados.

## Pendências separadas

- Confirmar escopo e amostras autorizadas para RAW/ProRAW antes de implementar.
- Concluir a auditoria histórica antes de propor publicação do código recente.
  Preservar o histórico, preparar integração isolada, revisar conteúdo e obter
  a autorização correspondente. Este repositório não concede essa autorização.
- Manter Vids e skill nos trabalhos próprios. Este snapshot não certifica seu
  estado atual nem autoriza alterações cruzadas.

## Manutenção econômica aprovada

Registrar somente decisões importantes, fechamentos de bloco e novas pendências.
Cada registro deve ser curto: data, decisão ou resultado, referência da evidência
e próximo passo. Atualizar o documento responsável, evitando duplicar a conversa.

Consolidar semanalmente de forma incremental, incorporando apenas os registros
novos e mudanças de estado. Na retomada após reset, ler o resumo inicial
`LEIA_PRIMEIRO` e consultar detalhes sob demanda. Se o reset ocorrer antes da
consolidação semanal, fazer uma consolidação final curta antes dele.

Essa política não cria uma automação: nenhum agendamento foi configurado nesta
preparação única. Código e backups continuam separados do contexto. Atualizações
públicas exigem sanitização e revisão; não publicar dados privados para completar
o resumo.

## Limite de recuperação

Com estes documentos, uma conversa recupera o objetivo, os checkpoints e as
pendências. **Sem o checkout e os artefatos locais autorizados, não recupera o
código recente, os dados, as credenciais, os backups ou a capacidade de gerar
o aplicativo.** Nenhum conteúdo privado deve ser acrescentado para preencher
essa lacuna. Atualizar este contexto apenas com fatos novos verificados,
mantendo revisão independente antes de publicar.
