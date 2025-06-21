# Data Science - Finanzas

# 01. Créditos

# 01. Definición de tazas de interés
- %TEA (Tasa efectiva anual): mas conocida en los bancos como E.A. de efectivo anual.
- %TEM (Tasa efectiva mensual): mas conocida en los bancos como M.V. de mes vencido. Es lo mismo que TEM, pero con el matiz de “vencido”.
- %TED (Tasa efectiva diaria):

Cálculo de tasas de intres mensual y diaria a partir de la taza de interes anual:
```python
%TEA = [(1 + %TEA/100)^(1/1) - 1 ] * 100
%TEM = [(1 + %TEA/100)^(1/12) - 1] * 100 
%TED = [(1 + %TEA/100)^(1/365) - 1] * 100
```

Cálculo de la tasa de intres anual a partir de la tazas de interes diaria y mensual:
```python
%TEA = [(1 + %TEA/100)^1 - 1 ] * 100
%TEM = [(1 + %TEA/100)^12 - 1] * 100 
%TED = [(1 + %TEA/100)^365 - 1] * 100
```

