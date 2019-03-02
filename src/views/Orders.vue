<template>
  <div class="animated fadeIn">
    <b-row>
      <b-col>
        <app-table :table-data="items" :fields="fields" caption></app-table>
      </b-col>
    </b-row>
  </div>
</template>

<script>
import Table from './base/Table.vue';

export default {
  components: {
    appTable: Table,
  }  
}
</script>
