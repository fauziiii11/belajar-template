<script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar solid>
      <template #logo>
        <NavbarLogo link="" alt="ADIDAS logo" image-url="https://www.adidas.co.id/media/logo/adidas-logo.png">
          Adidas
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink is-active>Home</NavbarLink>
          <NavbarLink>Men</NavbarLink>
          <NavbarLink>Women</NavbarLink>
          <NavbarLink>Kids</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>
