<template>
  <div>
    <ClientOnly>
      <SharedNavbar/>
      <slot />
      <SharedFooter/>
    </ClientOnly>
  </div>
</template>