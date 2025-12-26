# Baseline Access Control

Este documento define configuraciones mínimas de control de accesos, enfocadas en usuarios, grupos y permisos para sistemas Linux y entornos corporativos.

## Usuarios y grupos

- Crear cuentas individuales para cada usuario
- Evitar compartir cuentas administrativas
- Revisar periódicamente usuarios activos
- Eliminar cuentas inactivas o innecesarias

## Principio de menor privilegio

- Asignar permisos estrictamente necesarios
- Limitar uso de sudo a quienes lo requieren
- Documentar privilegios y cambios

## Modelos de control de acceso

- RBAC: Roles definidos con permisos específicos
- DAC: Acceso basado en propiedad de archivos
- MAC: Políticas de seguridad obligatorias si aplica

## Auditoría

- Registrar cambios de permisos
- Revisar logs de acceso
- Realizar revisiones periódicas
