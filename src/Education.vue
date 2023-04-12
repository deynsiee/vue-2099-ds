<template>
  <div id="education">
    <div id="todo-card">
      <div class="container">
        <div class="alert alert-primary" role="alert">
          <h1>{{ msgeduc }}</h1>
          <center>
            <table>
              <tr>
                <th>Elementary:</th>
                <th>2009 - 2015 Saint Catherine Academy : CCE Porac</th>
              </tr>

              <tr>
                <th>Junior High School:</th>
                <th>2015 - 2018 Saint Catherine Academy : CCE Porac</th>
              </tr>

              <tr>
                <th>Senior High School:</th>
                <th>2018 - 2021 Saint Catherine Academy : CCE Porac</th>
              </tr>

              <tr>
                <th>College:</th>
                <th>2021 - 2025 Holy Angel University</th>
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
  name: 'education',
  data() {
    return {
      msgeduc: 'This is the Education Component',
    };
  },
};
</script>
