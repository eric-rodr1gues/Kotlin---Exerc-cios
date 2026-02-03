# Kotlin - Exercícios

---

## Exercício 1. Fahrenheit 🌡️
```
fun main() {
    var entrada_celsius = 20
    val F = entrada_celsius * 9/5 + 32
    print(F)
}
```
---

## Exercício 2. Celsius 🌡️
```
fun main() {
    var entrada_fahrenheit = 40
    val C = (entrada_fahrenheit - 32) * 5/9
    print(C)
}
```

---

## Exercício 3. Volume 🥫
```
fun main() {
    var raio = 5.0
    var altura = 10
    val volume = 3.14 * (Math.pow(raio, 2.0) * altura)
    print(volume)
}
```

---

## Exercício 4. Combustível ⛽
```
fun main() {
    var km = 240
    var km_L = 12
    val gasto_combustivel = km / km_L
    print(gasto_combustivel)
}
```

---

## Exercício 5. Prestação 💸
```
fun main() {
    var valor_original = 1000.0
    var meses_atraso = 3.0
    var taxa_juros = 1.0
    val valor = valor_original * (1.0 + (taxa_juros / 100.0) * meses_atraso)
    print(valor)
}
```

---

## Exercício 6. Troca de Variáveis 🔛
```
fun main() {
    var A = 5
    var B = 10
    var troca = A
    A = B
    B = troca
    print("A: $A, B: $B")
}

```

---

## Exercício 7. Adição e Multiplicação ➕❌
```
fun main() {
    var n1 = 1
    var n2 = 2
    var n3 = 3
    var n4 = 4
    
    val s1 = n1 + n2
    val s2 = n1 + n3
    val s3 = n1 + n4
    val s4 = n2 + n3
    val s5 = n2 + n4
    val s6 = n3 + n4
    
    val m1 = n1 * n2
    val m2 = n1 * n3
    val m3 = n1 * n4
    val m4 = n2 * n3
    val m5 = n2 * n4
    val m6 = n3 * n4
    
    println("Adições: $n1+$n2=$s1, $n1+$n3=$s2, $n1+$n4=$s3, $n2+$n3=$s4, $n2+$n4=$s5, $n3+$n4=$s6")
    print("Multiplicações: $n1 x $n2=$m1, $n1 x $n3=$m2, $n1 x $n4=$m3, $n2 x $n3=$m4, $n2 x $n4=$m5, $n3 x $n4=$m6")
}

```

---

## Exercício 8. Volume da Caixa 📦
```
fun main() {
    var comprimento = 4
    var largura = 6
    var altura = 2
    val volume = comprimento * largura * altura
    print(volume)
}

```

---

## Exercício 9. Quadrado de um Número ⏹️
```
fun main() {
    var numero = 2.0
    val potencia = (Math.pow(numero,2.0))
    print(potencia)
}

```

---

## Exercício 10. diferença de Dois Números ➖
```
fun main() {
    var n1= -3
	var n2 = 8
    val dif = n1 - n2
    print("$dif ($n1 - $n2)")
}

```

---

## Exercício 11. Conversão Dólar para Real 💱
```
fun main() {
    var dolar = 50
    val real = dolar * 5.24
    print(real)
}
```

---

## Exercício 12. Converção Real para Dólar 💱
```
fun main() {
    var real = 100
    val dolar = real/5.24
    print(dolar)
}
```

---

## Exercício 13. Soma dos Quadrados 🚀
```
fun main() {
    var n1 = 2.0
    var n2 = 3.0
    var n3 = 4.0
    val quad1 = (Math.pow(n1, 2.0))
    val quad2= (Math.pow(n2,2.0))
    val quad3= (Math.pow(n3,2.0))
    val soma = quad1 + quad2 + quad3
    print("$soma ($n1² + $n2² + $n3² = $quad1 + $quad2 + $quad3 = $soma)")
}
```

---

## Exercício 14. Quadrado da Soma 🔍
```
fun main() {
    var n1 = 2.0
    var n2 = 3.0
    var n3 = 4.0
    val soma = n1 + n2 + n3
    val quad = (Math.pow(soma, 2.0))
	print("$quad (($n1 + $n2 + $n3)² = $soma² = $quad)")
}
```

---

## Exercício 15. Produto e Soma de Quatro Números ⁉️
```
fun main() {
    var n1 = 2.0
    var n2 = 3.0
    var n3 = 4.0
    var n4 = 5.0
    val prod = n1 * n3
    val soma = n2 + n4
    print("Produto: $prod ($n1 x $n3), Soma: $soma ($n2 + $n4)")
}
```

---

