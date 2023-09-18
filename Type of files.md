# Type of files

```bash
# Son entidades o clases que representan los datos de una aplicacion.

📁 models/
↪️ *.model.ts
↪️ *.type.ts

# Actúan como un puente entre el servidor web y la aplicación

📁 middlewares/
↪️ *.middleware.

# Servicios externos

📁 services/
↪️ *.service.

# Es una función que se ejecuta antes o después de una solicitud HTTP.

📁 interceptors/
↪️ .interceptor.ts

# Tiene como propósito conectar dos sistemas incompatibles.
# 💡 ejp. Recibe las solicitudes del usuario, adapta los datos y envia una respuesta adecuada.

📁 adapters/
↪️ *.adapter.ts

# Tiene como propósito gestionar el flujo de datos y la interacción entre los componentes de una aplicación.
# 📝 Pueden ser: Controladores de estado, de eventos, de componentes, etc

📁 controllers/
↪️ *.controller.ts

# Se encargan de proporcionar datos o servicios a la aplicación. Son una forma de centralizar la lógica y la dependencia de los datos.

📁 providers/
↪️ *.provider.ts

# REACT. Son los datos que pueden tener una página web.

📁 contexts/
↪️ .context.tsx

# Son mecanismos que permiten almacenar datos en el dispositivo del usuario.

📁 storage/
↪️ *.localstorage.ts
↪️ use*.store.ts # zustand
↪️ *.store.ts

# Permiten que el código se pueda volver a usar como se quiera en otras webs o aplicaciones.

📁 components/
↪️ *.component.tsx
↪️ *.styled-component.tsx

# Son funciones que permiten a los desarrolladores de React acceder a las funcionalidades del estado y los efectos secundarios sin tener que escribir clases.

📁 hooks/
↪️ *.hook.ts

# Se utilizan para realizar tareas generales dentro de un proyecto..

📁 utils/
↪️ *.util.ts

# Se utilizan para realizar tareas especificas dentro de un proyecto.

📁 helpers/
↪️ *.helper.ts

# Son herramientas o métodos que se utilizan para verificar la validez de los datos introducidos por el usuario.

📁 validators/
↪️ <Name>IsValid.ts
↪️ ensure<Name>Valid.ts

# Controlan la apariencia de los elementos de una página web.

📁 styles/
↪️ *.css
↪️ *.scss
↪️ *.module.scss

# Contienen los datos necesarios para representar un tipo de fuente.

📁 fonts/
↪️ *.font.ts
```
