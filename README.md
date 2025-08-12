body {
  margin: 0;
  font-family: 'Segoe UI', Arial, sans-serif;
  color: #222;
  background: #f8f9fa;
}
header {
  background: #0055a5;
  color: #fff;
  padding: 1rem 0;
}
.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
}
nav {
  float: right;
}
nav a {
  color: #fff;
  margin-left: 1.5rem;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.2s;
}
nav a:hover {
  color: #ffd700;
}
.hero {
  background: linear-gradient(90deg, #0055a5 65%, #ffd700 100%);
  color: #fff;
  padding: 3rem 0 2rem 0;
  text-align: center;
}
.hero .btn {
  background: #ffd700;
  color: #0055a5;
  padding: 0.8rem 2rem;
  border: none;
  border-radius: 25px;
  font-size: 1.1rem;
  cursor: pointer;
  font-weight: bold;
  text-decoration: none;
  transition: background 0.2s;
}
.hero .btn:hover {
  background: #fff56a;
}
.servicios {
  padding: 2rem 0;
  background: #fff;
}
.servicios-lista {
  display: flex;
  gap: 1.5rem;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 2rem;
}
.servicio {
  background: #f0f3fb;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0,85,165,0.05);
  padding: 1.5rem;
  width: 270px;
  text-align: center;
}
.servicio h3 {
  color: #0055a5;
}
.contacto {
  padding: 2rem 0;
  background: #f8f9fa;
}
.contacto a {
  color: #0055a5;
  text-decoration: underline;
}
form {
  margin-top: 1rem;
  display: flex;
  flex-direction: column;
  gap: 1rem;
  max-width: 400px;
}
input, textarea {
  padding: 0.7rem;
  border-radius: 5px;
  border: 1px solid #ccc;
  font-size: 1rem;
}
button[type="submit"] {
  background: #0055a5;
  color: #fff;
  border: none;
  border-radius: 25px;
  padding: 0.7rem;
  font-size: 1.1rem;
  font-weight: bold;
  cursor: pointer;
  transition: background 0.2s;
}
button[type="submit"]:hover {
  background: #003c73;
}
footer {
  background: #222;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
  margin-top: 2rem;
}
@media (max-width: 800px) {
  .servicios-lista {
    flex-direction: column;
    align-items: center;
  }
  nav {
    float: none;
    text-align: center;
    margin-top: 0.5rem;
  }
}
