# Presentación tomada de **FourierTalkOSCON**


Material de la plática [Sound Analysis with the Fourier Transform and Python](http://www.oscon.com/oscon2013/public/schedule/detail/28946) OSCON 2013 Talk.

---

### Puedes consultar el material original en: http://tinyurl.com/fourierpython

---


# Indice de libretas:

1. [Introducción (solo texto)](01_Introduction.ipynb)
2. [Naturaleza de las ondas](02_NatureOfWaves.ipynb)
3. [Transformada de Fouruer](03_FourierTransform.ipynb)
4. [Convolución y deconvolución de señales](04_WaveDeconvolution.ipynb)
5. [La formula de Euler y representación circular de señales](05_RotationWithE.ipynb)
6. [Transformada rápida de Fouruer en *python*](06_FFTInPython.ipynb)
7. [Analizando señales de audio](07_SeeingSound.ipynb)
8. [Análisis y tratamiento por ventanas de tiempo](08_STFT.ipynb)
9. [Filtros pasa bajo y pasa alto](09_AudioFiltering.ipynb)
10. [Conclusiones (texto y enlaces del autor)](http://nbviewer.ipython.org/url/raw.github.com/calebmadrigal/FourierTalkOSCON/master/10_Conclusion.ipynb)

---

Para grabar audio en tu computadora, usando linea de comandos se puede utilizar la utilería [SoX](http://sox.sourceforge.net).

Los dos comandos más utiles son los siguientes:

* `rec -r 44100 -c 2 -b 16 A4.wav`
    - Graba a 44100 muestras por segundo, 2 canales, 16 bits por muestra
* `sox audio_2channels.wav audio_1channel.wav channels 1`
    - Convierte de dos canales a uno
