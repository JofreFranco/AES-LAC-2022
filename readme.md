# Evaluación de técnicas de crosstalk aéreo utilizando el método pseudo espectral (PSTD)
Este repositorio contiene el paper "Evaluación de técnicas de crosstalk aéreo utilizando el método pseudo espectral (PSTD)" presentado por Jorge Petrosino, Georgina Lizaso y Franco Jofré en el 12º Congreso Iberoamericano de Acústica.

## Resumen:
Las técnicas de cancelación de crosstalk aéreo (XTC) buscan que cada oído reciba una señal diferente con mínima
interferencia entre señales. Esto requiere procesarlas mediante retardos, inversiones o alteraciones espectrales
para cancelar el crosstalk acústico que ocurre cuando llega al oído izquierdo señal de la derecha y viceversa.
Los primeros trabajos fueron desarrollados por Atal y Schroeder en la década del 60. En las últimas décadas,
la disponibilidad de herramientas digitales de procesamiento ha dado lugar a diversas técnicas para superar los
obstáculos intrínsecos que se presentan al momento de implementar esta cancelación en la práctica. Según el
estado del arte, alcanzar un nivel de XTC superior a los 20 dB resulta suficiente para lograr una buena percepción
de binauralidad. El presente trabajo realiza una comparación entre resolución analítica, medición y simulación en
el dominio del tiempo para evaluar los niveles de cancelación alcanzados mediante el diseño de filtros inversos con
regularización de parámetro constante. El diseño de filtros y el desarrollo analítico se basan en las descripciones
realizadas por Choueiri (2018), ajustando el parámetro de regularización para un rango de frecuencia adecuado a
la palabra hablada. La medición fue realizada en un ambiente semi anecoico con dos altavoces y micrófonos de
medición en la posición de los oídos. Para la simulación se utilizó el toolbox k-Wave para Matlab que implementa
la resolución de ecuaciones diferenciales de propagación acústica en base al método pseudo espectral del espacio
k en el dominio del tiempo (PSTD). Los resultados muestran que se alcanza un nivel de XTC satisfactorio para
lograr percepción binaural y que la simulación en el dominio del tiempo con el método pseudo espectral puede
considerarse una herramienta útil para la evaluación de técnicas de XTC

## Abstract:
Crosstalk Cancellation for binaural audio through loudspeakers (XTC-BAL) techniques seek to ensure that each
ear receives a different signal with minimal interference between them. Processing the signals through delays,
inversions, or spectral alterations is required to cancel the acoustic crosstalk from the right channel to the left
ear and vice versa. The first studies were published by Atal and Schroeder in the 1960s. In the last decades, the
availability of digital processing tools has given rise to various techniques to overcome the intrinsic obstacles that
arise when implementing this cancellation in practice. According to previous research, reaching an XTC level
greater than 20 dB is enough to achieve an adequate binaural perception. The present work shows a comparison
between analytical resolution, measurement, and simulation in the time domain to evaluate the cancellation
levels achieved by designing inverse filters with constant parameter regularization. Filter design and analytical
development are based on the descriptions made by Choueiri (2018), adjusting the regularization parameter for a
frequency range appropriate to the spoken word. Measurements were carried out in a semi-anechoic environment
with two loudspeakers and measurement microphones in the position of the ears. Simulations run using the
Matlab toolbox, named k-Wave, which solves differential equations of acoustic wave propagation using the
k-space pseudo-spectral method in the time domain (PSTD). Results show an adequate XTC level to achieve
binaural perception and suggest PSTD simulations can be considered helpful in evaluating XTC techniques.

Además se encuentran 4 audios, un par de audios binaurales sin procesamiento y estos mismos audios procesados con la técnica que se investigó para ser reproducidos en un parlante JBL Flip 4. 
 - Binaural_Match_Sticks.wav y Haircut16-44p1.wav son audios binaurales (para escuchar con auriculares)
 - JBLBinaural_Match_Sticks.wav y JBLHaircut16-44p1.wav son las versiones de los audios anteriores procesadas para ser reproducidas con el JBL Flip 4.
