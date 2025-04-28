<template>
    <div class="page">
      <div class="container">
        <h1 class="title">Trustiee - Privacy Policy Summarizer</h1>
  
        <!-- Install Button Section -->
        <div class="install-section">
          <a
            href="https://chromewebstore.google.com/detail/trustiee/ndbdgkpnbkffnbmldcjcoefmlmgojlhl?authuser=1&hl=en"
            target="_blank"
            class="install-button"
          >
            Install Trustiee Extension
          </a>
        </div>
  
        <section class="card">
          <h2 class="card-title">What is Trustiee?</h2>
          <p class="text">
            Trustiee simplifies complex legal documents like Privacy Policies and Terms of Service, helping users quickly understand key points.
          </p>
        </section>
  
        <section class="card">
          <h2 class="card-title">How to Use</h2>
          <ul class="list">
            <li>Install the extension from the Chrome Web Store or manually load it.</li>
            <li>Click the Trustiee icon in the toolbar to activate.</li>
            <li>Visit a page and click Summarize, or highlight text and use the context menu.</li>
            <li>Review the generated summary focusing on privacy risks.</li>
          </ul>
        </section>
  
        <section class="card">
          <h2 class="card-title">Features</h2>
          <ul class="list">
            <li>Automatic detection of legal content.</li>
            <li>Summarization in under 100 words.</li>
            <li>Lightweight and fast performance.</li>
            <li>No personal data collection.</li>
          </ul>
        </section>
  
        <section class="card">
          <h2 class="card-title">Privacy Commitment</h2>
          <p class="text">
            Trustiee does not track your activity or store any extracted content. Your privacy is fully respected.
          </p>
        </section>
      </div>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  .page {
    background: #f9fafb;
    min-height: 100vh;
    padding: 2rem;
  }
  
  .container {
    max-width: 800px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 2rem;
  }
  
  .title {
    font-size: 2.5rem;
    text-align: center;
    color: #1e293b;
    font-weight: 700;
  }
  
  /* Install button section */
  .install-section {
    text-align: center;
  }
  
  .install-button {
    background: #2563eb;
    color: #ffffff;
    padding: 0.75rem 1.5rem;
    border-radius: 8px;
    font-size: 1.1rem;
    font-weight: 600;
    text-decoration: none;
    transition: background 0.3s;
  }
  
  .install-button:hover {
    background: #1d4ed8;
  }
  
  .card {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    padding: 2rem;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  }
  
  .card-title {
    font-size: 1.5rem;
    color: #1d4ed8;
    margin-bottom: 1rem;
    font-weight: 600;
  }
  
  .text {
    font-size: 1rem;
    color: #334155;
    line-height: 1.6;
  }
  
  .list {
    padding-left: 1.5rem;
    list-style-type: disc;
    color: #334155;
    line-height: 1.6;
  }
  </style>