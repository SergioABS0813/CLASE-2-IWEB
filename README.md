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
## Para pasar de String a Int
        int opcion = Integer.parseInt(opcionSeleccionada);
        
