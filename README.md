## <p align="justify"> Objtetivo del Challenge

#### <p align="justify"> Analizar el churn de clientes de la empresa de telecomunicaciones con la base de datos de clientes que tiene los siguientes datos categoricos y numericos:

    customerID: número de identificación único de cada cliente
    Churn: si el cliente dejó o no la empresa
    gender: género (masculino y femenino)
    SeniorCitizen: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
    Partner: si el cliente tiene o no una pareja
    Dependents: si el cliente tiene o no dependientes
    tenure: meses de contrato del cliente
    PhoneService: suscripción al servicio telefónico
    MultipleLines: suscripción a más de una línea telefónica
    InternetService: suscripción a un proveedor de internet
    OnlineSecurity: suscripción adicional de seguridad en línea
    OnlineBackup: suscripción adicional de respaldo en línea
    DeviceProtection: suscripción adicional de protección del dispositivo
    TechSupport: suscripción adicional de soporte técnico, menor tiempo de espera
    StreamingTV: suscripción de televisión por cable
    StreamingMovies: suscripción de streaming de películas
    Contract: tipo de contrato
    PaperlessBilling: si el cliente prefiere recibir la factura en línea
    PaymentMethod: forma de pago
    Charges.Monthly: total de todos los servicios del cliente por mes
    Charges.Total: total gastado por el cliente

#### <p align="justify"> Se realizan transformaciones de tipos, manejo de NaNs y duplicados, aplanamiento, normalización, estandarización y uso de one_hot_encoder para datos multicategoricos.
#### <p align="justify"> El proyecto se desarrollo usando numpy, pandas, matplotlib, seaborn y scipy para manipulacion de dataframes y graficación.
#### <p align="justify"> En el archivo se encuentra un informe final con los graficos de correlación y distribución (Matriz de correlaciones, Heatmap de Crammer's V).
