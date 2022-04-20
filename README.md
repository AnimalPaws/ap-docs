# Contenido #

- [Animal Paws](#animal-paws)
  - [Idea principal](#idea-principal)
  - [Métricas de desarrollo](#métricas-de-desarrollo)
  - [Equipo de desarrollo](#equipo-de-desarrollo)
  - [Documentación relevante](#documentación-relevante)

# Animal Paws #

**Animal Paws** es una plataforma que brinda un medio por el cual se facilite la comunicación entre las fundaciones y los contribuyentes, que haya un constante flujo de información respecto a temas relaciones con los animales y que se cree un intermediario entre los donantes y las organizaciones para la entrega de los bienes y el uso correcto de estos.

## Idea principal ##

La idea principal de **Animal Paws** se centra en conectar a las personas a una comunidad dedicada a la ayuda y cuidado animal, dónde el usuario podrá seleccionar un rol en la aplicación (usuario o entidad). Si quien ingresa, es una entidad, podrá tener mayor acceso a la parte de adopción desde la perspectiva de montar todas sus mascotas que tiene bajo cuidado junto a la opción de potenciar anuncios y poder acceder a las preferencias de los usuarios para ofrecerles un servicio más personalizado. La opción de donar y adoptar es para el usuario, aquí se contarán con contactos de quienes necesitan cubrir alguna necesidad para las mascotas que tiene, con las respectivas cosas que necesitan(Comida, medicamentos o alguna cirugía) y tendrán acceso a los anuncios, donde podrán publicar y visualizar aquellos que estén disponibles en el sistema.

## Métricas de desarrollo ##

Las métricas de desarrollo expresan a nivel de código las reglas semánticas que los desarrolladores deben seguir para gestionar adecuadamente los estándares de calidad y las buenas prácticas a la hora de codificación.

Se declararán las métricas las cuales estarán sujetas a ciertas reglas y estándares de códigos para el desarrollo de **Animal Paws**.

1. A nivel de código

   1.1 Todas las lineas de código tienen que estar escritas en inglés (clases, métodos, variables, etc) a excepción de los comentarios.
   1.2 Las clases deberán ser **sustantivos** y escritas con la notación Pascal. Eg:

      ```c#
         class User #Es sustantivo.
         class P̲rofileS̲ettings #Notación Pascal.
      ```

   1.3 Los métodos deberán representar **verbos** y ser escritas igualmente con la notación Pascal. Eg:

      ```c#
         Public void Search() #Es verbo.
         Private void S̲ystemN̲otification #Notación Pascal.
      ```

   1.4 Las propiedades públicas deberán ser escritas con la notación Pascal y las propiedades privadas con la notación Snake. Eg:
   ```c#
      Public string Name { get; set; } #Propiedad pública, notación Pascal
      Private char _id { get; set; } #Propiedad privada, notación Snake
   ```

   1.5 Las variables y los argumentos deberán ser escritas con la notación Camel. Eg:
   ```c#
      String phoneNumber = _phoneNumber #
      Private static void Verify(string id)
   ```

2. Flujo de trabajo (git)

   2.1 Cada miembro del equipo de desarrollo debe crear su rama con la siguiente notación:

      ```
         develop-<developer-name>
         git branch develop-Cristian
      ```

   2.2 Al realizar los commits se debe indicar en el mensaje, quién lo hizo, qué acción se realizó y que fue lo que hizo a nivel de código.
   Las acciones que se usarán son las siguientes:
   **Add - Fix - Change - Remove**
   Por ejemplo:

      ```
         # Primero se escribe las iniciales del desarrollador, luego separado
         #por un guión, la acción que se realizó y por último qué es lo que hizo.
         git commit -m "CA - Add chat system between users" 
      ```

## Equipo de desarrollo ##

El equipo de desarrollo representa los miembros responsables de realizar el proyecto **Animal Paws** son los siguientes:

1. [Angie Juliana Lugo](https://github.com/anonimo223)
2. [Angie Daniela Tapiero](https://github.com/angie932)
3. Jorge Iván Pito
4. [Julian Andrés Lozada](https://github.com/Ex1Kx)
5. [Cristian Andrés Penagos](https://github.com/SandGuru)
6. [Juan Camilo Cruz](https://github.com/camilocruz07)

## Documentación relevante ##

- (...)
