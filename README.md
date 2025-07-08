# Node + TypeScript - Basic Starter


Este repositorio es una plantilla mínima en TypeScript para realizar pruebas rápidas, escribir scripts pequeños o experimentar con el lenguaje.

## 🛠️ Tecnologías

- [TypeScript](https://www.typescriptlang.org/)
- [TSX](https://github.com/esbuild-kit/tsx) (para ejecutar archivos `.ts` sin compilarlos manualmente)

---

## 🔧 Requisitos:
1. Asegurate de que el directorio donde ejecutás esto ya existe y esté vacío.
2. Ejecutá el comando desde esa carpeta ya creada.

---

## 🚀 Cómo usar esta plantilla

### 1. Clonar el repositorio
```bash
git clone https://github.com/ValentinZoia/plantilla-simple-ts.git .

```
> 🟡 ¡Importante! El punto final (.) significa "clonar el contenido del repositorio en el directorio actual".

### 2. Eliminar historial Git Muy Importante
```bash
rm -rf .git && git init

```
> 🟡  Importante: Si estás usando esta plantilla como base para un nuevo proyecto, eliminá el historial de Git con ese comando.

### 3. Instalar dependencias
```bash
npm install
```

### 4. Ejecutar archivo principal
```bash
npx tsx src/app.ts
```

### 💡Sugerencias de uso
- Usá este proyecto como entorno para probar funciones, algoritmos o conceptos de TypeScript sin tener que configurar un proyecto grande.
- Si querés ejecutar múltiples archivos, simplemente agregalos dentro del directorio src/ y ejecutalos con npx tsx.
