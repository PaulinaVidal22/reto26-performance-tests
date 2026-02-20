cat > README.md <<'EOF'
# Reto 2026 - QA - Performance Tests (Ithaka & Nettra)

Repo de **pruebas de performance** para los dos proyectos del Reto:
- **Ithaka**
- **Nettra**

La idea es mantener **un repo por tipo de prueba** (API / E2E / Performance / IA).  
Dentro de cada repo se separa por proyecto (Ithaka / Nettra).

## Estructura

- `scenarios/ithaka/` escenarios de carga Ithaka (k6)
- `scenarios/nettra/` escenarios de carga Nettra (k6)
- `data/` datos de prueba por proyecto
- `config/` configuración por proyecto
- `docs/` notas de qué se mide y por qué
- `reports/` salida de resultados 
- `scripts/` helpers
