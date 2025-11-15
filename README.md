# Chomsky-Classifier-AI
1. Obtener el código desde GitHub
    * Opción A: Clonar: usa `git clone <URL-de-tu-repositorio> chomsky_classifier_ai` y entra a la carpeta del proyecto con `cd chomsky_classifier_ai`.
    * Opción B: ZIP: descarga el ZIP desde GitHub (Code → Download ZIP) y descomprímelo.

2. Requisitos

    * Python 3.9 o superior y `pip` funcionando.
    * `reportlab` para PDF, `streamlit` para la interfaz web, Graphviz del sistema y la librería `graphviz` o `pygraphviz` para exportar PNG desde DOT.

3. Instalar y ejecutar

    * `python -m pip install --upgrade pip`
    * `python -m pip install reportlab / streamlit / graphviz`
    * Ejecutar en modo consola: `python main.py`
    * Ejecutar interfaz web (Streamlit): `python -m streamlit run streamlit_app.py`

4. Uso básico

    * CLI: pega una gramática o un autómata AFD/AP/MT de la carpeta de `examples` y presiona Enter en blanco para terminar; verás el tipo detectado y la explicación paso a paso; se genera `gramatica.dot` o `automata.dot`.
    * Reporte: desde el menú del CLI se crea `reporte.pdf` gracias al `reportlab`.
    * Interfaz web: permite clasificar, convertir Regex→AFD→Gramática Regular y GLC→AP, descargar DOT; incluye un modo Quiz para práctica.

