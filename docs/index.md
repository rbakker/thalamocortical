---
layout: default
title: Long-range thalamocortical neuron repository
crumbtitle: Main
---

## Thalamocortical neuron repository

Show neuron <input type="button" size="100" onclick="showNeuron(event,'R281HI')" value="R281HI"/> anchored in the Allen Mouse CCF_v3 atlas.

<script type="module">
  import { rpcInterface_class } from 'https://sba-dev.incf.org/js/rpc-interface.js';
  window.rpcInterface_class = rpcInterface_class;
  console.log('module',window.rpcInterface_class);
</script> 
<script type="text/javascript">
console.log('script',window.rpcInterface_class);
function showNeuron(evt,name) {
  console.log('showNeuron');
}
</script>
