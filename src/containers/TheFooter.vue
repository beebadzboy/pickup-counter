<template>
  <CFooter :fixed="false">
    <div>
      
      <span class="ml-1">&copy; {{new Date().getFullYear()}} Create By DBD.</span>
    </div>
    <div class="mfs-auto">
      <span class="mr-1" target="_blank">Powered by</span>
      <a href="https://www.kingpower.com">King Power Group</a>
    </div>
  </CFooter>
</template>

<script>
export default {
  name: 'TheFooter'
}
</script>
