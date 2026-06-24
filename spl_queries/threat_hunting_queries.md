# Threat Hunting Queries

## Successful Logins

```spl
index=main EventCode=4624
```

## Failed Logins

```spl
index=main EventCode=4625
```

## User Creation

```spl
index=main EventCode=4720
```

## User Deletion

```spl
index=main EventCode=4726
```

## Admin Group Addition

```spl
index=main EventCode=4732
```

## Service Creation

```spl
index=main EventCode=7045
```
