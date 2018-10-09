﻿---
title: Windows7Param members (Microsoft.Isam.Esent.Interop.Windows7)
TOCTitle: Windows7Param members
ms:assetid: AllMembers.T:Microsoft.Isam.Esent.Interop.Windows7.Windows7Param
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.isam.esent.interop.windows7.windows7param_members(v=EXCHG.10)
ms:contentKeyID: 55104286
ms.date: 07/30/2014
mtps_version: v=EXCHG.10
---

# Windows7Param members

Include protected members  
Include inherited members  

System parameters that have been added to the Windows 7 version of ESENT.

The [Windows7Param](dn335429\(v=exchg.10\).md) type exposes the following members.

## Fields

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335314(v=exchg.10).md">DbScanIntervalMaxSec</a></td>
<td>Maximum interval to allow the database scan to finish, in seconds.</td>
</tr>
<tr class="even">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335431(v=exchg.10).md">DbScanIntervalMinSec</a></td>
<td>Minimum interval to repeat the database scan, in seconds.</td>
</tr>
<tr class="odd">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335316(v=exchg.10).md">DbScanThrottle</a></td>
<td>Throttling of the database scan, in milliseconds.</td>
</tr>
<tr class="even">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335434(v=exchg.10).md">EnableDbScanInRecovery</a></td>
<td>Enable Database Maintenance during recovery.</td>
</tr>
<tr class="odd">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335318(v=exchg.10).md">LVChunkSizeMost</a></td>
<td>This parameter is used to retrieve the chunk size of long-value (blob) data. Setting and retrieving data in multiples of this size increases efficiency.</td>
</tr>
<tr class="even">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335433(v=exchg.10).md">MaxCoalesceReadGapSize</a></td>
<td>Maximum number of bytes that can be gapped for a coalesced read IO operation.</td>
</tr>
<tr class="odd">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335435(v=exchg.10).md">MaxCoalesceReadSize</a></td>
<td>Maximum number of bytes that can be grouped for a coalesced read operation.</td>
</tr>
<tr class="even">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335322(v=exchg.10).md">MaxCoalesceWriteGapSize</a></td>
<td>Maximum number of bytes that can be gapped for a coalesced write IO operation.</td>
</tr>
<tr class="odd">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335437(v=exchg.10).md">MaxCoalesceWriteSize</a></td>
<td>Maximum number of bytes that can be grouped for a coalesced write operation.</td>
</tr>
<tr class="even">
<td><img src="images/Hh596466.pubfield(EXCHG.10).gif" title="Public field" alt="Public field" /><img src="images/Dn292146.static(EXCHG.10).gif" title="Static member" alt="Static member" /></td>
<td><a href="dn335438(v=exchg.10).md">WaypointLatency</a></td>
<td>This parameter sets the number of logs that esent will defer database flushes for. This can be used to increase database recoverability if failures cause logfiles to be lost.</td>
</tr>
</tbody>
</table>


Top

## See also

#### Reference

[Windows7Param class](dn335429\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop.Windows7 namespace](hh577573\(v=exchg.10\).md)
