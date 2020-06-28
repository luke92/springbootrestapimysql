# Spring Boot with REST API wuth MySQL
Requires JDK 8, MAVEN 3 and MySQL 5
# Change DATABASE in the file application.properties
# If you have una SQL Exception by Time Zone, run this code

  -- SABER LA VERSION DE MI MYSQL <br>
SELECT version (); <br>
-- DEFINIR LAS ZONA HORARIA <br>
SET @@global.time_zone = '+00:00'; <br>
SET @@session.time_zone = '+00:00'; <br>
-- VER MI CONFIGURACION DE ZONA HORARIA <br>
SELECT @@global.time_zone, @@session.time_zone; <br>
