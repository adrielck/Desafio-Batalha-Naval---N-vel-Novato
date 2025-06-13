# 🚢 Desafio Batalha Naval - Nível Novato

Este repositório contém a solução do **Desafio Batalha Naval - Nível Novato**, desenvolvido em linguagem C. O objetivo foi implementar a lógica de posicionamento de navios em um tabuleiro utilizando uma matriz bidimensional.

## 📋 Descrição do Desafio

No nível Novato do desafio, o foco está em:
- Criar um tabuleiro 5x5 com matriz bidimensional.
- Posicionar dois navios:
  - Um navio **horizontal** com 3 posições.
  - Um navio **vertical** com 2 posições.
- Exibir no console as **coordenadas de cada parte dos navios** com `printf`.

## 💡 O que foi feito

- Utilizei uma matriz `int tabuleiro[5][5]` para representar o campo de batalha.
- Os navios foram posicionados manualmente em coordenadas pré-definidas.
- As coordenadas foram impressas de forma clara e organizada no console.

## 🛠️ Tecnologias

- Linguagem: C
- Compilador recomendado: GCC

## ▶️ Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/adrielck/desafio-batalha-naval-nivel-novato.git
   ```

2. Compile o código:
   ```bash
   gcc batalha_naval.c -o batalha_naval
   ```

3. Execute:
   ```bash
   ./batalha_naval
   ```

## 📌 Exemplo de Saída

```
Coordenadas do navio horizontal:
(1, 0)
(1, 1)
(1, 2)

Coordenadas do navio vertical:
(2, 3)
(3, 3)
```

## 📚 Próximos passos

- [ ] Nível Aventureiro: simular tiros e identificar acertos ou erros.
- [ ] Nível Mestre: adicionar interação do jogador e posicionamento automático.

## ✍️ Autor

Desenvolvido por [Adriel Cardoso](https://github.com/adrielck)
