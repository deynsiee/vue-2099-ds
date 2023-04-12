<template>
  <div id="profile">
    <div id="todo-card">
      <div class="container">
        <div class="alert alert-primary" role="alert">
          <h1>{{ msgprofile }}</h1>
          <center>
            <table>
              <tr>
                <th>Name:</th>
                <th>Salalila, Dayna Micaela M.</th>
              </tr>

              <tr>
                <th>Address:</th>
                <th>48 General Luna Street, Babo Sacan, Porac, Pampanga</th>
              </tr>

              <tr>
                <th>Birthday:</th>
                <th>December 26, 2002</th>
              </tr>

              <tr>
                <th>Email:</th>
                <th>dmsalalila@student.hau.edu.ph</th>
              </tr>

              <tr>
                <th>Phone:</th>
                <th>(045) 649 - 5255</th>
              </tr>
            </table>
          </center>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'profile',
  data() {
    return {
      msgprofile: 'This is the Profile Component',
    };
  },
};
</script>
