# Aprendiendo Markdown

Mis primeros *pasos* en **Markdown**, que es un formato de marcado de ***archivos de texto***.

A continuacion una ___lista___ :

* Item 1
* Item 2
    * Item 2.1
    * Item 2.2
* Item 3
    
A continuacion una __tabla__:

| Codigo | Nombre | Precio | 
| :-: | - | -: |
| 1 | TV | 553.99 |
| 2 | Computador | 1687.23 |
| 3 | Celular | 791.51 |

A continuacion un _enlace_ o *link*:

[Perro Pomerania](https://es.wikipedia.org/wiki/Pomerania_%28perro%29)

A continuacion una ___imagen___:

![Perro Pomeranian](https://static.wixstatic.com/media/d63eb2_4048d0005851490daeac79b6d28991b5~mv2.jpg/v1/fill/w_1000,h_667,al_c,q_85,usm_0.66_1.00_0.01/d63eb2_4048d0005851490daeac79b6d28991b5~mv2.jpg)

# Titulo de nivel 1
## Titulo nivel 2
### Titulo nivel 3

A continuacion el **codigo de un programa**:

    import java.util.Scanner;
    public class Saludo2 {
        public static void main (String[] args) {
            Scanner sc = new Scanner(System.in) ;
            String nombre;
            System.out.print("Dime tu nombre: ") ;
            nombre = sc.nextLine() ;
            System.out.print("Hola " + nombre) ;
            System.out.println(", encantado de conocerte!") ;
        }
    }

Fin