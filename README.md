

Durante este ejercicio se aplicaron los siguientes principios de diseño:

# Single Responsibility Principle (SRP): - Carolina

# Open/Closed Principle (OCP):  

Este principio indica que las clases deberían estar abiertas para poder extenderse y cerradas para modificarse.

Dentro del ejercicio se aplica este principio en la clase cargarCombustible, ya que cualquier tipo de vehículo sin la necesidad de hacer modificaciones a la clase, puede hacer uso de esta al implementar la interfaz vehiculoCombustible y heredar la clase Vehículo.

# Interface Segregation Principle (ISP) :

Este principio consiste en que ninguna clase debería depender de métodos que no son utilizados por ella, por esto en la clase CargarCombustible define un comportamiento unico para los vehiculos el cual es cargar combustible sin que ello represente un metodo que no va a ser utilizado por los vehiculos


# KISS (Keep It Simple, Stupid):

Este principio consiste en que basicamente el código debe ser lo mas simple posible ningun patron o principio discute o va en contra de la simplicidad si algo se puede solucionar de la forma mas simple esta es la mejor manera de hacerlo y por ende se debe mantener asi, por eso aqui quisismos implementar de la manera mas simple estos principios donde cargar combustible es propio de todos los vehiculos,pero cada tipo de vehiculo maneja su particularidad (ejes o turbinas).
