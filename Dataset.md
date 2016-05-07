
Información 
===================

La información que se tiene es sobre pacientes con diabetes que se encuentran hospitalizados en los Estados Unidos, se tiene los datos suficientes para el análisis.
Gestión de la hiperglucemia en pacientes hospitalizados tienen repercusiones en los resultados de 10 años de la atención clínica en:
130 hospitales:
	Medio Oeste= 18 hospitales
	Noreste = 58 hospitales
	Sur = 28 hospitales
	Oeste = 16 hospitales

Se tienen 101767 pacientes en el dataset.

Descripción de las columnas
-------------


Se hará la descripción de las columnas que se consideran necesarias para el análisis:

	 - **patient_nbr:** Codigo que tiene cada paciente.
	 - **race:** La raza a la que pertenece el paciente. Puede ser: Caucasian, AfricanAmerian, Asian, Hispanic o Other.
	 - **gender**: Sexo del paciente puede ser Male o Female.
	 - **age**: La edad del paciente. Este atributo se encuentra dentro de un rango por ejemplo:  [0-10), [70-80).
	 - **admission_type_id**: Tiene la información del tipo de admisión que se le dió al paciente. Puede tener valores del 1 al 8 la descripción la tenemos en el archivo IDs_mapping.csv los tipos de admisión son: Emergency, Urgent, Elective, Newborn, Not Available, NULL, Trauma Center y Not Mapped.
	 - **discharge_disposition_id**: El id de la disposición de descarga, indica que es lo que se hará con el paciente por ejemplo que pueda ser dado de alta e ir a su casa o ser transferido a otro hospital. La descripcion de cada id esta en el archivo IDs_mapping.csv.
	 -  **admission_source_id**: Id de la fuente de ingreso del paciente indica cómo se lo derivó para que ingrese al hospital. La descripcion la tenemos en el archivo IDs_mapping.csv.
	 - **time_in_hospital**: Tiempo que pasa en el hospital el paciente en días.
	 - **medical_specialty**: Especialidad médica en la que estaderivado el paciente.
	 - **num_medications**: Cantidad de medicación que se le da al paciente.
	 - **number_diagnoses**: Número de diagnósticos que se le hace al paciente.
	 - **insulin**: Indica el nivel de insulina que tiene el paciente.
	 