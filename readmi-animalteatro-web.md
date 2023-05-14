<a name="br1"></a>Mi READMI sobre mi proyecto de Desarrollo Web

¡Hola! Soy Laura Loredo Rubio, actriz, Licenciada en Artes, docente y, ahora, aspirante a front-end developer. Este es el proyecto que hice para el curso de **Desarrollo Web de Coder House**.

Desde hace más de un año trabajo como productora, actriz y CM en **Animal Teatro**, un espacio cultural que queda en el barrio de Boedo, y se me ocurrió que podía venirle muy bien tener una web.

Mis primeros pasos

` `En mis primeras clases intenté hacer al pie de la letra todo lo que la profesora hacía, copiando susdiseños para sentir que así me apropiaba de lenguajes tan complejos como los de HTML y CSS. Es por elloque mis primeros wireframes variaron en relación a lo que la web quedó al ﬁnal. No sólo porque añadímuchas más páginas, sino porque pensé en la especiﬁcidad del teatro y lo que podría necesitar su página anivel de funcionalidad y diseño.

Así fue mi primer boceto

` `Al ir soltándome más en ambos lenguajes, fui **investigando por mi cuenta, googleando,** ydescubriendo etiquetas no vistas en clase como <span>, a las que hipervinculé a páginas o a un archivo pdf(spoiler alert: luego la reemplace por un <button>)

` `También recordé lo importante de **investigar en páginas aﬁnes**, así que entré a las web de Timbre 4,Teatro Ciego, Teatro Nacional Cervantes, y Teatro San Martín, explorando cómo las maquetaban con lasherramientas para desarrolladores. Les fui **mostrando mis avances** a diversos amigxs para tener sufeedback y entender qué podía hacerle falta a la página. Usé mucho el **Coder Ask**, un Whastapp deCoderhouse que me fue de mucha ayuda para los momentos de crisis.

"Maldición Grids, maldición Git, pero hola SCSS, how you doing"

` `Grids y Git fueron contenidos que me costaron mucho. Para grid cree una **carpeta aparte** y empecé de"cero". Necesitaba ir probando sin arruinar mi proyecto original Todavía me queda la carpeta "prueba-de-contenidos", donde voy experimentando diversas cosas y luego, si me gustan y funcionas, las vuelco en miproyecto principal. Con Git sentí que me hablaban en otro idioma, uno que no dominaba en lo absoluto. Perogracias a la paciencia (y quizás un poco a la terquedad y a la autoexigencia que conﬁeso que tengo), logréentenderlo.




<a name="br2"></a> **SCSS fue amor a primera vista**. Aunque no lo entendí desde el vamos y tuve que ver la grabación dela clase nuevamente, el hecho de que que existiese un preprocesador de CSS que me permitiese ordenar lacaótica hoja de estilo, me dio paz mental. En mi computadora tengo todo ordenado en carpetas ysubcarpetas, los Excel formulados son mis mejores amigos, y esto sentí que iba en esa línea.

Quiero mi lightbox

` `En un afterclass la profesora había explicado cómo hacer un **ligthbox**. Desde el momento en quetuvimos esa clase hasta que ﬁnalmente la realicé, pasaron casi dos meses, pero supe desde siempre cuálsería su ﬁn. En Animal todos los ciclos que produce el teatro se registran con un fotógrafo que va a cubrir lafunción: hay, así, una gran cantidad de fotografías en alta calidad, un registro de todo aquello que hacemos yque merecía ser mostrado en una hermosa galería.

` `Solo para la parte de la galería cree tres wireframes ya que el encastre de fotografías en diverso tamañoparecían ser difíciles de pensar sin una ayuda visual. Estos son los wireframes.

Desktop: <https://wireframe.cc/62wd8f>

Formato mediano: <https://wireframe.cc/RHVSSd>

Mobile: <https://wireframe.cc/9QaFQy>

Algunas dudas e interrogantes

` `Seguro debo tener errores de principiante, hubieron momentos en que dudé en cómo resolver algunasdiﬁcultades. Fueron muchas. Comento alguna a modo de ejemplo.

` `Cuando hice la galería en la pestaña “nuestras producciones”, pensé que, como la galería iba a serarmada con grids, correspondía que utilizase el mixin de grid que había armado, y luego personalizarlo en lapágina de sccs hecha para todos los grids del proyecto. Pero **¿cómo indicar la propiedad de object ﬁtsolo para esas fotos?** La profesora en clase había mostrado una ruta *(main section img)* que, en mi proyecto,afectaría a un montón de imágenes (no solo las de la galería) Por otro lado, si ponía esas imágenes en webp(como hice con la gran mayoría de las imgs de la web) se verían afectadas por un border radius que le habíaaplicado a todos los archivos webp usando el selector **[src$=".webp"]** Fue allí que decidí dejar las fotos de lagalería como jpg (optimizadas), y aplicar también selector universal para los arhivos jpg dado que serían lasúnicas con ese formato en toda la página.

` `Así han habido muchos momentos, momentos de decisiones que me pregunto si hice bien. Acáestamos, aprendiendo.

Esta es la web ﬁnal.

¡Gracias por todo!
