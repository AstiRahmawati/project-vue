    <script setup>
import { Navbar, NavbarLogo, NavbarCollapse, NavbarLink } from 'flowbite-vue'
</script>
<template>
    <Navbar>
      <template #logo>
        <NavbarLogo link="https://www.google.com/" alt="Flowbite logo" image-url="https://media.istockphoto.com/id/1308743843/id/vektor/elemen-desain-logo-rumah.jpg?s=170667a&w=0&k=20&c=tWOXzdX4MkG1OIee_4pZbu65sZvSMENuTqzYekowTF0=">
          Nekaso
        </NavbarLogo>
      </template>
      <template #default="{isShowMenu}">
        <NavbarCollapse :isShowMenu="isShowMenu">
          <NavbarLink isActive link="#">Beranda</NavbarLink>
          <NavbarLink link="#">Tentang</NavbarLink>
          <NavbarLink link="#">Galeri</NavbarLink>
          <NavbarLink link="#">Kontak</NavbarLink>
        </NavbarCollapse>
      </template>
    </Navbar>
</template>