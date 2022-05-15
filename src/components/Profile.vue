<template>
  <div>
    <h1>Profile</h1>
    <h2>{{ "Name : " + first + " " + last }}</h2>
    <h2>{{ "Age  : " + age }}</h2>
    <h2>{{ "Skill : " + skill }}</h2>
  </div>
</template>>



<script>
export default {
  data() {
    return {
      first: "Songkiet",
      last: "Siriso",
      age: 12,
      skill: "Basic SQL, Basic C#, Bacis java",
    };
  },
};
</script>>