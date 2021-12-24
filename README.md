<p align="center">
    <img src="https://github.com/GeeksHubsAcademy/2020-geekshubs-media/blob/master/image/logo.png" >	
</p>


    Considere el siguiente problema:

    Escriba un programa corto que imprima un rango de números del 1 a N.

    Para cada múltiplo de 3, imprima "Geeks" en lugar del número.
    Para cada múltiplo de 5, imprima "Hubs" en lugar del número.
    Para los números que son múltiplos de 3 y 5, imprima "GeeksHubs" en lugar del número.
    Cada número debe de estar en una línea nueva.
    El resultado se debe de ser una string.
    
    Se atiende al siguiente ejemplo:

    Iterador 3
    1
    2
    Geeks

    Iterador 7
    1
    2
    Geeks
    4
    Hubs
    Geeks
    7

    Iterador 16
    1
    2
    Geeks
    4
    Hubs
    Geeks
    7
    8
    Geeks
    Hubs
    11
    Geeks
    13
    14
    GeeksHubs
    16
    


    En la carpeta 'tests/test_kata.js' se encuentra el fichero con la definición de nuestro método vacío.
    
    El modus operandi de trabajo es el siguiente:
    
    Debes 'forkear' el proyecto a tu cuenta.
    Puedes hacer PR's ilimitadas e ir validando poco a poco la solución contra nuestro respositorio con CI.
    Puedes trabajar en local y subir la solución haciendo un PR a nuestro repositorio.
    Cuando se envíe la PR final, debes indicar el tiempo de dedicación y los intentos que has hecho.
    También puedes añadir un comentario para dar cualquier tipo de feedback.
    
    En caso de duda, revisa en el apartado de 'Referencias'.
    
    Ejecución en local :
        - python -m pytest -vv tests/test_kata.py

    A continuación se muestran los resultado que se tienen que obtener tras desarrollar el algoritmo.
    
    def test_apply_3(self):
        expected = "1\n2\nGeeks\n"
        assert(apply(3) == expected)

    def test_apply_30(self):
        expected = "1\n2\nGeeks\n4\nHubs\nGeeks\n7\n8\nGeeks\nHubs\n11\nGeeks\n13\n14\nGeeksHubs...."
        assert(apply(30) == expected)

    def test_apply_60(self):
        expected = "1\n2\nGeeks\n4\nHubs\nGeeks\n7\n8\nGeeks\nHubs\n11\nGeeks\n13\n14\nGeeksHubs...."
        assert(apply(60) == expected)

    def test_apply_100(self):
        expected = "1\n2\nGeeks\n4\nHubs\nGeeks\n7\n8\nGeeks\nHubs\n11\nGeeks\n13\n14\nGeeksHubs...."
        assert(apply(100) == expected)


        collected 4 items                                                                                                               

        tests/test_kata.py::Test_kata::test_apply_100 PASSED                                                                     [ 25%]
        tests/test_kata.py::Test_kata::test_apply_3 PASSED                                                                       [ 50%] 
        tests/test_kata.py::Test_kata::test_apply_30 PASSED                                                                      [ 75%] 
        tests/test_kata.py::Test_kata::test_apply_60 PASSED                                                                      [100%] 

        ====================================================== 4 passed in 0.03s ====================================================== 
    
    
## Referencias

* [Tutorial - Testing Automatizado](https://github.com/GeeksHubsAcademy/2020-js-vanilla-testing-FFFF/blob/master/README.md)

