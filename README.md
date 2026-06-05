# Video_club
Diseño de bases de datos, gestión de Videoclub
El sistema tiene como objetivo administrar la información de un videoclub, incluyendo sus socios, películas, actores, directores, archivadores y alquileres. De esta forma, se puede mantener un control organizado del catálogo de películas, su almacenamiento y los préstamos realizados por los socios.

2. Identificación de entidades y atributos

 Entidades detectadas

A partir del análisis del problema se identificaron las siguientes entidades:

* Socio
* Director
* Película
* Actor
* Archivador
* Alquiler

### Atributos y tipos

#### Socio

**Atributos simples:**

* socio_id
* nombre
* dirección
* teléfono

**Atributos compuestos:** Ninguno.

**Atributos multivaluados:** Ninguno.

**Clave primaria (PK):**

* socio_id

---

#### Director

**Atributos simples:**

* director_id
* nombre

**Atributos compuestos:** Ninguno.

**Atributos multivaluados:** Ninguno.

**Clave primaria (PK):**

* director_id

---

#### Película

**Atributos simples:**

* título
* género
* año

**Atributos compuestos:** Ninguno.

**Atributos multivaluados:** Ninguno.

**Clave primaria (PK):**

* título, director_id y año (clave primaria compuesta según las reglas del negocio).

---

#### Actor

**Atributos simples:**

* actor_id
* nombre

**Atributos compuestos:** Ninguno.

**Atributos multivaluados:** Ninguno.

**Clave primaria (PK):**

* actor_id

---

#### Archivador

**Atributos simples:**

* archivador_id
* ubicación
* número_estanterías
* fecha_compra

**Atributos compuestos:** Ninguno.

**Atributos multivaluados:** Ninguno.

**Clave primaria (PK):**

* archivador_id

---

#### Alquiler

**Atributos simples:**

* alquiler_id
* fecha_alquiler
* fecha_devolución

**Atributos compuestos:** Ninguno.

**Atributos multivaluados:** Ninguno.

**Clave primaria (PK):**

* alquiler_id
