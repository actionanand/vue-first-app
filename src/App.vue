<template>
  <section>
    <header>
      <h1>My Friends</h1>
    </header>
    <ul>
      <friend-contact v-for="friend in friends"
        :key="friend.id"
        :name="friend.name"
        :phone-number="friend.phone"
        :email-address="friend.email"
        :is-favorite="friend.favorite"
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
            favorite: true
          },
          {
            id: 'julie',
            name: 'Julie Jones',
            phone: '09876 543 221',
            email: 'julie@localhost.com',
            favorite: true
          },
        ],
      };
    }
  };
</script>