# ffe_practicas
Odoo 17 — Módulo “ffe_practicas” para gestionar FCT/FFE del IES Enrique Tierno Galván: ciclos FB/SMR/ASIR/DAM/DAW, tutorías por año/curso/turno, elegibilidad por empresa, asignaciones, partes de horas, interacciones, import CSV y reportes.

# ffe_practicas (Odoo 17)

Módulo para gestionar FCT/FFE del IES Enrique Tierno Galván (FB, SMR, ASIR, DAM, DAW):
- Tutorías por Año Académico + Ciclo + Curso (1º/2º) + Turno (M/T)
- Empresas, elegibilidad anual por combo, contactos por ciclo/curso/turno
- Asignaciones (bloqueo por no elegibilidad), partes de horas, interacciones
- Importación CSV y reportes PDF (y opcional XLSX en rama `xlsx`)

## Requisitos
- Odoo 17
- Dependencias: `base`, `mail`, `contacts`, `web`
- (Opcional XLSX) `report_xlsx` — ver rama `xlsx`

## Instalación
1. Copiar `ffe_practicas/` en tu `extra_addons`.
2. Asegurar `addons_path` en `odoo.conf`.
3. Apps → Update Apps List → “FFE Prácticas (FCT/FFE)” → Install.

## Uso rápido
- Configura Año Académico, Tutorías y Empresas.
- Define `Elegibilidad` por año/ciclo/curso/turno.
- Crea `Asignaciones` (se bloquean si no hay elegibilidad).
- Registra `Horas` e `Interacciones`.

## Licencia
AGPL-3.0

