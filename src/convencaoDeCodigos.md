# Convenção de códigos em Java
 No Java, há convenções bem estabelecidas para a nomeação e formatação de código. Essas boas práticas ajudam a manter o código limpo, legível e padronizado, principalmente quando trabalhamos em equipe.

---

### Nomes de Classes:
PascalCase *(cada palavra começa com letra maiúscula)*.   
```public class MinhaClasse {}```   
```public class CalculadoraFinanceira {}```

---

### Nomes de Métodos
camelCase *(primeira palavra minúscula, as seguintes com maiúscula).*   
```public void calcularTotal() {}```   
```public String obterNomeCliente() {}```   

---

### Nomes de Variáveis:
camelCase   
```int idadeCliente;```   
```String nomeCompleto;```

---

### Nomes de Constantes:
MAIUSCULA_COM_UNDERSCORE  
```public static final int TAMANHO_MAXIMO = 100;```  
```private static final String URL_BASE = "https://api.site.com";```

---

### Pacotes: 
letras minúsculas, separadas por ponto, geralmente iniciando com domínio invertido.   
```package com.sitepress.controle;```  
```package br.com.meunegocio.utils;```

---

### Indentação e Espaçamento
* Indentação padrão: 4 espaços por nível (evite TAB).
* Chaves {}: abertas na mesma linha do if, for, while, class, etc.

```
public class Pessoa {
private String nome;

    public void setNome(String nome) {
        this.nome = nome;
    }
}
```

---

### Comentários
```// comentario curto ```

```
/*
* Comentario longo...
*/
```

```declarative
/**
* Calcula o valor total da compra
* @param preço Preço do Item
* @return Valor total
*/
public double calcularTotal(double preco, int quantidade){
    return preco * quantidade;
}
```

---

### Organização do Código
Ordem recomendada dos membros da classe:
  1. Constantes
  2.  Atributos
  3. Construtores
  4. Métodos públicos
  5. Métodos privados
  6. Getters e Setters
  7. Métodos sobrescritos (toString, equals, hashCode, etc.)
