---
layout: default
title: Long-range thalamocortical neuron repository
crumbtitle: Main
---

## Thalamocortical neuron repository

- Dataset: hosted at [EBRAINS](https://dx.doi.org/10.25493/AWS5-MZG).
- License: Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International

Show neuron <input type="button" size="100" onclick="showNeuron(event,'R281HI')" value="R281HI"/> anchored in the Allen Mouse CCF_v3 atlas.

<script type="module">
  const rpc = import('https://sba-dev.incf.org/js/rpc-interface.js')
  .then( (rpc) => {
    window.sbaInterface = new rpc.rpcInterface_class('https://sba-dev.incf.org/composer/?template=ABA_v3','SBA Composer');
  } );
</script> 
<script type="text/javascript">
var showNeuron = function(evt,name) {
  if (!sbaInterface) {
    setTimeout(() => showNeuron(evt,name),100);
  } else {
    console.log(sbaInterface);
  }
}
</script>
