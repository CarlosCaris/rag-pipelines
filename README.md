# Source

La idea de este repositorio es documentar el proceso de iniciar un proyecto en Python usando [UV](https://docs.astral.sh/uv/getting-started/installation/).

Ademas, se utilizara el siguiente repositorio para probar el pipeline de RAG: [rag-pipelines](https://github.com/NirDiamant/RAG_Techniques)

Algunos articulos de interes:

- [Strategies for Optimal Performance of RAG](https://medium.com/@bijit211987/strategies-for-optimal-performance-of-rag-6faa1b79cd45)

### Como iniciar un proyecto en Python usando UV

1.- Instalar [UV](https://docs.astral.sh/uv/getting-started/installation/)

2.- Instalar Python

`uv python install 3.11 3.12 3.13`

3.- Pinnear una version de Python

`uv python pin python3.11`

Creara el archivo .python-version con la version de Python que elegimos

4.- Inicializar un proyecto

`uv init`

5.- Crear el ambiente virtual

`uv venv`

6.- Activar el ambiente virtual

`.venv\Scripts\activate`

7.- Lock dependencies

`uv pip compile pyproject.toml -o requirements.txt`

8.- Instalar las dependencias

`uv pip install -r pyproject.toml`
