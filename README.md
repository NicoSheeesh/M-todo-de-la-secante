# Método de la Secante -- README

Este repositorio contiene la plantilla en Excel para resolver ecuaciones
mediante el **método de la secante**, así como instrucciones para
completar la actividad.

------------------------------------------------------------------------

##  Contenido del repositorio

-   **plantilla_secante.xlsx**\
    Archivo en Excel con columnas estructuradas para:
    -   Iteración\
    -   x_prev\
    -   x\
    -   f(x_prev)\
    -   f(x)\
    -   x_next\
    -   error

------------------------------------------------------------------------

##  Fórmulas recomendadas (Excel en español)

### f(x)

    =LN(C2)-2*C2+3

### f(x_prev)

    =LN(B2)-2*B2+3

### x_next (método de la secante)

    =SI(E2-D2=0; NA(); C2 - E2*(C2-B2)/(E2-D2))

### error

    =ABS(F2-C2)

------------------------------------------------------------------------

## ✔ Pasos para usar la plantilla

1.  Ingrese los valores iniciales en **x_prev** y **x**.
2.  Copie las fórmulas tal como están descritas.
3.  Arrastre hacia abajo para generar las iteraciones.
4.  Deténgase cuando **error → 0** o deje de cambiar significativamente.

------------------------------------------------------------------------

## ✔ Herramientas sugeridas

-   **Excel**
-   **Google Sheets**
-   Alternativas recomendadas:
    -   GeoGebra CAS
    -   WolframAlpha (versión web)
    -   Octave / Matlab

------------------------------------------------------------------------

##  Subida del trabajo

1.  Complete los cuatro ejercicios.
2.  Exporte los resultados en PDF (si su docente lo solicita).
3.  Suba los archivos finales a GitHub y a la plataforma institucional.

------------------------------------------------------------------------

##  Autor

Estudiante de Ingeniería de Software -- Universidad de Santander (UDES)

------------------------------------------------------------------------

¡Mucho éxito! 
