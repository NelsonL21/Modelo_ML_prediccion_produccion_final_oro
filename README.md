# Modelo_ML_prediccion_produccion_final_oro

Se buscar preparar un prototipo de un modelo de machine learning para Zyfra. 

La empresa desarrolla soluciones de eficiencia para la industria pesada.


El modelo debe predecir la cantidad de oro extraído del mineral de oro. 
Dispones de los datos de extracción y purificación.


El modelo ayudará a optimizar la producción y a eliminar los parámetros no rentables.

El mineral extraído se somete a un tratamiento primario para obtener la mezcla de mineral, o alimentación rougher, que es la materia prima utilizada para la flotación (también conocida como proceso rougher). Después de la flotación, el material se somete al proceso de purificación en dos etapas.

## **Conclusión del proyecto** 

En el presente proyecto se requería que la empresa Zyfra fuese capaz de predecir cuales serían las concentraciones finales del oro en su proceso de recuperación de metales pesados.

Se observa una clara presencia de valores atípicos que deben estar seguramnete distribuidos  a lo largo de todas las características. Esto podía causar problemas a la hora de realizar predicciones.

Se evidenció como las dictribuciones entre los valores calculados y los reales son parecidos, siendo un 26.62 % mayores en lo que a media se refiere los reales a los teteóricos, sin embargo, las caracteristicas se coportaban de manera similar, haciendo alusión a que las tendencias son las mismas.

Se logró observar como cambian las distribuciones de los diferentes elementos dentro del procesos, viendo como al final las concentraciones de oro y plomo aumentaron considerablemente, y las de plata se vieron reducidas.

Se ópta por utilizar el modelo de arbol de decisión regresor, ya que mismo proporciona una mayor confiabilidad de los valores para la empresa, además de un margen de rror mucho menor, grarantizando un mejor funcionamineto.

Se logra obtener un modleo de machine learning que tiene un error medio absoluto porcentual simétrico final del 14.78% garantizando una buena eficiencia del mismo.

Así mismo, con el conjunto de prueba, se obtuvo un valor de sMAPE_final = 13.48% pudiendo concluir que es un buen modelo para predecir los valores 
