# MONITOREO DEL PATRÓN Y FRECUENCIA RESPIRATORIA
# Parte A
# 1) Revisión de la literatura

El proceso respiratorio constituye una de las funciones fisiológicas más importantes del organismo ya que permite el intercambio continuo de oxígeno (O₂) y dióxido de carbono (CO₂) entre el medio ambiente y los tejidos. Este proceso asegura el suministro de oxígeno necesario para la respiración celular y la producción de ATP, al mismo tiempo que elimina el dióxido de carbono generado por el metabolismo. Según Hall y Hall (2021), la respiración comprende una serie de eventos coordinados que incluyen la ventilación pulmonar, el intercambio gaseoso, el transporte de gases por la sangre y la respiración tisular. Desde el punto de vista de la ingeniería biomédica y de la fisiología, estos mecanismos están gobernados por principios físicos como la dinámica de fluidos, las leyes de los gases, la elasticidad de los tejidos y los fenómenos de difusión; estudios recientes publicados en PubMed resaltan que comprender estas variables físicas es fundamental para el desarrollo de dispositivos de soporte ventilatorio, sistemas de monitoreo respiratorio y modelos fisiológicos aplicados al diagnóstico clínico.[1]

**- Ventilación Pulmonar**:


La ventilación pulmonar corresponde al movimiento de aire entre la atmósfera y los pulmones y constituye la primera etapa del proceso respiratorio, este fenómeno ocurre gracias a la acción coordinada del diafragma y de los músculos intercostales, los cuales modifican el volumen de la cavidad torácica. Durante la inspiración, la contracción del diafragma incrementa el volumen intratorácico y produce una disminución de la presión alveolar con respecto a la presión atmosférica, permitiendo el ingreso del aire, en la espiración sucede el fenómeno contrario: la relajación de estos músculos reduce el volumen pulmonar, aumenta la presión alveolar y favorece la salida del aire. Este comportamiento está explicado por la Ley de Boyle, la cual establece que, a temperatura constante, la presión de un gas es inversamente proporcional a su volumen.[2]

Desde el punto de vista mecánico, la ventilación depende de la interacción entre las propiedades elásticas del pulmón, la resistencia de las vías respiratorias y el trabajo realizado por los músculos respiratorios. Kreit y Eschenbacher describen que la ventilación espontánea representa un equilibrio entre la presión generada por la musculatura respiratoria y las fuerzas elásticas del sistema respiratorio, mientras que cualquier alteración en estos componentes modifica la eficiencia del intercambio gaseoso. [2]

**- Intercambio Gaseoso**:

Una vez que el aire alcanza los alvéolos pulmonares, ocurre el intercambio de gases entre el aire alveolar y la sangre de los capilares pulmonares. Este proceso se lleva a cabo por difusión pasiva y está gobernado por la Ley de Fick, la cual establece que la velocidad de difusión depende del área disponible para el intercambio, del espesor de la membrana alveolocapilar, del coeficiente de difusión del gas y del gradiente de presión parcial existente entre ambos compartimentos.[3]

El oxígeno difunde desde los alvéolos hacia la sangre debido a que su presión parcial es mayor en el aire alveolar que en la sangre venosa, mientras que el dióxido de carbono sigue el gradiente opuesto para ser eliminado durante la espiración. Aunque el CO₂ posee un gradiente de presión menor, su elevada capacidad de difusión permite que el intercambio ocurra de manera eficiente. Diversos estudios publicados en PubMed señalan que alteraciones en cualquiera de estas variables físicas disminuyen significativamente la eficiencia respiratoria y favorecen la aparición de insuficiencia respiratoria.[3]

**- Variables físicas utilizadas en el proceso respiratorio**:


El proceso respiratorio depende de múltiples variables físicas que determinan la eficiencia de la ventilación y del intercambio gaseoso. La primera de ellas es la presión, considerada el principal motor del movimiento del aire. Las diferencias entre la presión atmosférica, la presión alveolar y la presión intrapleural generan los gradientes necesarios para que el aire entre o salga de los pulmones. Sin estos gradientes de presión no sería posible la ventilación.[4]

Otra variable fundamental es el volumen pulmonar, el cual representa la cantidad de aire contenida en los pulmones durante las diferentes fases de la respiración. Entre los parámetros más utilizados se encuentran el volumen corriente, el volumen residual y las capacidades pulmonares, las cuales son ampliamente empleadas para evaluar la función respiratoria mediante pruebas como la espirometría.[4]

