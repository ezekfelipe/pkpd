# pkpd
Calculadora de PkPd vanco H9J
{
  "type": "line",
  "title": {
    "text": "Ajuste de Dose de Vancomicina ao Longo dos Dias"
  },
  "series": [
    {
      "name": "Dose Administrada (mg)",
      "data": [1500, 1500, 1250, 1250, 1000, 1000],
      "mode": "lines+markers",
      "marker": {
        "size": 8,
        "color": "blue",
        "symbol": "circle"
      },
      "line": {
        "width": 2,
        "shape": "spline",
        "dash": "solid"
      },
      "fill": "none"
    }
  ],
  "categories": ["Dia 1", "Dia 2", "Dia 3", "Dia 4", "Dia 5", "Dia 6"]
}
