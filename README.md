# 📦 Distribution
Distributions for Minecraft Servers

---

## 🚀 Clonar e instalar dependencias

```bash
git clone https://github.com/MRYISUSX/distribution.git
cd DinosaurLauncher
npm install
```

---

## ▶️ Ejecutar la aplicación

```bash
npm start
```

---

## 🛠️ Construir instaladores

### 🖥️ Build para tu plataforma actual

```bash
npm run dist
```

### 🧩 Build para una plataforma específica

| Plataforma    | Comando            |
|---------------|--------------------|
| Windows x64   | `npm run dist:win` |
| macOS         | `npm run dist:mac` |
| Linux x64     | `npm run dist:linux` |

⚠️ **Importante:**  
Los builds para macOS pueden no funcionar en Windows/Linux y vice-versa.

---

## 📄 Notas

- Asegúrate de tener Node.js y npm instalados (recomendado Node 16+).  
- Si usas GitHub Actions u otro CI para builds, revisa la configuración de electron-builder (u otra herramienta que uses) para compatibilidad entre plataformas.  
- Si quieres agregar un icono, resourcepack o configuración predefinida para el launcher, agrégala en la carpeta correspondiente del repositorio y actualiza los scripts de build si es necesario.

---
