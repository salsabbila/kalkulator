<script>
export default {
    data() {
      return{
          nama : "Restu Sugesti Putri",
          tahunlahir : 2000,
          kotalahir : "Bandung"
      }  
    },
    methods:{
        next(){
            this.tahunlahir += 1;
        }
    },
    mounted(){
        this.tahunlahir = 2021 - this.tahunlahir;
    }
}
</script>