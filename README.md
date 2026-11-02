# Cove Vault

> **Tu IA privada: lo que pasa en tu navegador, se queda en tu navegador.**

Cove Vault es una aplicación de privacidad **local-first** para autónomos y particulares: una bóveda digital donde tus operaciones, facturas y datos fiscales se leen, calculan y almacenan **exclusivamente en tu dispositivo**.

<img width="1383" height="896" alt="01-portada-inicio" src="https://github.com/user-attachments/assets/1ed3ea3c-eed3-4575-a13c-7f7cceef4f45" />

---

## 🔐 El principio: soberanía de datos

| Promesa | Cómo la cumplimos |
|---|---|
| ✅ **Sin nube para tus datos** | Todo se procesa y guarda en la base de datos local de tu navegador, cifrada con **AES-GCM 256-bit**. Desconecta el WiFi y sigue funcionando. |
| ✅ **Sin telemetría ni rastreadores** | No hay analítica, ni cookies de seguimiento, ni píxeles de terceros. |
| ✅ **Sin cuentas externas para el núcleo** | El acceso se realiza con una **licencia portable firmada (`aether_license.p12`) + PIN**. Ni usuarios en bases de datos ajenas ni contraseñas en la nube. |
| ✅ **RGPD desde el diseño** | Exportación limpia (JSON/CSV) y borrado definitivo local: tus derechos de acceso y eliminación se ejercen con dos clics, no con correos de soporte. |

---

## 🎛️ Qué hace Cove Vault

### Operaciones — cobros y pagos con beneficios netos al instante

Registra gastos e ingresos con cliente o proveedor, divisa, tipo de IVA, categoría y fecha de vencimiento. El panel calcula tus **beneficios netos al instante** y muestra la evolución mensual con filtros por categoría y cliente. Importa tu histórico desde un CSV.

La higiene de datos también está pensada: **rectificativas y abonos** en su propio cajón, y una **papelera** que expira sola a los 30 días sin contar para los totales ni para el límite gratuito.

Tus operaciones se apoyan en **fichas de proveedores** validadas (NIF/CIF con dígito de control real) para que cada gasto quede identificado desde el minuto uno. Del mismo modo, los ingresos se identifican con **fichas de clientes** (CIF válido, email y dirección fiscal).

<img width="1383" height="2608" alt="19-operaciones-datos-reales" src="https://github.com/user-attachments/assets/e873fb44-ade6-4df4-9cfb-f90d3e2989ac" />
<img width="1390" height="896" alt="23-ficha-proveedor" src="https://github.com/user-attachments/assets/7317122d-732b-4735-8277-e5c8ab8f13c3" />
<img width="1390" height="896" alt="24-ficha-cliente" src="https://github.com/user-attachments/assets/fb652757-6488-4768-85da-4946c84a93e4" />

### Facturación — facturas desde tus operaciones, no a mano

La factura no es un formulario vacío: eliges las **operaciones ya registradas** (pendientes de facturar), la app calcula totales e impuestos y **genera el PDF completo de la factura**, con datos de cliente rellenados solo (NIF, dirección), nº de factura **automático o propio**, formas de pago del catálogo UN/ECE y referencias opcionales de contrato, pedido y albarán.

Las **facturas emitidas no se pueden borrar** (nadie puede manipular su historial): para corregir, la app emite una **rectificativa** con la normativa. Acceso protegido con PIN: si no estás en sesión, la bóveda no se abre.

La facturación funciona sobre tus fichas: eliges las operaciones del cliente y el panel de impuestos trimestrales recalcula en vivo IVA repercutido y soportado, retenciones y resultado a ingresar, con tus datos reales. Cuando marcas una operación pendiente, un resumen aplica IVA e IRPF y te muestra el total de la factura, antes de descargar su PDF.

