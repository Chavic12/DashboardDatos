| #  | Column                | Non-Null Count | Dtype   | Descripción                                                        |
|----|-----------------------|----------------|---------|--------------------------------------------------------------------|
| 0  | Unnamed: 0            | 17981          | int64   | Índice de la fila                                                  |
| 1  | Name                  | 17981          | object  | Nombre del jugador                                                 |
| 2  | Age                   | 17981          | int64   | Edad del jugador                                                   |
| 3  | Photo                 | 17981          | object  | URL de la foto del jugador                                         |
| 4  | Nationality           | 17981          | object  | Nacionalidad del jugador                                           |
| 5  | Flag                  | 17981          | object  | URL de la bandera de la nacionalidad del jugador                   |
| 6  | Overall               | 17981          | int64   | Puntuación general del jugador                                     |
| 7  | Potential             | 17981          | int64   | Potencial del jugador                                              |
| 8  | Club                  | 17733          | object  | Nombre del club del jugador                                        |
| 9  | Club Logo             | 17981          | object  | URL del logo del club                                              |
| 10 | Value                 | 17981          | object  | Valor del jugador (en formato string)                              |
| 11 | Wage                  | 17981          | object  | Salario del jugador (en formato string)                            |
| 12 | Special               | 17981          | int64   | Habilidad especial del jugador                                     |
| 13 | Acceleration          | 17981          | object  | Aceleración del jugador                                            |
| 14 | Aggression            | 17981          | object  | Agresividad del jugador                                            |
| 15 | Agility               | 17981          | object  | Agilidad del jugador                                               |
| 16 | Balance               | 17981          | object  | Balance del jugador                                                |
| 17 | Ball control          | 17981          | object  | Control del balón del jugador                                      |
| 18 | Composure             | 17981          | object  | Compostura del jugador                                             |
| 19 | Crossing              | 17981          | object  | Cruces del jugador                                                 |
| 20 | Curve                 | 17981          | object  | Curva del jugador                                                  |
| 21 | Dribbling             | 17981          | object  | Regate del jugador                                                 |
| 22 | Finishing             | 17981          | object  | Definición del jugador                                             |
| 23 | Free kick accuracy    | 17981          | object  | Precisión en tiros libres del jugador                              |
| 24 | GK diving             | 17981          | object  | Habilidad de parada en salto del portero                           |
| 25 | GK handling           | 17981          | object  | Habilidad de manejo del portero                                    |
| 26 | GK kicking            | 17981          | object  | Habilidad de pateo del portero                                     |
| 27 | GK positioning        | 17981          | object  | Posicionamiento del portero                                        |
| 28 | GK reflexes           | 17981          | object  | Reflejos del portero                                               |
| 29 | Heading accuracy      | 17981          | object  | Precisión en cabezazos del jugador                                 |
| 30 | Interceptions         | 17981          | object  | Intercepciones del jugador                                         |
| 31 | Jumping               | 17981          | object  | Capacidad de salto del jugador                                     |
| 32 | Long passing          | 17981          | object  | Pases largos del jugador                                           |
| 33 | Long shots            | 17981          | object  | Tiros largos del jugador                                           |
| 34 | Marking               | 17981          | object  | Marcaje del jugador                                                |
| 35 | Penalties             | 17981          | object  | Penalizaciones del jugador                                         |
| 36 | Positioning           | 17981          | object  | Posicionamiento del jugador                                        |
| 37 | Reactions             | 17981          | object  | Reacciones del jugador                                             |
| 38 | Short passing         | 17981          | object  | Pases cortos del jugador                                           |
| 39 | Shot power            | 17981          | object  | Potencia de tiro del jugador                                       |
| 40 | Sliding tackle        | 17981          | object  | Entrada deslizante del jugador                                     |
| 41 | Sprint speed          | 17981          | object  | Velocidad de sprint del jugador                                    |
| 42 | Stamina               | 17981          | object  | Resistencia del jugador                                            |
| 43 | Standing tackle       | 17981          | object  | Entrada de pie del jugador                                         |
| 44 | Strength              | 17981          | object  | Fuerza del jugador                                                 |
| 45 | Vision                | 17981          | object  | Visión del jugador                                                 |
| 46 | Volleys               | 17981          | object  | Voleas del jugador                                                 |
| 47 | CAM                   | 15952          | float64 | Habilidad del jugador como mediapunta central. CAM significa "Centrocampista Ofensivo" en la posición central.                     |
| 48 | CB                    | 15952          | float64 | Habilidad del jugador como defensa central. CB significa "Defensa Central".                         |
| 49 | CDM                   | 15952          | float64 | Habilidad del jugador como mediocentro defensivo. CDM significa "Centrocampista Defensivo" en la posición central.                   |
| 50 | CF                    | 15952          | float64 | Habilidad del jugador como delantero centro. CF significa "Centro delantero".                        |
| 51 | CM                    | 15952          | float64 | Habilidad del jugador como mediocentro. CM significa "Centrocampista" en la posición central.                             |
| 52 | ID                    | 17981          | int64   | Identificador del jugador                                          |
| 53 | LAM                   | 15952          | float64 | Habilidad del jugador como mediapunta izquierdo. LAM significa "Mediapunta Izquierdo".                   |
| 54 | LB                    | 15952          | float64 | Habilidad del jugador como lateral izquierdo. LB significa "Lateral Izquierdo".                      |
| 55 | LCB                   | 15952          | float64 | Habilidad del jugador como defensa central izquierdo. LCB significa "Defensa Central Izquierdo".               |
| 56 | LCM                   | 15952          | float64 | Habilidad del jugador como mediocentro izquierdo. LCM significa "Centrocampista Izquierdo" en la posición central.                   |
| 57 | LDM                   | 15952          | float64 | Habilidad del jugador como mediocentro defensivo izquierdo. LDM significa "Centrocampista Defensivo Izquierdo" en la posición central.         |
| 58 | LF                    | 15952          | float64 | Habilidad del jugador como extremo izquierdo. LF significa "Extremo Izquierdo".                       |
| 59 | LM                    | 15952          | float64 | Habilidad del jugador como mediocampista izquierdo. LM significa "Mediocampista Izquierdo".                     |
| 60 | LS                    | 15952          | float64 | Habilidad del jugador como delantero izquierdo. LS significa "Delantero Izquierdo".                     |
| 61 | LW                    | 15952          | float64 | Habilidad del jugador como extremo izquierdo. LW significa "Extremo Izquierdo".                        |
| 62 | LWB                   | 15952          | float64 | Habilidad del jugador como carrilero izquierdo. LWB significa "Carrilero Izquierdo".                     |
| 63 | Preferred Positions   | 17981          | object  | Posiciones preferidas del jugador, indicando las posiciones en las que prefiere jugar.                |
| 64 | RAM                   | 15952          | float64 | Habilidad del jugador como mediapunta derecho. RAM significa "Mediapunta Derecho".                      |
| 65 | RB                    | 15952          | float64 | Habilidad del jugador como lateral derecho. RB significa "Lateral Derecho".                         |
| 66 | RCB                   | 15952          | float64 | Habilidad del jugador como defensa central derecho. RCB significa "Defensa Central Derecho".                 |
| 67 | RCM                   | 15952          | float64 | Habilidad del jugador como mediocentro derecho. RCM significa "Centrocampista Derecho" en la posición central.                |
| 68 | RDM                   | 15952          | float64 | Habilidad del jugador como mediocentro defensivo derecho. RDM significa "Centrocampista Defensivo Derecho" en la posición central.          |
| 69 | RF                    | 15952          | float64 | Habilidad del jugador como extremo derecho. RF significa "Extremo Derecho".                         |
| 70 | RM                    | 15952          | float64 | Habilidad del jugador como mediocampista derecho. RM significa "Mediocampista Derecho".                    |
| 71 | RS                    | 15952          | float64 | Habilidad del jugador como delantero derecho. RS significa "Delantero Derecho".                        |
| 72 | RW                    | 15952          | float64 | Habilidad del jugador como extremo derecho. RW significa "Extremo Derecho".                          |
| 73 | RWB                   | 15952          | float64 | Habilidad del jugador como carrilero derecho. RWB significa "Carrilero Derecho".                        |
| 74 | ST                    | 15952          | float64 | Habilidad del jugador como delantero. ST significa "Delantero".                                  |