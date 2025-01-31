# Backend de Ludex  
## Formato  
- Inglés
- Clases Singular PascalCase  
- Tablas Plural snake_case  
- Campos camelCase
```java
@Table(name = "users") // cuando se crea la tabla lo nombra 'users'
private class User { // clase singular PascalCase
    private Long id; 
    private String createdAt; // campo camelCase, cuando se crea la tabla aparece 'created_at
}
```  
## Flujo del Proyecto  
### Configurar Git  
Configurar con su nombre y gmail para que se guarden sus cambios con su nombre y gmail.  
```bash  
git config --global user.name "Tu Nombre"  
git config --global user.email "tu.email@example.com"  
```  
### Clonar Repositorio  
Tendrás el repositorio en tu máquina.  
```bash  
git clone https://github.com/Uhziel-1/art-ludex-backend.git  
```  
### Trabajar  
1. Entra al proyecto  
```bash  
cd art-ludex-database  
```  
2. Crea una rama nueva  
```bash  
git checkout -b nueva_rama  
```  
3. Trabaja en el código  
4. Actualiza tu rama  
Cambia a la rama principal  
```bash  
git checkout main  
```  
Trae los cambios  
```bash  
git pull origin main  
```  
Vuelve a tu rama  
```bash  
git checkout nueva_rama  
```  
Trae los cambios de la rama main  
```bash  
git merge main  
```  
5. Resuelve conflictos (si hay)  
Si dos personas modifican las mismas partes del código, esto puede generar un conflicto.  
Abre el archivo marcado con conflicto.  
Busca las líneas entre `<<<<<<`, `======`, y `>>>>>>` que indican el conflicto.  
Edita el código para resolver el conflicto y guarda el archivo.  
7. Guarda los cambios  
```bash  
git status  
git add .  
git commit -m "Descripción de lo que se hizo"  
```  
8. Sube la github la rama
```bash
git push origin nueva_rama
```  
9. Crea un pull request en github
Ve al repositorio en GitHub.
GitHub te sugerirá crear un Pull Request cuando detecte que has subido una nueva rama.
Sigue las instrucciones para crear el PR, explica qué cambios hiciste y por qué son importantes.
### Datos
Por cada nueva tarea que hagas tienes que crear una nueva rama, si nó no aparecerá lo del pull request.
#   e x a m e n  
 #   e x a m e n  
 #   e x a m e n  
 