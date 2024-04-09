# Visualizar inferencias
- Clonar el proyecto usando 
```bash
git clone https://github.com/GBM-images-research/visualizar_inferencia.git
cd visualizar_inferencia
```
- Descargar el archivo `inferences.zip` en este link https://drive.google.com/file/d/1voFM5cCB4QvCoFZCncFn6aGfU8V2VlIM/view?usp=drive_link
- Descomprimirla en la carpeta raiz del proyecto de modo que quede el path `visualizar_inferencia/inferences`
- Descargar el archivo `Datset.zip` en este link https://drive.google.com/file/d/1kSq5qhkkc_H3AadspoddtbMi8-uECc6I/view?usp=drive_link
- Descomprimirla en la carpeta raiz del proyecto de modo que quede el path `visualizar_inferencia/Dataset/test` y `visualizar_inferencia/Dataset/recurrence`

## Generar un entorno virtual .venv

En window 
```bash 
python -m venv .venv
```
En linux
```bash 
python3 -m venv .venv
```
Activar el ambiente virtual en window
```bash
.\.venv\Scripts\activate
```
Activar el ambiente virtual en linux
```bash
.venv/bin/activate
```
## Instalar dependencias
```bash
pip install -r requirements.txt
```
## Correr el script `visualizar_slices.py`
En window
```bash
python visualizar_slices.py --serie 36
```
En linux
```bash
python3 visualizar_slices.py --serie 36
```
El valor `36` es el número de serie que se desea visualizar, puedes seleccionar cualquier número de serie presente en la carpeta `inferences` seg_00036.npy, seg_00042.npy, ... Solo poner el entero sin los ceros a la izquierda.