<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1 align="center">Microservicio App</h1>
    <p align="center">Primer proyecto implementado arquitectura de microservicios, logrando validar lo aprendido de manera autodidactica.</p>
    <h2>Índice</h2>
    <ul>
        <li><a href="#descripcion">Descripción</a></li>
        <li><a href="#caracteristicas">Características</a></li>
        <li><a href="#Tecnologias">Uso</a></li>
        <li><a href="#contacto">Contacto</a></li>
    </ul>
    <h2 id="descripcion">Descripción</h2>
    <p>Se aplico la arquitetura de microservicios para simular el ambiente de consulta de un colegio, en donde los servicios desarrollados son estudiantes y curso que interactuan entre si
        para dar respuestas a las solicitudes de consulta.
        Los servicios se comunican de manera sincronica por el metodo RestFull, cada servicio es una ApiRest. 
        Para la interaccion del usuario con nuestros ecosistema de microservicios se creo un microservicio GateWay que es el punto de acceso para solicitudes.
        Para la gestion de instancias de los microservicios se aplico Eureka.
        Para la configuracion centralizada de los microservicios se uso Spring Cloud Config. 
    </p>
    <h2 id="caracteristicas">Características</h2>
    <ul>
        <li>CRUD de entidades estudiantes y alumnos</li>
        <li>Solicitud de Consultas</li>
    </ul>
    <h2 id="Tecnologias">Tecnologias</h2>
    <ul>
        <li>SprigBoot</li>
        <li>Mysql - Student</li>
        <li>PostgreSql - Course</li>
        <li>Eukera</li>
        <li>REST - comunicacion</li>
        <li>Spring Cloud Config</li>
        <li>Spring Boot actuator</li>
    </ul>
    <h2 id="contacto">Contacto</h2>
    <p>Para cualquier consulta, contáctame en:</p>
    <ul>
        <li>LinkedIn: <a href="https://www.linkedin.com/in/diego-federico-narvaez/">linkedin.com/in/usuario</a></li>
        <li>GitHub: <a href="https://github.com/DiegoNirva">github.com/usuario</a></li>
    </ul>
</body>
</html>
