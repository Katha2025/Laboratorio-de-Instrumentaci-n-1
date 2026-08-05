# Laboratorio-de Instrumentación 1
# Parte A
# 1) Revisión de la literatura

El proceso respiratorio constituye una de las funciones fisiológicas más importantes del organismo ya que permite el intercambio continuo de oxígeno (O₂) y dióxido de carbono (CO₂) entre el medio ambiente y los tejidos. Este proceso asegura el suministro de oxígeno necesario para la respiración celular y la producción de ATP, al mismo tiempo que elimina el dióxido de carbono generado por el metabolismo. Según Hall y Hall (2021), la respiración comprende una serie de eventos coordinados que incluyen la ventilación pulmonar, el intercambio gaseoso, el transporte de gases por la sangre y la respiración tisular. Desde el punto de vista de la ingeniería biomédica y de la fisiología, estos mecanismos están gobernados por principios físicos como la dinámica de fluidos, las leyes de los gases, la elasticidad de los tejidos y los fenómenos de difusión. Estudios recientes publicados en PubMed resaltan que comprender estas variables físicas es fundamental para el desarrollo de dispositivos de soporte ventilatorio, sistemas de monitoreo respiratorio y modelos fisiológicos aplicados al diagnóstico clínico.

**- Ventilación Pulmonar**:


La ventilación pulmonar corresponde al movimiento de aire entre la atmósfera y los pulmones y constituye la primera etapa del proceso respiratorio. Este fenómeno ocurre gracias a la acción coordinada del diafragma y de los músculos intercostales, los cuales modifican el volumen de la cavidad torácica. Durante la inspiración, la contracción del diafragma incrementa el volumen intratorácico y produce una disminución de la presión alveolar con respecto a la presión atmosférica, permitiendo el ingreso del aire. En la espiración sucede el fenómeno contrario: la relajación de estos músculos reduce el volumen pulmonar, aumenta la presión alveolar y favorece la salida del aire. Este comportamiento está explicado por la Ley de Boyle, la cual establece que, a temperatura constante, la presión de un gas es inversamente proporcional a su volumen.

Desde el punto de vista mecánico, la ventilación depende de la interacción entre las propiedades elásticas del pulmón, la resistencia de las vías respiratorias y el trabajo realizado por los músculos respiratorios. Kreit y Eschenbacher describen que la ventilación espontánea representa un equilibrio entre la presión generada por la musculatura respiratoria y las fuerzas elásticas del sistema respiratorio, mientras que cualquier alteración en estos componentes modifica la eficiencia del intercambio gaseoso.

**- Intercambio Gaseoso**:

Una vez que el aire alcanza los alvéolos pulmonares, ocurre el intercambio de gases entre el aire alveolar y la sangre de los capilares pulmonares. Este proceso se lleva a cabo por difusión pasiva y está gobernado por la Ley de Fick, la cual establece que la velocidad de difusión depende del área disponible para el intercambio, del espesor de la membrana alveolocapilar, del coeficiente de difusión del gas y del gradiente de presión parcial existente entre ambos compartimentos.

El oxígeno difunde desde los alvéolos hacia la sangre debido a que su presión parcial es mayor en el aire alveolar que en la sangre venosa, mientras que el dióxido de carbono sigue el gradiente opuesto para ser eliminado durante la espiración. Aunque el CO₂ posee un gradiente de presión menor, su elevada capacidad de difusión permite que el intercambio ocurra de manera eficiente. Diversos estudios publicados en PubMed señalan que alteraciones en cualquiera de estas variables físicas disminuyen significativamente la eficiencia respiratoria y favorecen la aparición de insuficiencia respiratoria.

**- Variables físicas utilizadas en el proceso gaseoso**:


El proceso respiratorio depende de múltiples variables físicas que determinan la eficiencia de la ventilación y del intercambio gaseoso. La primera de ellas es la presión, considerada el principal motor del movimiento del aire. Las diferencias entre la presión atmosférica, la presión alveolar y la presión intrapleural generan los gradientes necesarios para que el aire entre o salga de los pulmones. Sin estos gradientes de presión no sería posible la ventilación.

Otra variable fundamental es el volumen pulmonar, el cual representa la cantidad de aire contenida en los pulmones durante las diferentes fases de la respiración. Entre los parámetros más utilizados se encuentran el volumen corriente, el volumen residual y las capacidades pulmonares, las cuales son ampliamente empleadas para evaluar la función respiratoria mediante pruebas como la espirometría.

El flujo de aire también constituye una variable esencial, ya que describe la velocidad con la que el aire circula por las vías respiratorias. Este flujo depende directamente del gradiente de presión y de la resistencia al paso del aire. La resistencia, por su parte, está determinada principalmente por el diámetro de las vías respiratorias, la longitud del árbol bronquial y la viscosidad del aire. Enfermedades obstructivas como el asma incrementan considerablemente esta resistencia, reduciendo el flujo respiratorio.

Igualmente importante es la distensibilidad pulmonar (compliance), definida como la facilidad con la que el pulmón puede expandirse cuando aumenta la presión transpulmonar. Esta propiedad depende de la elasticidad del tejido pulmonar y de la presencia del surfactante, el cual disminuye la tensión superficial de los alvéolos y reduce el trabajo respiratorio. De forma complementaria, la elasticidad pulmonar permite que los pulmones recuperen su tamaño original durante la espiración.

