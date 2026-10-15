# Cálculo de Área — Actividad 3: Enfoque Modular y Diseño Top-Down

**Materia:** LPR — 5° Año 3° División A-B | **Prof.:** Prof. Mansilla Muñoz York Elías | **Est.:** Aramis Demaria

## Objetivo
Calcular el área de un círculo con diseño modular (prototipo + definición) y constante protegida `const double PI`.

## Estructura
```
/calculoarea/
├── .gitignore
├── LICENSE
├── README.md
├── docs/InformeProyectoCALCULOAREA.pdf
├── src/main.cpp
└── capturas/
    ├── compilacion_area.png
    └── diagrama_flujo.png
```

## Fórmula
`área = π × r²` con `π = 3.1415926535` (const).

## Comandos
```powershell
g++ src/main.cpp -o src/area.exe
.\src\area.exe
```
Filtro: radio > 0. Diana ASCII según tamaño.
