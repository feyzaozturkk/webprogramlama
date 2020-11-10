<template>
    <v-app>
        <v-content>
            <v-container class="fill-height about" fluid>
                <v-col cols="12">
                    <v-row align="center">
                      
                <div  class="d-flex flex-row ">
                  
                
                       <v-tabs>
                         <v-tab class ="mdi-home" icon>
                            <v-icon> mdi-home </v-icon></v-tab>


                      <v-tab>YENİ SEZON AYAKKABI</v-tab>
                      <v-tab>ÇAĞLA X PELİN</v-tab>
                      <v-select
                     :items="items"
                     label="STILETTO"
                      dense
                    ></v-select>
                      <v-tab>EV TERLİĞİ</v-tab>
                      <v-tab>İNDİRİMDEKİLER</v-tab>
                       <v-tab>SPOR AYAKKABI VE BABETLER</v-tab>
                       <v-tab>ÇİZME</v-tab>
                       <v-tab>GERÇEK DERİ</v-tab>
                       <v-tab>TOPUKLU AYAKKABI</v-tab>


                        </v-tabs>
                  



        


                  </div>
                    </v-row>
                </v-col>
             
            </v-container>
       </v-content>
    </v-app>
</template>
<script>
  export default {
    data: () => ({
      items: ['>12 CM STILETTO', '>8 CM STILETTO', '>5 CM STILETTO', '>10 CM STILETTO'],
    }),
  }
</script>






