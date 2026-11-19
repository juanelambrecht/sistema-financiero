# SAMPOS · APP Financiera — Demo comercial

Demo pública, responsive e interactiva inspirada en APP Financiera. La versión real está desarrollada en Laravel y no está incluida en este repositorio.

## Módulos
- Escritorio ejecutivo: indicadores, gráfico y movimientos
- Transacciones: consulta y alta simulada
- Créditos: filtros por estado y oficina; detalle, alta y pagos con interés por mora
- Cheques/eCheqs: filtros, vencimientos y cobros simulados
- Agenda de cobranzas: consulta integrada de Créditos y Cheques
- Estadísticas: información ficticia y exportación CSV ilustrativa
- Usuarios y roles
- Oficinas

## Probar

Abrir `index.html` o publicar en GitHub Pages. No requiere instalar dependencias ni configurar servidores.

En **Settings → Pages**, configurar **Build and deployment → Source: GitHub Actions**. El workflow de `.github/workflows/pages.yml` publica automáticamente el frontend al actualizar `main`.

## Datos y seguridad
**Todos los datos son ficticios.** No se publicaron dumps, credenciales, contraseñas, contactos reales, código PHP/Laravel ni información de clientes. No se realiza ningún movimiento económico real. Los formularios sólo modifican registros simulados en la memoria de la pestaña y se reinician al recargar.

Esta demo no ofrece autenticación real, persistencia, integración bancaria, mensajes de WhatsApp ni cálculos financieros auditables. Su fin es exclusivamente comercial y visual.
