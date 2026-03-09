![GitHub License](https://img.shields.io/github/license/wilmeryf/lab-redes-01)

# Laboratório de Redes 01 - Projeto de Rede Local

**Aluno:** Anderson Wilmer Yapiticona Flores  
**Professor:** José de Assis  
**Data:** 09/03/2026

---

## 1. Objetivo
Implementar uma rede local simples conectando 3 notebooks a um roteador wireless com switch e uma impressora de rede.

O projeto será dividido em duas etapas:

1. Simulação da rede no Cisco Packet Tracer
2. Implementação da rede no laboratório real

---

## 2. Equipamentos utilizados neste laboratório:

- 3 notebooks
- 1 roteador wireless com 1 porta WAN e 4 portas LAN
- 1 impressora de rede
- cabos de rede

---

## 3. Topologia da Rede

Diagrama lógico da rede usada neste laboratório.

```mermaid
graph TD

WAN[Internet / WAN do provedor]

Router[Roteador Wireless <br> 1 Porta WAN <br> 4 Portas LAN]

PC1[Notebook 1]
PC2[Notebook 2]
PC3[Notebook 3]

Printer[Impressora de Rede]

WAN --> |Porta WAN| Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3
Router --> |LAN 4| Printer
```
Imagem da topologia usada neste laboratório:
!topologia]()
