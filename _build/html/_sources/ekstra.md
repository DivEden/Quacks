
# Svævende tekst
<style>
.tooltip {
  position: relative;
  display: inline-block;
  color: CadetBlue; /* Make the text blue */
  cursor: pointer; /* Optional: changes the cursor to indicate it's interactive */
}

.tooltip .tooltiptext {
  visibility: hidden;
  width: 120px;
  background-color: black;
  color: #fff;
  text-align: center;
  border-radius: 6px;
  padding: 5px;
  position: absolute;
  z-index: 1;
}

.tooltip:hover .tooltiptext {
  visibility: visible;
}

</style>
  This is an example of 
  <span class="tooltip">hoverable text
    <span class="tooltiptext">xd</span>
  </span> 