# Meu treino

App de treino para o celular, com os treinos A a G. Depois de instalado, funciona sem internet.

## 1. Publicar (uma vez, pelo computador)

1. No GitHub, crie um repositório **público** chamado `meu-treino`.
2. Clique em **Add file → Upload files**, arraste todos os arquivos desta pasta e confirme em **Commit changes**.
3. Vá em **Settings → Pages**. Em *Branch*, escolha `main` e `/ (root)` e clique em **Save**.
4. Em 1 ou 2 minutos o endereço aparece no topo dessa página: `https://SEU-USUARIO.github.io/meu-treino/`

## 2. Instalar no Android

1. Abra o endereço no **Chrome** do celular.
2. Toque em **Instalar** no aviso do app (ou no menu ⋮ → **Instalar app**).
3. Abra sempre pelo ícone na tela inicial. A partir daí funciona sem internet.

## Como usar

- Ao abrir, aparece o treino do dia. Toque no número de um exercício para marcá-lo como feito.
- Séries, repetições, carga e observação são editadas direto na lista e salvas na hora.
- **Finalizar treino** guarda as cargas no histórico e passa para o próximo. A ordem se escolhe na engrenagem → **Ordem dos treinos**:
  - **Dois ciclos** (padrão): **A → B → C → D → A** e **E → F → G → E**. O próximo é sempre do mesmo ciclo.
  - **Ciclo único**: **A → B → C → D → E → F → G → A**.
- Para fazer outro treino no dia, toque na letra dele e em **Fazer o … hoje**. No modo de dois ciclos, é assim que se troca de ciclo.
- O lápis serve para renomear, reordenar, adicionar e remover exercícios.

## Seus dados

Cargas e histórico ficam só no celular; o GitHub guarda apenas a ficha inicial. Faça um backup de vez em quando pela engrenagem → **Exportar backup**. Em outro celular, use **Importar backup**. O backup também guarda a ordem escolhida.

## Atualizar o app

Troque os arquivos no repositório e, em `sw.js`, aumente o número em `meu-treino-v3` (v4, v5 e assim por diante). Depois, abra o app no celular, espere alguns segundos, feche e abra de novo. Os dados do celular continuam lá.

## Versão 1.2

- Opção de **ciclo único** (A a G em sequência), na engrenagem → **Ordem dos treinos**.
- O backup passou para a mesma tela (o ícone de disquete virou engrenagem).

## Versão 1.1

- Novos treinos E, F e G, com as cargas da ficha nova.
- Quem já usava a versão 1.0 mantém treinos, cargas e histórico: os treinos E, F e G aparecem sozinhos assim que a versão nova abrir.
- A ficha inicial (usada num celular novo) já inclui as mudanças feitas nos treinos C e D.
