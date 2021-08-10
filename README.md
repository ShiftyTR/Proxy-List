# Proxy-List
Free proxy list UPDATED HOURLY!


<br>
<br>
<p align="center">
  <img src="https://raw.githubusercontent.com/ShiftyTR/Proxy-List/master/proxy.png"  title="proxy-list">
</p>

### Download
```bash
# Download and save to local file `proxy.txt` with format `IP:PORT`
curl -sSf "https://raw.githubusercontent.com/shiftytr/proxy-list/master/proxy.txt" > proxy.txt
```
<div class="container-fluid">

<div class="col-12">

<div class="card card-body">

<div class="table-responsive">

<table class="table mb-0" id="proxyTable">

<thead class="thead-light"></thead>

<thead class="thead-light">

<tr>

<th>Parameter</th>

<th>Value</th>

<th>Description</th>

<th>Example Format</th>

</tr>

</thead>

<tbody>

<tr>

<td>Format</td>

<td>json,txt</td>

<td>Format api output</td>

<td><a href="https://www.proxyscan.io/api/proxy?format=json" target="_blank">https://www.proxyscan.io/api/proxy?format=json</a></td>

</tr>

<tr>

<td>Level</td>

<td>transparent, anonymous, elite</td>

<td>Anonymity Level</td>

<td><a href="https://www.proxyscan.io/api/proxy?level=elite" target="_blank">https://www.proxyscan.io/api/proxy?level=elite</a></td>

</tr>

<tr>

<td>Type</td>

<td>http, https, socks4, socks5</td>

<td>Proxy Protocol</td>

<td><a href="https://www.proxyscan.io/api/proxy?type=http,https" target="_blank">https://www.proxyscan.io/api/proxy?type=http,https</a></td>

</tr>

<tr>

<td>Last_Check</td>

<td>Any Number</td>

<td>Seconds the proxy was last checked</td>

<td><a href="https://www.proxyscan.io/api/proxy?last_check=500" target="_blank">https://www.proxyscan.io/api/proxy?last_check=3600</a></td>

</tr>

<tr>

<td>Port</td>

<td>Any Number</td>

<td>Proxies with a specific port</td>

<td><a href="https://www.proxyscan.io/api/proxy?port=80" target="_blank">https://www.proxyscan.io/api/proxy?port=80</a></td>

</tr>

<tr>

<td>Ping</td>

<td>Any Number</td>

<td>How fast you get a response after you've sent out a request</td>

<td><a href="https://www.proxyscan.io/api/proxy?ping=100" target="_blank">https://www.proxyscan.io/api/proxy?ping=100</a></td>

</tr>

<tr>

<td>Limit</td>

<td>1 - 20</td>

<td>How many proxies to list.</td>

<td><a href="https://www.proxyscan.io/api/proxy?limit=10" target="_blank">https://www.proxyscan.io/api/proxy?limit=10</a></td>

</tr>

<tr>

<td>Uptime</td>

<td>1 - 100</td>

<td>How reliably a proxy has been running</td>

<td><a href="https://www.proxyscan.io/api/proxy?uptime=50" target="_blank">https://www.proxyscan.io/api/proxy?uptime=50</a></td>

</tr>

<tr>

<td>Country</td>

<td>Example: US, FR</td>

<td>Country of the proxy</td>

<td><a href="https://www.proxyscan.io/api/proxy?country=fr,us" target="_blank">https://www.proxyscan.io/api/proxy?country=fr,us</a></td>

</tr>

<tr>

<td>Not_Country</td>

<td>Example: CN, NL</td>

<td>Avoid proxy countries</td>

<td><a href="https://www.proxyscan.io/api/proxy?not_country=cn,nl" target="_blank">https://www.proxyscan.io/api/proxy?not_country=cn,nl</a></td>

</tr>

</tbody>

</table>

</div>

</div>

<div class="card card-body">

##### Sample usage

<span style="font-size: 15px;">[https://www.proxyscan.io/api/proxy?last_check=3800&country=fr,us&uptime=50&ping=100limit=10&type=http,https](https://www.proxyscan.io/api/proxy?last_check=3800&country=fr,us&uptime=50&ping=100&limit=10&type=http,https)</span></div>

</div>

</div>
