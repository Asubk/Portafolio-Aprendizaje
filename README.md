# 🚀 Mi Portafolio de Aprendizaje

Bienvenido a mi proceso de formación. Aquí documento mis avances, errores y soluciones de los cursos que tomo.


## 📚 Cursos Actuales
* **[Git y GitHub]**: Documentando mis primeras ramas y repositorios.
* **Próximamente**: Dart

## 🛠 Solución de Problemas (Troubleshooting)

### 🚨 Error: Push rechazado (Historias diferentes)
**Situación:** Intenté subir mis archivos locales a GitHub, pero el repositorio remoto ya tenía un archivo `README.md` que yo no tenía en mi PC. Git bloqueó el proceso para evitar pérdida de datos.

**Solución aplicada:**
Usé el comando de "fuerza":
`git push origin main --force` (o `-f`)

**Aprendizaje:** El comando `--force` sobreescribe el contenido del servidor con lo que tienes en tu computadora. 
> **⚠️ Nota:** Solo usar en proyectos personales o cuando estás seguro de que lo que está en la nube no sirve, ya que borra el historial previo de GitHub.

