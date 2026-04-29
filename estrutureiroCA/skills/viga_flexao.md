# Skill: Flexão simples em viga retangular

## Hipóteses

- Seção retangular

---

## Constantes padrão

Usar os seguintes valores fixos, salvo se o usuário informar explicitamente outro valor:

gamma_f = 1.4
gamma_c = 1.4
gamma_s = 1.15

---

## Unidades

- Mk em kN·m
- bw, h, d em cm
- fck, fyk em MPa
- As em cm²

---

## Fórmulas

Md = gamma_f × Mk

fcd = fck / gamma_c
fyd = fyk / gamma_s

---

## Regras de coeficientes

1. Se gamma_f não for informado, usar 1.4
2. Se gamma_c não for informado, usar 1.4
3. Se gamma_s não for informado, usar 1.15
4. Informar na saída os valores adotados

---

## Regra de consistência

Antes de qualquer cálculo:

- Garantir que Mk está em kN·m
- Garantir que fck e fyk estão em MPa
- Não converter unidades automaticamente
- Se houver inconsistência, solicitar correção ao usuário

---

## Ordem obrigatória

A IA DEVE seguir exatamente:

1. Definir gamma_f, gamma_c e gamma_s
2. Calcular Md
3. Calcular fcd
4. Calcular fyd
5. 
