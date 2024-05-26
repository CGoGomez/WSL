# Introduccón
# WSL

¿Qué es exactamente WSL?

Significa "Windows Subsystem for Linux" y es una característica de Windows (A partir de Windows 10 y 11) que les permite ejecutar un entorno Linux nativo sin la necesidad de instalar una máquina virtual o un arranque dual con ambos sitemas operativos en el mismo dispositivo de arranque, cosas de esas para ahorrar espacio.

Las características son las siguientes:
* Integración con Windows: Permite la ejecución de binarios de Linux junto con aplicaciones y herramientas de Windows, ofreciendo una experiencia integrada.
* Compatibilidad: Soporta varias distribuciones de Linux, como Ubuntu, Debian, Fedora, SUSE, entre otras.
* Acceso al Sistema de Archivos: Facilita el acceso mutuo entre los sistemas de archivos de Windows y Linux. Puedes acceder a archivos de Windows desde Linux y viceversa.
* Reducción de la Complejidad: Simplifica el desarrollo y las pruebas en entornos Linux sin la necesidad de configurar máquinas virtuales o entornos de arranque dual.

Actualmente existen dos versiones de WSL (WSL 1 y WSL2 )

WSL 1:

* Utiliza una capa de compatibilidad para traducir las llamadas del sistema Linux a las llamadas del sistema Windows.
* Es rápido en términos de rendimiento de E/S de archivos en el sistema de archivos de Windows.
* Es útil para operaciones que requieren un acceso rápido a los archivos de Windows.

WSL 2:

* Introduce un kernel Linux completo basado en la tecnología de virtualización ligera.
* Ofrece una mayor compatibilidad con las aplicaciones de Linux y un mejor rendimiento del sistema de archivos.
* Permite ejecutar software de Linux que requiere llamadas de sistema más complejas.
