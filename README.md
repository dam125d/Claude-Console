# Claude Console

Consola de escritorio para Windows para trabajar con Claude Code en varios proyectos a la vez: varias consolas por proyecto, sesiones y pendientes para retomar sin gastar tokens, tablero SDD, catálogo de skills y carriles de bug en worktrees.

## Descargar

👉 **[Última versión](https://github.com/dam125d/Claude-Console/releases/latest)**: descarga `Claude.Console.Setup.<versión>.exe`.

## Instalar

1. Ejecuta el `.exe`. Se instala solo para tu usuario (no requiere administrador) y crea accesos directos en el escritorio y en el menú Inicio.
2. Windows SmartScreen avisará porque el instalador no está firmado: **Más información → Ejecutar de todas formas**.

### Requisitos

La consola usa las herramientas instaladas en tu PC. Verifica en una terminal nueva que respondan:

| Herramienta | Comprobar | Para qué |
|---|---|---|
| Claude Code | `claude --version` (con sesión iniciada) | Cada pestaña es un `claude` real |
| Node.js | `node --version` | Claude Code y los carriles |
| Git | `git --version` | Carriles de bug (worktrees) |
| Engram *(opcional)* | `engram --version` | Panel Memoria |

## Actualizar

Descarga el `.exe` de la nueva versión e instálalo encima, con la consola cerrada. Se conservan tus proyectos, pendientes y pestañas.

## Atajos

| Atajo | Acción |
|---|---|
| `Ctrl+Shift+T` | Nueva consola Claude |
| `Ctrl+Shift+L` | Nuevo carril de bug |
| `Ctrl+Shift+W` | Cerrar pestaña |
| `Ctrl+Tab` / `Ctrl+Shift+Tab` | Pestaña siguiente / anterior |
| `Ctrl+1` … `Ctrl+9` | Cambiar de proyecto |
| `Ctrl+Shift+1` … `4` | Consolas · Tablero SDD · Catálogo · Ajustes |
| `Ctrl+Shift+B` / `Ctrl+Shift+P` | Ocultar o mostrar el panel izquierdo / derecho |
| `Ctrl +` / `Ctrl -` / `Ctrl 0` | Zoom: acercar / alejar / restablecer |
| `Ctrl+C` con selección | Copiar |
| `Ctrl+V` | Pegar (si el portapapeles tiene una imagen, la recibe Claude Code) |

## Datos

Todo se guarda en tu PC, en `%APPDATA%\claude-console`. No se envía nada a ningún servidor aparte de lo que ya hace Claude Code.
