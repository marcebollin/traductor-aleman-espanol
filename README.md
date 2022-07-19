
# Traductor Alemán a Español
Proyecto de la materia Traductores e Interpretadores | Universidad José Antonio Páez

### Integrantes:
    1.  Marcelo León
    2.  José Araya
    3.  Katherine Leal
    4.  Alejandro León
    5.  José Wildman
    6.  Mauricio Pernía
    7.  Carlos Gramcko
    8.  Jesús Ceballos
    9.  José Castro
    10. Bryan Miranda
    11. Luis Sandoval
    12. Andreas Peralta
    13. Enmanuel Díaz

## Grupos:

Serán 4 grupos de trabajo, el de búsqueda de información, el de creación de algoritmos para el formateo de la información, el desarrollo de la interfaz y el desarrollo de las fases del traductor.

* ### Búsqueda de información:
    En esta fase la idea es buscar todas las estructuras gramaticales del español de listas en internet que tengan algún tipo de formato [ejemplo de verbos en este link](https://www.idiomax.com/es/spanish-verb-list.aspx)

    En ese link, hay una lista de verbos, la idea de este grupo es buscar de por lo menos 3 páginas diferentes las siguientes estructuras:
    - Verbos sin conjugar (Alejandro León)
    - Adjetivos (Mauricio Pernía y Luis Sandoval)
    - Sustantivos (Jesús Ceballos y Enmanuel Díaz)
    - Conjunciones (Bryan Miranda)
    - Preposiciones (Bryan Miranda) 
    
    Nota: Las preposiciones siempre son las mismas, sólo copia todas las que hay en la primera página

    Las listas deben tener algún patrón de separación, bien sea comas, espacios, puntos.
    Las +3 listas que consigan las agregan a archivos de texto diferentes, traten de identificarlas para que se le haga más fácil manejarlas al siguiente grupo.

*  ### Formateo de información:
    En este grupo van a trabajar José Wildman y Carlos Gramcko

    En esta fase se va a agrupar, formatear y filtrar la información conseguida por el anterior grupo. Se van a usar expresiones regulares (regex) para hacer el formateo manual, algunas de las que pueden usar son:

    * /n para eliminar saltos de línea
    * /w+ para agrupar por palabra
    * /s para detectar espacios  

    Además, es necesario eliminar todas las tildes, diéresis y mayúsculas.
    Después de generar todos los arreglos de las listas anteriores, hacer un algoritmo para unificarla en un sólo arreglo sin repeticiones. La idea de esto es cubrir la mayor cantidad de palabras posibles y luego me la envían. Ejemplo:
    ```javascript
    const verbos = ["abrir", "acabar", "acercar", "aconsejar", "acordar", "amar", "andar", "apoyar", "aprender", "armar", "asesinar", "atacar", "ayudar", "bailar", "bajar", "bastar", "bañar", "beber", "buscar", "caer", "callar", "calmar", "cambiar", "caminar", "campar", "cantar", "cazar", "cenar", "centrar", "cercar", "cerrar", "citar", "cocinar", "coger", "comenzar", "comer", "comparar", "comprar", "conducir", "conocer", "conseguir", "contar", "continuar", "correr", "cortar", "coser", "costar", "crear", "creer", "cuidar", "culpar", "dar", "dañar", "deber", "decidir", "decir", "dejar", "descansar", "describir", "desear", "destruir", "disculpar", "divertir", "doler", "dormir", "durar", "elegir", "empezar", "empujar", "encantar", "encontrar", "enseñar", "entender", "entrar", "equipar", "esconder", "escribir", "escuchar", "esperar", "esposar", "estar", "estudiar", "existir", "explicar", "extrañar", "faltar", "forzar", "funcionar", "ganar", "gritar", "gustar", "haber", "hablar", "hacer", "importar", "intentar", "ir", "jugar", "jurar", "lamentar", "lanzar", "largar", "lavar", "leer", "limpiar", "llamar", "llegar", "llenar", "llevar", "llorar", "luchar", "mandar", "matar", "mejor", "mejorar", "mentir", "mirar", "morir", "mostrar", "mover", "necesitar", "negociar", "nombrar", "ocurrir", "odiar", "ofrecer", "olvidar", "orar", "oír", "pagar", "parar", "parecer", "partir", "pasar", "pelar", "pelear", "peligrar", "penar", "pensar", "perder", "perdonar", "permitir", "pisar", "poder", "poner", "preferir", "preguntar", "preocupar", "preparar", "probar", "prometer", "pulsar", "quedar", "quemar", "querer", "recibir", "reconocer", "recordar", "regalar", "regresar", "repetir", "responder", "reír", "saber", "sacar", "salir", "saltar", "salvar", "seguir", "sentar", "sentir", "ser", "significar", "sonar", "sonreír", "soñar", "suceder", "suponer", "tardar", "temer", "tener", "terminar", "tirar", "tocar", "tomar", "trabajar", "traer", "tratar", "usar", "valer", "vender", "venir", "ver", "viajar", "visitar", "vivir", "volver"]
    ```

*   ### Diseño y desarrollo de la interfaz:
    Este grupo se encarga de diseñar y desarrollar la interfaz donde se va a ejecutar el traductor, van a trabajar:
    * Katherine Leal
    * José Castro
    * Andreas Peralta

    Usando HTML y CSS nada más para mantenerlo simple al momento de entregarlo. Para la salida y entrada del texto usen etiquetas de textarea, no inputs.

*   ### Desarrollo de las fases del traductor:
    Este grupo es para el desarrollo e implementación de las fases del traductor, se va a utilizar una API para simplificar la tabla de símbolos.
    * Marcelo León
    * José Araya


###
Al final se va a tener que realizar un algoritmo para leer un archivo de texto y que retorne un string al formato que acepte nuestro traductor. 
