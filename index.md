# Métodos Numéricos II 2025

Este curso es continuación de los temas estudiados en Métodos Numéricos 1. En esta materia, se estudian o revisan temas no introductorios de algoritmos para cálculo científico y aplicado y su implementación computacional. Se estudian tres grandes temas: 

(1) Álgebra lineal computacional, 

(2) Optimización numérica continua, 

(3) Optimización discreta. 

La primera parte el curso se enfoca en temas sobre cálculo de autovalores y autovectores, y la solución eficiente de sistemas lineales. En el segundo bloque, el bloque principal del curso, introduce los temas de optimización numérica, principalmente los métodos de gradiente y punto interior, así como métodos de la familia de gradiente conjugado y métodos quasi-Newton. El tema culmina haciendo un estudio de la teoría de optimización restricta, particularmente programación lineal y programación cuadrática. Finalmente, en el tercer bloque, hacemos una introducción a algunos métodos de optimización combinatoria y discreta. 

**Importante!!** El curso cuenta con una parte práctica extensiva, en la que el estudiante implementará en código computacional cada uno de los algoritmos estudiados. Parte fundamental del curso consiste en utilizar las herramientas aprendidas en varios proyectos aplicados donde se trabajará con datos reales y comunicar los resultados mediante reportes técnicos y seminarios.


# Prerrequisitos

Se recomienda que los estudiantes antes del curso estén habituados con los temas:
* Cálculo vectorial
* Álgebra lineal (teoría)
* Algunos elementos de análisis (convergencia de secuencias y series, análisis en Rn)
* Métodos numéricos para una variable (*root finding*, *fitting*, *numerical differentiation and integration*)
* Un curso de Programación.


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-opt2025.pdf){:target="_blank"}


### Horario
<div id='id-horario'/>

* Martes de 19:50 a 21:25 CIT-312, y Jueves de 19:50 a 21:25 CIT-312.

### Office Hours
<div id='id-office'/>

* Martes o jueves de 19:00 a 19:50.

# Material del curso
<div id='id-material'/>

**No.**  | **Fecha**    | **Tópicos**                                                              | **Recursos**
-------- | ------------ | ------------------------------------------------------------------------ |  ---------------------------------
01       | 01.07.2025   | Introducción. Aspectos generales del curso. <br/>                        | Repasar notas álgebra lineal. 
02       | 03.07.2025   | Normas matriciales. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"}  | Trefethen-Bau, Lecture 3. <br/> [norms.ipynb](code/norms.ipynb){:target="_blank"}
03       | 10.07.2025   | Autovectores. Descomposición espectral. Condición para diagonalización. [Aula 02](aulas/Aula02.pdf){:target="_blank"} | Trefethen-Bau, Lecture 4.  
04       | 15.07.2025   | Ejemplos de descomposición espectral. <br/>                              | [spectral.ipynb](code/spectral.ipynb){:target="_blank"}  
L1       | 15.07.2025   |  | [Lista 01](listas/lista01.pdf){:target="_blank"} <br/> **Entrega: jueves 24 de julio** 
05       | 17.07.2025   | Descomposición en valores singulares (SVD). <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Trefethen-Bau, Lecture 5. <br/> [svd.ipynb](code/svd.ipynb){:target="_blank"} 
06       | 22.07.2025   | Aplicaciones de la SVD: Componentes principales. [Aula 04](aulas/Aula04.pdf){:target="_blank"} | [pca.ipynb](code/pca.ipynb){:target="_blank"} 
07       | 24.07.2025   | Aplicaciones de la SVD: Compresión de imágenes. | [image_compression_ipynb](code/svd_image_compression_basico.ipynb){:target="_blank"} [quetzal.png](code/quetzal.png){:target="_blank"} <br/> [SVD Compression Demo](http://timbaumann.info/svd-image-compression-demo/){:target="_blank"}  
08       | 29.07.2025   | Condicionamiento y Estabilidad. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} [Aula 06](aulas/Aula06.pdf){:target="_blank"} | Trefethen-Bau, Lectures 13-15.
09       | 29.07.2025   | Eliminación gaussiana. Factoración LU. <br/> [Aula 07](aulas/Aula07.pdf){:target="_blank"} | Trefethen-Bau, Lecture 6. <br/> Burden-Faires, 6.1. 
10       | 31.07.2025   | Factoración PA = LU. Aplicaciones de eliminación gaussiana. | [gaussian_elimination.ipynb](code/gaussian_elimination.ipynb){:target="_blank"} 
L2       | 31.07.2025   |  | [Lista 02](listas/lista02.pdf){:target="_blank"} <br/> **Entrega: jueves 14 de agosto**  
11       | 05.08.2025   | Técnicas de pivoteo. <br/> [Aula 08](aulas/Aula08.pdf){:target="_blank"} | Burden-Faires, 6.2. <br/>  [pivoteo.xlsx](code/pivoteo.xlsx){:target="_blank"} 
12       | 07.08.2025   | Diagonal dominancia. Matrices definidas positivas. Factoración de Cholesky. [Aula 09](aulas/Aula09.pdf){:target="_blank"} | Trefethen-Bau, Lecture 23. <br/> Burden-Faires, Cap 6. 
13       | 12.08.2025   | Distribución normal multivariada. Generación de una normal multivariada. [Aula 09b](aulas/Aula09b.pdf){:target="_blank"} |  
14       | 14.08.2025   | Métodos iterativos para sistemas lineales. <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | Quarteroni *et al.*, Cap. 4. 
15       | 19.08.2025   | Cálculo de autovalores. Método de las potencias. *Shift-trick*. [Aula 11](aulas/Aula11.pdf){:target="_blank"} | Trefethen-Bau, Lecture 27. 
16       | 21.08.2025   | Proyectores. Descomposición QR. Forma de Hessemberg. [Aula 12](aulas/Aula12.pdf){:target="_blank"} | Trefethen-Bau, Lectures 6-8 y 10.  
17       | 21.08.2025   | Cálculo de autovalores. Método QR. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"} | Trefethen-Bau, Lecture 27. 
L3       | 21.08.2025   |  | [Lista 03](listas/lista03.pdf){:target="_blank"} <br/> **Entrega: domingo 31 de agosto**  
18       | 26.08.2025   | Matrices ralas. <br/> [Aula 14](aulas/Aula14.pdf){:target="_blank"} |    
19       | 28.08.2025   | Ejercicios de preparación para examen. | 
20       | 02.09.2025   | Agrupamiento espectral. | 
21       | 04.09.2025   | Parcial 1. <br/> | 
22       | 09.09.2025   | Programación lineal. Forma estándar. <br/> | Taha, Cap. 1 <br/> Matousek-Gärner, Cap. 4
23       | 11.09.2025   | Soluciones básicas. El método Simplex. <br/> | Taha, Cap. 2 y 3 <br/> Matousek-Gärner, Cap. 5 
24       | 23.09.2025   | Ejemplos. Uso de Julia para solución de problemas LP.  |  
L4       | 25.09.2025   | Aplicaciones de programación lineal. <br/> | [Lista 04](listas/lista04.pdf){:target="_blank"} <br/> **Entrega: jueves 2 de octubre** 
25       | 30.09.2025   | Fundamentos de optimización. Derivadas vectoriales y matriciales. [Aula 20](aulas/Aula20.pdf){:target="_blank"} | Fukunaga, App A.  
26       | 02.10.2025   | Fundamentos de optimización II. Gradiente y conjuntos de nivel. [Aula 21](aulas/Aula21.pdf){:target="_blank"} | Nocedal-Wright, Cap 1.  
27       | 07.10.2025   | Términos de error en serie la de Taylor. Condiciones de optimalidad. [Aula 22](aulas/Aula22.pdf){:target="_blank"} | Nocedal-Wright, Cap 1. 
28       | 09.10.2025   | Funciones convexas. <br/> [Aula 23](aulas/Aula23.pdf){:target="_blank"} | Boyd-Vandenberghe. 
29       | 14.10.2025   | Optimización 1-dimensional. <br/> |  


