a# G4-2020-1 (ALGORITMOS PARALELOS Y DISTRIBUIDOS)
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

- Lenguaje: [C](http://www.mingw.org/)
- Servicio Cloud: [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb)
- Diagrama de componentes:[Visual Paradigm Online Diagrams Express Edition](https://online.visual-paradigm.com/diagrams/solutions/free-visual-paradigm-online/)
- Editor: [Visual Studio](https://visualstudio.microsoft.com/es/)

## Diagrama de componentes 



## Codificacion del programa 
# Conpilador: MINGW GNU 

The GNU General Public License is a free, copyleft license for software and other kinds of works.

The licenses for most software and other practical works are designed to take away your freedom to share and change the works. By contrast, the GNU General Public License is intended to guarantee your freedom to share and change all versions of a program--to make sure it remains free software for all its users. We, the Free Software Foundation, use the GNU General Public License for most of our software; it applies also to any other work released this way by its authors. You can apply it to your programs, too.


Fase 1: Completado ,nociones basicas de algoritmos de ordenamiento

Fase 2: Cambiar entorno de desarrollo y mejores entornos de desarrollo

Si debemos considerar el rendimiento del programa como un todo, independientemente de cada algoritmo de ordenamiento por separado, la ejecución más rápida fue la primera (8 núcleos e igual cantidad de threads), logrando 78,27 segundos. Ninguna otra ejecución pudo bajar ese tiempo (aunque la segunda ejecución quedó apenas por debajo con 78,982 segundos), ya que el Burbujeo Paralelo comenzó a volverse más lento, afectando al resultado general. Por otro lado, quizás sorpresivamente, la ejecución más lenta fue la cuarta (8 núcleos y 50 threads), ya que el burbujeo paralelo tomó 76,542 segundos, totalizando 151,995 segundos. Esto permite concluir que al superar la misma cantidad de núcleos que de threads, el comportamiento del burbujeo paralelo comienza a tardar más tiempo, en vez de mejorar.


