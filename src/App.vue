<script setup>
import { RadioButtonComponent as EjsRadiobutton } from '@syncfusion/ej2-vue-buttons';
import { CheckBoxComponent as EjsCheckbox } from '@syncfusion/ej2-vue-buttons';
</script>

<template>
  <ejs-checkbox label="Default" checked="true"
                cssClass="e-small" enableRtl="true" disabled="true"></ejs-checkbox>

    
<!-- <ul>
  <li><ejs-radiobutton label="Credit/Debit Card" name="payment" checked="true"
                       cssClass="e-small" enableRtl="true"></ejs-radiobutton></li>
  <li><ejs-radiobutton label="Net Banking" name="payment"
                       cssClass="e-small" enableRtl="true"></ejs-radiobutton></li>
  <li><ejs-radiobutton label="Cash on Delivery" name="payment"
                       cssClass="e-small" enableRtl="true" disabled="true"></ejs-radiobutton></li>
  <li><ejs-radiobutton label="Others" name="payment"
                       cssClass="e-small" enableRtl="true"></ejs-radiobutton></li>
</ul> -->
</template>

<style>
 @import '../node_modules/@syncfusion/ej2-base/styles/material.css';
 @import '../node_modules/@syncfusion/ej2-buttons/styles/material.css';
.e-radio-wrapper {
  margin-top: 18px;
}
.e-checkbox-wrapper {
  margin-top: 18px;
}
li {
  list-style: none;
}
</style>
