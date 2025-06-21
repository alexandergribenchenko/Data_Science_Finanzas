# Data Science - Finanzas

# 01. Créditos

# 01. Definiciín de tazas de interés
- TEA (Tasa efectiva anual): mas conocida enlos bancos como E.A. de efectivo anual.
- TEM (Tasa efectiva mensual): mas conocida en los bancos como M.V. de mes vencido. Es lo mismo que TEM, pero con el matiz de “vencido”.
- TED (Tasa efectiva diaria):

Cálculo de tasas de intres mensual y diaria a partir de la taza de interes anual:
```python
TEA = (1 + TEA)^(1/1) - 1  
TEM = (1 + TEA)^(1/12) - 1  
TED = (1 + TEA)^(1/365) - 1
```