El flujo de aire también constituye una variable esencial, ya que describe la velocidad con la que el aire circula por las vías respiratorias. Este flujo depende directamente del gradiente de presión y de la resistencia al paso del aire. La resistencia, por su parte, está determinada principalmente por el diámetro de las vías respiratorias, la longitud del árbol bronquial y la viscosidad del aire. Enfermedades obstructivas como el asma incrementan considerablemente esta resistencia, reduciendo el flujo respiratorio.[4]

Igualmente importante es la distensibilidad pulmonar (compliance), definida como la facilidad con la que el pulmón puede expandirse cuando aumenta la presión transpulmonar. Esta propiedad depende de la elasticidad del tejido pulmonar y de la presencia del surfactante, el cual disminuye la tensión superficial de los alvéolos y reduce el trabajo respiratorio. De forma complementaria, la elasticidad pulmonar permite que los pulmones recuperen su tamaño original durante la espiración.[4]

Finalmente, las presiones parciales de oxígeno y dióxido de carbono, junto con la relación ventilación/perfusión (V/Q), representan variables indispensables para mantener un intercambio gaseoso eficiente. Una adecuada correspondencia entre la ventilación alveolar y el flujo sanguíneo pulmonar optimiza la oxigenación de la sangre y la eliminación del dióxido de carbono. Diversas revisiones recientes destacan que el análisis conjunto de la presión, el flujo, el volumen y la resistencia constituye la base del diseño de ventiladores mecánicos y de otros sistemas biomédicos utilizados en el soporte respiratorio.[4]

**- Regulación del proceso respiratorio**:

La respiración está regulada por centros nerviosos ubicados en el bulbo raquídeo y la protuberancia, los cuales ajustan continuamente la frecuencia y la profundidad respiratoria según las necesidades metabólicas del organismo. Estos centros reciben información proveniente de quimiorreceptores centrales y periféricos que responden principalmente a cambios en la presión parcial de dióxido de carbono, la presión parcial de oxígeno y el pH sanguíneo. Cuando aumenta la concentración de CO₂ o disminuye el pH, el sistema nervioso incrementa la ventilación para restablecer el equilibrio fisiológico. Estudios recientes indican que el desarrollo de la insuficiencia respiratoria ocurre cuando existe un desequilibrio entre la carga mecánica del sistema respiratorio y la capacidad de los músculos respiratorios para generar la presión necesaria para la ventilación.[5]

# 2) Selección de sensor

Para la selección del sensor se evaluaron diferentes alternativas con el fin de identificar la que ofreciera un mejor desempeño para el monitoreo del patrón respiratorio durante la práctica de laboratorio, entre las opciones consideradas se encontraban el sensor de fuerza resistivo FSR402 y el sensor MQ-2. Tras comparar las características de ambos dispositivos, se optó por el sensor de fuerza resistivo, debido a que permite detectar las variaciones mecánicas producidas por la expansión y contracción del tórax durante la respiración de forma más precisa. Además, este sensor ofrece una adaptación más ergonómica al cuerpo del sujeto, no invasiva, disminuyendo las molestias durante la adquisición de la señal y reduciendo la posibilidad de interferencias ocasionadas por movimientos indeseados.

El FSR402 funciona mediante un principio piezorresistivo, en el cual la resistencia eléctrica del material cambia cuando se aplica una fuerza o presión sobre su superficie. Cuando el tórax se expande durante la inspiración, la banda ejerce una mayor presión sobre el sensor, provocando una disminución de su resistencia. Durante la espiración, la presión disminuye y la resistencia vuelve a incrementar. Estas variaciones de resistencia pueden convertirse en cambios de voltaje mediante un circuito divisor de tensión, permitiendo obtener una señal eléctrica relacionada con los movimientos respiratorios del sujeto.[6]


En consecuencia, este proporcionó una señal respiratoria más estable y representativa, facilitando la obtención de la frecuencia respiratoria y el análisis del patrón respiratorio requerido en la práctica. 

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/7e24a0ed-e56e-456e-853e-157eb8601979" />

**Imagen 1.** *sensor de fuerza resistivo FSR402.*

*Tomado de: https://www.zamux.co/sensor-de-fuerza-resistivo-fsr402.*


# 3) Diseño del sistema

