 <template>
  <div class="container-fluid">
    <cover></cover>
      <div class="row d-flex justify-content-center" >
          <sidebar class="col-lg-2 col-md-12 col-sm-12"></sidebar>
          <usercontent class="col-lg-8 col-md-12 col-sm-12 "></usercontent>
          <whotofollow class="col-lg-2 col-md-12 col-sm-12  "></whotofollow>
      </div>
  </div>
</template>

<script>

import sidebar from '../components/templates/sidebar.vue'
import usercontent from '../components/templates/usercontent.vue'
import whotofollow from '../components/templates/whotofollow.vue'
import cover from '../components/templates/cover.vue'
export default {
  name: 'userpage',
  components: {
    sidebar,
    usercontent,
    whotofollow,
    cover
  }
}
</script>

<style scoped lang="scss">
@import '../styles/variables.scss';
.container-fluid{
  max-width:1440px;
  margin:0 auto;
  padding:0;
// float: left;
}

</style>
