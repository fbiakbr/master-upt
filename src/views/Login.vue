<template>
  <div class="container">
    <div class="row justify-content-center mt-5">
      <div class="card col-md-6 pt-4 pb-4">
        <div class="text-center mb-3">
          <img src="/upt.png" width="125" />
          <h3 class="mt-2">UPT Server</h3>
        </div>
        <form class="container">
          <div class="form-group mb-2">
            <label for="nim">NIM</label>
            <input
              type="text"
              class="form-control"
              id="nim"
              placeholder="Enter NIM"
              pattern="[0-9]{2}.[0-9]{3}.[0-9]{4}"
              oninvalid="setCustomValidity('Format NIM : XX.XXX.XXXX')"
              required
            />
          </div>
          <div class="form-group mb-2">
            <label for="password">Password</label>
            <input
              type="password"
              class="form-control"
              id="password"
              placeholder="Password"
              required
            />
          </div>
          <button type="submit" class="btn btn-primary mt-2">Submit</button>
        </form>
      </div>
    </div>
  </div>
</template>
<script></script>
<style>
.card {
  border-radius: 20px;
}
</style>
