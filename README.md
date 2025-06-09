# Maa-janki-library
For making website 
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Poppins', sans-serif;
  color: white;
  background-color: #0f172a;
}

nav {
  background: rgba(31, 41, 55, 0.95);
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 999;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #444;
}

nav h1 {
  color: #ef4444;
  font-size: 1.5rem;
  font-weight: 800;
  display: flex;
  align-items: center;
  gap: 10px;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 2rem;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav ul li a:hover {
  color: #ef4444;
}

.hero {
  background: url('https://images.unsplash.com/photo-1462331940025-496dfbfc7564?auto=format&fit=crop&w=1470&q=80') no-repeat center center/cover;
  position: relative;
  padding: 8rem 2rem 6rem;
  text-align: center;
}

.hero::before {
  content: "";
  position: absolute;
  inset: 0;
  background-color: rgba(0, 0, 0, 0.6);
  z-index: 0;
}

.hero-content {
  position: relative;
  z-index: 1;
  max-width: 900px;
  margin: auto;
}

.hero h1 {
  font-size: 3rem;
  font-weight: 800;
  margin-bottom: 1rem;
}

.hero p {
  font-size: 1.2rem;
  color: #ccc;
  margin-bottom: 1rem;
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  margin-top: 3rem;
}

.card {
  background: rgba(255, 255, 255, 0.1);
  border: 1px solid rgba(255, 255, 255, 0.2);
  padding: 1.5rem;
  border-radius: 1rem;
  text-align: center;
  backdrop-filter: blur(8px);
}

.card i {
  font-size: 2.5rem;
  color: #ef4444;
  margin-bottom: 1rem;
}

.buttons {
  margin-top: 2rem;
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.buttons button {
  padding: 0.75rem 1.5rem;
  border: none;
  border-radius: 8px;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}

.btn-primary {
  background-color: #ef4444;
  color: white;
}

.btn-primary:hover {
  background-color: #dc2626;
}

.btn-outline {
  background-color: transparent;
  border: 2px solid white;
  color: white;
}

.btn-outline:hover {
  background-color: white;
  color: black;
}

@media (max-width: 768px) {
  nav ul {
    display: none;
  }
}
