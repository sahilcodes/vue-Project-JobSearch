<script>
export default {
  data() {
    return {
      name: "SahilCodes",
      status: "active",
      tasks: ["Task One", "Task Two", "Task Three"]
    };
  },
};
</script>

<template>
  <h1>{{ name }}</h1>
  <p v-if="status === 'active'">User is active</p>
  <p v-else-if="status === 'pending'">User is pending</p>
  <p v-else>User is inactive</p>
</template>
