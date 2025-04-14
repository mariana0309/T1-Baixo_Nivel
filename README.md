# T1-Baixo_Nivel
# 🖼️ Editor de Imagens PPM em C

Este programa é um editor de imagens simples em linguagem C, que trabalha com arquivos de imagem no formato **PPM (P3)**. Ele permite aplicar diversos filtros e transformações em uma imagem carregada, gerando novas imagens com os efeitos desejados.

---

## 📂 Formato Suportado

- Apenas imagens no formato **PPM (P3)**.
- O arquivo de entrada deve se chamar `imagem.ppm` e estar no mesmo diretório do executável.

---

## ⚙️ Funcionalidades

O programa possui um menu interativo com as seguintes opções:

| Opção | Descrição                                 | Saída Gerada               |
|-------|-------------------------------------------|----------------------------|
| 1     | Converter para tons de cinza              | `imagemCinza.png`         |
| 2     | Aplicar filtro negativo                   | `imagemNegativa.png`      |
| 3     | Aplicar efeito raio-X                     | `imagemRaioX.png`         |
| 4     | Aplicar efeito envelhecido (sépia)        | `imagemEnvelhecida.png`   |
| 5     | Rotacionar imagem em 90 graus             | `imagem90.png`            |
| 6     | Rotacionar imagem em 180 graus            | `imagem180.png`           |
| 0     | Encerrar o programa                       | -                          |

---

## 🖥️ Como Executar

### 1. Compile o código:

```bash
gcc -o editorImagem editorImagem.c -lm
