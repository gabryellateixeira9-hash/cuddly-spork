/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* CORPO */
body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: linear-gradient(135deg, #f5f5f5, #e0e0e0);
    color: #333;
}

/* HEADER */
header {
    background: #e91e63;
    color: white;
    text-align: center;
    padding: 30px 20px;
}

header h1 {
    font-size: 2rem;
    margin-bottom: 5px;
}

/* MAIN */
main {
    max-width: 900px;
    margin: 30px auto;
    padding: 0 15px;
}

/* CARDS */
.card {
    background: white;
    padding: 20px;
    margin-bottom: 20px;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

/* TITULOS */
h2 {
    color: #e91e63;
    margin-bottom: 10px;
}

/* LISTA */
ul {
    padding-left: 20px;
}

/* FOOTER */
footer {
    text-align: center;
    padding: 20px;
    background: #222;
    color: white;
    margin-top: 30px;
}