Con relación al diseño del sistema, inicialmente se planteó implementar un puente de Wheatstone con el fin de acondicionar la señal proveniente del sensor resistivo. Sin embargo, debido a la simplicidad del montaje y a que el sensor resistivo no posee una polaridad definida, se optó por utilizar un divisor de voltaje, el cual permitía obtener una variación de tensión proporcional a los cambios de resistencia del sensor.

Para el diseño del divisor de voltaje, primero se midió la resistencia del sensor utilizando un multímetro, obteniéndose un valor aproximado de 220 Ω. Con base en esta medición, se seleccionó una resistencia fija de 220 Ω para conformar el divisor, con el fin de obtener un punto de operación adecuado y maximizar la sensibilidad del circuito frente a las variaciones producidas por la respiración.

Posteriormente, para la adquisición de la señal se empleó el dispositivo de adquisición de datos (DAQ), encargado de capturar la señal analógica generada por el divisor de voltaje y convertirla al dominio digital, una vez digitalizada la señal pudo ser procesada y analizada en el computador, permitiendo observar el comportamiento del patrón respiratorio y calcular la frecuencia respiratoria durante las dos diferentes condiciones evaluadas.


<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/1ebef4ae-e72b-406a-ab9a-502729053fc4" />

**Imagen 2.** *Dispositivo de adquisición de datos (DAQ) de National Instruments.*

*Tomado de: https://www.digikey.com/en/products/detail/ni/782602-01/12817647.*


<img width="555" height="312" alt="image" src="https://github.com/user-attachments/assets/1836559d-9071-4441-9362-f7c04407cbf6" />

**Imagen 3.** *Circuito del divisor de voltaje.*

*Tomado de: Elaboración propia.*



# 4) Montaje y prueba del sensor (Foto)

<img width="400" alt="image" src="https://github.com/user-attachments/assets/7ae43601-8a1b-4053-b6a5-21aed5002b84" />

**Imagen 4.** *Montaje.*

*Tomado de: Elaboración propia.*

<img width="400" alt="image" src="https://github.com/user-attachments/assets/dd2a6470-92b2-4aa3-b7ac-d7cecc23145a" />

**Imagen 5.** *Prueba del sensor.*

*Tomado de: Elaboración propia.*



# 5) Adquisición de la señal respiratoria 

Para empezar con la adquisición de la señal a partir del circuito antes hablado se uso el programa base NI-MAX que utiliza la DAQ para poder visualizar la señal antes de capturarla:

- Primero se visualizó con el sujeto respirando normal:
  
 <img width="400" alt="image" src="https://github.com/user-attachments/assets/966073e9-0d07-426e-8451-58ce8d1be8fd" />

 **Imagen 6.** *Señal de respiración tranquila de prueba en NI-MAX.*
 
*Tomado de: Elaboración propia.*

- Luego , el participante se puso a leer en voz alta :
  
<img width="400" alt="image" src="https://github.com/user-attachments/assets/489020ea-3772-42ff-bf86-07de40a1bc76" />

**Imagen 7.** *Señal de respiración mientras lee en voz alta de prueba en NI-MAX.*

*Tomado de: Elaboración propia.*
  
# Parte B
1. Código de matlab
   Para poder adquirir las señales se utilizó este código de matlab
   
``` matlab
clear;
clc;
close all;

dq = daq("ni");
addinput(dq, "Dev8", "ai0", "Voltage");

dq.Rate = 100;    % Frecuencia de muestreo en Hz
duracion = 30;    % Tiempo de adquisición en segundos

disp("Iniciando captura de 30 segundos...");

datos = read(dq, seconds(duracion), OutputFormat="Timetable");

disp("Captura finalizada.");

tiempo = seconds(datos.Time);
voltaje = datos{:,1};
figure;

plot(tiempo, voltaje, "LineWidth", 1);

title("Señal respiratoria sin filtrar");
xlabel("Tiempo (s)");
ylabel("Voltaje (V)");

grid on;
xlim([0 duracion]);

ylim([0 5]);    

%Para guardar el archivo
fecha = string(datetime("now", ...
    "Format","yyyy-MM-dd_HH-mm-ss"));

nombreArchivo = "respiracion_" + fecha + ".mat";

save(nombreArchivo, "datos");

disp("Archivo guardado como:");
disp(nombreArchivo);

```
Dando como resultado:

Primero para la persona respirando tranquilamente:

