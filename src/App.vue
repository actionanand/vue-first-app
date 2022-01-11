<template>
  <section>
    <header>
      <h1>My Friends</h1>
    </header>
    <ul>
      <friend-contact></friend-contact>
      <friend-contact></friend-contact>
    </ul>
  </section>
</template>

<script>
  export default {
    data() {
      return {
        friends: [
          {
            id: 'rajesh',
            name: 'Rajesh Kumar',
            phone: '01234 5678 991',
            email: 'rajesh@localhost.com',
          },
          {
            id: 'julie',
            name: 'Julie Jones',
            phone: '09876 543 221',
            email: 'julie@localhost.com',
          },
        ],
      };
    }
  };
</script>