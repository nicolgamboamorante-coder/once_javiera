# Explicación de etiquetas semánticas

**header**: para el título y presentación.

**main**: contiene el contenido principal.

**article**: porque todo trata sobre mi perfil.

**section**: para dividir la información en partes.

**ul> y <li**: para listas de habilidades y pasatiempos.

**aside**: para información adicional.

**footer**: para el contacto.

**address**: para datos de contacto.

**time**: para una fecha importante.

**strong**: para resaltar una palabra clave.

# Árbol DOM 

html
├── head
│   ├── meta
│   ├── meta
│   └── title
│
└── body
    ├── header
    │   ├── h1
    │   └── p
    │
    ├── main
    │   ├── article
    │   │   ├── section (Sobre mí)
    │   │   │   ├── h2
    │   │   │   ├── p
    │   │   │   │   └── time
    │   │   │   └── p
    │   │   │       └── strong
    │   │   │
    │   │   └── section (Habilidades)
    │   │       ├── h2
    │   │       ├── section
    │   │       │   ├── h3
    │   │       │   └── ul
    │   │       │       ├── li
    │   │       │       ├── li
    │   │       │       └── li
    │   │       │
    │   │       └── section
    │   │           ├── h3
    │   │           └── ul
    │   │               ├── li
    │   │               ├── li
    │   │               └── li
    │   │
    │   └── aside
    │       ├── h2
    │       └── p
    │
    └── footer
        ├── h2
        └── address
            ├── p
            │   └── a
            ├── p
            │   └── a
            └── p