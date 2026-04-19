# Sesion05Maven-vgr004

El Dependency Check (el plugin que busca vulnerabilidades en tus librerías) está intentando conectar con un servidor externo (ossindex.sonatype.org) y este le está denegando el acceso con un error 401 Unauthorized.

Se ha usado este comando para obviarlo

mvn clean verify site "-Ddependency-check.skip=true"

[![Maven Build](https://github.com/ualhmis2026-g16/Sesion05Maven-vgr004/actions/workflows/maven-build.yml/badge.svg)](https://github.com/ualhmis2026-g16/Sesion05Maven-vgr004/actions/workflows/maven-build.yml)
