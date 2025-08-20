# 🌐 MutanTech - Proyecto Web Oficial

Bienvenidos al repositorio de **MutanTech**, empresa de desarrollo de software.  
Este proyecto está construido con **React** y organizado por ramas de features para cada colaborador.  

---

## 🚀 Flujo de trabajo para colaboradores

👉 Importante: **Nadie trabaja en `main` ni en `develop` directamente**.  
Cada colaborador tiene su propia rama (`feature/*`).  

---

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/MutanTech.git
cd MutanTech
```

---

### 2️⃣ Cambiarse a su rama asignada

- **Navbar** → `feature/navbar`  
- **Servicios** → `feature/servicios`  
- **Portafolio** → `feature/portafolio`  
- **Footer** → `feature/footer`  
- **Contacto** → `feature/contacto`  

Ejemplo (si trabajas en Navbar):  

```bash
git checkout feature/navbar
```

⚠️ Si no la tienes local, primero haz:  
```bash
git fetch origin
git checkout feature/navbar
```

---

### 3️⃣ Antes de empezar a trabajar

Siempre actualiza tu rama:  

```bash
git pull origin feature/navbar
```

---

### 4️⃣ Guardar cambios y subirlos

```bash
git add .
git commit -m "Navbar: se agregó menú responsivo"
git push origin feature/navbar
```

---

### 5️⃣ Crear un Pull Request

Cuando termines tu parte:  

1. En GitHub → ve a la pestaña **Pull Requests**.  
2. Haz clic en **New Pull Request**.  
3. Selecciona tu rama (`feature/*`) → `develop`.  
4. Escribe un título claro, ejemplo: `Navbar listo para revisión`.  

---

## ✅ Reglas básicas

- Trabaja **solo en tu rama asignada**.  
- Los **Pull Requests** siempre van hacia `develop`.  
- Usa mensajes de commit claros:  
  - ✔️ `Footer: se agregó redes sociales`  
  - ✔️ `Contacto: formulario validado`  

---

## 📌 Estructura de ramas

- `main` → Producción (estable)  
- `develop` → Integración (testing interno)  
- `feature/navbar` → Navbar  
- `feature/servicios` → Servicios  
- `feature/portafolio` → Portafolio  
- `feature/footer` → Footer  
- `feature/contacto` → Contacto  

---

👨‍💻 Equipo MutanTech  
🚀 *Innovamos para transformar tu mundo digital*
