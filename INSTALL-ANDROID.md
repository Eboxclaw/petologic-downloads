# Instalar ou atualizar o Petologic no Android

O Petologic é uma prova de conceito: uma app Android com um agente de IA local (0xPaladino), verificações de antivírus, antimalware e anti spam, tudo a correr no telemóvel. Esta prévia é para testes; não substitui um antivírus completo.

## 1. Descarregar

1. No telemóvel, abre a página oficial: https://eboxclaw-petologic.eitherbox.workers.dev
2. Toca em DOWNLOAD PALADINO PREVIEW. O APK é para Android 12 ou superior e processadores ARM64.
3. Abre o ficheiro descarregado. Se o Android pedir autorização, permite Instalar apps desconhecidas apenas ao browser que estás a usar.
4. Confirma Instalar ou Atualizar.

O ficheiro SHA256SUMS.txt acompanha cada versão para verificar a integridade antes de instalar:

```sh
shasum -a 256 -c SHA256SUMS.txt
```

## 2. Modelos locais

Em Definições, descarrega LFM3-Omni-2B Q4_K_M (cerca de 1.1 GB). Opcional: pacote de visão (516 MB) e d1-2B (1.1 GB). As verificações de segurança funcionam mesmo sem modelos.

## 3. O que esta prova de conceito não faz

Não é um antivírus completo. Não remove aplicações, não bloqueia mensagens, não filtra chamadas e não oferece proteção VPN nesta versão. Uma verificação sem correspondências não garante que um ficheiro, app ou dispositivo seja seguro.
