# Final_Project_Interconnect
Proyecto Final para el curso de DataScience de TripleTen

## Introducción
Al operador de telecomunicaciones Interconnect le gustaría poder pronosticar su tasa de cancelación de clientes. Si se descubre que un usuario o usuaria planea irse, se le ofrecerán códigos promocionales y opciones de planes especiales. El equipo de marketing de Interconnect ha recopilado algunos de los datos personales de sus clientes, incluyendo información sobre sus planes y contratos.

## Servicios de Interconnect
Interconnect proporciona principalmente dos tipos de servicios:
1. Comunicación por teléfono fijo. El teléfono se puede conectar a varias líneas de manera simultánea.
2. Internet. La red se puede configurar a través de una línea telefónica (DSL, línea de abonado digital) o a través de un cable de fibra óptica.

Algunos otros servicios que ofrece la empresa incluyen:
- Seguridad en Internet: software antivirus (ProtecciónDeDispositivo) y un bloqueador de sitios web maliciosos (SeguridadEnLínea).
- Una línea de soporte técnico (SoporteTécnico).
- Almacenamiento de archivos en la nube y backup de datos (BackupOnline).
- Streaming de TV (StreamingTV) y directorio de películas (StreamingPelículas).

La clientela puede elegir entre un pago mensual o firmar un contrato de 1 o 2 años. Puede utilizar varios métodos de pago y recibir una factura electrónica después de una transacción.

## Objetivos
Los objetivos principales son:
1. Realizar una Exploración de Datos, analizando los diferentes Datasets.
2. Crear modelos de Machine Learning que permitirán predecir la probabilidad de cancelación de clientes.
3. Evaluar los modelos creados con la métrica principal AUC-ROC.
4. Preparar informe respectivo a los modelos y sus resultados.

## Descripción de datos
Los datos consisten en archivos obtenidos de diferentes fuentes:

- `contract.csv` - información del contracto;
- `personal.csv` - datos personales del cliente;
- `internet.csv` - información sobre los servicios de Internet;
- `phone.csv`    - información sobre los servicios telefónicos.

En cada archivo, la columna `costumerID`(ID de cliente) contiene un código único asignado a cada cliente.
