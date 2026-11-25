<div style="text-align: center;">
  <img src="https://www.uvlhub.io/static/img/logos/logo-light.svg" alt="Logo">
</div>

# uvlhub.io

Repository of feature models in UVL format integrated with Zenodo and flamapy following Open Science principles - Developed by DiversoLab

## Official documentation

You can consult the official documentation of the project at [docs.uvlhub.io](https://docs.uvlhub.io/)

## Primera modificación.

## Conventional commits

### Formato

```text
<tipo>(<alcance opcional>): <descripción>
```

### Tipos permitidos

- `feat`: nueva funcionalidad
- `fix`: corrección de un error
- `docs`: cambios en la documentación
- `style`: formato de código sin cambios de lógica
- `refactor`: refactorización sin cambiar el comportamiento
- `perf`: mejoras de rendimiento
- `test`: añadir o modificar pruebas
- `build`: cambios en el sistema de compilación o dependencias
- `ci`: cambios en workflows y configuración de CI/CD
- `chore`: tareas de mantenimiento o herramientas del repositorio
- `revert`: revertir un commit anterior

### Reglas básicas

- La descripción debe empezar en **minúscula** y **no terminar en punto (`.`)**.
- La primera línea no debe superar los **100 caracteres**.
- Para indicar un cambio incompatible (*breaking change*), se añade `!` antes de los dos puntos (por ejemplo, `feat!: ...`).

### Activar la validación local en `git commit`

La comprobación siempre se realiza al hacer un push, pero para que también se realice al hace commit se debe activar ejecutando el siguiente código:

```bash
git config core.hooksPath .githooks
```

