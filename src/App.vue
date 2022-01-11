<template>
  <section>
    <header>
      <h1>My Friends</h1>
    </header>
    <ul>
      <friend-contact
        name="Rajesh Kumar" phone-number="01234 5678 991" email-address="rajesh@localhost.com"
      ></friend-contact>
      <friend-contact
        name="Julie Jones" phone-number="09876 543 221" email-address="julie@localhost.com"
      ></friend-contact>
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