<img width="1383" height="896" alt="04-facturacion-bloqueada" src="https://github.com/user-attachments/assets/155331ca-0202-4d7d-97dd-c10351c2f80d" />
<img width="1383" height="2849" alt="20-facturacion-datos-reales" src="https://github.com/user-attachments/assets/116c4239-60c6-4924-bd5d-e02f00186291" />

### Recursos — modelo oficial 303 y 130 en tiempo real

Simulador de los **modelos oficiales** de la agencia fiscal: 303 (IVA) y 130 (IRPF de pagos fraccionados), con **declaraciones trimestrales calculadas en tiempo real** a partir de tus operaciones: IVA devengado y soportado, deducciones y resultado de liquidación. Descarga lista para presentar: el **PDF del modelo oficial** y el **fichero para la agencia formato `.200`** de la Sede Electrónica. Con el aviso justo donde toca: es una estimación según su normativa (RD 1624/1992), **verifica con tu gestor antes de presentar**.

<img width="1383" height="896" alt="03-recursos-bloqueados" src="https://github.com/user-attachments/assets/4edce8a1-625c-4c24-bc17-be715d1226f4" />
<img width="1383" height="1755" alt="21-modelo303-datos-reales" src="https://github.com/user-attachments/assets/f8aea17f-23f3-48d0-ad3e-f77006f7288b" />

### Simulador Fiscal — decisiones antes de que cuesten dinero

Conecta escenarios "what-if" con **tus datos reales** del trimestre para ver el efecto antes de decidir. Incluye 5 escenarios predeterminados (+10% de ingresos, −15% de gastos, límite legal de deducción de vehículos según el Art. 16 del IRPF…), **escenarios personalizados** con nombre, color y descripción, **mutaciones** (multiplicar, añadir, quitar o reclasificar operaciones, mover facturas entre periodos), filtros por categoría, tipo, IVA, IRPF o cliente, y análisis en **mapa de calor, sensibilidad, comparador y optimizador**, todo exportable.

<img width="1383" height="3210" alt="22-simulador-datos-reales" src="https://github.com/user-attachments/assets/3e42f40a-c422-40ae-872c-8313b54af231" />

### Acceso — licencia portable firmada

Sin contraseñas en la nube: una licencia con firma criptográfica RSA guardada en tu equipo (o USB) y un PIN que solo tú conoces. ¿Olvidaste el PIN? Un código de recuperación te devuelve el acceso — nadie más puede suplantarte.

<img width="1390" height="896" alt="05-acceso-licencia" src="https://github.com/user-attachments/assets/0020362b-8281-42f1-acd9-21a7c23984a5" />
<img width="1390" height="896" alt="25-inicio-sesion" src="https://github.com/user-attachments/assets/a906c027-4972-4f43-9468-8a758ddd7c32" />

---

## 💳 Planes y precios

| Plan | Precio | Qué incluye |
|---|---|---|
| **Gratuito** | 0 € | Registro de operaciones (gastos e ingresos) con tope de 10 |
| **Prueba gratuita** | 0 € · 7 días | Todo desbloqueado durante 7 días (facturación, exportaciones, simulador, copia de seguridad), con tope de 10 operaciones. **Sin tarjeta**: solo tu email, una prueba por persona. Se te avisa en el día 5. |
| **Mensual** | 45,00 €/mes · sin permanencia | Todas las funciones premium (540,00 €/año si lo pagas mes a mes) |
| **Mensual con permanencia** | 19,00 €/mes los 3 primeros meses · 45,00 €/mes después (12 meses de compromiso mínimo) | Todas las funciones premium, con precio fijo garantizado el primer año: aunque subamos precio, tú no subes |
| **Add-on: Simulador Fiscal** | +9,90 €/mes | Escenarios _what-if_, mapa de calor, análisis de sensibilidad y optimizador para los modelos 130 y 303, como suscripción mensual independiente del plan |

