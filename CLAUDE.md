# Diretrizes para trabalhar neste repositório

- Não mencionar Claude, Anthropic ou IA/assistente em nenhum lugar dos
  arquivos, mensagens de commit ou descrições de PR deste projeto, nem
  adicionar linhas `Co-Authored-By` de assistente.
- **O repositório é público.** Nenhuma senha, token, chave de API, chave de
  criptografia do ESPHome, SSID ou IP interno entra em arquivo versionado. No
  ESPHome isso vai por `!secret`, com o `secrets.yaml` fora do git; aqui fica
  só a estrutura.
- `BluePrint/iluminacao_inteligente.yaml` é um blueprint do Home Assistant.
  A `description` dele lista a prioridade das regras (alarme em "Home" acima
  de tudo, depois as demais); mudou a lógica, atualiza essa lista junto. Ela
  é o que aparece para quem importa o blueprint, então não pode ficar
  desatualizada.
- `ESPHome/athom-presence-sensor-v3.yaml` está vazio (só o arquivo foi
  criado).