<img width="400" alt="image" src="https://github.com/user-attachments/assets/c23c45f1-a562-4027-873a-a97e9bb9b9ab" />


**Imagen 8.** *Señal de respiración tranquila capturada en matlab sin filtrar.*

*Tomado de: Elaboración propia.*


Y luego para la persona que lee en voz alta:


<img width="400" alt="image" src="https://github.com/user-attachments/assets/3c4de9e8-68f1-4d8c-98cf-a86f86afcc09" />


**Imagen 9.** *Señal de respiración mientras se lee en voz alta capturada en matlab sin filtrar.*

*Tomado de: Elaboración propia.*



# Parte C

Al notar la presencia de ruido en la señal, se implementó un filtro pasa-bajas Butterworth con una frecuencia de corte de 1 Hz, debido a que la señal respiratoria se concentra principalmente en el intervalo de 0,1 a 0,5 Hz [7].
La selección de una frecuencia de corte ligeramente superior al rango respiratorio permite conservar la morfología de la señal y sus variaciones fisiológicas, mientras se atenúan componentes de alta frecuencia asociadas al ruido eléctrico, vibraciones y movimientos indeseados del sensor. De esta manera, se obtiene una señal más limpia sin afectar significativamente la información correspondiente a los ciclos de inspiración y espiración.


