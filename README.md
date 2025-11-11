# Tugas-1-Jarkom_Nabilah-Anindya_006

### IP PREFIX = 10.46.0.0


## TOPOLOGI
![](assets/Topologi.png)

## Ringkasan Alokasi IP
| SUBNET | JUMLAH IP | NETMASK |
|:-----------------------------|:-----------:|:---------:|
| Bidang Guru & Tendik | 96 host | /25 |
| Bidang Kurikulum | 221 host | /24 |
| Bidang Sarana Prasarana | 46 host | /26 |
| Bidang Pengawas Sekolah (Branch) | 19 host | /27 |
| Server & Admin | 7 host | /28 |
| Sekretariat | 381 host | /23 |
| A1 | 2 host | /30 |
| A2 | 2 host | /30 |
| A3 | 2 host | /30 |
| A4 | 2 host | /30 |
| A5 | 2 host | /30 |
| A6 | 2 host | /30 |
| **TOTAL** | **782 host** | **/22** |


## VSLM
![](assets/vlsm%20sub.png)

![](assets/vlsm.png)


## Sekretariat
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.4.0 |
| Netmask | 255.255.254.0 |
| Broadcast Address | 10.46.5.255 |
| Available Host | 510 |
| Range IP Tersedia | 10.46.4.1 – 10.46.5.254 |

## Bidang Guru & Tendik
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.1.0 |
| Netmask | 255.255.255.128 |
| Broadcast Address | 10.46.1.127 |
| Available Host | 126 |
| Range IP Tersedia | 10.46.1.1 – 10.46.1.126 |

## Bidang Kurikulum
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.2.0 |
| Netmask | 255.255.255.0 |
| Broadcast Address | 10.46.2.255 |
| Available Host | 254 |
| Range IP Tersedia | 10.46.2.1 – 10.46.2.254 |

## Bidang Sarana Prasarana
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.0.128 |
| Netmask | 255.255.255.192 |
| Broadcast Address | 10.46.0.191 |
| Available Host | 62 |
| Range IP Tersedia | 10.46.0.129 – 10.46.0.190 |

## Bidang Pengawas Sekolah (Branch)
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.0.64 |
| Netmask | 255.255.255.224 |
| Broadcast Address | 10.46.0.95 |
| Available Host | 30 |
| Range IP Tersedia | 10.46.0.65 – 10.46.0.94 |

## Server & Admin
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.0.32 |
| Netmask | 255.255.255.240 |
| Broadcast Address | 10.46.0.47 |
| Available Host | 14 |
| Range IP Tersedia | 10.46.0.33 – 10.46.0.46 |

## A1
| Parameter | Nilai |
|---|---|
| NID | 10.46.0.0 |
| Netmask | 255.255.255.252 |
| Broadcast | 10.46.0.3 |
| Host Tersedia | 2 |
| Range IP | 10.46.0.1 – 10.46.0.2 |

## A2
| Parameter | Nilai |
|---|---|
| NID | 10.46.0.4 |
| Netmask | 255.255.255.252 |
| Broadcast | 10.46.0.7 |
| Host Tersedia | 2 |
| Range IP | 10.46.0.5 – 10.46.0.6 |

## A3
| Parameter | Nilai |
|---|---|
| NID | 10.46.0.8 |
| Netmask | 255.255.255.252 |
| Broadcast | 10.46.0.11 |
| Host Tersedia | 2 |
| Range IP | 10.46.0.9 – 10.46.0.10 |

## A4
| Parameter | Nilai |
|---|---|
| NID | 10.46.0.12 |
| Netmask | 255.255.255.252 |
| Broadcast | 10.46.0.15 |
| Host Tersedia | 2 |
| Range IP | 10.46.0.13 – 10.46.0.14 |

## A5
| Parameter | Nilai |
|---|---|
| NID | 10.46.0.16 |
| Netmask | 255.255.255.252 |
| Broadcast | 10.46.0.19 |
| Host Tersedia | 2 |
| Range IP | 10.46.0.17 – 10.46.0.18 |

## A6
| Parameter | Nilai |
|---|---|
| NID | 10.46.0.20 |
| Netmask | 255.255.255.252 |
| Broadcast | 10.46.0.23 |
| Host Tersedia | 2 |
| Range IP | 10.46.0.21 – 10.46.0.22 |


---

## CIDR

![](assets/cidr%20sub.png)

![](assets/cidr.png)


## Sekretariat
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.0.0 |
| Netmask | 255.255.254.0 |
| Broadcast Address | 10.46.1.255 |
| Available Host | 510 |
| Range IP Tersedia | 10.46.0.1 – 10.46.1.254 |

## Bidang Guru & Tendik
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.32.0 |
| Netmask | 255.255.255.128 |
| Broadcast Address | 10.46.32.127 |
| Available Host | 126 |
| Range IP Tersedia | 10.46.32.1 – 10.46.32.126 |

## Bidang Kurikulum
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.33.0 |
| Netmask | 255.255.255.0 |
| Broadcast Address | 10.46.33.255 |
| Available Host | 254 |
| Range IP Tersedia | 10.46.33.1 – 10.46.33.254 |

## Bidang Sarana Prasarana
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.36.0 |
| Netmask | 255.255.255.192 |
| Broadcast Address | 10.46.35.63 |
| Available Host | 62 |
| Range IP Tersedia | 10.46.35.1 – 10.46.35.62 |

## Bidang Pengawas Sekolah (Branch)
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.16.0 |
| Netmask | 255.255.255.224 |
| Broadcast Address | 10.46.16.31 |
| Available Host | 30 |
| Range IP Tersedia | 10.46.16.1 – 10.46.16.30 |

## Server & Admin
| Parameter | Nilai |
|---|---|
| Network ID (NID) | 10.46.4.0 |
| Netmask | 255.255.255.240 |
| Broadcast Address | 10.46.4.15 |
| Available Host | 14 |
| Range IP Tersedia | 10.46.4.1 – 10.46.4.14 |

## Subnet A-series (/30)
| Nama | NID | Broadcast | Range IP |
|---|---|---|---|
| A1 | 10.46.2.0 | 10.46.2.3 | 10.46.2.1 – 10.46.2.2 |
| A2 | 10.46.8.0 | 10.46.8.3 | 10.46.8.1 – 10.46.8.2 |
| A3 | 10.46.32.128 | 10.46.32.131 | 10.46.32.129 – 10.46.32.130 |
| A4 | 10.46.34.0 | 10.46.34.3 | 10.46.34.1 – 10.46.34.2 |
| A5 | 10.46.40.0 | 10.46.40.3 | 10.46.40.1 – 10.46.40.2 |
| A6 | 10.46.16.32 | 10.46.16.35 | 10.46.16.33 – 10.46.16.34 |

---
