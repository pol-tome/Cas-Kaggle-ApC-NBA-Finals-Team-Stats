# Cas-Kaggle-ApC-NBA-Finals-Team-Stats

# 🏀 Diccionario de Datos: NBA Finals Team Stats

Este documento describe las variables contenidas en el dataset de estadísticas de las finales de la NBA (1980-2018). Los datos incluyen métricas detalladas juego a juego tanto para el equipo campeón como para el subcampeón.

**Fuente del dataset:** [Kaggle - NBA Finals Team Stats](https://www.kaggle.com/datasets/daverosenman/nba-finals-team-stats)

---

## 📋 1. Información del Partido (Game Info)

Estas variables identifican el contexto del partido, quién jugó, cuándo y el resultado final.

| Variable | Nombre Completo | Descripción | Notas |
| :--- | :--- | :--- | :--- |
| **Year** | Year | Año en que se jugaron las finales. | Ej: 1996, 2016. |
| **Team** | Team Name | Nombre del equipo. | Ej: "Bulls", "Warriors". |
| **Game** | Game Number | Número de partido dentro de la serie. | Generalmente del 1 al 7. |
| **Win** | Win Result | Resultado del partido para el equipo. | `1` = Victoria <br> `0` = Derrota |
| **Home** | Home Court | Factor cancha / Localía. | `1` = Local (Home) <br> `0` = Visitante (Away) |
| **MP** | Minutes Played | Minutos totales jugados por el equipo. | Base = 240 (48 min x 5 jugadores). <br> >240 indica Prórroga (Overtime). |

## 🎯 2. Tiros y Anotación (Shooting & Scoring)

Estadísticas relacionadas con la eficiencia ofensiva y el volumen de tiro.

| Variable | Nombre Completo | Descripción |
| :--- | :--- | :--- |
| **FG** | Field Goals | Tiros de campo encestados (suma de 2 y 3 puntos). |
| **FGA** | Field Goal Attempts | Tiros de campo intentados totales. |
| **FGP** | Field Goal Percentage | Porcentaje de acierto en tiros de campo. |
| **TP** | Three Points | Tiros de 3 puntos (triples) encestados. |
| **TPA** | Three Point Attempts | Tiros de 3 puntos intentados. |
| **TPP** | Three Point Percentage | Porcentaje de acierto en triples. |
| **FT** | Free Throws | Tiros libres encestados. |
| **FTA** | Free Throw Attempts | Tiros libres intentados. |
| **FTP** | Free Throw Percentage | Porcentaje de acierto en tiros libres. |
| **PTS** | Points | Puntos totales anotados en el partido. |

## 🏀 3. Rebotes (Rebounding)

Control de los tableros.

| Variable | Nombre Completo | Descripción |
| :--- | :--- | :--- |
| **ORB** | Offensive Rebounds | Rebotes ofensivos (recuperados tras fallo propio). |
| **DRB** | Defensive Rebounds | Rebotes defensivos (recuperados tras fallo rival). |
| **TRB** | Total Rebounds | Suma total de rebotes (`ORB + DRB`). |

## 🛡️ 4. Juego y Defensa (Playmaking & Defense)

Otras métricas que miden la circulación de balón y la actividad defensiva.

| Variable | Nombre Completo | Descripción |
| :--- | :--- | :--- |
| **AST** | Assists | Asistencias (pases que llevan a canasta). |
| **STL** | Steals | Robos de balón. |
| **BLK** | Blocks | Tapones / Bloqueos realizados. |
| **TOV** | Turnovers | Pérdidas de balón. |
| **PF** | Personal Fouls | Faltas personales cometidas. |

---
*Documentación generada para análisis de datos de la NBA.*
