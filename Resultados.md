# Resutlados 

## Función periodicidad
    Lista: [2, 3, 4, 9, 10, 16, 2, 3, 4]
    Periocidad: 7
    Valores faltantes: [0, 1, 5, 6, 7, 8, 11, 12, 13, 14, 15]

## Función generador congruencial mixto
    Parametros: seed=4, limit=8, a=5, c=7, m=8
    Lista: [3, 6, 5, 0, 7, 2, 1, 4]

## Función generadir congruencial multiplicativo
    Parametros: seed=4, limit=8, a=5, m=39
    Lista: [20, 22, 32, 4, 20, 22, 32, 4]

## Actividades
    2. Determine el periodo de los siguientes generadores mixtos
        * a = 8, c = 16, m = 100, x_0 = 15
        * a = 50, c = 17, m = 64, x_0 = 13
        * a = 9, c = 13, m = 32, x_0 = 8

    Generador_Mixto-1: a = 8, c = 16, m = 100, x_0 = 15
    Lista generada: [36, 4, 48, 0, 16, 44, 68, 60, 96, 84, 88, 20, 76, 24, 8, 80, 56, 64, 28, 40, 36, 4, 48, 0, 16, 44, 68, 60, 96, 84, 88, 20, 76, 24, 8, 80, 56, 64, 28, 40, 36, 4, 48, 0, 16, 44, 68, 60, 96, 84, 88, 20, 76, 24, 8, 80, 56, 64, 28, 40, 36, 4, 48, 0, 16, 44, 68, 60, 96, 84, 88, 20, 76, 24, 8, 80, 56, 64, 28, 40, 36, 4, 48, 0, 16, 44, 68, 60, 96, 84, 88, 20, 76, 24, 8, 80, 56, 64, 28, 40]
    Periocidad: 21

    Generador_Mixto-2: a = 50, c = 17, m = 64, x_0 = 13
    Lista generada: [27, 23, 15, 63, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31, 31]
    Periocidad: 6

    Generador_Mixto-3: a = 9, c = 13, m = 32, x_0 = 8
    Lista generada: [21, 10, 7, 12, 25, 14, 11, 16, 29, 18, 15, 20, 1, 22, 19, 24, 5, 26, 23, 28, 9, 30, 27, 0, 13, 2, 31, 4, 17, 6, 3, 8]
    Periocidad: 32

    3. Determine el periodo de los siguientes generadores multiplicativos
        * a = 203, m = 10^5, x_0 = 17
        * a = 221, m = 10^3, x_0 = 3
        * a = 5, m = 64, x_0 = 7

    Generador_Multiplicativo-1: a = 203, m = 10^5, x_0 = 17
    Lista generada: [1, 8, 4, 2, 1, 8, 4, 2, 1, 8, 4, 2, 1, 8, 4]
    Periocidad: 5

    Generador_Multiplicativo-2: a = 221, m = 10^3, x_0 = 3
    Lista generada: [6, 3, 6, 3, 6, 3, 6, 3, 6]
    Periocidad: 3

    Generador_Multiplicativo-3: a = 5, m = 64, x_0 = 7
    Lista generada: [35, 47, 43, 23, 51, 63, 59, 39, 3, 15, 11, 55, 19, 31, 27, 7, 35, 47, 43, 23, 51, 63, 59, 39, 3, 15, 11, 55, 19, 31, 27, 7, 35, 47, 43, 23, 51, 63, 59, 39, 3, 15, 11, 55, 19, 31, 27, 7, 35, 47, 43, 23, 51, 63, 59, 39, 3, 15, 11, 55, 19, 31, 27, 7]
    Periocidad: 17