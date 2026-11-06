# ScreenRecorder Pro — correções visuais

## Arquivos alterados
- `app/src/main/java/com/example/ui/theme/Color.kt`
  - Corrigidos os tokens semânticos `NavySurface`, `NavySurfaceVariant`, `NavySurfaceHigh` e `NavyBorder`.
  - As superfícies Navy agora usam tons azul-marinho, evitando texto branco sobre fundo branco.
  - Mantido o fundo principal azul royal `#1300F5`, azul-marinho `#101B3D` e ciano `#00D9FF`.
- `app/src/main/java/com/example/ui/theme/Type.kt`
  - Criada hierarquia tipográfica consistente com sans-serif nativa (Roboto no Android), sem adicionar dependências externas.

## O que foi preservado
Nenhuma lógica de gravação, áudio, Facecam, anotações, galeria ou persistência foi intencionalmente alterada.

## Validação
O ZIP original não contém `gradlew` e o ambiente de execução não disponibiliza Gradle instalado. Portanto, não foi possível executar uma compilação Android aqui. Abra o projeto no Android Studio, sincronize o Gradle e execute `Build > Make Project` antes de instalar no aparelho.

## Como aplicar
1. Faça uma cópia de segurança do projeto atual.
2. Extraia este ZIP em uma pasta nova.
3. Abra a pasta raiz no Android Studio.
4. Aguarde a sincronização do Gradle.
5. Compile e teste as quatro abas: Início, Sinalizar, Gravações e Ajustes.
