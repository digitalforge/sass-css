<template>
  <section class="section-book">
    <div class="row">
      <div class="book">
        <div class="book__form">
          <div class="u-margin-bottom-medium">
            <h2 class="heading-secondary">Start booking now</h2>
          </div>
          <form class="form">
            <div class="form__group">
              <input
                type="text"
                class="form__input"
                placeholder="Full Name"
                id="name"
                required
              />
              <label for="name" class="form__label">Full Name</label>
            </div>
            <div class="form__group">
              <input
                type="email"
                class="form__input"
                placeholder="Email Address"
                id="email"
                required
              />
              <label for="email" class="form__label">Email</label>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style></style>
