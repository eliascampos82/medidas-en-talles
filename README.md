# medidas-en-talles
ingresar unas medidas t te da un talle
#  talles
basado en sus medidas definiremos sus talles
El programa estara en el lenguaje de python creador del proyecto: Elias colaboreador: Joel_flores
#  las medidas de los talles
PECHO
PEXS_MIN = 82
PEXS_MAX = 90
PES_MIN = 91
PES_MAX = 98
PEM_MIN = 99
PEM_MAX = 106
PEL_MIN = 107
PEL_MAX = 114
PEXL_MIN = 115
PEXL_MAX = 123
PEXXL_MIN = 124
PEXXL_MAX = 135
PE3XL_MIN = 136
PE3XL_MAX = 147


CADERA
CAXS_MIN = 101
CAXS_MAX = 108
CAS_MIN = 109
CAS_MAX = 116
CAM_MIN = 117
CAM_MAX = 125
CAL_MIN = 126
CAL_MAX = 137
CAXL_MIN = 138
CAXL_MAX = 149
CAXXL_MIN = 150
CAXXL_MAX = 161
CA3XL_MIN = 162
CA3XL_MAX = 173

CINTURA
CIXS_MIN = 70
CIXS_MAX = 78
CIS_MIN = 79
CIS_MAX = 86
CIM_MIN = 87
CIM_MAX = 94
CIL_MIN = 95
CIL_MAX = 102
CIXL_MIN = 103
CIXL_MAX = 111
CIXXL_MIN = 112
CIXXL_MAX = 123
CI3XL_MIN = 124
CI3XL_MAX = 135

LARGO DEL BRAZO
LBXS_MIN = 55
LBXS_MAX = 61
LBS_MIN = 62
LBS_MAX = 63
LBM_MIN = 64
LBM_MAX = 65
LBL_MIN = 66
LBL_MAX = 67
LBXL_MIN = 68
LBXL_MAX = 69
LBXXL_MIN = 70
LBXXL_MAX = 71
LB3XL_MIN = 72
LB3XL_MAX = 73

ENTRE-PIERNA
ENXS_MIN = 55
ENXS_MAX = 80
ENS_MIN = 81
ENS_MAX = 84
ENM_MIN = 85
ENM_MAX = 88
ENL_MIN = 89
ENL_MAX = 92
ENXL_MIN = 93
ENXL_MAX = 96
ENXXL_MIN = 97
ENXXL_MAX = 100
EN3XL_MIN = 101
EN3XL_MAX = 120

 3  main.py 
@@ -7,6 +7,7 @@
TALLE_XXL = 5
TALLE_XXXL = 6
ESPECIAL = 7
#todas las funciones de los talles cumplen casi la misma función pero con distintas variables.
def  talle_pecho ():

    mientras es  cierto :
@@ -136,6 +137,7 @@ def talle_ldbrazo ():
    otra cosa :
        print ( "usted es un talle especial" )  
        imprimir ( ldbrazo )

def  talle_entrepierna ():
    mientras es  cierto :
        prueba :
@@ -171,6 +173,7 @@ def talle_entrepierna ():
def  ejecutar ():
    print ( 'Bienvenido !!! \ n ' )
    print ( 'Ingrese las medidas del equipo:' )
    #llamo a las funciones que me retornan el talle de cada parte del cuerpo
    talle_pecho ()
    talle_cadera ()
    talle_cintura ()
