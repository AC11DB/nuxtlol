<template>
  <main>
    <header>
      <h1 class="main-heading">CPRG Day 1</h1>
      <p>
        HTML, CSS, and Git examples. This file also includes a little form
        that we can use when we learn some JS.
      </p>
    </header>
    <section>
      <h2>Form Example</h2>
      <form>
        <div class="form-example">
          <label for="name">Enter your name: </label>
          <input type="text" name="name" id="name" required />
        </div>
        <div class="form-example">
          <label for="email">Enter your email: </label>
          <input type="email" name="email" id="email" required />
        </div>
        <div class="form-example">
          <label for="password">Enter your password: </label>
          <input type="password" name="password" id="password" required />
        </div>
        <div class="form-example">
          <input type="submit" value="Subscribe!" />
        </div>
      </form>
    </section>
  </main>
</template>
