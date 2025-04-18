# NetScaler Console Agent SNMP OID Reference

## MIB-II OIDs

### system(1.3.6.1.2.1.1)

- (1.3.6.1.2.1.1)
- sysDescr (1.3.6.1.2.1.1.1)
- sysObjectID (1.3.6.1.2.1.1.2)
- sysUpTime (1.3.6.1.2.1.1.3)
- sysContact (1.3.6.1.2.1.1.4)
- sysName (1.3.6.1.2.1.1.5)
- sysLocation (1.3.6.1.2.1.1.6)
- sysServices (1.3.6.1.2.1.1.7)

### ifTable(1.3.6.1.2.1.2.2)

- (1.3.6.1.2.1.2.2)
- ifIndex (1.3.6.1.2.1.2.2.1.1)
- ifDescr (1.3.6.1.2.1.2.2.1.2)
- ifType (1.3.6.1.2.1.2.2.1.3)
- ifMtu (1.3.6.1.2.1.2.2.1.4)
- ifSpeed (1.3.6.1.2.1.2.2.1.5)
- ifPhysAddress (1.3.6.1.2.1.2.2.1.6)
- ifAdminStatus (1.3.6.1.2.1.2.2.1.7)
- ifOperStatus (1.3.6.1.2.1.2.2.1.8)
- ifLastChange (1.3.6.1.2.1.2.2.1.9)
- ifInOctets (1.3.6.1.2.1.2.2.1.10)
- ifInUcastPkts (1.3.6.1.2.1.2.2.1.11)
- ifInNUcastPkts (1.3.6.1.2.1.2.2.1.12)
- ifInDiscards (1.3.6.1.2.1.2.2.1.13)
- ifInErrors (1.3.6.1.2.1.2.2.1.14)
- ifInUnknownProtos (1.3.6.1.2.1.2.2.1.15)
- ifOutOctets (1.3.6.1.2.1.2.2.1.16)
- ifOutUcastPkts (1.3.6.1.2.1.2.2.1.17)
- ifOutNUcastPkts (1.3.6.1.2.1.2.2.1.18)
- ifOutDiscards (1.3.6.1.2.1.2.2.1.19)
- ifOutErrors (1.3.6.1.2.1.2.2.1.20)
- ifOutQLen (1.3.6.1.2.1.2.2.1.21)
- ifSpecific (1.3.6.1.2.1.2.2.1.22)

### icmp(1.3.6.1.2.1.5)

- (1.3.6.1.2.1.5)
- icmpInMsgs (1.3.6.1.2.1.5.1)
- icmpInErrors (1.3.6.1.2.1.5.2)
- icmpInDestUnreachs (1.3.6.1.2.1.5.3)
- icmpInTimeExcds (1.3.6.1.2.1.5.4)
- icmpInParmProbs (1.3.6.1.2.1.5.5)
- icmpInSrcQuenchs (1.3.6.1.2.1.5.6)
- icmpInRedirects (1.3.6.1.2.1.5.7)
- icmpInEchos (1.3.6.1.2.1.5.8)
- icmpInEchoReps (1.3.6.1.2.1.5.9)
- icmpInTimestamps (1.3.6.1.2.1.5.10)
- icmpInTimestampReps (1.3.6.1.2.1.5.11)
- icmpInAddrMasks (1.3.6.1.2.1.5.12)
- icmpInAddrMaskReps (1.3.6.1.2.1.5.13)
- icmpOutMsgs (1.3.6.1.2.1.5.14)
- icmpOutErrors (1.3.6.1.2.1.5.15)
- icmpOutDestUnreachs (1.3.6.1.2.1.5.16)
- icmpOutTimeExcds (1.3.6.1.2.1.5.17)
- icmpOutParmProbs (1.3.6.1.2.1.5.18)
- icmpOutSrcQuenchs (1.3.6.1.2.1.5.19)
- icmpOutRedirects (1.3.6.1.2.1.5.20)
- icmpOutEchos (1.3.6.1.2.1.5.21)
- icmpOutEchoReps (1.3.6.1.2.1.5.22)
- icmpOutTimestamps (1.3.6.1.2.1.5.23)
- icmpOutTimestampReps (1.3.6.1.2.1.5.24)
- icmpOutAddrMasks (1.3.6.1.2.1.5.25)
- icmpOutAddrMaskReps (1.3.6.1.2.1.5.26)

### udp(1.3.6.1.2.1.7)

- (1.3.6.1.2.1.7)
- udpInDatagrams (1.3.6.1.2.1.7.1)
- udpNoPorts (1.3.6.1.2.1.7.2)
- udpInErrors (1.3.6.1.2.1.7.3)
- udpOutDatagrams (1.3.6.1.2.1.7.4)

### udpTable(1.3.6.1.2.1.7.5)

