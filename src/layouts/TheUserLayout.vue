<template>
  <div class="the-user-layout">
    <h1>Welcome {{ $route.params.user }}</h1>
    <MessageHandlerContainer></MessageHandlerContainer>
  </div>
</template>

<script>
import MessageHandlerContainer from '../components/MessageHandlerContainer'

export default {
  name: 'TheUserLayout',
  components: {
    MessageHandlerContainer
  }
}
</script>

<style lang="scss">
.the-user-layout {
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>