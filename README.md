# 🔃 HotRecovery-RMAN- 📀

---
- Ingresamos a la consola de Docker y luego ingresamos a la consola SQL como sysdba

<img width="975" height="350" alt="image" src="https://github.com/user-attachments/assets/90e4b115-f8b3-4ff0-9c8c-6f170eb741b8" />

---

- Verificamos el estado, cerramos la BD y la montamos.

<img width="975" height="692" alt="image" src="https://github.com/user-attachments/assets/1c197df1-f6be-453e-9d40-0021902038b4" />

---

- Habilitamos los ARCHIEVELOG

<img width="975" height="242" alt="image" src="https://github.com/user-attachments/assets/1ee46fd0-0b34-4a06-a739-54c9ad0e0d33" />

---

- Ahora el estado aparece habilitado

<img width="975" height="281" alt="image" src="https://github.com/user-attachments/assets/cca51453-5585-46b7-ac6a-0f32d2cc8504" />

---

- Activamos el archivado automático

<img width="975" height="185" alt="image" src="https://github.com/user-attachments/assets/7af039c1-0306-4127-b1d4-28a6d3dc4d9b" />

---

## 📍Abrimos una nueva consola de Docker con el comando: docker exec -it “nombre del contenedor” (en mi caso es oracle19c) bash

---

- Una vez dentro de la consola de Docker ingresamos

<img width="974" height="318" alt="image" src="https://github.com/user-attachments/assets/a5e1b433-5c5a-4555-ab18-54e6c1629fb8" />

---

- Vemos la política actual

<img width="974" height="132" alt="image" src="https://github.com/user-attachments/assets/fbf9b006-b4ca-40e2-94b4-ef58421a0385" />

---

- Configuramos la política de retención para conservar solo 2 backups

<img width="974" height="202" alt="image" src="https://github.com/user-attachments/assets/163198ad-52f6-4796-bf4d-41eaec1fae65" />

---

- Agregamos el respaldo automático del control file

<img width="974" height="189" alt="image" src="https://github.com/user-attachments/assets/a3cd17b7-4702-4933-9472-6399faebf95f" />

--- 

- Configuramos el formato del controle file backup

<img width="974" height="184" alt="image" src="https://github.com/user-attachments/assets/53480a70-3408-479a-8e40-cc36745f5fb5" />


---

- Establecemos el tipo de dispositivo por defecto el disco

<img width="974" height="205" alt="image" src="https://github.com/user-attachments/assets/3d7bb021-9899-4b95-be5a-8783f8b937f2" />

---

- Configuramos el canal de respaldo y la ruta para los datafiles

<img width="974" height="181" alt="image" src="https://github.com/user-attachments/assets/ad94f19c-1ea6-48f4-9d00-065dd3dec203" />

---

- Permitirnos el tamaño ilimitado para los conjuntos de backup

<img width="976" height="214" alt="image" src="https://github.com/user-attachments/assets/551c5652-cda4-4f43-a624-d23b5010c5b8" />

---


## ✅Ya configurado el RMAN procedemos a ejecutar el backup

---

- Hacemos backup de los datafiles

<img width="975" height="973" alt="image" src="https://github.com/user-attachments/assets/ea5d546b-2786-4c31-a798-ab92bbf50d1f" />

---

- Borramos los ARCHIVELOG obsoletos

<img width="975" height="496" alt="image" src="https://github.com/user-attachments/assets/d1970d42-a6e5-4776-9020-fab3df81ced6" />

---

- Copia extra de los controlfiles

<img width="975" height="326" alt="image" src="https://github.com/user-attachments/assets/5e6f8e2e-b6bd-4859-b5eb-6c0b0d2d1646" />

---

- Borramos las copias obsoletas

<img width="975" height="361" alt="image" src="https://github.com/user-attachments/assets/26adc132-14d3-42af-896e-1ac74cd744a7" />








