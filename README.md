# wiki
Main Wiki for http://hacklab.cc/

## Contributing

1.  Create a fork of this repository

2.  Edit the files

3.  Submit Pull Request.
   
4. The Wiki Administrator will then export the modifications to the Wiki.


## Wiki Structure


```
├── Blog.md
├── Contacto.md
├── Equipamiento
│   ├── Condiciones_de_uso.md
│   └── Inventario.md
├── Equipamiento.md
├── LICENSE
├── Membresia.md
├── Nosotros
│   └── README.txt
├── Nosotros.md
├── README.md
├── Tutoriales
│   └── README.txt
└── Tutoriales.md
```

*  As you can see each directory has it's own md file at the same level.
   
   for example:
 
   Equipamiento has an Equipamiento.md file on the root and the directory 
   
   Contains two more files, this structure at export time will render to the following

   web structure:

```
   md file /Equipamiento.md -> http://hacklab.cc/Equipamiento

   md file /Equipamiento/Condiciones_de_uso.md -> http://hacklab.cc/Equipamiento/Condiciones_de_uso

```

