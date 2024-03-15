# Integracion Continua
Integracion continua paso a paso en github actions
## Crear runners en github actions

1. **Accede a tu repositorio en GitHub:**
   - Entra al repositorio al que quieres añadir runners

3. **Accede a la configuración de Actions:**
   - En la configuracion del repositorio busca actions

4. **Accede a la sección de "Runners":**
   -  Busca runners. Aqui puedes crear y editar los runners en repositorio

5. **Añade un nuevo runner:**
   - Pulsa en Add runner. Haz clic en el para agregar un nuevo runner a tu repositorio

6. **Descarga e instala el runner:**
   - Sigue las instrucciones proporcionadas para descargar e instalar el runner en tu maquina local

7. **Configura el runner:**
   - Durante el proceso de instalación, se te pedirá que proporciones un token de acceso. Este token se utilizará para autenticar el runner con GitHub. Sigue las instrucciones para proporcionar este token durante la configuración del runner.

8. **Inicia el runner:**
   - Una vez configurado el runner, puedes iniciarlo en tu maquina local para ejecutar trabajos de GitHub Actions

---

## Uso de Pipelines en GitHub Actions

Los pipelines son una buena forma de automatizar flujos de trabajo

1. **Crea un archivo de configuracion:**
   - En la raíz de tu repositorio, crea un archivo llamado `nombre-del-flujo.yml`. Este archivo contendra los pasos que quieres que se ejecuten automaticamente.

2. **Define tus jobs:**
   - En el archivo de configuracion, define los diferentes trabajos (jobs) que quieres que se realicen. Puedes especificar que acciones o comandos quieres que se ejecuten en cada job.

3. **Configura los triggers:**
   - Puedes configurar los desencadenadores (triggers) que activarán tus pipelines. Esto podría ser un push a una rama especifica, un pull request abierto, o incluso un cron job que se ejecute en un horario determinado.

4. **Ejecuta y monitorea tus pipelines:**
   - Una vez que hayas definido tus pipelines, podrás verlos en la pestaña "Actions" de tu repositorio. Desde allí, podrás ejecutar manualmente tus pipelines y ver el estado de cada paso en tiempo real.


## Beneficios de la integracion continua

- **Detección temprana de errores:** Permite identificar errores de manera inmediata

- **Entregas más frecuentes:** Al integrar y probar el código de forma regular, es mas facil sacar nuevas versiones

- **Mejora de la calidad del software:** Al ejecutar pruebas automáticas mejora la calidad 

- **Reducción de riesgos:** Se minimiza el riesgo de introducir errores en el código base

- **Mayor colaboración:** Fomenta la colaboración y la comunicacion

- **Feedback rápido:** Se recibe rapidamente retroalimentacion sobre cada cambio