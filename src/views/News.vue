<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>ข่าวสาร</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">-ข่าวสาร</ion-title>
        </ion-toolbar>
      </ion-header>
      
      <ion-card>
  <ion-item>
    <ion-icon name="pin" slot="start"></ion-icon>
    <ion-label>รายละเอียด</ion-label>
    <ion-button fill="outline" slot="end">View</ion-button>
  </ion-item>

  <ion-card-content>
   รายละเอียด
  </ion-card-content>
</ion-card>
<ion-card>
  <ion-item>
    <ion-icon name="pin" slot="start"></ion-icon>
    <ion-label>รายละเอียด</ion-label>
    <ion-button fill="outline" slot="end">View</ion-button>
  </ion-item>

  <ion-card-content>
   รายละเอียด
  </ion-card-content>
</ion-card>
<ion-card>
  <ion-item>
    <ion-icon name="pin" slot="start"></ion-icon>
    <ion-label>รายละเอียด</ion-label>
    <ion-button fill="outline" slot="end">View</ion-button>
  </ion-item>

  <ion-card-content>
   รายละเอียด
  </ion-card-content>
</ion-card>
      <ExploreContainer name="ข่าวสาร" />
    </ion-content>
  </ion-page>

  
</template>

<script lang="ts">
//import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
//import ExploreContainer from '../components/ExploreContainer.vue';


export default  {
 // name: 'News',
 //  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
}
</script>