*Todos los precios con IVA incluido. El pago se realiza con **PayPal o Stripe** (conexión cifrada SSL). La licencia queda ligada a tu email y almacenada **cifrada y en local**. ¿Un amigo te invitó? Con su código de invitación ambos ganáis 1 mes extra de licencia. Y el plan mensual puedes cancelarlo cuando quieras desde tu menú (encima de Cerrar sesión), sin perder lo pagado.*

| | |
|---|---|
| <img width="1390" height="896" alt="26-elegir-plan" src="https://github.com/user-attachments/assets/9d221b06-5c93-409b-9cd5-17b5a5f60ed7" />|<img width="1390" height="896" alt="27-addon-simulador" src="https://github.com/user-attachments/assets/91938380-f295-4e32-bdcc-9cd66a1acef7" />|

<img width="1390" height="896" alt="28-metodo-pago-datos" src="https://github.com/user-attachments/assets/bf065e1d-b10c-46c4-8b8f-ba54e3d21949" />

<img width="1390" height="896" alt="29-pago-confirmado" src="https://github.com/user-attachments/assets/a8e6f141-8bd8-4211-baa9-703c0fa31a11" />


## 🔑 Tu PIN maestro y tu llave

<p align="center">
  <img src="./30-configurar-pin.jpeg" width="440" alt="Configurar Acceso Portable: PIN maestro con licencia vinculada y descarga de llave USB">
</p>

El alta termina creando tu **PIN maestro** (mínimo 10 caracteres, con medidor de robustez en pantalla) y descargando **dos archivos**: tu **llave para USB** (`aether_license.p12`, el sistema de acceso portable con el que inicias sesión en cualquier equipo) y una **copia de seguridad cifrada** (`.aethbak`) para restaurar si algo saliera mal.

Por seguridad, la app se autoprotege: si dejas la sesión sin actividad, se cierra sola y vuelve a pedir tu PIN; y solo una pestaña a la vez puede tener la bóveda abierta, para evitar borrados accidentales. Y si tu navegador bloqueó alguna descarga del alta, un botón la re-descarga con un clic.

### Iniciar sesión en otro equipo

Con tu archivo de licencia y tu email + PIN (o tu código de recuperación si olvidas el PIN), abres tu bóveda en cualquier equipo. La misma llave sirve en todos tus dispositivos: cópiala de uno a otro y entra con tu PIN; no hace falta generar llaves nuevas. Tus datos quedan cifrados solo en ese equipo y pueden borrarse al cerrar, con tu copia de seguridad `.aethbak` disponible en Descargas para restaurar.

---

## 🧱 Bajo el capó (versión resumida)

- **React 19 + TypeScript estricto + TailwindCSS 4**, construido con Vite 6.
- **Base de datos local IndexedDB (Dexie)** con cifrado AES-GCM 256-bit vía Web Crypto API.
- **Política de Seguridad de Contenidos (CSP)** estricta sin `unsafe-inline`, con protección contra XSS, clickjacking y abusos.
- **Verificación de licencias** mediante firmas RSA (servicios de verificación en el servidor que **nunca ven tus datos**).
- **Copia de seguridad y recuperación**: kit de recuperación, copia portátil cifrada en USB, fusión segura al restaurar y cuarentena ante datos de origen sospechosos — nunca se pierde información.
- **Calidad verificada en cada envío**: tipos en modo estricto, >440 pruebas unitarias, control de código duplicado (<2%), auditoría de dependencias y detección de código muerto.

> **Aviso de código:** el repositorio principal es privado por diseño: **el código no se distribuye**. Este escaparate documenta el producto y sus garantías; para una demostración en privado, usa los canales de contacto de abajo.

---

## 📬 Contacto

- GitHub: [covevaultadmin-sudo](https://github.com/covevaultadmin-sudo)
- Cualquier duda sobre privacidad, licencias o demostración en privado: abre una discusión en este repositorio o escríbeme directamente.

---

*© 2026 Cove Vault. Sovereignty by design.*
