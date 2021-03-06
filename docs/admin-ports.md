# Admin Ports

The following is a list of ports used by internal DC/OS services, and their corresponding systemd unit.

## All Roles

### TCP

 - 53: dcos-net (dns)
 - 61091: dcos-metrics
 - 61420: dcos-net (epmd)
 - 62080: dcos-net (rest)
 - 62501: dcos-net (disterl)

### UDP

 - 53: dcos-net (dns)

## Master

### TCP

 - 80: dcos-adminrouter
 - 443: dcos-adminrouter
 - 1050: dcos-diagnostics
 - 1801: dcos-oauth
 - 2181: dcos-exhibitor
 - 2888: dcos-exhibitor
 - 3888: dcos-exhibitor
 - 5050: dcos-mesos-master
 - 7070: dcos-cosmos
 - 8080: dcos-marathon
 - 8123: dcos-mesos-dns
 - 8181: dcos-exhibitor
 - 9990: dcos-cosmos
 - 15055: dcos-history-service
 - 15101: dcos-marathon libprocess
 - 15201: dcos-metronome libprocess
 - 61053: dcos-mesos-dns

### UDP

 - 61053: dcos-mesos-dns

## Agent, Public Agent

### TCP

 - 5051: dcos-mesos-slave
 - 61001: dcos-adminrouter-agent
