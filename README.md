

---

# Trabajo Practico N°6 - pandas y sqlite

## como usar el repositorio

1. **Clonamos el repositorio en la computadora**:
   ```bash
   git clone https://github.com/luciannoFr/pandas_df_tlp3_roa_luciano
   ```

2. **vamos al directorio del repositorio**:
   ```bash
   cd pandas_df_tlp3_roa_luciano
   ```

3. **Crear un entorno virtual**:
    para que el proyecto se ejecute de manera segura y aislada hay que hacer un entorno virtual, que se hace de la siguiente forma:
   - **En Windows**:
     ```bash
     python -m venv venv
     ```
   
   - **En macOS/Linux**:
     ```bash
     python3 -m venv venv
     ```

4. **Activamos el entorno virtual**:

   - **En Windows**:
     ```bash
     .\venv\Scripts\activate
     ```

   - **En macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

    para saber si esta activo, en la terminal saldrá venv al incio
5. **Instalamos las dependencias**:
   Una vez activado el entorno virtual, instalá las librerías necesarias para ejecutar el cuaderno de Jupyter.
   ```bash
   pip install -r requirements.txt
   ```

6. **Abrimos Visual Studio Code**:
   ```bash
   code .
   ```

7. **Seleccionamos el archivo `.ipynb` que contiene las actividades**:
   En VS Code, selecciona el archivo `actividad_df.ipynb` y se ejecuta cada bloque de codigo para ver si esta bien

---

## Requisitos

Para poder ejecutar se necesiita:

- **Python 3.x**  
- **Visual Studio Code** con alguna de las siguientes extensiones:
    - **Jupack**
    - La extension oficial de jupyter notebook para Visual Studio Code.

- **Dependencias**: Las librerías necesarias estan escritas en el archivo `requirements.txt`, la podemos instalar asi:
  ```bash
  pip install -r requirements.txt
  ```

---

## Cosas para aclarar del entorno virtual

- Si ya terminó o quiere salir del entorno virtual, se usa:
  ```bash
  deactivate
  ```
- Si no esta `Jupyter` instalado, podés instalarlo con:
  ```bash
  pip install notebook
  ```