``` matlab

clear;
clc;
close all;

archivo = 'respiracion_2026-08-06_09-04-34.mat';

S= load(archivo);


if ~isfield(S, 'datos')
    error('El archivo no contiene una variable llamada "datos".');
end

datos = S.datos;

disp('Variables encontradas en el archivo:');
disp(datos.Properties.VariableNames);

senal = double(datos{:,1});
senal = senal(:);

tiempoOriginal = datos.Properties.RowTimes;
tiempo = seconds(tiempoOriginal - tiempoOriginal(1));
tiempo = double(tiempo(:));


validos = isfinite(tiempo) & isfinite(senal);

tiempo = tiempo(validos);
senal = senal(validos);

senal = fillmissing(senal, 'linear');

dt = median(diff(tiempo));
fs = 1 / dt;

fprintf('Frecuencia de muestreo: %.2f Hz\n', fs);
fprintf('Duración de la señal: %.2f segundos\n', tiempo(end));

diferencias = diff(tiempo);

if max(abs(diferencias - dt)) > 0.05 * dt

    disp('El tiempo no es completamente uniforme.');
    disp('Se realizará una interpolación.');

    tiempoUniforme = (tiempo(1):dt:tiempo(end))';

    senal = interp1( ...
        tiempo, ...
        senal, ...
        tiempoUniforme, ...
        'pchip');

    tiempo = tiempoUniforme;
end


fc = 1;       % Frecuencia de corte en Hz
orden = 4;

if fc >= fs/2
    error(['La frecuencia de corte debe ser menor que fs/2. ', ...
           'Frecuencia de muestreo: %.2f Hz'], fs);
end

Wn = fc / (fs/2);

[b, a] = butter(orden, Wn, 'low');


senalFiltrada = filtfilt(b, a, -(senal));


inicioVentana = 0;
duracionVentanaDeseada = 30;

finVentana = min( ...
    inicioVentana + duracionVentanaDeseada, ...
    tiempo(end));

indicesVentana = ...
    tiempo >= inicioVentana & tiempo <= finVentana;

tiempoVentana = tiempo(indicesVentana);
senalOriginalVentana = senal(indicesVentana);
senalFiltradaVentana = senalFiltrada(indicesVentana);

duracionVentanaReal = ...
    tiempoVentana(end) - tiempoVentana(1);

fprintf('Ventana analizada: %.2f a %.2f segundos\n', ...
    tiempoVentana(1), tiempoVentana(end));

fprintf('Duración real de la ventana: %.2f segundos\n', ...
    duracionVentanaReal);


distanciaMinimaPicos = 2;  % segundos


amplitudVentana = ...
    max(senalFiltradaVentana) - min(senalFiltradaVentana);

prominenciaMinima = 0.15 * amplitudVentana;

[picosRespiratorios, tiemposPicos] = findpeaks( ...
    senalFiltradaVentana, ...
    tiempoVentana, ...
    'MinPeakDistance', distanciaMinimaPicos, ...
    'MinPeakProminence', prominenciaMinima);


numeroRespiraciones = length(picosRespiratorios);

respiracionesPorMinuto = ...
    numeroRespiraciones * (60 / duracionVentanaReal);

fprintf('\n-------------------------------------\n');
fprintf('Respiraciones detectadas: %d\n', ...
    numeroRespiraciones);

fprintf('Respiraciones por minuto: %.1f RPM\n', ...
    respiracionesPorMinuto);

fprintf('-------------------------------------\n');


figure( ...
    'Name', 'Detección de respiraciones', ...
    'NumberTitle', 'off', ...
    'Color', 'black');

tiledlayout(2,1, 'TileSpacing', 'compact');


nexttile;

plot( ...
    tiempoVentana, ...
    senalOriginalVentana, ...
    'LineWidth', 0.7);

title('Señal respiratoria original — ventana de 30 segundos');
xlabel('Tiempo (s)');
ylabel('Voltaje (V)');

grid on;
xlim([tiempoVentana(1), tiempoVentana(end)]);


nexttile;

plot( ...
    tiempoVentana, ...
    senalFiltradaVentana, ...
    'LineWidth', 2);

hold on;

plot( ...
    tiemposPicos, ...
    picosRespiratorios, ...
    'ro', ...
    'MarkerSize', 8, ...
    'MarkerFaceColor', 'r');





% ESPECTRO DE FRECUENCIA DE LA SEÑAL FILTRADA

senalParaFFT = senalFiltradaVentana - mean(senalFiltradaVentana);

N = length(senalParaFFT);
ventanaHann = hann(N);
senalVentaneada = senalParaFFT .* ventanaHann;

% Calcular la transformada rápida de Fourier
Y = fft(senalVentaneada);

P2 = abs(Y / N);

P1 = P2(1:floor(N/2) + 1);

if length(P1) > 2
    P1(2:end-1) = 2 * P1(2:end-1);
end


frecuencias = fs * (0:floor(N/2)) / N;


indicesBusqueda = ...
    frecuencias > 0 & ...
    frecuencias <= fc;


frecuenciasBusqueda = frecuencias(indicesBusqueda);
amplitudesBusqueda = P1(indicesBusqueda);


if isempty(frecuenciasBusqueda)
    error('No existen frecuencias disponibles en el rango seleccionado.');
end

[amplitudDominante, indiceDominante] = ...
    max(amplitudesBusqueda);

frecuenciaDominante = ...
    frecuenciasBusqueda(indiceDominante);

rpmFFT = frecuenciaDominante * 60;

fprintf('\n-------------------------------------\n');
fprintf('ANÁLISIS EN FRECUENCIA\n');
fprintf('Punto más alto: %.3f Hz\n', ...
    frecuenciaDominante);

fprintf('Amplitud del punto más alto: %.5f\n', ...
    amplitudDominante);

fprintf('Equivalencia: %.1f RPM\n', ...
    rpmFFT);

fprintf('-------------------------------------\n');

figure( ...
    'Name', 'Espectro de frecuencia', ...
    'NumberTitle', 'off', ...
    'Color', 'black');


plot( ...
    frecuencias, ...
    P1, ...
    'LineWidth', 1.8);

hold on;

plot( ...
    frecuenciaDominante, ...
    amplitudDominante, ...
    'ro', ...
    'MarkerSize', 10, ...
    'MarkerFaceColor', 'r');


xline( ...
    fc, ...
    '--', ...
    sprintf('Corte = %.1f Hz', fc), ...
    'LineWidth', 1.5);

textoPico = sprintf( ...
    '  %.3f Hz\n  %.1f RPM', ...
    frecuenciaDominante, ...
    rpmFFT);

text( ...
    frecuenciaDominante, ...
    amplitudDominante, ...
    textoPico, ...
    'FontSize', 11, ...
    'FontWeight', 'bold', ...
    'VerticalAlignment', 'bottom', ...
    'HorizontalAlignment', 'left');

hold off;

title(sprintf( ...
    ['Espectro de la señal filtrada — ' ...
     'frecuencia dominante: %.3f Hz = %.1f RPM'], ...
    frecuenciaDominante, ...
    rpmFFT));

xlabel('Frecuencia (Hz)');
ylabel('Amplitud');

legend( ...
    'Espectro filtrado', ...
    'Punto más alto', ...
    'Frecuencia de corte', ...
    'Location', 'best');

grid on;
box on;

xlim([0, min(fc + 0.5, fs/2)]);
ylim([0, amplitudDominante * 1.15]);

```

