# proyecto-desarrollo-web
Proyecto de desarrollo web para una evaluacion del cft san agustin, este proyecto junta bootstrap con css, asi que se recomienda aplicar archivo style.css de para que los estilos
hagan efecto.

# Demo
Pagina: [https://cftjohndoe.netlify.app/](https://cftjohndoe.netlify.app/)

Code: https://github.com/itodev-source/proyecto-desarrollo-web

## Navbar
![image](https://user-images.githubusercontent.com/92868937/229210284-75ee4434-a4d1-4c6f-87c2-6c05839b06f2.png)

```html
 <nav class="navbar navbar-expand-md bg-body-tertiary navbar-light">
      <div class="container-fluid">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbar-toggler"
          aria-controls="navbarTogglerDemo01"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbar-toggler">
          <a class="navbar-brand" href="#"
            ><img src="/img/letra-j.png" width="40" alt="logo de la pagina web"
          /></a>
          <ul
            class="navbar-nav d-flex justify-content-center align-items-center"
          >
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#sobre-mi"
                >Sobre mi</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#experiencia">Experiencia</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#proyectos">Proyectos</a>
            </li>
          
            <li class="nav-item">
              <a class="nav-link" href="#articulos">Articulos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
```

## Hero
![image](https://user-images.githubusercontent.com/92868937/229210389-bd5ffd19-4c94-45c6-a2fb-7da0bfbac42a.png)

```html
<section class="hero align-items-stretch">
      <img
        src="img/desarrollador-ejemplo.svg"
        alt="Foto de Jane Doe"
        class="imagen-desarrollador"
      />
      <h1>Hola soy <span class="hero-nombre">John Doe</span></h1>
      <h2>Desarrollador de sitios web y escribir articulos de programacion</h2>
      <div class="hero-inferior">
        <img
          class="hero-inferior-imagen img-fluid"
          src="img/hero-inferior.svg"
          alt="Imagen con contenido HTML, CSS, JavaScript y React"
        />
      </div>
    </section>
```

## Sobre mi
![image](https://user-images.githubusercontent.com/92868937/229210445-bd66f0b7-d7d3-4d3b-a2b0-1f605a3132dd.png)

```html
   <section class="seccion__oscura" id="sobre-mi">
      <div class="container text-center">
        <h3 class="seccion__oscura--titulo">
          Hola mi nombre es <span class="fw-bolder">Jane Doe</span>
        </h3>
        <p class="seccion__oscura--parrafo">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Alias harum
          expedita, quas et distinctio, facilis voluptatibus ipsam aspernatur
          quis, rem unde minima beatae quisquam autem vero! Itaque accusantium
          quo in? Lorem ipsum dolor sit amet consectetur, adipisicing elit. Illo
          earum minus at eaque dolores, rem quibusdam soluta dolorum nostrum sit
          ipsa ab id repellendus molestias odio doloribus itaque facere
          delectus!
        </p>
      </div>
    </section>
```

## Experiencia
![image](https://user-images.githubusercontent.com/92868937/229210558-290459dd-bc40-4701-947c-28e9ff7aa6bf.png)

```html
<section id="experiencia" class="seccion__blanca experiencia">
      <div class="container row text-center">
        <div class="col-12 col-md-4 py-5">
          <div class="card">
            <img
              class="card-img-top img-fluid"
              src="img/desarrollo-web.png"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5
                class="card-title py-2 d-flex align-items-center justify-content-center gap-1"
              >
                <i class="bi bi-file-earmark-code-fill"></i> Desarrollo Web
              </h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>

              <span class="badge badge-primary text-primary">HTML</span>
              <span class="badge badge-primary text-primary">CSS3</span>
              <span class="badge badge-primary text-primary">JavaScript</span>
              <span class="badge badge-primary text-primary">React</span>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4 py-5">
          <div class="card">
            <img
              class="card-img-top img-fluid"
              src="img/articulos.jpg"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5
                class="card-title py-2 d-flex align-items-center justify-content-center gap-1"
              >
                <i class="bi bi-newspaper"></i> Articulos
              </h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <span class="badge badge-primary text-primary">Escritor</span>
              <span class="badge badge-primary text-primary">Publicador</span>
              <span class="badge badge-primary text-primary">Editor</span>
              <span class="badge badge-primary text-primary">Blogs</span>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-4 py-5">
          <div class="card">
            <img
              class="card-img-top img-fluid"
              src="img/estudiantes.jpg"
              alt="Card image cap"
            />
            <div class="card-body">
              <h5
                class="card-title py-2 d-flex align-items-center justify-content-center gap-1"
              >
                <i class="bi bi-people-fill"></i> Estudiantes
              </h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <span class="badge badge-primary text-primary"
                >Desarrollo Web</span
              >
              <span class="badge badge-primary text-primary"
                >Clases Virtuales</span
              >
              <span class="badge badge-primary text-primary">Auditor</span>
            </div>
          </div>
        </div>
      </div>
    </section>
```

##Proyectos
![image](https://user-images.githubusercontent.com/92868937/229210637-de42497c-43b9-4d39-99b2-7c433a383676.png)

```html
<section id="proyectos" class="proyectos__recientes seccion__clara d-flex flex-column">
      <h2 class="proyectos__recientes-titulo">Mis Proyectos recientes</h2>
      <h3 class="proyecto__recientes-parrafo">
        Estos son algunos proyectos que realizado recientesmente
      </h3>

      <!-- Galeria de Proyectos -->
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-6 col-lg-4">
            <div class="proyecto__unico">
              <img
                class="proyecto__unico-imagen img-fluid"
                src="img/proyectos/proyecto1.jpg"
                alt=""
              />
              <div class="proyecto__unico-overlay">
                <p>Proyecto 1</p>
                <div class="proyecto__unico-iconos gap-3">
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-github"></i>
                  </a>
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-browser-chrome"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4">
            <div class="proyecto__unico">
              <img
                class="proyecto__unico-imagen img-fluid"
                src="img/proyectos/proyecto2.jpeg"
                alt=""
              />
              <div class="proyecto__unico-overlay">
                <p>Proyecto 2</p>
                <div class="proyecto__unico-iconos gap-3">
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-github"></i>
                  </a>
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-browser-chrome"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4">
            <div class="proyecto__unico">
              <img
                class="proyecto__unico-imagen img-fluid"
                src="img/proyectos/proyecto3.png"
                alt=""
              />
              <div class="proyecto__unico-overlay">
                <p>Proyecto 3</p>
                <div class="proyecto__unico-iconos gap-3">
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-github"></i>
                  </a>
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-browser-chrome"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4">
            <div class="proyecto__unico">
              <img
                class="proyecto__unico-imagen img-fluid"
                src="img/proyectos/proyecto4.jpeg"
                alt=""
              />
              <div class="proyecto__unico-overlay">
                <p>Proyecto 4</p>
                <div class="proyecto__unico-iconos gap-3">
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-github"></i>
                  </a>
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-browser-chrome"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4">
            <div class="proyecto__unico">
              <img
                class="proyecto__unico-imagen img-fluid"
                src="img/proyectos/proyecto5.jpeg"
                alt=""
              />
              <div class="proyecto__unico-overlay">
                <p>Proyecto 5</p>
                <div class="proyecto__unico-iconos gap-3">
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-github"></i>
                  </a>
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-browser-chrome"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-4">
            <div class="proyecto__unico">
              <img
                class="proyecto__unico-imagen img-fluid"
                src="img/proyectos/proyecto6.jpeg"
                alt=""
              />
              <div class="proyecto__unico-overlay">
                <p>Proyecto 6</p>
                <div class="proyecto__unico-iconos gap-3">
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-github"></i>
                  </a>
                  <a href="#" target="_blank" rel="noopener noreferrer">
                    <i class="bi bi-browser-chrome"></i>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <button type="button" class="btn btn-primary">
        Ver mas proyectos <i class="bi bi-arrow-bar-right ms-1"></i>
      </button>
    </section>
```

## Articulos
![image](https://user-images.githubusercontent.com/92868937/229210714-616b3c06-3f20-4cf5-93b6-263889d52270.png)

```html
 <section id="articulos" class="articulos seccion__oscura justify-content-start">
      <h2>Articulos</h2>
      <div class="card articulos-card">
        <div class="card-header">Mas recientes</div>
        <ul class="list-group list-group-flush">
          <li class="list-group-item">
            <a href=""
              >Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet,
              beatae? Aut laborum magni reprehenderit. Reprehenderit eaque culpa
              eum quidem quam.</a
            >
          </li>
          <li class="list-group-item"><a href="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet,
            beatae? Aut laborum magni reprehenderit. Reprehenderit eaque culpa
            eum quidem quam.</a></li>
          <li class="list-group-item"><a href="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet,
            beatae? Aut laborum magni reprehenderit. Reprehenderit eaque culpa
            eum quidem quam.</a></li>
        </ul>
      </div>
    </section>
```

## Footer
![image](https://user-images.githubusercontent.com/92868937/229210774-88c7008a-e6eb-4c63-9211-cea19fe3449e.png)

```html
 <footer class="bg-light text-center text-lg-start">
      <!-- Copyright -->
      <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
        © 2020 Copyright:
        <a class="text-dark" href="https://mdbootstrap.com/">John Doe</a>
      </div>
      <!-- Copyright -->
    </footer>
```