# Proyectos
<div id='id-proyectos'/>

En este curso de trabajarán dos proyectos, los cuales se indicarán más adelante. 

## Primer Proyecto 

**Fecha**    | **Tópicos**                                   | **Recursos**
------------ | --------------------------------------------- |  -------------------------------------
02.09.2025   | Proyecto 1 - *Spectral Clustering*.           | [Proyecto 1](proyectos/Proyecto1.pdf){:target="_blank"} <br/>  
07.10.2025   | Entrega del proyecto.                         | 


# Referencias
<div id='id-ref'/>

### Textos:

* [L. Trefethen, L. Bau III (1997). *Numerical Linear Algebra*.](https://libgen.li/ads.php?md5=079ea6c3fd8cdf23b0c2acd901ca9a26){:target="_blank"}

* [J. Nocedal, S. Wright (2006). *Numerical Optimization*.](https://libgen.li/ads.php?md5=7016b74cfe6dc64c75864322ee4aa081){:target="_blank"}

* [D. Luenberger, Y. Ye (2021). *Linear and Nonlinear Programming*.](https://libgen.li/ads.php?md5=a4f245169b2ca11bf27c640ffddbf957){:target="_blank"}

### Referencias adicionales:

* [R. Burden, A. Burden, D. J. Faires (2017). *Análisis numérico.*](https://libgen.li/ads.php?md5=8b84557e0b5a5c8effd22ce47bc2737f){:target="_blank"}

* [G. Golub, C. Van Loan (2013). *Matrix Computations*.](https://libgen.li/ads.php?md5=51d5272bc715b34ac74a8034940a4008){:target="_blank"}

* [A. Quarteroni, R. Sacco, F. Saleri (2006). *Numerical Mathematics*.](https://libgen.li/ads.php?md5=ebf3fbe744eb40bd56cc91f8a4339300){:target="_blank"}

* [J. Stoer, R. Bulirsch (2002). *Introduction to Numerical Analysis*.](https://libgen.li/ads.php?md5=5920d8c25547f6e67b4c990bb2a2194d){:target="_blank"}

* [A. Izmailov, M. Solodov (2014). *Newton-type for Optimization and Variational Problems*.](http://library.lol/main/C8C3ED2461D9C8C2608595B223ABDD91){:target="_blank"}

* [S. Boyd, L. Vandenberghe (2009). *Convex Optimization*.](http://library.lol/main/A9A5D9C3CA105DB0F41AF39A6C89706C){:target="_blank"}

* [C. Meyer (2001). *Matrix Analysis and Applied Linear Algebra*.](http://library.lol/main/7EF368F2EA42EB4E48F09EA438C1822E){:target="_blank"}

### Referencias programación lineal:

* [J. Matousek, B. Gärtner, (2007). *Understanding and Using Linear Programming*.](https://libgen.li/ads.php?md5=b760fdd2b747713ec1c8f24301fc2540){:target="_blank"}

* [A. Schrijver (1997). *Theory of Linear and Integer Programming*.](https://libgen.li/ads.php?md5=35edf7d8dfc7fccc3939fddab6680ed3){:target="_blank"}

---

