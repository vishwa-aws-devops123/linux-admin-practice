# Log Analysis

## View Log File

```bash
cat logfile.log
```

## View Last Lines of Log

```bash
tail logfile.log
```

## Monitor Logs in Real Time

```bash
tail -f logfile.log
```

## Search Text in Logs

```bash
grep "ERROR" logfile.log
```

## Search Case Insensitive

```bash
grep -i "error" logfile.log
```

## View Large Logs Page by Page

```bash
less logfile.log
```

## Common Troubleshooting Approach

1. Identify affected service
2. Locate relevant logs
3. Search for errors and warnings
4. Correlate timestamps
5. Collect evidence for root cause analysis
