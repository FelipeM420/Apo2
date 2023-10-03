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

java : lenguaje de codigo utilizado para programacion.
eclipse - enlanzado con java.

## Versionado

control de verion del programa eclipse es de 2023-09 (4.29)​ (info) ( 12 de septiembre de 2023)

## Autores

* **Sebastian Moreno** 


## Licencia

La Licencia Pública de Eclipse está diseñado para ser una licencia de software favorable a los negocios y cuenta con disposiciones más débiles que las licencias copyleft contemporáneas, como la Licencia Pública General de GNU (GPL). El receptor de programas licenciados EPL pueden utilizar, modificar, copiar y distribuir el trabajo y las versiones modificadas, en algunos casos están obligados a liberar sus propios cambios.

## Expresiones de gratitud (Acknowledgments)

* un buen proyecto para aprender las funciones con el tema a la programacion
* Inspirado de un taller educativo de apo 2.

