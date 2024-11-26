## Escenario web con cliente

Neste escenario, podemos escoller os nomes que queiramos para o servidor web, sendo sempre resoltos desde o cliente

Podemos lanzar un navegador web no cliente, neste caso firefox con

docker compose exec cliente firefox-esr

Este navegador executase dentro do cliente, e será capaz de acceder a http://www.proba.lan/

Lembrarse sempre de poñer a barra ao final para evitar a búsqueda no google

w

    Configura dosus sitios virtuais (server1.lan e server2.lan). Cada un co seu DocumentRoot en dous cartafois diferentes (montados coma volumes colgando de /web

    Tomando un dos dous servidores virtuais, varía o DirectoryIndex (a nivel do directorio do DocumentRoot), para que teña valores, como a.html, b.html e c.html. Crea varios cartafoles dentro dese, e varia o nome dos ficheiros que alí existe.

    Monta outro directorio con volumes en /srv, e fai que esté accesible mediante unha ruta dentro do espazo web.

    No directorio fotos do DocumentRoot, so queremos que se poidan e visualizar fotos (escolle 6 tipos de arquivo). O resto de extensións denegaranse.

    No directorio privado, amosarás un listado dos ficheiros que ali existan. Os ficheiros .php, non deberán aparecer no listado

    Fai o mesmo que todo o anteiros, no server2.lan pero empregando ficheiros .htaccess

    Configura as páxinas de erros personalizados.

    Permite que a ruta /interno so se lle permita acceder a un determinado equipo.

    Configura un sitio virtual como calquera dos anteriores, pero empregando HTTPS.
