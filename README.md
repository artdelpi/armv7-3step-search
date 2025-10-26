<h1 align="center">Lena-3Step-SAD-ARMv7</h1>

<p align="center">
  <em>Three-Step Search (8→4→2) com SAD para localizar blocos 8×8 na Lena 64×64 no CPUlator</em>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Assembly-ARMv7-6E4C13?style=for-the-badge" alt="ARMv7 ASM"></a>
  <a href="#"><img src="https://img.shields.io/badge/Platform-CPUlator-0A7CFF?style=for-the-badge" alt="CPUlator"></a>

</p>

---

## Overview
Implementação em **ARMv7** do **Three-Step Search (8→4→2)** com métrica **SAD** para localizar blocos **8×8** na imagem **Lena 64×64**. Desenha no VGA (RGB565) e marca **blocoA** (branco), **resultado do blocoB** (vermelho) e **gabarito do blocoB** (azul).

## Arquivo principal
- `busca3p_sad.s` — rotinas `sad`, `busca3p`, desenho no VGA e `main`.

## Como executar (CPUlator)
1. Abra o **CPUlator** (ARMv7 DE1-SoC) e cole `motion_3step_sad_armv7.s`.
2. Monte e rode. A Lena e os contornos aparecerão no VGA.
