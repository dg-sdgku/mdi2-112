# MDI2-112 - Mobile Development II

Repositorio oficial de código fuente para el curso **Mobile Development II (MDI2-112)**.

El curso está organizado en 4 clases introductorias sobre desarrollo para Android Wearables.

## Estrategia de ramas

Este repositorio usa una estrategia simple pensada para clase:

- `main` contiene la versión estable más reciente y completa de la app.
- `class-*` contiene el código usado durante cada clase.
- `prep/*` contiene trabajo de preparación, pruebas y experimentación del instructor.

No se debe desarrollar directamente sobre `main`. El trabajo debe prepararse en ramas `prep/*` o construirse durante clase en ramas `class-*`.

## Ramas de clase

- `class-01-wear-compose-basics`
- `class-02-state-and-interaction`
- `class-03-lists-and-navigation`
- `class-04-final-app`

Estas ramas representan el estado del código usado durante cada sesión. Los alumnos pueden revisarlas como referencia para seguir el avance del curso.

## Ramas de preparación

- `prep/class-01`
- `prep/class-02`
- `prep/class-03`
- `prep/class-04`

Estas ramas son para preparación del instructor, exploración de ideas, pruebas antes de clase y ajustes que todavía no forman parte del material estable.

## Flujo recomendado

1. Preparar o experimentar en la rama `prep/class-XX`.
2. Llevar el contenido listo a la rama `class-XX-*` correspondiente.
3. Usar la rama `class-XX-*` durante la clase.
4. Al terminar la clase, mergear la rama `class-XX-*` en `main`.

De esta forma, `main` siempre queda como la versión estable más reciente del proyecto, mientras que las ramas de clase conservan referencias claras para los alumnos.
