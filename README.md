# DNI-EXTRACTOR



Este código genera un DNI español a partir del nombre completo de una persona. Para ello, primero calcula la suma de los códigos ASCII de todos los caracteres alfabéticos del nombre. A continuación, utiliza esta suma para calcular el número de control del DNI. Por último, combina el número de control con los primeros 8 dígitos del DNI para obtener el número completo.

## Instalar con PyPI

```bash
pip install dni-extractor
```

## Uso

```py
from dni-extractor import main

main()
```

```bash
$ python -m dni-extractor
#o
$ dni-extractor
```


