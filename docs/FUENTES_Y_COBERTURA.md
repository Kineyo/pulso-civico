# Catálogo de Fuentes Oficiales y Cobertura por Estado

> **Regla de adopción:** Si vas a scrapear un estado o integrar una nueva fuente, abre un Issue en GitHub con el título `[Scraper] Congreso de <Estado>` o `[Nueva fuente] <Nombre>` para asignártelo aquí.
> 
> **Convención de archivos:** `storage/data/json/congreso_<estado_slug>_leg_<numero>.json`  
> **Convención de scraper:** `src/Services/Scrapers/Congreso<Estado>ScraperService.php` (o en `src/Services/`)

---

## Leyenda de Estado
- ✅ **Completado / Cubierta**: Dataset integrado en `main`, verificado con SHA-256 y fuente `.gob.mx`.
- 🚧 **En Progreso**: Asignado a un colaborador con branch/PR activo.
- 🙋 **Disponible / Busca voluntario**: Pendiente de asignar. ¡Cualquiera puede adoptarlo!

---

## 1. Fuentes Federales y Órganos Autónomos

| Fuente | URL | Datos | Estado | Responsable |
|---|---|---|---|---|
| SIL – SEGOB | http://sil.gobernacion.gob.mx | Legisladores LXVI, perfiles, comisiones, trayectoria, fotos | ✅ | Core |
| SITL – Cámara de Diputados | https://sitl.diputados.gob.mx/LXVI_leg/ | Votaciones nominales, asistencias LXVI | ✅ | Core |
| SIL – legislaturas anteriores (LX–LXV) | http://sil.gobernacion.gob.mx | Históricos para seguir trayectorias | 🙋 | — |
| SITL – legislaturas anteriores | https://sitl.diputados.gob.mx | Votaciones históricas | 🙋 | — |
| Senado de la República | https://www.senado.gob.mx | Senadores, votaciones, asistencias | 🙋 | — |
| Gaceta Parlamentaria | https://gaceta.diputados.gob.mx | Iniciativas, dictámenes | 🙋 | — |
| Diario de los Debates | https://cronica.diputados.gob.mx | Qué dijo cada legislador en tribuna | 🙋 | — |
| INE – Cómputos y candidaturas | https://www.ine.mx | Candidaturas, coaliciones, resultados | 🙋 | — |
| Declaranet / PNT | https://www.plataformadetransparencia.org.mx | Declaraciones patrimoniales públicas | 🙋 | — |

---

## 2. Congresos Locales (32 Entidades Federativas)