Dando como resultado las siguientes señales:


<img width="400" alt="image" src="https://github.com/user-attachments/assets/a6585d54-29b4-42f6-a54c-0ed4f90b7101" />


**Imagen 10.** *Señal de respiración tranquila después de filtrarla y corregir la orientación*

*Tomado de: Elaboración propia.*

y su respectivo espectro de frecuencia:

<img width="400" alt="image" src="https://github.com/user-attachments/assets/1df75169-4dfa-44a7-be7a-c40c703ad51b" />


**Imagen 11.** *Espectro de frecuencia de la señal de respiración  tranquila después de filtrarla*

*Tomado de: Elaboración propia.*

<img width="400" alt="image" src="https://github.com/user-attachments/assets/81ac850c-1772-4b11-b025-c0d370230756" /> 


**Imagen 12.** *Señal de respiración mientras lee en voz alta después de filtrarla y corregir la orientación*

*Tomado de: Elaboración propia.*

y su respectivo espectro de frecuencia:

<img width="400" alt="image" src="https://github.com/user-attachments/assets/ad6af40e-e382-493b-9f8e-b08de19f56e6" />

**Imagen 13.** *Espectro de frecuencia de la señal de respiración mientras lee en voz alta después de filtrarla*

*Tomado de: Elaboración propia.*

# Procedimiento

1. Para iniciar, se hizo una revisión de literatura acerca del proceso respiratorio para poder comprender qué señales se necesitaban medir y que significan las variables físicas involucradas en el proceso. 

2. A partir de esta información, se seleccionó el sensor más adecuado para el propósito de esta práctica, el cuál fue un sensor de fuerza resistivo FSR402. Al elegir dicho sensor, se investigó cómo condicionar la señal para poder capturarla a través de un conversor análogo-digital donde se concluyó que el circuito mejor adaptado para esta práctica de laboratorio es un divisor de voltaje. Asimismo, se consideraron diferentes conversores análogos digitales para observar cuales se podían integrar al  montaje con más facilidad, el cual en este caso fue un Dispositivo de adquisición de datos (DAQ).

3. Continuando, al conocer cómo se necesitaba condicionar el sensor, se diseñó un montaje donde el sensor se podía adaptar al cuerpo del sujeto de prueba, se podía conectar al circuito de acondicionamiento y su salida fuera leída por el conversor análogo digital el cual mostraría los resultados en un computador. Se alimentó el circuito con una tensión de 5V.

4. Al construir el circuito, se comprobó que la señal de salida fuera correcta a través de los paneles de prueba dados por el software de NI MAX. Se hizo la prueba en dos estados, cuando el sujeto de prueba estuviera relajado y cuando el sujeto de prueba estuviera hablando. Dado que sus resultados fueron satisfactorios, se continuó con la práctica.

5. Después, se elaboró un código de MATLAB que pudiera capturar la señal respiratoria en 30 segundos, graficarla y guardarla como un archivo “.MAT”. Se utilizó una frecuencia de muestreo de 100 Hz. Nuevamente, se adquirió la señal en dos estados, en reposo y cuando el sujeto estuviera hablando. Al obtener los resultados, se evidenció la necesidad de aplicar un filtro Butterworth con frecuencia de corte de 1.0 Hz.  

6. El filtro se aplicó por medio de un código de MATLAB. Una vez se obtuvo una señal más legible, se calcularon las frecuencias de ambas señales y se realizó una representación en frecuencia para cada caso. Con esto se pudo identificar la frecuencia dominante en ambas situaciones. Debido a las propiedades del sensor piezorresistivo, la señal capturada se encuentra invertida, por lo cuál fue necesario multiplicarla por (-1) para que representara de manera más precisa el proceso respiratorio.

7. Para finalizar, se analizaron y se compararon las respuesta. A partir de esto se creó un repositorio de GitHub para documentar los resultados de la práctica.


# Análisis de los Resultados

En esta práctica se evaluó la influencia del habla o verbalización sobre elpatrón respiratorio. Para ello, se implementó un sensor de fuerza resistivo FSR402 , acondicionado por medio de un circuito de divisor de voltaje, con el fin de registrar las variaciones mecánicas producidas por la expansión y contracción del tórax durante el proceso de respiración. Los resultados obtenidos mediante el microcontrolador NI-DAQ mostraron un comportamiento consistente con la señal respiratoria teórica, evidenciando variaciones periódicas de voltaje asociados a los ciclos de inspiración y espiración. 

