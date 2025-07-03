# fps-limit-gsync-tutorial 🎮⚡

## Guia Completo: Como Limitar FPS com RTSS para Turbinar seu G-Sync e Jogar Suave

---

### Olá, gamer!

Se você curte jogar com o mínimo de lag, sem aquele famoso *tearing* e engasgos, e quer entender **por que limitar o FPS do seu jogo ajuda o G-Sync a funcionar melhor**, você está no lugar certo!  

Este tutorial é para **qualquer pessoa** que queira configurar tudo do jeito certo, com calma e explicações fáceis — mesmo que você não seja um expert em hardware.

---

## 1. Por que limitar FPS ajuda o G-Sync?

- O **G-Sync** sincroniza a frequência do seu monitor com os frames que a placa de vídeo entrega.  
- Quando o jogo gera mais frames do que seu monitor consegue exibir (ex: 150 FPS em um monitor 144Hz), o G-Sync desliga e o V-Sync do driver NVIDIA assume.  
- Isso pode causar **input lag** e aquele incômodo **tearing** (cortes na imagem).  
- Limitando o FPS **alguns quadros abaixo** do refresh do seu monitor, você mantém o G-Sync sempre ativo e evita esses problemas.

---

## 2. O que você vai precisar

- **RTSS (RivaTuner Statistics Server)**, pra limitar o FPS de forma fácil e prática.  
- **Painel de Controle NVIDIA**, pra configurar o G-Sync e o V-Sync direito.  
- Seu jogo favorito, pronto pra jogar no capricho.

---

## 3. Instalando o RTSS 🛠️

1. Acesse o site oficial e faça o download:  
   [Guru3D RTSS Download](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)  
2. Instale o programa normalmente.  
3. Execute o RTSS; ele vai ficar rodando em segundo plano.

---

## 4. Configurando o Painel NVIDIA 🎛️

### Ativando o G-Sync

- Clique com o botão direito na área de trabalho e abra o **Painel de Controle NVIDIA**.  
- Vá em **Display > Configurar G-SYNC**.  
- Marque as opções:  
  - “Ativar G-SYNC, G-SYNC Compatible”.  
  - “Ativar para modo tela cheia e janela” (isso ajuda no modo janela tela cheia, que muita gente gosta por permitir alt-tab rápido).  
- Selecione seu monitor na lista e confirme.

### Configurando o V-Sync

- Ainda no painel NVIDIA, vá para **Gerenciar configurações 3D**.  
- Procure por **Sincronização vertical**.  
- Coloque como **Ligado**.  
- Isso funciona como um "plano B" para evitar tearing se seu FPS passar do refresh do monitor.

---

## 5. Configurando o RTSS para limitar FPS 🎯

- Abra o RTSS.  
- Se quiser limitar todos os jogos, selecione o perfil “Global”.  
- Para limitar um jogo específico, clique no botão “+” e escolha o executável.  
- No campo **Framerate limit**, coloque um valor:  
  - Para monitor 144Hz: **141 FPS** (ou 140.7 para estabilidade extra).  
  - Para monitor 60Hz: **58 FPS** (ou 57.9).  
  - Para outros refresh rates, limite sempre 1 a 3 FPS abaixo do máximo.  
- Deixe o RTSS aberto enquanto estiver jogando.

---

## 6. Configurações dentro do jogo 🎮

- Desative o **V-Sync dentro do jogo**!  
- Use o modo **tela cheia** ou **janela tela cheia** conforme sua preferência.  
- O modo janela tela cheia ajuda bastante para alt-tab rápido, mas certifique-se que seu G-Sync está ativado para funcionar nesse modo (verifique no painel NVIDIA).

---

## 7. Por que isso funciona? ⚙️

- Ao limitar o FPS um pouco abaixo do refresh do monitor, o G-Sync fica **sempre ativo** e sincroniza perfeitamente as imagens.  
- Quando o FPS ultrapassa o limite do monitor, o V-Sync do driver entra para evitar tearing, mas pode gerar input lag.  
- Esse balanceamento deixa a jogabilidade mais fluida, com imagem estável e resposta rápida.

---

## 8. Dicas extras para ficar tinindo ✨

- O RTSS aceita valores decimais, tipo **140.7 FPS**, que ajuda a evitar micro variações que causam stutter.  
- Use o **indicador de G-Sync** no painel NVIDIA para confirmar se está funcionando.  
- Se sentir tearing, diminua o limite de FPS em 1 ou 2.  
- Se sentir input lag, experimente diminuir o limite um pouco mais ou usar modo tela cheia exclusivo.

---

## 9. Resumo rápido

| Configuração               | Valor/Status                                   |
|---------------------------|------------------------------------------------|
| G-Sync                    | Ativado para modo tela cheia e janela          |
| V-Sync (driver NVIDIA)    | Ligado (fallback)                              |
| V-Sync (in-game)          | Desligado                                     |
| FPS limit (RTSS)          | 1-3 FPS abaixo do refresh do monitor           |
| Modo de exibição          | Tela cheia ou janela tela cheia (para alt-tab) |

---

## 10. Referências úteis 📚

- [Guru3D RTSS Download](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)  
- [NVIDIA G-Sync Overview](https://www.nvidia.com/en-us/geforce/news/gsync-ultimate-experience/)  
- [Como limitar FPS para G-Sync - Fórum NVIDIA](https://www.nvidia.com/en-us/geforce/forums/game-ready-drivers/13/3148/how-to-properly-cap-fps-for-g-sync/)

---


