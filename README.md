Aqui son algunas de las funcion que viene en este primer codigo que es lo Frontend, en cual puse unos algoritmos para ser una interfaz para leer los textos y unos botones para que abra el archivo y cuente los caracter
Función abrirarchivo(): Esta función se llama cuando se hace clic en el botón "Abrir Archivo". Abre un cuadro de diálogo para seleccionar un archivo y luego muestra la ruta del archivo seleccionado en una etiqueta llamada mensaje. También habilita el botón "Calcular Frecuencia".
Función mostrar_contenido(ruta_archivo): Abre una nueva ventana (Toplevel) que muestra el contenido del archivo seleccionado. Utiliza un widget Text para mostrar el contenido.
Función calcular_frecuencia(): Se activa cuando se hace clic en el botón "Calcular Frecuencia". Calcula la frecuencia de cada carácter en el archivo seleccionado y luego muestra una nueva ventana con los caracteres ordenados por frecuencia.
Función ventana_frecuencia(frecuencias): Crea una ventana secundaria que muestra los caracteres y sus frecuencias.
Función caracteres(ruta_archivo): Esta función cuenta la frecuencia de cada carácter en el archivo y devuelve un diccionario con los caracteres y sus frecuencias ordenados de mayor a menor.
Configuración de la interfaz gráfica (Tk()): Creas la ventana principal (Tk()) y agregas varios widgets como etiquetas y botones. También configuras algunos botones para que estén deshabilitados hasta que se seleccione un archivo.