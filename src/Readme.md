## Pasos seguidos

1) Creada rama readme
2) Checkout rama readme
   - creado archivo readme.md
3) Checkout rama interface
   - revert al commit anterior
   - (para duplicar un commit y traerlo al la cabecera sin borrar commits posteriores)
4) Creada rama final
   - (para poder hacer merge de las dos otras ramas sin preocuparme de los comits)
5) Checkout rama final
   - Merge interface 
   - Merge datos
6) Checkout rama main
   - Merge squash final
