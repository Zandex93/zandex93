### Hi there š

<!--
**Zandex93/zandex93** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->


// This function returns a string padded with leading zeros
function padZeros(num, totalLen) {
   var numStr = num.toString();             // Initialize return value as string
   var numZeros = totalLen - numStr.length; // Calculate no. of zeros
   for (var i = 1; i <= numZeros; i++) {
      numStr = "0" + numStr;
   }
   return numStr;
}
