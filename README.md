# Bing
必应每日壁纸与故事接口
# 更新 2017.11.16
API:https://www.todaybing.com/api.html
<table>
<thead>
<tr>
<th align="center">参数名</th>
<th align="center">类型</th>
<th align="center">是否必要</th>
<th>备注</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">title</td>
<td align="center"><code>string</code></td>
<td align="center">否</td>
<td>故事标题</td>
</tr>
<tr>
<td align="center">image</td>
<td align="center"><code>sting</code></td>
<td align="center">否</td>
<td>图片地址</td>
</tr>
<tr>
<td align="center">story</td>
<td align="center"><code>string</code></td>
<td align="center">否</td>
<td>故事内容</td>
</tr>
</tbody>
</table>



现在你可以按照如下参数形式进行接口调用：<br>
api调用示例:<br>
https://www.todaybing.com/api
<br>
<table>
<thead>
<tr>
<th align="center">参数名</th>
<th align="center">类型</th>
<th align="center">是否必要</th>
<th>备注</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">w</td>
<td align="center"><code>Int</code></td>
<td align="center">是</td>
<td>图片宽度</td>
</tr>
<tr>
<td align="center">h</td>
<td align="center"><code>Int</code></td>
<td align="center">是</td>
<td>图片高度</td>
</tr>
<tr>
<td align="center">d</td>
<td align="center"><code>Int</code></td>
<td align="center">否</td>
<td>自今日起第<code>d</code>天前的图片</td>
</tr>
</tbody>
</table>
可用分辨率如下：
<blockquote><span class="pl-pds">'</span>1920x1080<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>1366x768<span class="pl-pds">'</span>,</br>
<span class="pl-pds">'</span>1280x768<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>1024x768<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>800x600<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>800x480<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>768x1280<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>720x1280<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>640x480<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>480x800<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>400x240<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>320x240<span class="pl-pds">'</span>,<br>
<span class="pl-pds">'</span>240x320<span class="pl-pds">'</span></blockquote>
可用日期：<br>
d={-1,0,1,2,3,4,5,6,7}
