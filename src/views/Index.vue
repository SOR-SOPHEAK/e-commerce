<template>
    <header>
      <!-- <img alt="Vue logo" class="logo" src="@/assets/images/logo.svg" width="125" height="125" /> -->
  
      <div class="wrapper">
        <nav>
          <!-- klaeng del access tv link -->
          <RouterLink to="/">Home</RouterLink> 
          <RouterLink to="/about">About</RouterLink>
          <RouterLink to="/product">Product</RouterLink>
          <RouterLink to="/checkout">Checkout</RouterLink>
          <button @click="$emit('checkout')">Go To Checkout</button>
        </nav>
      </div>
    </header>
  
    <!-- klaeng render -->
    <RouterView />
  </template>
  