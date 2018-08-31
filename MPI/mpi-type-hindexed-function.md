﻿---
title: MPI_Type_hindexed function
TOCTitle: MPI_Type_hindexed function
ms:assetid: d3fcd851-924b-4148-aedb-9b2829cdd569
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/Dn520574(v=VS.85)
ms:contentKeyID: 59361045
ms.date: 03/28/2018
mtps_version: v=VS.85
f1_keywords:
- MPI_TYPE_HINDEXED
- mpif/MPI_Type_hindexed
- mpi/MPI_TYPE_HINDEXED
dev_langs:
- C++
- C
---

# MPI\_Type\_hindexed function

This function is deprecated in MPI-2 and removed from MPI-3. It is replaced by the [**MPI\_Type\_create\_hindexed**](mpi-type-create-hindexed-function.md) function.

## Syntax

``` c++
int
MPIAPI MPI_Type_hindexed(
        int          count,
        _In_count_   oldtype,
  _Out_ MPI_Datatype *newtype
);
```

## Parameters

  - *count*  
    TBD

  - *oldtype*  
    TBD

  - *newtype* \[out\]  
    TBD

## Return value

TBD

## Fortran

    MPI_TYPE_HINDEXED(COUNT, ARRAY_OF_BLOCKLENGTHS, ARRAY_OF_DISPLACEMENTS, OLDTYPE, NEWTYPE, IERROR)
        COUNT, ARRAY_OF_BLOCKLENGTHS, ARRAY_OF_DISPLACEMENTS, OLDTYPE, NEWTYPE, IERROR

## Requirements

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Product</p></td>
<td><p>HPC Pack 2012 MS-MPI Redistributable Package, HPC Pack 2008 R2 MS-MPI Redistributable Package, HPC Pack 2008 MS-MPI Redistributable Package or HPC Pack 2008 Client Utilities</p></td>
</tr>
<tr class="even">
<td><p>Header</p></td>
<td>Mpi.h;
Mpif.h</td>
</tr>
<tr class="odd">
<td><p>Library</p></td>
<td>Msmpi.lib</td>
</tr>
<tr class="even">
<td><p>DLL</p></td>
<td>Msmpi.dll</td>
</tr>
</tbody>
</table>


## See also

[MPI Miscellaneous Functions](mpi-miscellaneous-functions.md)

[**MPI\_Type\_create\_hindexed**](mpi-type-create-hindexed-function.md)
