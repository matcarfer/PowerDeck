# Política de privacidad

**Español** · [English](PRIVACY.md)

*Última actualización: 2026-11-11 · Vale para PowerDeck (`io.github.matcarfer.powerdeck`), todas las versiones.*

**PowerDeck no junta, no comparte ni vende ningún dato. Nada sale de tu equipo.**

- **Sin permiso de internet.** Sin servidores, cuentas, publicidad, estadísticas ni rastreadores; sin librerías de terceros. Los únicos permisos son `ACCESS_NETWORK_STATE` (para mostrar la IP del equipo) y, opcional, `WRITE_SECURE_SETTINGS`, que solo podés dar vos desde una computadora, para manejar adb sin root.
- Solo corre, en el mismo equipo, la acción que vos confirmás (apagar, reiniciar, interruptores de adb…): con `su` si hay root, o cambiando los ajustes de adb si no.
- **Lo que queda en el equipo:** nada personal. Los interruptores de adb dejan un script de arranque en `/data/adb/service.d` y dos propiedades del sistema (`debug.powerdeck.*`) solo mientras los tengas prendidos; al apagarlos se borran.
- Si esta política cambia alguna vez, el cambio va a figurar en el [CHANGELOG](CHANGELOG.md). Preguntas: abrí un issue.
