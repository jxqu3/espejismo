---
title: Ordenadores cuánticos, qué son, qué solucionan, y qué problemas traen.
layout: ../../layouts/Articulo.astro
---

### Gerardo Jiménez Lizana

## Los ordenadores cuánticos son una tecnología que está emergiendo y se está popularizando. Pueden ser muy útiles, o destruir toda la seguridad informática tal y cómo la conocemos.



Según una encuesta realizada en el instituto Alfonso XI, el 16 de cada 20 (80%) estudiantes no conocen lo que es un ordenador cuántico. En este artículo hablaremos de lo que es un ordenador cuántico, sus ventajas sobre uno convencional, los problemas que puede solucionar, y los que podría causar.  
  
Como quizá sabrás, la memoria de los ordenadores convencionales digitales se componen por unos y ceros. Estos valores representan el estado de un “bit”. Un bit es la unidad más pequeña de información que puede representar un ordenador. Juntando 8 bits, se forma un byte. Y juntando muchos de ellos se puede llegar a almacenar toda la información de un ordenador, por ejemplo: 1 gigabyte (“un giga”) equivale a 230 bytes: 1073741824 bytes.  
  
A diferencia de un ordenador convencional, uno cuántico no utiliza bits, sino qubits. En lugar de solo tener 1 y 0, puede estar en un estado intermedio: al igual que el gato de Schrodinger puede estar vivo y muerto a la vez, un qubit puede estar en 1 y 0 al mismo tiempo, lo cual permite velocidad exponencialmente mayor en algunos cálculos a un ordenador convencional.  
  
Muchos problemas matemáticos, sobre todo de física, antes considerados imposibles de resolver por su complejidad, gracias a estos ordenadores se vuelven posibles, pero, esto también trae un problema: la encriptación.  
  
Tus contraseñas se guardan en la base de datos de un servidor externo al crearte una cuenta. Un servidor es un simple ordenador con acceso a internet, configurado para que otros ordenadores puedan acceder a él. Para prevenir que un atacante o un empleado con malas intenciones pueda robarte tus contraseñas, se encriptan antes de subirse a esta base de datos, por lo que cuando un atacante acceda a la base de datos, verá algo así:  
  

```
User=iKtTTBx0RzBYHOoyrKi89QBlNQ7RgnWCx6z89dPGNOqmkBFoK2JP8AeK0FHWxm8lRhi2TFxCbzBVyGHRoFn7KRFVfaSUwFFuNeNwNsHqH9BR6IX3hBRsydgPxohlLElaWYaLFQUhsn1U87KjbIYoS9To0SbWjW3RnOAzzeRM8A4=
```  

```
Password=NBMW65AzZZzKLJ2qsfSJVYxZBz/WtljmN9vKIQmGys/IrbDPzUNMtxbZB0NS66sO9OJD5lYF67Or1FPM6gHZCRWYA0xvOUBowJRZVqETVInLJ9Cp7V8AgllkXBiJJ04df3lIrvyGkzUn8NgrfqCrnXrPd74B0fXA1oNSthfl+p8=
```

Este texto no se puede entender gracias a que está encriptado, lo que hace que no se pueda saber lo que pone sin una clave de desencriptación.  

Los mecanismos de encriptación más utilizados actualmente se basan en tres problemas matemáticos muy complicados de resolver, tan complicados, que se basa su forma de funcionar en que un superordenador digital tardaría incluso millones de años en resolverlos. El problema viene porque un ordenador cuántico suficientemente grande podría resolver estos problemas fácilmente usando el algoritmo de Shor, u otras alternativas. Esto supondría la posibilidad de descifrar muchos de estos mecanismos de encriptación, lo que permitiría a atacantes u otros delincuentes apoderarse de cosas como tus contraseñas, tus cuentas bancarias, entre otros.

Afortunadamente, ya se han creado nuevos algoritmos conocidos como “quantum-safe” que son resistentes a los ordenadores cuánticos, pero las webs que no se actualicen seguirán vulnerables hasta que lo hagan.

¿Qué puedes hacer para protegerte?
Aún no hay problema, pero para cuando lo haga, deberías:
Usar distintas contraseñas para cada web.
Si por alguna razón resultas ser criptógrafo, usar mecanismos de encriptación simétricos y “hashers”, ya que se cree que estos son seguros para la desencriptación cuántica.

En conclusión, los ordenadores cuánticos traerán muchas ventajas, podría solucionar problemas de física y médicos, incluso salvar vidas, pero los proveedores de sitios web deben 
