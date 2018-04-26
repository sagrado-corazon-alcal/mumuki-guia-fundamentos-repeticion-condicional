Ojo que en la última celda **también puede haber una planta**, ese caso vas a tener que manejarlo por separado.

Te dejamos un ejemplo que te puede ayudar:

<table class= "table" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Inicial</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Final</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
        GBB/1.0
        size 4 2
        cell 0 0 Verde 1
        cell 1 0 Negro 1
        cell 2 0 Negro 1
        cell 3 0 Verde 1
        head 0 0
      </gs-board>
    </td>
    <td style="text-align: center"><i class="fa fa-arrow-right"></i></td> 
    <td style="text-align: center">
      <gs-board>
        GBB/1.0
        size 4 2
        cell 1 0 Negro 1
        cell 2 0 Negro 1
        head 3 0
      </gs-board>
    </td>
  </tr>
  <tbody>
</table>
