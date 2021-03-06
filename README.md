![bandera-en-pie](https://user-images.githubusercontent.com/385670/30645087-3ddb7eb6-9dda-11e7-8ecd-17424b852299.jpg)

# TerremotoMX

En septiembre 2017 sismos afectaron a diferentes partes de México.

* [Septiembre 7, 2017](https://es.wikipedia.org/wiki/Terremoto_del_sureste_de_M%C3%A9xico_de_2017) con epicentro en Chiapas.
* [Septiembre 19, 2017](https://es.wikipedia.org/wiki/Terremoto_de_Puebla_de_2017) con epicentro en Puebla.

Hasta ahora los estados con más afectaciones reportadas han sido Oaxaca,
Chiapas, Ciudad de México, Tlaxcala, Puebla, Guerrero, Morelos y Michoacán.

## Sobre este repositorio

El repositorio contiene un sitio creado a partir del sismo de Septiembre 19
2017, fue creado inicialmente para concentrar los diferentes esfuerzos de apoyo
tras el siniestro y proveer información rápidamente a quienes puedan
necesitarla.

Este proyecto podría ser usado como base para organizar una pronta respuesta en
caso de desastres posteriores.

## ¿Cómo Ayudar?

La conversación y coordinación de las tareas las estamos llevando en el Slack de Codeando México, dentro del canal de `#equipo-humanitario`. Para unirte a Slack, registrate en http://slack.codeandomexico.org.

Una vez en Slack, puedes:

* Unirte a un grupo de trabajo.
* Agregar un issue en este repositorio con la etiqueta adecuada.

## Grupos de trabajo

| Equipo | Slack | Descripción |
| :--- | :--- | :--- |
| [Comunicación](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Acomunicacion%20) | `#sismomx-comunicación` | Tareas de comunicación, monitoreo de redes y vinculación con otras organizaciones. |
| [Data](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Adata%20) | `#sismomx-data` | Tareas de limpieza, validación, análisis y ETL de datos. |
| [Desarrollo](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3desarrollo%20) | `#sismomx-desarrollo` | Tareas de desarrollo para todos los proyectos. Súmate si buscas ayuda o cómo contribuir. |
| [Diseño](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Adise%C3%B1o%20) | `#sismomx-diseño` | Tareas de diseño de UI/UX para múltiples proyectos. Ofrece y busca ayuda de diseño para proyectos. |
| [Docs](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Adocs%20) | `#sismomx-docs` | Tareas de documentación de procesos y repositorios.  |
| [GitHub](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Agithub%20) | `#sismomx-github` | Ayúdanos a revisar y hacer merge de PR's en los distintos repositorios. |
| [Mapas](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Amapas%20) | `#sismomx-mapas` | Tareas de mapeo y trabajo con datos geográficos. |
| [Webiste](https://github.com/CodeandoMexico/terremoto-cdmx/issues?utf8=%E2%9C%93&q=is%3Aissue%20label%3Awebsite%20) | `#sismomx-website` | Ayúdanos a actualizar el sitio web del proyecto. |


### Como correr este repositorio en local

Para correr el proyecto en local necesitas
[Ruby](https://www.ruby-lang.org/es/) mayor de 1.9 y
[RubyGems](https://rubygems.org/pages/download/).


##### Instrucciones para Linux y OSX

```
$ gem install bundler
$ bundle install
$ jekyll serve
```

El sistema estará disponible en http://127.0.0.1:4000/


#### Centros de Acopio <a name="centrosacopio"></a>

API para conectarse a la base de datos de centros de acopio se esta desarrollando en un [repositorio de github](https://github.com/Skycatch/acopio-api) y coordinando en el canal de Slack `#equipo-humanitario`.


#### App de priorización de necesidad para vincular con centros de acopio <a name="prioritizacion"></a>

App para buscar lugares donde se esta pidiendo ayuda se esta desarrollando en un [repositorio de github](https://github.com/civica-digital/quake-relief-cdmx) y coordinando en el canal de Slack `#equipo-humanitario`.

#### App de SMS <a name="appsms"></a>

App para [utilización de SMS](https://sismomx-sms.herokuapp.com/) y coordinando en el canal de Slack `#equipo-humanitario`.

#### Obtención de información a partir de Twitter <a name="twitterinfo"></a>

Filtra información valiosa relacionada al terremoto. Se esta desarrollando en un [repositorio de github](https://github.com/Garyi/Filtro-Informaci-n-Valiosa-Terremoto-Twitter) y coordinando en el canal de Slack `#equipo-humanitario`.

#### Script de python para encontrar a personas desaparecidas]<a name="desaparecidas"></a>

Bot que busca información sobre personas desaparecidas durante el sismo. Se esta desarrollando en un [repositorio de github](https://github.com/regenhans/earthquake-bot)  y coordinando en el canal de Slack `#equipo-humanitario`.

## Otros proyectos desarrollandose

* [Ban FakeNews](https://github.com/RZEROSTERN/banfakenews) en PHP, Yii
* [API para centros de acopio](https://github.com/Skycatch/acopio-api) en JS, Hapi
* [Repositorio de información para ayudar en desastres naturales](https://github.com/eldelentes/comoayudarmx) en HTML, JS y CSS plano
* [Backend de comoayudar.mx](https://github.com/ComoAyudarMX/CAMbackend) en JS, express
* [Encontrar las necesidades más prioritarias por zona para enviar ayuda y notificar](https://github.com/civica-digital/quake-relief-cdmx/commits/master) en Ruby on Rails 5.0
* [SMS Alerts para sismo en Mexico](https://github.com/denialtorres/SMS-ALERTS) en Ruby on Rails 4.2
* [Herramienta para el reporte ciudadano](https://github.com/leodc/mapeo_colaborativo) en JS, express, socket.io
* [Bot que filtra información valiosa de Twitter relacionada al terremoto](https://github.com/Garyi/Filtro-Informaci-n-Valiosa-Terremoto-Twitter) en Python
* [Respuesta rápida ante el terremoto CDMX](https://github.com/erikcaffrey/AyudaMexico) en Java
* [Bot inteligente en twitter responde a busquedas de personas](https://github.com/carlosherrera/cdmxbot) en JS, api twitter 

## Licencia

MIT

> Se concede permiso, de forma gratuita, a cualquier persona que obtenga una
> copia de este software y de los archivos de documentación asociados (el
> "Software"), para utilizar el Software sin restricción, incluyendo sin
> limitación los derechos a usar, copiar, modificar, fusionar, publicar,
> distribuir, sublicenciar, y/o vender copias del Software, y a permitir a las
> personas a las que se les proporcione el Software a hacer lo mismo, sujeto a
> las siguientes condiciones:
>
> El aviso de copyright anterior y este aviso de permiso se incluirán en todas
> las copias o partes sustanciales del Software.
>
> EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O
> IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A GARANTÍAS DE COMERCIALIZACIÓN,
> IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS
> AUTORES O TITULARES DEL COPYRIGHT SERÁN RESPONSABLES DE NINGUNA RECLAMACIÓN,
> DAÑOS U OTRAS RESPONSABILIDADES, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O
> CUALQUIER OTRO MOTIVO, QUE SURJA DE O EN CONEXIÓN CON EL SOFTWARE O EL USO U
> OTRO TIPO DE ACCIONES EN EL SOFTWARE.
