## Cambiar de usuario de GitHub en tu PC

Este README te ayudará a cambiar el usuario de GitHub configurado en tu PC.

**Pasos:**

1. **Abre la terminal:** Busca la terminal en tu PC (por ejemplo, "cmd" en Windows o "Terminal" en macOS).

2. **Configura el nombre de usuario:** Ejecuta el siguiente comando, reemplazando "usuario" con tu nuevo nombre de usuario:

   ```bash
   git config --global user.name "usuario"
   ```

3. **Configura el correo electrónico:** Ejecuta el siguiente comando, reemplazando "tucorreo@gmail.com" con tu correo electrónico de GitHub:

   ```bash
   git config --global user.email "tucorreo@gmail.com"
   ```

**Verificar el usuario actual:**

Para verificar qué usuario tienes configurado actualmente, ejecuta los siguientes comandos:

```bash
git config --global user.name
git config --global user.email
```

**Borrar el usuario actual:**

Si deseas borrar el usuario actual, ejecuta los siguientes comandos:

```bash
git config --global --unset user.name
git config --global --unset user.email
```

**¡Listo!** Ahora puedes colaborar en proyectos de GitHub utilizando tu nuevo nombre de usuario. 

**Recuerda:** Estos comandos solo modifican la configuración de tu PC. Para cambiar el usuario en GitHub.com, debes iniciar sesión con tu nueva cuenta. 

¡Espero que esta información te sea útil! Si tienes más preguntas, no dudes en preguntar.