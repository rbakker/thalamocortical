---
layout: default
title: Long-range thalamocortical neuron repository
crumbtitle: Main
---

## Thalamocortical neuron repository

EBRAINS DOI  10.25493/AWS5-MZG
LicenseCreative Commons Attribution-NonCommercial-ShareAlike 4.0 International
Project
Custodians
This dataset describes quantitatively the somatodendritic and axonal structure of individual thalamocortical projection neurons in the thalamic somatic and visual sensory nuclei. The cells in the dataset were labeled using state-of the art viral vectors able to drive massive levels of expression of marker proteins in a neuron after a single transfection event, leaving the rest of the brain unlabeled. This allows the unambiguous visualization /measurement of the entire axonal tree, no matter how large or complex. They are the first visualization of these cells ever reported in mice. Experiments were conducted in vivo in wildtype C57BL76 adult animals and have a low (<5%) success rate. Accurate labeling analysis is extremely labor-intensive, especially for large and widespread-axon cells. The present dataset may thus be viewed as a collection of “archetypal” reference specimens of these neuron populations. The accurate 3D data and measurement of axonal arborizations of thalamocortical neurons provide in this dataset will be re-usable by any scientist developing biologically-based models of local and long range brain circuitry.


Show neuron <input type="button" size="100" onclick="showNeuron(event,'R281HI')" value="R281HI"/> anchored in the Allen Mouse CCF_v3 atlas.

<script type="module">
  const rpc = await import('https://sba-dev.incf.org/js/rpc-interface.js');
  window.sbaInterface = new rpc.rpcInterface_class('https://sba-dev.incf.org/composer/?template=ABA_v3','SBA Composer');
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
