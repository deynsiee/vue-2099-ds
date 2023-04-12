<template>
  <div id="skills">
    <div id="todo-card">
      <div class="container">
        <div class="alert alert-primary" role="alert">
          <h1>{{ msgskills }}</h1>
          <center>
            <table>
              <tr>
                <th>Skills</th>
              </tr>

              <tr>
                <th>Python</th>
              </tr>

              <tr>
                <th>Java</th>
              </tr>

              <tr>
                <th>Database and SQL</th>
              </tr>

              <tr>
                <th>HTML and CSS</th>
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
  name: 'skills',
  data() {
    return {
      msgskills: 'This is the Skills Component',
    };
  },
};
</script>
