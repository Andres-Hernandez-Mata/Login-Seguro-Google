# Login-Seguro-Google
Web App with Google Login

# Google Login
Es posible que desees que los usuarios individuales tengan perfiles. O tal vez desees proporcionar funciones solo a ciertos usuarios. En cualquier caso, necesitarás saber quién está interactuando con tu aplicación. En otras palabras, deberás autenticar a los usuarios e identificarlos de alguna manera única.

La solución tradicional es utilizar un nombre de usuario único y una contraseña secreta. Tu aplicación almacenaría esa información y la solicitaría cuando fuera necesario. Sin embargo, hay algunas desventajas en esa solución:

- Tienes que gestionar de forma segura las contraseñas.
- Tienes que implementar cualquier funcionalidad relacionada con la cuenta:
    - Autenticación de dos factores
    - Restablecimiento de contraseña
- Debes proteger contra intentos de inicio de sesión maliciosos.
- Tus usuarios tienen que recordar otro nombre de usuario y contraseña.

Al utilizar el inicio de sesión de Google para tus usuarios, les dejas toda esa responsabilidad a ellos. Tu aplicación espera a que el usuario pase por la autenticación. Luego, Google le informa a tu aplicación sobre ese usuario. En ese momento, puede iniciar sesión de manera efectiva en tu aplicación.

De esta manera no tienes que almacenar ninguna contraseña y Google se encarga de toda la seguridad.