## Exercício 16. Aumento de Salário 💰
```
fun main() {
	var salario = 1000.0
    var porcentagem = 10.0
    val aumento = salario * (porcentagem / 100.0)
    val novo_salario = salario + aumento
    print("Novo salário: $novo_salario, Aumento concedido: $aumento")
}
```

---

## Exercício 17. Área de Circunferência 🛞
```
fun main() {
	fun main() {
	var raio = 5.0
    val area = 3.14 * raio * raio
    print(area)
}
```

---

## Exercício 19. Cáculo Operações Básicas 🧮
```
fun main() {
	var n1 = 10.0
    var n2 = 5.0
    
    val soma = n1 + n2
    val sub = n1 - n2
    val multi = n1 * n2
    val div = n1 / n2
    
    println("Adição: $n1 + $n2 = $soma")
    println("Subtração: $n1 - $n2 = $sub")
    println("Multiplicação: $n1 x $n2 = $multi")
    println("Divisão: $n1 / $n2 = $div")
}
```

---

## Exercício 20. Velocidade de um Projétil ☄️
```
fun main() {
	var distancia = 200.0
    var tempo = 4.0
    
    val velocidade = distancia / tempo / 3.6
    
    print("Velocidade: $velocidade m/s")
}
```

---

## Exercício 21. Cáculo Potência 🔢
```
fun main() {
	var base = 2.0
    var expoente = 3.0
    
    val resultado = (Math.pow(base, expoente))
    print(resultado)
}
```

---

## Exercício 22. Volume da Esfera ⚽
```
fun main() {
	var raio = 5.0
    
    val volume = (4.0/3.0)* 3.14 * (Math.pow(raio, 3.0))
    print(volume)
}
```

---

## Exercício 23. Pés para Metros 👣
```
fun main() {
	var pes = 10
    
    val metros = pes* 0.3048
    print(metros)
}
```

---

## Exercício 24. Cáuculo Raiz Quadrada 🫚
```
fun main() {
	var base = 16.0
    var indice = 2.0
    
    val raiz = Math.pow(base, 1.0/indice)
    print(raiz)
}
```

---

## Exercício 25. Sucessor e Antecessor 👶👴
```
fun main() {
	var numero = 5
    
    val sucessor = numero - 1
    val antecessor = numero + 1
    
    print("Sucessor: $sucessor, Antecessor: $antecessor")
}
```

---

## Exercício 26. Quadrado da Divisão de Dois Números Inteiros ➗
```
fun main() {
	var n1 = 10.0
    var n2 = 2.0
    
    val div = n1/n2
    val quad = Math.pow(div, 2.0)
    
    print(quad)
}
```

---

## Exercício 27. Diferença entre Dois Números Inteiros 🤓
```
fun main() {
	var n1 = 10.0
    var n2 = 5.0
    
    val diferenca:Double
    
    if(n1 > n2){
        diferenca = n1 - n2
    } else {
        diferenca = n2 - n1
    }
    print(diferenca)
}
```

---

## Exercício 28. Positivo ou Negativo 📊
```
fun main() {
	var numero = -5
    
    if (numero > 0) {
    	print("Positivo")
    } else if (numero < 0){
        print("Negativo")
    } else {
        print("Neutro")
    }
}
```

---

## Exercício 29. Média e Verificação de Aprovação ✅
```
fun main() {
	var n1 = 7.0
    var n2 = 6.0
    var n3 = 4.0
    var n4 = 5.0
    
    val media = (n1 + n2 + n3 + n4)/4.0
    if (media >= 5.0) {
        print("Média: $media, Aprovado")
    } else {
        print("Média: $media, Reprovado")
    }
}
```

---

## Exercício 30. Média e Verificação de Aprovação com Exame 🧾
```
fun main() {
	var n1 = 6.0
    var n2 = 7.0
    var n3 = 5.0
    var n4 = 8.0
    
    val media = (n1 + n2 + n3 + n4)/4.0
    if (media > 7.0) {
        print("Média: $media, Aprovado")
    } else if (media >= 5.0) {
        print("Média: $media, Exame")
    } else {
        print("Média: $media, Reprovado")
    }
}
```

---

## Exercício 32. Ordenação de Três Números 🔢
```
fun main() {
	var n1 = 5
    var n2 = 2
    var n3 = 7
    var temp:Int
    
    if (n1 > n2){
        temp = n1
        n1 = n2
        n2 = temp
    } else if (n1 > n3){
        temp = n1
        n1 = n3
        n3 = temp
    } else if (n2 > n3) {
        temp = n2
        n2 = n3
        n3 = temp
    } else {
        print("Error")
    }
    
    print("$n1, $n2, $n3")
}
```
