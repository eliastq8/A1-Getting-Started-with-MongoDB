# A1-Getting-Started-with-MongoDB

## Objetivos
- Configurar un clúster gratuito de MongoDB Atlas.
- Crear una base de datos y una colección.
- Insertar y consultar datos en la colección.
- Documentar el proceso y los hallazgos.

## Pasos de la tarea

### 1. Configurar MongoDB Atlas
1. Crea una cuenta gratuita en [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
2. Configura un nuevo clúster.
3. Crea una base de datos llamada `NoSQL_Intro` con una colección llamada `Users`.
4. Crear el usuaruio para acceder y agregar la IP
5. Instalar MongoDB 

### 2. Insertar documentos de muestra
Inserta tres documentos en la colección `Users`.
```json
{
  "name": "John Doe",
  "age": 29,
  "interests": ["coding", "reading"],
  "location": "USA"
}
```
![image](https://github.com/user-attachments/assets/e091ca83-fdcb-4192-b8bc-d21c9bdaab2e)
--
### 3. Realizar Consultas Básicas
```json
db.Users.find({})
```
![image](https://github.com/user-attachments/assets/3a0dc2dd-2d54-4380-bed2-c33b83266d65)
--
