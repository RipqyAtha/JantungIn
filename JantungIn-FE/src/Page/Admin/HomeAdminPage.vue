<script setup>
import FooterComponent from '@/components/Footer-component.vue'
// Komponen untuk landing page JantungIn
</script>

<template>
  <div class="landing-page">
    <!-- Hero Section -->
    <section class="hero text-white py-16 px-4 pt-0">
      <div class="container mx-auto text-center pt-16">
        <h1 class="text-4xl font-bold mb-4">Welcome to JantungIn</h1>
        <p class="text-xl">Detect cardiovascular risk with AI-driven prediction and care</p>
      </div>
    </section>

    <!-- Why Choose Section -->
    <section class="why-choose bg-blue-50 py-16 px-4">
      <div class="container mx-auto text-center">
        <h2 class="text-2xl font-bold mb-10 text-blue-600">Why Choose JantungIn?</h2>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-5xl mx-auto">
          <!-- Card 1 -->
          <div class="feature-card bg-white rounded-lg shadow-md p-6 text-center">
            <div class="icon-wrapper flex justify-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-8 w-8 text-blue-600"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"
                  />
                </svg>
              </div>
            </div>
            <h3 class="text-lg font-semibold mb-2">Accurate Diagnosis</h3>
            <p class="text-gray-600 text-sm">
              Early risk identification to prevent cardiovascular issues with reliable results
            </p>
          </div>

          <!-- Card 2 -->
          <div class="feature-card bg-white rounded-lg shadow-md p-6 text-center">
            <div class="icon-wrapper flex justify-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-8 w-8 text-blue-600"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"
                  />
                </svg>
              </div>
            </div>
            <h3 class="text-lg font-semibold mb-2">Monitoring</h3>
            <p class="text-gray-600 text-sm">
              AI-driven visualization for personal cardiovascular condition monitoring
            </p>
          </div>

          <!-- Card 3 -->
          <div class="feature-card bg-white rounded-lg shadow-md p-6 text-center">
            <div class="icon-wrapper flex justify-center mb-4">
              <div class="bg-blue-100 p-3 rounded-full">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-8 w-8 text-blue-600"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                  />
                </svg>
              </div>
            </div>
            <h3 class="text-lg font-semibold mb-2">Health Insights</h3>
            <p class="text-gray-600 text-sm">
              Get in-depth insights to better secure your health and plan for better care
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- Expert Quote Section with Heart Images -->

    <section class="expert-quote py-10 px-4 text-white">
      <div class="container mx-auto">
        <div class="quote-content text-center max-w-4xl mx-auto">
          <p class="italic mb-4 text-sm md:text-base">
            "Penyakit jantung berisiko jika mengonsumsi rokok dan kafein yang tidak sehat. Gaya
            hidup modern yang kurang gerak, diet tinggi lemak jenuh menyebabkan penyakit
            kardiovaskular. Deteksi penyakit sejak dini membantu keamanan jantung yang jadi kunci
            kesehatan tubuh manusia sehat."
          </p>
          <p class="font-semibold text-sm mb-8">dr. Vita O, Sp.PD, M.Kes, FINASIM, FICA</p>
          <!-- Heart Images -->
          <div
            class="flex flex-col sm:flex-row justify-center sm:space-x-4 md:space-x-10 space-y-6 sm:space-y-0 mx-auto mt-8 sm:mt-12 mb-4"
          >
            <div class="image-container w-64 sm:w-40 md:w-48 mx-auto sm:mx-0">
              <img
                src="/images/heart1.jpg"
                alt="Heart condition 1"
                class="rounded-lg w-full h-40 object-cover"
                onerror="this.src='https://images.unsplash.com/photo-1559757175-7b21671636f6?ixlib=rb-4.0.3&auto=format&fit=crop&w=1589&q=80'"
              />
            </div>
            <div class="image-container w-64 sm:w-40 md:w-48 mx-auto sm:mx-0">
              <img
                src="/images/heart2.jpg"
                alt="Heart condition 2"
                class="rounded-lg w-full h-40 object-cover"
                onerror="this.src='https://images.unsplash.com/photo-1638913974023-cef988e81629?ixlib=rb-4.0.3&auto=format&fit=crop&w=1470&q=80'"
              />
            </div>
            <div class="image-container w-64 sm:w-40 md:w-48 mx-auto sm:mx-0">
              <img
                src="/images/heart3.jpg"
                alt="Heart condition 3"
                class="rounded-lg w-full h-40 object-cover"
                onerror="this.src='https://images.unsplash.com/photo-1701696602374-7cb01810a90f?ixlib=rb-4.0.3&auto=format&fit=crop&w=1374&q=80'"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Call to action -->
    <section class="cta bg-blue-50 py-20 px-4">
      <div class="container mx-auto text-center py-8">
        <h2 class="text-3xl font-bold mb-3 text-blue-500">What are you waiting for?</h2>
        <p class="mb-8 text-blue-500 text-lg">Let's get started</p>
        <button>
          <router-link
            to="/diagnose-admin"
            class="bg-blue-500 hover:bg-blue-600 text-white font-medium py-3 px-8 rounded-md text-lg shadow-md"
          >
            Start Diagnose
          </router-link>
        </button>
      </div>
    </section>

    <!-- Footer Component -->
    <FooterComponent />
  </div>
</template>

<style scoped>
.landing-page {
  font-family: 'Arial', sans-serif;
}

.hero {
  background-image: linear-gradient(
    to bottom,
    #3b82f6,
    #60a5fa
  ); /* Gradasi biru dari gelap ke terang */
  margin-top: -37px; /* Menghilangkan gap kecil antara navbar dan hero section */
}

.feature-card {
  transition: transform 0.3s ease;
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.08);
}

.feature-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.1);
}

.expert-quote {
  background-image: linear-gradient(
    to bottom,
    #2563eb,
    #4f86f7
  ); /* Gradasi biru dari gelap ke terang sama dengan hero section */
  color: white;
}

.image-container img {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  transition: transform 0.3s ease;
}

.image-container img:hover {
  transform: scale(1.03);
}

.cta h2 {
  color: #2563eb; /* Warna biru yang lebih sesuai dengan navbar */
}

button {
  background-color: #3b82f6; /* Updated blue color matching the image */
}

button:hover {
  background-color: #2563eb; /* Slightly darker blue for hover */
}

.newsletter-title {
  font-family: 'Times New Roman', Times, serif;
  font-weight: normal;
  letter-spacing: 0.5px;
  color: #333;
  font-size: 1.75rem;
}
</style>
