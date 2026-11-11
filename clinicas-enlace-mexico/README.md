# Clínicas Enlace México

Sistema web para una red de clínicas: registro único de pacientes en toda la red, agenda de citas por sede sin traslapes y seguimiento de la llegada y atención de cada paciente.

Proyecto de la materia **Ingeniería de Software** · Universidad Tecnológica de la Mixteca · Grupo **502-A · Equipo IV**
Docente: Mario Alberto Moreno Rocha

## Problema y objetivo

Cada clínica de la red lleva sus registros por separado: un paciente atendido en otra sede recibe un registro nuevo y las citas pueden encimarse. El objetivo del **Incremento 1** es tener un solo registro de paciente para toda la red, agendas por sede sin traslapes y el seguimiento de la llegada y la atención.

| Incluido en el Incremento 1 | Pospuesto |
| --- | --- |
| Acceso por rol y clínica | Laboratorio (Incremento 2) |
| Registro de pacientes con aviso de duplicados | Cargos, pagos y saldos (Incremento 3) |
| Agenda de citas con historial de cambios | Cuentas para pacientes |
| Llegada y estados de atención | |
| Reportes por clínica y de la red | |

## Equipo

| Integrante | Rol | Responsabilidad principal |
| --- | --- | --- |
| Xochitl Nerina López López | Líder de equipo · Scrum Master | Enlace con la cliente, minuta y seguimiento del sprint |
| Ivri Nitzani Arenas Rojas | Desarrolladora | Backend, modelo de datos y reglas de negocio |
| Itzel Amairani Hernández Torija | Administradora | Plan, riesgos, pruebas y métricas de calidad |
| Israel Bautista Jiménez | Diseñador UI | Interfaces, prototipos y diseño visual |

Cliente: Laura Méndez, coordinadora nacional de la red (personaje representado por el docente).

## Metodología

Scrum con sprints de dos semanas y una demostración a la cliente al final de cada sprint. Detalle en [`plan/sprints.md`](plan/sprints.md) y [`plan/metricas.md`](plan/metricas.md).

| Sprint | Fechas | Objetivo |
| --- | --- | --- |
| Sprint 0 · Preparación | 03/11 al 09/11/2026 | Entorno, modelo de datos, prototipos y decisiones técnicas |
| Sprint 1 · Base | 10/11 al 23/11/2026 | Inicio de sesión, usuarios, roles y permisos por clínica |
| Sprint 2 · Pacientes | 24/11 al 07/12/2026 | Registro, búsqueda en red y aviso de duplicados |
| Sprint 3 · Agenda | 08/12 al 21/12/2026 | Disponibilidad; crear, reprogramar y cancelar citas |
| Sprint 4 · Recepción y reportes | 22/12/2026 al 04/01/2027 | Llegada, atención, agenda del médico y reportes |

## Estructura del repositorio

```
├── docs/
│   ├── 502_A_4_segundo_parcial.pdf   Segundo parcial completo
│   ├── srs/                          SRS por versión
│   ├── minuta/                       Minuta de alcance aceptada por la cliente
│   ├── evidencia-slack/              Capturas de la entrevista y la aceptación (FUE-001 a FUE-012)
│   ├── diagramas/                    Contexto, procesos y permisos, estados, calendario
│   └── prototipos/                   Pantallas del prototipo de citas
├── plan/                             Backlog, sprints, riesgos y métricas
├── src/                              Código fuente (desde el Sprint 1)
└── tests/                            Pruebas CP-001 en adelante
```

## Documentos principales

- [Segundo parcial: Descubrir y acordar](docs/502_A_4_segundo_parcial.pdf)
- [SRS v0.1](docs/srs/SRS_v0.1.pdf)
- [Minuta de alcance aceptada](docs/minuta/minuta_alcance_v1.pdf) · [evidencia de aceptación](docs/evidencia-slack/08_FUE-012_aceptacion_minuta.png)
- [Prototipos](docs/prototipos/) y [diagramas](docs/diagramas/)

## Cómo trabajamos

Las reglas para ramas, commits y pull requests están en [`CONTRIBUTING.md`](CONTRIBUTING.md). Cada historia de usuario es un *issue* y el avance se sigue en el tablero del proyecto.

> Todos los datos de pacientes y profesionales del repositorio son ficticios.
