<template>
  <div>
    <header>
      <div class="logo"></div>
      <nav>
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/shop">Shop</NuxtLink>
        <NuxtLink to="/">Events</NuxtLink>
        <NuxtLink to="/about">About Us</NuxtLink>
        <NuxtLink to="/">Contact Us</NuxtLink>
      </nav>
      <div class="relative w-full max-w-sm items-center">
        <Input id="search" type="text" placeholder="Search..." class="pl-10" />
        <span
          class="absolute start-0 inset-y-0 flex items-center justify-center px-2"
        >
          <Search class="size-6 text-muted-foreground" />
        </span>
      </div>
      <div class="buttons">
        <Button class="button" variant="outline" size="icon">
          <ChevronRight class="w-4 h-4" />
        </Button>
        <Button class="button" variant="outline" size="icon">
          <ChevronRight class="w-4 h-4" />
        </Button>
        <Button class="button" variant="outline" size="icon">
          <ChevronRight class="icon w-4 h-4" />
        </Button>
      </div>
    </header>
  </div>
</template>

<script>
import { ChevronRight } from "lucide-vue-next";
</script>

<style scoped>
.icon {
  color: red;
}
header {
  height: 100px;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
a {
  padding: 10px 15px;
  font-weight: 500;
}
.buttons {
  background-color: white;
}
.buttons:hover {
  background-color: white;
}
.button {
  margin: 0 10px;
}
</style>