Durante la adquisición, fue posible observar como en las señales adquiridas se presenciaron ruidos y pequeñas fluctuaciones de altas frecuencias, atribuibles al ruido eléctrico del sistema de adquisición, movimientos por el sujeto durante el tiempo de captura de datos y pequeñas variaciones mecánicas del montaje. Por esta razón, fue necesario implementar un filtro pasa-bajas Butterworth de cuarto orden con frecuencia de corte de 1 Hz, ya que la mayor parte de la energía de la señal respiratoria se concentra por debajo de esta frecuencia. Como es posible visualizar en las imágenes 10 y 12, el filtrado permitió obtener una señal con una morfología mucho más definida, lo cual facilitó la identificación de cada ciclo respiratorio y la detección confiable de los picos respiratorios. 

Es importante resaltar que, debido al principio piezorresistivo del sensor FSR402 y la configuración del divisor de voltaje, al aumentar la presión ejercida sobre el sensor durante la expansión del tórax produce una disminución del voltaje de salida. En consecuencia, la inspiración se representa como una depresión de la señal, comportamiento opuesto al que convencionalmente se utiliza para representar una onda respiratoria. Para facilitar su interpretación y hacerla consistente con la representación habitual, la señal fue invertida matemáticamente mediante la multiplicación por (-1).

En la primera condición de reposo, el resultado fue una señal con un comportamiento relativamente uniforme, con una amplitud y un periodo casi constantes. Esto se puede evidenciar en la imagen 8. Esto indica que el sujeto mantenía un ritmo respiratorio estable, propio de una condición tranquila. En contraste, cuando el sujeto realizó la lectura en voz alta, la señal presentó una mayor irregularidad en su amplitud. En la imagen 9 es posible visualizar los picos causados por la inhalación como una pendiente casi recta, junto con unos picos irregulares causados por las vibraciones al hablar. Con estos picos es posible identificar los ciclos respiratorios. Este comportamiento es esperado, ya que durante el habla se mantiene la respiración mientras se articula y se hacen pequeñas pausas abruptas para tomar aire, además de sincronizar la respiración con la producción del lenguaje.

El análisis en el dominio de la frecuencia respaldo estos resultados. En ambos casos se identificó una frecuencia dominante correspondiente a la frecuencia respiratoria del sujeto; sin embargo, dicha frecuencia presentó diferencias entre las dos condiciones evaluadas, reflejando la modificación del patrón ventilatorio al hablar. La Transformada Rápida de Fourier permitió identificar de manera objetiva la componente de mayor energía, verificando los valores obtenidos mediante la detección de picos en el dominio del tiempo.
En términos generales, los resultados demuestran que el sistema de medición diseñado fue capaz de registrar adecuadamente la actividad respiratoria utilizando un sensor de bajo costo y un circuito de acondicionamiento sencillo. Aunque existen fuentes de ruido e interferencias inherentes al movimiento del sujeto y a la naturaleza del sensor, el procesamiento digital permitió mejorar significativamente la calidad de la señal, facilitando el cálculo de la frecuencia respiratoria y el análisis del patrón respiratorio en diferentes condiciones experimentales.

# Conclusión

- El uso del sensor piezorresistivo FSR402 permitió transformar las variaciones mecánicas producidas por la expansión y contracción del tórax en cambios de voltaje medibles mediante un divisor de tensión y una tarjeta DAQ. Esto demuestra que es posible desarrollar un sistema sencillo, económico y no invasivo para registrar el patrón respiratorio, con potencial de aplicación en dispositivos de monitoreo de pacientes.
- La implementación del filtro pasa-bajas Butterworth con frecuencia de corte de 1 Hz mejoró la calidad de la señal al disminuir el ruido eléctrico, las vibraciones y las alteraciones producidas por movimientos involuntarios, conservando los componentes relacionados con la inspiración y la espiración. En el contexto biomédico, este acondicionamiento es fundamental para detectar correctamente los ciclos respiratorios y reducir errores en el cálculo de las respiraciones por minuto.
- El análisis temporal mediante la detección de picos y el análisis frecuencial mediante la transformada rápida de Fourier permitieron estimar la frecuencia respiratoria y observar cambios en el patrón respiratorio entre la respiración tranquila y la lectura en voz alta. Esta capacidad podría aplicarse en sistemas de vigilancia respiratoria para identificar variaciones asociadas con actividad física, habla, estrés o posibles alteraciones pulmonares; sin embargo, para utilizarlo clínicamente sería necesario realizar calibraciones, pruebas con más participantes y una validación frente a equipos médicos de referencia.


