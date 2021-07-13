# Proyecto4
Como primera observación, se puede mencionar que debido a la cantidad de bits que recibe el tipo de modulación, se tuvo que cambiar la forma en la que la función moduladora recibe los bits de la imagen. Lo mismo sucede para el caso de la demoduladora, obteniendo como resultado la siguiente imagen.

![image](https://user-images.githubusercontent.com/85804091/125529762-9ddb66dc-b654-4327-a08b-dc17ad01aac1.png)

Es interesante notar la diferencia entre la imagen obtenida con la modulación 16-QAM y la modulación obtenida con la modulación BPSK, la cual esta última presenta más "puntos" indeseados. Esto se debe principalmente a que la modulación 16-QAM recibe más bits y por lo tanto, más información.

En cuanto a las señales obtenidas y la densidad espectral de potencia, se pueden apreciar las siguientes imágenes, donde queda en evidencia que las señales viajan en forma síncrona y con un desfase de 90º, obteniendo una correlación teórica aceptable y concisa:

![image](https://user-images.githubusercontent.com/85804091/125531184-be4c89e2-f72b-4bf8-9b30-ab6e695a9d4b.png)

![image](https://user-images.githubusercontent.com/85804091/125531207-518e2311-07fe-4d56-9008-20c1261c492e.png)

Al simular su estacionaridad y ergodicidad, se obtuvo la siguiente gráfica:

![image](https://user-images.githubusercontent.com/85804091/125532321-de2928d8-0057-4097-9ddc-a9b968b0516c.png)

La cual concuerda con los datos previamente configurados, ya que la frecuencia utilizada es de 5000 Hz y se evidencia en el comportamiento de la transformada de Fourier representada en la imagen anterior.
