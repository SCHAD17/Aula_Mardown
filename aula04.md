# Tabelas 

Por padrão alinhamento é feito a esquerda

Tabela 1

Mês | Demanda (R$) | 
----|-------- |
Janeiro |  1.100 
Fevereiro| 1.200 
Março | 1.200 
Abril | 2.000 
Maio | 2.300 
Junho | 1.800 
Julho | 1.800 
Agosto | 1.800  
Setembro | 1.300 
Outubro | 1.500 
Novembro | 1.600
Dezembro | 1.600

Tabela 2



Mês | Demanda | Política 1 | Política 2
----|:--------: |:------------:|:---------:
Janeiro | 1.100 | 1.600 | 1.650
Fevereiro| 1.200 | 1.600 | 1.650
Março | 1.200 | 1.600 | 1.650
Abril | 2.000 | 1.600 | 1.650
Maio | 2.300 | 1.600 | 1.650
Junho | 1.800 | 1.600 | 1.650
Julho | 1.800 | 1.600 | 1.650
Agosto | 1.800 | 1.600 | 1.650
Setembro | 1.300 | 1.600 | 1.500
Outubro | 1.500 | 1.600 | 1.500
Novembro | 1.600 | 1.600 | 1.500
Dezembro | 1.600 | 1.600 | 1.500 

Alinhamento na direta (--: )

Mês | Demanda (R$) | 
----|--------------:
Janeiro |  1.100 
Fevereiro| 1.200 
Março | 1.200 
Abril | 2.000 
Maio | 2.300 
Junho | 1.800 
Julho | 1.800 
Agosto | 1.800  
Setembro | 1.300 
Outubro | 1.500 
Novembro | 1.600
Dezembro | 1.600


Alinhamento no centro (colocando :----: )

Mês | Demanda (R$) | 
----|:--------------:
Janeiro |  1.100 
Fevereiro| 1.200 
Março | 1.200 
Abril | 2.000 
Maio | 2.300 
Junho | 1.800 
Julho | 1.800 
Agosto | 1.800  
Setembro | 1.300 
Outubro | 1.500 
Novembro | 1.600
Dezembro | 1.600


#### Texto Mono-espaçado

Feio, sem coloração

### Python
```
from sympy import*
import numpy.linalg as la
import numpy as np

samp_rate = 32000
f0=1000
c= np.cos(2*np.pi*f0) + np.sin(2*np.pi*f0)
l = np.arange(np.round(0.01*samp_rate))/float(samp_rate)
tau =0.02
vet = np.hstack((np.ones(int(tau*samp_rate)),np.zeros(int((0.1-tau)*samp_rate))))
print("Vetor =", vet, "L =", l, "Sinal =", c)
```
### JAVA
```
public class App {
    public static void main(String[] args) throws Exception {
        System.out.println("Hello, World!");
    }
}
```

Bonito com coloração

### Python
```python
from sympy import*
import numpy.linalg as la
import numpy as np

samp_rate = 32000
f0=1000
c= np.cos(2*np.pi*f0) + np.sin(2*np.pi*f0)
l = np.arange(np.round(0.01*samp_rate))/float(samp_rate)
tau =0.02
vet = np.hstack((np.ones(int(tau*samp_rate)),np.zeros(int((0.1-tau)*samp_rate))))
print("Vetor =", vet, "L =", l, "Sinal =", c)
```
### JAVA
```java
public class App {
    public static void main(String[] args) throws Exception {
        System.out.println("Hello, World!");
    }
}
```

