### G4-2020-1 (ALGORITMOS PARALELOS Y DISTRIBUIDOS)
---

### Datos Academicos 📚📓

- **Institucion:** Universidad Nacional de San Antonio Abad del Cusco
- **Facultad:** Facultad de ingenieria electrica, electronica , informatica y mecanica
- **Escuela Profesional:** Ingenieria Informatica y de Sistemas

#### Docente:👩‍🏫
- **Quintanilla Portugal Roxana Lisette** - _Docente_ - [Concytec](http://directorio.concytec.gob.pe/appDirectorioCTI/VerDatosInvestigador.do?id_investigador=40930).

#### Trabajo:📂

- Documentacion y entendimiento de un programa paralelizable.
- Utilizacion del lenguaje de programacion C, para luego ejecutarlo en el google colaboratory

#### Integrantes : 📌

- **Huancara Ccolqque Alex Helder** - _GitHub Account_ - [AlexHelder-Tyzer](https://github.com/AlexHelder-Tyzer)
- **Huillca Herrera Victor Pool** - _GitHub Account_ - [VictorPoolHuillcaHerrera](https://github.com/VictorPoolHuillcaHerrera)
- **Inca Cruz Carlos Eduardo** - _GitHub Account_ - [CarlosEdu322](https://github.com/CarlosEdu322)
- **Quispe Palomino Luiyi Antony** - _GitHub Account_ - [blablabla115](https://github.com/blablabla115)
- **Sipaucar Condori Maritza** - _GitHub Account_ - [MaritzaSipaucar](https://github.com/MaritzaSipaucar)
- **Tintaya Taco Yurema Lisbeth** - _GitHub Account_ - [YuremaLTT](https://github.com/YuremaLTT)
- **Ugarte Castillo Briggitte Leonor** - _GitHub Account_ - [briluc](https://github.com/briluc)
---
## Empezamos... 

Algoritmos de ordenamiento en programacion paralela 

### Construido con... 💻

- Lenguaje: [C](cython)
- Servicio Cloud: [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb)
- Diagrama de componentes:[Visual Paradigm Online Diagrams Express Edition](https://online.visual-paradigm.com/diagrams/solutions/free-visual-paradigm-online/)

## Contenido del proyecto

Este notebook contiene 4 secciones, en los cuales se expone detalladamente a los distintos algoritmos de ordenamiento; una vez seleccionada; el programa ejecutará primero un ordenamiento lineal, y luego en paralelo; indicando los tiempos de cada uno. Para llevar a cabo dicho objetivo, se utilizó la librería time, donde al comienzo de cada ordenamiento se declaró dos variables de tipo double la primera es start y la segunda end:
```
start = omp_get_wtime();
/*Codigo secuencial o paralelo
end = omp_get_wtime();
```

y al finalizar dicho ordenamiento, se obtuvo la diferencia, para luego mostrarla por pantalla tanto en ticks del reloj como en segundos, la funcion printf propia del lenguaje de programacion c:
```
printf("Tiempo de ejecucion %f seconds\\n", end - start);
```

Luego de cada set de ordenamientos, es posible ver determinada posición del arreglo, para corroborar que el mismo fue correctamente realizado. Esto fue corroborado en todos los casos, mostrando el arreglo, por mas larga que sea la cadena mostrara todos los resultados de la cadena

LINK COLAB

https://colab.research.google.com/gist/CarlosEdu322/d2b231c16f63ca21e0727ee982f32487/ordenamiento-openmp.ipynb#scrollTo=PwRIg-ZE2dwl






