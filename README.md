# Pokedex Vue

Este código es una página web que funciona como una Pokédex utilizando Vue.js y la PokeAPI. Aquí tienes una explicación breve de las partes principales:

- **HTML y CSS**: Define la estructura y el estilo de la página web, utilizando Bootstrap para el diseño responsivo y algunos estilos personalizados.

- **Vue.js**: Es un marco de JavaScript utilizado para crear interfaces de usuario de una sola página. En este código, Vue.js se utiliza para la manipulación de datos y la interactividad de la página.

- **PokeAPI**: Se utiliza para obtener datos de Pokémon, como sus nombres, imágenes, tipos y movimientos.

- **Funciones Vue.js**:
  - `data`: Define los datos utilizados en la aplicación, como la lista de Pokémon, el estado de visualización de los detalles de un Pokémon, el Pokémon seleccionado, la búsqueda actual, la lista de todos los Pokémon y los Pokémon sugeridos.
  - `methods`: Contiene funciones para obtener datos de Pokémon, ver detalles de un Pokémon, obtener todos los Pokémon y limpiar la lista de Pokémon sugeridos.
  - `watch`: Observa cambios en la búsqueda actual y filtra la lista de Pokémon sugeridos según lo ingresado en el campo de búsqueda.
  - `mounted`: Se ejecuta cuando la instancia Vue se monta en el DOM, utilizada para llamar a las funciones para obtener datos de Pokémon al cargar la página.

- **Interacción HTML-Vue**: Las partes de la interfaz de usuario (HTML) están conectadas con los datos y métodos de Vue.js a través de directivas como `v-model`, `v-if`, `v-for`, y eventos como `@click`.
