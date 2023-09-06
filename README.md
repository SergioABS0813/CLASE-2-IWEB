# CLASE-2-IWEB

## Para imprimir un texto y luego dar un salto de línea se usa:
        System.out.println("Bienvenido a mi albergue");

## Para imprimir un texto y no quieres el salto de línea automático:
        System.out.print("Bienvenido a mi albergue");

## Creación de objeto
        Albergue albergue = new Albergue();
![iweb2](https://github.com/SergioABS0813/CLASE-2-IWEB/assets/134556600/83eb0841-b71e-4dd8-819d-837760a6fc59)

## PARA QUE EL USUARIO INGRESE DATOS:
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



