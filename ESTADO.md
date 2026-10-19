# Estado técnico e limites de evidência

Checkpoint de 19/10/2026, derivado dos documentos e recibos locais revisados.
Este repositório publica somente o resumo sanitizado, sem os artefatos privados.

## Identidade do trabalho

| Referência | Valor |
|---|---|
| Projeto de desenvolvimento | `inlifemedicina/cevra-take` |
| Branch local recente | `feat/consolidated-approved-flows-2026-10-16` |
| HEAD documental local conferido | `2c43930f00e35a19a9d09c9c7e7bcd3d39a0a5c0` |
| Fonte da build 19001 | `840bcfaa954cf60f5a3bf428f71c054004441824` |
| Fonte da build 18002 | `02de4f23648c3ae09f351312341bf384bf99ccc3` |
| Fechamento da instalação 19001 | `91b2d1abcbd5ab86f309170ee9a81d10c0308f5c` |
| `main` remoto de desenvolvimento observado | `4130c26b7e8935ce3b3b581d4274e4bfeb60c5f1` |

Os hashes recentes identificam commits locais verificados; não se presume que
estejam disponíveis no GitHub. No HEAD documental acima, os históricos tinham
base comum, mas divergiam em um commit exclusivo remoto e 56 locais. A branch
recente não foi anunciada pela consulta remota. A publicação deste contexto
não sincroniza nem copia esses commits.

## Resultados comprovados

- **18002 — fotografia:** percursos delimitados aceitos por relato humano,
  incluindo o complemento de captura horizontal, orientação, reabertura e
  exportações. Esses relatos não certificam toda a qualidade profissional.
- **19001 — offline:** 159 testes PASS, um opcional SKIPPED, build nativo iOS
  PASS e dois casos de UI no Simulator PASS. Os casos de UI cobrem português,
  inglês, rotação e texto ampliado. O teste opcional requer material real de
  recuperação não utilizado nessa rodada; não é evidência física.
- **19001 — instalação:** instalada uma única vez em 19/10/2026. Duas cópias
  completas antes e uma depois confirmaram os 209 arquivos preservados,
  incluindo fotos e revisões. Backups arquivados e verificados localmente,
  fora da sincronização em nuvem; revisão independente aprovada.
- Os 65 hashes de fontes da candidata permaneceram iguais nos fechamentos
  documentais. Os testes aprovados foram reutilizados por correspondência de
  fontes, sem repetição na instalação ou na publicação deste contexto.

O build de produto usa o caminho Swift nativo já validado; o projeto Xcode
de UI é um harness de testes. Não presumir um novo projeto Xcode de produto.

## Resultados que permanecem delimitados

A comparação estrita após instalação ficou **BLOCKED** por ausência de duas
pastas vazias de snapshots. Uma decisão separada aceitou exatamente essa
diferença pela política previamente aprovada; todos os arquivos permaneceram
idênticos. Nenhuma exceção geral para dados ou caches foi introduzida.

Depois das consultas físicas concluídas, o último comando Git local excedeu
o prazo. O bloqueio original foi preservado; um complemento local revisado
concluiu os gates de identidade e integridade, sem repetir operações físicas.

**Aceite humano do tratamento SDR: NOT_RUN.** Qualidade no aparelho,
memória, desempenho térmico e latência em 4K não foram certificados pelos
testes sintéticos ou pela instalação. Produto completo e RAW/ProRAW não foram
promovidos a concluídos.

A auditoria histórica completa do repositório de desenvolvimento excedeu seu
prazo e permanece incompleta. A verificação delimitada da árvore atual não
certifica todo o histórico para publicação. Este novo repositório documental
tem conteúdo e histórico próprios; não transporta aquele histórico Git.