## PREGUNTAS A DISCUSIÓN

• **Pregunta 1: ¿Son los patrones respiratorios y frecuencias respiratorias
iguales o diferentes en cada caso? ¿A qué se debe esto?**

Respuesta: Los patrones respiratorios y las frecuencias respiratorias obtenidos no son iguales en las dos condiciones evaluadas, en la respiración tranquila se observa una señal más periódica, con ciclos regulares y una frecuencia dominante cercana a 0,167 Hz, equivalente aproximadamente a 10 respiraciones por minuto (RPM). En cambio, durante la lectura en voz alta la señal presenta un patrón más irregular, con variaciones en la amplitud y en la duración de los ciclos respiratorios, además de una frecuencia respiratoria mayor cercana a 12 RPM, como se evidencia en la señal filtrada.
Estas diferencias se deben a que hablar modifica el patrón normal de la respiración, ya que la inspiración y la espiración deben coordinarse con la producción de la voz; durante la lectura, las espiraciones suelen prolongarse para permitir la emisión continua del habla y las inspiraciones ocurren de forma más rápida y variable, generando cambios tanto en la forma de la señal como en la frecuencia respiratoria. Además, el esfuerzo asociado al habla incrementa ligeramente la demanda ventilatoria, lo que explica las diferencias observadas entre ambas mediciones.


• **Pregunta 2: ¿Cuáles serían las ventajas y desventajas de emplear múltiples
sensores para el monitoreo del proceso respiratorio? ¿Cuáles podrían ser
las razones?**

Respuesta: El uso de múltiples sensores para el monitoreo del proceso respiratorio ofrece como principal ventaja una mayor precisión y confiabilidad, ya que cada sensor puede medir una variable diferente, como el movimiento torácico, el flujo de aire, la presión o la saturación de oxígeno; la combinación de estas mediciones proporciona información complementaria, facilita la detección de alteraciones respiratorias y reduce la posibilidad de errores causados por el ruido o la falla de un sensor. Sin embargo, el empleo de varios sensores también presenta desventajas, como el aumento del costo, una mayor complejidad en el procesamiento y sincronización de las señales, y una menor comodidad para el paciente debido a la cantidad de dispositivos utilizados.
Estas ventajas y desventajas se deben a que ningún sensor es capaz de medir por sí solo todos los aspectos del proceso respiratorio. Por esta razón, combinar varios sensores permite obtener una evaluación más completa del estado respiratorio, aunque esto implica un sistema más complejo y con mayores requerimientos técnicos.

## Referencias
[1] Nicolai, T. (2006). The physiological basis of respiratory support. Paediatric Respiratory Reviews, 7(2), 97–102. https://doi.org/10.1016/j.prrv.2006.03.002.

[2] Kreit, J. W., & Eschenbacher, W. L. (1988). The Physiology of Spontaneous and Mechanical Ventilation. Clinics in Chest Medicine, 9(1), 11–21.

[3] “Intercambio gaseoso: qué es y definición médica | Diccionario CUN,” https://www.cun.es. https://www.cun.es/diccionario-medico/terminos/intercambio-gaseoso.

[4] Pleil, J. D., Wallace, M. A. G., & Davis, M. D. (2021). The physics of human breathing: flow, timing, volume, and pressure parameters for normal, on-demand, and ventilator respiration. Journal of Breath Research, 15(4).

[5] Adler, D., & Janssens, J. P. (2019). The Pathophysiology of Respiratory Failure: Control of Breathing, Respiratory Load, and Muscle Capacity. Respiration, 97(2), 93–104. https://doi.org/10.1159/000494063.

[6] Interlink Electronics, FSR 400 Series Integration Guide. Camarillo, CA, USA: Interlink Electronics. [Online]. Available: https://www.interlinkelectronics.com/downloads/integration-guides/fsr-400-series-integration-guide.pdf.

[7] Equimed, “La frecuencia respiratoria: qué es, cómo controlarla y equipos para monitorearla,” 29 de julio de 2022. [En línea]. Disponible en: https://equimed.es/la-frecuencia-respiratoria-que-es-como-controlarla-y-equipos-para-monitorearla/
