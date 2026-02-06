# SentiLab - Análisis de Sentimientos

![SentiLab](https://img.shields.io/badge/SentiLab-Análisis%20de%20Sentimientos-blue)
![Python](https://img.shields.io/badge/Python-3.8+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🌐 Demo en Vivo

Accede a la aplicación en: **[https://sentilab.mltstudios.dev/](https://sentilab.mltstudios.dev/)**

## 📋 Descripción

SentiLab es una aplicación web de análisis de sentimientos diseñada específicamente para procesar reseñas en español. Utiliza técnicas de procesamiento de lenguaje natural (NLP) para clasificar automáticamente las reseñas como positivas o negativas, proporcionando insights valiosos sobre la percepción del usuario.

## ✨ Características

- **Análisis Individual**: Analiza reseñas de texto ingresadas manualmente
- **Análisis por Lotes**: Carga archivos JSON con múltiples reseñas para análisis masivo
- **Dashboard Estadístico**: Visualiza el resumen general de sentimientos
  - Total de reseñas analizadas
  - Cantidad de reseñas positivas
  - Cantidad de reseñas negativas
- **Análisis Detallado**: Revisa el resultado individual de cada reseña procesada
- **Interfaz Intuitiva**: Diseño limpio y fácil de usar
- **Procesamiento en Español**: Optimizado para el idioma español

## 🛠️ Tecnologías Utilizadas

### Backend
- Python
- Framework de procesamiento de lenguaje natural
- API REST para el análisis de sentimientos

### Frontend
- HTML5
- CSS3
- JavaScript

### Deployment
- GitHub Actions (CI/CD)
- Servidor de producción en mltstudios.dev

## 📁 Estructura del Proyecto

```
Sentiment-Analysis-Deploy/
│
├── .github/
│   └── workflows/          # Configuración de CI/CD
│
├── backend/                # API y lógica de análisis
│   └── ...
│
├── frontend/               # Interfaz de usuario
│   └── ...
│
├── requirements.txt        # Dependencias de Python
├── .gitignore
└── .gitattributes
```

## 🚀 Instalación Local

### Prerrequisitos

- Python 3.8 o superior
- pip (gestor de paquetes de Python)

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/Solaquin/Sentiment-Analysis-Deploy.git
   cd Sentiment-Analysis-Deploy
   ```

2. **Instalar dependencias de Python**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configurar el backend**
   ```bash
   cd backend
   # Sigue las instrucciones específicas del backend
   ```

4. **Configurar el frontend**
   ```bash
   cd frontend
   # Abre index.html en un navegador o usa un servidor local
   ```

## 💻 Uso

### Análisis Individual

1. Ingresa tu reseña en el campo de texto
2. Haz clic en "Analizar Sentimiento"
3. Visualiza el resultado de la clasificación

### Análisis por Lotes

1. Prepara un archivo JSON con el siguiente formato:
   ```json
   {
     "reviews": [
       "Esta es una excelente reseña",
       "No me gustó para nada el producto",
       "Cumple con lo esperado"
     ]
   }
   ```

2. Haz clic en el botón "Subir .json"
3. Selecciona tu archivo
4. Revisa el resumen general y los resultados individuales

## 📊 Formato de Datos

El archivo JSON para análisis por lotes debe seguir esta estructura:

```json
{
  "reviews": [
    "Primera reseña en español",
    "Segunda reseña en español",
    "Tercera reseña en español"
  ]
}
```

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👥 Autores

Desarrollado por:
- **Simón Porras**
- **Angel Tovar**
- **Juan Fique**

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🔗 Enlaces

- **Aplicación en Producción**: [https://sentilab.mltstudios.dev/](https://sentilab.mltstudios.dev/)
- **Repositorio Entrenamiento**: [https://github.com/Solaquin/Sentiment-Analysis-LSTM](https://github.com/Solaquin/Sentiment-Analysis-LSTM)

## 📞 Contacto

Para preguntas, sugerencias o reportes de bugs, por favor abre un [issue](https://github.com/Solaquin/Sentiment-Analysis-Deploy/issues) en el repositorio.

---

⭐ Si este proyecto te resulta útil, considera darle una estrella en GitHub!
