# CheckDG: versiones

Este repositorio solo contiene las **versiones instalables (APK)** de **CheckDG**, una app Android de registro y seguimiento personal de glucosa, cetonas, insulina, alimentación, actividad física, peso y presión arterial. El código fuente no está aquí.

La app consulta las *Releases* de este repositorio para avisarte cuando hay una versión nueva (Más → Acerca de → Buscar actualización).

## Instalar
1. Descarga el `.apk` de la última versión en [Releases](../../releases).
2. Ábrelo en tu teléfono Android y permite instalar desde esa fuente si Android lo pide.

## Verificar la descarga
Cada versión publica su huella **SHA-256** en las notas. La app la comprueba sola antes de instalar una actualización. Para comprobarla a mano en Windows: `Get-FileHash CheckDG-x.y.z.apk -Algorithm SHA256`.

## Importante
CheckDG es una herramienta de registro personal. **No es un dispositivo de diagnóstico ni reemplaza a tu profesional de salud**, y no recomienda cambios de dosis ni de tratamiento.
