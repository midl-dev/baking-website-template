---
layout: default
---

## Baking website template

Enter your Tezos address here:

<input type="text" id="tezos_address" rows="800" placeholder="Your tezos address (starting with tz)">
<button onclick="window.location='payouts/'+getInputValue()+'.html';">Go!</button>

<script>
    function getInputValue(){
        // Selecting the input element and get its value 
        var inputVal = document.getElementById("tezos_address").value;
        
        // Displaying the value
        return inputVal;
    }
</script>
