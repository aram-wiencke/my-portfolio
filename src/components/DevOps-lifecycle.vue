<template>
  <div>
    <h1>DevOps Lifecycle</h1>
    <div class="lifecycle">
      <div class="phase">
        <h2>Plan</h2>
        <p>Define goals, requirements, and strategies for the project.</p>
      </div>
      <div class="phase">
        <h2>Code</h2>
        <p>Write, test, and debug the code for the application.</p>
      </div>
      <div class="phase">
        <h2>Build</h2>
        <p>Compile and package the code into deployable artifacts.</p>
      </div>
      <div class="phase">
        <h2>Test</h2>
        <p>Verify the functionality and quality of the application using automated and manual tests.</p>
      </div>
      <div class="phase">
        <h2>Release</h2>
        <p>Deploy the application to production or staging environments for users to access.</p>
      </div>
      <div class="phase">
        <h2>Configure</h2>
        <p>Manage and monitor the application and infrastructure in the production environment.</p>
      </div>
      <div class="phase">
        <h2>Monitor</h2>
        <p>Collect and analyze data to evaluate the performance and availability of the application.</p>
      </div>
    </div>
  </div>
</template>

<style>
.lifecycle {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 20px 0;
}

.phase {
  width: 20%;
  text-align: center;
}
</style>