| ID | Entidad Federativa | Portal Oficial | Legislaturas | Estado | Responsable / PR |
|---|---|---|---|---|---|
| 01 | **Aguascalientes** | https://congresoags.gob.mx | — | 🙋 Disponible | — |
| 02 | **Baja California** | https://www.congresobc.gob.mx | XVI a XXV (10 legs, 250 dips) | ✅ Completado | Issue #12 |
| 03 | **Baja California Sur** | https://www.cbcs.gob.mx | — | 🙋 Disponible | — |
| 04 | **Campeche** | https://congresocampeche.gob.mx | — | 🙋 Disponible | — |
| 05 | **Coahuila** | https://congresocoahuila.gob.mx | — | 🙋 Disponible | — |
| 06 | **Colima** | https://congresocolima.gob.mx | — | 🙋 Disponible | — |
| 07 | **Chiapas** | https://www.congresochiapas.gob.mx | — | 🙋 Disponible | — |
| 08 | **Chihuahua** | https://www.congresochihuahua.gob.mx | — | 🙋 Disponible | — |
| 09 | **Ciudad de México** | https://www.congresocdmx.gob.mx | — | 🙋 Disponible | — |
| 10 | **Durango** | https://congresodurango.gob.mx | — | 🙋 Disponible | — |
| 11 | **Guanajuato** | https://www.congresogto.gob.mx | — | 🙋 Disponible | — |
| 12 | **Guerrero** | https://congresogro.gob.mx | — | 🙋 Disponible | — |
| 13 | **Hidalgo** | https://www.congresohidalgo.gob.mx | — | 🙋 Disponible | — |
| 14 | **Jalisco** | https://www.congresojal.gob.mx | — | 🙋 Disponible | — |
| 15 | **Estado de México** | https://legislativoedomex.gob.mx | — | 🙋 Disponible | — |
| 16 | **Michoacán** | https://congresomich.gob.mx | — | 🙋 Disponible | — |
| 17 | **Morelos** | https://congresomorelos.gob.mx | — | 🙋 Disponible | — |
| 18 | **Nayarit** | https://congresonayarit.gob.mx | — | 🙋 Disponible | — |
| 19 | **Nuevo León** | https://www.hcnl.gob.mx | — | 🙋 Disponible | — |
| 20 | **Oaxaca** | https://www.congresooaxaca.gob.mx | — | 🙋 Disponible | — |
| 21 | **Puebla** | https://www.congresopuebla.gob.mx | — | 🙋 Disponible | — |
| 22 | **Querétaro** | https://legislaturaqueretaro.gob.mx | — | 🙋 Disponible | — |
| 23 | **Quintana Roo** | https://congresoqroo.gob.mx | — | 🙋 Disponible | — |
| 24 | **San Luis Potosí** | https://congresosanluis.gob.mx | — | 🙋 Disponible | — |
| 25 | **Sinaloa** | https://www.congresosinaloa.gob.mx | — | 🙋 Disponible | — |
| 26 | **Sonora** | https://www.congresoson.gob.mx | — | 🙋 Disponible | — |
| 27 | **Tabasco** | https://congresotabasco.gob.mx | — | 🙋 Disponible | — |
| 28 | **Tamaulipas** | https://www.congresotamaulipas.gob.mx | LVII a LXVI (10 legs, 306 dips) | ✅ Completado | PR #8 |
| 29 | **Tlaxcala** | https://congresotlaxcala.gob.mx | — | 🙋 Disponible | — |
| 30 | **Veracruz** | https://www.legisver.gob.mx | — | 🙋 Disponible | — |
| 31 | **Yucatán** | https://www.congresoyucatan.gob.mx | — | 🙋 Disponible | — |
| 32 | **Zacatecas** | https://www.congresozac.gob.mx | — | 🙋 Disponible | — |

---

## 3. Noticias y Medios (Fase Posterior)

| Medio | RSS | Estado |
|---|---|---|
| *(por definir en comunidad, priorizando pluralidad editorial)* | — | 🙋 Busca voluntario |

---

## 4. Reglas para Agregar Fuentes
- Debe ser **oficial** (dominio `.gob.mx`, órgano autónomo constitucional) o medio periodístico formalmente identificable.
- Revisar `robots.txt` y términos de uso antes de scrapear.
- Documentar formato original (HTML, PDF, CSV, API) y frecuencia de actualización estimada.

---

## 5. Protocolo para Reclamar y Entregar un Estado o Fuente

1. **Reclamar**:
   - Avisa en el grupo o abre un Issue en GitHub: *"Tomo el Congreso de <Estado>"* o *"Nueva fuente: <Nombre>"*.
   - Se actualiza la tabla marcando 🚧 **En Progreso** y tu nombre/usuario de GitHub.
2. **Crear el Scraper**:
   - Programar en `src/Services/Scrapers/Congreso<Estado>ScraperService.php` (o `src/Services/`).
   - Seguir [`docs/COMO_CREAR_UN_SCRAPER.md`](COMO_CREAR_UN_SCRAPER.md).
   - Rate limit mínimo: 1,000 ms; sin peticiones en paralelo.
3. **Subir los datos con evidencia**:
   - Los registros deben incluir `fuente_url` al portal oficial `.gob.mx` y hash SHA-256 de respaldo.
4. **Validación y Merge**:
   - Validar sintaxis y salud del proyecto:
     ```bash
     php tools/gateway.php lint "<archivos_modificados>"
     php tools/gateway.php health
     ```
     *(En Windows: `powershell -ExecutionPolicy Bypass -File .\tools\run.ps1 lint "<archivos>"`)*
   - Someter Pull Request para auditoría automatizada.
