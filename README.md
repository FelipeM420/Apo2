![Logo Java](https://seeklogo.com/images/J/java-logo-7833D1D21A-seeklogo.com.png))

# Cálculo del Factorial

Se necesita crear un programa en Java que permita al usuario calcular el factorial de un número entero positivo.
Utiliza condicionales, ciclos y funciones para lograrlo.

## Empezando

Se rea una función llamada calcularFactorial que tome un número entero positivo como parámetro y devuelva
su factorial.

### Requisitos previos
1. Uso de JOption Pane para ingreso y muestra de datos
2. Cumplimiento de los requisitos funcionales


```
examples
  1. int j = Integer.parseInt(JOptionPane.showInputDialog(null, "Ingrese un numero", "NUMERO FACTORIAL", 3));


2.  public static int fac (int j) {
			int res = 1;
			for (int i = 1; i<=j; i++) {
				res = res*i; 
```

### Instalación
Se toma un número entero positivo como parámetro y devuelva
su factorial y en el programa principal, utiliza un bucle para permitir que el usuario realice múltiples cálculos de factoriales.
Solicita al usuario que ingrese un número entero positivo y garantice que la entrada sea válida.
Utiliza la función calcularFactorial para calcular el factorial del número ingresado.


```
int num = 1;
while (num != 2) {
            if (num == 1) {
                int j = Integer.parseInt(JOptionPane.showInputDialog(null, "Ingrese un numero", "NUMERO FACTORIAL", 3));

                if (j > 0) {
                    int res1 = fac(j);
                    JOptionPane.showMessageDialog(null, "El factorial de " + j + " es " + res1);
                }
else {
 JOptionPane.showMessageDialog(null, "El número está fuera de alcance. Ingresa un número positivo.");
}
```

Para saber si un numero esta fuera del rango entre 1 y 2 se aplica un mensaje que diga que realmente se debe escoger entre esos dos numeros.

```
else {
JOptionPane.showMessageDialog(null, "Debes escoger solo entre 1 y 2.");
 }
```


### Prueba para digitar si quiere continuar o quiere salir del programa.

para este ejemplo se necesita aplicar un mensaje donde se pueda digitar entre el numero uno (que es para continuar con otro numero factorial) y numero 2 (sirve para salir del programa)

```
  num = Integer.parseInt(JOptionPane.showInputDialog(null, "¿Qué número deseas digitar?\n1. Continuar\n2. Salir"));
        }

JOptionPane.showMessageDialog(null, "¡Hasta luego!");
    }
```

## Metodo funcional

como se conocio anteriormente, para este codigo se necesita de un metodo llamado funciones que sirve para desplegar todo el codigo y ejecutar el numero factorial.

```
}
		public static int fac (int j) {
			int res = 1;
			for (int i = 1; i<=j; i++) {
				res = res*i; 
			}
			return res;
		
   }
}
```

## Construido con

Dropwizard : el marco web utilizado
Maven - Gestión de dependencias
ROMA : se utiliza para generar canales RSS

## Versionado

Usamos Git para el control de versiones. Para conocer las versiones disponibles, consulte las etiquetas en este repositorio .

## Autores

* **Gustavo Sánchez** 


## Licencia

Este proyecto tiene la licencia MIT; consulte el archivo LICENSE.md para obtener más detalles.

## Expresiones de gratitud (Acknowledgments)

* Un consejo para cualquiera cuyo código se haya utilizado
* Inspiración
* etc
