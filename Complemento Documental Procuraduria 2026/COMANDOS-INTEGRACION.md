# Integración sin sobrescribir el repositorio original

```powershell
git clone https://github.com/ecapdevilla/material-concurso-procuraduria.git
cd material-concurso-procuraduria
git switch -c docs/complemento-auditoria-2026
# Extraiga el ZIP y copie su contenido dentro de esta carpeta, conservando rutas.
git status
git add .
git commit -m "docs: auditoria y complemento de estudio Procuraduria 2026"
git push -u origin docs/complemento-auditoria-2026
```

Revisar los cambios antes de crear PR y fusionar a `master`. No hacer `git add` de credenciales ni certificados personales.
