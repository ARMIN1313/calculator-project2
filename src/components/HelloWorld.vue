 <template>
  <div>
    <table id="calculator" dir="ltr" style="text-align: center; margin: auto">
      <tr>
        <!-- table row -->
        <td colspan="5">
          <!-- span = امتداد داشتن -->
          <input
            v-model="screen"
            dir="ltr"
            id="result"
            type="number"
            style="padding: 5px; font-weight: bold; text-align: right"
          />
      <td>
        <!-- table data -->
        </tr>
      <tr>
        <td><button @click="digit(7)" class="digit">7</button></td>
        <td><button @click="digit(8)" class="digit">8</button></td>
        <td><button @click="digit(9)" class="digit">9</button></td>
        <td><button @click="div" id="div">/</button></td>
        <td><button @click="clear" id="clear">C</button></td>
      </tr>
 </template>