Finalmente, las presiones parciales de oxígeno y dióxido de carbono, junto con la relación ventilación/perfusión (V/Q), representan variables indispensables para mantener un intercambio gaseoso eficiente. Una adecuada correspondencia entre la ventilación alveolar y el flujo sanguíneo pulmonar optimiza la oxigenación de la sangre y la eliminación del dióxido de carbono. Diversas revisiones recientes destacan que el análisis conjunto de la presión, el flujo, el volumen y la resistencia constituye la base del diseño de ventiladores mecánicos y de otros sistemas biomédicos utilizados en el soporte respiratorio.

**- Regulación del proceso respiratorio**:

La respiración está regulada por centros nerviosos ubicados en el bulbo raquídeo y la protuberancia, los cuales ajustan continuamente la frecuencia y la profundidad respiratoria según las necesidades metabólicas del organismo. Estos centros reciben información proveniente de quimiorreceptores centrales y periféricos que responden principalmente a cambios en la presión parcial de dióxido de carbono, la presión parcial de oxígeno y el pH sanguíneo. Cuando aumenta la concentración de CO₂ o disminuye el pH, el sistema nervioso incrementa la ventilación para restablecer el equilibrio fisiológico. Estudios recientes indican que el desarrollo de la insuficiencia respiratoria ocurre cuando existe un desequilibrio entre la carga mecánica del sistema respiratorio y la capacidad de los músculos respiratorios para generar la presión necesaria para la ventilación.

# 2) Selección de sensor

Para la selección del sensor se evaluaron diferentes alternativas con el fin de identificar la que ofreciera un mejor desempeño para el monitoreo del patrón respiratorio durante la práctica de laboratorio, entre las opciones consideradas se encontraban el sensor de fuerza resistivo FSR402 y el sensor MQ-2. Tras comparar las características de ambos dispositivos, se optó por el sensor de fuerza resistivo, debido a que permite detectar las variaciones mecánicas producidas por la expansión y contracción del tórax durante la respiración de forma más precisa. Además, este sensor ofrece una adaptación más ergonómica al cuerpo del sujeto, disminuyendo las molestias durante la adquisición de la señal y reduciendo la posibilidad de interferencias ocasionadas por movimientos indeseados.

En consecuencia, este proporcionó una señal respiratoria más estable y representativa, facilitando la obtención de la frecuencia respiratoria y el análisis del patrón respiratorio requerido en la práctica. 

<img width="732" height="732" alt="image" src="https://github.com/user-attachments/assets/7e24a0ed-e56e-456e-853e-157eb8601979" />

**Imagen 1** *sensor de fuerza resistivo FSR402.*

*Tomado de: https://www.zamux.co/sensor-de-fuerza-resistivo-fsr402*


# 3) Diseño del sistema

Con relación al diseño del sistema, inicialmente se planteó implementar un puente de Wheatstone con el fin de acondicionar la señal proveniente del sensor resistivo. Sin embargo, debido a la simplicidad del montaje y a que el sensor resistivo no posee una polaridad definida, se optó por utilizar un divisor de voltaje, el cual permitía obtener una variación de tensión proporcional a los cambios de resistencia del sensor.

Para el diseño del divisor de voltaje, primero se midió la resistencia del sensor utilizando un multímetro, obteniéndose un valor aproximado de 220 Ω. Con base en esta medición, se seleccionó una resistencia fija de 220 Ω para conformar el divisor, con el fin de obtener un punto de operación adecuado y maximizar la sensibilidad del circuito frente a las variaciones producidas por la respiración.

Posteriormente, para la adquisición de la señal se empleó el microcontrolador NI DAQmx, encargado de capturar la señal analógica generada por el divisor de voltaje y convertirla al dominio digital, una vez digitalizada la señal pudo ser procesada y analizada en el computador, permitiendo observar el comportamiento del patrón respiratorio y calcular la frecuencia respiratoria durante las dos diferentes condiciones evaluadas.


<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/1ebef4ae-e72b-406a-ab9a-502729053fc4" />

**Imagen 2** *Microcontrolador NI DAQMx.*

*Tomado de: https://www.digikey.com/en/products/detail/ni/782602-01/12817647*


<img width="555" height="312" alt="image" src="https://github.com/user-attachments/assets/1836559d-9071-4441-9362-f7c04407cbf6" />

**Imagen 3** *Circuito del divisor de voltaje.*

*Tomado de: Elaboración propia*



# 4) Montaje y prueba del sensor



# 5) Adquisición de la señal respiratoria

# Parte B

1. cÓDIGO DE MATLAB
2. fRECUENCIAS

# Parte C
# Procedimiento
# Análisis de los Resultados
# Conclusiones


## PREGUNTAS A DISCUSIÓN

• **Pregunta 1: ¿Son los patrones respiratorios y frecuencias respiratorias
iguales o diferentes en cada caso? ¿A qué se debe esto?**


• **Pregunta 2: ¿Cuáles serían las ventajas y desventajas de emplear múltiples
sensores para el monitoreo del proceso respiratorio? ¿Cuáles podrían ser
las razones?**

