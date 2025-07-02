# fps-limit-gsync-tutorial

## Guia Completo: Como Limitar FPS com RTSS para Melhorar a Experiência com G-Sync

### 1. Introdução

Este tutorial explica, de forma simples e direta, como usar o **RTSS (RivaTuner Statistics Server)** para limitar o FPS dos seus jogos, garantindo que o **G-Sync funcione de maneira ideal**. O objetivo é eliminar tearing, stuttering e reduzir input lag, proporcionando uma jogabilidade mais suave.

---

### 2. Por que limitar FPS ajuda com G-Sync?

- **G-Sync sincroniza a taxa de atualização do monitor com o número de frames gerados pela GPU.**  
- Quando o FPS ultrapassa o máximo que o monitor pode exibir (ex: mais de 144 FPS num monitor 144Hz), o G-Sync desativa e o V-Sync do driver entra em ação, causando input lag e tearing.  
- Limitar FPS para um valor **um pouco abaixo do refresh rate do monitor** mantém o FPS dentro do range de funcionamento do G-Sync, eliminando tearing e reduzindo lag.

---

### 3. Ferramentas necessárias

- **RTSS (RivaTuner Statistics Server):** Para limitar o FPS facilmente.  
- **Painel de controle NVIDIA:** Para configurar G-Sync e V-Sync corretamente.  
- Seu jogo favorito.

---

### 4. Instalando o RTSS

- Baixe no site oficial:  
  [Guru3D RTSS](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)  
- Instale e execute o programa.

---

### 5. Configurando o Painel de Controle NVIDIA

#### Ativar G-Sync:

1. Abra o **Painel de Controle NVIDIA** (clicando com o botão direito na área de trabalho).  
2. Vá em **Display > Configurar G-SYNC**.  
3. Marque:  
   - “Ativar G-SYNC, G-SYNC Compatible”.  
   - “Ativar para modo tela cheia e janela” (para suportar jogos em ambos os modos).  
4. Confirme seu monitor na lista.

#### Configurar V-Sync:

1. Vá para **Gerenciar configurações 3D**.  
2. Encontre a opção **Sincronização vertical**.  
3. Defina como **Ligado** — para servir como fallback caso o FPS ultrapasse o limite do G-Sync.

---

### 6. Configurando o RTSS para limitar FPS

1. Abra o **RTSS**.  
2. Para limitar FPS globalmente, selecione o perfil “**Global**”.  
3. Para limitar um jogo específico:  
   - Clique no botão “+”.  
   - Selecione o executável do jogo.  
4. No campo **“Framerate limit”**, insira:  
   - Para monitor 144Hz: limite em **141 FPS** ou **140.7 FPS** para estabilidade extra.  
   - Para monitor 60Hz: limite em **58 FPS** ou **57.9 FPS**.  
   - Para qualquer outro refresh, limite 1-3 FPS abaixo do refresh rate nativo.  
5. Deixe o RTSS aberto enquanto joga.

---

### 7. Configurações dentro do jogo

- Desligue o V-Sync **dentro do jogo** para evitar conflitos com o V-Sync do driver.  
- Use modo **tela cheia ou janela tela cheia** conforme sua preferência (janela tela cheia permite alt-tab rápido).

---

### 8. Como funciona na prática

- Limitar FPS mantém o G-Sync ativo todo o tempo.  
- O V-Sync do driver só atua se o FPS ultrapassar o limite do monitor, prevenindo tearing.  
- A experiência fica mais suave, com menos input lag e sem tearing.

---

### 9. Dicas extras

- Use valores decimais no limite de FPS para maior precisão (ex: 140.7 FPS).  
- Use o indicador de G-Sync no painel NVIDIA para verificar se está ativo.  
- Ajuste o limite se perceber tearing ou input lag.

---

### 10. Resumo rápido

| Configuração               | Valor/Status                                   |
|---------------------------|------------------------------------------------|
| G-Sync                    | Ativado para modo tela cheia e janela          |
| V-Sync (driver NVIDIA)    | Ligado (fallback)                              |
| V-Sync (in-game)          | Desligado                                     |
| FPS limit (RTSS)          | 1-3 FPS abaixo do refresh do monitor           |
| Modo de exibição          | Tela cheia ou janela tela cheia (para alt-tab) |

---

### 11. Referências

- [Guru3D RTSS Download](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html)  
- [NVIDIA G-Sync](https://www.nvidia.com/en-us/geforce/news/gsync-ultimate-experience/)  
- [Como limitar FPS para G-Sync - Fórum NVIDIA](https://www.nvidia.com/en-us/geforce/forums/game-ready-drivers/13/3148/how-to-properly-cap-fps-for-g-sync/)

---
