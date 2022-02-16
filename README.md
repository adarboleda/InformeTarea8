# InformeTarea8

1. OBJETIVOS

Objetivo General

* Conocer sobre los circuitos RC y circuitos RL mediante la utilización del libro de Floyd "Principios de Circuitos Eléctricos"

Objetivo Específico

* Resumir los capitulos quince y dieciséis del libro de Floyd "Principios de Circuitos Eléctricos", para que de esta forma se pueda comprender de una mejor manera los temas descritos.
* Aplicar los conocimientos adquiridos de circuitos RC y circuitos RL para la resolcuión de los ejercicos propuestos por el libro de Floyd.

2. MARCO TEÓRICO

![image](https://user-images.githubusercontent.com/93734334/153768295-3324c0cd-e75c-4621-8627-292a2053c91b.png)

![image](https://user-images.githubusercontent.com/93734334/153769181-511fb984-2c31-4449-acef-bdf8c80d58aa.png)

![image](https://user-images.githubusercontent.com/93734334/153770716-32b7dec6-6720-40ca-8600-4b829107937c.png)

![image](https://user-images.githubusercontent.com/93734334/153947007-3d560c79-8a14-46c0-baec-fa6456fe20f1.png)

![image](https://user-images.githubusercontent.com/93734334/153951252-3a69ce50-ca57-496b-be2a-d6325d05f6f4.png)

![image](https://user-images.githubusercontent.com/93734334/153954140-73f96de4-78d8-4cd1-b59f-319814a40079.png)

3. EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

**Capitulo 15**                                                                                                                                                                   
**SECCIÓN 15–4 Análisis de circuitos RC en serie**

39. Repita el problema 38 para el circuito de la figura 15-92. Vs = 10 V rms y f = 1 kHz

![image](https://user-images.githubusercontent.com/93734334/153955050-db7b1c12-1e65-4b44-8c36-8bae4c661c10.png)

**Respuesta**

![image](https://user-images.githubusercontent.com/93734334/153973642-3840e16e-7c4e-420b-9815-111c97a76bc0.png)

**PARTE 2: CIRCUITOS EN PARALELO**                                                                                                                                               
**SECCIÓN 15–5 Impedancia y admitancia de circuitos RC en paralelo**

41. Determine la magnitud de la impedancia y el ángulo de fase en la figura 15-94. 

![image](https://user-images.githubusercontent.com/93734334/153955218-6f73c855-59c2-4930-b743-adead1b07752.png)

RT = 470+330+680                                                                                                                                                                 
RT= 1480 ohm

CT = 0.1 + 0.22                                                                                                                                                                   
CT = 0.32 uF                                                                                                                                                                     
CT = 3.32x10^-7 F

f = 2 KHz                                                                                                                                                                         
f = 2000 Hz

Xc = 1/((2pi)(f)(C))                                                                                                                                                             
Xc = 1/((2pi)(2000)(3.2x10^-7))                                                                                                                                                   
Xc = 248.68 ohm

Z = (1480)(248.68)/(√(1480)^2 + (248.68)^2) < -tan^-1 (1480/248.68)

**Z = 245 ohm**

**θ = 80.5°**

**SECCIÓN 15–6 Análisis de circuitos RC en paralelo**

43. Para el circuito de la figura 15-95, encuentre todas las corrientes y los voltajes en forma polar.

![image](https://user-images.githubusercontent.com/93734334/153955381-a686a119-f845-4b66-9dca-8782269765bd.png)

**VC = VR = 10 < 0°**

IR = Vs/R                                                                                                                                                                         
IR = 10 < 0° / 68 < 0°                                                                                                                                                           
**IR = 147 < 0° mA**

Ic = Vs/Xc                                                                                                                                                                       
Ic = 10 < 0° / 90 < -90°                                                                                                                                                        
**Ic = 111 < 90° mA**

Itot = √(IR)^2 + (Ic)^2 < tan^-1 (Ic/IR)                                                                                                                                         
Itot = √(147)^2 + (111)^2 < tan^-1 (111/147)                                                                                                                                     
**Itot = 184 < 37.1° mA**

45. Para el circuito de la figura 15-97, determine lo siguiente:                                 
(a) Z (b) IR (c) IC(tot) (d) Itot (e) θ

![image](https://user-images.githubusercontent.com/93734334/153955663-df6cf923-fd99-4b3f-90ee-b9a283044ddd.png)

(a)

Z = (10)(8.75)/(√(10)^2 + (8.75)^2) < -tan^-1 (10/8.75)

**Z = 6.59 < -48.8° ohm**

(b)

IR = Vs/R                                                                                                                                                                         
IR = 0.1 < 0° / 10 < 0°                                                                                                                                                           
**IR = 10 < 0° mA**

(c)

1/Xct = 1/21 + 1/5
Xc = 8.75

Ic = Vs/Xc                                                                                                                                                                       
Ic = 0.1 < 0° / 8.75 < -90°                                                                                                                                                        
**Ic = 11,4 < 90° mA**

(d)

Itot = √(IR)^2 + (Ic)^2 < tan^-1 (Ic/IR)                                                                                                                                         
Itot = √(10)^2 + (11.4)^2 < tan^-1 (10/11.4)                                                                                                                                     
**Itot = 15.2 < 48.8° mA**

(e)

θ = tan^-1(Ic/IR)                                                                               
θ = tan^-1(11.4/10)                                                                             
**θ = 48.8° mA**

47. Cambie el circuito de la figura 15-98 a una forma equivalente dispuesta en serie

![image](https://user-images.githubusercontent.com/93734334/153955866-fe237813-a0df-40f0-a0bf-3f024da80add.png)

Rt = 10+12                                                                                                                                                                       
Rt = 22 kohm

1/Ct = 1/100 + 1/47                                                                                                                                                               
Ct = 31.97 pF

Xc = 1/((2pi)(f)(C))                                                                                                                                                             
Xc = 1/((2pi)(100000)(31.97x10^-12))                                                                                                                                                   
Xc = 49.783 kohm
  
G = 1/22 Komh                                                                                                                                                                     
G = 0.045 uS

Bc = 1/49.783                                                                                                                                                                     
Bc = 0.02 uS

Y = √(G)^2 + (Bc)^2 < tan^-1 (Bc/G)                                                                                                                                               
Y = √(0.045)^2 + (0.02)^2 < tan^-1 (0.02/0.045)                                                                                                                                   
Y = 0.049 < 23.96° uS

Ztot = 1/Y                                                                                                                                                                       
Ztot = 1/0.049 < 23.96°                                                                                                                                                           
Ztot = 20.41 < -23.96° Kohm

Forma rectangular

Ztot = Zcosθ - jZsenθ                                                                                                                                                             
Ztot = 20.41cos(-23.96) -j20.41sen(-23.96)                                                                                                                                       
Ztot = 18.7 kohm - j8.288 kohm

**Req = 18.7 khom**
  
C = 1/((2pi)(f)(Xc))                                                                                                                                                             
C = 1/((2pi)(10000)(8288))                                                                                                                                                       
**C = 192 pF**

El resistor de 18.7 kohm en serie con el capacitor de 192 pF

**PARTE 3: CIRCUITOS EN SERIE-PARALELO**
**SECCIÓN 15–7 Análisis de circuitos RC en serie-paralelo**

49. Determine los voltajes en forma polar a través de cada elemento de la figura 15-100. Trace el diagrama fasorial de voltaje. 

![image](https://user-images.githubusercontent.com/93734334/153956017-f24216e3-c6ee-4f92-8c8c-9a8f5e3ad251.png)


51. Encuentre la corriente a través de cada rama y la corriente total en la figura 15-100. Exprese las corrientes en forma polar. Trace el diagrama fasorial de corriente. 

![image](https://user-images.githubusercontent.com/93734334/153956029-3cb60a9c-d9e3-4c31-8668-903d7e8cfa96.png)


53. Determine el valor de C2 en la figura 15-102 cuando VA = VB.

![image](https://user-images.githubusercontent.com/93734334/153956217-c254a662-2b11-4abd-9003-0a723762cb2d.png)

55. Encuentre la corriente a través de cada componente en la figura 15-103. 

![image](https://user-images.githubusercontent.com/93734334/153956281-4994844b-ab23-4464-8045-5ccf42d7525e.png)

**PARTE 4: TEMAS ESPECIALES**
**SECCIÓN 15–8 Potencia en circuitos RC**

57. En un circuito RC en serie, la potencia real es de 2 W y la potencia reactiva de 3.5 VAR. Determine la
potencia aparente.

Pa = √(Preal)^2+(Pr)^2                                                                                                                                                           
Pa = √(2)^2+(3.5)^2}

**Pa = 4.03 VA**

59. ¿Cuál es el factor de potencia para el circuito de la figura 15-98?

![image](https://user-images.githubusercontent.com/93734334/153956829-8ddd7c73-4871-4687-b9ed-749d8c0fc40c.png)

Rt = 10+12                                                                                                                                                                       
Rt = 22 kohm

1/Ct = 1/100 + 1/47                                                                                                                                                               
Ct = 31.97 pF

Xc = 1/((2pi)(f)(C))                                                                                                                                                             
Xc = 1/((2pi)(100000)(31.97x10^-12))                                                                                                                                             
Xc = 49.783 kohm

Z = √(R)^2 + (Xc)^2 < -tan^-1 (Xc/R)                                                                                                                                             
Z = √(22)^2 + (49.78)^2 < -tan^-1 (49.78/22)                                                                                                                                     
Z = 54.42 < -66.2° Kohm

PF = cosθ                                                                                                                                                                         
PF = cos(-66.2°)                                                                                                                                                                 
**PF = 0.914**

61. Una sola fuente de 240 V y 60 Hz alimenta dos cargas. La carga A tiene impedancia de 50 Æ y factor
de potencia de 0.85. La carga B tiene impedancia de 72 Æ y factor de potencia de 0.95.

(a) ¿Cuánta corriente consume cada carga?                                                                                                                                         
(b) ¿Cuál es la potencia reactiva en cada carga?                                                                                                                                 
(c) ¿Cuál es la potencia real en cada carga?                                                                                                                                     
(d) ¿Cuál es la potencia aparente en cada carga?                                                                                                                                 
(e) ¿Cuál carga tiene más caída de voltaje a lo largo de las líneas que la conectan a la fuente?

63. ¿Qué valor de capacitor de acoplamiento se requiere en la figura 15-104 de modo que el voltaje de señal a la entrada del amplificador 2 sea por lo menos un 70.7% del voltaje de señal a la salida del amplificador 1 cuando la frecuencia es de 20 Hz?

![image](https://user-images.githubusercontent.com/93734334/153957058-9e1ac31d-a179-4c13-9d05-ec84291e3477.png)

**SECCIÓN 15–10 Localización de fallas**

65. Suponga que el capacitor de la figura 15-106 tiene fugas en exceso. Muestre cómo afecta esta degradación al voltaje de salida y al ángulo de fase, suponiendo que la resistencia de fuga es de 5 kÆ y la frecuencia de 10 Hz. 

![image](https://user-images.githubusercontent.com/93734334/153957157-fe53ffea-d525-47dc-b518-1b41ee13ef37.png)

Rth = RRfuga/(R+Rfuga)
Rth = (4.7)(5)/(4.7+5)
Rth = 2.42 komh

Vth = (Rfuga/(R+Rfuga)) Vs
Vth = (5/(4.7+5)) 10
Vth = 5.15 V


Xc = 1/((2pi)(f)(C))                                                                                                                                                             
Xc = 1/((2pi)(10)(10x10^-5))                                                                                                                                             
Xc = 1.592 kohm

Vsal = (Xc/√(Rth)^2+(Xc)^2) Vth                                                                                                                                                   
Vsal = (1.592/√(2.42)^2+(1.592)^2) 5.15                                                                                                                                           
**Vsal = 2.83 V**

IR = Vs/R                                                                                                                                                                         
IR = 5.15 < 0° / 4.7 < 0°                                                                                                                                                         
IR = 1.096 < 0° mA

Ic = Vs/Xc                                                                                                                                                                       
Ic = 5.15 < 0° / 1.592 < -90°                                                                                                                                                     
Ic = 3.235 < 90° mA

θ = tan^-1(3.235/1.096)                                                                               
θ = tan^-1(11.4/10)                                                                             
**θ = -56.7° mA**

67. Determine el voltaje de salida para el circuito de la figura 15-107(a) para cada uno de los siguientes modos de falla, y compárelo con la salida correcta:

(a) R1 abierto (b) R2 abierto (c) C abierto (d) C en cortocircuito

![image](https://user-images.githubusercontent.com/93734334/153957469-2b462227-f4e1-42df-bf6e-cc23de64bd21.png)

**PARTE 1: CIRCUITOS EN SERIE**                                                                                                                                                   
**SECCIÓN 16–1 Respuesta sinusoidal de circuitos RL en serie**

1. Se aplica un voltaje sinusoidal de 15 kHz a un circuito RL en serie. ¿Cuál es la frecuencia de I, VR y VL?

**Respuesta**

15kHz

**SECCIÓN 16–2 Impedancia de circuitos RL en serie**

3. Exprese la impedancia total de cada circuito de la figura 16-54 tanto en forma polar como rectangular.

![image](https://user-images.githubusercontent.com/93734334/153957774-7deac3d1-609e-4186-a028-5c2aff44a49e.png)

Z = R + jXL

(a)

**Z = 100 ohm + j50 ohm**

Z = √(R)^2 + (XL)^2 < tan^-1 (XL/R)                                                                                                                                             
Z = √(100)^2 + (50)^2 < tan^-1 (50/100)                                                                                                                                     
**Z = 112 < 26.6° ohm**

(b)

**Z = 1.5 kohm + j1 kohm**

Z = √(R)^2 + (XL)^2 < tan^-1 (XL/R)                                                                                                                                             
Z = √(1.5)^2 + (1)^2 < tan^-1 (1/1.5)                                                                                                                                     
**Z = 1.8 < 33.7° kohm**

5. En la figura 16-56, determine la impedancia para cada una de las siguientes frecuencias:

(a) 100 Hz (b) 500 Hz (c) 1 kHz (d) 2 kHz

![image](https://user-images.githubusercontent.com/93734334/153957852-63069268-f859-4693-9d8a-36ed6a2c5937.png)

7. Reduzca el circuito de la figura 16-57 a una sola resistencia e inductancia en serie.

![image](https://user-images.githubusercontent.com/93734334/153957921-1e7c3d96-99a6-46a6-967d-10c83e5f3d63.png)

4. VIDEO

5. CONCLUSIONES

6. BIBLIOGRAFÍA

Floyd, T. (2007). Principios de circuitos eléctricos. PEARSON Educación. https://drive.google.com/file/d/15UCq2JrPEKKB8SwajlmtTcE07nMiowaK/view

RUBRICA

![](https://github.com/doalulema/InformeTarea/blob/main/Tarea.png)
