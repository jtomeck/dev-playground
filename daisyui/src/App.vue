<template>
  <AppBar />

  <div class="container mx-auto py-12">
    <div class="grid grid-cols-3 gap-12">

      <div class="bg-white card bordered rounded-none">
        <figure>
          <img src="https://picsum.photos/id/1005/400/250">
        </figure>
        <div class="card-body">
          <h2 class="card-title">Top image
            <div class="badge mx-2 bg-green-500 border-none">NEW</div>
          </h2>
          <p>Rerum reiciendis beatae tenetur excepturi aut pariatur est eos. Sit sit necessitatibus veritatis sed molestiae voluptates incidunt iure sapiente.</p>
          <div class="justify-end card-actions">
            <button class="btn btn-primary btn-shadowed">More info</button>
          </div>
        </div>
      </div>

      <div class="bg-white card bordered">
        <figure>
          <img src="https://picsum.photos/id/1005/400/250">
        </figure>
        <div class="card-body">
          <h2 class="card-title">Top image
            <div class="badge mx-2 badge-secondary">NEW</div>
          </h2>
          <p>Rerum reiciendis beatae tenetur excepturi aut pariatur est eos. Sit sit necessitatibus veritatis sed molestiae voluptates incidunt iure sapiente.</p>
          <div class="justify-end card-actions">
            <button class="btn btn-secondary">More info</button>
          </div>
        </div>
      </div>

      <div class="bg-white card bordered">
        <figure>
          <img src="https://picsum.photos/id/1005/400/250">
        </figure>
        <div class="card-body">
          <h2 class="card-title">Top image
            <div class="badge mx-2 badge-secondary">NEW</div>
          </h2>
          <p>Rerum reiciendis beatae tenetur excepturi aut pariatur est eos. Sit sit necessitatibus veritatis sed molestiae voluptates incidunt iure sapiente.</p>
          <div class="justify-end card-actions">
            <button class="btn btn-secondary">More info</button>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<script setup>
import AppBar from './components/AppBar.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
</script>
