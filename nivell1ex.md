# Spring framework

![Spring Framework](spring.png)

L'**Spring framework** és un marc de treball de ```codi obert per la plataforma Java.``` La primera versió va ser escrita per Rod Johnson, que inicialment va llençar el producte juntament amb el llibre _One-on-One Java EE Design and Development_.També hi ha un port disponible per la plataforma [.NET](https://ca.wikipedia.org/wiki/Microsoft_.NET), Spring.NET.

## Funcionalitats clau

- Gestió de la configuració basada en [JavaBeans](https://ca.wikipedia.org/wiki/JavaBeans).
- Una _factoria de Beans central_, que és usada globalment.
- Capa genèrica d'abstracció per la gestió de transaccions de la base de dades.
- Estratègies preincorporades per la **JTA** i un sol DataSource de **JDBC**.
- ntegració amb entorns de persistència com **Hibernate**, **JDO**, **iBatis** i **db4o**.
- Entorn d'aplicació web [MVC](https://ca.wikipedia.org/wiki/Model-Vista-Controlador), construït al nucli de la funcionalitat de Spring. 
- Entorn extensiu de _programació orientada a aspectes_ per proveir serveis, com ara ```gestió de les transaccions```.


## Mòduls de l'Spring Framework

1. Contenidor d'Inversió de Control
2. Entorn de **Programació orientada a aspectes** 
3. Entorn d'accés a les _dades_
4. Entorn de gestió de transaccions
5. Entorn ```model-vista-controlador```
6. Entorn d'accés remot
7. Entorn d'autenticació i personalització
8. Entorn de missatgeria
9. Entorn de **testeig**

## Codi

Un codi sencill sería el següent:

```java
class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!"); 
    }
}
```
El resultat sería:
```
Hello, World!
```  



També es pot mostrar el resultat d'una operació

```java
class HelloWorld {
    public static void main(String[] args) {
        var a = 2;
        var b = 4;
        var result = a + b;
        System.out.println(result);
    }
}
```
El resultat sería:
```
6
```