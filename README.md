# Application-Web-Design

## Activity 1

### Michel Alexis Bocanegra Arredondo - AL02997578

### Software Development Engineering -  José Antonio León Borges


###  8th Semester 

markdown is a basic type of text format, its used regularly to maximize readability
its main focus is to be easy-to-read in online forums, collaborative software,
documentation pages, and readme files. despite being basic it has enough characteristics
like:

> This is a quote

**able to quote**

1. list
2. format
3. that work 
4. automatic

**tables**



-[ ] checkmarks
-  [x] completed


**Checkmarks** 

**and some stylistic choises** 

This is **bold**

This is *italic*

This is ~~crossed out~~ 

This is ==highlighted==

**and basic code format**

JS Variable: `let x = 1` 

# Homework 1

```markdown
### 1. **Verificar el estado de un repositorio local:**
```bash 
   git status
```

---

### 2. **Agregar archivos individuales o globalmente:**
- **Archivo individual:**
  ```bash
  git add <archivo>
  ```
- **Todos los archivos:**
  ```bash
  git add .
  ```

---

### 3. **Agregar comentarios al commit:**
```bash
git commit -m "Mensaje descriptivo"
```

---

### 4. **Subir cambios al repositorio remoto:**
```bash
git push origin <rama>
# Opcional (si ya sigues la rama remota):
git push
```

---

### 5. **Gestionar ramas:**
- **Crear rama:**
  ```bash
  git branch <nombre-rama>
  ```
- **Cambiar a rama:**
  ```bash
  git checkout <nombre-rama>
  # Crear y cambiar en un paso:
  git checkout -b <nombre-rama>
  ```
- **Listar ramas:**
  ```bash
  git branch
  ```
- **Eliminar rama:**
  ```bash
  git branch -d <nombre-rama> # Eliminación segura
  git branch -D <nombre-rama> # Eliminación forzada
  ```

---

### 6. **Revertir a un commit específico:**
1. **Obtener hash del commit:**
   ```bash
   git log --oneline
   ```
2. **Resetear cambios (peligroso):**
   ```bash
   git reset --hard <hash-commit>
   ```
3. **Revertir sin perder cambios posteriores:**
   ```bash
   git revert <hash-commit>
   ```
```