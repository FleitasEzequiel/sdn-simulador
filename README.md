## Instalación
1. Clonar el repositorio con el comando ```git clone```

```bash
git clone https://github.com/FleitasEzequiel/sdn-simulador.git
```

2. Dirigirse a la carpeta __snd-simulador__

```bash
cd sdn-simulador
```

3. Crear el entorno virtual e instalar las dependencias con __uv__.

```bash
uv sync
```

4. Activar el entorno virtual.

```bash
.venv/Scripts/Activate
```

## Ejecución

* Correr el simulador:
```bash
python main.py 
```

* Correr los tests:
```bash
python tests.py
```