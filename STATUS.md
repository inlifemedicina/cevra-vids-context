# Estado de retomada — 19/10/2026

## Escopo e decisões

- Manter pausada a expansão do editor original. Não instalar, promover builds,
  migrar projetos ou alterar os apps/stores existentes por causa deste contexto.
- Preservar Project IR e histórico tipado como autoridades do app; não adotar
  engine, dependência ou arquitetura nova implicitamente.
- A skill independente foi aprovada e a organização visual Mesa A foi escolhida.
  Seu desenvolvimento é separado do app; integrações futuras exigem contratos e
  conciliação explícitos. O alvo funcional continua a cobertura completa do EDvid;
  os blocos incrementais não demonstram essa paridade.
- HyperFrames permanece candidato a benchmark, não engine adotada. Apple-design
  foi referência documental; não equivale a componente instalado. OpenDesign não
  foi encontrado como dependência/importação no recorte local consultado.

## Marcadores técnicos das fontes existentes

Os hashes abaixo identificam fontes locais ou o estado remoto informado na
auditoria de continuidade. **Não são commits deste repositório de contexto** e
sua listagem não significa que o código correspondente esteja publicado.

| Marco | Commit | Limite |
|---|---|---|
| Main do app observado na auditoria remota recebida | `e70242e27085ba408b02ebbf8d9327130e71e9f4` | Referência de 16/10; não inclui automaticamente trabalho local posterior |
| Biblioteca local R2 implementada | `1b4748e72a55e558598bf7a09ae30280264b024e` | Entrega técnica; aceite físico/humano adiado |
| Contexto local detalhado consolidado | `987a853b06d25890bb50d855c5e1ca6fbc829a40` | Inclui registros da skill até 18/10; não é promoção do app |

A auditoria local encontrou 23 commits além da referência local de main acima,
incluindo código e documentação. Isso não é uma atualização só de contexto e não
autoriza integrar a branch inteira. O histórico desses projetos não foi copiado
para cá. Estes marcadores precisam ser reconferidos nos projetos de origem antes
de uma futura integração.

## Entregas e evidência histórica

Há melhorias locais de feedback de exportação/localização de mídia, estabilidade
de controles e timeline, centésimos e biblioteca de projetos. A biblioteca R2
tem candidato isolado e prova do Host empacotado: 22 requisições em store sintético
próprio cobriram transições, preservação de estado/histórico e rejeição de respostas
antigas. A revisão técnica do pacote não deixou bloqueios no delta delimitado.

Essas provas não demonstram aceitação do fluxo físico Tauri ou julgamento de UX.
Tempos de Host não são latência visual; não há promessa de eliminar 2,2 segundos.
Resultados focados aprovados não significam CI amplo integralmente aprovado ou
release do produto. Falhas históricas não são apagadas por este resumo.

## Aceites e trabalho pendente

- R2: delta coordenado no Tauri real para Novo/Abrir, vínculo de sessão/picker,
  fechamento/reabertura e julgamento humano de UX. Está adiado, não aprovado.
- Extensão experimental vertical: apresentação Tauri e julgamento visual mínimo
  permanecem pendentes no registro detalhado. Não promover flags/defaults.
- Na skill: imagem/orientação/áudio/sync e um trecho na Mesa A original, além de
  aceite de exportação pessoal no modo durável, permanecem separados dos testes
  automatizados. Não inferir aceite do app a partir da skill.

Não foi revalidada a atividade de nenhuma sessão humana durante a auditoria.
Registros antigos de processo/porta não provam que a sessão continue ativa.

## Próximos passos

1. Recuperar as fontes e evidências detalhadas nos projetos de desenvolvimento;
   conferir HEAD, branch e alterações locais antes de agir.
2. Retomar somente o escopo autorizado, coordenando a GUI para o menor delta
   humano ainda pendente. Não repetir gates já aprovados sem motivo novo.
3. Se houver decisão de integração, revisar os commits de produto separadamente
   da documentação. Este repositório não autoriza merge, instalação ou release.
4. Atualizar este resumo com fatos verificados, distinguindo teste automatizado,
   aceite humano e bloqueios. Manter código, mídia e evidência privada nos locais
   apropriados; não publicar conversas integrais ou dados de sessões.
