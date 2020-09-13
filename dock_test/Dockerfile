FROM polinux/snmpd
ENTRYPOINT [ "snmptrap", " -v2c -c public testing_snmptrapd:162 '' SNMPv2-MIB::coldStart.0 SNMPv2-MIB::sysContact.0 s 'yep22'" ]

