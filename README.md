# Trabajo Práctico - Desarrollo de Software (DSW) 🏟️
> **UTN Facultad Regional Rosario**

---

<p align="center">
  <img src="imagenes/UTN_logo.jpg" alt="Logo UTN" width="500" height="500">
</p>

## 👥 Integrandes del grupo
* 53786, Ondategui, Mateo. 
* 54153, Lagostina, Lautaro Antolin
* 55027, Surjak, Mirko.


## 📝 Descripción del Proyecto
La propuesta de nuestro trabajo consiste en desarrollar un sistema que permita la gestión de alquileres de canchas de distintos deportes. Los Clientes podrán visualizar los turnos disponibles y realizar reservas sobre los mismos. Además, el Encargado podrá gestionar las canchas que tenga asignadas. Finalmente, el Dueño podrá acceder a distintas métricas relevantes para analizar el rendimiento de su negocio.

---

## 🏗️ Arquitectura y Modelo

<p align="center">
  <img src="imagenes/oscuro2.jpg" alt="Modelo de Dominio" width="100%">
  <br>
  <em>Diagrama de Modelo de Dominio</em>
</p>

---

## 🚀 Alcance del Sistema


| Categoría | Detalle de Funcionalidades |
| :--- | :--- |
| **CRUDs Simples** | • CRUD Cliente <br> • CRUD Encargado de cancha <br> •CRUD  Dueño de cancha <br> • CRUD Turno <br> • CRUD Tipo de cancha <br> • CRUD Tipo de turno |
| **CRUDs Dependientes** | • CRUD **Localidad** {depende de} CRUD Provincia <br> • CRUD **Cancha** {depende de} CRUD Complejo |
| **Listado + detalle** | 1. Disponibilidad de complejos por horario y deporte. <br> 2. Historial de turnos realizados por complejo con detalle. <br> 3. Reporte de reservas diarias. <br> 4. Recaudación mensual detallada por complejo. |
| **CUU/Epic** | • Reservar un turno de una cancha en un horario <br> • Cancelar un turno <br> • Registrarse como cliente <br> • Enviar recordatorio de turno previo a su realización <br> • Dar de alta cuenta de dueño de complejo <br> • Recuperación de contraseña <br> |

---





