<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <hr>
  <hr>

  <div class="card">    
    <hr>
    <hr>
    <h2>BIODATA PRIBADI</h2>
    
    <div class="biodata">
      <p><strong>Nama Lengkap:</strong> Irsyadel Fikri</p>
      <p><strong>Npm:</strong> 233510591</p>
      <p><strong>Universitas:</strong> Universitas Islam Riau</p>
      <p><strong>Program Studi:</strong> Teknik Informatika</p>
      <p><strong>Tempat, Tanggal Lahir:</strong> Teluk Kuantan, 26 Juni 2005</p>
      <p><strong>Alamat:</strong> Jl. Rambah Raya, Kubang Raya, Riau</p>
      <p><strong>Email:</strong> irsyadelf@gmail.com</p>
      <p><strong>Telepon:</strong> 0823-8568-1353</p>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.card {
  text-align: center;
}

.biodata {
  margin-top: 1em;
  display: inline-block;
  text-align: left;
  padding: 1em;
  border: 1px solid #ddd;
  border-radius: 8px;
  background-color: #100f0f;
}
.biodata p {
  margin: 6px 0;
}
</style>
