<script>
import Navbar from "../components/Navbar/Navbar.vue";
import InputForm from "../components/ContactComponents/InputForm.vue";
import TextAreaForm from "../components/ContactComponents/TextAreaForm.vue";

export default {
  name: "ContactView",
  components: {
    Navbar,
    InputForm,
    TextAreaForm,
  },
  data() {
    return {
      email: "",
      phone: "",
      textarea: "",
    };
  },
};
</script>

<template>
  <div class="bg-[url('/src/components/Backgrounds/background-home.svg')] bg-no-repeat bg-cover h-screen">
    <Navbar />
    <h1 class="text-center font-[500] text-[30px] leading-[136%] text-black">Contact Us</h1>

    <div class="flex justify-center mt-[89px]">
      <div class="w-[932px] h-[462px] bg-white shadow-md rounded-md">
        <div>
          <InputForm type="email" placeholder="E-mail" v-model="email" />
          <InputForm type="number" placeholder="Phone" v-model="phone" />
        </div>
        <TextAreaForm cols="40" rows="8" placeholder="Message" v-model="textarea" />
      </div>
    </div>
  </div>
</template>
