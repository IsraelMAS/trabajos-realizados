# 📁 Trabajos realizados — Israel Angulo Salas

Portafolio de proyectos full stack desarrollados por **Israel Angulo Salas** (IsraelMAS).
Cada carpeta es un **submódulo de Git** que apunta al repositorio original del proyecto.

## Proyectos

| Proyecto | Carpeta | Descripción | Stack |
|---|---|---|---|
| **Abastix** | [`fullstack/abastix`](https://github.com/IsraelMAS/abastix) | Plataforma de gestión comercial, inventario y punto de venta (POS). | React 19 · Vite · Tailwind CSS 4 · Spring Boot 4 · Java 21 · SQL Server 2022 · RabbitMQ · Docker Compose |
| **FisioMarca** | [`fullstack/FisioMarca`](https://github.com/IsraelMAS/FisioMarca) | Plataforma web para un centro de fisioterapia: reservas con horario real, carrito, pagos y panel de administración. | Microservicios Spring Boot (Eureka, API Gateway, OpenFeign, JWT, SOAP + REST) · Next.js 16 · React 19 · TypeScript · MySQL 8.4 · Docker |
| **Sistema de Carga Aérea** | [`fullstack/sistema-carga-aerea`](https://github.com/IsraelMAS/sistema-carga-aerea) | Gestión de usuarios, vuelos, encomiendas y operaciones de carga aérea con roles. | Spring Boot · Spring Security + JWT · Angular · monorepo pnpm |
| **Barbershop** | [`java-web/ProyBarberia2025`](https://github.com/IsraelMAS/ProyBarberia2025) | Sistema web de gestión de citas, turnos y control operativo de barberías. | Java Web (JSP/Servlets) · Maven · MySQL |
| **AppWebFerreteria** | [`dotnet/AppWebFerreteria`](https://github.com/IsraelMAS/AppWebFerreteria) | Aplicación web para ferretería con arquitectura en capas (Datos, Dominio, Negocio, Web). | ASP.NET MVC · .NET Framework 4.7.2 · C# |

## Clonar todo de una vez

```bash
git clone --recurse-submodules https://github.com/IsraelMAS/trabajos-realizados.git
```

Si ya lo clonaste sin submódulos:

```bash
git submodule update --init --recursive
```

Para traer los últimos cambios de todos los proyectos:

```bash
git submodule update --remote --merge
```

## Contacto

- GitHub: [@IsraelMAS](https://github.com/IsraelMAS)
