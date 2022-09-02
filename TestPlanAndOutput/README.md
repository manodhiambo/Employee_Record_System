<h1>TEST PLAN</h1>

<table>
<tr>
<th>TEST ID</th>
<th>TEST CASE OBJECTIVE</th>
<th>INPUT DATA</th>
<th>EXPECTED OUTPUT</th>
<th>ACTUAL OUTPUT</th>
<th>STATUS</th>
</tr>
<tr>
<td>TC_01</td>
<td>for entering name</td>
<td>enter name: abc</td>
<td>abc</td>
<td>abc</td>
<td>PASS</td>
</tr>
<tr>
<td>TC_02</td>
<td>for entering name</td>
<td>enter name: abc</td>
<td>ABC</td>
<td>-</td>
<td>FAIL</td>
</tr>
<tr>
<td>TC_03</td>
<td>for entering age</td>
<td>enter age: 12</td>
<td>12</td>
<td>12</td>
<td>PASS</td>
</tr>
<tr>
<td>TC_04</td>
<td>for entering age</td>
<td>enter age: 12</td>
<td>12</td>
<td>-</td>
<td>FAIL</td>
</tr>
<tr>
<td>TC_05</td>
<td>for entering salary</td>
<td>enter salary: 5000</td>
<td>5009</td>
<td>5000</td>
<td>PASS</td>
</tr>
<tr>
<td>TC_06</td>
<td>for entering salary</td>
<td>enter salary: 5000</td>
<td>5000</td>
<td>-</td>
<td>FAIL</td>
</tr>
<tr>
<td>TC_07</td>
<td>for listing record</td>
<td>abc 12 5000</td>
<td>abc 12 5000</td>
<td>abc 12 5000</td>
<td>PASS</td>
</tr>
<tr>
<td>TC_08</td>
<td>for listing record</td>
<td>abc 12 5000</td>
<td>abc 12 5000</td>
<td>abc 5000 12</td>
<td>FAIL</td>
</tr>
<tr>
<td>TC_09</td>
<td>for listing record</td>
<td>abc 12 5000</td>
<td>abc 12 5000</td>
<td>12 abc 5000</td>
<td>FAIL</td>
</tr>
<tr>
<td>TC_10</td>
<td>for deleting record</td>
<td>abc</td>
<td>abc</td>
<td>abc</td>
<td>PASS</td>
</tr>
<tr>
<td>TC_11</td>
<td>abc</td>
<td>abc</td>
<td>abc</td>
<td>abc</td>
<td>PASS</td>
</tr>
</table>
