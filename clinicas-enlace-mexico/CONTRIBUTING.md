# Cómo trabajamos en este repositorio

## Flujo de trabajo

1. Toma un *issue* del tablero (una historia de usuario o tarea) y asígnatelo.
2. Crea una rama desde `main` con el ID del requisito:
   `feature/rf-002-registro-paciente` · `fix/rn-004-traslape` · `docs/srs-v0.2`
3. Haz commits pequeños que mencionen el requisito:
   `RF-008: valida traslape de citas (RN-004)`
4. Abre un *pull request* hacia `main` usando la plantilla y pide revisión a otra integrante del equipo.
5. Solo se une a `main` cuando cumple la **definición de terminado**.

## Definición de terminado

- El código fue revisado por otra persona del equipo.
- Los criterios de aceptación (CA) de la historia se ejecutaron y aprobaron.
- Las pruebas de permisos de la historia se aprobaron.
- No quedan defectos críticos abiertos.
- La función se mostró con datos ficticios y se actualizó la trazabilidad.

## Reglas

- Nunca subas contraseñas, claves ni datos reales de pacientes.
- No se trabaja directamente en `main`.
- Cada cambio de requisitos pedido por la cliente se registra como solicitud de cambio (CAM) antes de programarse.
