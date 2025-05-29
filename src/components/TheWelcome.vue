<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
</script>

<template>
  <WelcomeItem>
    <template #heading>Webapps</template>
    <h3>Digital Health Index Website [<a href="https://www.dhindex.com" target="_blank" rel="noopener">Link</a>]</h3>
    <p><b>Description: </b>Website to visualize the Center for Virtual Health, Value, and Excellence's Digital Health Index.</p>
    <p><b>Uses: </b>NextJS, TypeScript, MapboxJS, Mapbox APIs, PostgreSQL, Matomo, AWS, & Railway</p>
    <p><b>Role: </b> Built site and database architecture. Set up API calls with Mapbox and Llama (forthcoming)</p>
    <p><b>Currently: </b> Building AI Chatbot interface and back-end</p>
    <h3>Plurio [Link Coming]</h3>
    <p><b>Description: </b>Webapp for private educators to send automated natural language check-ins and reminders while keeping assignment completion analytics using Gen AI agents.</p>
    <p><b>Uses: </b>VueJS, TypeScript, AWS S3, AWS Sagemaker, Gmail API, Supabase</p>
    <p><b>Role: </b> Built site and database architecture. Set up API end points for AI processing using GCP.</p>
    <p><b>Currently: </b> Building Gmail API integration and authentication</p>
    <h3>Inglorious Artists Omeka S Website [<a href="https://digitalresearch.lib.unc.edu/s/inglorious-artists/page/home" target="_blank" rel="noopener">Link</a>]</h3>
    <p><b>Description: </b>Omeka S site for the Inglorious Artists project, a digital humanities project that explores the history of artists who were not recognized in their time.</p>
    <p><b>Uses: </b>Omeka S, PHP, MySQL, Docker, Ansible</p>
    <p><b>Role: </b>Created custom PHP theme and modules to optimize browsing and display. Created custom ansible tasks and docker environment for local testing.</p>
  </WelcomeItem>
  <WelcomeItem>
    <template #heading>Utility Tools</template>
      <h3>UCSF's Industry Document Library API Python Wrapper [<a href="https://github.com/UNC-Libraries/UCSF-Industry-Docs-API-Python-Wrapper" target="_blank" rel="noopener">Link</a>]</h3>
      <p><b>Description: </b>Python wrapper for the UCSF Industry Document Library API. Allows for CSV, JSON, or parquet output files.</p>
      <p><b>Uses: </b>Python, Polars</p>
      <h3>UCSF's Industry Document Library API R Wrapper [<a href="https://github.com/UNC-Libraries/UCSF-Industry-Docs-API-R-Wrapper" target="_blank" rel="noopener">Link</a>]</h3>
      <p><b>Description: </b>R wrapper for the UCSF Industry Document Library API. Allows for CSV, JSON, or parquet output files.</p>
      <p><b>Uses: </b>R, R6, dplyr</p>
      <h3>Library Chrome Extension [<a href="https://github.com/RolRodr/automatingcollectionsreview" target="_blank" rel="noopener">Link</a>]</h3>
      <p><b>Description: </b>Student project. Chrome extension to automate adding results from a catalogue or database search to CSV with simple UI.</p>
      <p><b>Uses: </b>JavaScript, Python</p>
  </WelcomeItem>

  <!-- <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Data Visualizations</template>
  </WelcomeItem> -->
</template>
  

<style scoped>
b {
  font-weight: 600;
}
p {
  max-width: 60vw;
  overflow: auto;
}
h2 {
  margin-top: 1rem;
  margin-bottom: 0.5rem;
  font-weight: 700;
  font-size: 1.4rem;
  color: var(--color-text-secondary);
}
h3 {
  margin-top: 1rem;
  margin-bottom: 0.5rem;
  font-weight: 700;
}
</style>