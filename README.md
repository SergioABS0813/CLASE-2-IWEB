# CLASE-2-IWEB

## Para imprimir un texto y luego dar un salto de línea se usa:
        System.out.println("Bienvenido a mi albergue");

## Para imprimir un texto y no quieres el salto de línea automático:
        System.out.print("Bienvenido a mi albergue");

## Creación de objeto
        Albergue albergue = new Albergue();
![iweb2](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/83eb0841-b71e-4dd8-819d-837760a6fc59)

## SCANNER :
        Scanner scanner = new Scanner(System.in);
        String opcionSeleccionada = scanner.nextLine();
La primera línea solo es necesaria para instanciar la clase Scanner, así que solo se haría una vez. La segunda línea es la que se usará más en caso se requiera de que el usuario coloque más datos.
## Convertimos de String a Integer
        int opcion = Integer.parseInt(opcionSeleccionada);

## Convertimos de String a Boolean
        boolean vacunadobool = Boolean.parseBoolean(vacunadoStr);
        
Solo cuando la variable que vamos a convertir sea TRUE o FALSE.

## MODULAMOS EL REGISTRO DE GATO CON UN MÉTODO AÑADIDO AL GATO

![iweb3](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/705156ba-f240-4e5e-8f5a-482b483d9a66)

Esto sirve para no sobrecargar la clase Main

## Cambiamos a "this" porque ya estamos en la misma clase
![iweb](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/9b1664ae-afd6-4bf5-9fd1-435bac5def48)

## SEGUNDA FORMA DE REGISTRAR DATOS
Los metodos estáticos pueden acceder solamente a atributos estáticos (static)

![a](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/9a9cb3da-7a35-4c8d-a8ed-3744852f3e23)

Recordemos que "nombre" es atributo no estático en este ejemplo

## Scanner.close()
        scanner.close();
        
Se coloca antes del final de cada programa

## CONSTRUCTOR

Creamos el constructor en la misma clase (sirve para inicializar variables):

![aa](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/010fb93c-d546-4dad-962b-d2bea7735d73)

Luego en el Main podemos inicializar los atributos de los objetos que creemos:

![aaa](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/a25b64ef-b723-424d-bf54-73544a8398ba)

OJO: ES IMPORTANTE CREAR EL CONSTRUCTOR SIN PARÁMETROS PARA QUE NO SE MALOGRE NUESTRO PROGRAMA:

![CONS](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/734d7aae-b3f8-4c68-8291-f0b178a15490)


## CONSTRUCTORES CON MÁS ATRIBUTOS INICIALIZADOS:
Si creamos muchos constructores, podría haber sobrecarga de constructores, por lo que podemos crear un constructor de más atributos iniciales:

![b](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/1bc5d6d5-c0b7-4e34-9ecd-f38294ebe649)

Luego en el Main pondriamos:

![bb](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/199a3622-ac07-420d-8ed6-71eed19f17e6)

OJO: ES IMPORTANTE CREAR EL CONSTRUCTOR SIN PARÁMETROS PARA QUE NO SE MALOGRE NUESTRO PROGRAMA:

![CONS](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/734d7aae-b3f8-4c68-8291-f0b178a15490)

## CLASES COMO ATRIBUTOS

![bb](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/ceaa7509-c4f0-4b3d-8c8e-bedccb278dc1)

Se puede utilizar esta forma para ir entrando de Afuera HACIA Adentro

## Cómo cambiar el atributo de una clase-atributo? (como cambiar ingrediente de galleta de morita?)

![ca](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/eb787641-6163-4020-8349-620ddd147d90)