- (1.3.6.1.2.1.7.5)
- udpLocalAddress (1.3.6.1.2.1.7.5.1.1)
- udpLocalPort (1.3.6.1.2.1.7.5.1.2)

### snmp(1.3.6.1.2.1.11)

- (1.3.6.1.2.1.11)
- snmpInPkts (1.3.6.1.2.1.11.1)
- snmpInBadVersions (1.3.6.1.2.1.11.3)
- snmpInBadCommunityNames (1.3.6.1.2.1.11.4)
- snmpInBadCommunityUses (1.3.6.1.2.1.11.5)
- snmpInASNParseErrs (1.3.6.1.2.1.11.6)
- snmpEnableAuthenTraps (1.3.6.1.2.1.11.30)
- snmpSilentDrops (1.3.6.1.2.1.11.31)
- snmpProxyDrops (1.3.6.1.2.1.11.32)

### ifMIBObjects(1.3.6.1.2.1.31.1)

- (1.3.6.1.2.1.31.1)

### ifXTable(1.3.6.1.2.1.31.1.1)

- (1.3.6.1.2.1.31.1.1)
- ifNamed (1.3.6.1.2.1.31.1.1.1.1)
- ifInMulticastPkts (1.3.6.1.2.1.31.1.1.1.2)
- ifInBroadcastPkts (1.3.6.1.2.1.31.1.1.1.3)
- ifOutMulticastPkts (1.3.6.1.2.1.31.1.1.1.4)
- ifOutBroadcastPkts (1.3.6.1.2.1.31.1.1.1.5)
- ifHCInOctets (1.3.6.1.2.1.31.1.1.1.6)
- ifHCInUcastPkts (1.3.6.1.2.1.31.1.1.1.7)
- ifHCInMulticastPkts (1.3.6.1.2.1.31.1.1.1.8)
- ifHCInBroadcastPkts (1.3.6.1.2.1.31.1.1.1.9)
- ifHCOutOctets (1.3.6.1.2.1.31.1.1.1.10)
- ifHCOutUcastPkts (1.3.6.1.2.1.31.1.1.1.11)
- ifHCOutMulticastPkts (1.3.6.1.2.1.31.1.1.1.12)
- ifHCOutBroadcastPkts (1.3.6.1.2.1.31.1.1.1.13)
- ifLinkUpDownTrapEnable (1.3.6.1.2.1.31.1.1.1.14)
- ifHighSpeed (1.3.6.1.2.1.31.1.1.1.15)
- ifPromiscuousMode (1.3.6.1.2.1.31.1.1.1.16)
- ifConnectorPresent (1.3.6.1.2.1.31.1.1.1.17)
- ifAlias (1.3.6.1.2.1.31.1.1.1.18)
- ifCounterDiscontinuityTime (1.3.6.1.2.1.31.1.1.1.19)
- ifTableLastChange (1.3.6.1.2.1.31.1.5)

## NetScaler Agent OIDs


### masEventGroup(1.3.6.1.4.1.5951.7.1)

- masEventGroup(1.3.6.1.4.1.5951.7.1)

### systemGroup(1.3.6.1.4.1.5951.7.2)

- systemGroup(1.3.6.1.4.1.5951.7.2)
- systemPlatform(1.3.6.1.4.1.5951.7.2.1)
- systemProduct(1.3.6.1.4.1.5951.7.2.2)
- systemBuildNumber(1.3.6.1.4.1.5951.7.2.3)
- systemIPAddressType(1.3.6.1.4.1.5951.7.2.4)
- systemIPAddress(1.3.6.1.4.1.5951.7.2.5)
- systemNetmaskType(1.3.6.1.4.1.5951.7.2.6)
- systemNetmask(1.3.6.1.4.1.5951.7.2.7)
- systemGatewayType(1.3.6.1.4.1.5951.7.2.8)
- systemGateway(1.3.6.1.4.1.5951.7.2.9)
- systemDnsType(1.3.6.1.4.1.5951.7.2.10)
- systemDns(1.3.6.1.4.1.5951.7.2.11)
- systemSysId(1.3.6.1.4.1.5951.7.2.12)
- systemSerial(1.3.6.1.4.1.5951.7.2.13)
- systemUptime(1.3.6.1.4.1.5951.7.2.14)
- systemCurrentTime(1.3.6.1.4.1.5951.7.2.15)
- systemCustomID(1.3.6.1.4.1.5951.7.2.17)
- systemCpu_usage(1.3.6.1.4.1.5951.7.2.18)
- systemMemory_usage(1.3.6.1.4.1.5951.7.2.19)
- systemDisk_usage(1.3.6.1.4.1.5951.7.2.20)

### eventVarBindOids(1.3.6.1.4.1.5951.7.1.1)

- eventVarBindOids(1.3.6.1.4.1.5951.7.1.1)

## Generic Traps

- coldStart (1.3.6.1.6.3.1.1.5.1)

## Enterprise Specific Traps
