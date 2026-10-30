# Guia de instalação — Paladino 0.0.1 (Android)

1. Descarregue o APK da versão `v0.0.1` na página do projeto e abra-o no telefone.
2. Permita a instalação deste navegador apenas quando o Android pedir.
3. Instale os modelos locais (conversa, visão ou memória vetorial) nas Definições da aplicação,
   quando quiser. Todos os downloads são verificados antes da instalação.
4. Ao atualizar, mantenha a aplicação existente instalada para preservar conversas e definições.

## Verificar a integridade do ficheiro

Compare o SHA-256 do APK descarregado com o valor publicado em `SHA256SUMS.txt` da mesma versão:

```sh
shasum -a 256 petologic-0.0.1-arm64.apk
```

Se o valor não coincidir, não instale o ficheiro e reporte o problema no repositório principal.

## Requisitos

- Android 12 ou superior (ARM64).
- Sem conta e sem chave de API para o modo local (Tiny). A cloud (Maxx) é opcional e usa a sua
  própria chave.

## Limites desta prévia

Uma verificação sem correspondências não garante que um ficheiro, aplicação ou dispositivo seja
seguro. As regras incluídas são intencionalmente limitadas e a atualização automática de ameaças
ainda não está configurada. O Paladino não remove aplicações, bloqueia mensagens, filtra
chamadas nem oferece proteção VPN nesta versão.
