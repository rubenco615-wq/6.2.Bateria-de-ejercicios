# 6.2.Bateria-de-ejercicios

EJERCICIO 1 
classDiagram
    class Usuario {
        -String nombreUsuario
        -String password
        +String correo
        +cambiarPassword(nueva : String) void
        -validarEmail() boolean
    }
    
