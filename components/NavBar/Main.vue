<script setup lang="ts">
import { Input } from "@/components/ui/input";
</script>

<template>
  <header>
    <nav
      class="fixed flex flex-row bg-primary px-16 h-[4rem] text-primary-foreground justify-between items-center w-full z-50"
    >
      <NuxtLink to="/">
        <div>Logo + Brand</div>
      </NuxtLink>
      <div class="flex flex-row items-center gap-2">
        <div class="relative w-full max-w-sm items-center text-black">
          <Input
            id="search"
            type="text"
            placeholder="Search..."
            class="pl-10"
          />
          <span
            class="absolute start-0 inset-y-0 flex items-center justify-center px-2"
          >
            <IconsSearch class="" />
          </span>
        </div>
        <NuxtLink to="/Login">
          <div>| Login</div>
        </NuxtLink>
      </div>
    </nav>
  </header>
</template>
