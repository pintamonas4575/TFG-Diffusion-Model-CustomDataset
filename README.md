# TFG-Diffusion-Model-CustomDataset
Creación en Pytorch de un modelo de difusión para generación incondicional de imágenes con un dataset propio.

Se ha creado un modelo que sigue el estándar DDIM sobre un *dataset* local de imágenes.

🙋‍♂️ Los archivos de este repositorio pertenecen al **TFG** de **Alejandro Mendoza Medina**.

----------------------

# 📓 Notebook *DDIM_50_steps*

Este notebook es el corazón de la creación y entrenamiento del modelo de difusión. Se ha hecho uso del algoritmo DDIM (***D**enoising **D**iffusion **I**mplicit **M**odels*) con *noise scheduler* de tipo coseno. Se ha entrenado con 1000 *timesteps* pero la generación se ha hecho con 50 pasos, gracias a la ventaja de flexibilidad frente al algoritmo DDPM (***D**enoising **D**iffusion **P**robabilistic **M**odels*).

Se ha entrenado durante 580 *epochs*, tardando 87 horas en completar el entrenmiento.

# 📓 Notebook *DDIM_pruebas_generación*

Este notebook presenta la evolución de una semilla a lo largo de los *epochs*, así como distintas pruebas de generación. 

# 📂 Carpeta "generated-samples"

En esta carpeta se encontrarán ejemplos generados por el modelo.

# ⚖️ Licencia

Hay algún proceso "difuminado" en la burocracía de España que hace que vaya muy lenta. 

# 👤 Contacto

Cualquier duda o sugerencia contactar con el autor:

Alejandro Mendoza: alejandro.embi@gmail.com

