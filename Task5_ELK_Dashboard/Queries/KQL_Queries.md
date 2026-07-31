# Kibana Queries Used

## Credential Stuffing

```kql
status:"failed"
```

---

## DNS Events

```kql
event_type:"dns"
```

---

## PowerShell Events

```kql
powershell_command:*
```

---

## All Attack Logs

```kql
*
```

---

## Specific Source IP

```kql
source_ip:"192.168.1.10"
```

---

## Failed Logins by Username

```kql
username:"admin" AND status:"failed"
```