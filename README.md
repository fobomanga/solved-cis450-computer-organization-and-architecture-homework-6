Download Link: https://assignmentchef.com/product/solved-cis450-computer-organization-and-architecture-homework-6
<br>
<ol>

 <li>Consider the Simple Memory System given in Lecture 20 with 14-bit virtual addresses, 12-bit physical addresses, and a page size of 2<sup>6</sup> = 64 bytes:</li>

</ol>




<table width="288">

 <tbody>

  <tr>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

  </tr>

 </tbody>

</table>

Use the Simple Memory System above to complete the following address translation problems to convert the given Virtual Address to the corresponding Physical Address. Note that all table values are given in hexadecimal format. Complete the virtual address and other fields.




<ul>

 <li>Virtual Address: 0x036A</li>

</ul>




<ul>

 <li>12 11  10  9   8   7  6   5  4   3   2   1  0</li>

</ul>

<table width="336">

 <tbody>

  <tr>

   <td width="24">0</td>

   <td width="24">    0</td>

   <td width="24">    0</td>

   <td width="24">   0</td>

   <td width="24">    1</td>

   <td width="24">    1</td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

  </tr>

 </tbody>

</table>




VPN ______   TLBI ______  TLBT ______  TLB Hit? ___  Page Fault? ___  PPN: _______




Physical Address: _________

<ul>

 <li>10 9   8   7  6   5  4   3   2   1  0</li>

</ul>










<ul>

 <li>Virtual Address: 0x0177</li>

</ul>




<ul>

 <li>12 11  10  9   8   7  6   5  4   3   2   1  0</li>

</ul>

<table width="336">

 <tbody>

  <tr>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

  </tr>

 </tbody>

</table>

VPN ______   TLBI ______  TLBT ______  TLB Hit? ___  Page Fault? ___  PPN: _______




Physical Address: _________

<ul>

 <li>10 9   8   7  6   5  4   3   2   1  0</li>

</ul>

<ol start="2">

 <li>Once the physical address is resolved, use the Data Cache shown below to determine if the data can be obtained from the cache, or if access to memory is required (just write MEM for your answer). You may assume that:</li>

</ol>

<ul>

 <li>The memory is byte addressable. Memory accesses are to 1-byte words, not 4-byte words.</li>

 <li>Physical addresses are 12 bits wide.</li>

 <li>The cache is a direct mapped cache with a 4-byte block size and 16 lines total as shown below. Note that all numbers are given in <strong>hexadecimal</strong></li>

</ul>




<sub>        </sub>

(a) For each physical address given below, if a cache hit occurs, indicate the cache entry accessed and the cache byte value returned in hex. If a cache miss occurs, just write ‘N’ next to “Cache Hit?” and just write “MEM” for the cache byte returned to indicate that the reference must be resolve by going out to main memory.




<h1> Physical Address: 0xB6A</h1>

11  10  9   8   7  6   5  4   3   2   1   0

<table width="288">

 <tbody>

  <tr>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

  </tr>

 </tbody>

</table>










<table width="379">

 <tbody>

  <tr>

   <td width="241"><strong>Parameter </strong></td>

   <td width="138"><strong>Value </strong></td>

  </tr>

  <tr>

   <td width="241">Cache Byte Offset</td>

   <td width="138">0x</td>

  </tr>

  <tr>

   <td width="241">Cache Index</td>

   <td width="138">0x</td>

  </tr>

  <tr>

   <td width="241">Cache Tag</td>

   <td width="138">0x</td>

  </tr>

  <tr>

   <td width="241">Cache Hit (Y/N)?</td>

   <td width="138"> </td>

  </tr>

  <tr>

   <td width="241">If Hit, Cache Byte Returned</td>

   <td width="138">0x</td>

  </tr>

 </tbody>

</table>




<h1>Physical Address: 0x05B7</h1>




11  10  9   8   7  6   5  4   3   2   1   0

<table width="288">

 <tbody>

  <tr>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

   <td width="24"> </td>

  </tr>

 </tbody>

</table>










<table width="379">

 <tbody>

  <tr>

   <td width="241"><strong>Parameter </strong></td>

   <td width="138"><strong>Value </strong></td>

  </tr>

  <tr>

   <td width="241">Cache Byte Offset</td>

   <td width="138">0x</td>

  </tr>

  <tr>

   <td width="241">Cache Index</td>

   <td width="138">0x</td>

  </tr>

  <tr>

   <td width="241">Cache Tag</td>

   <td width="138">0x</td>

  </tr>

  <tr>

   <td width="241">Cache Hit (Y/N)?</td>

   <td width="138"> </td>

  </tr>

  <tr>

   <td width="241">If Hit, Cache Byte Returned</td>

   <td width="138">0x</td>

  </tr>

 </tbody>

</table>


