# Instalación

**Aviso**: Esta presentación no presenta ninguna captura de pantalla esencial del programa instalado, se puede dar el caso de que la instalación no funcione correctamente incluso si los pasos están hechos al 100% al pie de la letra.

A continuación, tendrás aquí una guía paso a paso para instalar WSL, si no te fias de hacerlo directamente en tu PC, siempre puedes practicar en una Máquina Virtual y cuando te hayas asegurado, entonces ya puedes hacerlo en tu Windows 10/11 físico (Aunque en el caso
que tengo no ha llegado a funcionar en ningún caso). Estos son los pasos a seguir

1. Abre PowerShell con privilegios de administrador y ejecuta: wsl --install
  * Este comando habilitará WSL y descargará e instalará una distribución de Linux predeterminada
2. Instalar una distribución específica:
  Después de habilitar WSL, puedes instalar una distribución específica con el siguiente comando: wsl --install -d Ubuntu
  * **Nota**: Puedes cambiar Ubuntu por cualquier otra distribución, en otras palabras, puedes instalar lo que quieras, cuando quieres y como quieras
3. (Paso Opcional) Por defecto, se te instala la versión 1 de WSL, si lo quieres en la más reciente posible introduce el siguiente comando en Powershell: wsl --set-default-version 2
4. Reinicia el PC... ya está, ese es el punto, una vez lo hayas instalado solo queda reinicar para que los cambios se apliquen
