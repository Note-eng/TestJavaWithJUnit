# UnitTesting

modelo de soma para ser testado, codigo dentro de `src/Calculadora.java`
```java
    public double somar( int n1, int n2 ){
        resultado = n1 + n2;
        return resultado;
```
----
modelo para testar a soma, codigo dentro de `src/CalculadoraTest.java`
```java
public void testSomar() {
        System.out.println("somar");
        int n1 = 5;
        int n2 = 5;
        Calculadora instance = new Calculadora();
        double expResult = 10.0;
        double result = instance.somar(n1, n2);
        assertEquals(expResult, result, 0);
    }
```

Resultado: <br>
![image](https://user-images.githubusercontent.com/64230498/187518293-81b6b93b-ffc9-4400-b2f8-be4ee788ae7a.png)
