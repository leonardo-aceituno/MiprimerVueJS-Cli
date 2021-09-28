<template>
  <table class="table">
    <thead>
      <tr>
        <th scope="col">#</th>
        <th scope="col">Nombre</th>
        <th scope="col">Apellido</th>
        <th scope="col">RUN</th>
        <th scope="col">Nacimiento</th>
        <th scope="col">Edad</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th scope="row">1</th>
          <td>{{usuarios[0].nombre}}</td>
          <td>{{usuarios[0].apellido}}</td>
          <td>{{usuarios[0].rut}}</td>
          <td>{{usuarios[0].nacimiento}}</td>
          <td>{{usuarios[0].edad}}</td>
        </tr>
      <tr>
      
      <th scope="row">2</th>
        <td>{{usuarios[1].nombre}}</td>
        <td>{{usuarios[1].apellido}}</td>
        <td>{{usuarios[1].rut}}</td>
        <td>{{usuarios[1].nacimiento}}</td>
        <td>{{usuarios[1].edad}}</td>
      </tr>

      <tr>
        <th scope="row">3</th>
        <td>{{usuarios[2].nombre}}</td>
        <td>{{usuarios[2].apellido}}</td>
        <td>{{usuarios[2].rut}}</td>
        <td>{{usuarios[2].nacimiento}}</td>
        <td>{{usuarios[2].edad}}</td>
      </tr>
    </tbody>
  </table>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  data(){
    return {
       usuarios:[
            {
                nombre:'Jose',
                apellido: 'Perez',
                rut: 123456-2,
                nacimiento: '12-04-67',
                edad: 52
            },
            {
                nombre:'Maria Rodriguez',
                apellido: 'Rodriguez',
                rut: 654321-1,
                nacimiento: '30-01-90',
                edad: 29
            },
            {
                nombre:'Manuel',
                apellido: 'Patiño',
                rut: 654321-177,
                nacimiento: '300-01-90',
                edad: 298
            }
        ]
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
