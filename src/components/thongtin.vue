<script setup>
defineProps({
  mssv: {
    type: String,
    required: true
  },
  ten: {
    type: String,
    required: true
  }
  ,
  tuoi: {
    type: String,
    required: true
  }
  ,
  lop: {
    type: String,
    required: true
  }
  ,
  sothich: {
    type: String,
    required: true
  }
  ,
  diemmanh: {
    type: String,
    required: true
  }
  ,
  diemyeu: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div >
    <h1>Giới thiệu thông tin cá nhân</h1>
    <h2> mssv : {{ mssv }}</h2>
    <h2>Tên : {{ ten }}</h2>
    <h2>Tuổi : {{ tuoi }}</h2>
    <h2>Lop : {{ lop }}</h2>
    <h2>So Thich : {{ sothich }}</h2>
    <h2>Diem Manh : {{ diemmanh }}</h2>
    <h2>Diem Yeu : {{ diemyeu }}</h2>
  </div>

   
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>