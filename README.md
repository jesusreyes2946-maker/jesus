
st.set_page_config(
    page_title="Mi Página Personal mia de mi",
    layout="centered"
)

# --- ENCABEZADO ---
st.title("¡Hola soy jesus xd")
st.subtitle("Estudiante / Apasionado por la Tecnología y la Programación")

st.write("---")

# --- SOBRE MÍ ---
st.header("📌 Sobre mí")
st.write(
    """
    Bienvenido a mi sitio web personal. Me interesa la programación, la resolución de 
    problemas matemáticos y el desarrollo de proyectos tecnológicos.
    """
)

# --- HABILIDADES ---
st.header("jugar minecraft)
col1, col2 = st.columns(2)

with col1:
    st.markdown("- **Áreas:** Lógica, Algoritmos, Matemáticas")

with col2:
    st.markdown("- **Entornos:** Windows, IDLE, VS Code")
    st.markdown("- **Herramientas:** Git, Streamlit")

st.write("---")

# --- PROYECTOS ---
st.header("terminar el tec")

# --- CONTACTO Y REDES ---
st.header("soy lonewolf en insta")
st.write("¿Quieres ponerte en contacto conmigo o revisar mi trabajo?")

st.markdown("[🐙 GitHub](https://github.com)")
st.markdown("[💼 LinkedIn](https://linkedin.com)")
