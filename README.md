qthreadpool-demo
================

Ejemplo ilustrativo del uso del _pool_ de hilos [QThreadPool](http://qt-project.org/doc/qt-5.0/qtcore/qthreadpool.html) en Qt.

Básicamente genera dos vectores de números aleatorios y calcula su producto escalar, paralelizando ambas tareas por medio del _pool_ de hilos de Qt.

Por defecto el _pool_ tiene tantos hilos como núcleos de CPU hay en el sistema. Para ajustar el tamaño del _pool_ con el objeto de ver su efecto sobre el rendimiento, basta con descomentar [main.cppi#110](https://github.com/ull-etsii-sistemas-operativos/qthreadpool-demo/blob/master/main.cpp#L101) y ajustar el valor. Obviamente, por lo general, el valor óptimo está entorno al número de núcleos disponibles en el sistema.

-- Jesús Torres <jmtorres@ull.es>
