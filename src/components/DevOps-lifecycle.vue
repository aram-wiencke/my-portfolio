<template>
  <div class="infinity-container">
    <div class="infinity-loop">
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
.infinity-container {
  display: flex;
  justify-content: center;
}

.infinity-loop {
  width: 80%;
  height: 80%;
  border: 1px solid black;
  border-radius: 50%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
}

.phase {
  width: 100%;
  text-align: center;
}
</style>
